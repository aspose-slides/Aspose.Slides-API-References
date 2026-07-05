---
title: GroupShape
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: يمثل مجموعة من الأشكال على شريحة.
type: docs
weight: 5090
url: /ar/aspose.slides/groupshape/
---
## GroupShape فئة

يمثل مجموعة من الأشكال على الشريحة.

```csharp
public class GroupShape : Shape, IGroupShape
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | يعيد أو يعيّن النص البديل المرتبط بالشكل. قراءة/كتابة String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | يعيد أو يعيّن عنوان النص البديل المرتبط بالشكل. قراءة/كتابة String. |
| [AsIShape](../../aspose.slides/groupshape/asishape) { get; } | يتيح الحصول على واجهة IShape الأساسية. قراءة فقط [`IShape`](../ishape). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | تحدد الخاصية كيفية عرض الشكل في وضع العرض بالأبيض والأسود.. قراءة/كتابة [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | يعيد عدد نقاط الاتصال على الشكل. قراءة فقط Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | يعيد بيانات الشكل المخصصة. قراءة فقط [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | يعيد كائن EffectFormat الذي يحتوي على التأثيرات البكسلية المطبقة على الشكل. ملاحظة: قد يُعيد null لأنواع معينة من الأشكال التي لا تملك خصائص تأثير. قراءة فقط [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | يعيد كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة للشكل. ملاحظة: قد يُعيد null لأنواع معينة من الأشكال التي لا تملك خصائص تعبئة. قراءة فقط [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | يعيد أو يعيّن خصائص إطار الشكل. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [GroupShapeLock](../../aspose.slides/groupshape/groupshapelock) { get; } | يعيد أقفال الشكل. قراءة فقط [`IGroupShapeLock`](../igroupshapelock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | يحصل أو يعيّن ارتفاع الشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | يحدد ما إذا كان الشكل مخفيًا. قراءة/كتابة Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | يعيد أو يعيّن الارتباط التشعبي المحدد للنقر بالماوس. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | يعيد مدير الارتباط التشعبي. قراءة فقط [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | يعيد أو يعيّن الارتباط التشعبي المحدد لتحوم الماوس فوقه. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | يحصل أو يعيّن خيار 'Mark as decorative'. قراءة/كتابة Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | يحدد ما إذا كان الشكل مجمعًا. قراءة فقط Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | يحدد ما إذا كان الشكل TextHolder_PPT. قراءة فقط Boolean. |
| override [LineFormat](../../aspose.slides/groupshape/lineformat) { get; } | يعيد كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل. ملاحظة: يُعيد null لكائنات GroupShape لأنها لا تملك خصائص خط. قراءة فقط [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | يعيد أو يعيّن اسم الشكل. يجب ألا يكون فارغًا. استخدم قيمة سلسلة فارغة إذا لزم الأمر. قراءة/كتابة String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | يعيد معرفًا فريدًا محصورًا بالشريحة يبقى ثابتًا طوال عمر الشكل ويسمح لبرنامج PowerPoint أو كود التفاعل بالإشارة إلى الشكل من أي مكان في المستند. قراءة فقط UInt32. انظر أيضًا [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | يعيد كائن GroupShape الأصل إذا كان الشكل مجمعًا. وإلا يُعيد null. قراءة فقط [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | يعيد العنصر النائب للشكل. يُعيد null إذا لم يكن للشكل عنصر نائب. قراءة فقط [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | يعيد العرض التقديمي الأب للشفرة. قراءة فقط [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | يعيد أو يعيّن خصائص إطار الشكل الخام. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | يعيد أو يعيّن عدد درجات دوران الشكل المحدد حول المحور z. القيمة الموجبة تشير إلى دوران مع عقارب الساعة؛ القيمة السالبة تشير إلى دوران عكس عقارب الساعة. قراءة/كتابة Single. |
| [ShapeLock](../../aspose.slides/groupshape/shapelock) { get; } | يعيد أقفال الشكل. قراءة فقط [`IGroupShapeLock`](../igroupshapelock). (2 خصائص) |
| [Shapes](../../aspose.slides/groupshape/shapes) { get; } | يعيد مجموعة الأشكال داخل المجموعة. قراءة فقط [`IShapeCollection`](../ishapecollection). |
| [Slide](../../aspose.slides/shape/slide) { get; } | يعيد الشريحة الأم للشكل. قراءة فقط [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | يعيد كائن ThreeDFormat الذي يحتوي على خصائص التأثير ثلاثي الأبعاد للشكل. ملاحظة: قد يُعيد null لأنواع معينة من الأشكال التي لا تملك خصائص ثلاثية الأبعاد. قراءة فقط [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | يعيد معرفًا داخليًا محصورًا بالعرض التقديمي مخصصًا لاستخدام الإضافات أو كود آخر. لأن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، لا ينبغي اعتبارها مفتاحًا فريدًا دائمًا. قراءة فقط UInt32. انظر أيضًا [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | يحصل أو يعيّن عرض الشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | يحصل أو يعيّن الإحداثي x للزاوية اليسرى العليا للشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | يحصل أو يعيّن الإحداثي y للزاوية اليسرى العليا للشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | يعيد موضع الشكل في ترتيب الـ z. Shapes[0] تُعيد الشكل الخلفي في ترتيب الـ z، وShapes[Shapes.Count - 1] تُعيد الشكل الأمامي في ترتيب الـ z. قراءة فقط Int32. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويعيّن خصائص العنصر النائب إلى العنصر المحدد. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | يعيد شكل عنصر نائب أساسي (شكل من تخطيط و/أو شريحة رئيسية يُورّث منه الشكل الحالي). يُعاد null إذا لم يكن الشكل الحالي مُورّثًا. |
| [GetImage](../../aspose.slides/shape/getimage)() | يعيد صورة مصغرة للشكل. يُستخدم النوع ShapeThumbnailBounds.Shape كحدود الصورة المصغرة افتراضيًا. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | يعيد صورة مصغرة للشكل. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | يحصل على حدود الشكل البصرية المحتسبة من محتواه المعروض. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | يُعرّف أن هذا الشكل ليس عنصرًا نائبًا. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | يحفظ محتوى الشكل كملف SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | يحفظ محتوى الشكل كملف SVG. |

### انظر أيضًا

* فئة [Shape](../shape)
* واجهة [IGroupShape](../igroupshape)
* مساحة اسم [Aspose.Slides](../../aspose.slides)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->