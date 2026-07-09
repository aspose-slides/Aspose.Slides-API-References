---
title: TiffOptions
second_title: Aspose.Sildes لـ .NET مرجع API
description: يوفر خيارات تتحكم في طريقة حفظ العرض التقديمي بتنسيق TIFF.
type: docs
weight: 4570
url: /ar/aspose.slides.export/tiffoptions/
---
## فئة TiffOptions

يوفر خيارات تتحكم في كيفية حفظ العرض التقديمي بتنسيق TIFF.

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
| [BwConversionMode](../../aspose.slides.export/tiffoptions/bwconversionmode) { get; set; } | يحدد الخوارزمية لتحويل صورة ملونة إلى صورة أبيض وأسود. سيتم تطبيق هذا الخيار فقط إذا كان [`CompressionType`](./compressiontype) مُعينًا إلى CCITT4 أو CCITT3 قابل للقراءة/الكتابة [`BlackWhiteConversionMode`](../blackwhiteconversionmode). الافتراضي هو Default. |
| [CompressionType](../../aspose.slides.export/tiffoptions/compressiontype) { get; set; } | يحدد نوع الضغط. قابل للقراءة/الكتابة [`TiffCompressionTypes`](../tiffcompressiontypes). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | يعيد أو يضبط الخط المستخدم في حالة عدم العثور على الخط المصدر. قابل للقراءة/الكتابة String. |
| [DpiX](../../aspose.slides.export/tiffoptions/dpix) { get; set; } | يحدد الدقة الأفقية بوحدة النقاط لكل بوصة. قابل للقراءة/الكتابة UInt32. |
| [DpiY](../../aspose.slides.export/tiffoptions/dpiy) { get; set; } | يحدد الدقة العمودية بوحدة النقاط لكل بوصة. قابل للقراءة/الكتابة UInt32. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | يعيد أو يضبط النمط البصري للتدرج. قابل للقراءة/الكتابة [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageSize](../../aspose.slides.export/tiffoptions/imagesize) { get; set; } | يحدد حجم صورة TIFF المُولدة. القيمة الافتراضية هي 0x0، ما يعني أن أحجام الصور المتولدة سُتحسب بناءً على قيمة حجم شريحة العرض. قابل للقراءة/الكتابة Size. |
| [InkOptions](../../aspose.slides.export/tiffoptions/inkoptions) { get; } | يوفر خيارات تتحكم في مظهر كائنات الحبر في المستند المصدر. للقراءة فقط [`IInkOptions`](../iinkoptions) |
| [PixelFormat](../../aspose.slides.export/tiffoptions/pixelformat) { get; set; } | يحدد تنسيق البكسل للصور المتولدة. قابل للقراءة/الكتابة [`ImagePixelFormat`](../imagepixelformat). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | يمثل كائن استدعاء للعودة لتحديثات تقدم الحفظ بالنسبة المئوية. انظر [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowHiddenSlides](../../aspose.slides.export/tiffoptions/showhiddenslides) { get; set; } | يحدد ما إذا كان المستند المُولد يجب أن يتضمن الشرائح المخفية أم لا. الافتراضي هو `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | يحدد ما إذا كان يجب تخطي الروابط التشعبية ذات استدعاءات JavaScript عند حفظ العرض التقديمي. قابل للقراءة/الكتابة Boolean. القيمة الافتراضية هي **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/tiffoptions/slideslayoutoptions) { get; set; } | يحصل أو يضبط الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | يعيد أو يضبط كائنًا يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أو ستُجهض. قابل للقراءة/الكتابة [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### الأمثلة

المثال التالي يوضح كيفية تحويل PowerPoint إلى TIFF بالحجم الافتراضي.

```csharp
[C#]
// إنشاء كائن Presentation يمثل ملف عرض تقديمي
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    // حفظ العرض التقديمي إلى مستند TIFF
    presentation.Save("Tiffoutput_out.tiff", SaveFormat.Tiff);
}
```

المثال التالي يوضح كيفية تحويل PowerPoint إلى TIFF بحجم مخصص.

```csharp
[C#]
// إنشاء كائن Presentation يمثل ملف عرض تقديمي
using (Presentation pres = new Presentation("Convert_Tiff_Custom.pptx"))
{
    // إنشاء كائن من فئة TiffOptions
    TiffOptions opts = new TiffOptions();
    // تعيين نوع الضغط
    opts.CompressionType = TiffCompressionTypes.Default;
    NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    opts.SlidesLayoutOption = notesOptions;
    // أنواع الضغط
    // Default - يحدد نظام الضغط الافتراضي (LZW).
    // None - يحدد عدم وجود ضغط.
    // CCITT3
    // CCITT4
    // LZW
    // RLE
    // يعتمد العمق على نوع الضغط ولا يمكن تعيينه يدويًا.
    // وحدة الدقة دائمًا تساوي “2” (نقطة لكل بوصة)
    // تعيين DPI الصورة
    opts.DpiX = 200;
    opts.DpiY = 100;
    // تعيين حجم الصورة
    opts.ImageSize = new Size(1728, 1078);
    // حفظ العرض التقديمي إلى TIFF مع حجم الصورة المحدد
    pres.Save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
}
```

المثال التالي يوضح كيفية تحويل PowerPoint إلى TIFF بتنسيق بكسل صورة مخصص.

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
    // حفظ العرض التقديمي إلى TIFF مع حجم الصورة المحدد
    presentation.Save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
}
```

### انظر أيضًا

* فئة [SaveOptions](../saveoptions)
* واجهة [ITiffOptions](../itiffoptions)
* مساحة الاسم [Aspose.Slides.Export](../../aspose.slides.export)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->