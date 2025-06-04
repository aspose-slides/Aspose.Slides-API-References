---
title: Videos
second_title: Aspose.Sildes для .NET API Reference
description: Возвращает коллекцию всех встроенных видеофайлов в презентации. Только для чтения IVideoCollection aspose.slides/ivideocollection.
type: docs
weight: 280
url: /ru/aspose.slides/presentation/videos/
---

## Presentation.Videos свойство

Возвращает коллекцию всех встроенных видеофайлов в презентации. Только для чтения [`IVideoCollection`](../../ivideocollection).

```csharp
public IVideoCollection Videos { get; }
```

### Примеры

Следующие примеры показывают, как создать встроенный видеофрейм в презентации PowerPoint.

```csharp
[C#]
// Создаем экземпляр класса Presentation, который представляет PPTX
using (Presentation pres = new Presentation())
{
    // Получаем первый слайд
    ISlide sld = pres.Slides[0];
    // Встраиваем видео в презентацию
    IVideo vid = pres.Videos.AddVideo(new FileStream("Wildlife.mp4", FileMode.Open));
    // Добавляем видеофрейм
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 350, vid);
    // Устанавливаем видео в видеофрейм
    vf.EmbeddedVideo = vid;
    // Устанавливаем режим воспроизведения и громкость видео
    vf.PlayMode = VideoPlayModePreset.Auto;
    vf.Volume = AudioVolumeMode.Loud;
    // Сохраняем PPTX файл на диск
    pres.Save("VideoFrame_out.pptx", SaveFormat.Pptx);
}
```

Следующие примеры показывают, как добавить видео, передав путь к видеофайлу непосредственно в метод AddVideoFrame для презентации PowerPoint.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    ISlide sld = pres.Slides[0];
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 150, "video1.avi");
}
```

Следующие примеры показывают, как добавить большой файл через BLOB в презентацию.

```csharp
[C#]
const string pathToVeryLargeVideo = "veryLargeVideo.avi";
// Создает новую презентацию, в которую будет добавлено видео
using (Presentation pres = new Presentation())
{
    using (FileStream fileStream = new FileStream(pathToVeryLargeVideo, FileMode.Open))
    {
        // Давайте добавим видео в презентацию - мы выбрали поведение KeepLocked, потому что мы не собираемся
        // обращаться к файлу "veryLargeVideo.avi".
        IVideo video = pres.Videos.AddVideo(fileStream, LoadingStreamBehavior.KeepLocked);
        pres.Slides[0].Shapes.AddVideoFrame(0, 0, 480, 270, video);
        // Сохраняет презентацию. В то время как большая презентация выводится, потребление памяти
        // остается низким на протяжении всего жизненного цикла объекта pres
        pres.Save("presentationWithLargeVideo.pptx", SaveFormat.Pptx);
    }
}
```

Следующие примеры показывают, как экспортировать большой файл через BLOB из презентации PowerPoint.

```csharp
[C#]
const string hugePresentationWithAudiosAndVideosFile = @"Large  Video File Test1.pptx";
LoadOptions loadOptions = new LoadOptions
{
	BlobManagementOptions = {
		// Блокирует исходный файл и НЕ загружает его в память
		PresentationLockingBehavior = PresentationLockingBehavior.KeepLocked,
	}
};
// Создает экземпляр презентации, блокирует файл "hugePresentationWithAudiosAndVideos.pptx".
using (Presentation pres = new Presentation(hugePresentationWithAudiosAndVideosFile, loadOptions))
{
	// Давайте сохраним каждое видео в файл. Чтобы предотвратить высокое потребление памяти, нам нужен буфер, который будет использоваться
	// для передачи данных из видеопотока презентации в поток для вновь создаваемого видеофайла.
	byte[] buffer = new byte[8 * 1024];
	// Итерация по видео
	for (var index = 0; index < pres.Videos.Count; index++)
	{
		IVideo video = pres.Videos[index];
		// Открывает видеопоток презентации. Обратите внимание, что мы специально избегали обращения к свойствам
		// таким как video.BinaryData - потому что это свойство возвращает массив байтов, содержащий полное видео, что затем
		// вызывает загрузку байтов в память. Мы используем video.GetStream, который вернет Stream - и НЕ
		// требует загрузки всего видео в память.
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
		// Потребление памяти останется низким независимо от размера видео или презентации,
	}
	// Если необходимо, вы можете применить те же шаги для аудиофайлов.
}
```

Следующие примеры показывают, как добавить гиперссылку на видео в презентации PowerPoint.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    IVideo video = pres.Videos.AddVideo(File.ReadAllBytes("video.avi"));
    IVideoFrame videoFrame = pres.Slides[0].Shapes.AddVideoFrame(10, 10, 100, 100, video);
    videoFrame.HyperlinkClick = new Hyperlink("https://www.aspose.com/");
    videoFrame.HyperlinkClick.Tooltip = "Более 70% компаний Fortune 100 доверяют API Aspose";
    pres.Save("pres-out.pptx", SaveFormat.Pptx);
}
```

Следующие примеры показывают, как создать видеофрейм с видео из веб-источника в презентации PowerPoint.

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
    // добавляем видеофрейм
    IVideoFrame videoFrame = pres.Slides[0].Shapes.AddVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
    videoFrame.PlayMode = VideoPlayModePreset.Auto;
    // загружаем миниатюру
    using (WebClient client = new WebClient())
    {
        string thumbnailUri = "http://img.youtube.com/vi/" + videoId + "/hqdefault.jpg";
        videoFrame.PictureFormat.Picture.Image = pres.Images.AddImage(client.DownloadData(thumbnailUri));
    }
}
```

Следующие примеры показывают, как извлечь видео из слайда презентации PowerPoint.

```csharp
[C#]
// Создаем объект Presentation, который представляет файл презентации
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

### См. также

* интерфейс [IVideoCollection](../../ivideocollection)
* класс [Presentation](../../presentation)
* пространство имен [Aspose.Slides](../../presentation)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->