---
title: Videos
second_title: Aspose.Sildes for .NET API 參考
description: 傳回簡報中所有嵌入式影片檔案的集合。唯讀 IVideoCollectionaspose.slides/ivideocollection.
type: docs
weight: 290
url: /zh-hant/aspose.slides/presentation/videos/
---
## Presentation.Videos 屬性

傳回簡報中所有嵌入式 video files 的集合。唯讀 [`IVideoCollection`](../../ivideocollection)。

```csharp
public IVideoCollection Videos { get; }
```

### 範例

以下範例說明如何在 PowerPoint 簡報中建立嵌入式 Video Frame。

```csharp
[C#]
// 實例化代表 PPTX 的 Presentation 類別
using (Presentation pres = new Presentation())
{
    // 取得第一張投影片
    ISlide sld = pres.Slides[0];
    // 在簡報中嵌入影片
    IVideo vid = pres.Videos.AddVideo(new FileStream("Wildlife.mp4", FileMode.Open));
    // 新增 Video Frame
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 350, vid);
    // 設定影片至 Video Frame
    vf.EmbeddedVideo = vid;
    // 設定影片的播放模式與音量
    vf.PlayMode = VideoPlayModePreset.Auto;
    vf.Volume = AudioVolumeMode.Loud;
    // 將 PPTX 檔案寫入磁碟
    pres.Save("VideoFrame_out.pptx", SaveFormat.Pptx);
}
```

以下範例說明如何將影片檔案路徑直接傳遞給 AddVideoFrame 方法，以在 PowerPoint 簡報中新增影片。

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    ISlide sld = pres.Slides[0];
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 150, "video1.avi");
}
```

以下範例說明如何透過 BLOB 將大型檔案新增至 Presentation。

```csharp
[C#]
const string pathToVeryLargeVideo = "veryLargeVideo.avi";
// 建立一個將加入影片的新簡報
using (Presentation pres = new Presentation())
{
    using (FileStream fileStream = new FileStream(pathToVeryLargeVideo, FileMode.Open))
    {
        // 讓我們將影片加入簡報 - 我們選擇 KeepLocked 行為因為我們
        // 不打算存取 "veryLargeVideo.avi" 檔案。
        IVideo video = pres.Videos.AddVideo(fileStream, LoadingStreamBehavior.KeepLocked);
        pres.Slides[0].Shapes.AddVideoFrame(0, 0, 480, 270, video);
        // 儲存簡報。雖然輸出大型簡報，記憶體使用
        // 在 pres 物件的生命週期中保持低位
        pres.Save("presentationWithLargeVideo.pptx", SaveFormat.Pptx);
    }
}
```

以下範例說明如何從 PowerPoint 簡報中透過 BLOB 匯出大型檔案。

```csharp
[C#]
const string hugePresentationWithAudiosAndVideosFile = @"Large  Video File Test1.pptx";
LoadOptions loadOptions = new LoadOptions
{
	BlobManagementOptions = {
		// 鎖定來源檔案且不會將其載入記憶體
		PresentationLockingBehavior = PresentationLockingBehavior.KeepLocked,
	}
};
// 建立 Presentation 實例，並鎖定 "hugePresentationWithAudiosAndVideos.pptx" 檔案。
using (Presentation pres = new Presentation(hugePresentationWithAudiosAndVideosFile, loadOptions))
{
	// 讓我們將每個影片儲存為檔案。為了避免高記憶體使用，我們需要一個緩衝區來使用
	// 將簡報影片串流的資料傳輸到新建立的影片檔案的串流中。
	byte[] buffer = new byte[8 * 1024];
	// Iterates through the videos
	for (var index = 0; index < pres.Videos.Count; index++)
	{
		IVideo video = pres.Videos[index];
		// 開啟簡報的影片串流。請注意，我們刻意避免存取屬性
		// 如 video.BinaryData - 因為此屬性會回傳包含完整影片的位元組陣列，接著
		// 造成位元組被載入記憶體。我們使用 video.GetStream，它會回傳 Stream，且不會
		//  需要我們將整個影片載入記憶體。
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
		// 記憶體消耗將保持低位，無論影片或簡報的大小如何，
	}
	// 如有需要，您可以對音訊檔案套用相同步驟。
}
```

以下範例說明如何在 PowerPoint 簡報中為影片新增超連結。

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

以下範例說明如何在 PowerPoint 簡報中使用來自 Web Source 的影片建立 Video Frame。

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
    // 新增 videoFrame
    IVideoFrame videoFrame = pres.Slides[0].Shapes.AddVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
    videoFrame.PlayMode = VideoPlayModePreset.Auto;
    // 載入縮圖
    using (WebClient client = new WebClient())
    {
        string thumbnailUri = "http://img.youtube.com/vi/" + videoId + "/hqdefault.jpg";
        videoFrame.PictureFormat.Picture.Image = pres.Images.AddImage(client.DownloadData(thumbnailUri));
    }
}
```

以下範例說明如何從 PowerPoint 簡報的投影片中擷取 Video。

```csharp
[C#]
// 實例化一個代表簡報檔案的 Presentation 物件
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

### 另請參閱

* 介面 [IVideoCollection](../../ivideocollection)
* 類別 [Presentation](../../presentation)
* 命名空間 [Aspose.Slides](../../presentation)
* 組件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->