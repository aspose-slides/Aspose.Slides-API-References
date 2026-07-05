---
title: TiffOptions
second_title: Aspose.Sildes لـ .NET مرجع API
description: يقدم خيارات تتحكم في كيفية حفظ العرض التقديمي بصيغة TIFF.
type: docs
weight: 4570
url: /ar/aspose.slides.export/tiffoptions/
---
## فئة TiffOptions

يوفر خيارات تتحكم في طريقة حفظ العرض التقديمي بصيغة TIFF.

```csharp
public class TiffOptions : SaveOptions, ITiffOptions
```

## المُنشئين

| الاسم | الوصف |
| --- | --- |
| [TiffOptions](tiffoptions)() | منشئ افتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BwConversionMode](../../aspose.slides.export/tiffoptions/bwconversionmode) { get; set; } | يحدد الخوارزمية لتحويل صورة ملونة إلى صورة ذات لونين (أبيض وأسود). سيتم تطبيق هذا الخيار فقط إذا تم تعيين [`CompressionType`](./compressiontype) إلى CCITT4 أو CCITT3. قابل للقراءة والكتابة [`BlackWhiteConversionMode`](../blackwhiteconversionmode). القيمة الافتراضية هي Default. |
| [CompressionType](../../aspose.slides.export/tiffoptions/compressiontype) { get; set; } | يحدد نوع الضغط. قابل للقراءة والكتابة [`TiffCompressionTypes`](../tiffcompressiontypes). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | إرجاع أو تعيين الخط المستخدم في حالة عدم العثور على خط المصدر. قابل للقراءة والكتابة String. |
| [DpiX](../../aspose.slides.export/tiffoptions/dpix) { get; set; } | يحدد الدقة الأفقية بالنقاط لكل بوصة. قابل للقراءة والكتابة UInt32. |
| [DpiY](../../aspose.slides.export/tiffoptions/dpiy) { get; set; } | يحدد الدقة الرأسية بالنقاط لكل بوصة. قابل للقراءة والكتابة UInt32. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | إرجاع أو تعيين النمط البصري للتدرج. قابل للقراءة والكتابة [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageSize](../../aspose.slides.export/tiffoptions/imagesize) { get; set; } | يحدد حجم صورة TIFF المُولدة. القيمة الافتراضية هي 0x0، مما يعني أن أحجام الصور المُولدة ستحسب بناءً على قيمة حجم شريحة العرض التقديمي. قابل للقراءة والكتابة Size. |
| [InkOptions](../../aspose.slides.export/tiffoptions/inkoptions) { get; } | يوفر خيارات تتحكم في مظهر كائنات الحبر في المستند المُصدَّر. للقراءة فقط [`IInkOptions`](../iinkoptions) |
| [PixelFormat](../../aspose.slides.export/tiffoptions/pixelformat) { get; set; } | يحدد تنسيق البكسل للصور المُولدة. قابل للقراءة والكتابة [`ImagePixelFormat`](../imagepixelformat). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | يمثل كائن رد نداء لتحديثات تقدم الحفظ بالنسبة المئوية. انظر [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowHiddenSlides](../../aspose.slides.export/tiffoptions/showhiddenslides) { get; set; } | يحدد ما إذا كان يجب أن يتضمن المستند المُولد الشرائح المخفية أم لا. القيمة الافتراضية هي `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | يحدد ما إذا كان سيتم تخطي الروابط التشعبية ذات استدعاءات JavaScript عند حفظ العرض التقديمي. قابل للقراءة والكتابة Boolean. القيمة الافتراضية هي **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/tiffoptions/slideslayoutoptions) { get; set; } | يحصل أو يضبط الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | إرجاع أو تعيين كائن يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أم ستُوقف. قابل للقراءة والكتابة [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### أمثلة

يوضح المثال التالي كيفية تحويل PowerPoint إلى TIFF بالحجم الافتراضي.

```csharp
[C#]
// إنشاء كائن Presentation يمثل ملف عرض تقديمي
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    // حفظ العرض التقديمي كملف TIFF
    presentation.Save("Tiffoutput_out.tiff", SaveFormat.Tiff);
}
```

يوضح المثال التالي كيفية تحويل PowerPoint إلى TIFF بحجم مخصص.

```csharp
[C#]
// إنشاء كائن Presentation يمثل ملف عرض تقديمي
using (Presentation pres = new Presentation("Convert_Tiff_Custom.pptx"))
{
    // إنشاء كائن من فئة TiffOptions
    TiffOptions opts = new TiffOptions();
    // تحديد نوع الضغط
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
    // يعتمد العمق على نوع الضغط ولا يمكن تحديده يدويًا.
    // وحدة الدقة دائمًا تساوي “2” (نقطة لكل بوصة)
    // تحديد DPI للصورة
    opts.DpiX = 200;
    opts.DpiY = 100;
    // تحديد حجم الصورة
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
    يحتوي ImagePixelFormat على القيم التالية (كما هو موضح في الوثائق):
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

* فئة [SaveOptions](../saveoptions)
* واجهة [ITiffOptions](../itiffoptions)
* مساحة الاسم [Aspose.Slides.Export](../../aspose.slides.export)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->