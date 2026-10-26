---
title: get_Videos()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar samlingen av alla inbäddade videofiler i presentationen. Skrivskyddad IVideoCollection.
type: docs
weight: 235
url: /sv/aspose.slides/presentation/get_videos/
---
## Presentation::get_Videos() metod


Returnerar samlingen av alla inbäddade videofiler i presentationen. Skrivskyddad [IVideoCollection](../../ivideocollection/).

```cpp
System::SharedPtr<IVideoCollection> Aspose::Slides::Presentation::get_Videos() override
```

## Anmärkningar


Följande exempel visar hur man skapar inbäddad [Video](../../video/) Frame i en PowerPoint [Presentation](../). 
```cpp
// Instansiera Presentation-klassen som representerar PPTX
auto pres = System::MakeObject<Presentation>();

// Hämta den första bilden
auto slide = pres->get_Slides()->idx_get(0);

// Bädda in video i presentationen
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::MakeObject<System::IO::FileStream>(u"Wildlife.mp4", System::IO::FileMode::Open));

// Lägg till videoruta
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 350.0f, video);

// Ställ in video på videorutan
vf->set_EmbeddedVideo(video);
// Ställ in uppspelningsläge och volym för videon

vf->set_PlayMode(VideoPlayModePreset::Auto);
vf->set_Volume(AudioVolumeMode::Loud);

// Skriv PPTX-filen till disk
pres->Save(u"VideoFrame_out.pptx", SaveFormat::Pptx);
```
Följande exempel visar hur man lägger till en video genom att skicka sökvägen till videofilen direkt till AddVideoFrame-metoden för PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 150.0f, u"video1.avi");
```
Följande exempel visar hur man lägger till en stor fil via BLOB till en [Presentation](../). 
```cpp
const System::String pathToVeryLargeVideo = u"veryLargeVideo.avi";
// Skapar en ny presentation som videon kommer att läggas till
auto pres = System::MakeObject<Presentation>();

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToVeryLargeVideo, System::IO::FileMode::Open);

// Låt oss lägga till videon i presentationen - vi valde KeepLocked-beteendet eftersom vi
// inte avser att komma åt filen "veryLargeVideo.avi".
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(fileStream, LoadingStreamBehavior::KeepLocked);
pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 480.0f, 270.0f, video);

// Sparar presentationen. Medan en stor presentation skrivs ut, förblir minnesförbrukningen
// låg under hela pres-objektets livscykel
pres->Save(u"presentationWithLargeVideo.pptx", Export::SaveFormat::Pptx);
```
Följande exempel visar hur man exporterar en stor fil via BLOB från PowerPoint [Presentation](../). 
```cpp
const System::String hugePresentationWithAudiosAndVideosFile = u"Large  Video File Test1.pptx";
auto loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_BlobManagementOptions(System::MakeObject<BlobManagementOptions>());
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);

// Skapar en Presentation-instans, låser filen "hugePresentationWithAudiosAndVideos.pptx" file.
auto pres = System::MakeObject<Presentation>(hugePresentationWithAudiosAndVideosFile, loadOptions);

// Låt oss spara varje video till en fil. För att förhindra hög minnesanvändning behöver vi en buffer som kommer att användas
// för att överföra data från presentationens videoström till en ström för en ny skapad videofil.
System::ArrayPtr<uint8_t> buffer = System::MakeArray<uint8_t>(8 * 1024, 0);
// Itererar igenom videorna
for (int32_t index = 0; index < pres->get_Videos()->get_Count(); index++)
{
    System::SharedPtr<IVideo> video = pres->get_Videos()->idx_get(index);
    // Öppnar presentationens videoström. Observera att vi medvetet undvek att komma åt egenskaper
    // som video.BinaryData - eftersom den här egenskapen returnerar en byte-array som innehåller hela videon, vilket då
    // får att bytes laddas in i minnet. Vi använder video.GetStream, som returnerar en Stream – och kräver INTE
    //  att vi laddar hela videon i minnet.
    auto presVideoStream = video->GetStream();

    auto outputFileStream = System::IO::File::OpenWrite(System::String::Format(u"video{0}.avi", index));

    int32_t bytesRead;
    while ((bytesRead = presVideoStream->Read(buffer, 0, buffer->get_Length())) > 0)
    {
        outputFileStream->Write(buffer, 0, bytesRead);
    }
    // Minnesanvändningen kommer att förbli låg oavsett storleken på videon eller presentationen,
}
// Vid behov kan du tillämpa samma steg för ljudfiler.
```
Följande exempel visar hur man lägger till en hyperlänk till en video i en PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::IO::File::ReadAllBytes(u"video.avi"));
System::SharedPtr<IVideoFrame> videoFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 100.0f, 100.0f, video);
videoFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
videoFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```
Följande exempel visar hur man skapar [Video](../../video/) Frame med [Video](../../video/) från webbkälla i en PowerPoint [Presentation](../). 
```cpp
void Run()
{
    auto pres = System::MakeObject<Presentation>();

    AddVideoFromYouTube(pres, u"Tj75Arhq5ho");
    pres->Save(u"AddVideoFrameFromWebSource_out.pptx", SaveFormat::Pptx);
}

void AddVideoFromYouTube(System::SharedPtr<Presentation> pres, System::String videoId)
{
    // Lägg till videoruta
    auto slide = pres->get_Slides()->idx_get(0);
    System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 427.0f, 240.0f, System::String(u"https://www.youtube.com/embed/") + videoId);
    videoFrame->set_PlayMode(VideoPlayModePreset::Auto);

    // Läs in miniatyrbild
    auto client = System::MakeObject<System::Net::WebClient>();
    System::String thumbnailUri = System::String(u"http://img.youtube.com/vi/") + videoId + u"/hqdefault.jpg";
    videoFrame->get_PictureFormat()->get_Picture()->set_Image(pres->get_Images()->AddImage(client->DownloadData(thumbnailUri)));
}
```
Följande exempel visar hur man extraherar [Video](../../video/) från en bild i PowerPoint [Presentation](../). 
```cpp
// Instansiera ett Presentation-objekt som representerar en presentationsfil
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

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IVideoCollection](../../ivideocollection/)
* Klass [Presentation](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)