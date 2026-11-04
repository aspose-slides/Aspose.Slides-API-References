---
title: SwfOptions
second_title: مرجع API Aspose.Sildes برای .NET
description: گزینه‌هایی را فراهم می‌کند که نحوه ذخیره یک ارائه در قالب Swf را کنترل می‌کنند.
type: docs
weight: 4550
url: /fa/aspose.slides.export/swfoptions/
---
## SwfOptions کلاس

گزینه‌هایی را فراهم می‌کند که نحوه ذخیره یک ارائه در قالب Swf را کنترل می‌کنند.

```csharp
public class SwfOptions : SaveOptions, ISwfOptions
```

## سازندگان

| نام | توضیح |
| --- | --- |
| [SwfOptions](swfoptions)() | سازنده پیش‌فرض. |

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [Compressed](../../aspose.slides.export/swfoptions/compressed) { get; set; } | مشخص می‌کند که آیا سند SWF تولید شده باید فشرده شود یا نه. پیش‌فرض `true` است. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | فونتی را که در صورت عدم یافتن فونت منبع استفاده می‌شود، باز می‌گرداند یا تنظیم می‌کند. رشته قابل خواندن و نوشتن. |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | منوی زمینه را فعال/غیرفعال می‌کند. پیش‌فرض true است. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | سبک بصری گرادیانت را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | کیفیت تصاویر JPEG را مشخص می‌کند. پیش‌فرض 95 است. |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | تصویری که به عنوان لوگو در گوشه بالا-راست مشاهده‌گر نمایش داده می‌شود. تصویر باید PNG با ابعاد ۳۲×۶۴ پیکسل باشد، در غیر این صورت ممکن است لوگو به درستی نمایش داده نشود. |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | آدرس کامل پیوند برای لوگو را دریافت یا تنظیم می‌کند. فقط در صورتی که [`LogoImageBytes`](./logoimagebytes) مشخص شده باشد مؤثر است. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | یک شیء فراخوانی بازگشتی را برای به‌روزرسانی پیشرفت ذخیره‌سازی به درصد نشان می‌دهد. ببینید [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | نمایش/پنهان‌سازی پانل پایین. می‌تواند در flashvars بازنویسی شود. پیش‌فرض true است. |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | نمایش/پنهان‌سازی دکمه تمام‌صفحه. می‌تواند در flashvars بازنویسی شود. پیش‌فرض true است. |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | مشخص می‌کند که آیا سند تولید شده باید اسلایدهای پنهان را شامل شود یا نه. پیش‌فرض `false` است. |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | نمایش/پنهان‌سازی پانل چپ. می‌تواند در flashvars بازنویسی شود. پیش‌فرض true است. |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | مشخص می‌کند که آیا مرز اطراف صفحات نمایش داده شود یا نه. پیش‌فرض true است. |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | نمایش/پنهان‌سازی پیمایشگر صفحه. می‌تواند در flashvars بازنویسی شود. پیش‌فرض true است. |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | نمایش/پنهان‌سازی بخش جستجو. می‌تواند در flashvars بازنویسی شود. پیش‌فرض true است. |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | نمایش/پنهان‌سازی کل پانل بالا. می‌تواند در flashvars بازنویسی شود. پیش‌فرض true است. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | مشخص می‌کند که آیا هنگام ذخیره ارائه پیوندهای حاوی فراخوانی JavaScript رد شوند یا نه. Boolean قابل خواندن و نوشتن. مقدار پیش‌فرض **false** است. |
| [SlidesLayoutOptions](../../aspose.slides.export/swfoptions/slideslayoutoptions) { get; set; } | حالت قرارگیری اسلایدها بر روی صفحه هنگام صادرات یک ارائه [`ISlidesLayoutOptions`](../islideslayoutoptions) را دریافت یا تنظیم می‌کند. این ویژگی از اختصاص اشیائی از نوع [`HandoutLayoutingOptions`](../handoutlayoutingoptions) پشتیبانی نمی‌کند. |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | با پنل چپ باز شروع می‌شود. می‌تواند در flashvars بازنویسی شود. پیش‌فرض false است. |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | مشخص می‌کند که آیا سند SWF تولید شده باید نمایشگر سند یکپارچه را شامل شود یا نه. پیش‌فرض `true` است. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | یک شیء را باز می‌گرداند یا تنظیم می‌کند که هشارات را دریافت می‌کند و تصمیم می‌گیرد فرآیند بارگذاری ادامه یابد یا لغو شود. [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback) قابل خواندن و نوشتن. |

### مثال‌ها

مثال زیر نشان می‌دهد چگونه PowerPoint به SWF Flash تبدیل می‌شود.

```csharp
[C#]
// یک شی Presentation ایجاد می‌کند که نمایانگر یک فایل ارائه است
using (Presentation presentation = new Presentation("HelloWorld.pptx"))
{
    SwfOptions swfOptions = new SwfOptions();
    swfOptions.ViewerIncluded = false;
    INotesCommentsLayoutingOptions notesOptions = swfOptions.NotesCommentsLayouting;
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    // ذخیره ارائه و صفحات یادداشت‌ها
    presentation.Save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
    swfOptions.ViewerIncluded = true;
    presentation.Save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
}
```

### موارد مرتبط

* کلاس [SaveOptions](../saveoptions)
* رابط [ISwfOptions](../iswfoptions)
* فضای نام [Aspose.Slides.Export](../../aspose.slides.export)
* اسمبل [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->