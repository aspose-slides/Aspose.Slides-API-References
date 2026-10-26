---
title: get_Videos()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve la colección de todos los archivos de video incrustados en la presentación. Solo lectura IVideoCollection.
type: docs
weight: 235
url: /es/aspose.slides/presentation/get_videos/
---
## Presentation::get_Videos() método

Devuelve la colección de todos los archivos de video incrustados en la presentación. Solo lectura [IVideoCollection](../../ivideocollection/).

```cpp
System::SharedPtr<IVideoCollection> Aspose::Slides::Presentation::get_Videos() override
```

## Comentarios

Los siguientes ejemplos muestran cómo crear un marco [Video](../../video/) incrustado en un PowerPoint [Presentation](../). 
```cpp
// Instancia la clase Presentation que representa el PPTX
auto pres = System::MakeObject<Presentation>();

// Obtiene la primera diapositiva
auto slide = pres->get_Slides()->idx_get(0);

// Inserta video dentro de la presentación
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::MakeObject<System::IO::FileStream>(u"Wildlife.mp4", System::IO::FileMode::Open));

// Añade un Video Frame
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 350.0f, video);

// Asigna el video al Video Frame
vf->set_EmbeddedVideo(video);
// Establece el modo de reproducción y el volumen del video

vf->set_PlayMode(VideoPlayModePreset::Auto);
vf->set_Volume(AudioVolumeMode::Loud);

// Escribe el archivo PPTX en disco
pres->Save(u"VideoFrame_out.pptx", SaveFormat::Pptx);
```
Los siguientes ejemplos muestran cómo añadir un video pasando la ruta al archivo de video directamente en el método AddVideoFrame para PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 150.0f, u"video1.avi");
```
Los siguientes ejemplos muestran cómo añadir un archivo grande mediante BLOB a un [Presentation](../). 
```cpp
const System::String pathToVeryLargeVideo = u"veryLargeVideo.avi";
// Crea una nueva presentación a la que se agregará el video
auto pres = System::MakeObject<Presentation>();

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToVeryLargeVideo, System::IO::FileMode::Open);

// Añadamos el video a la presentación - elegimos el comportamiento KeepLocked porque
// no pretendemos acceder al archivo "veryLargeVideo.avi" file.
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(fileStream, LoadingStreamBehavior::KeepLocked);
pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 480.0f, 270.0f, video);

// Guarda la presentación. Mientras se genera una presentación grande, el consumo de memoria
// permanece bajo durante el ciclo de vida del objeto pres
pres->Save(u"presentationWithLargeVideo.pptx", Export::SaveFormat::Pptx);
```
Los siguientes ejemplos muestran cómo exportar un archivo grande mediante BLOB desde PowerPoint [Presentation](../). 
```cpp
const System::String hugePresentationWithAudiosAndVideosFile = u"Large  Video File Test1.pptx";
auto loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_BlobManagementOptions(System::MakeObject<BlobManagementOptions>());
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);

// Crea una instancia de Presentation y bloquea el archivo "hugePresentationWithAudiosAndVideos.pptx" file.
auto pres = System::MakeObject<Presentation>(hugePresentationWithAudiosAndVideosFile, loadOptions);

// Guardemos cada video en un archivo. Para evitar un uso elevado de memoria, necesitamos un buffer que será usado
// para transferir los datos del flujo de video de la presentación a un flujo para un archivo de video recién creado.
System::ArrayPtr<uint8_t> buffer = System::MakeArray<uint8_t>(8 * 1024, 0);
// Recorre los videos
for (int32_t index = 0; index < pres->get_Videos()->get_Count(); index++)
{
    System::SharedPtr<IVideo> video = pres->get_Videos()->idx_get(index);
    // Abre el flujo de video de la presentación. Por favor, note que evitamos intencionalmente acceder a propiedades
    // como video.BinaryData - porque esta propiedad devuelve una matriz de bytes que contiene el video completo, lo que entonces
    // provoca que los bytes se carguen en memoria. Usamos video.GetStream, que devolverá Stream - y NO
    //  requiere que carguemos todo el video en la memoria.
    auto presVideoStream = video->GetStream();

    auto outputFileStream = System::IO::File::OpenWrite(System::String::Format(u"video{0}.avi", index));

    int32_t bytesRead;
    while ((bytesRead = presVideoStream->Read(buffer, 0, buffer->get_Length())) > 0)
    {
        outputFileStream->Write(buffer, 0, bytesRead);
    }
    // El consumo de memoria permanecerá bajo sin importar el tamaño del video o la presentación,
}
// Si es necesario, puede aplicar los mismos pasos para archivos de audio.
```
Los siguientes ejemplos muestran cómo añadir un hipervínculo a un video en un PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::IO::File::ReadAllBytes(u"video.avi"));
System::SharedPtr<IVideoFrame> videoFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 100.0f, 100.0f, video);
videoFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
videoFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```
Los siguientes ejemplos muestran cómo crear un marco [Video](../../video/) con [Video](../../video/) desde la fuente web en un PowerPoint [Presentation](../). 
```cpp
void Run()
{
    auto pres = System::MakeObject<Presentation>();

    AddVideoFromYouTube(pres, u"Tj75Arhq5ho");
    pres->Save(u"AddVideoFrameFromWebSource_out.pptx", SaveFormat::Pptx);
}

void AddVideoFromYouTube(System::SharedPtr<Presentation> pres, System::String videoId)
{
    // Agregar videoFrame
    auto slide = pres->get_Slides()->idx_get(0);
    System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 427.0f, 240.0f, System::String(u"https://www.youtube.com/embed/") + videoId);
    videoFrame->set_PlayMode(VideoPlayModePreset::Auto);

    // Cargar miniatura
    auto client = System::MakeObject<System::Net::WebClient>();
    System::String thumbnailUri = System::String(u"http://img.youtube.com/vi/") + videoId + u"/hqdefault.jpg";
    videoFrame->get_PictureFormat()->get_Picture()->set_Image(pres->get_Images()->AddImage(client->DownloadData(thumbnailUri)));
}
```
Los siguientes ejemplos muestran cómo extraer [Video](../../video/) de una diapositiva de PowerPoint [Presentation](../). 
```cpp
// Instanciar un objeto Presentation que representa un archivo de presentación
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

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IVideoCollection](../../ivideocollection/)
* Class [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)