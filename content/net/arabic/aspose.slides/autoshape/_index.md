---
title: AutoShape
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: يمثّل AutoShape.
type: docs
weight: 900
url: /ar/aspose.slides/autoshape/
---
## فئة AutoShape

يمثّل AutoShape.

```csharp
public sealed class AutoShape : GeometryShape, IAutoShape
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | تُرجِع مجموعة من قيم تعديل الشكل. قراءة فقط [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | تُرجِع أو تُعيّن النص البديل المرتبط بالشكل. قراءة/كتابة String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | تُرجِع أو تُعيّن عنوان النص البديل المرتبط بالشكل. قراءة/كتابة String. |
| [AutoShapeLock](../../aspose.slides/autoshape/autoshapelock) { get; } | تُرجِع أقفال الشكل التلقائي. قراءة فقط [`IAutoShapeLock`](../iautoshapelock). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | الخاصية تحدد كيفية عرض الشكل في وضع العرض بالأبيض والأسود. قراءة/كتابة [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تُرجِع عدد نقاط الاتصال على الشكل. قراءة فقط Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | تُرجِع البيانات المخصصة للشكل. قراءة فقط [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | تُرجِع كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على الشكل. ملاحظة: قد يُعيد null لبعض أنواع الأشكال التي لا تملك خصائص تأثير. قراءة فقط [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | تُرجِع كائن FillFormat الذي يحتوي على خصائص تنسيق الملء للشكل. ملاحظة: قد يُعيد null لبعض أنواع الأشكال التي لا تملك خصائص ملء. قراءة فقط [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | تُرجِع أو تُعيّن خصائص إطار الشكل. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | تُعيد أو تُعيّن ارتفاع الشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | يحدّد ما إذا كان الشكل مخفيًا. قراءة/كتابة Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | تُرجِع أو تُعيّن الارتباط التشعبي المحدد للنقر بالفأرة. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | تُرجِع مدير الارتباط التشعبي. قراءة فقط [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | تُرجِع أو تُعيّن الارتباط التشعبي المحدد للتمرير فوق الفأرة. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | تُعيد أو تُعيّن خيار 'وضع علامة كديكور' قراءة/كتابة Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | يحدّد ما إذا كان الشكل مجموعة. قراءة فقط Boolean. |
| [IsTextBox](../../aspose.slides/autoshape/istextbox) { get; } | يحدّد ما إذا كان الشكل صندوق نص. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | يحدّد ما إذا كان الشكل TextHolder_PPT. قراءة فقط Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | تُرجِع كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل. ملاحظة: قد يُعيد null لبعض أنواع الأشكال التي لا تملك خصائص خط. قراءة فقط [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | تُرجِع أو تُعيّن اسم الشكل. يجب أن لا يكون Null. استخدم قيمة سلسلة فارغة إذا لزم الأمر. قراءة/كتابة String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | تُرجِع معرفًا فريدًا محصورًا في الشريحة يظل ثابتًا طوال حياة الشكل ويسمح لبرنامج PowerPoint أو رمز التفاعل بالإشارة إلى الشكل من أي مكان في المستند بثقة. قراءة فقط UInt32. أنظر أيضًا [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | تُرجِع كائن GroupShape الأب إذا كان الشكل مجموعة. وإلا تُرجِع null. قراءة فقط [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | تُرجِع العنصر النائب للشكل. تُرجِع null إذا لم يكن للshape عنصر نائب. قراءة فقط [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | تُرجِع العرض التقديمي الأب للشريحة. قراءة فقط [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | تُرجِع أو تُعيّن خصائص إطار الشكل الخام. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تُرجِع أو تُعيّن عدد الدرجات التي يدورها الشكل المحدد حول محور z. القيمة الموجبة تدل على دوران باتجاه عقارب الساعة؛ القيمة السالبة تدل على دوران عكس عقارب الساعة. قراءة/كتابة Single. |
| [ShapeLock](../../aspose.slides/autoshape/shapelock) { get; } | تُرجِع أقفال الشكل. قراءة فقط [`IAutoShapeLock`](../iautoshapelock). (خاصيتان) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | تُرجِع كائن نمط الشكل. قراءة فقط [`IShapeStyle`](../ishapestyle). |
| virtual [ShapeType](../../aspose.slides/geometryshape/shapetype) { get; set; } | تُرجِع أو تُعيّن نوع التpreset الهندسي. ملاحظة: عند تغيير القيمة ستُعاد جميع قيم التعديل إلى القيم الافتراضية. قراءة/كتابة [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | تُرجِع الشريحة الأم للشكل. قراءة فقط [`IBaseSlide`](../ibaseslide). |
| [TextFrame](../../aspose.slides/autoshape/textframe) { get; } | تُرجِع كائن TextFrame للـ AutoShape. قراءة فقط [`ITextFrame`](../itextframe). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | تُرجِع كائن ThreeDFormat الذي يحتوي على خصائص التأثير ثلاثي الأبعاد للشكل. ملاحظة: قد يُعيد null لبعض أنواع الأشكال التي لا تملك خصائص ثلاثية الأبعاد. قراءة فقط [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | تُرجِع معرفًا داخليًا محصورًا في العرض التقديمي مخصصًا للاستخدام من قبل الإضافات أو الكود الآخر. نظرًا لأن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، لا يجب معاملتها كمفتاح فريد دائم. قراءة فقط UInt32. أنظر أيضًا [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [UseBackgroundFill](../../aspose.slides/autoshape/usebackgroundfill) { get; set; } | يحدّد ما إذا كان يجب ملء هذا الشكل التلقائي بملء خلفية الشريحة بدلاً من ما يحدده النمط أو تنسيق الملء. قراءة/كتابة Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | تُعيد أو تُعيّن عرض الشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | تُعيد أو تُعيّن إحداثي x للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | تُعيد أو تُعيّن إحداثي y للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | تُرجِع موقع الشكل في ترتيب z. Shapes[0] تُرجِع الشكل في الخلفية، و Shapes[Shapes.Count - 1] تُرجِع الشكل في المقدمة. قراءة فقط Int32. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى المحدد. |
| [AddTextFrame](../../aspose.slides/autoshape/addtextframe)(string) | يضيف TextFrame جديدًا إلى الشكل. إذا كان الشكل يحتوي بالفعل على TextFrame فسيغيّر نصه فقط. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | ينشئ ويُرجِع مصفوفة من عناصر الشكل. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | تُرجِع شكل عنصر نائب أساسي (شكل من التخطيط و/أو الشريحة الرئيسة التي يرث منها الشكل الحالي). تُرجِع null إذا لم يكن الشكل الحالي موروثًا. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | تُرجِع نسخة من مسار الشكل الهندسي. الإحداثيات نسبية للزاوية اليسرى العليا للشكل. |
| [GetImage](../../aspose.slides/shape/getimage)() | تُرجِع صورة مصغرة للشكل. يُستخدم النوع ShapeThumbnailBounds.Shape كحدود الصورة المصغرة بشكل افتراضي. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تُرجِع صورة مصغرة للشكل. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | تُعيد حدود الشكل البصرية محسوبة من المحتوى المُعرض. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | يُحدّث هندسة الشكل من كائن [`IGeometryPath`](../igeometrypath). يجب أن تكون الإحداثيات نسبية للزاوية اليسرى العليا للشكل. يغيّر نوع الشكل ([`ShapeType`](../geometryshape/shapetype)) إلى Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | يُحدّث هندسة الشكل من مصفوفة [`IGeometryPath`](../igeometrypath). يجب أن تكون الإحداثيات نسبية للزاوية اليسرى العليا للشكل. يغيّر نوع الشكل ([`ShapeType`](../geometryshape/shapetype)) إلى Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | يحفظ محتوى الشكل كملف SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | يحفظ محتوى الشكل كملف SVG. |

### انظر أيضًا

* فئة [GeometryShape](../geometryshape)
* واجهة [IAutoShape](../iautoshape)
* فضاء الاسم [Aspose.Slides](../../aspose.slides)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->