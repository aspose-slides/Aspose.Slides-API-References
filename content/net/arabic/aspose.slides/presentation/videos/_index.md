---
title: Videos
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: يرجع مجموعة جميع ملفات الفيديو المضمنة في العرض التقديمي. للقراءة فقط IVideoCollectionaspose.slides/ivideocollection.
type: docs
weight: 290
url: /ar/aspose.slides/presentation/videos/
---
## Presentation.Videos خاصية

يرجع مجموعة جميع ملفات الفيديو المضمنة في العرض التقديمي. للقراءة فقط [`IVideoCollection`](../../ivideocollection).

```csharp
public IVideoCollection Videos { get; }
```

### أمثلة

توضح الأمثلة التالية كيفية إنشاء Video Frame مضمّن في PowerPoint Presentation.

```csharp
[C#]
// استنساخ فئة Presentation التي تمثل ملف PPTX
using (Presentation pres = new Presentation())
{
    // الحصول على الشريحة الأولى
    ISlide sld = pres.Slides[0];
    // إدراج فيديو داخل العرض التقديمي
    IVideo vid = pres.Videos.AddVideo(new FileStream("Wildlife.mp4", FileMode.Open));
    // إضافة إطار فيديو
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 350, vid);
    // تعيين الفيديو إلى إطار الفيديو
    vf.EmbeddedVideo = vid;
    // تعيين وضع التشغيل ومستوى الصوت للفيديو
    vf.PlayMode = VideoPlayModePreset.Auto;
    vf.Volume = AudioVolumeMode.Loud;
    // كتابة ملف PPTX إلى القرص
    pres.Save("VideoFrame_out.pptx", SaveFormat.Pptx);
}
```

توضح الأمثلة التالية كيفية إضافة فيديو بتمرير مسار ملف الفيديو مباشرةً إلى طريقة AddVideoFrame في PowerPoint Presentation.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    ISlide sld = pres.Slides[0];
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 150, "video1.avi");
}
```

توضح الأمثلة التالية كيفية إضافة ملف كبير عبر BLOB إلى Presentation.

```csharp
[C#]
const string pathToVeryLargeVideo = "veryLargeVideo.avi";
// ينشئ عرض تقديمي جديد سيتم إضافة الفيديو إليه
using (Presentation pres = new Presentation())
{
    using (FileStream fileStream = new FileStream(pathToVeryLargeVideo, FileMode.Open))
    {
        // لنضيف الفيديو إلى العرض التقديمي - اخترنا سلوك KeepLocked لأننا
        // لا ننوي الوصول إلى ملف "veryLargeVideo.avi"
        IVideo video = pres.Videos.AddVideo(fileStream, LoadingStreamBehavior.KeepLocked);
        pres.Slides[0].Shapes.AddVideoFrame(0, 0, 480, 270, video);
        // يحفظ العرض التقديمي. أثناء إخراج عرض تقديمي كبير
        // يظل استهلاك الذاكرة منخفضًا طوال دورة حياة كائن pres
        pres.Save("presentationWithLargeVideo.pptx", SaveFormat.Pptx);
    }
}
```

توضح الأمثلة التالية كيفية تصدير ملف كبير عبر BLOB من PowerPoint Presentation.

```csharp
[C#]
const string hugePresentationWithAudiosAndVideosFile = @"Large  Video File Test1.pptx";
LoadOptions loadOptions = new LoadOptions
{
	BlobManagementOptions = {
		// يقفل ملف المصدر ولا يحمله إلى الذاكرة
		PresentationLockingBehavior = PresentationLockingBehavior.KeepLocked,
	}
};
// ينشئ مثيلًا من Presentation، يقفل ملف "hugePresentationWithAudiosAndVideos.pptx".
using (Presentation pres = new Presentation(hugePresentationWithAudiosAndVideosFile, loadOptions))
{
	// لنحفظ كل فيديو في ملف. لتجنب الاستخدام العالي للذاكرة، نحتاج إلى مخزن وسيستخدم
	// لنقل البيانات من تدفق الفيديو في العرض التقديمي إلى تدفق لملف فيديو تم إنشاؤه حديثًا.
	byte[] buffer = new byte[8 * 1024];
	// يتكرر عبر مقاطع الفيديو
	for (var index = 0; index < pres.Videos.Count; index++)
	{
		IVideo video = pres.Videos[index];
		// يفتح تدفق فيديو العرض التقديمي. يرجى ملاحظة أننا تجنبنا عمدًا الوصول إلى الخصائص
		// مثل video.BinaryData - لأن هذه الخاصية تُعيد مصفوفة بايت تحتوي على فيديو كامل، مما
		// يسبب تحميل البايتات إلى الذاكرة. نستخدم video.GetStream، والتي ستُعيد Stream - ولا تقوم
		//  بطلب تحميل الفيديو بالكامل إلى الذاكرة.
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
		// استهلاك الذاكرة سيبقى منخفضًا بغض النظر عن حجم الفيديو أو العرض التقديمي،
	}
	// إذا لزم الأمر، يمكنك تطبيق نفس الخطوات على ملفات الصوت.
}
```

توضح الأمثلة التالية كيفية إضافة ارتباط تشعبي إلى فيديو في PowerPoint Presentation.

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

توضح الأمثلة التالية كيفية إنشاء Video Frame مع فيديو من مصدر ويب في PowerPoint Presentation.

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
    //إضافة إطار فيديو
    IVideoFrame videoFrame = pres.Slides[0].Shapes.AddVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
    videoFrame.PlayMode = VideoPlayModePreset.Auto;
    //تحميل الصورة المصغرة
    using (WebClient client = new WebClient())
    {
        string thumbnailUri = "http://img.youtube.com/vi/" + videoId + "/hqdefault.jpg";
        videoFrame.PictureFormat.Picture.Image = pres.Images.AddImage(client.DownloadData(thumbnailUri));
    }
}
```

توضح الأمثلة التالية كيفية استخراج Video من شريحة في PowerPoint Presentation.

```csharp
[C#]
// إنشاء كائن Presentation يمثل ملف عرض تقديمي
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

### انظر أيضًا

* الواجهة [IVideoCollection](../../ivideocollection)
* الفئة [Presentation](../../presentation)
* مساحة أسماء [Aspose.Slides](../../presentation)
* مجمع [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->