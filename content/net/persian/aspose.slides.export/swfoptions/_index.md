---
title: SwfOptions
second_title: مرجع API Aspose.Sildes برای .NET
description: گزینه‌هایی را فراهم می‌کند که نحوه ذخیره ارائه در قالب Swf را کنترل می‌کنند.
type: docs
weight: 4530
url: /fa/aspose.slides.export/swfoptions/
---
## کلاس SwfOptions

گزینه‌هایی را فراهم می‌کند که نحوه ذخیره ارائه در قالب Swf را کنترل می‌کنند.

```csharp
public class SwfOptions : SaveOptions, ISwfOptions
```

## سازنده‌ها

| نام | توضیح |
| --- | --- |
| [SwfOptions](swfoptions)() | سازنده پیش‌فرض. |

## خواص

| نام | توضیح |
| --- | --- |
| [Compressed](../../aspose.slides.export/swfoptions/compressed) { get; set; } | مشخص می‌کند که آیا سند SWF تولید شده باید فشرده باشد یا خیر. پیش‌فرض `true` است. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | فونتی را که در صورت عدم یافتن فونت منبع استفاده می‌شود برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن String. |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | منوی زمینه را فعال/غیر فعال می‌کند. پیش‌فرض true است. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | سبک بصری گرادیانت را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | کیفیت تصاویر JPEG را مشخص می‌کند. پیش‌فرض 95 است. |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | تصویری که به عنوان لوگو در گوشهٔ بالا-راست ویُئر نمایش داده می‌شود. تصویر باید PNG با اندازهٔ ۳۲×۶۴ پیکسل باشد؛ در غیر این صورت ممکن است لوگو به‌درستی نمایش داده نشود. |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | آدرس کامل پیوند برای لوگو را برمی‌گرداند یا تنظیم می‌کند. فقط در صورت تعیین [`LogoImageBytes`](./logoimagebytes) اثر دارد. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | یک شیء callback برای به‌روزرسانی‌های پیشرفت ذخیره‌سازی به‌صورت درصد را نمایش می‌دهد. رجوع کنید به [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | قابلیت نمایش/پنهان‌سازی نوار پایین. می‌توان در flashvars بازنویسی شد. پیش‌فرض true است. |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | دکمهٔ تمام‌صفحه نمایش/پنهان می‌شود. می‌توان در flashvars بازنویسی شد. پیش‌فرض true است. |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | مشخص می‌کند که سند تولید شده اسلایدهای پنهان را شامل شود یا خیر. پیش‌فرض `false` است. |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | قابلیت نمایش/پنهان‌سازی نوار چپ. می‌توان در flashvars بازنویسی شد. پیش‌فرض true است. |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | مشخص می‌کند که حاشیهٔ اطراف صفحات نمایش داده شود یا نه. پیش‌فرض true است. |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | قابلیت نمایش/پنهان‌سازی صفحه-ستپر. می‌توان در flashvars بازنویسی شد. پیش‌فرض true است. |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | قابلیت نمایش/پنهان‌سازی بخش جستجو. می‌توان در flashvars بازنویسی شد. پیش‌فرض true است. |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | قابلیت نمایش/پنهان‌سازی کل نوار بالایی. می‌توان در flashvars بازنویسی شد. پیش‌فرض true است. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | مشخص می‌کند که هنگام ذخیره ارائه، پیوندهای حاوی فراخوانی‌های JavaScript نادیده گرفته شوند یا نه. قابل‌خواندن/قابل‌نوشتن Boolean. مقدار پیش‌فرض **false** است. |
| [SlidesLayoutOptions](../../aspose.slides.export/swfoptions/slideslayoutoptions) { get; set; } | حالت چیدمان اسلایدها بر روی صفحه هنگام استخراج ارائه [`ISlidesLayoutOptions`](../islideslayoutoptions) را برمی‌گرداند یا تنظیم می‌کند. این ویژگی از اختصاص اشیاء از نوع [`HandoutLayoutingOptions`](../handoutlayoutingoptions) پشتیبانی نمی‌کند. |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | شروع با نوار چپ باز. می‌توان در flashvars بازنویسی شد. پیش‌فرض false است. |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | مشخص می‌کند که سند SWF تولید شده شامل نمایشگر سند یکپارچه باشد یا خیر. پیش‌فرض `true` است. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | یک شیء که هشدارها را دریافت می‌کند و تصمیم می‌گیرد فرآیند بارگذاری ادامه یابد یا خاتمه یابد، را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### مثال‌ها

مثال زیر نشان می‌دهد چگونه می‌توان PowerPoint را به SWF Flash تبدیل کرد.

```csharp
[C#]
// یک شیء Presentation ایجاد می‌کند که نمایانگر یک فایل ارائه است
using (Presentation presentation = new Presentation("HelloWorld.pptx"))
{
    SwfOptions swfOptions = new SwfOptions();
    swfOptions.ViewerIncluded = false;
    INotesCommentsLayoutingOptions notesOptions = swfOptions.NotesCommentsLayouting;
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    // ذخیرهٔ ارائه و صفحات یادداشت‌ها
    presentation.Save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
    swfOptions.ViewerIncluded = true;
    presentation.Save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
}
```

### همچنین ببینید

* کلاس [SaveOptions](../saveoptions)
* رابط [ISwfOptions](../iswfoptions)
* فضای‌نام [Aspose.Slides.Export](../../aspose.slides.export)
* مجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->