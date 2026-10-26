---
title: get_Videos()
second_title: Aspose.Slides için C++ API Referansı
description: Sunumda gömülü tüm video dosyalarının koleksiyonunu döndürür. Salt-okunur IVideoCollection.
type: docs
weight: 235
url: /tr/aspose.slides/presentation/get_videos/
---
## Presentation::get_Videos() metodu

Sunumda gömülü tüm video dosyalarının koleksiyonunu döndürür. Salt-okunur [IVideoCollection](../../ivideocollection/).

```cpp
System::SharedPtr<IVideoCollection> Aspose::Slides::Presentation::get_Videos() override
```

## Açıklamalar

Aşağıdaki örnekler, PowerPoint [Presentation](../) içinde gömülü [Video](../../video/) Frame oluşturmanın nasıl yapılacağını gösterir. 
```cpp
// PPTX'i temsil eden Presentation sınıfını örnekle
auto pres = System::MakeObject<Presentation>();

// İlk slaytı al
auto slide = pres->get_Slides()->idx_get(0);

// Videoyu sunuma göm
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::MakeObject<System::IO::FileStream>(u"Wildlife.mp4", System::IO::FileMode::Open));

// Video Çerçevesi Ekle
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 350.0f, video);

// Videoyu Video Çerçevesine ayarla
vf->set_EmbeddedVideo(video);
// Videonun Oynatma Modunu ve Ses Düzeyini ayarla
vf->set_PlayMode(VideoPlayModePreset::Auto);
vf->set_Volume(AudioVolumeMode::Loud);

// PPTX dosyasını diske yaz
pres->Save(u"VideoFrame_out.pptx", SaveFormat::Pptx);
```
Aşağıdaki örnekler, PowerPoint [Presentation](../) için AddVideoFrame metoduna video dosyasının yolunu doğrudan geçirerek bir video eklemenin nasıl yapılacağını gösterir. 
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 150.0f, u"video1.avi");
```
Aşağıdaki örnekler, BLOB aracılığıyla büyük bir dosyanın [Presentation](../)'a nasıl ekleneceğini gösterir. 
```cpp
const System::String pathToVeryLargeVideo = u"veryLargeVideo.avi";
// Videonun ekleneceği yeni bir sunum oluşturur
auto pres = System::MakeObject<Presentation>();

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToVeryLargeVideo, System::IO::FileMode::Open);

// Videoyu sunuma ekleyelim - KeepLocked davranışını seçtik çünkü
// "veryLargeVideo.avi" dosyasına erişmeyi amaçlamıyoruz.
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(fileStream, LoadingStreamBehavior::KeepLocked);
pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 480.0f, 270.0f, video);

// Sunumu kaydeder. Büyük bir sunum çıktı alınırken, bellek tüketimi
// pres nesnesinin yaşam döngüsü boyunca düşük kalır
pres->Save(u"presentationWithLargeVideo.pptx", Export::SaveFormat::Pptx);
```
Aşağıdaki örnekler, BLOB aracılığıyla büyük bir dosyanın PowerPoint [Presentation](../)'den nasıl dışa aktarılacağını gösterir. 
```cpp
const System::String hugePresentationWithAudiosAndVideosFile = u"Large  Video File Test1.pptx";
auto loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_BlobManagementOptions(System::MakeObject<BlobManagementOptions>());
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);

// Presentation örneği oluşturur ve "hugePresentationWithAudiosAndVideos.pptx" dosyasını kilitler.
auto pres = System::MakeObject<Presentation>(hugePresentationWithAudiosAndVideosFile, loadOptions);

// Her videoyu bir dosyaya kaydedelim. Yüksek bellek kullanımını önlemek için bir tampon (buffer) gereklidir ve bu tampon kullanılacak
// sunumun video akışından yeni oluşturulan video dosyası için bir akışa veriyi aktarmak amacıyla.
System::ArrayPtr<uint8_t> buffer = System::MakeArray<uint8_t>(8 * 1024, 0);
// Videoları dolaşır
for (int32_t index = 0; index < pres->get_Videos()->get_Count(); index++)
{
    System::SharedPtr<IVideo> video = pres->get_Videos()->idx_get(index);
    // Sunumun video akışını açar. Lütfen, özelliklere erişmekten kasıtlı olarak kaçındığımızı unutmayın
    // video.BinaryData gibi - çünkü bu özellik tam bir video içeren bir bayt dizisi döndürür, bu da
    // baytların belleğe yüklenmesine neden olur. video.GetStream'i kullanırız, bu bir Stream döndürür - ve
    //  bütün videoyu belleğe yüklememizi gerektirmez.
    auto presVideoStream = video->GetStream();

    auto outputFileStream = System::IO::File::OpenWrite(System::String::Format(u"video{0}.avi", index));

    int32_t bytesRead;
    while ((bytesRead = presVideoStream->Read(buffer, 0, buffer->get_Length())) > 0)
    {
        outputFileStream->Write(buffer, 0, bytesRead);
    }
    // Video veya sunumun boyutu ne olursa olsun, bellek tüketimi düşük kalacaktır,
}
 // Gerekirse, aynı adımları ses dosyaları için de uygulayabilirsiniz.
```
Aşağıdaki örnekler, PowerPoint [Presentation](../) içinde bir videoya hiperlink eklemenin nasıl yapılacağını gösterir. 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::IO::File::ReadAllBytes(u"video.avi"));
System::SharedPtr<IVideoFrame> videoFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 100.0f, 100.0f, video);
videoFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
videoFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```
Aşağıdaki örnekler, PowerPoint [Presentation](../) içinde Web Kaynağından [Video](../../video/) ile [Video](../../video/) Frame oluşturmanın nasıl yapılacağını gösterir. 
```cpp
void Run()
{
    auto pres = System::MakeObject<Presentation>();

    AddVideoFromYouTube(pres, u"Tj75Arhq5ho");
    pres->Save(u"AddVideoFrameFromWebSource_out.pptx", SaveFormat::Pptx);
}

void AddVideoFromYouTube(System::SharedPtr<Presentation> pres, System::String videoId)
{
    // videoFrame ekle
    auto slide = pres->get_Slides()->idx_get(0);
    System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 427.0f, 240.0f, System::String(u"https://www.youtube.com/embed/") + videoId);
    videoFrame->set_PlayMode(VideoPlayModePreset::Auto);

    // küçük resmi yükle
    auto client = System::MakeObject<System::Net::WebClient>();
    System::String thumbnailUri = System::String(u"http://img.youtube.com/vi/") + videoId + u"/hqdefault.jpg";
    videoFrame->get_PictureFormat()->get_Picture()->set_Image(pres->get_Images()->AddImage(client->DownloadData(thumbnailUri)));
}
```
Aşağıdaki örnekler, PowerPoint [Presentation](../) slaytından [Video](../../video/) çıkarmanın nasıl yapılacağını gösterir. 
```cpp
// Bir sunum dosyasını temsil eden Presentation nesnesi oluşturur
auto presentation = System::MakeObject<Presentation>(u"Video.pptx");

for (auto&& slide : presentation->get_Slides())
{
    for (auto&& shape : slide->get_Shapes())
    {
        if (System::ObjectExt::Is<VideoFrame>(shape))
        {
            System::SharedPtr<IVideoFrame> vf = System::AsCast<IVideoFrame>(shape);
            System::String type = vf->get_EmbeddedVideo()->get_ContentType();
            int32_t ss = type.LastIndexOf(u'/');
            type = type.Remove(0, type.LastIndexOf(u'/') + 1);
            System::ArrayPtr<uint8_t> buffer = vf->get_EmbeddedVideo()->get_BinaryData();
            auto stream = System::MakeObject<System::IO::FileStream>(System::String(u"NewVideo_out.") + type,
                                                                     System::IO::FileMode::Create,
                                                                     System::IO::FileAccess::Write,
                                                                     System::IO::FileShare::Read);
            stream->Write(buffer, 0, buffer->get_Length());
        }
    }
}
```

## İlgili Bölümler

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IVideoCollection](../../ivideocollection/)
* Class [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)