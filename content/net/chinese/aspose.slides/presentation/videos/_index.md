---
title: Videos
second_title: Aspose.Sildes for .NET API 参考
description: 返回演示文稿中所有嵌入视频文件的集合。只读 IVideoCollectionaspose.slides/ivideocollection。
type: docs
weight: 280
url: /zh/aspose.slides/presentation/videos/
---

## Presentation.Videos 属性

返回演示文稿中所有嵌入视频文件的集合。只读 [`IVideoCollection`](../../ivideocollection)。

```csharp
public IVideoCollection Videos { get; }
```

### 示例

以下示例展示了如何在 PowerPoint 演示文稿中创建嵌入式视频框架。

```csharp
[C#]
// 实例化表示 PPTX 的 Presentation 类
using (Presentation pres = new Presentation())
{
    // 获取第一张幻灯片
    ISlide sld = pres.Slides[0];
    // 在演示文稿中嵌入视频
    IVideo vid = pres.Videos.AddVideo(new FileStream("Wildlife.mp4", FileMode.Open));
    // 添加视频框架
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 350, vid);
    // 将视频设置为视频框架
    vf.EmbeddedVideo = vid;
    // 设置视频的播放模式和音量
    vf.PlayMode = VideoPlayModePreset.Auto;
    vf.Volume = AudioVolumeMode.Loud;
    // 将 PPTX 文件写入磁盘
    pres.Save("VideoFrame_out.pptx", SaveFormat.Pptx);
}
```

以下示例展示了如何直接将视频文件的路径传递给 AddVideoFrame 方法来添加视频到 PowerPoint 演示文稿。

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    ISlide sld = pres.Slides[0];
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 150, "video1.avi");
}
```

以下示例展示了如何通过 BLOB 向演示文稿添加大文件。

```csharp
[C#]
const string pathToVeryLargeVideo = "veryLargeVideo.avi";
// 创建一个新的演示文稿，视频将被添加到其中
using (Presentation pres = new Presentation())
{
    using (FileStream fileStream = new FileStream(pathToVeryLargeVideo, FileMode.Open))
    {
        // 我们选择保持锁定行为，因为我们不打算访问 "veryLargeVideo.avi" 文件。
        IVideo video = pres.Videos.AddVideo(fileStream, LoadingStreamBehavior.KeepLocked);
        pres.Slides[0].Shapes.AddVideoFrame(0, 0, 480, 270, video);
        // 保存演示文稿。尽管生成了一个大演示文稿，内存消耗在 pres 对象的整个生命周期中保持较低
        pres.Save("presentationWithLargeVideo.pptx", SaveFormat.Pptx);
    }
}
```

以下示例展示了如何通过 BLOB 从 PowerPoint 演示文稿中导出大文件。

```csharp
[C#]
const string hugePresentationWithAudiosAndVideosFile = @"Large  Video File Test1.pptx";
LoadOptions loadOptions = new LoadOptions
{
	BlobManagementOptions = {
		// 锁定源文件，并不将其载入内存
		PresentationLockingBehavior = PresentationLockingBehavior.KeepLocked,
	}
};
// 创建演示文稿实例，锁定 "hugePresentationWithAudiosAndVideos.pptx" 文件。
using (Presentation pres = new Presentation(hugePresentationWithAudiosAndVideosFile, loadOptions))
{
	// 我们将每个视频保存到文件。为了防止高内存使用，我们需要一个缓冲区，
	// 用于在演示文稿的视频流和新创建的视频文件的流之间传输数据。
	byte[] buffer = new byte[8 * 1024];
	// 迭代视频
	for (var index = 0; index < pres.Videos.Count; index++)
	{
		IVideo video = pres.Videos[index];
		// 打开演示文稿视频流。请注意，我们故意避免访问像 video.BinaryData
		// 这样的属性，因为这个属性返回一个包含完整视频的字节数组，这会导致字节被加载到内存中。 
		// 我们使用 video.GetStream，将返回 Stream 并且不需要将整个视频加载到内存中。
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
		// 无论视频或演示文稿的大小如何，内存消耗将保持在较低水平
	}
	// 如有必要，您可以对音频文件执行相同的步骤。
}
```

以下示例展示了如何在 PowerPoint 演示文稿中为视频添加超链接。

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    IVideo video = pres.Videos.AddVideo(File.ReadAllBytes("video.avi"));
    IVideoFrame videoFrame = pres.Slides[0].Shapes.AddVideoFrame(10, 10, 100, 100, video);
    videoFrame.HyperlinkClick = new Hyperlink("https://www.aspose.com/");
    videoFrame.HyperlinkClick.Tooltip = "超过 70% 的财富 100 强公司信任 Aspose API";
    pres.Save("pres-out.pptx", SaveFormat.Pptx);
}
```

以下示例展示了如何在 PowerPoint 演示文稿中从 Web 源创建视频框架。

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
    // 添加视频框架
    IVideoFrame videoFrame = pres.Slides[0].Shapes.AddVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
    videoFrame.PlayMode = VideoPlayModePreset.Auto;
    // 加载缩略图
    using (WebClient client = new WebClient())
    {
        string thumbnailUri = "http://img.youtube.com/vi/" + videoId + "/hqdefault.jpg";
        videoFrame.PictureFormat.Picture.Image = pres.Images.AddImage(client.DownloadData(thumbnailUri));
    }
}
```

以下示例展示了如何从 PowerPoint 演示文稿的幻灯片中提取视频。

```csharp
[C#]
// 实例化一个表示演示文稿文件的 Presentation 对象
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

### 另见

* 接口 [IVideoCollection](../../ivideocollection)
* 类 [Presentation](../../presentation)
* 命名空间 [Aspose.Slides](../../presentation)
* 程序集 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->