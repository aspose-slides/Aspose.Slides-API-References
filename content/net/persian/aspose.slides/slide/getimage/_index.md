---
title: GetImage
second_title: مرجع API Aspose.Sildes برای .NET
description: یک شیء تصویر بندانگشتی را با مقیاس‌بندی سفارشی برمی‌گرداند.
type: docs
weight: 80
url: /fa/aspose.slides/slide/getimage/
---
## GetImage(float, float) {#getimage_5}

یک شیء تصویر بندانگشتی با مقیاس سفارشی برمی‌گرداند.

```csharp
public IImage GetImage(float scaleX, float scaleY)
```

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| scaleX | Single | مقداری که برای مقیاس‌بندی این تصویر بندانگشتی در جهت محور x استفاده می‌شود. |
| scaleY | Single | مقداری که برای مقیاس‌بندی این تصویر بندانگشتی در جهت محور y استفاده می‌شود. |

### مقدار بازگشت

IImage object.

### مثال‌ها

مثال زیر نشان می‌دهد چطور می‌توان از یک ارائه PowerPoint تصویرهای بندانگشتی تولید کرد.

```csharp
[C#]
// یک شیء از کلاس Presentation ایجاد می‌کند که فایل ارائه را نمایندگی می‌کند
using (Presentation pres = new Presentation("ThumbnailFromSlide.pptx"))
{
    // دسترسی به اولین اسلاید
    ISlide sld = pres.Slides[0];
    // ایجاد یک تصویر با مقیاس کامل
    IImage bmp = sld.GetImage(1f, 1f);
    // ذخیره تصویر در دیسک به فرمت JPEG
    bmp.Save("Thumbnail_out.jpg", ImageFormat.Jpeg);
}
```

مثال زیر نشان می‌دهد چطور اسلایدها را به بیت‌مپ تبدیل کرده و تصاویر را در فرمت PNG ذخیره می‌کنیم.

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // اسلاید اول ارائه را به شیء Bitmap تبدیل می‌کند
    using (IImage bmp = pres.Slides[0].GetImage())
    {
        // تصویر را در قالب PNG ذخیره می‌کند
        bmp.Save("Slide_0.png", ImageFormat.Png);
    }
}
```

مثال زیر نشان می‌دهد چطور PowerPoint PPT/PPTX را به JPG تبدیل می‌کنیم.

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.ppt"))
{
	foreach (ISlide sld in pres.Slides)
	{
		// یک تصویر با مقیاس کامل ایجاد می‌کند
		IImage bmp = sld.GetImage(1f, 1f);
		// تصویر را در دیسک به فرمت JPEG ذخیره می‌کند
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

مثال زیر نشان می‌دهد چطور PowerPoint PPT/PPTX را به JPG با ابعاد سفارشی تبدیل می‌کنیم.

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.pptx"))
{
	// تعریف ابعاد
	int desiredX = 1200;
	int desiredY = 800;
	// دریافت مقادیر مقیاس‌بندی شده X و Y
	float ScaleX = (float)(1.0 / pres.SlideSize.Size.Width) * desiredX;
	float ScaleY = (float)(1.0 / pres.SlideSize.Size.Height) * desiredY;
	foreach (ISlide sld in pres.Slides)
	{
		// یک تصویر با مقیاس کامل ایجاد می‌کند
		IImage bmp = sld.GetImage(ScaleX, ScaleY);
		// تصویر را در دیسک به فرمت JPEG ذخیره می‌کند
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

### موارد مرتبط

* رابط [IImage](../../iimage)
* کلاس [Slide](../../slide)
* فضای‌نام [Aspose.Slides](../../slide)
* مجمع [Aspose.Slides](../../../)

---

## GetImage() {#getimage}

یک شیء تصویر بندانگشتی (20٪ از اندازه واقعی) برمی‌گرداند.

```csharp
public IImage GetImage()
```

### موارد مرتبط

* رابط [IImage](../../iimage)
* کلاس [Slide](../../slide)
* فضای‌نام [Aspose.Slides](../../slide)
* مجمع [Aspose.Slides](../../../)

---

## GetImage(Size) {#getimage_6}

یک شیء تصویر بندانگشتی با اندازه مشخص برمی‌گرداند.

```csharp
public IImage GetImage(Size imageSize)
```

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| imageSize | Size | اندازه‌ی تصویری که باید ایجاد شود. |

### مقدار بازگشت

Image object.

### مثال‌ها

مثال زیر نشان می‌دهد چطور اسلایدها را به تصاویر با اندازه‌های سفارشی تبدیل کنیم با استفاده از C#.

```csharp
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // اسلاید اول ارائه را به یک Bitmap با اندازه مشخص تبدیل می‌کند
    using (IImage bmp = pres.Slides[0].GetImage(new Size(1820, 1040)))
    {
        // تصویر را در قالب JPEG ذخیره می‌کند
        bmp.Save("Slide_0.jpg", ImageFormat.Jpeg);
    }
}
```

### موارد مرتبط

* رابط [IImage](../../iimage)
* کلاس [Slide](../../slide)
* فضای‌نام [Aspose.Slides](../../slide)
* مجمع [Aspose.Slides](../../../)

---

## GetImage(ITiffOptions) {#getimage_4}

یک شیء تصویر بندانگشتی tiff با پارامترهای مشخص برمی‌گرداند.

```csharp
public IImage GetImage(ITiffOptions options)
```

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| options | ITiffOptions | گزینه‌های Tiff. |

### مقدار بازگشت

Image object.

### استثناها

| استثنا | شرط |
| --- | --- |
| InvalidOperationException | هنگامی که options.SlideLayoutOption برابر NotesCommentsLayoutingOptions باشد و ویژگی NotesPosition مقدار NotesPositions.BottomFull را داشته باشد. |

### موارد مرتبط

* رابط [IImage](../../iimage)
* رابط [ITiffOptions](../../../aspose.slides.export/itiffoptions)
* کلاس [Slide](../../slide)
* فضای‌نام [Aspose.Slides](../../slide)
* مجمع [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions) {#getimage_1}

یک شیء تصویر بندانگشتی برمی‌گرداند.

```csharp
public IImage GetImage(IRenderingOptions options)
```

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| options | IRenderingOptions | گزینه‌های رندر کردن. |

### مقدار بازگشت

Image object.

### استثناها

| استثنا | شرط |
| --- | --- |
| InvalidOperationException | هنگامی که notesCommentsLayouting.NotesPosition مقدار NotesPositions.BottomFull را داشته باشد. |

### موارد مرتبط

* رابط [IImage](../../iimage)
* رابط [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* کلاس [Slide](../../slide)
* فضای‌نام [Aspose.Slides](../../slide)
* مجمع [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, float, float) {#getimage_2}

یک شیء تصویر بندانگشتی با مقیاس سفارشی برمی‌گرداند.

```csharp
public IImage GetImage(IRenderingOptions options, float scaleX, float scaleY)
```

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| options | IRenderingOptions | گزینه‌های رندر کردن. |
| scaleX | Single | مقداری که برای مقیاس‌بندی این تصویر بندانگشتی در جهت محور x استفاده می‌شود. |
| scaleY | Single | مقداری که برای مقیاس‌بندی این تصویر بندانگشتی در جهت محور y استفاده می‌شود. |

### مقدار بازگشت

Bitmap objects.

### استثناها

| استثنا | شرط |
| --- | --- |
| InvalidOperationException | هنگامی که notesCommentsLayouting.NotesPosition مقدار NotesPositions.BottomFull را داشته باشد. |

### مثال‌ها

مثال زیر نشان می‌دهد چطور اسلایدها را همراه با یادداشت‌ها و نظرات به تصاویر تبدیل کنیم با استفاده از C#.

```csharp
using (Presentation pres = new Presentation("PresentationNotesComments.pptx"))
{
    // گزینه‌های رندر را ایجاد می‌کند
    IRenderingOptions options = new RenderingOptions();
    // گزینه‌های چینش یادداشت‌ها و نظرات را ایجاد می‌کند
    NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
    // موقعیت یادداشت‌ها را در صفحه تنظیم می‌کند
    notesCommentsLayouting.NotesPosition = NotesPositions.BottomTruncated;
    // موقعیت نظرات را در صفحه تنظیم می‌کند
    notesCommentsLayouting.CommentsPosition = CommentsPositions.Right;
    // عرض ناحیه خروجی نظرات را تنظیم می‌کند
    notesCommentsLayouting.CommentsAreaWidth = 500;
    // رنگ ناحیه نظرات را تنظیم می‌کند
    notesCommentsLayouting.CommentsAreaColor = Color.AntiqueWhite;
    // گزینه‌های چینش برای رندر را تنظیم می‌کند
    options.SlidesLayoutOptions = notesCommentsLayouting;
    // اولین اسلاید ارائه را به شیء IImage تبدیل می‌کند
    IImage image = pres.Slides[0].GetImage(options, 2f, 2f);
    // تصویر را در قالب GIF ذخیره می‌کند
    image.Save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
}
```

### موارد مرتبط

* رابط [IImage](../../iimage)
* رابط [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* کلاس [Slide](../../slide)
* فضای‌نام [Aspose.Slides](../../slide)
* مجمع [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, Size) {#getimage_3}

یک شیء تصویر بندانگشتی با اندازه مشخص برمی‌گرداند.

```csharp
public IImage GetImage(IRenderingOptions options, Size imageSize)
```

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| options | IRenderingOptions | گزینه‌های رندر کردن. |
| imageSize | Size | اندازه‌ی تصویری که باید ایجاد شود. |

### مقدار بازگشت

Image object.

### استثناها

| استثنا | شرط |
| --- | --- |
| InvalidOperationException | هنگامی که options.SlideLayoutOption برابر NotesCommentsLayoutingOptions باشد و ویژگی NotesPosition مقدار NotesPositions.BottomFull را داشته باشد. |

### موارد مرتبط

* رابط [IImage](../../iimage)
* رابط [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* کلاس [Slide](../../slide)
* فضای‌نام [Aspose.Slides](../../slide)
* مجمع [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->