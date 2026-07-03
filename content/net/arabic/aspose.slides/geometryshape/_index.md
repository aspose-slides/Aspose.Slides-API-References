---
title: GeometryShape
second_title: مرجع API لـ Aspose.Sildes for .NET
description: يمثل الفئة الأساسية لجميع الأشكال الهندسية.
type: docs
weight: 4970
url: /ar/aspose.slides/geometryshape/
---
## فئة GeometryShape

يمثل الفئة الأساسية لجميع الأشكال الهندسية.

```csharp
public abstract class GeometryShape : Shape, IGeometryShape
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | يعيد مجموعة من قيم ضبط الشكل. قراءة فقط [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | يعيد أو يعيّن النص البديل المرتبط بالشكل. قراءة/كتابة String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | يعيد أو يعيّن عنوان النص البديل المرتبط بالشكل. قراءة/كتابة String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | تحدد الخاصية طريقة عرض الشكل في وضع الألوان الأسود والأبيض. قراءة/كتابة [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | يعيد عدد نقاط الاتصال على الشكل. قراءة فقط Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | يعيد البيانات المخصصة للشكل. قراءة فقط [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | يعيد كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على الشكل. ملاحظة: قد يُعيد null لبعض أنواع الأشكال التي لا تحتوي على خصائص تأثير. قراءة فقط [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | يعيد كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة للشكل. ملاحظة: قد يُعيد null لبعض أنواع الأشكال التي لا تحتوي على خصائص تعبئة. قراءة فقط [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | يعيد أو يعيّن خصائص إطار الشكل. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | يعيد أو يعيّن ارتفاع الشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | يحدد ما إذا كان الشكل مخفيًا. قراءة/كتابة Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | يعيد أو يعيّن الارتباط التشعبي المحدد للنقر بالفأرة. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | يعيد مدير الارتباط التشعبي. قراءة فقط [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | يعيد أو يعيّن الارتباط التشعبي المحدد للتمرير فوق الفأرة. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | يعيد أو يعيّن خيار "Mark as decorative". قراءة/كتابة Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | يحدد ما إذا كان الشكل مجمعًا. قراءة فقط Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | يحدد ما إذا كان الشكل TextHolder_PPT. قراءة فقط Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | يعيد كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل. ملاحظة: قد يُعيد null لبعض أنواع الأشكال التي لا تحتوي على خصائص خط. قراءة فقط [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | يعيد أو يعيّن اسم الشكل. يجب ألا يكون فارغًا. استخدم قيمة سلسلة فارغة إذا لزم الأمر. قراءة/كتابة String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | يعيد معرفًا فريدًا نطاق الشرائح يبقى ثابتًا طوال عمر الشكل ويسمح لبرنامج PowerPoint أو كود التفاعل بالإشارة إلى الشكل موثوقًا من أي مكان في المستند. قراءة فقط UInt32. راجع أيضًا [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | يعيد كائن GroupShape الأب إذا كان الشكل مُجَمَّعًا. وإلا يعيد null. قراءة فقط [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | يعيد العنصر النائب للشكل. يُعيد null إذا لم يكن لل形形 عنصر نائب. قراءة فقط [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | يعيد العرض التقديمي الأب للشرائح. قراءة فقط [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | يعيد أو يعيّن خصائص إطار الشكل الخام. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | يعيد أو يعيّن عدد الدرجات التي يدور بها الشكل المحدد حول المحور z. القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ القيمة السالبة تشير إلى دوران عكس اتجاه عقارب الساعة. قراءة/كتابة Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | يعيد أقفال الشكل. قراءة فقط [`IBaseShapeLock`](../ibaseshapelock). |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | يعيد كائن نمط الشكل. قراءة فقط [`IShapeStyle`](../ishapestyle). |
| virtual [ShapeType](../../aspose.slides/geometryshape/shapetype) { get; set; } | يعيد أو يعيّن نوع إعداد الهندسة المسبق. ملاحظة: عند تغيير القيمة سيتم إعادة تعيين جميع قيم الضبط إلى القيم الافتراضية. قراءة/كتابة [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | يعيد الشريحة الأب للشكل. قراءة فقط [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | يعيد كائن ThreeDFormat الذي يحتوي على خصائص التأثير ثلاثي الأبعاد للشكل. ملاحظة: قد يُعيد null لبعض أنواع الأشكال التي لا تمتلك خصائص ثلاثية الأبعاد. قراءة فقط [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | يعيد معرفًا داخليًا نطاق العرض مخصصًا للاستخدام من قبل الإضافات أو أكواد أخرى. ولأن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، لا ينبغي اعتبارها مفتاحًا فريدًا دائمًا. قراءة فقط UInt32. راجع أيضًا [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | يعيد أو يعيّن عرض الشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | يعيد أو يعيّن إحداثي x للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | يعيد أو يعيّن إحداثي y للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | يعيد موقع الشكل في ترتيب الـ z. Shapes[0] يعيد الشكل في خلفية ترتيب الـ z، و Shapes[Shapes.Count - 1] يعيد الشكل في مقدمة ترتيب الـ z. قراءة فقط Int32. |

## الأساليب

| الاسم | الوصف |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويعيّن خصائص العنصر النائب إلى عنصر محدد. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | ينشئ ويعيد مصفوفة من عناصر الشكل. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | يعيد شكلًا نائبًا أساسيًا (شكل من تخطيط و/أو شريحة رئيسية يتم وراثة الشكل الحالي منها). يتم إرجاع null إذا لم يكن الشكل الحالي مُورّثًا. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | يعيد نسخة من مسار الشكل الهندسي. الإحداثيات نسبية للزاوية اليسرى العليا للشكل. |
| [GetImage](../../aspose.slides/shape/getimage)() | يعيد صورة مصغرة للشكل. يُستخدم النوع ShapeThumbnailBounds.Shape كحدود الصورة المصغرة بشكل افتراضي. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | يعيد صورة مصغرة للشكل. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | يعيد حدود الشكل البصرية المحسوبة من محتواه المُرَسَم. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | يُحدّث هندسة الشكل من كائن [`IGeometryPath`](../igeometrypath). يجب أن تكون الإحداثيات نسبية للزاوية اليسرى العليا للشكل. يغيّر نوع الشكل ([`ShapeType`](./shapetype)) إلى مخصص. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | يُحدّث هندسة الشكل من مصفوفة من [`IGeometryPath`](../igeometrypath). يجب أن تكون الإحداثيات نسبية للزاوية اليسرى العليا للشكل. يغيّر نوع الشكل ([`ShapeType`](./shapetype)) إلى مخصص. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | يحفظ محتوى الشكل كملف SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | يحفظ محتوى الشكل كملف SVG. |

### انظر أيضًا

* فئة [Shape](../shape)
* واجهة [IGeometryShape](../igeometryshape)
* نطاق الاسم [Aspose.Slides](../../aspose.slides)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->