---
title: SmartArtShape
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: يمثل شكل SmartArt
type: docs
weight: 10660
url: /ar/aspose.slides.smartart/smartartshape/
---
## فئة SmartArtShape

يمثل شكل SmartArt

```csharp
public class SmartArtShape : GeometryShape, ISmartArtShape
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | يعيد مجموعة من قيم تعديل الشكل. للقراءة فقط [`IAdjustValueCollection`](../../aspose.slides/iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | يعيد أو يضع النص البديل المرتبط بالشكل. قابل للقراءة والكتابة String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | يعيد أو يضع عنوان النص البديل المرتبط بالشكل. قابل للقراءة والكتابة String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | تحدد الخاصية كيفية عرض الشكل في وضع العرض بالأبيض والأسود. قابل للقراءة والكتابة [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | يعيد عدد مواقع الاتصال على الشكل. للقراءة فقط Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | يعيد البيانات المخصصة للشكل. للقراءة فقط [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | يعيد كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على الشكل. ملاحظة: قد يرجع قيمة خالية لأشكال معينة لا تمتلك خصائص تأثير. للقراءة فقط [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | يعيد كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة للشكل. ملاحظة: قد يرجع قيمة خالية لأشكال معينة لا تمتلك خصائص تعبئة. للقراءة فقط [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | يعيد خصائص إطار الشكل. قابل للقراءة والكتابة [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | يعيد أو يضع ارتفاع الشكل، مقاسًا بالنقاط. قابل للقراءة والكتابة Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | يحدد ما إذا كان الشكل مخفيًا. قابل للقراءة والكتابة Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | يعيد أو يضع الارتباط التشعبي المحدد للنقر بالماوس. قابل للقراءة والكتابة [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | يعيد مدير الارتباط التشعبي. للقراءة فقط [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | يعيد أو يضع الارتباط التشعبي المحدد للماوس فوق. قابل للقراءة والكتابة [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | يعيد أو يضع خيار 'علامة كديكور'. قابل للقراءة والكتابة Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | يحدد ما إذا كان الشكل مجموعًا. للقراءة فقط Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | يحدد ما إذا كان الشكل TextHolder_PPT. للقراءة فقط Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | يعيد كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل. ملاحظة: قد يرجع قيمة خالية لأشكال معينة لا تمتلك خصائص خط. للقراءة فقط [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | يعيد أو يضع اسم الشكل. يجب ألا يكون فارغًا. استخدم قيمة سلسلة فارغة إذا لزم الأمر. قابل للقراءة والكتابة String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | يعيد معرفًا فريدًا ضمن نطاق الشريحة يبقى ثابتًا طوال عمر الشكل ويسمح لبرنامج PowerPoint أو شفرة التفاعل بالإشارة إلى الشكل من أي مكان في المستند. للقراءة فقط UInt32. انظر أيضًا [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | يعيد كائن GroupShape الأصل إذا كان الشكل مجموعة. وإلا يرجع قيمة خالية. للقراءة فقط [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | يعيد العنصر النائب للشكل. يرجع قيمة خالية إذا لم يحتوي الشكل على عنصر نائب. للقراءة فقط [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | يعيد العرض التقديمي الأصل لل شريحة. للقراءة فقط [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | يعيد أو يضع الخصائص الأولية لإطار الشكل. قابل للقراءة والكتابة [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | يعيد أو يضع عدد الدرجات التي يتم فيها تدوير الشكل المحدد حول محور z. القيمة الموجبة تشير إلى التدوير مع عقارب الساعة؛ القيمة السالبة تشير إلى التدوير عكس اتجاه العقارب. قابل للقراءة والكتابة Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | يعيد أقفال الشكل. للقراءة فقط [`IBaseShapeLock`](../../aspose.slides/ibaseshapelock). |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | يعيد كائن نمط الشكل. للقراءة فقط [`IShapeStyle`](../../aspose.slides/ishapestyle). |
| override [ShapeType](../../aspose.slides.smartart/smartartshape/shapetype) { get; set; } | يعيد أو يضع نوع التكوين الهندسي المسبق. ملاحظة: عند تغيير القيمة سيتم إعادة تعيين جميع قيم التعديل إلى القيم الافتراضية. قابل للقراءة والكتابة [`ShapeType`](../../aspose.slides/shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | يعيد الشريحة الأصلية للشكل. للقراءة فقط [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [TextFrame](../../aspose.slides.smartart/smartartshape/textframe) { get; } | يعيد نص شكل SmartArt. للقراءة فقط [`ITextFrame`](../../aspose.slides/itextframe). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | يعيد كائن ThreeDFormat الذي يحتوي على خصائص التأثير ثلاثي الأبعاد للشكل. ملاحظة: قد يرجع قيمة خالية لأشكال معينة لا تمتلك خصائص ثلاثية الأبعاد. للقراءة فقط [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | يعيد معرفًا داخليًا ضمن نطاق العرض التقديمي مخصصًا للاستخدام من قبل الإضافات أو الشفرة الأخرى. نظرًا لأن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، يجب عدم اعتبارها مفتاحًا فريدًا دائمًا. للقراءة فقط UInt32. انظر أيضًا [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | يعيد أو يضع عرض الشكل، مقاسًا بالنقاط. قابل للقراءة والكتابة Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | يعيد أو يضع الإحداثي س للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط. قابل للقراءة والكتابة Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | يعيد أو يضع الإحداثي ص للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط. قابل للقراءة والكتابة Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | يعيد موضع الشكل في ترتيب z. Shapes[0] يعيد الشكل في خلفية ترتيب z، و Shapes[Shapes.Count - 1] يعيد الشكل في مقدمة ترتيب z. للقراءة فقط Int32. |

## الأساليب

| الاسم | الوصف |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يوجد ويضبط خصائص العنصر النائب إلى عنصر محدد. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | ينشئ ويرجع مصفوفة من عناصر الشكل. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | يعيد شكل عنصر نائب أساسي (شكل من التخطيط و/أو شريحة القالب التي يُورث منها الشكل الحالي). تُرجع قيمة خالية إذا لم يكن الشكل الحالي مُورثًا. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | يعيد نسخة من مسار الشكل الهندسي. الإحداثيات نسبية إلى الزاوية اليسرى العلوية للشكل. |
| [GetImage](../../aspose.slides/shape/getimage)() | يعيد صورة مصغرة للشكل. يُستخدم النوع ShapeThumbnailBounds.Shape كحدود الصورة المصغرة للشكل بشكل افتراضي. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | يعيد صورة مصغرة للشكل. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | يحصل على حدود الشكل البصرية المحسوبة من المحتوى المعروض. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | يُحدّث هندسة الشكل من كائن [`IGeometryPath`](../../aspose.slides/igeometrypath). يجب أن تكون الإحداثيات نسبية إلى الزاوية اليسرى العلوية للشكل. يغيّر نوع الشكل ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) إلى مخصص. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | يُحدّث هندسة الشكل من مصفوفة من [`IGeometryPath`](../../aspose.slides/igeometrypath). يجب أن تكون الإحداثيات نسبية إلى الزاوية اليسرى العلوية للشكل. يغيّر نوع الشكل ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) إلى مخصص. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | يحفظ محتوى الشكل كملف SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | يحفظ محتوى الشكل كملف SVG. |

### انظر أيضًا

* فئة [GeometryShape](../../aspose.slides/geometryshape)
* واجهة [ISmartArtShape](../ismartartshape)
* مساحة اسم [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->