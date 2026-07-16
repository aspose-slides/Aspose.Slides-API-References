---
title: get_Videos()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie la collection de tous les fichiers vidéo intégrés dans la présentation. Lecture seule IVideoCollection.
type: docs
weight: 235
url: /fr/aspose.slides/presentation/get_videos/
---
## Presentation::get_Videos() méthode

Renvoie la collection de tous les fichiers vidéo intégrés dans la présentation. En lecture seule [IVideoCollection](../../ivideocollection/).

```cpp
System::SharedPtr<IVideoCollection> Aspose::Slides::Presentation::get_Videos() override
```

## Remarques

Les exemples suivants montrent comment créer une [Video](../../video/) Frame intégrée dans un PowerPoint [Presentation](../). 
```cpp
// Instancier la classe Presentation qui représente le PPTX
auto pres = System::MakeObject<Presentation>();

// Obtenir la première diapositive
auto slide = pres->get_Slides()->idx_get(0);

// Intégrer la vidéo dans la présentation
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::MakeObject<System::IO::FileStream>(u"Wildlife.mp4", System::IO::FileMode::Open));

// Ajouter une Frame vidéo
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 350.0f, video);

// Définir la vidéo pour la Frame vidéo
vf->set_EmbeddedVideo(video);
// Définir le mode de lecture et le volume de la vidéo

vf->set_PlayMode(VideoPlayModePreset::Auto);
vf->set_Volume(AudioVolumeMode::Loud);

// Écrire le fichier PPTX sur le disque
pres->Save(u"VideoFrame_out.pptx", SaveFormat::Pptx);
```
Les exemples suivants montrent comment ajouter une vidéo en passant le chemin du fichier vidéo directement dans la méthode AddVideoFrame pour PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 150.0f, u"video1.avi");
```
Les exemples suivants montrent comment ajouter un gros fichier via BLOB à un [Presentation](../). 
```cpp
const System::String pathToVeryLargeVideo = u"veryLargeVideo.avi";
// Crée une nouvelle présentation à laquelle la vidéo sera ajoutée
auto pres = System::MakeObject<Presentation>();

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToVeryLargeVideo, System::IO::FileMode::Open);

// Ajoutons la vidéo à la présentation - nous avons choisi le comportement KeepLocked parce que nous
// n'avons pas l'intention d'accéder au fichier "veryLargeVideo.avi".
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(fileStream, LoadingStreamBehavior::KeepLocked);
pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 480.0f, 270.0f, video);

// Enregistre la présentation. Bien qu'une grande présentation soit générée, la consommation de mémoire
// reste faible pendant le cycle de vie de l'objet pres
pres->Save(u"presentationWithLargeVideo.pptx", Export::SaveFormat::Pptx);
```
Les exemples suivants montrent comment exporter un gros fichier via BLOB depuis PowerPoint [Presentation](../). 
```cpp
const System::String hugePresentationWithAudiosAndVideosFile = u"Large  Video File Test1.pptx";
auto loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_BlobManagementOptions(System::MakeObject<BlobManagementOptions>());
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);

// Crée une instance de Presentation, verrouille le fichier "hugePresentationWithAudiosAndVideos.pptx".
auto pres = System::MakeObject<Presentation>(hugePresentationWithAudiosAndVideosFile, loadOptions);

// Enregistrez chaque vidéo dans un fichier. Pour éviter une forte consommation de mémoire, nous avons besoin d'un tampon qui sera utilisé
// pour transférer les données du flux vidéo de la présentation vers un flux pour un nouveau fichier vidéo créé.
System::ArrayPtr<uint8_t> buffer = System::MakeArray<uint8_t>(8 * 1024, 0);
// Parcourt les vidéos
for (int32_t index = 0; index < pres->get_Videos()->get_Count(); index++)
{
    System::SharedPtr<IVideo> video = pres->get_Videos()->idx_get(index);
    // Ouvre le flux vidéo de la présentation. Veuillez noter que nous avons intentionnellement évité d'accéder aux propriétés
    // comme video.BinaryData - car cette propriété renvoie un tableau d'octets contenant toute la vidéo, ce qui alors
    // provoque le chargement des octets en mémoire. Nous utilisons video.GetStream, qui renvoie un Stream - et ne
    //  oblige à charger toute la vidéo en mémoire.
    auto presVideoStream = video->GetStream();

    auto outputFileStream = System::IO::File::OpenWrite(System::String::Format(u"video{0}.avi", index));

    int32_t bytesRead;
    while ((bytesRead = presVideoStream->Read(buffer, 0, buffer->get_Length())) > 0)
    {
        outputFileStream->Write(buffer, 0, bytesRead);
    }
    // La consommation de mémoire restera faible quel que soit la taille de la vidéo ou de la présentation,
}
// Si nécessaire, vous pouvez appliquer les mêmes étapes pour les fichiers audio.
```
Les exemples suivants montrent comment ajouter un hyperlien à une vidéo dans un PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::IO::File::ReadAllBytes(u"video.avi"));
System::SharedPtr<IVideoFrame> videoFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 100.0f, 100.0f, video);
videoFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
videoFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```
Les exemples suivants montrent comment créer une [Video](../../video/) Frame avec [Video](../../video/) à partir d'une source Web dans un PowerPoint [Presentation](../). 
```cpp
void Run()
{
    auto pres = System::MakeObject<Presentation>();

    AddVideoFromYouTube(pres, u"Tj75Arhq5ho");
    pres->Save(u"AddVideoFrameFromWebSource_out.pptx", SaveFormat::Pptx);
}

void AddVideoFromYouTube(System::SharedPtr<Presentation> pres, System::String videoId)
{
    // Ajouter une VideoFrame
    auto slide = pres->get_Slides()->idx_get(0);
    System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 427.0f, 240.0f, System::String(u"https://www.youtube.com/embed/") + videoId);
    videoFrame->set_PlayMode(VideoPlayModePreset::Auto);

    // Charger la miniature
    auto client = System::MakeObject<System::Net::WebClient>();
    System::String thumbnailUri = System::String(u"http://img.youtube.com/vi/") + videoId + u"/hqdefault.jpg";
    videoFrame->get_PictureFormat()->get_Picture()->set_Image(pres->get_Images()->AddImage(client->DownloadData(thumbnailUri)));
}
```
Les exemples suivants montrent comment extraire [Video](../../video/) d'une diapositive de PowerPoint [Presentation](../). 
```cpp
// Instancier un objet Presentation qui représente un fichier de présentation
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

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IVideoCollection](../../ivideocollection/)
* Classe [Presentation](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)