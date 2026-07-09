---
title: GraphicalObject
second_title: Aspose.Sildes لـ .NET مرجع API
description: يمثل كائنًا رسوميًا مجردًا.
type: docs
weight: 5070
url: /ar/aspose.slides/graphicalobject/
---
## GraphicalObject فئة

يمثل كائنًا رسوميًا مجردًا.

```csharp
public class GraphicalObject : Shape, IGraphicalObject
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | يرجع أو يضبط النص البديل المرتبط بشكَل. قراءة/كتابة String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | يرجع أو يضبط عنوان النص البديل المرتبط بشكَل. قراءة/كتابة String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | المِلكية تُحدّد كيفية عرض الشكل في وضع العرض بالأبيض والأسود. قراءة/كتابة [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | يرجع عدد مواقع الاتصال على الشكل. قراءة فقط Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | يرجع بيانات الشكل المخصصة. قراءة فقط [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | يرجع كائن EffectFormat الذي يحتوي على تأثيرات البكسل المُطبقة على الشكل. ملاحظة: يمكن أن يُعيد null لأنواع معينة من الأشكال التي لا تحتوي على خصائص تأثير. قراءة فقط [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | يرجع كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة للشكل. ملاحظة: يمكن أن يُعيد null لأنواع معينة من الأشكال التي لا تحتوي على خصائص تعبئة. قراءة فقط [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | يرجع أو يضبط خصائص إطار الشكل. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | يرجع أقفال الشكل. قراءة فقط [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | يحصل أو يضبط ارتفاع الشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | يحدد ما إذا كان الشكل مخفيًا. قراءة/كتابة Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | يرجع أو يضبط الارتباط التشعبي المحدد للنقر بالماوس. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | يرجع مدير الارتباط التشعبي. قراءة فقط [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | يرجع أو يضبط الارتباط التشعبي المحدد للماوس فوق. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | يحصل أو يضبط خيار 'وضع علامة كزخرفة'. قراءة/كتابة Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | يحدد ما إذا كان الشكل مجموعة. قراءة فقط Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | يحدد ما إذا كان الشكل TextHolder_PPT. قراءة فقط Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | يرجع كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل. ملاحظة: يمكن أن يُعيد null لأنواع معينة من الأشكال التي لا تحتوي على خصائص خط. قراءة فقط [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | يرجع أو يضبط اسم الشكل. يجب ألا يكون فارغًا. استخدم قيمة سلسلة فارغة إذا لزم الأمر. قراءة/كتابة String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | يرجع معرفًا فريدًا ضمن نطاق الشريحة يبقى ثابتًا طوال عمر الشكل ويسمح لبرنامج PowerPoint أو كود التفاعل بالإشارة إلى الشكل بثقة من أي مكان في المستند. قراءة فقط UInt32. انظر أيضًا [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | يرجع كائن GroupShape الأب إذا كان الشكل مجموعة. وإلا يرجع null. قراءة فقط [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | يرجع العنصر النائب لل shape. يرجع null إذا لم يكن لل shape أي عنصر نائب. قراءة فقط [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | يرجع العرض التقديمي الأب للشريحة. قراءة فقط [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | يرجع أو يضبط خصائص إطار الشكل الخام. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | يرجع أو يضبط عدد الدرجات التي يدور بها الشكل المحدد حول محور z. القيمة الإيجابية تشير إلى دوران باتجاه عقارب الساعة؛ القيمة السلبية تشير إلى دوران عكس اتجاه العقارب. قراءة/كتابة Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | يرجع أقفال الشكل. قراءة فقط [`IGraphicalObjectLock`](../igraphicalobjectlock). (خاصيتان) |
| [Slide](../../aspose.slides/shape/slide) { get; } | يرجع الشريحة الأم لل shape. قراءة فقط [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | يرجع كائن ThreeDFormat الذي يحتوي على خصائص تأثير ثلاثي الأبعاد للشكل. ملاحظة: يمكن أن يُعيد null لأنواع معينة من الأشكال التي لا تمتلك خصائص ثلاثية الأبعاد. قراءة فقط [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | يرجع معرفًا داخليًا ضمن نطاق العرض التقديمي مخصصًا للاستخدام بواسطة الإضافات أو كود آخر. لأن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، لا ينبغي اعتبارها مفتاحًا فريدًا ثابتًا. قراءة فقط UInt32. انظر أيضًا [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | يحصل أو يضبط عرض الشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | يحصل أو يضبط إحداثي x للزاوية العليا اليسرى لل shape، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | يحصل أو يضبط إحداثي y للزاوية العليا اليسرى لل shape، مقاسًا بالنقاط. قراءة/كتابة Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | يرجع موضع الشكل في ترتيب z. Shapes[0] يرجع الشكل الموجود في خلفية ترتيب z، و Shapes[Shapes.Count - 1] يرجع الشكل في مقدمة ترتيب z. قراءة فقط Int32. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى العنصر المحدد. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | يرجع شكل عنصر نائب أساسي (شكل من التخطيط و/أو الشريحة الرئيسية التي يرث منها الشكل الحالي). يتم إرجاع null إذا لم يكن الشكل الحالي موروثًا. |
| [GetImage](../../aspose.slides/shape/getimage)() | يرجع صورة مصغرة للشكل. يتم استخدام النوع ShapeThumbnailBounds.Shape كحدود الصورة المصغرة للshape بشكل افتراضي. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | يرجع صورة مصغرة للشكل. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | يحصل على الحدود البصرية للشكل المحسوبة من محتواه المروض. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | يحفظ محتوى الشكل كملف SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISSVGOptions) | يحفظ محتوى الشكل كملف SVG. |

### انظر أيضًا

* فئة [Shape](../shape)
* واجهة [IGraphicalObject](../igraphicalobject)
* نطاق [Aspose.Slides](../../aspose.slides)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->