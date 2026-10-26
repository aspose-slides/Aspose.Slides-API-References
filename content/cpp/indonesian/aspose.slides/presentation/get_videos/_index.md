---
title: get_Videos()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan koleksi semua file video tertanam dalam presentasi. Hanya-baca IVideoCollection.
type: docs
weight: 235
url: /id/aspose.slides/presentation/get_videos/
---
## Presentation::get_Videos() metode

Mengembalikan koleksi semua file video yang disematkan dalam presentasi. Hanya-baca [IVideoCollection](../../ivideocollection/).

```cpp
System::SharedPtr<IVideoCollection> Aspose::Slides::Presentation::get_Videos() override
```

## Catatan

```cpp
// Instansiasi kelas Presentation yang mewakili PPTX
auto pres = System::MakeObject<Presentation>();

// Dapatkan slide pertama
auto slide = pres->get_Slides()->idx_get(0);

// Sematkan video ke dalam presentasi
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::MakeObject<System::IO::FileStream>(u"Wildlife.mp4", System::IO::FileMode::Open));

// Tambahkan Video Frame
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 350.0f, video);

// Setel video ke Video Frame
vf->set_EmbeddedVideo(video);
// Setel Mode Putar dan Volume Video

vf->set_PlayMode(VideoPlayModePreset::Auto);
vf->set_Volume(AudioVolumeMode::Loud);

// Tuliskan file PPTX ke disk
pres->Save(u"VideoFrame_out.pptx", SaveFormat::Pptx);
```
 Contoh berikut menunjukkan cara membuat [Video](../../video/) Frame yang disematkan di PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 150.0f, u"video1.avi");
```
 Contoh berikut menunjukkan cara menambahkan video dengan memberikan path ke file video langsung ke metode AddVideoFrame untuk PowerPoint [Presentation](../). 
```cpp
const System::String pathToVeryLargeVideo = u"veryLargeVideo.avi";
// Membuat presentasi baru yang akan ditambahkan video
auto pres = System::MakeObject<Presentation>();

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToVeryLargeVideo, System::IO::FileMode::Open);

// Mari tambahkan video ke presentasi - kami memilih perilaku KeepLocked karena kami
// tidak bermaksud mengakses file "veryLargeVideo.avi" file.
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(fileStream, LoadingStreamBehavior::KeepLocked);
pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 480.0f, 270.0f, video);

// Menyimpan presentasi. Saat presentasi besar dihasilkan, konsumsi memori
// tetap rendah sepanjang siklus hidup objek pres
pres->Save(u"presentationWithLargeVideo.pptx", Export::SaveFormat::Pptx);
```
 Contoh berikut menunjukkan cara menambahkan file besar melalui BLOB ke [Presentation](../). 
```cpp
const System::String hugePresentationWithAudiosAndVideosFile = u"Large  Video File Test1.pptx";
auto loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_BlobManagementOptions(System::MakeObject<BlobManagementOptions>());
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);

// Membuat instance Presentation, mengunci file "hugePresentationWithAudiosAndVideos.pptx".
auto pres = System::MakeObject<Presentation>(hugePresentationWithAudiosAndVideosFile, loadOptions);

// Mari simpan setiap video ke file. Untuk mencegah penggunaan memori yang tinggi, kita memerlukan buffer yang akan digunakan
// untuk mentransfer data dari aliran video presentasi ke aliran untuk file video yang baru dibuat.
System::ArrayPtr<uint8_t> buffer = System::MakeArray<uint8_t>(8 * 1024, 0);
// Mengiterasi video-video
for (int32_t index = 0; index < pres->get_Videos()->get_Count(); index++)
{
    System::SharedPtr<IVideo> video = pres->get_Videos()->idx_get(index);
    // Membuka aliran video presentasi. Harap perhatikan bahwa kami sengaja menghindari mengakses properti
    // seperti video.BinaryData - karena properti ini mengembalikan array byte yang berisi video lengkap, yang kemudian
    // menyebabkan byte-byte dimuat ke memori. Kami menggunakan video.GetStream, yang akan mengembalikan Stream - dan TIDAK
    //  memerlukan kami memuat seluruh video ke memori.
    auto presVideoStream = video->GetStream();

    auto outputFileStream = System::IO::File::OpenWrite(System::String::Format(u"video{0}.avi", index));

    int32_t bytesRead;
    while ((bytesRead = presVideoStream->Read(buffer, 0, buffer->get_Length())) > 0)
    {
        outputFileStream->Write(buffer, 0, bytesRead);
    }
    // Konsumsi memori akan tetap rendah terlepas dari ukuran video atau presentasi,
}
// Jika diperlukan, Anda dapat menerapkan langkah yang sama untuk file audio.
```
 Contoh berikut menunjukkan cara mengekspor file besar melalui BLOB dari PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::IO::File::ReadAllBytes(u"video.avi"));
System::SharedPtr<IVideoFrame> videoFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 100.0f, 100.0f, video);
videoFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
videoFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```
 Contoh berikut menunjukkan cara menambahkan hyperlink ke video dalam PowerPoint [Presentation](../). 
```cpp
void Run()
{
    auto pres = System::MakeObject<Presentation>();

    AddVideoFromYouTube(pres, u"Tj75Arhq5ho");
    pres->Save(u"AddVideoFrameFromWebSource_out.pptx", SaveFormat::Pptx);
}

void AddVideoFromYouTube(System::SharedPtr<Presentation> pres, System::String videoId)
{
    // Tambahkan videoFrame
    auto slide = pres->get_Slides()->idx_get(0);
    System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 427.0f, 240.0f, System::String(u"https://www.youtube.com/embed/") + videoId);
    videoFrame->set_PlayMode(VideoPlayModePreset::Auto);

    // Muat thumbnail
    auto client = System::MakeObject<System::Net::WebClient>();
    System::String thumbnailUri = System::String(u"http://img.youtube.com/vi/") + videoId + u"/hqdefault.jpg";
    videoFrame->get_PictureFormat()->get_Picture()->set_Image(pres->get_Images()->AddImage(client->DownloadData(thumbnailUri)));
}
```
 Contoh berikut menunjukkan cara membuat [Video](../../video/) Frame dengan [Video](../../video/) dari Sumber Web di PowerPoint [Presentation](../). 
```cpp
// Buat objek Presentation yang mewakili file presentasi
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
 Contoh berikut menunjukkan cara mengekstrak [Video](../../video/) dari slide PowerPoint [Presentation](../). 

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IVideoCollection](../../ivideocollection/)
* Kelas [Presentation](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)