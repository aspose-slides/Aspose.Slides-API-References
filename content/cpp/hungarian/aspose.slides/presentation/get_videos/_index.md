---
title: get_Videos()
second_title: Aspose.Slides C++ API referencia
description: Visszaadja a prezentációban beágyazott összes videófájl gyűjteményét. Csak olvasható IVideoCollection.
type: docs
weight: 235
url: /hu/aspose.slides/presentation/get_videos/
---
## Presentation::get_Videos() metódus

Visszaadja a prezentációban beágyazott összes videófájl gyűjteményét. Csak olvasható [IVideoCollection](../../ivideocollection/).

```cpp
System::SharedPtr<IVideoCollection> Aspose::Slides::Presentation::get_Videos() override
```

## Megjegyzések

Az alábbi példák bemutatják, hogyan hozhat létre beágyazott [Video](../../video/) keretet egy PowerPoint [Presentation](../)-ben.  
```cpp
// Példányosítja a PPTX-et képviselő Presentation osztályt
auto pres = System::MakeObject<Presentation>();

// Lekéri az első diát
auto slide = pres->get_Slides()->idx_get(0);

// Beágyazza a videót a prezentációba
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::MakeObject<System::IO::FileStream>(u"Wildlife.mp4", System::IO::FileMode::Open));

// Videokeret hozzáadása
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 350.0f, video);

// Videó beállítása a videokerethez
vf->set_EmbeddedVideo(video);
// Lejátszási mód és hangerő beállítása a videóhoz

vf->set_PlayMode(VideoPlayModePreset::Auto);
vf->set_Volume(AudioVolumeMode::Loud);

// A PPTX fájl írása a lemezre
pres->Save(u"VideoFrame_out.pptx", SaveFormat::Pptx);
```  
Az alábbi példák bemutatják, hogyan lehet videót hozzáadni, a videó fájl elérési útját közvetlenül az AddVideoFrame metódusba adva a PowerPoint [Presentation](../)-hez.  
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 150.0f, u"video1.avi");
```  
Az alábbi példák bemutatják, hogyan lehet nagy fájlt BLOB-on keresztül egy [Presentation](../)-hez hozzáadni.  
```cpp
const System::String pathToVeryLargeVideo = u"veryLargeVideo.avi";
// Létrehozza az új prezentációt, amelyhez a videót hozzáadjuk
auto pres = System::MakeObject<Presentation>();

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToVeryLargeVideo, System::IO::FileMode::Open);

// Adjunk hozzá egy videót a prezentációhoz - a KeepLocked viselkedést választottuk, mert
// nem szándékozunk hozzáférni a "veryLargeVideo.avi" fájlhoz.
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(fileStream, LoadingStreamBehavior::KeepLocked);
pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 480.0f, 270.0f, video);

// Elmenti a prezentációt. Míg egy nagy prezentáció kerül kiírásra, a memóriahasználat
// alacsony marad a prez objektum életciklusa során
pres->Save(u"presentationWithLargeVideo.pptx", Export::SaveFormat::Pptx);
```  
Az alábbi példák bemutatják, hogyan lehet nagy fájlt BLOB-on keresztül exportálni a PowerPoint [Presentation](../)-ból.  
```cpp
const System::String hugePresentationWithAudiosAndVideosFile = u"Large  Video File Test1.pptx";
auto loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_BlobManagementOptions(System::MakeObject<BlobManagementOptions>());
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);

// Létrehozza a Presentation példányt, és zárolja a "hugePresentationWithAudiosAndVideos.pptx" fájlt.
auto pres = System::MakeObject<Presentation>(hugePresentationWithAudiosAndVideosFile, loadOptions);

// Mentsük el az egyes videókat fájlba. A magas memóriahasználat elkerülése érdekében szükségünk van egy puffert, amelyet
// a prezentáció videófolyamából egy újonnan létrehozott videófájl áramlathoz való adatátvitelhez.
System::ArrayPtr<uint8_t> buffer = System::MakeArray<uint8_t>(8 * 1024, 0);
// Végig iterál a videókon
for (int32_t index = 0; index < pres->get_Videos()->get_Count(); index++)
{
    System::SharedPtr<IVideo> video = pres->get_Videos()->idx_get(index);
    // Megnyitja a prezentáció videófolyamát. Kérjük, vegye figyelembe, hogy szándékosan elkerültük a
    // olyan tulajdonságok, mint a video.BinaryData elérését - mivel ez a property egy teljes videót tartalmazó
    // bájtok memóriába töltését okozza. A video.GetStream-et használjuk, amely egy Stream-et ad vissza - és NEM
    //  igényli, hogy a teljes videót betöltsük a memóriába.
    auto presVideoStream = video->GetStream();

    auto outputFileStream = System::IO::File::OpenWrite(System::String::Format(u"video{0}.avi", index));

    int32_t bytesRead;
    while ((bytesRead = presVideoStream->Read(buffer, 0, buffer->get_Length())) > 0)
    {
        outputFileStream->Write(buffer, 0, bytesRead);
    }
    // A memóriafogyasztás alacsony marad a videó vagy a prezentáció méretétől függetlenül,
}
// Szükség esetén ugyanazokat a lépéseket alkalmazhatja audio fájlokra is.
```  
Az alábbi példák bemutatják, hogyan lehet hiperhivatkozást hozzáadni egy videóhoz egy PowerPoint [Presentation](../)-ban.  
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::IO::File::ReadAllBytes(u"video.avi"));
System::SharedPtr<IVideoFrame> videoFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 100.0f, 100.0f, video);
videoFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
videoFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```  
Az alábbi példák bemutatják, hogyan lehet [Video](../../video/) keretet létrehozni [Video](../../video/)-vel a webes forrásból egy PowerPoint [Presentation](../)-ban.  
```cpp
void Run()
{
    auto pres = System::MakeObject<Presentation>();

    AddVideoFromYouTube(pres, u"Tj75Arhq5ho");
    pres->Save(u"AddVideoFrameFromWebSource_out.pptx", SaveFormat::Pptx);
}

void AddVideoFromYouTube(System::SharedPtr<Presentation> pres, System::String videoId)
{
    // Videókeret hozzáadása
    auto slide = pres->get_Slides()->idx_get(0);
    System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 427.0f, 240.0f, System::String(u"https://www.youtube.com/embed/") + videoId);
    videoFrame->set_PlayMode(VideoPlayModePreset::Auto);

    // Bélyegkép betöltése
    auto client = System::MakeObject<System::Net::WebClient>();
    System::String thumbnailUri = System::String(u"http://img.youtube.com/vi/") + videoId + u"/hqdefault.jpg";
    videoFrame->get_PictureFormat()->get_Picture()->set_Image(pres->get_Images()->AddImage(client->DownloadData(thumbnailUri)));
}
```  
Az alábbi példák bemutatják, hogyan lehet [Video](../../video/)-t kinyerni a PowerPoint [Presentation](../) diájából.  
```cpp
// Létrehozza a Presentation objektumot, amely egy bemutató fájlt képvisel
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

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IVideoCollection](../../ivideocollection/)
* Osztály [Presentation](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)