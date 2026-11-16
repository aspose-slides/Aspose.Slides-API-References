---
title: IShape
second_title: Aspose.Sildes لتوثيق API لـ .NET
description: يمثل شكلاً على شريحة.
type: docs
weight: 6970
url: /ar/aspose.slides/ishape/
---
## واجهة IShape

يمثل شكلاً على شريحة.

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | ترجع أو تعين النص البديل المرتبط بالشكل. قراءة/كتابة String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | ترجع أو تعين عنوان النص البديل المرتبط بالشكل. قراءة/كتابة String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | يسمح بالحصول على واجهة IHyperlinkContainer الأساسية. قراءة فقط [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | يسمح بالحصول على واجهة ISlideComponent الأساسية. قراءة فقط [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | الخاصية تحدد كيفية عرض الشكل في وضع أبيض-أسود. قراءة/كتابة [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | ترجع عدد نقاط الاتصال على الشكل. قراءة فقط Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | ترجع البيانات المخصصة للشكل. قراءة فقط [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | ترجع كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على الشكل. قراءة فقط [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | ترجع كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة للشكل. قراءة فقط [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | ترجع أو تعين خصائص إطار الشكل. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | تحصل أو تعين ارتفاع الشكل، مقاساً بالنقاط. قراءة/كتابة Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | تحدد ما إذا كان الشكل مخفيًا. قراءة/كتابة Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | تحصل أو تعين خيار 'Mark as decorative'. قراءة/كتابة Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | تحدد ما إذا كان الشكل مجموعًا. قراءة فقط Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | تحدد ما إذا كان الشكل TextHolder. قراءة فقط Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | ترجع كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل. قراءة فقط [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | ترجع أو تعين اسم الشكل. قراءة/كتابة String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | ترجع معرفًا فريدًا ضمن الشريحة يبقى ثابتًا طوال عمر الشكل ويسمح لبرنامج PowerPoint أو كود التفاعل بالإشارة إلى الشكل من أي مكان في المستند. قراءة فقط UInt32. انظر أيضًا [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | ترجع كائن GroupShape الأصل إذا كان الشكل مجموعًا. وإلا ترجع null. قراءة فقط [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | ترجع العنصر النائب للشكل. قراءة فقط [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | ترجع أو تعين خصائص إطار الشكل الخام. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | ترجع أو تعين عدد الدرجات التي يتم فيها تدوير الشكل المحدد حول محور z. القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ القيمة السالبة تشير إلى دوران عكس اتجاه عقارب الساعة. قراءة/كتابة Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | ترجع أقفال الشكل. قراءة فقط [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | ترجع كائن ThreeDFormat الذي يحتوي على خصائص تنسيق الخط للشكل. قراءة فقط [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | ترجع معرفًا داخليًا ضمن العرض مخصصًا للاستخدام من قبل الإضافات أو الكود الآخر. نظرًا لأن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، لا ينبغي أن تُعامل كمفتاح فريد دائم. قراءة فقط UInt32. انظر أيضًا [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/ishape/width) { get; set; } | تحصل أو تعين عرض الشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | تحصل أو تعين الإحداثي x للزاوية العليا اليسرى للشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | تحصل أو تعين الإحداثي y للزاوية العليا اليسرى للشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | ترجع موضع الشكل في ترتيب z. Shapes[0] تعيد الشكل في مؤخرة ترتيب z، و Shapes[Shapes.Count - 1] تعيد الشكل في مقدمة ترتيب z. قراءة فقط Int32. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويعيّن خصائص العنصر النائب إلى معين. |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | ترجع شكل عنصر نائب أساسي (شكل من تخطيط و/أو شريحة رئيسية يرث منه الشكل الحالي). تُرجع null إذا لم يكن الشكل الحالي مُورّثًا. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | ترجع صورة مصغرة للشكل. يُستخدم النوع ShapeThumbnailBounds.Shape للحدود المصغرة بشكل افتراضي. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | ترجع صورة مصغرة للشكل. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | يحدد أن هذا الشكل ليس عنصراً قابلاً للأنابة. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | يحفظ محتوى الشكل كملف SVG. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | يحفظ محتوى الشكل كملف SVG. |

### انظر أيضًا

* واجهة [IHyperlinkContainer](../ihyperlinkcontainer)
* واجهة [ISlideComponent](../islidecomponent)
* نطاق [Aspose.Slides](../../aspose.slides)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->