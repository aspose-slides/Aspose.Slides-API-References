---
title: get_Videos()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce la collezione di tutti i file video incorporati nella presentazione. Solo lettura IVideoCollection.
type: docs
weight: 235
url: /it/aspose.slides/presentation/get_videos/
---
## Presentation::get_Videos() metodo


Restituisce la collezione di tutti i file video incorporati nella presentazione. Solo lettura [IVideoCollection](../../ivideocollection/).

```cpp
System::SharedPtr<IVideoCollection> Aspose::Slides::Presentation::get_Videos() override
```

## Osservazioni


Il seguente esempio mostra come creare un Frame incorporato [Video](../../video/) in un PowerPoint [Presentation](../). 
```cpp
// Istanziare la classe Presentation che rappresenta il PPTX
auto pres = System::MakeObject<Presentation>();

// Ottieni la prima diapositiva
auto slide = pres->get_Slides()->idx_get(0);

// Incorpora video nella presentazione
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::MakeObject<System::IO::FileStream>(u"Wildlife.mp4", System::IO::FileMode::Open));

// Aggiungi Video Frame
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 350.0f, video);

// Imposta il video nel Video Frame
vf->set_EmbeddedVideo(video);
// Imposta la modalità di riproduzione e il volume del video

vf->set_PlayMode(VideoPlayModePreset::Auto);
vf->set_Volume(AudioVolumeMode::Loud);

// Scrivi il file PPTX su disco
pres->Save(u"VideoFrame_out.pptx", SaveFormat::Pptx);
```
 Il seguente esempio mostra come aggiungere un video passando il percorso del file video direttamente al metodo AddVideoFrame per PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 150.0f, u"video1.avi");
```
 Il seguente esempio mostra come aggiungere un file di grandi dimensioni tramite BLOB a un [Presentation](../). 
```cpp
const System::String pathToVeryLargeVideo = u"veryLargeVideo.avi";
// Crea una nuova presentazione a cui verrà aggiunto il video
auto pres = System::MakeObject<Presentation>();

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToVeryLargeVideo, System::IO::FileMode::Open);

// Aggiungiamo il video alla presentazione - abbiamo scelto il comportamento KeepLocked perché
// non intendiamo accedere al file "veryLargeVideo.avi".
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(fileStream, LoadingStreamBehavior::KeepLocked);
pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 480.0f, 270.0f, video);

// Salva la presentazione. Mentre viene generata una presentazione di grandi dimensioni, il consumo di memoria
// rimane basso per il ciclo di vita dell'oggetto pres
pres->Save(u"presentationWithLargeVideo.pptx", Export::SaveFormat::Pptx);
```
 Il seguente esempio mostra come esportare un file di grandi dimensioni tramite BLOB da PowerPoint [Presentation](../). 
```cpp
// Crea un'istanza di Presentation e blocca il file "hugePresentationWithAudiosAndVideos.pptx" file.
auto pres = System::MakeObject<Presentation>(hugePresentationWithAudiosAndVideosFile, loadOptions);

// Salviamo ogni video in un file. Per evitare un elevato consumo di memoria, è necessario un buffer che verrà usato
// per trasferire i dati dallo stream video della presentazione a uno stream per un nuovo file video.
System::ArrayPtr<uint8_t> buffer = System::MakeArray<uint8_t>(8 * 1024, 0);
// Itera attraverso i video
for (int32_t index = 0; index < pres->get_Videos()->get_Count(); index++)
{
    System::SharedPtr<IVideo> video = pres->get_Videos()->idx_get(index);
    // Apre lo stream video della presentazione. Si noti che abbiamo evitato intenzionalmente di accedere alle proprietà
    // come video.BinaryData - perché questa proprietà restituisce un array di byte contenente l'intero video, il che
    // causa il caricamento dei byte in memoria. Utilizziamo video.GetStream, che restituirà Stream - e NON
    //  richiede di caricare l'intero video in memoria.
    auto presVideoStream = video->GetStream();

    auto outputFileStream = System::IO::File::OpenWrite(System::String::Format(u"video{0}.avi", index));

    int32_t bytesRead;
    while ((bytesRead = presVideoStream->Read(buffer, 0, buffer->get_Length())) > 0)
    {
        outputFileStream->Write(buffer, 0, bytesRead);
    }
    // Il consumo di memoria rimarrà basso indipendentemente dalle dimensioni del video o della presentazione,
}
// Se necessario, è possibile applicare gli stessi passaggi per i file audio.
```
 Il seguente esempio mostra come aggiungere un collegamento ipertestuale a un video in un PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::IO::File::ReadAllBytes(u"video.avi"));
System::SharedPtr<IVideoFrame> videoFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 100.0f, 100.0f, video);
videoFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
videoFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```
 Il seguente esempio mostra come creare un Frame [Video](../../video/) con [Video](../../video/) da una sorgente web in un PowerPoint [Presentation](../). 
```cpp
void Run()
{
    auto pres = System::MakeObject<Presentation>();

    AddVideoFromYouTube(pres, u"Tj75Arhq5ho");
    pres->Save(u"AddVideoFrameFromWebSource_out.pptx", SaveFormat::Pptx);
}

void AddVideoFromYouTube(System::SharedPtr<Presentation> pres, System::String videoId)
{
    // Aggiungi videoFrame
    auto slide = pres->get_Slides()->idx_get(0);
    System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 427.0f, 240.0f, System::String(u"https://www.youtube.com/embed/") + videoId);
    videoFrame->set_PlayMode(VideoPlayModePreset::Auto);

    // Carica miniatura
    auto client = System::MakeObject<System::Net::WebClient>();
    System::String thumbnailUri = System::String(u"http://img.youtube.com/vi/") + videoId + u"/hqdefault.jpg";
    videoFrame->get_PictureFormat()->get_Picture()->set_Image(pres->get_Images()->AddImage(client->DownloadData(thumbnailUri)));
}
```
 Il seguente esempio mostra come estrarre [Video](../../video/) da una diapositiva di PowerPoint [Presentation](../). 
```cpp
// Istanziare un oggetto Presentation che rappresenta un file di presentazione
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

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IVideoCollection](../../ivideocollection/)
* Classe [Presentation](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)