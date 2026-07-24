---
title: get_Videos()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die Sammlung aller eingebetteten Videodateien in der Präsentation zurück. Nur lesbar IVideoCollection.
type: docs
weight: 235
url: /de/aspose.slides/presentation/get_videos/
---
## Presentation::get_Videos() Methode

Gibt die Sammlung aller eingebetteten Videodateien in der Präsentation zurück. Nur lesbar [IVideoCollection](../../ivideocollection/).

```cpp
System::SharedPtr<IVideoCollection> Aspose::Slides::Presentation::get_Videos() override
```

## Hinweise

Die folgenden Beispiele zeigen, wie ein eingebetteter [Video](../../video/) Frame in einer PowerPoint [Presentation](../) erstellt wird. 
```cpp
// Instanziiere die Presentation-Klasse, die die PPTX darstellt
auto pres = System::MakeObject<Presentation>();

// Hole die erste Folie
auto slide = pres->get_Slides()->idx_get(0);

// Video in die Präsentation einbetten
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::MakeObject<System::IO::FileStream>(u"Wildlife.mp4", System::IO::FileMode::Open));

// Video-Frame hinzufügen
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 350.0f, video);

// Video im Video-Frame setzen
vf->set_EmbeddedVideo(video);
// Wiedergabemodus und Lautstärke des Videos festlegen

vf->set_PlayMode(VideoPlayModePreset::Auto);
vf->set_Volume(AudioVolumeMode::Loud);

// Schreibe die PPTX-Datei auf die Festplatte
pres->Save(u"VideoFrame_out.pptx", SaveFormat::Pptx);
```
Die folgenden Beispiele zeigen, wie man ein Video hinzufügt, indem man den Pfad zur Videodatei direkt an die AddVideoFrame-Methode für PowerPoint [Presentation](../) übergibt. 
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 150.0f, u"video1.avi");
```
Die folgenden Beispiele zeigen, wie man eine große Datei über BLOB zu einem [Presentation](../) hinzufügt. 
```cpp
const System::String pathToVeryLargeVideo = u"veryLargeVideo.avi";
// Erstellt eine neue Präsentation, zu der das Video hinzugefügt wird
auto pres = System::MakeObject<Presentation>();

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToVeryLargeVideo, System::IO::FileMode::Open);

// Fügen wir das Video zur Präsentation hinzu - wir haben das KeepLocked-Verhalten gewählt, weil wir
// nicht beabsichtigen, auf die Datei "veryLargeVideo.avi" zuzugreifen.
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(fileStream, LoadingStreamBehavior::KeepLocked);
pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 480.0f, 270.0f, video);

// Speichert die Präsentation. Während eine große Präsentation ausgegeben wird, bleibt der Speicherverbrauch
// gering während des gesamten Lebenszyklus des pres-Objekts
pres->Save(u"presentationWithLargeVideo.pptx", Export::SaveFormat::Pptx);
```
Die folgenden Beispiele zeigen, wie man eine große Datei über BLOB aus PowerPoint [Presentation](../) exportiert. 
```cpp
const System::String hugePresentationWithAudiosAndVideosFile = u"Large  Video File Test1.pptx";
auto loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_BlobManagementOptions(System::MakeObject<BlobManagementOptions>());
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);

// Erstellt eine Instanz von Presentation und sperrt die "hugePresentationWithAudiosAndVideos.pptx" Datei.
auto pres = System::MakeObject<Presentation>(hugePresentationWithAudiosAndVideosFile, loadOptions);

// Speichern wir jedes Video in eine Datei. Um hohen Speicherverbrauch zu verhindern, benötigen wir einen Puffer, der verwendet wird
// um die Daten vom Videostream der Präsentation zu einem Stream für eine neu erstellte Videodatei zu übertragen.
System::ArrayPtr<uint8_t> buffer = System::MakeArray<uint8_t>(8 * 1024, 0);
// Durchläuft die Videos
for (int32_t index = 0; index < pres->get_Videos()->get_Count(); index++)
{
    System::SharedPtr<IVideo> video = pres->get_Videos()->idx_get(index);
    // Öffnet den Videostream der Präsentation. Bitte beachten Sie, dass wir bewusst vermieden haben, Eigenschaften zuzugreifen
    // wie video.BinaryData - weil diese Eigenschaft ein Byte-Array mit dem gesamten Video zurückgibt, was dann
    // verursacht, dass Bytes in den Speicher geladen werden. Wir verwenden video.GetStream, das einen Stream zurückgibt – und nicht
    //  erfordert, dass wir das gesamte Video in den Speicher laden.
    auto presVideoStream = video->GetStream();

    auto outputFileStream = System::IO::File::OpenWrite(System::String::Format(u"video{0}.avi", index));

    int32_t bytesRead;
    while ((bytesRead = presVideoStream->Read(buffer, 0, buffer->get_Length())) > 0)
    {
        outputFileStream->Write(buffer, 0, bytesRead);
    }
    // Der Speicherverbrauch bleibt niedrig, unabhängig von der Größe des Videos oder der Präsentation,
}
// Bei Bedarf können Sie dieselben Schritte für Audiodateien anwenden.
```
Die folgenden Beispiele zeigen, wie man einem Video in einer PowerPoint [Presentation](../) einen Hyperlink hinzufügt. 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::IO::File::ReadAllBytes(u"video.avi"));
System::SharedPtr<IVideoFrame> videoFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 100.0f, 100.0f, video);
videoFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
videoFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```
Die folgenden Beispiele zeigen, wie man einen [Video](../../video/) Frame mit [Video](../../video/) aus einer Webquelle in einer PowerPoint [Presentation](../) erstellt. 
```cpp
void Run()
{
    auto pres = System::MakeObject<Presentation>();

    AddVideoFromYouTube(pres, u"Tj75Arhq5ho");
    pres->Save(u"AddVideoFrameFromWebSource_out.pptx", SaveFormat::Pptx);
}

void AddVideoFromYouTube(System::SharedPtr<Presentation> pres, System::String videoId)
{
    // Video-Frame hinzufügen
    auto slide = pres->get_Slides()->idx_get(0);
    System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 427.0f, 240.0f, System::String(u"https://www.youtube.com/embed/") + videoId);
    videoFrame->set_PlayMode(VideoPlayModePreset::Auto);

    // Miniaturansicht laden
    auto client = System::MakeObject<System::Net::WebClient>();
    System::String thumbnailUri = System::String(u"http://img.youtube.com/vi/") + videoId + u"/hqdefault.jpg";
    videoFrame->get_PictureFormat()->get_Picture()->set_Image(pres->get_Images()->AddImage(client->DownloadData(thumbnailUri)));
}
```
Die folgenden Beispiele zeigen, wie man [Video](../../video/) aus einer Folie von PowerPoint [Presentation](../) extrahiert. 
```cpp
// Instanziiere ein Presentation-Objekt, das eine Präsentationsdatei darstellt
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

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IVideoCollection](../../ivideocollection/)
* Klasse [Presentation](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)