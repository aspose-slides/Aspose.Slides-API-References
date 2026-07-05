---
title: Videos
second_title: Aspose.Sildes สำหรับ .NET เอกสารอ้างอิง API
description: คืนค่าชุดของไฟล์วิดีโอฝังทั้งหมดในงานนำเสนอ. อ่านอย่างเดียว IVideoCollectionaspose.slides/ivideocollection.
type: docs
weight: 290
url: /th/aspose.slides/presentation/videos/
---
## Presentation.Videos คุณสมบัติ

คืนค่าชุดของไฟล์วิดีโอฝังทั้งหมดในงานนำเสนอ. อ่านอย่างเดียว [`IVideoCollection`](../../ivideocollection).

```csharp
public IVideoCollection Videos { get; }
```

### ตัวอย่าง

ตัวอย่างต่อไปนี้แสดงวิธีสร้าง Video Frame ฝังใน PowerPoint Presentation.

```csharp
[C#]
// สร้างอินสแตนซ์ของคลาส Presentation ที่แทนไฟล์ PPTX
using (Presentation pres = new Presentation())
{
    // รับสไลด์แรก
    ISlide sld = pres.Slides[0];
    // ฝังวิดีโอในงานนำเสนอ
    IVideo vid = pres.Videos.AddVideo(new FileStream("Wildlife.mp4", FileMode.Open));
    // เพิ่ม Video Frame
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 350, vid);
    // ตั้งค่าวิดีโอให้กับ Video Frame
    vf.EmbeddedVideo = vid;
    // ตั้งค่าโหมดการเล่นและระดับเสียงของวิดีโอ
    vf.PlayMode = VideoPlayModePreset.Auto;
    vf.Volume = AudioVolumeMode.Loud;
    // บันทึกไฟล์ PPTX ลงดิสก์
    pres.Save("VideoFrame_out.pptx", SaveFormat.Pptx);
}
```

ตัวอย่างต่อไปนี้แสดงวิธีเพิ่มวิดีโอโดยส่งเส้นทางไปยังไฟล์วิดีโอโดยตรงในเมธอด AddVideoFrame สำหรับ PowerPoint Presentation.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    ISlide sld = pres.Slides[0];
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 150, "video1.avi");
}
```

ตัวอย่างต่อไปนี้แสดงวิธีเพิ่มไฟล์ขนาดใหญ่ผ่าน BLOB ไปยัง Presentation.

```csharp
[C#]
const string pathToVeryLargeVideo = "veryLargeVideo.avi";
// สร้างงานนำเสนอใหม่ที่วิดีโอจะถูกเพิ่มเข้าไป
using (Presentation pres = new Presentation())
{
    using (FileStream fileStream = new FileStream(pathToVeryLargeVideo, FileMode.Open))
    {
        // เราจะเพิ่มวิดีโอเข้าไปในงานนำเสนอ - เราเลือกพฤติกรรม KeepLocked เนื่องจากเรา
        // ไม่ได้ตั้งใจเข้าถึงไฟล์ "veryLargeVideo.avi" file.
        IVideo video = pres.Videos.AddVideo(fileStream, LoadingStreamBehavior.KeepLocked);
        pres.Slides[0].Shapes.AddVideoFrame(0, 0, 480, 270, video);
        // บันทึกงานนำเสนอ. ขณะที่งานนำเสนอขนาดใหญ่ถูกสร้างออกมา, การใช้หน่วยความจำ
        // จะคงต่ำตลอดวงจรชีวิตของวัตถุ pres
        pres.Save("presentationWithLargeVideo.pptx", SaveFormat.Pptx);
    }
}
```

ตัวอย่างต่อไปนี้แสดงวิธีส่งออกไฟล์ขนาดใหญ่ผ่าน BLOB จาก PowerPoint Presentation.

```csharp
[C#]
const string hugePresentationWithAudiosAndVideosFile = @"Large  Video File Test1.pptx";
LoadOptions loadOptions = new LoadOptions
{
	BlobManagementOptions = {
		// ล็อกไฟล์ต้นฉบับและไม่โหลดเข้าหน่วยความจำ
		PresentationLockingBehavior = PresentationLockingBehavior.KeepLocked,
	}
};
// สร้างอินสแตนซ์ของ Presentation, ล็อกไฟล์ "hugePresentationWithAudiosAndVideos.pptx"
using (Presentation pres = new Presentation(hugePresentationWithAudiosAndVideosFile, loadOptions))
{
	// เราจะบันทึกวิดีโอแต่ละไฟล์ลงไฟล์. เพื่อป้องกันการใช้หน่วยความจำสูง, เราต้องการบัฟเฟอร์ที่จะใช้
	// เพื่อโอนย้ายข้อมูลจากสตรีมวิดีโอของงานนำเสนอไปยังสตรีมของไฟล์วิดีโอที่สร้างใหม่
	byte[] buffer = new byte[8 * 1024];
	// วนผ่านวิดีโอทั้งหมด
	for (var index = 0; index < pres.Videos.Count; index++)
	{
		IVideo video = pres.Videos[index];
		// เปิดสตรีมวิดีโอของงานนำเสนอ. โปรดทราบว่าเราตตั้งใจหลีกเลี่ยงการเข้าถึงคุณสมบัติ
		// เช่น video.BinaryData - เพราะคุณสมบัตินี้คืนอาเรย์ไบต์ที่มีวิดีโอเต็ม, ซึ่งต่อมาจะ
		// ทำให้ไบต์ถูกโหลดเข้าสู่หน่วยความจำ. เราใช้ video.GetStream, ซึ่งจะคืนค่า Stream - และไม่
		//  จำเป็นต้องโหลดวิดีโอทั้งหมดเข้าสู่หน่วยความจำ.
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
		// การใช้หน่วยความจำจะคงต่ำไม่ว่าขนาดของวิดีโอหรือการนำเสนอจะเป็นเท่าใด,
	}
	// หากจำเป็น, คุณสามารถทำตามขั้นตอนเดียวกันสำหรับไฟล์เสียงได้.
}
```

ตัวอย่างต่อไปนี้แสดงวิธีเพิ่มไฮเปอร์ลิงก์ไปยังวิดีโอใน PowerPoint Presentation.

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

ตัวอย่างต่อไปนี้แสดงวิธีสร้าง Video Frame พร้อมวิดีโอจากแหล่งเว็บใน PowerPoint Presentation.

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
    //เพิ่ม videoFrame
    IVideoFrame videoFrame = pres.Slides[0].Shapes.AddVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
    videoFrame.PlayMode = VideoPlayModePreset.Auto;
    //โหลด thumbnail
    using (WebClient client = new WebClient())
    {
        string thumbnailUri = "http://img.youtube.com/vi/" + videoId + "/hqdefault.jpg";
        videoFrame.PictureFormat.Picture.Image = pres.Images.AddImage(client.DownloadData(thumbnailUri));
    }
}
```

ตัวอย่างต่อไปนี้แสดงวิธีแยก Video จากสไลด์ของ PowerPoint Presentation.

```csharp
[C#]
// สร้างออบเจกต์ Presentation ที่แทนไฟล์งานนำเสนอ
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

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IVideoCollection](../../ivideocollection)
* คลาส [Presentation](../../presentation)
* เนมสเปซ [Aspose.Slides](../../presentation)
* แอสเซมบลี [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->