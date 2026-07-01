---
title: Videos
second_title: Riferimento API di Aspose.Slides per .NET
description: Restituisce la raccolta di tutti i file video incorporati nella presentazione. Solo lettura IVideoCollectionaspose.slides/ivideocollection.
type: docs
weight: 290
url: /it/aspose.slides/presentation/videos/
---
## Presentation.Videos proprietà

Restituisce la raccolta di tutti i file video incorporati nella presentazione. Solo lettura [`IVideoCollection`](../../ivideocollection).

```csharp
public IVideoCollection Videos { get; }
```

### Esempi

Gli esempi seguenti mostrano come creare un Video Frame incorporato in una Presentazione PowerPoint.

```csharp
[C#]
// Istanzia la classe Presentation che rappresenta il PPTX
using (Presentation pres = new Presentation())
{
    // Ottieni la prima diapositiva
    ISlide sld = pres.Slides[0];
    // Inserisci video nella presentazione
    IVideo vid = pres.Videos.AddVideo(new FileStream("Wildlife.mp4", FileMode.Open));
    // Aggiungi Video Frame
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 350, vid);
    // Imposta il video nel Video Frame
    vf.EmbeddedVideo = vid;
    // Imposta la modalità di riproduzione e il volume del video
    vf.PlayMode = VideoPlayModePreset.Auto;
    vf.Volume = AudioVolumeMode.Loud;
    // Scrivi il file PPTX su disco
    pres.Save("VideoFrame_out.pptx", SaveFormat.Pptx);
}
```

Gli esempi seguenti mostrano come aggiungere un video specificando il percorso del file video direttamente nel metodo AddVideoFrame per una Presentazione PowerPoint.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    ISlide sld = pres.Slides[0];
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 150, "video1.avi");
}
```

Gli esempi seguenti mostrano come aggiungere un file di grandi dimensioni tramite BLOB a una Presentazione.

```csharp
[C#]
const string pathToVeryLargeVideo = "veryLargeVideo.avi";
// Crea una nuova presentazione a cui verrà aggiunto il video
using (Presentation pres = new Presentation())
{
    using (FileStream fileStream = new FileStream(pathToVeryLargeVideo, FileMode.Open))
    {
        // Aggiungiamo il video alla presentazione - abbiamo scelto il comportamento KeepLocked perché noi
//non intendiamo accedere al file "veryLargeVideo.avi".
        IVideo video = pres.Videos.AddVideo(fileStream, LoadingStreamBehavior.KeepLocked);
        pres.Slides[0].Shapes.AddVideoFrame(0, 0, 480, 270, video);
        // Salva la presentazione. Mentre una presentazione di grandi dimensioni viene esportata, il consumo di memoria
        // rimane basso durante il ciclo di vita dell'oggetto pres
        pres.Save("presentationWithLargeVideo.pptx", SaveFormat.Pptx);
    }
}
```

Gli esempi seguenti mostrano come esportare un file di grandi dimensioni tramite BLOB da una Presentazione PowerPoint.

```csharp
[C#]
const string hugePresentationWithAudiosAndVideosFile = @"Large  Video File Test1.pptx";
LoadOptions loadOptions = new LoadOptions
{
	BlobManagementOptions = {
		// Blocca il file sorgente e NON lo carica in memoria
		PresentationLockingBehavior = PresentationLockingBehavior.KeepLocked,
	}
};
// Crea un'istanza di Presentation, blocca il file "hugePresentationWithAudiosAndVideos.pptx".
using (Presentation pres = new Presentation(hugePresentationWithAudiosAndVideosFile, loadOptions))
{
	// Salviamo ogni video in un file. Per evitare un alto consumo di memoria, è necessario un buffer che verrà usato
	// per trasferire i dati dallo stream video della presentazione a uno stream per il nuovo file video.
	byte[] buffer = new byte[8 * 1024];
	// Iterates through the videos
	for (var index = 0; index < pres.Videos.Count; index++)
	{
		IVideo video = pres.Videos[index];
		// Apre lo stream video della presentazione. Si prega di notare che abbiamo intenzionalmente evitato di accedere alle proprietà
		// come video.BinaryData - perché questa proprietà restituisce un array di byte contenente l'intero video, che quindi
		// causa il caricamento dei byte in memoria. Usiamo video.GetStream, che restituirà uno Stream - e NON
		//  richiede di caricare l'intero video in memoria.
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
		// Il consumo di memoria rimarrà basso indipendentemente dalle dimensioni del video o della presentazione,
	}
	// Se necessario, è possibile applicare gli stessi passaggi per i file audio.
}
```

Gli esempi seguenti mostrano come aggiungere un collegamento ipertestuale a un video in una Presentazione PowerPoint.

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

Gli esempi seguenti mostrano come creare un Video Frame con video da una fonte Web in una Presentazione PowerPoint.

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
    //add videoFrame
    IVideoFrame videoFrame = pres.Slides[0].Shapes.AddVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
    videoFrame.PlayMode = VideoPlayModePreset.Auto;
    //load thumbnail
    using (WebClient client = new WebClient())
    {
        string thumbnailUri = "http://img.youtube.com/vi/" + videoId + "/hqdefault.jpg";
        videoFrame.PictureFormat.Picture.Image = pres.Images.AddImage(client.DownloadData(thumbnailUri));
    }
}
```

Gli esempi seguenti mostrano come estrarre un Video da una diapositiva di una Presentazione PowerPoint.

```csharp
[C#]
// Istanzia un oggetto Presentation che rappresenta un file di presentazione
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

### Vedi anche

* interfaccia [IVideoCollection](../../ivideocollection)
* classe [Presentation](../../presentation)
* spazio dei nomi [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->