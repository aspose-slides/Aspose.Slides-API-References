---
title: Videos
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Trả về tập hợp của tất cả các tệp video được nhúng trong bản trình chiếu. Chỉ đọc IVideoCollectionaspose.slides/ivideocollection.
type: docs
weight: 290
url: /vi/aspose.slides/presentation/videos/
---
## Thuộc tính Presentation.Videos

Trả về tập hợp của tất cả các tệp video nhúng trong bản trình chiếu. Chỉ đọc [`IVideoCollection`](../../ivideocollection).

```csharp
public IVideoCollection Videos { get; }
```

### Ví dụ

Các ví dụ sau cho thấy cách tạo Khung Video nhúng trong một Bản trình chiếu PowerPoint.

```csharp
[C#]
// Khởi tạo lớp Presentation đại diện cho tệp PPTX
using (Presentation pres = new Presentation())
{
    // Lấy slide đầu tiên
    ISlide sld = pres.Slides[0];
    // Nhúng video vào bản trình chiếu
    IVideo vid = pres.Videos.AddVideo(new FileStream("Wildlife.mp4", FileMode.Open));
    // Thêm khung video
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 350, vid);
    // Đặt video cho khung video
    vf.EmbeddedVideo = vid;
    // Đặt chế độ phát và âm lượng cho video
    vf.PlayMode = VideoPlayModePreset.Auto;
    vf.Volume = AudioVolumeMode.Loud;
    // Ghi tệp PPTX ra đĩa
    pres.Save("VideoFrame_out.pptx", SaveFormat.Pptx);
}
```

Các ví dụ sau cho thấy cách thêm video bằng cách truyền đường dẫn tới tệp video trực tiếp vào phương thức AddVideoFrame cho Bản trình chiếu PowerPoint.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    ISlide sld = pres.Slides[0];
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 150, "video1.avi");
}
```

Các ví dụ sau cho thấy cách thêm tệp lớn thông qua BLOB vào một Bản trình chiếu.

```csharp
[C#]
const string pathToVeryLargeVideo = "veryLargeVideo.avi";
// Tạo một bản trình chiếu mới mà video sẽ được thêm vào
using (Presentation pres = new Presentation())
{
    using (FileStream fileStream = new FileStream(pathToVeryLargeVideo, FileMode.Open))
    {
        // Hãy thêm video vào bản trình chiếu - chúng tôi chọn hành vi KeepLocked vì chúng tôi muốn
        // không dự định truy cập tệp "veryLargeVideo.avi".
        IVideo video = pres.Videos.AddVideo(fileStream, LoadingStreamBehavior.KeepLocked);
        pres.Slides[0].Shapes.AddVideoFrame(0, 0, 480, 270, video);
        // Lưu bản trình chiếu. Khi một bản trình chiếu lớn được xuất, mức tiêu thụ bộ nhớ
        // vẫn thấp trong suốt vòng đời của đối tượng pres
        pres.Save("presentationWithLargeVideo.pptx", SaveFormat.Pptx);
    }
}
```

Các ví dụ sau cho thấy cách xuất tệp lớn thông qua BLOB từ Bản trình chiếu PowerPoint.

```csharp
[C#]
const string hugePresentationWithAudiosAndVideosFile = @"Large  Video File Test1.pptx";
LoadOptions loadOptions = new LoadOptions
{
	BlobManagementOptions = {
		// Khóa tệp nguồn và KHÔNG tải nó vào bộ nhớ
		PresentationLockingBehavior = PresentationLockingBehavior.KeepLocked,
	}
};
// Tạo một thể hiện của Presentation, khóa tệp "hugePresentationWithAudiosAndVideos.pptx".
using (Presentation pres = new Presentation(hugePresentationWithAudiosAndVideosFile, loadOptions))
{
	// Hãy lưu mỗi video vào một tệp. Để ngăn ngừa việc sử dụng bộ nhớ cao, chúng ta cần một bộ đệm sẽ được sử dụng
	// để chuyển dữ liệu từ luồng video của bản trình chiếu sang một luồng cho tệp video mới tạo.
	byte[] buffer = new byte[8 * 1024];
	// Duyệt qua các video
	for (var index = 0; index < pres.Videos.Count; index++)
	{
		IVideo video = pres.Videos[index];
		// Mở luồng video của bản trình chiếu. Vui lòng lưu ý rằng chúng tôi cố ý tránh truy cập các thuộc tính
		// như video.BinaryData - vì thuộc tính này trả về một mảng byte chứa toàn bộ video, sau đó
		// làm cho các byte được tải vào bộ nhớ. Chúng tôi sử dụng video.GetStream, phương thức sẽ trả về Stream - và KHÔNG
		//  yêu cầu chúng ta tải toàn bộ video vào bộ nhớ.
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
		// Mức tiêu thụ bộ nhớ sẽ vẫn thấp bất kể kích thước của video hay bản trình chiếu,
	}
	// Nếu cần, bạn có thể áp dụng các bước tương tự cho các tệp âm thanh.
}
```

Các ví dụ sau cho thấy cách thêm siêu liên kết vào video trong Bản trình chiếu PowerPoint.

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

Các ví dụ sau cho thấy cách tạo Khung Video với Video từ nguồn Web trong Bản trình chiếu PowerPoint.

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
    //thêm khung video
    IVideoFrame videoFrame = pres.Slides[0].Shapes.AddVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
    videoFrame.PlayMode = VideoPlayModePreset.Auto;
    //tải ảnh thu nhỏ
    using (WebClient client = new WebClient())
    {
        string thumbnailUri = "http://img.youtube.com/vi/" + videoId + "/hqdefault.jpg";
        videoFrame.PictureFormat.Picture.Image = pres.Images.AddImage(client.DownloadData(thumbnailUri));
    }
}
```

Các ví dụ sau cho thấy cách trích xuất Video từ slide của Bản trình chiếu PowerPoint.

```csharp
[C#]
// Khởi tạo đối tượng Presentation đại diện cho một tệp bản trình chiếu
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

### Xem thêm

* giao diện [IVideoCollection](../../ivideocollection)
* lớp [Presentation](../../presentation)
* không gian tên [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->