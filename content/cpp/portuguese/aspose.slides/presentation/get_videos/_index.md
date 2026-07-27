---
title: get_Videos()
second_title: Referência da API Aspose.Slides para C++
description: Retorna a coleção de todos os arquivos de vídeo incorporados na apresentação. Somente leitura IVideoCollection.
type: docs
weight: 235
url: /pt/aspose.slides/presentation/get_videos/
---
## Presentation::get_Videos() método

Retorna a coleção de todos os arquivos de vídeo incorporados na apresentação. Somente leitura [IVideoCollection](../../ivideocollection/).

```cpp
System::SharedPtr<IVideoCollection> Aspose::Slides::Presentation::get_Videos() override
```

## Observações

```cpp
// Instanciar a classe Presentation que representa o PPTX
auto pres = System::MakeObject<Presentation>();

// Obter o primeiro slide
auto slide = pres->get_Slides()->idx_get(0);

// Incorporar vídeo na apresentação
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::MakeObject<System::IO::FileStream>(u"Wildlife.mp4", System::IO::FileMode::Open));

// Adicionar Video Frame
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 350.0f, video);

// Definir vídeo no Video Frame
vf->set_EmbeddedVideo(video);
// Definir modo de reprodução e volume do vídeo

vf->set_PlayMode(VideoPlayModePreset::Auto);
vf->set_Volume(AudioVolumeMode::Loud);

// Gravar o arquivo PPTX no disco
pres->Save(u"VideoFrame_out.pptx", SaveFormat::Pptx);
```
 O exemplo a seguir mostra como criar um [Video](../../video/) Frame incorporado em um PowerPoint [Presentation](../).
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 150.0f, u"video1.avi");
```
 O exemplo a seguir mostra como adicionar um vídeo passando o caminho para o arquivo de vídeo diretamente ao método AddVideoFrame para PowerPoint [Presentation](../).
```cpp
const System::String pathToVeryLargeVideo = u"veryLargeVideo.avi";
// Cria uma nova apresentação à qual o vídeo será adicionado
auto pres = System::MakeObject<Presentation>();

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToVeryLargeVideo, System::IO::FileMode::Open);

// Vamos adicionar o vídeo à apresentação - escolhemos o comportamento KeepLocked porque nós
// não pretendemos acessar o arquivo "veryLargeVideo.avi" file.
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(fileStream, LoadingStreamBehavior::KeepLocked);
pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 480.0f, 270.0f, video);

// Salva a apresentação. Enquanto uma apresentação grande é gerada, o consumo de memória
// permanece baixo ao longo do ciclo de vida do objeto pres
pres->Save(u"presentationWithLargeVideo.pptx", Export::SaveFormat::Pptx);
```
 O exemplo a seguir mostra como adicionar um arquivo grande através de BLOB para um [Presentation](../).
```cpp
const System::String hugePresentationWithAudiosAndVideosFile = u"Large  Video File Test1.pptx";
auto loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_BlobManagementOptions(System::MakeObject<BlobManagementOptions>());
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);

// Cria uma instância de Presentation, bloqueia o arquivo "hugePresentationWithAudiosAndVideos.pptx".
auto pres = System::MakeObject<Presentation>(hugePresentationWithAudiosAndVideosFile, loadOptions);

// Vamos salvar cada vídeo em um arquivo. Para evitar alto consumo de memória, precisamos de um buffer que será usado
// para transferir os dados do fluxo de vídeo da apresentação para um fluxo de um novo arquivo de vídeo.
System::ArrayPtr<uint8_t> buffer = System::MakeArray<uint8_t>(8 * 1024, 0);
// Itera pelos vídeos
for (int32_t index = 0; index < pres->get_Videos()->get_Count(); index++)
{
    System::SharedPtr<IVideo> video = pres->get_Videos()->idx_get(index);
    // Abre o fluxo de vídeo da apresentação. Por favor, note que evitamos intencionalmente acessar propriedades
    // como video.BinaryData - porque essa propriedade retorna um array de bytes contendo o vídeo completo, o que então
    // faz com que os bytes sejam carregados na memória. Usamos video.GetStream, que retornará um Stream - e NÃO
    //  requer que carreguemos o vídeo inteiro na memória.
    auto presVideoStream = video->GetStream();

    auto outputFileStream = System::IO::File::OpenWrite(System::String::Format(u"video{0}.avi", index));

    int32_t bytesRead;
    while ((bytesRead = presVideoStream->Read(buffer, 0, buffer->get_Length())) > 0)
    {
        outputFileStream->Write(buffer, 0, bytesRead);
    }
    // O consumo de memória permanecerá baixo independentemente do tamanho do vídeo ou da apresentação,
}
// Se necessário, você pode aplicar os mesmos passos para arquivos de áudio.
```
 O exemplo a seguir mostra como exportar um arquivo grande através de BLOB do PowerPoint [Presentation](../).
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::IO::File::ReadAllBytes(u"video.avi"));
System::SharedPtr<IVideoFrame> videoFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 100.0f, 100.0f, video);
videoFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
videoFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```
 O exemplo a seguir mostra como adicionar um hyperlink a um vídeo em um PowerPoint [Presentation](../).
```cpp
void Run()
{
    auto pres = System::MakeObject<Presentation>();

    AddVideoFromYouTube(pres, u"Tj75Arhq5ho");
    pres->Save(u"AddVideoFrameFromWebSource_out.pptx", SaveFormat::Pptx);
}

void AddVideoFromYouTube(System::SharedPtr<Presentation> pres, System::String videoId)
{
    // Adicionar videoFrame
    auto slide = pres->get_Slides()->idx_get(0);
    System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 427.0f, 240.0f, System::String(u"https://www.youtube.com/embed/") + videoId);
    videoFrame->set_PlayMode(VideoPlayModePreset::Auto);

    // Carregar miniatura
    auto client = System::MakeObject<System::Net::WebClient>();
    System::String thumbnailUri = System::String(u"http://img.youtube.com/vi/") + videoId + u"/hqdefault.jpg";
    videoFrame->get_PictureFormat()->get_Picture()->set_Image(pres->get_Images()->AddImage(client->DownloadData(thumbnailUri)));
}
```
 O exemplo a seguir mostra como criar um [Video](../../video/) Frame com [Video](../../video/) a partir da Web Source em um PowerPoint [Presentation](../).
```cpp
// Instanciar um objeto Presentation que representa um arquivo de apresentação
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
 O exemplo a seguir mostra como extrair [Video](../../video/) do slide do PowerPoint [Presentation](../).

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IVideoCollection](../../ivideocollection/)
* Class [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)