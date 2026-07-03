---
title: SwfOptions
second_title: مرجع API Aspose.Sildes لـ .NET
description: يوفر خيارات تتحكم في طريقة حفظ عرض تقديمي بتنسيق Swf.
type: docs
weight: 4530
url: /ar/aspose.slides.export/swfoptions/
---
## فئة SwfOptions

يوفر خيارات تتحكم في طريقة حفظ عرض تقديمي بتنسيق Swf.

```csharp
public class SwfOptions : SaveOptions, ISwfOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [SwfOptions](swfoptions)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Compressed](../../aspose.slides.export/swfoptions/compressed) { get; set; } | يحدد ما إذا كان يجب ضغط مستند SWF الذي تم إنشاؤه أم لا. القيمة الافتراضية هي `true`. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | يعيد أو يعيّن الخط المستخدم في حالة عدم العثور على الخط الأصلي. سلسلة قابل للقراءة والكتابة. |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | تمكين/تعطيل قائمة السياق. القيمة الافتراضية هي true. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | يعيد أو يعيّن النمط البصري للمتدرج. قابل للقراءة والكتابة [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | يحدد جودة صور JPEG. القيمة الافتراضية هي 95. |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | الصورة التي سيتم عرضها كشعار في الزاوية العلوية اليمنى للعارض. يجب أن تكون الصورة PNG بحجم 32×64 بكسل، وإلا قد يتم عرض الشعار بشكل غير صحيح. |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | يعيد أو يعيّن عنوان الارتباط الكامل لشعار. له تأثير فقط إذا تم تحديد [`LogoImageBytes`](./logoimagebytes). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | يمثل كائنًا رد نداء لتحديثات تقدم الحفظ بالنسبة المئوية. انظر [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | إظهار/إخفاء الجزء السفلي. يمكن تجاوزه في flashvars. القيمة الافتراضية هي true. |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | إظهار/إخفاء زر ملء الشاشة. يمكن تجاوزه في flashvars. القيمة الافتراضية هي true. |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | يحدد ما إذا كان المستند المُنشأ يجب أن يتضمن الشرائح المخفية أم لا. القيمة الافتراضية هي `false`. |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | إظهار/إخفاء الجزء الأيسر. يمكن تجاوزه في flashvars. القيمة الافتراضية هي true. |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | يحدد ما إذا كان يجب إظهار الحدود حول الصفحات. القيمة الافتراضية هي true. |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | إظهار/إخفاء أداة التنقل بين الصفحات. يمكن تجاوزه في flashvars. القيمة الافتراضية هي true. |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | إظهار/إخفاء قسم البحث. يمكن تجاوزه في flashvars. القيمة الافتراضية هي true. |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | إظهار/إخفاء الجزء العلوي بالكامل. يمكن تجاوزه في flashvars. القيمة الافتراضية هي true. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | يحدد ما إذا كان يجب تخطي الروابط ذات استدعاءات JavaScript عند حفظ العرض التقديمي. منطقي قابل للقراءة والكتابة. القيمة الافتراضية هي **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/swfoptions/slideslayoutoptions) { get; set; } | يعيد أو يعيّن الوضع الذي توضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [`ISlidesLayoutOptions`](../islideslayoutoptions). لا يدعم هذا الخاصية تعيين كائنات من النوع [`HandoutLayoutingOptions`](../handoutlayoutingoptions) |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | ابدأ بالجزء الأيسر المفتوح. يمكن تجاوزه في flashvars. القيمة الافتراضية هي false. |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | يحدد ما إذا كان يجب أن يتضمن مستند SWF المُنشئ عارض المستندات المدمج أم لا. القيمة الافتراضية هي `true`. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | يعيد أو يعيّن كائنًا يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أم ستُجهض. قابل للقراءة والكتابة [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### أمثلة

المثال التالي يوضح كيفية تحويل PowerPoint إلى SWF Flash.

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

### انظر أيضاً

* فئة [SaveOptions](../saveoptions)
* واجهة [ISwfOptions](../iswfoptions)
* مساحة اسم [Aspose.Slides.Export](../../aspose.slides.export)
* مجموعة تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->