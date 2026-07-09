---
title: SwfOptions
second_title: Aspose.Sildes لـ .NET مرجع API
description: يوفر خيارات تتحكم في كيفية حفظ عرض تقديمي بتنسيق Swf.
type: docs
weight: 4530
url: /ar/aspose.slides.export/swfoptions/
---
## فئة SwfOptions

يوفر خيارات تتحكم في كيفية حفظ العرض التقديمي بتنسيق Swf.

```csharp
public class SwfOptions : SaveOptions, ISwfOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [SwfOptions](swfoptions)() | منشئ افتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Compressed](../../aspose.slides.export/swfoptions/compressed) { get; set; } | يحدد ما إذا كان يجب ضغط المستند SWF الناتج أم لا. القيمة الافتراضية هي `true`. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | يعيد أو يضبط الخط المستخدم في حالة عدم العثور على الخط الأصلي. قابل للقراءة والكتابة String. |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | تمكين/تعطيل قائمة السياق. القيمة الافتراضية هي true. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | يعيد أو يضبط النمط البصري للتدرج. قابل للقراءة/الكتابة [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | يحدد جودة صور JPEG. القيمة الافتراضية هي 95. |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | الصورة التي سيتم عرضها كشعار في الزاوية العلوية اليمنى للعارض. يجب أن تكون الصورة PNG بمقاس 32x64 بكسل، وإلا قد يُعرض الشعار بشكل غير صحيح. |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | يعيد أو يضبط عنوان الارتباط الكامل للشعار. له تأثير فقط إذا تم تحديد [`LogoImageBytes`](./logoimagebytes). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | يمثل كائن استدعاء للرجوع لتحديثات تقدم الحفظ بالنسبة المئوية. راجع [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | إظهار/إخفاء اللوحة السفلية. يمكن تجاوزها في flashvars. القيمة الافتراضية هي true. |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | إظهار/إخفاء زر ملء الشاشة. يمكن تجاوزها في flashvars. القيمة الافتراضية هي true. |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | يحدد ما إذا كان يجب أن يتضمن المستند الناتج الشرائح المخفية أم لا. القيمة الافتراضية هي `false`. |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | إظهار/إخفاء اللوحة اليسرى. يمكن تجاوزها في flashvars. القيمة الافتراضية هي true. |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | يحدد ما إذا كان يجب إظهار الحد حول الصفحات. القيمة الافتراضية هي true. |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | إظهار/إخفاء متحكم الصفحات. يمكن تجاوزها في flashvars. القيمة الافتراضية هي true. |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | إظهار/إخفاء قسم البحث. يمكن تجاوزها في flashvars. القيمة الافتراضية هي true. |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | إظهار/إخفاء اللوحة العلوية بالكامل. يمكن تجاوزها في flashvars. القيمة الافتراضية هي true. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | يحدد ما إذا كان يجب تخطي الروابط التي تحتوي على استدعاءات JavaScript عند حفظ العرض التقديمي. قابل للقراءة/الكتابة Boolean. القيمة الافتراضية هي **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/swfoptions/slideslayoutoptions) { get; set; } | يعيد أو يضبط الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير العرض التقديمي [`ISlidesLayoutOptions`](../islideslayoutoptions). هذه الخاصية لا تدعم تعيين كائنات من النوع [`HandoutLayoutingOptions`](../handoutlayoutingoptions) |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | ابدأ باللوحة اليسرى المفتوحة. يمكن تجاوزها في flashvars. القيمة الافتراضية هي false. |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | يحدد ما إذا كان يجب أن يتضمن المستند SWF الناتج عارض الوثائق المدمج أم لا. القيمة الافتراضية هي `true`. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | يعيد أو يضبط كائنًا يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أم ستُجهَز. قابل للقراءة/الكتابة [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### أمثلة

يعرض المثال التالي كيفية تحويل PowerPoint إلى SWF Flash.

```csharp
[C#]
// إنشاء كائن Presentation يمثل ملف عرض تقديمي
using (Presentation presentation = new Presentation("HelloWorld.pptx"))
{
    SwfOptions swfOptions = new SwfOptions();
    swfOptions.ViewerIncluded = false;
    INotesCommentsLayoutingOptions notesOptions = swfOptions.NotesCommentsLayouting;
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    // حفظ العرض التقديمي وصفحات الملاحظات
    presentation.Save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
    swfOptions.ViewerIncluded = true;
    presentation.Save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
}
```

### انظر أيضا

* فئة [SaveOptions](../saveoptions)
* واجهة [ISwfOptions](../iswfoptions)
* مساحة أسماء [Aspose.Slides.Export](../../aspose.slides.export)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->