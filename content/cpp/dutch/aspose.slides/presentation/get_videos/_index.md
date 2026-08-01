---
title: get_Videos()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de collectie van alle ingesloten videobestanden in de presentatie. Alleen-lezen IVideoCollection.
type: docs
weight: 235
url: /nl/aspose.slides/presentation/get_videos/
---
## Presentation::get_Videos() methode


Retourneert de verzameling van alle ingesloten videobestanden in de presentatie. Alleen-lezen [IVideoCollection](../../ivideocollection/).

```cpp
System::SharedPtr<IVideoCollection> Aspose::Slides::Presentation::get_Videos() override
```

## Opmerkingen


Het volgende voorbeeld laat zien hoe je een ingesloten [Video](../../video/) Frame maakt in een PowerPoint [Presentation](../). 
```cpp
// Instantieer Presentation-klasse die de PPTX voorstelt
auto pres = System::MakeObject<Presentation>();

// Haal de eerste dia op
auto slide = pres->get_Slides()->idx_get(0);

// Voeg video in in de presentatie
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::MakeObject<System::IO::FileStream>(u"Wildlife.mp4", System::IO::FileMode::Open));

// Voeg videoframe toe
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 350.0f, video);

// Stel video in op videoframe
vf->set_EmbeddedVideo(video);
// Stel afspeelmodus en volume van de video in

vf->set_PlayMode(VideoPlayModePreset::Auto);
vf->set_Volume(AudioVolumeMode::Loud);

// Schrijf het PPTX-bestand naar schijf
pres->Save(u"VideoFrame_out.pptx", SaveFormat::Pptx);
```
 Het volgende voorbeeld laat zien hoe je een video toevoegt door het pad naar het videobestand direct door te geven aan de AddVideoFrame-methode voor PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 150.0f, u"video1.avi");
```
 Het volgende voorbeeld laat zien hoe je een groot bestand via BLOB toevoegt aan een [Presentation](../). 
```cpp
const System::String pathToVeryLargeVideo = u"veryLargeVideo.avi";
// Maakt een nieuwe presentatie waaraan de video zal worden toegevoegd
auto pres = System::MakeObject<Presentation>();

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToVeryLargeVideo, System::IO::FileMode::Open);

// Laten we de video aan de presentatie toevoegen - we kozen het KeepLocked-gedrag omdat we
// niet van plan zijn het bestand "veryLargeVideo.avi" te benaderen.
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(fileStream, LoadingStreamBehavior::KeepLocked);
pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 480.0f, 270.0f, video);

// Slaat de presentatie op. Terwijl een grote presentatie wordt uitgegeven, blijft het geheugenverbruik
// laag gedurende de levensduur van het pres-object
pres->Save(u"presentationWithLargeVideo.pptx", Export::SaveFormat::Pptx);
```
 Het volgende voorbeeld laat zien hoe je een groot bestand via BLOB exporteert vanuit PowerPoint [Presentation](../). 
```cpp
const System::String hugePresentationWithAudiosAndVideosFile = u"Large  Video File Test1.pptx";
auto loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_BlobManagementOptions(System::MakeObject<BlobManagementOptions>());
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);

// Maakt een instantie van Presentation, vergrendelt het bestand "hugePresentationWithAudiosAndVideos.pptx" file.
auto pres = System::MakeObject<Presentation>(hugePresentationWithAudiosAndVideosFile, loadOptions);

// Laten we elke video opslaan naar een bestand. Om hoog geheugengebruik te voorkomen, hebben we een buffer nodig die zal worden gebruikt
// om de gegevens van de videostream van de presentatie over te dragen naar een stream voor een nieuw aangemaakt video-bestand.
System::ArrayPtr<uint8_t> buffer = System::MakeArray<uint8_t>(8 * 1024, 0);
// Itereert door de video's
for (int32_t index = 0; index < pres->get_Videos()->get_Count(); index++)
{
    System::SharedPtr<IVideo> video = pres->get_Videos()->idx_get(index);
    // Opent de videostream van de presentatie. Let op, we hebben opzettelijk vermeden eigenschappen te benaderen
    // zoals video.BinaryData - omdat deze eigenschap een byte-array teruggeeft die een volledige video bevat, wat vervolgens
    // bytes in het geheugen laadt. We gebruiken video.GetStream, die een Stream teruggeeft - en het LAADT niet
    //  vereist dat we de volledige video in het geheugen laden.
    auto presVideoStream = video->GetStream();

    auto outputFileStream = System::IO::File::OpenWrite(System::String::Format(u"video{0}.avi", index));

    int32_t bytesRead;
    while ((bytesRead = presVideoStream->Read(buffer, 0, buffer->get_Length())) > 0)
    {
        outputFileStream->Write(buffer, 0, bytesRead);
    }
    // Geheugengebruik blijft laag ongeacht de grootte van de video of presentatie,
}
// Indien nodig kun je dezelfde stappen toepassen voor audiobestanden.
```
 Het volgende voorbeeld laat zien hoe je een hyperlink toevoegt aan een video in een PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::IO::File::ReadAllBytes(u"video.avi"));
System::SharedPtr<IVideoFrame> videoFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 100.0f, 100.0f, video);
videoFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
videoFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```
 Het volgende voorbeeld laat zien hoe je een [Video](../../video/) Frame maakt met [Video](../../video/) van een webbron in een PowerPoint [Presentation](../). 
```cpp
void Run()
{
    auto pres = System::MakeObject<Presentation>();

    AddVideoFromYouTube(pres, u"Tj75Arhq5ho");
    pres->Save(u"AddVideoFrameFromWebSource_out.pptx", SaveFormat::Pptx);
}

void AddVideoFromYouTube(System::SharedPtr<Presentation> pres, System::String videoId)
{
    // Voeg videoFrame toe
    auto slide = pres->get_Slides()->idx_get(0);
    System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 427.0f, 240.0f, System::String(u"https://www.youtube.com/embed/") + videoId);
    videoFrame->set_PlayMode(VideoPlayModePreset::Auto);

    // Laad miniatuur
    auto client = System::MakeObject<System::Net::WebClient>();
    System::String thumbnailUri = System::String(u"http://img.youtube.com/vi/") + videoId + u"/hqdefault.jpg";
    videoFrame->get_PictureFormat()->get_Picture()->set_Image(pres->get_Images()->AddImage(client->DownloadData(thumbnailUri)));
}
```
 Het volgende voorbeeld laat zien hoe je [Video](../../video/) extraheert uit een dia van PowerPoint [Presentation](../). 
```cpp
// Instantieer een Presentation-object dat een presentatiebestand vertegenwoordigt
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

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IVideoCollection](../../ivideocollection/)
* Klasse [Presentation](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)