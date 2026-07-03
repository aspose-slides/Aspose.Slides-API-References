---
title: Shape
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: يمثل شكلاً على شريحة.
type: docs
weight: 9830
url: /ar/aspose.slides/shape/
---
## الفئة Shape

يمثل شكلاً على شريحة.

```csharp
public class Shape : IShape
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | إرجاع أو تعيين النص البديل المرتبط بالشكل. قراءة/كتابة String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | إرجاع أو تعيين عنوان النص البديل المرتبط بالشكل. قراءة/كتابة String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | الخاصة تحدد كيفية عرض الشكل في وضع العرض بالأبيض والأسود.. قراءة/كتابة [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | إرجاع عدد نقاط الاتصال على الشكل. قراءة فقط Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | إرجاع البيانات المخصصة للشكل. قراءة فقط [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | إرجاع كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على الشكل. ملاحظة: قد يُرجع null لبعض أنواع الأشكال التي لا تحتوي على خصائص تأثير. قراءة فقط [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | إرجاع كائن FillFormat الذي يحتوي على خصائص تنسيق الملء للشكل. ملاحظة: قد يُرجع null لبعض أنواع الأشكال التي لا تحتوي على خصائص ملء. قراءة فقط [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | إرجاع أو تعيين خصائص إطار الشكل. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | إرجاع أو تعيين ارتفاع الشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | تحديد ما إذا كان الشكل مخفيًا. قراءة/كتابة Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | إرجاع أو تعيين الارتباط التشعبي المحدد للنقر بالفأرة. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | إرجاع مدير الارتباط التشعبي. قراءة فقط [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | إرجاع أو تعيين الارتباط التشعبي المحدد للتمرير فوق الفأرة. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | إرجاع أو تعيين خيار 'Mark as decorative'. قراءة/كتابة Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | تحديد ما إذا كان الشكل مجموعة. قراءة فقط Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | تحديد ما إذا كان الشكل هو TextHolder_PPT. قراءة فقط Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | إرجاع كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل. ملاحظة: قد يُرجع null لبعض أنواع الأشكال التي لا تحتوي على خصائص خط. قراءة فقط [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | إرجاع أو تعيين اسم الشكل. يجب ألا يكون null. استخدم قيمة سلسلة فارغة إذا لزم الأمر. قراءة/كتابة String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | إرجاع معرف فريد محصور بالشرائح يبقى ثابتًا طوال عمر الشكل ويسمح لـ PowerPoint أو كود التفاعل بالرجوع إلى الشكل من أي مكان في المستند. قراءة فقط UInt32. انظر أيضًا [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | إرجاع كائن GroupShape الأب إذا كان الشكل مجموعة. وإلا يُرجع null. قراءة فقط [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | إرجاع العنصر النائب للشكل. يُرجع null إذا لم يكن للشكل عنصر نائب. قراءة فقط [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | إرجاع العرض التقديمي الأب للشرائح. قراءة فقط [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | إرجاع أو تعيين خصائص إطار الشكل الخام. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | إرجاع أو تعيين عدد الدرجات التي يتم تدوير الشكل المحدد حول محور z. القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ القيمة السالبة تشير إلى دوران عكس اتجاه العقارب. قراءة/كتابة Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | إرجاع أقفال الشكل. قراءة فقط [`IBaseShapeLock`](../ibaseshapelock). |
| [Slide](../../aspose.slides/shape/slide) { get; } | إرجاع الشريحة الأم للشكل. قراءة فقط [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | إرجاع كائن ThreeDFormat الذي يحتوي على خصائص تأثير ثلاثي الأبعاد للشكل. ملاحظة: قد يُرجع null لبعض أنواع الأشكال التي لا تحتوي على خصائص ثلاثية الأبعاد. قراءة فقط [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | إرجاع معرف داخلي محصور بالعرض التقديمي مخصص للاستخدام من قبل الإضافات أو كود آخر. نظرًا لأن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، فلا ينبغي اعتبارها مفتاحًا فريدًا دائمًا. قراءة فقط UInt32. انظر أيضًا [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | إرجاع أو تعيين عرض الشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | إرجاع أو تعيين إحداثي x لزاوية الشكل العليا اليسرى، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | إرجاع أو تعيين إحداثي y لزاوية الشكل العليا اليسرى، مقاسًا بالنقاط. قراءة/كتابة Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | إرجاع موضع الشكل في ترتيب z. Shapes[0] تُرجع الشكل في الخلفية، وShapes[Shapes.Count - 1] تُرجع الشكل في المقدمة. قراءة فقط Int32. |

## الأساليب

| الاسم | الوصف |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى المحدد. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | إرجاع شكل عنصر نائب أساسي (شكل من التخطيط و/أو الشريحة الأصل التي يرث منها الشكل الحالي). يُرجع null إذا لم يكن الشكل الحالي وراثيًا. |
| [GetImage](../../aspose.slides/shape/getimage#getimage)() | إرجاع صورة مصغرة للشكل. يُستخدم النوع ShapeThumbnailBounds.Shape كحدود الصورة المصغرة بشكل افتراضي. |
| [GetImage](../../aspose.slides/shape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | إرجاع صورة مصغرة للشكل. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | إرجاع حدود الشكل البصرية المحسوبة من محتواه المعروض. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg#writeassvg)(Stream) | يحفظ محتوى الشكل كملف SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | يحفظ محتوى الشكل كملف SVG. |

### راجع أيضًا

* الواجهة [IShape](../ishape)
* النطاق [Aspose.Slides](../../aspose.slides)
* التجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->