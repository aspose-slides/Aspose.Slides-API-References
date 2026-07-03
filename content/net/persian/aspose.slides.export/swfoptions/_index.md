---
title: SwfOptions
second_title: Aspose.Sildes برای .NET مرجع API
description: گزینه‌هایی را فراهم می‌کند که نحوه ذخیره‌سازی یک ارائه در قالب Swf را کنترل می‌کنند.
type: docs
weight: 4530
url: /fa/aspose.slides.export/swfoptions/
---
## SwfOptions کلاس

گزینه‌هایی را فراهم می‌کند که نحوهٔ ذخیره‌سازی ارائه در فرمت Swf را کنترل می‌کنند.

```csharp
public class SwfOptions : SaveOptions, ISwfOptions
```

## سازنده‌ها

| نام | توضیح |
| --- | --- |
| [SwfOptions](swfoptions)() | سازندهٔ پیش‌فرض. |

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [Compressed](../../aspose.slides.export/swfoptions/compressed) { get; set; } | تعیین می‌کند که سند SWF تولید شده فشرده باشد یا نه. پیش‌فرض `true` است. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | فونت استفاده شده در صورت عدم یافتن فونت منبع را برمی‌گرداند یا تنظیم می‌کند. خواندنی-نوشتنی String. |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | فعال/غیرفعال کردن منوی متنی. پیش‌فرض true است. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | سبک بصری گرادیان را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | کیفیت تصاویر JPEG را تعیین می‌کند. پیش‌فرض 95 است. |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | تصویری که به‌عنوان لوگو در بالای سمت راست نمایشگر نشان داده می‌شود. تصویر باید PNG با ابعاد 32×64 پیکسل باشد، در غیر این صورت ممکن است لوگو به‌درستی نمایش داده نشود. |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | آدرس کامل ابرپیوند برای یک لوگو را برمی‌گیرد یا تنظیم می‌کند. فقط در صورتی مؤثر است که [`LogoImageBytes`](./logoimagebytes) مشخص شده باشد. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | یک شیء بازگشتی برای دریافت به‌روزرسانی‌های پیشرفت ذخیره‌سازی به درصد را نشان می‌دهد. به [`IProgressCallback`](../../aspose.slides/iprogresscallback) مراجعه کنید. |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | نشان / پنهان کردن پنل پایین. می‌تواند در flashvars بازنویسی شود. پیش‌فرض true است. |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | نشان / پنهان کردن دکمهٔ تمام‌صفحه. می‌تواند در flashvars بازنویسی شود. پیش‌فرض true است. |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | تعیین می‌کند که سند تولید شده شامل اسلایدهای پنهان باشد یا نه. پیش‌فرض `false` است. |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | نشان / پنهان کردن پنل چپ. می‌تواند در flashvars بازنویسی شود. پیش‌فرض true است. |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | تعیین می‌کند که حاشیه اطراف صفحات نشان داده شود یا نه. پیش‌فرض true است. |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | نشان / پنهان کردن صفحه‌گذاران. می‌تواند در flashvars بازنویسی شود. پیش‌فرض true است. |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | نشان / پنهان کردن بخش جستجو. می‌تواند در flashvars بازنویسی شود. پیش‌فرض true است. |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | نشان / پنهان کردن کل پنل بالایی. می‌تواند در flashvars بازنویسی شود. پیش‌فرض true است. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | تعیین می‌کند که هنگام ذخیره ارائه پیوندهایی که فراخوانی‌های JavaScript دارند، نادیده گرفته شوند. خواندنی/نوشتنی Boolean. مقدار پیش‌فرض **false** است. |
| [SlidesLayoutOptions](../../aspose.slides.export/swfoptions/slideslayoutoptions) { get; set; } | حالت چیدمان اسلایدها بر روی صفحه هنگام خروجی گرفتن از ارائه را برمی‌گیرد یا تنظیم می‌کند [`ISlidesLayoutOptions`](../islideslayoutoptions). این ویژگی از انتساب اشیاء از نوع [`HandoutLayoutingOptions`](../handoutlayoutingoptions) پشتیبانی نمی‌کند. |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | با پنل چپ باز شروع می‌شود. می‌تواند در flashvars بازنویسی شود. پیش‌فرض false است. |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | تعیین می‌کند که سند SWF تولید شده شامل نمایشگر یکپارچه سند باشد یا نه. پیش‌فرض `true` است. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | یک شیء را برمی‌گرداند یا تنظیم می‌کند که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا خاتمه یابد. خواندنی/نوشتنی [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### مثال‌ها

مثال زیر نشان می‌دهد چگونه می‌توان PowerPoint را به SWF Flash تبدیل کرد.

```csharp
[C#]
// یک شیء Presentation ایجاد می‌کند که یک فایل ارائه را نمایندگی می‌کند
using (Presentation presentation = new Presentation("HelloWorld.pptx"))
{
    SwfOptions swfOptions = new SwfOptions();
    swfOptions.ViewerIncluded = false;
    INotesCommentsLayoutingOptions notesOptions = swfOptions.NotesCommentsLayouting;
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    // ذخیره‌سازی ارائه و صفحات یادداشت‌ها
    presentation.Save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
    swfOptions.ViewerIncluded = true;
    presentation.Save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
}
```

### موارد مرتبط

* کلاس [SaveOptions](../saveoptions)
* رابط [ISwfOptions](../iswfoptions)
* فضای‌نام [Aspose.Slides.Export](../../aspose.slides.export)
* مجتمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->