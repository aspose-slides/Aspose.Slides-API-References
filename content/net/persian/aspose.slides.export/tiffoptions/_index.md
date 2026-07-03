---
title: TiffOptions
second_title: Aspose.Sildes برای .NET مرجع API
description: گزینه‌هایی را فراهم می‌کند که نحوه ذخیره‌سازی یک ارائه در قالب TIFF را کنترل می‌کند.
type: docs
weight: 4570
url: /fa/aspose.slides.export/tiffoptions/
---
## TiffOptions کلاس

گزینه‌هایی را فراهم می‌کند که نحوه ذخیره‌سازی یک ارائه در قالب TIFF را کنترل می‌کند.

```csharp
public class TiffOptions : SaveOptions, ITiffOptions
```

## سازنده‌ها

| نام | توضیح |
| --- | --- |
| [TiffOptions](tiffoptions)() | سازنده پیش‌فرض. |

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [BwConversionMode](../../aspose.slides.export/tiffoptions/bwconversionmode) { get; set; } | الگوریتم تبدیل تصویر رنگی به تصویر سیاه و سفید را مشخص می‌کند. این گزینه فقط در صورتی اعمال می‌شود که [`CompressionType`](./compressiontype) بر روی CCITT4 یا CCITT3 تنظیم شده باشد. خواندنی/نوشتنی [`BlackWhiteConversionMode`](../blackwhiteconversionmode). پیش‌فرض Default است. |
| [CompressionType](../../aspose.slides.export/tiffoptions/compressiontype) { get; set; } | نوع فشرده‌سازی را مشخص می‌کند. خواندنی/نوشتنی [`TiffCompressionTypes`](../tiffcompressiontypes). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | فونتی را که در صورت عدم یافتن فونت منبع استفاده می‌شود بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [DpiX](../../aspose.slides.export/tiffoptions/dpix) { get; set; } | وضوح افقی را بر حسب نقطه در اینچ مشخص می‌کند. خواندنی/نوشتنی UInt32. |
| [DpiY](../../aspose.slides.export/tiffoptions/dpiy) { get; set; } | وضوح عمودی را بر حسب نقطه در اینچ مشخص می‌کند. خواندنی/نوشتنی UInt32. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | سبک بصری گرادیان را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageSize](../../aspose.slides.export/tiffoptions/imagesize) { get; set; } | اندازه تصویر TIFF تولید شده را مشخص می‌کند. مقدار پیش‌فرض 0x0 است که به این معنی است که اندازه‌های تصویر تولید شده بر اساس مقدار اندازه اسلاید ارائه محاسبه می‌شوند. خواندنی/نوشتنی Size. |
| [InkOptions](../../aspose.slides.export/tiffoptions/inkoptions) { get; } | گزینه‌هایی را فراهم می‌کند که ظاهر اشیاء Ink را در سند صادر شده کنترل می‌کنند. فقط‌خواندنی [`IInkOptions`](../iinkoptions) |
| [PixelFormat](../../aspose.slides.export/tiffoptions/pixelformat) { get; set; } | قالب پیکسل برای تصاویر تولید شده را مشخص می‌کند. خواندنی/نوشتنی [`ImagePixelFormat`](../imagepixelformat). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | شیء callback برای به‌روزرسانی پیشرفت ذخیره‌سازی به‌صورت درصدی را نشان می‌دهد. مشاهده [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowHiddenSlides](../../aspose.slides.export/tiffoptions/showhiddenslides) { get; set; } | مشخص می‌کند که آیا سند تولید شده اسلایدهای پنهان را شامل شود یا خیر. پیش‌فرض `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | مشخص می‌کند که آیا هنگام ذخیره‌سازی ارائه، لینک‌های ابرمتنی با فراخوانی‌های JavaScript حذف شوند یا نه. خواندنی/نوشتنی Boolean. مقدار پیش‌فرض **false** است. |
| [SlidesLayoutOptions](../../aspose.slides.export/tiffoptions/slideslayoutoptions) { get; set; } | حالت قرارگیری اسلایدها روی صفحه هنگام صادر کردن یک ارائه را بازمی‌گرداند یا تنظیم می‌کند [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | شیئی را که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا متوقف شود، بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### مثال‌ها

مثال زیر نشان می‌دهد چگونه PowerPoint را به TIFF با اندازه پیش‌فرض تبدیل کنیم.

```csharp
[C#]
// یک شیء Presentation ایجاد می‌کند که نمایانگر یک فایل ارائه است
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    // ذخیره ارائه به سند TIFF
    presentation.Save("Tiffoutput_out.tiff", SaveFormat.Tiff);
}
```

مثال زیر نشان می‌دهد چگونه PowerPoint را به TIFF با اندازه سفارشی تبدیل کنیم.

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
    // عمق بستگی به نوع فشرده‌سازی دارد و نمی‌تواند به‌صورت دستی تنظیم شود.
    // واحد وضوح همیشه برابر با "2" (نقطه در اینچ) است
    // تنظیم DPI تصویر
    opts.DpiX = 200;
    opts.DpiY = 100;
    // تنظیم اندازه تصویر
    opts.ImageSize = new Size(1728, 1078);
    // ذخیره ارائه به TIFF با اندازه تصویر مشخص شده
    pres.Save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
}
```

مثال زیر نشان می‌دهد چگونه PowerPoint را به TIFF با قالب پیکسل تصویر سفارشی تبدیل کنیم.

```csharp
[C#]
// یک شیء Presentation ایجاد می‌کند که نمایانگر یک فایل ارائه است
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    TiffOptions options = new TiffOptions();
    options.PixelFormat = ImagePixelFormat.Format8bppIndexed;
    /*
    ImagePixelFormat شامل مقادیر زیر است (همانطور که در مستندات می‌توان دید):
    Format1bppIndexed; // 1 بیت در هر پیکسل، ایندکس‌شده.
    Format4bppIndexed; // 4 بیت در هر پیکسل، ایندکس‌شده.
    Format8bppIndexed; // 8 بیت در هر پیکسل، ایندکس‌شده.
    Format24bppRgb; // 24 بیت در هر پیکسل، RGB.
    Format32bppArgb; // 32 بیت در هر پیکسل، ARGB.
    */
    // ارائه را به TIFF با اندازه تصویر مشخص ذخیره می‌کند
    presentation.Save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
}
```

### موارد مرتبط

* کلاس [SaveOptions](../saveoptions)
* رابط [ITiffOptions](../itiffoptions)
* فضای‌نام [Aspose.Slides.Export](../../aspose.slides.export)
* مجتمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->