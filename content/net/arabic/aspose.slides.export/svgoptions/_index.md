---
title: SVGOptions
second_title: مرجع API الخاص بـ Aspose.Sildes لـ .NET
description: تمثّل خيارات SVG.
type: docs
weight: 4450
url: /ar/aspose.slides.export/svgoptions/
---
## فئة SVGOptions

تمثل خيارات SVG.

```csharp
public sealed class SVGOptions : SaveOptions, ISVGOptions
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [SVGOptions](svgoptions#constructor)() | يهيئ مثيلًا جديدًا من فئة SVGOptions. |
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | يهيئ مثيلًا جديدًا من فئة SVGOptions مع تحديد كائن مراقب تضمين الرابط. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | يرجع الإعدادات الافتراضية. للقراءة فقط [`SVGOptions`](../svgoptions). |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | يرجع الإعدادات لتوليد أصغر وأبسط ملف SVG. للقراءة فقط [`SVGOptions`](../svgoptions). |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | يرجع الإعدادات لتوليد ملف SVG بأعلى دقة. للقراءة فقط [`SVGOptions`](../svgoptions). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | يرجع أو يضبط الخط المستخدم في حالة عدم العثور على الخط المصدر. قراءة/كتابة String. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | إشارة منطقية تشير إلى ما إذا كانت الأجزاء المقصوصة تبقى جزءًا من المستند. إذا كان true سيتم إزالة الأجزاء المقصوصة، وإذا كان false فسيتم تسلسلها في المستند (مما قد يؤدي إلى ملف أكبر) |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | يحدد ما إذا كان نص 3D معطلًا في SVG. قراءة/كتابة Boolean. |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان النص يُعرض بدون استعمال الروابط الحرفية. عند تعيينه إلى `true`، ستُعطل الروابط الحرفية في الناتج المعروض. افتراضيًا، تُعيَّن هذه الخاصية إلى `false`. |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | يعطل تقسيم تدرجات FromCornerX و FromCenter. قراءة/كتابة Boolean. |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | تفتقر SVG 1.1 إلى القدرة على تعريف هوامش للعلامات. تمتلك محرك كتابة SVG في Aspose.Slides حلاً لهذه المشكلة: يقوم بقص نهاية الخط مع السهم، بحيث لا يتداخل الخط مع العلامات. هذا الخيار يعطل هذا السلوك. قراءة/كتابة Boolean. |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | يحدد طريقة معالجة الخطوط المحملة خارجيًا. قراءة/كتابة [`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | يرجع أو يضبط النمط البصري للتدرج. قراءة/كتابة [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | يوفر خيارات تتحكم في مظهر كائنات الحبر في المستند المصدر. للقراءة فقط [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | يحدد جودة ترميز JPEG. قراءة/كتابة Int32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | يرجع أو يضبط الحد الأدنى لدقة تحويل ملفات الميتافايل إلى نقطية. قراءة/كتابة Int32. |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | يمثل مستوى ضغط الصور |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | يمثل كائنًا للاتصال العكسي لتحديثات حفظ التقدم بالنسبة المئوية. راجع [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | يرجع ويضبط واجهة اتصال عكسي تسمح للمستخدم بالتحكم في تحويل الشكل. قراءة/كتابة [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | يحدد ما إذا كان سيتم تخطي الروابط التشعبية التي تحتوي على استدعاءات JavaScript عند حفظ العرض التقديمي. قراءة/كتابة Boolean. القيمة الافتراضية هي **false**. |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | يحدد ما إذا كان سيتم تنفيذ الدوران المحدد للشكل أثناء العرض أم لا. قراءة/كتابة Boolean. القيمة الافتراضية هي true. |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | يحدد ما إذا كان إطار النص سيُضمّن في منطقة العرض أم لا. قراءة/كتابة Boolean. القيمة الافتراضية هي false. |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | يحدد ما إذا كان النص على الشريحة سيُحفظ كرسومات. قراءة/كتابة Boolean. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | يرجع أو يضبط كائنًا يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أم ستُلغى. قراءة/كتابة [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### انظر أيضًا

* الفئة [SaveOptions](../saveoptions)
* الواجهة [ISVGOptions](../isvgoptions)
* نطاق [Aspose.Slides.Export](../../aspose.slides.export)
* التجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->