---
title: Videos
second_title: Aspose.Sildes für .NET API Referenz
description: Gibt die Sammlung aller eingebetteten Videodateien in der Präsentation zurück. Schreibgeschützte IVideoCollectionaspose.slides/ivideocollection.
type: docs
weight: 280
url: /de/aspose.slides/presentation/videos/
---

## Presentation.Videos Eigenschaft

Gibt die Sammlung aller eingebetteten Videodateien in der Präsentation zurück. Schreibgeschützt [`IVideoCollection`](../../ivideocollection).

```csharp
public IVideoCollection Videos { get; }
```

### Beispiele

Die folgenden Beispiele zeigen, wie man einen eingebetteten Video-Frame in einer PowerPoint-Präsentation erstellt.

```csharp
[C#]
// Instanziieren der Presentation-Klasse, die das PPTX darstellt
using (Presentation pres = new Presentation())
{
    // Erhalten der ersten Folie
    ISlide sld = pres.Slides[0];
    // Videodatei in die Präsentation einfügen
    IVideo vid = pres.Videos.AddVideo(new FileStream("Wildlife.mp4", FileMode.Open));
    // Video-Frame hinzufügen
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 350, vid);
    // Video zum Video-Frame setzen
    vf.EmbeddedVideo = vid;
    // Wiedergabemodus und Lautstärke des Videos einstellen
    vf.PlayMode = VideoPlayModePreset.Auto;
    vf.Volume = AudioVolumeMode.Loud;
    // Die PPTX-Datei auf die Festplatte schreiben
    pres.Save("VideoFrame_out.pptx", SaveFormat.Pptx);
}
```

Die folgenden Beispiele zeigen, wie man ein Video hinzufügt, indem man den Pfad zur Videodatei direkt in die Methode AddVideoFrame für eine PowerPoint-Präsentation übergibt.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    ISlide sld = pres.Slides[0];
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 150, "video1.avi");
}
```

Die folgenden Beispiele zeigen, wie man eine große Datei über BLOB in eine Präsentation hinzufügt.

```csharp
[C#]
const string pathToVeryLargeVideo = "veryLargeVideo.avi";
// Erstellt eine neue Präsentation, zu der das Video hinzugefügt wird
using (Presentation pres = new Presentation())
{
    using (FileStream fileStream = new FileStream(pathToVeryLargeVideo, FileMode.Open))
    {
        // Lassen Sie uns das Video zur Präsentation hinzufügen – wir haben das Verhalten KeepLocked gewählt, da wir
        // nicht beabsichtigen, auf die Datei "veryLargeVideo.avi" zuzugreifen.
        IVideo video = pres.Videos.AddVideo(fileStream, LoadingStreamBehavior.KeepLocked);
        pres.Slides[0].Shapes.AddVideoFrame(0, 0, 480, 270, video);
        // Speichert die Präsentation. Während eine große Präsentation ausgegeben wird, bleibt der Speicherverbrauch
        // während des Lebenszyklus des pres-Objekts niedrig
        pres.Save("presentationWithLargeVideo.pptx", SaveFormat.Pptx);
    }
}
```

Die folgenden Beispiele zeigen, wie man eine große Datei über BLOB aus einer PowerPoint-Präsentation exportiert.

```csharp
[C#]
const string hugePresentationWithAudiosAndVideosFile = @"Large  Video File Test1.pptx";
LoadOptions loadOptions = new LoadOptions
{
	BlobManagementOptions = {
		// Sperrt die Quelldatei und lädt sie NICHT in den Speicher
		PresentationLockingBehavior = PresentationLockingBehavior.KeepLocked,
	}
};
// Erstellt eine Präsentationsinstanz, sperrt die Datei "hugePresentationWithAudiosAndVideos.pptx".
using (Presentation pres = new Presentation(hugePresentationWithAudiosAndVideosFile, loadOptions))
{
	// Lassen Sie uns jedes Video in eine Datei speichern. Um einen hohen Speicherverbrauch zu vermeiden, benötigen wir einen Puffer, der verwendet wird
	// um die Daten vom Videostream der Präsentation in einen Stream für eine neu erstellte Videodatei zu übertragen.
	byte[] buffer = new byte[8 * 1024];
	// Iteriert durch die Videos
	for (var index = 0; index < pres.Videos.Count; index++)
	{
		IVideo video = pres.Videos[index];
		// Öffnet den Videostream der Präsentation. Bitte beachten Sie, dass wir absichtlich den Zugriff auf Eigenschaften vermieden haben,
		// wie z.B. video.BinaryData - weil diese Eigenschaft ein Byte-Array zurückgibt, das das gesamte Video enthält, was dann
		// dazu führt, dass Bytes in den Speicher geladen werden. Wir verwenden video.GetStream, das Stream zurückgibt - und nicht
		// erfordert, dass wir das gesamte Video in den Speicher laden.
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
		// Der Speicherverbrauch bleibt gering, unabhängig von der Größe des Videos oder der Präsentation,
	}
	// Bei Bedarf können Sie dieselben Schritte für Audiodateien anwenden.
}
```

Die folgenden Beispiele zeigen, wie man einen Hyperlink zu einem Video in einer PowerPoint-Präsentation hinzufügt.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    IVideo video = pres.Videos.AddVideo(File.ReadAllBytes("video.avi"));
    IVideoFrame videoFrame = pres.Slides[0].Shapes.AddVideoFrame(10, 10, 100, 100, video);
    videoFrame.HyperlinkClick = new Hyperlink("https://www.aspose.com/");
    videoFrame.HyperlinkClick.Tooltip = "Mehr als 70% der Fortune 100 Unternehmen vertrauen Aspose APIs";
    pres.Save("pres-out.pptx", SaveFormat.Pptx);
}
```

Die folgenden Beispiele zeigen, wie man einen Video-Frame mit Video aus einer Webquelle in einer PowerPoint-Präsentation erstellt.

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
    //VideoFrame hinzufügen
    IVideoFrame videoFrame = pres.Slides[0].Shapes.AddVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
    videoFrame.PlayMode = VideoPlayModePreset.Auto;
    //Thumbnail laden
    using (WebClient client = new WebClient())
    {
        string thumbnailUri = "http://img.youtube.com/vi/" + videoId + "/hqdefault.jpg";
        videoFrame.PictureFormat.Picture.Image = pres.Images.AddImage(client.DownloadData(thumbnailUri));
    }
}
```

Die folgenden Beispiele zeigen, wie man ein Video aus einer Folie einer PowerPoint-Präsentation extrahiert.

```csharp
[C#]
// Instanziieren eines Presentation-Objekts, das eine Präsentationsdatei darstellt
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

### Siehe Auch

* Schnittstelle [IVideoCollection](../../ivideocollection)
* Klasse [Presentation](../../presentation)
* Namensraum [Aspose.Slides](../../presentation)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->