---
title: Videos
second_title: Aspose.Sildes dla .NET referencja API
description: Zwraca kolekcję wszystkich osadzonych plików wideo w prezentacji. Tylko do odczytu IVideoCollectionaspose.slides/ivideocollection.
type: docs
weight: 290
url: /pl/aspose.slides/presentation/videos/
---
## Właściwość Presentation.Videos

Zwraca kolekcję wszystkich osadzonych plików wideo w prezentacji. Tylko do odczytu [`IVideoCollection`](../../ivideocollection).

```csharp
public IVideoCollection Videos { get; }
```

### Przykłady

Poniższe przykłady pokazują, jak utworzyć osadzoną klatkę wideo w prezentacji PowerPoint.

```csharp
[C#]
// Utwórz instancję klasy Presentation, która reprezentuje plik PPTX
using (Presentation pres = new Presentation())
{
    // Pobierz pierwszy slajd
    ISlide sld = pres.Slides[0];
    // Osadź wideo w prezentacji
    IVideo vid = pres.Videos.AddVideo(new FileStream("Wildlife.mp4", FileMode.Open));
    // Dodaj klatkę wideo
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 350, vid);
    // Ustaw wideo w klatce wideo
    vf.EmbeddedVideo = vid;
    // Ustaw tryb odtwarzania i głośność wideo
    vf.PlayMode = VideoPlayModePreset.Auto;
    vf.Volume = AudioVolumeMode.Loud;
    // Zapisz plik PPTX na dysku
    pres.Save("VideoFrame_out.pptx", SaveFormat.Pptx);
}
```

Poniższe przykłady pokazują, jak dodać wideo, podając ścieżkę do pliku wideo bezpośrednio w metodzie AddVideoFrame w prezentacji PowerPoint.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    ISlide sld = pres.Slides[0];
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 150, "video1.avi");
}
```

Poniższe przykłady pokazują, jak dodać duży plik za pomocą BLOB do prezentacji.

```csharp
[C#]
const string pathToVeryLargeVideo = "veryLargeVideo.avi";
// Tworzy nową prezentację, do której zostanie dodane wideo
using (Presentation pres = new Presentation())
{
    using (FileStream fileStream = new FileStream(pathToVeryLargeVideo, FileMode.Open))
    {
        // Dodajmy wideo do prezentacji – wybraliśmy zachowanie KeepLocked, ponieważ
        // nie zamierzamy uzyskiwać dostępu do pliku "veryLargeVideo.avi".
        IVideo video = pres.Videos.AddVideo(fileStream, LoadingStreamBehavior.KeepLocked);
        pres.Slides[0].Shapes.AddVideoFrame(0, 0, 480, 270, video);
        // Zapisuje prezentację. Podczas generowania dużej prezentacji
        // zużycie pamięci pozostaje niskie w całym cyklu życia obiektu pres
        pres.Save("presentationWithLargeVideo.pptx", SaveFormat.Pptx);
    }
}
```

Poniższe przykłady pokazują, jak wyeksportować duży plik za pomocą BLOB z prezentacji PowerPoint.

```csharp
[C#]
const string hugePresentationWithAudiosAndVideosFile = @"Large  Video File Test1.pptx";
LoadOptions loadOptions = new LoadOptions
{
	BlobManagementOptions = {
		// Blokuje plik źródłowy i nie ładuje go do pamięci
		PresentationLockingBehavior = PresentationLockingBehavior.KeepLocked,
	}
};
// Tworzy instancję klasy Presentation, blokuje plik "hugePresentationWithAudiosAndVideos.pptx".
using (Presentation pres = new Presentation(hugePresentationWithAudiosAndVideosFile, loadOptions))
{
	// Zapiszmy każde wideo do pliku. Aby zapobiec dużemu zużyciu pamięci, potrzebny jest bufor, który będzie używany
	// do przenoszenia danych z strumienia wideo prezentacji do strumienia nowo utworzonego pliku wideo.
	byte[] buffer = new byte[8 * 1024];
	// Iteruje po wideo
	for (var index = 0; index < pres.Videos.Count; index++)
	{
		IVideo video = pres.Videos[index];
		// Otwiera strumień wideo prezentacji. Należy zauważyć, że celowo unikamy dostępu do właściwości
		// takich jak video.BinaryData – ponieważ ta właściwość zwraca tablicę bajtów zawierającą pełne wideo, co
		// powoduje załadowanie bajtów do pamięci. Używamy video.GetStream, który zwróci Stream – i nie
		//  wymaga załadowania całego wideo do pamięci.
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
		// Zużycie pamięci pozostanie niskie bez względu na rozmiar wideo lub prezentacji,
	}
	// W razie potrzeby można zastosować te same kroki dla plików audio.
}
```

Poniższe przykłady pokazują, jak dodać hiperłącze do wideo w prezentacji PowerPoint.

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

Poniższe przykłady pokazują, jak utworzyć klatkę wideo z wideo z źródła internetowego w prezentacji PowerPoint.

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
    //dodaj klatkę wideo
    IVideoFrame videoFrame = pres.Slides[0].Shapes.AddVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
    videoFrame.PlayMode = VideoPlayModePreset.Auto;
    //załaduj miniaturkę
    using (WebClient client = new WebClient())
    {
        string thumbnailUri = "http://img.youtube.com/vi/" + videoId + "/hqdefault.jpg";
        videoFrame.PictureFormat.Picture.Image = pres.Images.AddImage(client.DownloadData(thumbnailUri));
    }
}
```

Poniższe przykłady pokazują, jak wyodrębnić wideo ze slajdu prezentacji PowerPoint.

```csharp
[C#]
// Utwórz obiekt Presentation, który reprezentuje plik prezentacji
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

### Zobacz także

* interfejs [IVideoCollection](../../ivideocollection)
* klasa [Presentation](../../presentation)
* przestrzeń nazw [Aspose.Slides](../../presentation)
* zestaw [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->