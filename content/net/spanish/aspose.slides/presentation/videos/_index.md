---
title: Videos
second_title: Aspose.Slides para .NET API Reference
description: Devuelve la colección de todos los archivos de video incrustados en la presentación. Solo lectura IVideoCollectionaspose.slides/ivideocollection.
type: docs
weight: 280
url: /es/aspose.slides/presentation/videos/
---

## Propiedad Presentation.Videos

Devuelve la colección de todos los archivos de video incrustados en la presentación. Solo lectura [`IVideoCollection`](../../ivideocollection).

```csharp
public IVideoCollection Videos { get; }
```

### Ejemplos

Los siguientes ejemplos muestran cómo crear un Marco de Video incrustado en una Presentación de PowerPoint.

```csharp
[C#]
// Instanciar la clase Presentation que representa el PPTX
using (Presentation pres = new Presentation())
{
    // Obtener la primera diapositiva
    ISlide sld = pres.Slides[0];
    // Incrustar video dentro de la presentación
    IVideo vid = pres.Videos.AddVideo(new FileStream("Wildlife.mp4", FileMode.Open));
    // Agregar Marco de Video
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 350, vid);
    // Establecer video en el Marco de Video
    vf.EmbeddedVideo = vid;
    // Establecer modo de reproducción y volumen del Video
    vf.PlayMode = VideoPlayModePreset.Auto;
    vf.Volume = AudioVolumeMode.Loud;
    // Escribir el archivo PPTX en disco
    pres.Save("VideoFrame_out.pptx", SaveFormat.Pptx);
}
```

Los siguientes ejemplos muestran cómo agregar un video pasando la ruta del archivo de video directamente al método AddVideoFrame para la Presentación de PowerPoint.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    ISlide sld = pres.Slides[0];
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 150, "video1.avi");
}
```

Los siguientes ejemplos muestran cómo agregar un archivo grande a través de BLOB a una Presentación.

```csharp
[C#]
const string pathToVeryLargeVideo = "veryLargeVideo.avi";
// Crea una nueva presentación a la que se añadirá el video
using (Presentation pres = new Presentation())
{
    using (FileStream fileStream = new FileStream(pathToVeryLargeVideo, FileMode.Open))
    {
        // Vamos a agregar el video a la presentación - elegimos el comportamiento KeepLocked porque no
        // pretendemos acceder al archivo "veryLargeVideo.avi".
        IVideo video = pres.Videos.AddVideo(fileStream, LoadingStreamBehavior.KeepLocked);
        pres.Slides[0].Shapes.AddVideoFrame(0, 0, 480, 270, video);
        // Guarda la presentación. Mientras se genera una presentación grande, el consumo de memoria
        // se mantiene bajo durante el ciclo de vida del objeto pres
        pres.Save("presentationWithLargeVideo.pptx", SaveFormat.Pptx);
    }
}
```

Los siguientes ejemplos muestran cómo exportar archivos grandes a través de BLOB desde una Presentación de PowerPoint.

```csharp
[C#]
const string hugePresentationWithAudiosAndVideosFile = @"Large  Video File Test1.pptx";
LoadOptions loadOptions = new LoadOptions
{
	BlobManagementOptions = {
		// Bloquea el archivo de origen y NO lo carga en memoria
		PresentationLockingBehavior = PresentationLockingBehavior.KeepLocked,
	}
};
// Crea una instancia de Presentation, bloquea el archivo "hugePresentationWithAudiosAndVideos.pptx".
using (Presentation pres = new Presentation(hugePresentationWithAudiosAndVideosFile, loadOptions))
{
	// Vamos a guardar cada video en un archivo. Para prevenir un alto uso de memoria, necesitamos un búfer que se usará
	// para transferir los datos del flujo de video de la presentación a un flujo para un archivo de video recién creado.
	byte[] buffer = new byte[8 * 1024];
	// Itera a través de los videos
	for (var index = 0; index < pres.Videos.Count; index++)
	{
		IVideo video = pres.Videos[index];
		// Abre el flujo de video de la presentación. Tenga en cuenta que evitamos intencionalmente acceder a propiedades
		// como video.BinaryData - porque esta propiedad devuelve un array de bytes que contiene un video completo, que luego
		// causa que los bytes se carguen en memoria. Usamos video.GetStream, que devolverá Stream - y NO
		// requiere que carguemos todo el video en la memoria.
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
		// El consumo de memoria se mantendrá bajo independientemente del tamaño del video o de la presentación,
	}
	// Si es necesario, puede aplicar los mismos pasos para archivos de audio.
}
```

Los siguientes ejemplos muestran cómo agregar un hipervínculo a un video en una Presentación de PowerPoint.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    IVideo video = pres.Videos.AddVideo(File.ReadAllBytes("video.avi"));
    IVideoFrame videoFrame = pres.Slides[0].Shapes.AddVideoFrame(10, 10, 100, 100, video);
    videoFrame.HyperlinkClick = new Hyperlink("https://www.aspose.com/");
    videoFrame.HyperlinkClick.Tooltip = "Más del 70% de las empresas Fortune 100 confían en las API de Aspose";
    pres.Save("pres-out.pptx", SaveFormat.Pptx);
}
```

Los siguientes ejemplos muestran cómo crear un Marco de Video con Video de una Fuente Web en una Presentación de PowerPoint.

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
    //agregar videoFrame
    IVideoFrame videoFrame = pres.Slides[0].Shapes.AddVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
    videoFrame.PlayMode = VideoPlayModePreset.Auto;
    //cargar miniatura
    using (WebClient client = new WebClient())
    {
        string thumbnailUri = "http://img.youtube.com/vi/" + videoId + "/hqdefault.jpg";
        videoFrame.PictureFormat.Picture.Image = pres.Images.AddImage(client.DownloadData(thumbnailUri));
    }
}
```

Los siguientes ejemplos muestran cómo extraer Video de una diapositiva de una Presentación de PowerPoint.

```csharp
[C#]
// Instanciar un objeto Presentation que representa un archivo de presentación
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

### Ver También

* interfaz [IVideoCollection](../../ivideocollection)
* clase [Presentation](../../presentation)
* espacio de nombres [Aspose.Slides](../../presentation)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->