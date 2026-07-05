---
title: Connector
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: يمثل موصلًا.
type: docs
weight: 2670
url: /ar/aspose.slides/connector/
---
## فئة Connector

يمثل موصلًا.

```csharp
public class Connector : GeometryShape, IConnector
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | يرجع مجموعة من قيم تعديل الشكل. قراءة فقط [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | يرجع أو يضبط النص البديل المرتبط بالشكل. قراءة/كتابة String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | يرجع أو يضبط عنوان النص البديل المرتبط بالشكل. قراءة/كتابة String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | تحدد الخاصية كيف سيتم عرض الشكل في وضع اللونين الأبيض والأسود. قراءة/كتابة [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | يرجع عدد مواقع الاتصال على الشكل. قراءة فقط Int32. |
| [ConnectorLock](../../aspose.slides/connector/connectorlock) { get; } | يرجع أقفال الموصل. قراءة فقط [`IConnectorLock`](../iconnectorlock). |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | يرجع البيانات المخصصة للشكل. قراءة فقط [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | يرجع كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على الشكل. ملاحظة: يمكن أن يرجع null لأنواع معينة من الأشكال التي لا تمتلك خصائص تأثير. قراءة فقط [`IEffectFormat`](../ieffectformat). |
| [EndShapeConnectedTo](../../aspose.slides/connector/endshapeconnectedto) { get; set; } | يرجع أو يضبط الشكل الذي يُرفق به طرف الموصل. قراءة/كتابة [`IShape`](../ishape). |
| [EndShapeConnectionSiteIndex](../../aspose.slides/connector/endshapeconnectionsiteindex) { get; set; } | يرجع أو يضبط فهرس موقع الاتصال للشكل النهائي. قراءة/كتابة UInt32. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | يرجع كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة للشكل. ملاحظة: يمكن أن يرجع null لأنواع معينة من الأشكال التي لا تمتلك خصائص تعبئة. قراءة فقط [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | يرجع أو يضبط خصائص إطار الشكل. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | يرجع أو يضبط ارتفاع الشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | يحدد ما إذا كان الشكل مخفيًا. قراءة/كتابة Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | يرجع أو يضبط الارتباط التشعبي المعرف للنقر بالفأرة. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | يرجع مدير الارتباط التشعبي. قراءة فقط [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | يرجع أو يضبط الارتباط التشعبي المعرف عند مرور الفأرة. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | يرجع أو يضبط خيار 'وضع علامة كزخرفة'. قراءة/كتابة Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | يحدد ما إذا كان الشكل مجموعة. قراءة فقط Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | يحدد ما إذا كان الشكل TextHolder_PPT. قراءة فقط Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | يرجع كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل. ملاحظة: يمكن أن يرجع null لأنواع معينة من الأشكال التي لا تمتلك خصائص خط. قراءة فقط [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | يرجع أو يضبط اسم الشكل. يجب ألا يكون فارغًا. استخدم قيمة سلسلة فارغة إذا لزم الأمر. قراءة/كتابة String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | يرجع معرفًا فريدًا يخص الشريحة يبقى ثابتًا طوال عمر الشكل ويسمح لـ PowerPoint أو كود التفاعل بالإشارة إلى الشكل من أي مكان في المستند. قراءة فقط UInt32. راجع أيضًا [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | يرجع كائن GroupShape الأب إذا كان الشكل مجموعة. وإلا يرجع null. قراءة فقط [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | يرجع العنصر النائب للشكل. يرجع null إذا لم يكن لدى الشكل عنصر نائب. قراءة فقط [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | يرجع العرض الأم للشرحة. قراءة فقط [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | يرجع أو يضبط خصائص إطار الشكل الخام. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | يرجع أو يضبط عدد الدرجات التي يدور فيها الشكل المحدد حول محور z. قيمة موجبة تشير إلى دوران باتجاه عقارب الساعة؛ قيمة سالبة تشير إلى دوران عكس اتجاه عقارب الساعة. قراءة/كتابة Single. |
| [ShapeLock](../../aspose.slides/connector/shapelock) { get; } | يرجع أقفال الشكل. قراءة فقط [`IConnectorLock`](../iconnectorlock). (2 خصائص) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | يرجع كائن نمط الشكل. قراءة فقط [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/connector/shapetype) { get; set; } | يرجع أو يضبط نوع AutoShape. قراءة/كتابة [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | يرجع الشريحة الأم للشكل. قراءة فقط [`IBaseSlide`](../ibaseslide). |
| [StartShapeConnectedTo](../../aspose.slides/connector/startshapeconnectedto) { get; set; } | يرجع أو يضبط الشكل الذي يُرفق به بداية الموصل. قراءة/كتابة [`IShape`](../ishape). |
| [StartShapeConnectionSiteIndex](../../aspose.slides/connector/startshapeconnectionsiteindex) { get; set; } | يرجع أو يضبط فهرس موقع الاتصال للشكل الابتدائي. قراءة/كتابة UInt32. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | يرجع كائن ThreeDFormat الذي يحتوي على خصائص التأثير ثلاثي الأبعاد للشكل. ملاحظة: يمكن أن يرجع null لأنواع معينة من الأشكال التي لا تمتلك خصائص ثلاثية الأبعاد. قراءة فقط [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | يرجع معرفًا داخليًا يخص العرض مخصصًا للاستخدام من قبل الإضافات أو كود آخر. نظرًا لأن هذا القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، يجب عدم اعتبارها مفتاحًا فريدًا دائمًا. قراءة فقط UInt32. راجع أيضًا [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | يرجع أو يضبط عرض الشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | يرجع أو يضبط إحداثي x للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | يرجع أو يضبط إحداثي y للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | يرجع موضع الشكل في ترتيب z. Shapes[0] يرجع الشكل في خلفية ترتيب z، و Shapes[Shapes.Count - 1] يرجع الشكل في مقدمة ترتيب z. قراءة فقط Int32. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى العنصر المحدد. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | ينشئ ويُرجع مصفوفة من عناصر الشكل. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | يرجع شكلًا عنصرًا نائبًا أساسيًا (شكل من التخطيط و/أو شريحة الماستر الذي يرث منه الشكل الحالي). يُرجع null إذا لم يكن الشكل الحالي موروثًا. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | يرجع نسخة من مسار الشكل الهندسي. الإحداثيات نسبية للزاوية العلوية اليسرى للشكل. |
| [GetImage](../../aspose.slides/shape/getimage)() | يرجع صورة مصغرة للشكل. يُستخدم النوع ShapeThumbnailBounds.Shape كحدود الصورة المصغرة افتراضيًا. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | يرجع صورة مصغرة للشكل. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | يرجع حدود الشكل البصرية المحسوبة من محتواه المرسوم. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [Reroute](../../aspose.slides/connector/reroute)() | يعيد توجيه الموصل بحيث يأخذ أقصر مسار ممكن بين الأشكال التي يربطها. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | يحدث هندسة الشكل من كائن [`IGeometryPath`](../igeometrypath). يجب أن تكون الإحداثيات نسبية للزاوية العلوية اليسرى للشكل. يغير نوع الشكل ([`ShapeType`](../geometryshape/shapetype)) إلى Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | يحدث هندسة الشكل من مصفوفة [`IGeometryPath`](../igeometrypath). يجب أن تكون الإحداثيات نسبية للزاوية العلوية اليسرى للشكل. يغير نوع الشكل ([`ShapeType`](../geometryshape/shapetype)) إلى Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | يحفظ محتوى الشكل كملف SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | يحفظ محتوى الشكل كملف SVG. |

### انظر أيضًا

* فئة [GeometryShape](../geometryshape)
* واجهة [IConnector](../iconnector)
* نطاق [Aspose.Slides](../../aspose.slides)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->