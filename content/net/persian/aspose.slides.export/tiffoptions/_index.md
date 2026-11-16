---
title: TiffOptions
second_title: Aspose.Sildes برای .NET API Reference
description: گزینه‌هایی را فراهم می‌آورد که نحوه ذخیره‌سازی یک ارائه را در قالب TIFF کنترل می‌کند.
type: docs
weight: 4590
url: /fa/aspose.slides.export/tiffoptions/
---
## TiffOptions کلاس

گزینه‌هایی را فراهم می‌آورد که نحوه ذخیره‌سازی یک ارائه در قالب TIFF را کنترل می‌کند.

```csharp
public class TiffOptions : SaveOptions, ITiffOptions
```

## سازنده‌ها

| نام | توضیح |
| --- | --- |
| [TiffOptions](tiffoptions)() | سازنده پیش‌فرض. |

## خواص

| نام | توضیح |
| --- | --- |
| [BwConversionMode](../../aspose.slides.export/tiffoptions/bwconversionmode) { get; set; } | الگوریتم تبدیل یک تصویر رنگی به تصویر سیاه و سفید را مشخص می‌کند. این گزینه فقط زمانی اعمال می‌شود که [`CompressionType`](./compressiontype) روی CCITT4 یا CCITT3 تنظیم شده باشد. خواندنی/نوشتنی [`BlackWhiteConversionMode`](../blackwhiteconversionmode). Default is Default. |
| [CompressionType](../../aspose.slides.export/tiffoptions/compressiontype) { get; set; } | نوع فشرده‌سازی را مشخص می‌کند. خواندنی/نوشتنی [`TiffCompressionTypes`](../tiffcompressiontypes). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | فونت استفاده‌شده را در صورتی که فونت منبع یافت نشود، برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [DpiX](../../aspose.slides.export/tiffoptions/dpix) { get; set; } | رزولوشن افقی را به نقطه در اینچ مشخص می‌کند. خواندنی/نوشتنی UInt32. |
| [DpiY](../../aspose.slides.export/tiffoptions/dpiy) { get; set; } | رزولوشن عمودی را به نقطه در اینچ مشخص می‌کند. خواندنی/نوشتنی UInt32. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | سبک بصری گرادیان را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageSize](../../aspose.slides.export/tiffoptions/imagesize) { get; set; } | اندازه تصویر TIFF تولید شده را مشخص می‌کند. مقدار پیش‌فرض 0x0 است، که به این معنی است که اندازه‌های تصویر تولید شده بر اساس مقدار اندازه اسلاید ارائه محاسبه می‌شوند. خواندنی/نوشتنی Size. |
| [InkOptions](../../aspose.slides.export/tiffoptions/inkoptions) { get; } | گزینه‌هایی را فراهم می‌کند که ظاهر اشیای جوهر را در سند صادر شده کنترل می‌کند. فقط‌خواندنی [`IInkOptions`](../iinkoptions) |
| [PixelFormat](../../aspose.slides.export/tiffoptions/pixelformat) { get; set; } | قالب پیکسلی تصاویر تولید شده را مشخص می‌کند. خواندنی/نوشتنی [`ImagePixelFormat`](../imagepixelformat). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | یک شیء کال‌بک را برای ذخیره‌سازی به‌روزرسانی‌های پیشرفت به درصد نشان می‌دهد. See [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowHiddenSlides](../../aspose.slides.export/tiffoptions/showhiddenslides) { get; set; } | مشخص می‌کند آیا سند تولید شده باید اسلایدهای پنهان را شامل شود یا نه. Default is `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | مشخص می‌کند آیا هنگام ذخیره‌سازی ارائه، پیوندهای افچین با فراخوانی‌های جاوااسکریپت صرف‌نظر شوند یا نه. خواندنی/نوشتنی Boolean. مقدار پیش‌فرض **false** است. |
| [SlidesLayoutOptions](../../aspose.slides.export/tiffoptions/slideslayoutoptions) { get; set; } | حالت قرارگیری اسلایدها در صفحه هنگام صادر کردن یک ارائه را برمی‌گرداند یا تنظیم می‌کند [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | یک شیء را برمی‌گرداند یا تنظیم می‌کند که هشدارها را دریافت کرده و تصمیم می‌گیرد آیا فرایند بارگذاری ادامه یابد یا متوقف شود. خواندنی/نوشتنی [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### مثال‌ها

مثال زیر نشان می‌دهد چگونه پاورپوینت را با اندازه پیش‌فرض به TIFF تبدیل کنیم.

```csharp
[C#]
// یک شیء Presentation ایجاد می‌کند که نمایانگر یک فایل ارائه است
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    // ذخیرهٔ ارائه به سند TIFF
    presentation.Save("Tiffoutput_out.tiff", SaveFormat.Tiff);
}
```

مثال زیر نشان می‌دهد چگونه پاورپوینت را با اندازهٔ سفارشی به TIFF تبدیل کنیم.

```csharp
[C#]
// یک شیء Presentation ایجاد می‌کند که نمایانگر یک فایل ارائه است
using (Presentation pres = new Presentation("Convert_Tiff_Custom.pptx"))
{
    // یک شیء از کلاس TiffOptions ایجاد می‌کند
    TiffOptions opts = new TiffOptions();
    // تنظیم نوع فشرده‌سازی
    opts.CompressionType = TiffCompressionTypes.Default;
    NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    opts.SlidesLayoutOption = notesOptions;
    // انواع فشرده‌سازی
    // Default - طرح فشرده‌سازی پیش‌فرض (LZW) را مشخص می‌کند.
    // None - عدم فشرده‌سازی را مشخص می‌کند.
    // CCITT3
    // CCITT4
    // LZW
    // RLE
    // عمق بستگی به نوع فشرده‌سازی دارد و نمی‌توان آن را به صورت دستی تنظیم کرد.
    // واحد وضوح همیشه برابر با “2” (نقطه در اینچ) است.
    // تنظیم DPI تصویر
    opts.DpiX = 200;
    opts.DpiY = 100;
    // تنظیم اندازه تصویر
    opts.ImageSize = new Size(1728, 1078);
    // ذخیرهٔ ارائه به TIFF با اندازه تصویر مشخص‌شده
    pres.Save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
}
```

مثال زیر نشان می‌دهد چگونه پاورپوینت را با قالب پیکسل تصویر سفارشی به TIFF تبدیل کنیم.

```csharp
[C#]
// یک شیء Presentation ایجاد می‌کند که نمایانگر یک فایل ارائه است
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    TiffOptions options = new TiffOptions();
    options.PixelFormat = ImagePixelFormat.Format8bppIndexed;
    /*
    ImagePixelFormat شامل مقادیر زیر است (همان‌طور که در مستندات دیده می‌شود):
    Format1bppIndexed; // 1 بیت در هر پیکسل، نمایه‌دار.
    Format4bppIndexed; // 4 بیت در هر پیکسل، نمایه‌دار.
    Format8bppIndexed; // 8 بیت در هر پیکسل، نمایه‌دار.
    Format24bppRgb; // 24 بیت در هر پیکسل، RGB.
    Format32bppArgb; // 32 بیت در هر پیکسل، ARGB.
    */
    // ارائه را با اندازه تصویر مشخص به TIFF ذخیره می‌کند
    presentation.Save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
}
```

### مراجع

* کلاس [SaveOptions](../saveoptions)
* اینترفیس [ITiffOptions](../itiffoptions)
* فضای‌نام [Aspose.Slides.Export](../../aspose.slides.export)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->