---
title: GetImage
second_title: مرجع API الخاص بـ Aspose.Sildes لـ .NET
description: يُرجِع كائن صورة مصغرة مع مقياس مخصص.
type: docs
weight: 80
url: /ar/aspose.slides/slide/getimage/
---
## GetImage(float, float) {#getimage_5}

يُرجِع كائن صورة مصغرة مع مقياس مخصص.

```csharp
public IImage GetImage(float scaleX, float scaleY)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| scaleX | Single | القيمة التي يتم بها تحجيم هذه الصورة المصغرة في اتجاه محور x. |
| scaleY | Single | القيمة التي يتم بها تحجيم هذه الصورة المصغرة في اتجاه محور y. |

### قيمة الإرجاع

كائن IImage.

### أمثلة

يوضح المثال التالي كيفية إنشاء صور مصغرة من عرض PowerPoint.

```csharp
[C#]
// إنشاء كائن من فئة Presentation يمثل ملف العرض
using (Presentation pres = new Presentation("ThumbnailFromSlide.pptx"))
{
    // الوصول إلى الشريحة الأولى
    ISlide sld = pres.Slides[0];
    // إنشاء صورة بمقياس كامل
    IImage bmp = sld.GetImage(1f, 1f);
    // حفظ الصورة إلى القرص بتنسيق JPEG
    bmp.Save("Thumbnail_out.jpg", ImageFormat.Jpeg);
}
```

يوضح المثال التالي كيفية تحويل الشرائح إلى bitmap وحفظ الصور بصيغة PNG.

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // تحويل الشريحة الأولى في العرض إلى كائن Bitmap
    using (IImage bmp = pres.Slides[0].GetImage())
    {
        // حفظ الصورة بتنسيق PNG
        bmp.Save("Slide_0.png", ImageFormat.Png);
    }
}
```

يوضح المثال التالي كيفية تحويل PowerPoint PPT/PPTX إلى JPG.

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.ppt"))
{
	foreach (ISlide sld in pres.Slides)
	{
		// إنشاء صورة بمقياس كامل
		IImage bmp = sld.GetImage(1f, 1f);
		// حفظ الصورة إلى القرص بتنسيق JPEG
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

يوضح المثال التالي كيفية تحويل PowerPoint PPT/PPTX إلى JPG بأبعاد مخصصة.

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.pptx"))
{
	// تحديد الأبعاد
	int desiredX = 1200;
	int desiredY = 800;
	// الحصول على القيم المقيّسة للمحور X و Y
	float ScaleX = (float)(1.0 / pres.SlideSize.Size.Width) * desiredX;
	float ScaleY = (float)(1.0 / pres.SlideSize.Size.Height) * desiredY;
	foreach (ISlide sld in pres.Slides)
	{
		// إنشاء صورة بمقياس كامل
		IImage bmp = sld.GetImage(ScaleX, ScaleY);
		// حفظ الصورة إلى القرص بتنسيق JPEG
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

### انظر أيضًا

* واجهة [IImage](../../iimage)
* فئة [Slide](../../slide)
* نطاق [Aspose.Slides](../../slide)
* تجميع [Aspose.Slides](../../../)

---

## GetImage() {#getimage}

يُرجِع كائن صورة مصغرة (20% من الحجم الحقيقي).

```csharp
public IImage GetImage()
```

### انظر أيضًا

* واجهة [IImage](../../iimage)
* فئة [Slide](../../slide)
* نطاق [Aspose.Slides](../../slide)
* تجميع [Aspose.Slides](../../../)

---

## GetImage(Size) {#getimage_6}

يُرجِع كائن صورة مصغرة بالحجم المحدد.

```csharp
public IImage GetImage(Size imageSize)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| imageSize | Size | حجم الصورة المراد إنشاؤها. |

### قيمة الإرجاع

كائن Image.

### أمثلة

يوضح المثال التالي كيفية تحويل الشرائح إلى صور بأحجام مخصصة باستخدام C#.

```csharp
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // يحوّل الشريحة الأولى في العرض إلى كائن Bitmap بالحجم المحدد
    using (IImage bmp = pres.Slides[0].GetImage(new Size(1820, 1040)))
    {
        // يحفظ الصورة بتنسيق JPEG
        bmp.Save("Slide_0.jpg", ImageFormat.Jpeg);
    }
}
```

### انظر أيضًا

* واجهة [IImage](../../iimage)
* فئة [Slide](../../slide)
* نطاق [Aspose.Slides](../../slide)
* تجميع [Aspose.Slides](../../../)

---

## GetImage(ITiffOptions) {#getimage_4}

يُرجِع كائن صورة tiff مصغرة مع معلمات محددة.

```csharp
public IImage GetImage(ITiffOptions options)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | ITiffOptions | خيارات Tiff. |

### قيمة الإرجاع

كائن Image.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| InvalidOperationException | يُرمى عندما تكون options.SlideLayoutOption هي NotesCommentsLayoutingOptions وخصيصة NotesPosition لها القيمة NotesPositions.BottomFull. |

### انظر أيضًا

* واجهة [IImage](../../iimage)
* واجهة [ITiffOptions](../../../aspose.slides.export/itiffoptions)
* فئة [Slide](../../slide)
* نطاق [Aspose.Slides](../../slide)
* تجميع [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions) {#getimage_1}

يُرجِع كائن صورة مصغرة.

```csharp
public IImage GetImage(IRenderingOptions options)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | IRenderingOptions | خيارات العرض. |

### قيمة الإرجاع

كائن Image.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| InvalidOperationException | يُرمى عندما تكون notesCommentsLayouting.NotesPosition تأخذ القيمة NotesPositions.BottomFull |

### انظر أيضًا

* واجهة [IImage](../../iimage)
* واجهة [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* فئة [Slide](../../slide)
* نطاق [Aspose.Slides](../../slide)
* تجميع [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, float, float) {#getimage_2}

يُرجِع كائن صورة مصغرة مع مقياس مخصص.

```csharp
public IImage GetImage(IRenderingOptions options, float scaleX, float scaleY)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | IRenderingOptions | خيارات العرض. |
| scaleX | Single | القيمة التي يتم بها تحجيم هذه الصورة المصغرة في اتجاه محور x. |
| scaleY | Single | القيمة التي يتم بها تحجيم هذه الصورة المصغرة في اتجاه محور y. |

### قيمة الإرجاع

كائنات Bitmap.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| InvalidOperationException | يُرمى عندما تكون notesCommentsLayouting.NotesPosition تأخذ القيمة NotesPositions.BottomFull |

### أمثلة

يوضح المثال التالي كيفية تحويل الشرائح مع الملاحظات والتعليقات إلى صور باستخدام C#.

```csharp
using (Presentation pres = new Presentation("PresentationNotesComments.pptx"))
{
    // إنشاء خيارات العرض
    IRenderingOptions options = new RenderingOptions();
    // إنشاء خيارات تخطيط الملاحظات والتعليقات
    NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
    // تعيين موضع الملاحظات في الصفحة
    notesCommentsLayouting.NotesPosition = NotesPositions.BottomTruncated;
    // تعيين موضع التعليقات في الصفحة
    notesCommentsLayouting.CommentsPosition = CommentsPositions.Right;
    // تعيين عرض مساحة التعليقات
    notesCommentsLayouting.CommentsAreaWidth = 500;
    // تعيين لون مساحة التعليقات
    notesCommentsLayouting.CommentsAreaColor = Color.AntiqueWhite;
    // تعيين خيارات التخطيط للعرض
    options.SlidesLayoutOptions = notesCommentsLayouting;
    // تحويل الشريحة الأولى في العرض إلى كائن IImage
    IImage image = pres.Slides[0].GetImage(options, 2f, 2f);
    // حفظ الصورة بتنسيق GIF
    image.Save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
}
```

### انظر أيضًا

* واجهة [IImage](../../iimage)
* واجهة [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* فئة [Slide](../../slide)
* نطاق [Aspose.Slides](../../slide)
* تجميع [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, Size) {#getimage_3}

يُرجِع كائن صورة مصغرة بالحجم المحدد.

```csharp
public IImage GetImage(IRenderingOptions options, Size imageSize)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | IRenderingOptions | خيارات العرض. |
| imageSize | Size | حجم الصورة المراد إنشاؤها. |

### قيمة الإرجاع

كائن Image.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| InvalidOperationException | يُرمى عندما تكون options.SlideLayoutOption هي NotesCommentsLayoutingOptions وخصيصة NotesPosition لها القيمة NotesPositions.BottomFull. |

### انظر أيضًا

* واجهة [IImage](../../iimage)
* واجهة [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* فئة [Slide](../../slide)
* نطاق [Aspose.Slides](../../slide)
* تجميع [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->