---
title: get_Videos()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací kolekci všech vložených video souborů v prezentaci. Pouze pro čtení IVideoCollection.
type: docs
weight: 235
url: /cs/aspose.slides/presentation/get_videos/
---
## Presentation::get_Videos() metoda

Vrací kolekci všech vložených video souborů v prezentaci. Pouze pro čtení [IVideoCollection](../../ivideocollection/).

```cpp
System::SharedPtr<IVideoCollection> Aspose::Slides::Presentation::get_Videos() override
```

## Poznámky

 Následující příklady ukazují, jak vytvořit vložený [Video](../../video/) Frame v PowerPoint [Presentation](../). 
```cpp
// Vytvořte instanci třídy Presentation, která představuje PPTX
auto pres = System::MakeObject<Presentation>();

// Získat první snímek
auto slide = pres->get_Slides()->idx_get(0);

// Vložit video do prezentace
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::MakeObject<System::IO::FileStream>(u"Wildlife.mp4", System::IO::FileMode::Open));

// Přidat video rámeček
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 350.0f, video);

// Nastavit video do video rámečku
vf->set_EmbeddedVideo(video);
// Nastavit režim přehrávání a hlasitost videa

vf->set_PlayMode(VideoPlayModePreset::Auto);
vf->set_Volume(AudioVolumeMode::Loud);

// Zapsat soubor PPTX na disk
pres->Save(u"VideoFrame_out.pptx", SaveFormat::Pptx);
```
 Následující příklady ukazují, jak přidat video předáním cesty k video souboru přímo do metody AddVideoFrame pro PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 150.0f, u"video1.avi");
```
 Následující příklady ukazují, jak přidat velký soubor pomocí BLOB do [Presentation](../). 
```cpp
const System::String pathToVeryLargeVideo = u"veryLargeVideo.avi";
// Vytvoří novou prezentaci, do které bude video přidáno
auto pres = System::MakeObject<Presentation>();

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToVeryLargeVideo, System::IO::FileMode::Open);

// Přidáme video do prezentace - zvolili jsme chování KeepLocked, protože
// neplánujeme přistupovat k souboru "veryLargeVideo.avi" file.
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(fileStream, LoadingStreamBehavior::KeepLocked);
pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 480.0f, 270.0f, video);

// Ukládá prezentaci. I když je výstupem velká prezentace, spotřeba paměti
// zůstává nízká po celou dobu životnosti objektu pres
pres->Save(u"presentationWithLargeVideo.pptx", Export::SaveFormat::Pptx);
```
 Následující příklady ukazují, jak exportovat velký soubor pomocí BLOB z PowerPoint [Presentation](../). 
```cpp
const System::String hugePresentationWithAudiosAndVideosFile = u"Large  Video File Test1.pptx";
auto loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_BlobManagementOptions(System::MakeObject<BlobManagementOptions>());
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);

// Vytvoří instanci třídy Presentation a zamkne soubor "hugePresentationWithAudiosAndVideos.pptx" file.
auto pres = System::MakeObject<Presentation>(hugePresentationWithAudiosAndVideosFile, loadOptions);

// Uložíme každé video do souboru. Pro zamezení vysoké spotřeby paměti potřebujeme buffer, který bude použit
// k přenosu dat z video proudu prezentace do proudu pro nově vytvořený video soubor.
System::ArrayPtr<uint8_t> buffer = System::MakeArray<uint8_t>(8 * 1024, 0);
// Prochází videa
for (int32_t index = 0; index < pres->get_Videos()->get_Count(); index++)
{
    System::SharedPtr<IVideo> video = pres->get_Videos()->idx_get(index);
    // Otevírá video proud prezentace. Všimněte si, že jsme úmyslně vyhnuli se přístupu k vlastnostem
    // jako video.BinaryData - protože tato vlastnost vrací pole bytů obsahující celé video, což pak
    // způsobí načtení bajtů do paměti. Používáme video.GetStream, který vrátí Stream - a NENÍ
    //  vyžadovat načíst celé video do paměti.
    auto presVideoStream = video->GetStream();

    auto outputFileStream = System::IO::File::OpenWrite(System::String::Format(u"video{0}.avi", index));

    int32_t bytesRead;
    while ((bytesRead = presVideoStream->Read(buffer, 0, buffer->get_Length())) > 0)
    {
        outputFileStream->Write(buffer, 0, bytesRead);
    }
    // Spotřeba paměti zůstane nízká bez ohledu na velikost videa nebo prezentace,
}
// V případě potřeby můžete použít stejný postup pro audio soubory.
```
 Následující příklady ukazují, jak přidat hypertextový odkaz na video v PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::IO::File::ReadAllBytes(u"video.avi"));
System::SharedPtr<IVideoFrame> videoFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 100.0f, 100.0f, video);
videoFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
videoFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```
 Následující příklady ukazují, jak vytvořit [Video](../../video/) Frame s [Video](../../video/) z Web Source v PowerPoint [Presentation](../). 
```cpp
void Run()
{
    auto pres = System::MakeObject<Presentation>();

    AddVideoFromYouTube(pres, u"Tj75Arhq5ho");
    pres->Save(u"AddVideoFrameFromWebSource_out.pptx", SaveFormat::Pptx);
}

void AddVideoFromYouTube(System::SharedPtr<Presentation> pres, System::String videoId)
{
    // Přidejte video rámec
    auto slide = pres->get_Slides()->idx_get(0);
    System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 427.0f, 240.0f, System::String(u"https://www.youtube.com/embed/") + videoId);
    videoFrame->set_PlayMode(VideoPlayModePreset::Auto);

    // Načíst náhled
    auto client = System::MakeObject<System::Net::WebClient>();
    System::String thumbnailUri = System::String(u"http://img.youtube.com/vi/") + videoId + u"/hqdefault.jpg";
    videoFrame->get_PictureFormat()->get_Picture()->set_Image(pres->get_Images()->AddImage(client->DownloadData(thumbnailUri)));
}
```
 Následující příklady ukazují, jak extrahovat [Video](../../video/) ze snímku PowerPoint [Presentation](../). 
```cpp
// Vytvořte objekt Presentation, který představuje soubor prezentace
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

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IVideoCollection](../../ivideocollection/)
* Třída [Presentation](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)