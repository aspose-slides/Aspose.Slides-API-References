---
title: Shape
second_title: مرجع API لـ Aspose.Sildes .NET
description: يمثل شكلاً على شريحة.
type: docs
weight: 9830
url: /ar/aspose.slides/shape/
---
## فئة Shape

Represents a shape on a slide.

```csharp
public class Shape : IShape
```

## الخصائص

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | تُرجِع أو تُعيّن النص البديل المرتبط بالشكل. قابل للقراءة/الكتابة String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | تُرجِع أو تُعيّن عنوان النص البديل المرتبط بالشكل. قابل للقراءة/الكتابة String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | تحدد الخاصية كيفية عرض الشكل في وضع العرض بالأبيض والأسود. قابل للقراءة/الكتابة [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تُرجِع عدد مواقع الاتصال على الشكل. قراءة فقط Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | تُرجِع البيانات المخصصة للشكل. قراءة فقط [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | تُرجِع كائن EffectFormat الذي يحتوي على التأثيرات البكسلية المطبقة على الشكل. ملاحظة: قد يُرجِع null لبعض أنواع الأشكال التي لا تحتوي على خصائص تأثير. قراءة فقط [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | تُرجِع كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة للشكل. ملاحظة: قد يُرجِع null لبعض أنواع الأشكال التي لا تحتوي على خصائص تعبئة. قراءة فقط [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | تُرجِع أو تُعيّن خصائص إطار الشكل. قابل للقراءة/الكتابة [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | تُعيد أو تُعيّن ارتفاع الشكل، مقاسًا بالنقاط. قابل للقراءة/الكتابة Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | يحدِّد ما إذا كان الشكل مخفيًا. قابل للقراءة/الكتابة Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | تُرجِع أو تُعيّن الارتباط التشعبي المحدد للنقر بالفأرة. قابل للقراءة/الكتابة [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | تُرجِع مدير الارتباط التشعبي. قراءة فقط [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | تُرجِع أو تُعيّن الارتباط التشعبي المحدد للتمرير فوق الفأرة. قابل للقراءة/الكتابة [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | تُعيد أو تُعيّن خيار 'تمييز كديكور'. قابل للقراءة/الكتابة Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | يحدِّد ما إذا كان الشكل مجموعة. قراءة فقط Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | يحدِّد ما إذا كان الشكل TextHolder_PPT. قراءة فقط Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | تُرجِع كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل. ملاحظة: قد يُرجِع null لبعض أنواع الأشكال التي لا تحتوي على خصائص خط. قراءة فقط [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | تُرجِع أو تُعيّن اسم الشكل. يجب ألا يكون فارغًا. استخدم قيمة سلسلة فارغة إذا لزم الأمر. قابل للقراءة/الكتابة String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | تُرجِع معرفًا فريدًا يخص الشريحة يظل ثابتًا طوال عمر الشكل ويسمح لـ PowerPoint أو كود التفاعل بالإشارة إلى الشكل من أي مكان في المستند. قراءة فقط UInt32. أنظر أيضًا [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | تُرجِع كائن GroupShape الأب إذا كان الشكل مُجَمَّعًا. وإلا تُرجِع null. قراءة فقط [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | تُرجِع العنصر النائب للشكل. تُرجِع null إذا لم يكن للشكل عنصر نائب. قراءة فقط [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | تُرجِع العرض الأب للشرائح. قراءة فقط [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | تُرجِع أو تُعيّن خصائص إطار الشكل الخام. قابل للقراءة/الكتابة [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تُرجِع أو تُعيّن عدد الدرجات التي يُدوَّر بها الشكل المحدد حول المحور z. القيمة الموجبة تدل على دوران باتجاه عقارب الساعة؛ والقيمة السالبة تدل على دوران عكس اتجاه العقارب. قابل للقراءة/الكتابة Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | تُرجِع أقفال الشكل. قراءة فقط [`IBaseShapeLock`](../ibaseshapelock). |
| [Slide](../../aspose.slides/shape/slide) { get; } | تُرجِع شريحة الأب للشكل. قراءة فقط [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | تُرجِع كائن ThreeDFormat الذي يحتوي على خصائص تأثير ثلاثي الأبعاد للشكل. ملاحظة: قد يُرجِع null لبعض أنواع الأشكال التي لا تحتوي على خصائص ثلاثية الأبعاد. قراءة فقط [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | تُرجِع معرفًا داخليًا يخص العرض مخصصًا للاستخدام من قبل الإضافات أو أي كود آخر. نظرًا لأن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، لا يجب معاملتها كمفتاح فريد دائم. قراءة فقط UInt32. أنظر أيضًا [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | تُعيد أو تُعيّن عرض الشكل، مقاسًا بالنقاط. قابل للقراءة/الكتابة Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | تُعيد أو تُعيّن إحداثي x للزاوية العليا اليسرى للشكل، مقاسًا بالنقاط. قابل للقراءة/الكتابة Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | تُعيد أو تُعيّن إحداثي y للزاوية العليا اليسرى للشكل، مقاسًا بالنقاط. قابل للقراءة/الكتابة Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | تُرجِع موضع الشكل في ترتيب z. Shapes[0] تُرجِع الشكل الموجود في الخلف من ترتيب z، وShapes[Shapes.Count - 1] تُرجِع الشكل الموجود في المقدمة من ترتيب z. قراءة فقط Int32. |

## الأساليب

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى العنصر المحدد. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | تُرجِع شكلًا عنصرًا نائبًا أساسيًا (شكل من التخطيط و/أو شريحة القالب التي يُورَث منها الشكل الحالي). تُرجِع null إذا لم يكن الشكل الحالي مُورَّثًا. |
| [GetImage](../../aspose.slides/shape/getimage#getimage)() | تُرجِع صورة مصغرة للشكل. يُستخدم النوع ShapeThumbnailBounds.Shape لحدود الصورة المصغرة بشكل افتراضي. |
| [GetImage](../../aspose.slides/shape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | تُرجِع صورة مصغرة للشكل. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | تُعيد حدود الشكل البصرية المحسوبة من محتواه المُرَسَم. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg#writeassvg)(Stream) | يحفظ محتوى الشكل كملف SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | يحفظ محتوى الشكل كملف SVG. |

### راجع أيضًا

* الواجهة [IShape](../ishape)
* النطاق [Aspose.Slides](../../aspose.slides)
* التجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->