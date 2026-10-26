---
title: Videos
second_title: Aspose.Sildes for .NET API 참조
description: 프레젠테이션에 포함된 모든 임베드된 비디오 파일 컬렉션을 반환합니다. 읽기 전용 IVideoCollectionaspose.slides/ivideocollection.
type: docs
weight: 290
url: /ko/aspose.slides/presentation/videos/
---
## Presentation.Videos 속성

프레젠테이션에 포함된 모든 임베드된 비디오 파일 컬렉션을 반환합니다. 읽기 전용 [`IVideoCollection`](../../ivideocollection).

```csharp
public IVideoCollection Videos { get; }
```

### 예제

다음 예제는 PowerPoint 프레젠테이션에서 임베드된 Video Frame을 만드는 방법을 보여줍니다.

```csharp
[C#]
// PPTX를 나타내는 Presentation 클래스를 인스턴스화합니다
using (Presentation pres = new Presentation())
{
    // 첫 번째 슬라이드를 가져옵니다
    ISlide sld = pres.Slides[0];
    // 프레젠테이션에 비디오를 삽입합니다
    IVideo vid = pres.Videos.AddVideo(new FileStream("Wildlife.mp4", FileMode.Open));
    // 비디오 프레임을 추가합니다
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 350, vid);
    // 비디오 프레임에 비디오를 설정합니다
    vf.EmbeddedVideo = vid;
    // 비디오의 재생 모드와 볼륨을 설정합니다
    vf.PlayMode = VideoPlayModePreset.Auto;
    vf.Volume = AudioVolumeMode.Loud;
    // PPTX 파일을 디스크에 저장합니다
    pres.Save("VideoFrame_out.pptx", SaveFormat.Pptx);
}
```

다음 예제는 PowerPoint 프레젠테이션의 AddVideoFrame 메서드에 비디오 파일 경로를 직접 전달하여 비디오를 추가하는 방법을 보여줍니다.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    ISlide sld = pres.Slides[0];
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 150, "video1.avi");
}
```

다음 예제는 BLOB을 통해 대용량 파일을 프레젠테이션에 추가하는 방법을 보여줍니다.

```csharp
[C#]
const string pathToVeryLargeVideo = "veryLargeVideo.avi";
// 비디오를 추가할 새 프레젠테이션을 생성합니다
using (Presentation pres = new Presentation())
{
    using (FileStream fileStream = new FileStream(pathToVeryLargeVideo, FileMode.Open))
    {
        // 비디오를 프레젠테이션에 추가합니다 - KeepLocked 동작을 선택한 이유는
        // "veryLargeVideo.avi" 파일에 접근할 의도가 없기 때문입니다.
        IVideo video = pres.Videos.AddVideo(fileStream, LoadingStreamBehavior.KeepLocked);
        pres.Slides[0].Shapes.AddVideoFrame(0, 0, 480, 270, video);
        // 프레젠테이션을 저장합니다. 큰 프레젠테이션이 출력되는 동안에도
        // pres 객체의 전체 수명 동안 메모리 사용량이 낮게 유지됩니다.
        pres.Save("presentationWithLargeVideo.pptx", SaveFormat.Pptx);
    }
}
```

다음 예제는 PowerPoint 프레젠테이션에서 BLOB을 통해 대용량 파일을 내보내는 방법을 보여줍니다.

```csharp
[C#]
const string hugePresentationWithAudiosAndVideosFile = @"Large  Video File Test1.pptx";
LoadOptions loadOptions = new LoadOptions
{
	BlobManagementOptions = {
		// 소스 파일을 잠그고 메모리로 로드하지 않습니다
		PresentationLockingBehavior = PresentationLockingBehavior.KeepLocked,
	}
};
// Presentation 인스턴스를 생성하고, "hugePresentationWithAudiosAndVideos.pptx" 파일을 잠급니다.
using (Presentation pres = new Presentation(hugePresentationWithAudiosAndVideosFile, loadOptions))
{
	// 각 비디오를 파일에 저장합니다. 높은 메모리 사용을 방지하기 위해 버퍼가 필요합니다
	// 프레젠테이션 비디오 스트림의 데이터를 새로 만든 비디오 파일 스트림으로 전달하기 위해서입니다.
	byte[] buffer = new byte[8 * 1024];
	// 비디오들을 반복합니다
	for (var index = 0; index < pres.Videos.Count; index++)
	{
		IVideo video = pres.Videos[index];
		// 프레젠테이션 비디오 스트림을 엽니다. 의도적으로 속성에 접근하지 않았음을 알려드립니다
		// video.BinaryData와 같은 속성은 전체 비디오를 포함한 바이트 배열을 반환하므로
		// 메모리로 로드됩니다. 우리는 video.GetStream을 사용하며, 이 메서드는 스트림을 반환하고 메모리에 전체 비디오를 로드하지 않습니다
		//  전체 비디오를 메모리로 로드할 필요가 없습니다.
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
		// 비디오나 프레젠테이션 크기에 관계없이 메모리 사용량이 낮게 유지됩니다,
	}
	// 필요하면 오디오 파일에도 동일한 절차를 적용할 수 있습니다.
}
```

다음 예제는 PowerPoint 프레젠테이션의 비디오에 하이퍼링크를 추가하는 방법을 보여줍니다.

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

다음 예제는 PowerPoint 프레젠테이션에서 웹 소스의 비디오를 사용하여 Video Frame을 만드는 방법을 보여줍니다.

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
    //비디오 프레임 추가
    IVideoFrame videoFrame = pres.Slides[0].Shapes.AddVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
    videoFrame.PlayMode = VideoPlayModePreset.Auto;
    //썸네일 로드
    using (WebClient client = new WebClient())
    {
        string thumbnailUri = "http://img.youtube.com/vi/" + videoId + "/hqdefault.jpg";
        videoFrame.PictureFormat.Picture.Image = pres.Images.AddImage(client.DownloadData(thumbnailUri));
    }
}
```

다음 예제는 PowerPoint 프레젠테이션 슬라이드에서 비디오를 추출하는 방법을 보여줍니다.

```csharp
[C#]
// 프레젠테이션 파일을 나타내는 Presentation 객체를 인스턴스화합니다
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

### 참조

* 인터페이스 [IVideoCollection](../../ivideocollection)
* 클래스 [Presentation](../../presentation)
* 네임스페이스 [Aspose.Slides](../../presentation)
* 어셈블리 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->