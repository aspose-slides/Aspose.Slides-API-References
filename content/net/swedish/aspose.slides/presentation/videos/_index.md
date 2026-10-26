---
title: Videos
second_title: Aspose.Sildes för .NET API-referens
description: Returnerar samlingen av alla inbäddade videofiler i presentationen. Read-only IVideoCollectionaspose.slides/ivideocollection.
type: docs
weight: 290
url: /sv/aspose.slides/presentation/videos/
---
## Presentation.Videos egenskap

Returnerar samlingen av alla inbäddade videofiler i presentationen. Skrivskyddad [`IVideoCollection`](../../ivideocollection).

```csharp
public IVideoCollection Videos { get; }
```

### Exempel

Följande exempel visar hur man skapar en inbäddad Video Frame i en PowerPoint-presentation.

```csharp
// Instansiera Presentation-klassen som representerar PPTX
using (Presentation pres = new Presentation())
{
    // Hämta den första bilden
    ISlide sld = pres.Slides[0];
    // Bädda in video i presentationen
    IVideo vid = pres.Videos.AddVideo(new FileStream("Wildlife.mp4", FileMode.Open));
    // Lägg till videoramen
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 350, vid);
    // Tilldela video till videoramen
    vf.EmbeddedVideo = vid;
    // Ställ in uppspelningsläge och volym för videon
    vf.PlayMode = VideoPlayModePreset.Auto;
    vf.Volume = AudioVolumeMode.Loud;
    // Skriv PPTX-filen till disk
    pres.Save("VideoFrame_out.pptx", SaveFormat.Pptx);
}
```

Följande exempel visar hur man lägger till en video genom att ange sökvägen till videofilen direkt i metoden AddVideoFrame för en PowerPoint-presentation.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    ISlide sld = pres.Slides[0];
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 150, "video1.avi");
}
```

Följande exempel visar hur man lägger till en stor fil via BLOB till en presentation.

```csharp
[C#]
const string pathToVeryLargeVideo = "veryLargeVideo.avi";
// Skapar en ny presentation som videon kommer att läggas till i
using (Presentation pres = new Presentation())
{
    using (FileStream fileStream = new FileStream(pathToVeryLargeVideo, FileMode.Open))
    {
        // Låt oss lägga till videon i presentationen - vi valde KeepLocked-beteendet eftersom vi
        // inte har för avsikt att komma åt filen "veryLargeVideo.avi".
        IVideo video = pres.Videos.AddVideo(fileStream, LoadingStreamBehavior.KeepLocked);
        pres.Slides[0].Shapes.AddVideoFrame(0, 0, 480, 270, video);
        // Sparar presentationen. När en stor presentation skrivs ut, förblir minnesförbrukningen
        // låg under hela pres-objektets livscykel
        pres.Save("presentationWithLargeVideo.pptx", SaveFormat.Pptx);
    }
}
```

Följande exempel visar hur man exporterar en stor fil via BLOB från en PowerPoint-presentation.

```csharp
[C#]
const string hugePresentationWithAudiosAndVideosFile = @"Large  Video File Test1.pptx";
LoadOptions loadOptions = new LoadOptions
{
	BlobManagementOptions = {
		// Låser källfilen och LÄSER INTE in i minnet
		PresentationLockingBehavior = PresentationLockingBehavior.KeepLocked,
	}
};
// Skapar en Presentation-instans, låser filen "hugePresentationWithAudiosAndVideos.pptx".
using (Presentation pres = new Presentation(hugePresentationWithAudiosAndVideosFile, loadOptions))
{
	// Låt oss spara varje video till en fil. För att undvika hög minnesanvändning behöver vi en buffert som kommer att användas
	// för att överföra data från presentationens videoström till en ström för en ny skapad videofil.
	byte[] buffer = new byte[8 * 1024];
	// Itererar genom videorna
	for (var index = 0; index < pres.Videos.Count; index++)
	{
		IVideo video = pres.Videos[index];
		// Öppnar presentationens videoström. Observera att vi med avsikt undvek att komma åt egenskaper
		// som video.BinaryData - eftersom denna egenskap returnerar en byte-array som innehåller en hel video, vilket då
		// får bytes att läsas in i minnet. Vi använder video.GetStream, som returnerar en Stream - och LÄSER INTE
		//  kräver att vi laddar hela videon i minnet.
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
		// Minnesanvändningen kommer att förbli låg oavsett videons eller presentationens storlek,
	}
	// Vid behov kan du tillämpa samma steg för ljudfiler.
}
```

Följande exempel visar hur man lägger till en hyperlänk till en video i en PowerPoint-presentation.

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

Följande exempel visar hur man skapar en Video Frame med video från en webbkälla i en PowerPoint-presentation.

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
    // lägg till videoFrame
    IVideoFrame videoFrame = pres.Slides[0].Shapes.AddVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
    videoFrame.PlayMode = VideoPlayModePreset.Auto;
    // ladda miniatyrbild
    using (WebClient client = new WebClient())
    {
        string thumbnailUri = "http://img.youtube.com/vi/" + videoId + "/hqdefault.jpg";
        videoFrame.PictureFormat.Picture.Image = pres.Images.AddImage(client.DownloadData(thumbnailUri));
    }
}
```

Följande exempel visar hur man extraherar video från en bild i en PowerPoint-presentation.

```csharp
[C#]
// Instansiera ett Presentation-objekt som representerar en presentationsfil
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

### Se även

* gränssnitt [IVideoCollection](../../ivideocollection)
* klass [Presentation](../../presentation)
* namnrymd [Aspose.Slides](../../presentation)
* samling [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->