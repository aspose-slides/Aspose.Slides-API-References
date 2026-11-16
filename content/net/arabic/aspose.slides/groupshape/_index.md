---
title: GroupShape
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: يمثل مجموعة من الأشكال على شريحة.
type: docs
weight: 5110
url: /ar/aspose.slides/groupshape/
---
## GroupShape فئة

يمثل مجموعة من الأشكال على شريحة.

```csharp
public class GroupShape : Shape, IGroupShape
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | تُرجِع أو تُعيّن النص البديل المرتبط بشكَل. قراءة/كتابة String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | تُرجِع أو تُعيّن عنوان النص البديل المرتبط بشكَل. قراءة/كتابة String. |
| [AsIShape](../../aspose.slides/groupshape/asishape) { get; } | يسمح بالحصول على واجهة IShape الأساسية. قراءة فقط [`IShape`](../ishape). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | الخاصية تحدد طريقة عرض الشكل في وضع العرض بالأبيض والأسود. قراءة/كتابة [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تُرجِع عدد نقاط الاتصال على الشكل. قراءة فقط Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | تُرجِع البيانات المخصصة للشكل. قراءة فقط [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | تُرجِع كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على الشكل. ملاحظة: قد يُرجع null لبعض أنواع الأشكال التي لا تمتلك خصائص تأثير. قراءة فقط [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | تُرجِع كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة لشكل. ملاحظة: قد يُرجع null لبعض أنواع الأشكال التي لا تمتلك خصائص تعبئة. قراءة فقط [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | تُرجِع أو تُعيّن خصائص إطار الشكل. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [GroupShapeLock](../../aspose.slides/groupshape/groupshapelock) { get; } | تُرجِع أقفال الشكل. قراءة فقط [`IGroupShapeLock`](../igroupshapelock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | تُعيد أو تُعيّن ارتفاع الشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | يحدّد ما إذا كان الشكل مخفيًا. قراءة/كتابة Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | تُرجِع أو تُعيّن الارتباط التشعبي المحدد للنقر بالماوس. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | تُرجِع مدير الارتباطات التشعبية. قراءة فقط [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | تُرجِع أو تُعيّن الارتباط التشعبي المحدد للتحويم بالماوس. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | تُعيد أو تُعيّن خيار 'Mark as decorative'. قراءة/كتابة Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | يحدّد ما إذا كان الشكل مجموعة. قراءة فقط Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | يحدّد ما إذا كان الشكل TextHolder_PPT. قراءة فقط Boolean. |
| override [LineFormat](../../aspose.slides/groupshape/lineformat) { get; } | تُرجِع كائن LineFormat الذي يحتوي على خصائص تنسيق الخط لشكل. ملاحظة: يُرجع null لكائنات GroupShape لأنها لا تمتلك خواص خط. قراءة فقط [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | تُرجِع أو تُعيّن اسم الشكل. يجب ألا يكون فارغًا. استخدم قيمة سلسلة فارغة إذا لزم الأمر. قراءة/كتابة String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | تُرجِع معرّفًا فريدًا ضمن الشريحة يبقى ثابتًا طوال عمر الشكل ويسمح لـ PowerPoint أو كود التفاعل بالإشارة إلى الشكل من أي مكان داخل المستند. قراءة فقط UInt32. أنظر أيضًا [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | تُرجِع كائن GroupShape الأصل إذا كان الشكل مجموعة. وإلا تُرجع null. قراءة فقط [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | تُرجِع العنصر النائب للشكل. تُرجع null إذا لم يكن للشكل عنصر نائب. قراءة فقط [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | تُرجِع عرض الشرائح الأصل للشفرة. قراءة فقط [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | تُرجِع أو تُعيّن خصائص إطار الشكل الخام. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تُرجِع أو تُعيّن عدد الدرجات التي يُدوّر فيها الشكل المحدد حول محور z. قيمة موجبة تعني دوران باتجاه عقارب الساعة؛ قيمة سالبة تعني دوران عكس عقارب الساعة. قراءة/كتابة Single. |
| [ShapeLock](../../aspose.slides/groupshape/shapelock) { get; } | تُرجِع أقفال الشكل. قراءة فقط [`IGroupShapeLock`](../igroupshapelock). (2 خاصية) |
| [Shapes](../../aspose.slides/groupshape/shapes) { get; } | تُرجِع مجموعة الأشكال داخل المجموعة. قراءة فقط [`IShapeCollection`](../ishapecollection). |
| [Slide](../../aspose.slides/shape/slide) { get; } | تُرجِع الشريحة الأصلية للشكل. قراءة فقط [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | تُرجِع كائن ThreeDFormat الذي يحتوي على خصائص التأثير ثلاثي الأبعاد للشكل. ملاحظة: قد يُرجع null لبعض أنواع الأشكال التي لا تمتلك خصائص ثلاثية الأبعاد. قراءة فقط [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | تُرجِع معرفًا داخليًا ضمن العرض مخصصًا للاستخدام من قبل الإضافات أو كود آخر. بما أن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، فلا يجب اعتبارها مفتاحًا فريدًا دائمًا. قراءة فقط UInt32. أنظر أيضًا [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | تُعيد أو تُعيّن عرض الشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | تُعيد أو تُعيّن الإحداثي السيني للزاوية العليا اليسرى للشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | تُعيد أو تُعيّن الإحداثي الصادي للزاوية العليا اليسرى للشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | تُرجِع موضع الشكل في ترتيب z. Shapes[0] تُرجع الشكل في الخلفية، وShapes[Shapes.Count - 1] تُرجع الشكل في المقدمة. قراءة فقط Int32. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى عنصر محدد. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | تُرجِع شكلًا نائبًا أساسيًا (شكل من التخطيط و/أو شريحة القالب التي يُورث منها الشكل الحالي). تُرجع null إذا لم يكن الشكل الحالي مُورَثًا. |
| [GetImage](../../aspose.slides/shape/getimage)() | تُرجِع صورة مصغرة للشكل. يُستخدم النوع ShapeThumbnailBounds.Shape لحدود الصورة المصغرة بشكل افتراضي. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تُرجِع صورة مصغرة للشكل. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | تُعيد حدود الشكل المرئية المحسوبة من المحتوى المُعرض. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | يحدّد أن هذا الشكل ليس عنصرًا نائبًا. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | يحفظ محتوى الشكل كملف SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | يحفظ محتوى الشكل كملف SVG. |

### أنظر أيضًا

* فئة [Shape](../shape)
* واجهة [IGroupShape](../igroupshape)
* مساحة الاسم [Aspose.Slides](../../aspose.slides)
* التجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->