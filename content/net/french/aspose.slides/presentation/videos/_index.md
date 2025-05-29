---
title: Vidéos
second_title: Référence API Aspose.Slides pour .NET
description: Renvoie la collection de tous les fichiers vidéo intégrés dans la présentation. Lecture seule IVideoCollectionaspose.slides/ivideocollection.
type: docs
weight: 280
url: /fr/aspose.slides/presentation/videos/
---

## Propriété Presentation.Videos

Renvoie la collection de tous les fichiers vidéo intégrés dans la présentation. Lecture seule [`IVideoCollection`](../../ivideocollection).

```csharp
public IVideoCollection Videos { get; }
```

### Exemples

Les exemples suivants montrent comment créer un cadre vidéo intégré dans une présentation PowerPoint.

```csharp
[C#]
// Instancier la classe Presentation qui représente le PPTX
using (Presentation pres = new Presentation())
{
    // Obtenir la première diapositive
    ISlide sld = pres.Slides[0];
    // Intégrer une vidéo dans la présentation
    IVideo vid = pres.Videos.AddVideo(new FileStream("Wildlife.mp4", FileMode.Open));
    // Ajouter un cadre vidéo
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 350, vid);
    // Définir la vidéo pour le cadre vidéo
    vf.EmbeddedVideo = vid;
    // Définir le mode de lecture et le volume de la vidéo
    vf.PlayMode = VideoPlayModePreset.Auto;
    vf.Volume = AudioVolumeMode.Loud;
    // Écrire le fichier PPTX sur le disque
    pres.Save("VideoFrame_out.pptx", SaveFormat.Pptx);
}
```

Les exemples suivants montrent comment ajouter une vidéo en passant le chemin du fichier vidéo directement dans la méthode AddVideoFrame pour une présentation PowerPoint.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    ISlide sld = pres.Slides[0];
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 150, "video1.avi");
}
```

Les exemples suivants montrent comment ajouter un gros fichier via BLOB à une présentation.

```csharp
[C#]
const string pathToVeryLargeVideo = "veryLargeVideo.avi";
// Crée une nouvelle présentation à laquelle la vidéo sera ajoutée
using (Presentation pres = new Presentation())
{
    using (FileStream fileStream = new FileStream(pathToVeryLargeVideo, FileMode.Open))
    {
        // Ajoutons la vidéo à la présentation - nous avons choisi le comportement KeepLocked car nous ne
        // souhaitons pas accéder au fichier "veryLargeVideo.avi".
        IVideo video = pres.Videos.AddVideo(fileStream, LoadingStreamBehavior.KeepLocked);
        pres.Slides[0].Shapes.AddVideoFrame(0, 0, 480, 270, video);
        // Enregistre la présentation. Alors qu'une grande présentation est générée, la consommation de mémoire
        // reste faible tout au long du cycle de vie de l'objet pres
        pres.Save("presentationWithLargeVideo.pptx", SaveFormat.Pptx);
    }
}
```

Les exemples suivants montrent comment exporter un gros fichier via BLOB depuis une présentation PowerPoint.

```csharp
[C#]
const string hugePresentationWithAudiosAndVideosFile = @"Large  Video File Test1.pptx";
LoadOptions loadOptions = new LoadOptions
{
	BlobManagementOptions = {
		// Verrouille le fichier source et ne le charge PAS en mémoire
		PresentationLockingBehavior = PresentationLockingBehavior.KeepLocked,
	}
};
// Crée une instance de la présentation, verrouille le fichier "hugePresentationWithAudiosAndVideos.pptx".
using (Presentation pres = new Presentation(hugePresentationWithAudiosAndVideosFile, loadOptions))
{
	// Enregistrons chaque vidéo dans un fichier. Pour éviter une forte consommation de mémoire, nous avons besoin d'un buffer qui sera utilisé
	// pour transférer les données du flux vidéo de la présentation vers un flux pour un nouveau fichier vidéo créé.
	byte[] buffer = new byte[8 * 1024];
	// Itère à travers les vidéos
	for (var index = 0; index < pres.Videos.Count; index++)
	{
		IVideo video = pres.Videos[index];
		// Ouvre le flux vidéo de présentation. Veuillez noter que nous avons intentionnellement évité d'accéder à des propriétés
		// comme video.BinaryData - car cette propriété retourne un tableau d'octets contenant une vidéo complète, ce qui provoque ensuite 
		// le chargement des octets en mémoire. Nous utilisons video.GetStream, qui retourne un Stream - et ne nécessite PAS
		// de charger la vidéo entière en mémoire.
		using (Stream presVideoStream = video.GetStream())
		{
			using (FileStream outputFileStream = File.OpenWrite($"video{index}.avi"))
			{
				int bytesRead;
				while ((bytesRead = presVideoStream.Read(buffer, 0, buffer.Length)) > 0)
				{
					outputFileStream.Write(buffer, 0, bytesRead);
				}
			}
		}
		// La consommation de mémoire restera faible quelle que soit la taille de la vidéo ou de la présentation.
	}
	// Si nécessaire, vous pouvez appliquer les mêmes étapes pour les fichiers audio.
}
```

Les exemples suivants montrent comment ajouter un lien hypertexte à une vidéo dans une présentation PowerPoint.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    IVideo video = pres.Videos.AddVideo(File.ReadAllBytes("video.avi"));
    IVideoFrame videoFrame = pres.Slides[0].Shapes.AddVideoFrame(10, 10, 100, 100, video);
    videoFrame.HyperlinkClick = new Hyperlink("https://www.aspose.com/");
    videoFrame.HyperlinkClick.Tooltip = "Plus de 70 % des entreprises du Fortune 100 font confiance aux API Aspose";
    pres.Save("pres-out.pptx", SaveFormat.Pptx);
}
```

Les exemples suivants montrent comment créer un cadre vidéo avec vidéo depuis une source web dans une présentation PowerPoint.

```csharp
[C#]
public static void Run()
{
    using (Presentation pres = new Presentation())
    {
        AddVideoFromYouTube(pres, "Tj75Arhq5ho");
        pres.Save("AddVideoFrameFromWebSource_out.pptx", SaveFormat.Pptx);
    }
}
private static void AddVideoFromYouTube(Presentation pres, string videoId)
{
    //ajouter videoFrame
    IVideoFrame videoFrame = pres.Slides[0].Shapes.AddVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
    videoFrame.PlayMode = VideoPlayModePreset.Auto;
    //charger la miniature
    using (WebClient client = new WebClient())
    {
        string thumbnailUri = "http://img.youtube.com/vi/" + videoId + "/hqdefault.jpg";
        videoFrame.PictureFormat.Picture.Image = pres.Images.AddImage(client.DownloadData(thumbnailUri));
    }
}
```

Les exemples suivants montrent comment extraire une vidéo d'une diapositive d'une présentation PowerPoint.

```csharp
[C#]
// Instancier un objet Presentation qui représente un fichier de présentation
using (Presentation presentation = new Presentation("Video.pptx"))
{
	foreach (ISlide slide in presentation.Slides)
	{
		foreach (IShape shape in presentation.Slides[0].Shapes)
		{
			if (shape is VideoFrame)
			{
				IVideoFrame vf = shape as IVideoFrame;
				String type = vf.EmbeddedVideo.ContentType;
				int ss = type.LastIndexOf('/');
				type = type.Remove(0, type.LastIndexOf('/') + 1);
				Byte[] buffer = vf.EmbeddedVideo.BinaryData;
				using (FileStream stream = new FileStream("NewVideo_out." + type, FileMode.Create, FileAccess.Write, FileShare.Read))
				{
					stream.Write(buffer, 0, buffer.Length);
				}
			}
		}
	}
}
```

### Voir aussi

* interface [IVideoCollection](../../ivideocollection)
* classe [Presentation](../../presentation)
* espace de noms [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: généré par xmldocmd pour Aspose.Slides.dll -->