---
title: SVGOptions
second_title: Aspose.Sildes لـ .NET مرجع API
description: يمثل خيارات SVG.
type: docs
weight: 4430
url: /ar/aspose.slides.export/svgoptions/
---
## SVGOptions الفئة

يمثل خيارات SVG.

```csharp
public sealed class SVGOptions : SaveOptions, ISVGOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [SVGOptions](svgoptions#constructor)() | يهيئ مثيلاً جديداً من الفئة SVGOptions. |
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | يهيئ مثيلاً جديداً من الفئة SVGOptions مع تحديد كائن وحدة تحكم تضمين الروابط. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | إرجاع الإعدادات الافتراضية. قراءة فقط [`SVGOptions`](../svgoptions). |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | إرجاع الإعدادات لإنشاء أصغر وأبسط ملف SVG. قراءة فقط [`SVGOptions`](../svgoptions). |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | إرجاع الإعدادات لإنشاء ملف SVG بأعلى دقة. قراءة فقط [`SVGOptions`](../svgoptions). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | إرجاع أو تعيين الخط المستخدم في حال عدم العثور على الخط المصدر. قراءة/كتابة String. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | علم منطقي يشير إلى ما إذا كانت الأجزاء المقصوصة تبقى جزءاً من المستند. إذا كان true ستُزال الأجزاء المقصوصة، إذا كان false سيتم تسلسلها في المستند (مما قد يؤدي إلى ملف أكبر). |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | يحدد ما إذا كان النص ثلاثي الأبعاد معطلًا في SVG. قراءة/كتابة Boolean. |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الحروف المتصلة. عند تعيينها إلى `true`، ستُعطل الحروف المتصلة في المخرجات المعروضة. بشكل افتراضي، الخاصية مُعينة إلى `false`. |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | تعطيل تقسيم تدرجات FromCornerX و FromCenter. قراءة/كتابة Boolean. |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | لا يدعم SVG 1.1 القدرة على تعريف الهوامش للعلامات. محرك كتابة Aspose.Slides SVG يحتوي على حل لهذه المشكلة: يقص نهاية الخط بالسهم، وبالتالي لا يتقاطع الخط مع العلامات. هذا الخيار يُغلق هذا السلوك. قراءة/كتابة Boolean. |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | يحدد طريقة معالجة الخطوط المحملة من الخارج. قراءة/كتابة [`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | إرجاع أو تعيين النمط البصري للتدرج. قراءة/كتابة [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | يوفر خيارات تتحكم في مظهر كائنات الحبر في المستند المصدّر. قراءة فقط [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | يحدد جودة ترميز JPEG. قراءة/كتابة Int32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | إرجاع أو تعيين الحد الأدنى لدقة التحويل الطباعي للملفات الوصفية. قراءة/كتابة Int32. |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | يمثل مستوى ضغط الصور |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | يمثل كائن استدعاء للرجوع لتحديثات حفظ التقدم بالنسبة المئوية. انظر [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | إرجاع وتعيين واجهة استدعاء للرجوع التي تسمح للمستخدم بالتحكم في تحويل الشكل. قراءة/كتابة [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | تحديد ما إذا كان يجب تخطي الروابط التشعبية التي تحتوي على استدعاءات JavaScript عند حفظ العرض التقديمي. قراءة/كتابة Boolean. القيمة الافتراضية هي **false**. |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | يحدد ما إذا كان سيتم تنفيذ دوران الشكل المحدد عند العرض أم لا. قراءة/كتابة Boolean. القيمة الافتراضية هي true. |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | يحدد ما إذا كان إطار النص سيُضمّن في منطقة العرض أم لا. قراءة/كتابة Boolean. القيمة الافتراضية هي false. |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | يحدد ما إذا كان النص على الشريحة سيُحفظ كرسومات. قراءة/كتابة Boolean. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | إرجاع أو تعيين كائن يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أم ستُلغى. قراءة/كتابة [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### انظر أيضًا

* الفئة [SaveOptions](../saveoptions)
* الواجهة [ISVGOptions](../isvgoptions)
* المساحة الاسمية [Aspose.Slides.Export](../../aspose.slides.export)
* التجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->