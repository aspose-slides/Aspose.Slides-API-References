---
title: get_Videos()
second_title: Aspose.Slides dla C++ Referencja API
description: Zwraca kolekcję wszystkich osadzonych plików wideo w prezentacji. Tylko do odczytu IVideoCollection.
type: docs
weight: 235
url: /pl/aspose.slides/presentation/get_videos/
---
## Presentation::get_Videos() metoda


Zwraca kolekcję wszystkich osadzonych plików wideo w prezentacji. Tylko do odczytu [IVideoCollection](../../ivideocollection/).

```cpp
System::SharedPtr<IVideoCollection> Aspose::Slides::Presentation::get_Videos() override
```

## Uwagi


 Poniższe przykłady pokazują, jak utworzyć osadzony [Video](../../video/) Frame w programie PowerPoint [Presentation](../). 
```cpp
// Instancjonuj klasę Presentation reprezentującą plik PPTX
auto pres = System::MakeObject<Presentation>();

// Pobierz pierwszy slajd
auto slide = pres->get_Slides()->idx_get(0);

// Osadź wideo w prezentacji
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::MakeObject<System::IO::FileStream>(u"Wildlife.mp4", System::IO::FileMode::Open));

// Dodaj ramkę wideo
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 350.0f, video);

// Ustaw wideo w ramce wideo
vf->set_EmbeddedVideo(video);
// Ustaw tryb odtwarzania i głośność wideo

vf->set_PlayMode(VideoPlayModePreset::Auto);
vf->set_Volume(AudioVolumeMode::Loud);

// Zapisz plik PPTX na dysku
pres->Save(u"VideoFrame_out.pptx", SaveFormat::Pptx);
```
 Poniższe przykłady pokazują, jak dodać wideo, przekazując ścieżkę do pliku wideo bezpośrednio do metody AddVideoFrame w programie PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 150.0f, u"video1.avi");
```
 Poniższe przykłady pokazują, jak dodać duży plik za pomocą BLOB do [Presentation](../). 
```cpp
const System::String pathToVeryLargeVideo = u"veryLargeVideo.avi";
// Tworzy nową prezentację, do której zostanie dodane wideo
auto pres = System::MakeObject<Presentation>();

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToVeryLargeVideo, System::IO::FileMode::Open);

// Dodajmy wideo do prezentacji - wybraliśmy zachowanie KeepLocked, ponieważ
// nie zamierzamy uzyskać dostępu do pliku "veryLargeVideo.avi" file.
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(fileStream, LoadingStreamBehavior::KeepLocked);
pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 480.0f, 270.0f, video);

// Zapisuje prezentację. Podczas gdy duża prezentacja jest tworzona, zużycie pamięci
// pozostaje niskie w trakcie całego cyklu życia obiektu pres
pres->Save(u"presentationWithLargeVideo.pptx", Export::SaveFormat::Pptx);
```
 Poniższe przykłady pokazują, jak wyeksportować duży plik za pomocą BLOB z programu PowerPoint [Presentation](../). 
```cpp
const System::String hugePresentationWithAudiosAndVideosFile = u"Large  Video File Test1.pptx";
auto loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_BlobManagementOptions(System::MakeObject<BlobManagementOptions>());
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);

// Tworzy instancję Presentation, blokując plik "hugePresentationWithAudiosAndVideos.pptx" file.
auto pres = System::MakeObject<Presentation>(hugePresentationWithAudiosAndVideosFile, loadOptions);

// Zapiszmy każde wideo do pliku. Aby zapobiec dużemu zużyciu pamięci, potrzebny jest bufor, który będzie używany
// do przenoszenia danych z strumienia wideo prezentacji do strumienia nowo utworzonego pliku wideo.
System::ArrayPtr<uint8_t> buffer = System::MakeArray<uint8_t>(8 * 1024, 0);
// Iteruje po wideo
for (int32_t index = 0; index < pres->get_Videos()->get_Count(); index++)
{
    System::SharedPtr<IVideo> video = pres->get_Videos()->idx_get(index);
    // Otwiera strumień wideo prezentacji. Proszę zauważyć, że celowo unikaliśmy dostępu do właściwości
    // takich jak video.BinaryData – ponieważ ta właściwość zwraca tablicę bajtów zawierającą całe wideo, co następnie
    // powoduje załadowanie bajtów do pamięci. Używamy video.GetStream, który zwróci Stream – i NIE
    //  wymaga załadowania całego wideo do pamięci.
    auto presVideoStream = video->GetStream();

    auto outputFileStream = System::IO::File::OpenWrite(System::String::Format(u"video{0}.avi", index));

    int32_t bytesRead;
    while ((bytesRead = presVideoStream->Read(buffer, 0, buffer->get_Length())) > 0)
    {
        outputFileStream->Write(buffer, 0, bytesRead);
    }
    // Zużycie pamięci pozostanie niskie niezależnie od rozmiaru wideo lub prezentacji,
}
 // W razie potrzeby możesz zastosować te same kroki dla plików audio.
```
 Poniższe przykłady pokazują, jak dodać hiperłącze do wideo w programie PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::IO::File::ReadAllBytes(u"video.avi"));
System::SharedPtr<IVideoFrame> videoFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 100.0f, 100.0f, video);
videoFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
videoFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```
 Poniższe przykłady pokazują, jak utworzyć [Video](../../video/) Frame z [Video](../../video/) z Źródła internetowego w programie PowerPoint [Presentation](../). 
```cpp
void Run()
{
    auto pres = System::MakeObject<Presentation>();

    AddVideoFromYouTube(pres, u"Tj75Arhq5ho");
    pres->Save(u"AddVideoFrameFromWebSource_out.pptx", SaveFormat::Pptx);
}

void AddVideoFromYouTube(System::SharedPtr<Presentation> pres, System::String videoId)
{
    // Dodaj ramkę wideo
    auto slide = pres->get_Slides()->idx_get(0);
    System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 427.0f, 240.0f, System::String(u"https://www.youtube.com/embed/") + videoId);
    videoFrame->set_PlayMode(VideoPlayModePreset::Auto);

    // Wczytaj miniaturę
    auto client = System::MakeObject<System::Net::WebClient>();
    System::String thumbnailUri = System::String(u"http://img.youtube.com/vi/") + videoId + u"/hqdefault.jpg";
    videoFrame->get_PictureFormat()->get_Picture()->set_Image(pres->get_Images()->AddImage(client->DownloadData(thumbnailUri)));
}
```
 Poniższe przykłady pokazują, jak wyodrębnić [Video](../../video/) ze slajdu programu PowerPoint [Presentation](../). 
```cpp
// Utwórz obiekt Presentation, który reprezentuje plik prezentacji
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

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IVideoCollection](../../ivideocollection/)
* Klasa [Presentation](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)