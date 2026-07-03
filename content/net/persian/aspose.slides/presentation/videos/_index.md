---
title: Videos
second_title: مرجع API Aspose.Sildes برای .NET
description: مجموعه‌ای از تمام فایل‌های ویدئویی جاسازی‌شده در ارائه را برمی‌گرداند. فقط قابل‌خواندن IVideoCollectionaspose.slides/ivideocollection.
type: docs
weight: 290
url: /fa/aspose.slides/presentation/videos/
---
## ویژگی Presentation.Videos

مجموعه‌ای از تمام فایل‌های ویدیویی جاسازی‌شده در ارائه را برمی‌گرداند. فقط قابل‌خواندن [`IVideoCollection`](../../ivideocollection).

```csharp
public IVideoCollection Videos { get; }
```

### مثال‌ها

مثال‌های زیر نشان می‌دهد چگونه یک فریم ویدئویی جاسازی‌شده در یک ارائه PowerPoint ایجاد شود.

```csharp
[C#]
// نمونه‌سازی کلاس Presentation که نمایانگر فایل PPTX است
using (Presentation pres = new Presentation())
{
    // دریافت اولین اسلاید
    ISlide sld = pres.Slides[0];
    // جاسازی ویدئو درون ارائه
    IVideo vid = pres.Videos.AddVideo(new FileStream("Wildlife.mp4", FileMode.Open));
    // افزودن فریم ویدئو
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 350, vid);
    // تنظیم ویدئو به فریم ویدئو
    vf.EmbeddedVideo = vid;
    // تنظیم حالت پخش و صدا برای ویدئو
    vf.PlayMode = VideoPlayModePreset.Auto;
    vf.Volume = AudioVolumeMode.Loud;
    // نوشتن فایل PPTX به دیسک
    pres.Save("VideoFrame_out.pptx", SaveFormat.Pptx);
}
```

مثال‌های زیر نشان می‌دهد چگونه یک ویدئو با مسیر فایل به‌صورت مستقیم به متد AddVideoFrame برای ارائه PowerPoint اضافه شود.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    ISlide sld = pres.Slides[0];
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 150, "video1.avi");
}
```

مثال‌های زیر نشان می‌دهد چگونه یک فایل بزرگ از طریق BLOB به یک ارائه اضافه شود.

```csharp
[C#]
const string pathToVeryLargeVideo = "veryLargeVideo.avi";
// ایجاد یک ارائه جدید که ویدئو به آن اضافه خواهد شد
using (Presentation pres = new Presentation())
{
    using (FileStream fileStream = new FileStream(pathToVeryLargeVideo, FileMode.Open))
    {
        // بیایید ویدئو را به ارائه اضافه کنیم - ما رفتار KeepLocked را انتخاب کردیم چون
        // قصد دسترسی به فایل "veryLargeVideo.avi" را نداریم.
        IVideo video = pres.Videos.AddVideo(fileStream, LoadingStreamBehavior.KeepLocked);
        pres.Slides[0].Shapes.AddVideoFrame(0, 0, 480, 270, video);
        // ذخیره ارائه. در حالی که یک ارائه بزرگ خروجی می‌شود، مصرف حافظه
        // در طول دوره حیات شی pres کم می‌ماند
        pres.Save("presentationWithLargeVideo.pptx", SaveFormat.Pptx);
    }
}
```

مثال‌های زیر نشان می‌دهد چگونه یک فایل بزرگ از طریق BLOB از ارائه PowerPoint صادر شود.

```csharp
[C#]
const string hugePresentationWithAudiosAndVideosFile = @"Large  Video File Test1.pptx";
LoadOptions loadOptions = new LoadOptions
{
	BlobManagementOptions = {
		// فایل منبع را قفل می‌کند و آن را در حافظه بارگذاری نمی‌کند
		PresentationLockingBehavior = PresentationLockingBehavior.KeepLocked,
	}
};
// یک نمونه از Presentation ایجاد می‌کند و فایل "hugePresentationWithAudiosAndVideos.pptx" را قفل می‌کند.
using (Presentation pres = new Presentation(hugePresentationWithAudiosAndVideosFile, loadOptions))
{
	// بیایید هر ویدئو را در یک فایل ذخیره کنیم. برای جلوگیری از استفاده زیاد حافظه، به یک بافر نیاز داریم که
	// برای انتقال داده‌ها از جریان ویدئوی ارائه به جریان یک فایل ویدئوی تازه ایجاد شده استفاده شود.
	byte[] buffer = new byte[8 * 1024];
	// در ویدئوها تکرار می‌کند
	for (var index = 0; index < pres.Videos.Count; index++)
	{
		IVideo video = pres.Videos[index];
		// جریان ویدئوی ارائه را باز می‌کند. لطفاً توجه داشته باشید که ما عمداً از دسترسی به ویژگی‌ها خودداری کردیم
		// مانند video.BinaryData - زیرا این ویژگی یک آرایه بایت شامل تمام ویدئو برمی‌گرداند که در نتیجه
		// باعث می‌شود بایت‌ها در حافظه بارگذاری شوند. ما از video.GetStream استفاده می‌کنیم که یک Stream برمی‌گرداند - و
		// نیاز نداریم کل ویدئو را در حافظه بارگذاری کنیم.
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
		// مصرف حافظه حتی با اندازه ویدئو یا ارائه بزرگ نیز کم خواهد ماند،
	}
	// در صورت لزوم می‌توانید همان مراحل را برای فایل‌های صوتی اعمال کنید.
}
```

مثال‌های زیر نشان می‌دهد چگونه یک پیوند به ویدئو در یک ارائه PowerPoint اضافه شود.

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

مثال‌های زیر نشان می‌دهد چگونه فریم ویدئویی با ویدئو از منبع وب در یک ارائه PowerPoint ایجاد شود.

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
    //افزودن فریم ویدئو
    IVideoFrame videoFrame = pres.Slides[0].Shapes.AddVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
    videoFrame.PlayMode = VideoPlayModePreset.Auto;
    //بارگذاری تصویر بندانگشتی
    using (WebClient client = new WebClient())
    {
        string thumbnailUri = "http://img.youtube.com/vi/" + videoId + "/hqdefault.jpg";
        videoFrame.PictureFormat.Picture.Image = pres.Images.AddImage(client.DownloadData(thumbnailUri));
    }
}
```

مثال‌های زیر نشان می‌دهد چگونه ویدئو را از اسلاید یک ارائه PowerPoint استخراج کنید.

```csharp
[C#]
// یک شیء Presentation ایجاد می‌کند که نمایانگر یک فایل ارائه است
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

### موارد مرتبط

* رابط [IVideoCollection](../../ivideocollection)
* کلاس [Presentation](../../presentation)
* فضای‌نام [Aspose.Slides](../../presentation)
* مجمع [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->