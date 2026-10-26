---
title: Videos
second_title: Aspose.Sildes voor .NET API-referentie
description: Retourneert de collectie van alle ingebedde videobestanden in de presentatie. Alleen-lezen IVideoCollectionaspose.slides/ivideocollection.
type: docs
weight: 290
url: /nl/aspose.slides/presentation/videos/
---
## Presentation.Videos eigenschap

Retourneert de collectie van alle ingebedde videobestanden in de presentatie. Alleen-lezen [`IVideoCollection`](../../ivideocollection).

```csharp
public IVideoCollection Videos { get; }
```

### Voorbeelden

De volgende voorbeelden laten zien hoe je een ingebedde Video Frame maakt in een PowerPoint-presentatie.

```csharp
[C#]
// Instantie van de Presentation-klasse die de PPTX vertegenwoordigt
using (Presentation pres = new Presentation())
{
    // Haal de eerste dia op
    ISlide sld = pres.Slides[0];
    // Video insluiten in de presentatie
    IVideo vid = pres.Videos.AddVideo(new FileStream("Wildlife.mp4", FileMode.Open));
    // Videoframe toevoegen
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 350, vid);
    // Video instellen op Video Frame
    vf.EmbeddedVideo = vid;
    // Speelmodus en volume van de video instellen
    vf.PlayMode = VideoPlayModePreset.Auto;
    vf.Volume = AudioVolumeMode.Loud;
    // Schrijf het PPTX-bestand naar schijf
    pres.Save("VideoFrame_out.pptx", SaveFormat.Pptx);
}
```

De volgende voorbeelden laten zien hoe je een video toevoegt door het pad naar het videobestand direct door te geven aan de AddVideoFrame-methode voor een PowerPoint-presentatie.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    ISlide sld = pres.Slides[0];
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 150, "video1.avi");
}
```

De volgende voorbeelden laten zien hoe je een groot bestand via BLOB toevoegt aan een presentatie.

```csharp
[C#]
const string pathToVeryLargeVideo = "veryLargeVideo.avi";
// Creëert een nieuwe presentatie waaraan de video zal worden toegevoegd
using (Presentation pres = new Presentation())
{
    using (FileStream fileStream = new FileStream(pathToVeryLargeVideo, FileMode.Open))
    {
        // Laten we de video aan de presentatie toevoegen - we hebben gekozen voor het KeepLocked-gedrag omdat we
        // niet van plan zijn het "veryLargeVideo.avi" bestand te benaderen.
        IVideo video = pres.Videos.AddVideo(fileStream, LoadingStreamBehavior.KeepLocked);
        pres.Slides[0].Shapes.AddVideoFrame(0, 0, 480, 270, video);
        // Slaat de presentatie op. Terwijl een grote presentatie wordt gegenereerd, blijft het geheugengebruik
        // laag gedurende de levensduur van het pres-object
        pres.Save("presentationWithLargeVideo.pptx", SaveFormat.Pptx);
    }
}
```

De volgende voorbeelden laten zien hoe je een groot bestand via BLOB exporteert vanuit een PowerPoint-presentatie.

```csharp
[C#]
const string hugePresentationWithAudiosAndVideosFile = @"Large  Video File Test1.pptx";
LoadOptions loadOptions = new LoadOptions
{
	BlobManagementOptions = {
		// Vergrendelt het bronbestand en laad het NIET in het geheugen
		PresentationLockingBehavior = PresentationLockingBehavior.KeepLocked,
	}
};
// Maakt een instantie van Presentation, vergrendelt het bestand "hugePresentationWithAudiosAndVideos.pptx".
using (Presentation pres = new Presentation(hugePresentationWithAudiosAndVideosFile, loadOptions))
{
	// Laten we elke video naar een bestand opslaan. Om hoog geheugenverbruik te voorkomen, hebben we een buffer nodig die zal worden gebruikt
	// om de gegevens van de videostream van de presentatie over te dragen naar een stream voor een nieuw aangemaakt videobestand.
	// Doorloopt de video's
	byte[] buffer = new byte[8 * 1024];
	for (var index = 0; index < pres.Videos.Count; index++)
	{
		IVideo video = pres.Videos[index];
		// Opent de videostream van de presentatie. Let op, we hebben opzettelijk vermeden om eigenschappen te benaderen
		// zoals video.BinaryData - omdat deze eigenschap een byte-array retourneert met een volledige video, wat vervolgens
		// ertoe leidt dat bytes in het geheugen worden geladen. We gebruiken video.GetStream, die een Stream retourneert - en laadt NIET
		//  vereist ons om de volledige video in het geheugen te laden.
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
		// Geheugengebruik blijft laag, ongeacht de grootte van de video of presentatie,
	}
	// Indien nodig kun je dezelfde stappen toepassen voor audiobestanden.
}
```

De volgende voorbeelden laten zien hoe je een hyperlink aan een video toevoegt in een PowerPoint-presentatie.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    IVideo video = pres.Videos.AddVideo(File.ReadAllBytes("video.avi"));
    IVideoFrame videoFrame = pres.Slides[0].Shapes.AddVideoFrame(10, 10, 100, 100, video);
    videoFrame.HyperlinkClick = new Hyperlink("https://www.aspose.com/");
    videoFrame.HyperlinkClick.Tooltip = "More than 70% Fortune 100 companies trust Aspose APIs";
    pres.Save("pres-out.pptx", SaveFormat.Pptx);
}
```

De volgende voorbeelden laten zien hoe je een Video Frame maakt met video van een webbron in een PowerPoint-presentatie.

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
    //videoFrame toevoegen
    IVideoFrame videoFrame = pres.Slides[0].Shapes.AddVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
    videoFrame.PlayMode = VideoPlayModePreset.Auto;
    //thumbnail laden
    using (WebClient client = new WebClient())
    {
        string thumbnailUri = "http://img.youtube.com/vi/" + videoId + "/hqdefault.jpg";
        videoFrame.PictureFormat.Picture.Image = pres.Images.AddImage(client.DownloadData(thumbnailUri));
    }
}
```

De volgende voorbeelden laten zien hoe je een Video extrahert uit een dia van een PowerPoint-presentatie.

```csharp
[C#]
// Instantieer een Presentation-object dat een presentatiebestand voorstelt
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

### Zie ook

* interface [IVideoCollection](../../ivideocollection)
* klasse [Presentation](../../presentation)
* naamruimte [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->