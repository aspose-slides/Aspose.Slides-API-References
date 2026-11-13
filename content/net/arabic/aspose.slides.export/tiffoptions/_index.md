---
title: TiffOptions
second_title: Aspose.Sildes لـ .NET مرجع API
description: يوفر خيارات تتحكم في طريقة حفظ العرض التقديمي بصيغة TIFF.
type: docs
weight: 4590
url: /ar/aspose.slides.export/tiffoptions/
---
## الفئة TiffOptions

يوفر خيارات تتحكم في طريقة حفظ العرض التقديمي بصيغة TIFF.

```csharp
public class TiffOptions : SaveOptions, ITiffOptions
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [TiffOptions](tiffoptions)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BwConversionMode](../../aspose.slides.export/tiffoptions/bwconversionmode) { get; set; } | يحدد الخوارزمية لتحويل الصورة الملونة إلى صورة بالأبيض والأسود. يتم تطبيق هذا الخيار فقط إذا تم تعيين [`CompressionType`](./compressiontype) إلى CCITT4 أو CCITT3 قراءة/كتابة [`BlackWhiteConversionMode`](../blackwhiteconversionmode). الافتراضي هو Default. |
| [CompressionType](../../aspose.slides.export/tiffoptions/compressiontype) { get; set; } | يحدد نوع الضغط. قراءة/كتابة [`TiffCompressionTypes`](../tiffcompressiontypes). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | إرجاع أو تعيين الخط المستخدم في حالة عدم العثور على الخط المصدر. قراءة/كتابة String. |
| [DpiX](../../aspose.slides.export/tiffoptions/dpix) { get; set; } | يحدد الدقة الأفقية بوحدة النقاط في البوصة. قراءة/كتابة UInt32. |
| [DpiY](../../aspose.slides.export/tiffoptions/dpiy) { get; set; } | يحدد الدقة الرأسية بوحدة النقاط في البوصة. قراءة/كتابة UInt32. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | إرجاع أو تعيين النمط البصري للتدرج. قراءة/كتابة [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageSize](../../aspose.slides.export/tiffoptions/imagesize) { get; set; } | يحدد حجم صورة TIFF المولدة. القيمة الافتراضية هي 0x0، مما يعني أن أحجام الصور المولدة ستحسب بناءً على قيمة حجم شريحة العرض التقديمي. قراءة/كتابة Size. |
| [InkOptions](../../aspose.slides.export/tiffoptions/inkoptions) { get; } | يوفر خيارات تتحكم في مظهر كائنات الحبر في المستند المُصدَّر. قراءة فقط [`IInkOptions`](../iinkoptions) |
| [PixelFormat](../../aspose.slides.export/tiffoptions/pixelformat) { get; set; } | يحدد تنسيق البكسل للصور المولدة. قراءة/كتابة [`ImagePixelFormat`](../imagepixelformat). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | يمثل كائن رد نداء لتحديثات حفظ التقدم كنسبة مئوية. انظر [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowHiddenSlides](../../aspose.slides.export/tiffoptions/showhiddenslides) { get; set; } | يحدد ما إذا كان المستند المولد يجب أن يتضمن الشرائح المخفية أم لا. القيمة الافتراضية هي `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | يحدد ما إذا كان سيتم تخطي الروابط التشعبية التي تحتوي على استدعاءات JavaScript عند حفظ العرض التقديمي. قراءة/كتابة Boolean. القيمة الافتراضية هي **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/tiffoptions/slideslayoutoptions) { get; set; } | إرجاع أو تعيين الوضع الذي توضع فيه الشرائح على الصفحة عند تصدير العرض التقديمي [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | إرجاع أو تعيين كائن يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أم تُلغى. قراءة/كتابة [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### أمثلة

يوضح المثال التالي كيفية تحويل PowerPoint إلى TIFF بالحجم الافتراضي.

```csharp
[C#]
// إنشاء كائن Presentation يمثل ملف عرض تقديمي
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    // حفظ العرض التقديمي إلى مستند TIFF
    presentation.Save("Tiffoutput_out.tiff", SaveFormat.Tiff);
}
```

يوضح المثال التالي كيفية تحويل PowerPoint إلى TIFF بحجم مخصص.

```csharp
[C#]
// إنشاء كائن Presentation يمثل ملف عرض تقديمي
using (Presentation pres = new Presentation("Convert_Tiff_Custom.pptx"))
{
    // إنشاء كائن من الفئة TiffOptions
    TiffOptions opts = new TiffOptions();
    // تعيين نوع الضغط
    opts.CompressionType = TiffCompressionTypes.Default;
    NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    opts.SlidesLayoutOption = notesOptions;
    // أنواع الضغط
    // Default - يحدد مخطط الضغط الافتراضي (LZW).
    // None - يحدد عدم وجود ضغط.
    // CCITT3
    // CCITT4
    // LZW
    // RLE
    // العمق يعتمد على نوع الضغط ولا يمكن تعيينه يدويًا.
    // وحدة الدقة دائمًا ما تكون مساوية لـ “2” (نقطة في البوصة)
    // تعيين DPI للصورة
    opts.DpiX = 200;
    opts.DpiY = 100;
    // تعيين حجم الصورة
    opts.ImageSize = new Size(1728, 1078);
    // حفظ العرض التقديمي إلى TIFF بالحجم المحدد للصورة
    pres.Save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
}
```

يوضح المثال التالي كيفية تحويل PowerPoint إلى TIFF بتنسيق بكسل صورة مخصص.

```csharp
[C#]
// إنشاء كائن Presentation يمثل ملف عرض تقديمي
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    TiffOptions options = new TiffOptions();
    options.PixelFormat = ImagePixelFormat.Format8bppIndexed;
    /*
    ImagePixelFormat يحتوي على القيم التالية (كما هو موضح في الوثائق):
    Format1bppIndexed; // 1 بت لكل بكسل، مفهرس.
    Format4bppIndexed; // 4 بت لكل بكسل، مفهرس.
    Format8bppIndexed; // 8 بت لكل بكسل، مفهرس.
    Format24bppRgb; // 24 بت لكل بكسل، RGB.
    Format32bppArgb; // 32 بت لكل بكسل، ARGB.
    */
    // حفظ العرض التقديمي إلى TIFF بالحجم المحدد للصورة
    presentation.Save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
}
```

### انظر أيضًا

* الفئة [SaveOptions](../saveoptions)
* الواجهة [ITiffOptions](../itiffoptions)
* مساحة الاسم [Aspose.Slides.Export](../../aspose.slides.export)
* التجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->