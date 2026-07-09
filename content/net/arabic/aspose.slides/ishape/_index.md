---
title: IShape
second_title: Aspose.Sildes لـ .NET مرجع API
description: يمثل شكلاً على شريحة.
type: docs
weight: 6950
url: /ar/aspose.slides/ishape/
---
## IShape الواجهة

يمثل شكلاً على شريحة.

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | إرجاع أو تعيين النص البديل المرتبط بالشكل. قراءة/كتابة String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | إرجاع أو تعيين عنوان النص البديل المرتبط بالشكل. قراءة/كتابة String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | السماح بالحصول على الواجهة الأساسية IHyperlinkContainer. قراءة فقط [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | السماح بالحصول على الواجهة الأساسية ISlideComponent. قراءة فقط [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | الخاصية تحدد كيف سيتم عرض الشكل في وضع العرض بالأبيض والأسود. قراءة/كتابة [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | إرجاع عدد نقاط الاتصال على الشكل. قراءة فقط Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | إرجاع البيانات المخصصة للشكل. قراءة فقط [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | إرجاع كائن EffectFormat الذي يحتوي على التأثيرات البكسلية المطبقة على الشكل. قراءة فقط [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | إرجاع كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة للشكل. قراءة فقط [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | إرجاع أو تعيين خصائص إطار الشكل. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | الحصول على أو تعيين ارتفاع الشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | تحديد ما إذا كان الشكل مخفيًا. قراءة/كتابة Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | الحصول على أو تعيين خيار 'وضع علامة كديكور'. قراءة/كتابة Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | تحديد ما إذا كان الشكل مجمّعًا. قراءة فقط Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | تحديد ما إذا كان الشكل حاملاً للنص. قراءة فقط Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | إرجاع كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل. قراءة فقط [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | إرجاع أو تعيين اسم الشكل. قراءة/كتابة String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | إرجاع معرف فريد ضمن نطاق الشريحة يبقى ثابتًا طوال عمر الشكل ويسمح لـ PowerPoint أو كود التفاعل بالإشارة إلى الشكل من أي مكان في المستند. قراءة فقط UInt32. انظر أيضًا [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | إرجاع كائن GroupShape الأب إذا كان الشكل مجمّعًا. وإلا يرجع قيمة null. قراءة فقط [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | إرجاع العنصر النائب للشكل. قراءة فقط [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | إرجاع أو تعيين خصائص إطار الشكل الخام. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | إرجاع أو تعيين عدد الدرجات التي يتم فيها تدوير الشكل المحدد حول محور z. القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ القيمة السالبة تشير إلى دوران عكس اتجاه العقارب. قراءة/كتابة Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | إرجاع أقفال الشكل. قراءة فقط [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | إرجاع كائن ThreeDFormat الذي يحتوي على خصائص تنسيق الخط للشكل. قراءة فقط [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | إرجاع معرف داخلي ضمن نطاق العرض مخصص للاستخدام من قبل الإضافات أو الكود الآخر. نظرًا لأن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، يجب عدم اعتبارها مفتاحًا فريدًا دائمًا. قراءة فقط UInt32. انظر أيضًا [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/ishape/width) { get; set; } | الحصول على أو تعيين عرض الشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | الحصول على أو تعيين إحداثي x للزاوية العليا اليسرى للشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | الحصول على أو تعيين إحداثي y للزاوية العليا اليسرى للشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | إرجاع موضع الشكل في ترتيب المحور z. Shapes[0] يرجع الشكل في مؤخرة ترتيب z، وShapes[Shapes.Count - 1] يرجع الشكل في مقدمة ترتيب z. قراءة فقط Int32. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب على العنصر المحدد. |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | يرجع شكل عنصر نائب أساسي (الشكل من التخطيط و/أو الشريحة الرئيسة التي يتم وراثة الشكل الحالي منها). يتم إرجاع null إذا لم يكن الشكل الحالي موروثًا. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | يرجع صورة مصغرة للشكل. يتم استخدام النوع ShapeThumbnailBounds.Shape لحدود الصورة المصغرة لل shape بشكل افتراضي. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | يرجع صورة مصغرة للشكل. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | يحفظ محتوى الشكل كملف SVG. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | يحفظ محتوى الشكل كملف SVG. |

### انظر أيضًا

* الواجهة [IHyperlinkContainer](../ihyperlinkcontainer)
* الواجهة [ISlideComponent](../islidecomponent)
* المجال [Aspose.Slides](../../aspose.slides)
* المجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->