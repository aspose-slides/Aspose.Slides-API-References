---
title: SVGOptions
second_title: مرجع API لـ Aspose.Sildes للـ .NET
description: يمثل خيارات SVG.
type: docs
weight: 4430
url: /ar/aspose.slides.export/svgoptions/
---
## فئة SVGOptions

يمثل خيارات SVG.

```csharp
public sealed class SVGOptions : SaveOptions, ISVGOptions
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [SVGOptions](svgoptions#constructor)() | ينشئ كائنًا جديدًا من فئة SVGOptions. |
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | ينشئ كائنًا جديدًا من فئة SVGOptions مع تحديد كائن وحدة تحكم تضمين الروابط. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | يرجع الإعدادات الافتراضية. للقراءة فقط [`SVGOptions`](../svgoptions). |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | يرجع إعدادات لإنشاء أصغر ملف SVG بأبسط طريقة. للقراءة فقط [`SVGOptions`](../svgoptions). |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | يرجع إعدادات لإنشاء ملف SVG بأعلى دقة. للقراءة فقط [`SVGOptions`](../svgoptions). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | يرجع أو يضبط الخط المستخدم في حال عدم العثور على الخط المصدر. قراءة/كتابة String. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | علامة منطقية تشير إلى ما إذا كانت الأجزاء المقصوصة ستظل جزءًا من المستند. إذا كانت true سيُزال الأجزاء المقصوصة، إذا كانت false سيتم تسلسلها في المستند (مما قد يؤدي إلى ملف أكبر) |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | يحدد ما إذا تم تعطيل النص ثلاثي الأبعاد في SVG. قراءة/كتابة Boolean. |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان يتم عرض النص دون استخدام الأحرف المتصلة. عند تعيينه إلى `true`، سيتم تعطيل الأحرف المتصلة في الناتج المعروض. بشكل افتراضي، تكون الخاصية مُعينة إلى `false`. |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | يعطل تقسيم تدرجات FromCornerX و FromCenter. قراءة/كتابة Boolean. |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | لا يملك SVG 1.1 القدرة على تعريف الهوامش للعلامات. محرك كتابة SVG الخاص بـ Aspose.Slides يحتوي على حل لهذه المشكلة: يقطع نهاية الخط مع السهم، بحيث لا يتداخل الخط مع العلامات. هذا الخيار يعطل هذا السلوك. قراءة/كتابة Boolean. |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | يحدد طريقة التعامل مع الخطوط المحملة خارجيًا. قراءة/كتابة [`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | يرجع أو يضبط النمط البصري للتدرج. قراءة/كتابة [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | يوفر خيارات تتحكم في مظهر كائنات الحبر في المستند المُصدَّر. للقراءة فقط [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | يحدد جودة ترميز JPEG. قراءة/كتابة Int32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | يرجع أو يضبط الحد الأدنى للقرار لتفعيل التحويل النقطي لملف الميتافيل. قراءة/كتابة Int32. |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | يمثل مستوى ضغط الصور |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | يمثل كائن استدعاء رجعي لتحديثات حفظ التقدم بالنسبة المئوية. راجع [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | يرجع ويضبط واجهة استدعاء رجعي تتيح للمستخدم التحكم في تحويل الشكل. قراءة/كتابة [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | يحدد ما إذا كان يجب تخطي الروابط ذات استدعاءات JavaScript عند حفظ العرض التقديمي. قراءة/كتابة Boolean. القيمة الافتراضية هي **false**. |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | يحدد ما إذا كان سيتم تنفيذ الدوران المحدد للشكل عند العرض أم لا. قراءة/كتابة Boolean. القيمة الافتراضية هي true. |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | يحدد ما إذا كان إطار النص سيُدرج في منطقة العرض أم لا. قراءة/كتابة Boolean. القيمة الافتراضية هي false. |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | يحدد ما إذا كان النص على الشريحة سيُحفظ كرسومات. قراءة/كتابة Boolean. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | يرجع أو يضبط كائنًا يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أم ستُوقف. قراءة/كتابة [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### انظر أيضًا

* فئة [SaveOptions](../saveoptions)
* واجهة [ISVGOptions](../isvgoptions)
* نطاق [Aspose.Slides.Export](../../aspose.slides.export)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->