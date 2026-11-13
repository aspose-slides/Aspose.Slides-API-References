---
title: GeometryShape
second_title: مرجع واجهة برمجة التطبيقات Aspose.Sildes لـ .NET
description: يمثل الفئة الأب لجميع الأشكال الهندسية.
type: docs
weight: 4990
url: /ar/aspose.slides/geometryshape/
---
## فئة GeometryShape

يمثل الفئة الأب لجميع الأشكال الهندسية.

```csharp
public abstract class GeometryShape : Shape, IGeometryShape
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | يرجع مجموعة من قيم تعديل الشكل. للقراءة فقط [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | يرجع أو يعيّن النص البديل المرتبط بالشكل. قابل للقراءة والكتابة String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | يرجع أو يعيّن عنوان النص البديل المرتبط بالشكل. قابل للقراءة والكتابة String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | الخاصية تحدد كيف سيظهر الشكل في وضع العرض بالأبيض والأسود.. قابل للقراءة والكتابة [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | يرجع عدد نقاط الاتصال على الشكل. للقراءة فقط Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | يرجع البيانات المخصصة للشكل. للقراءة فقط [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | يرجع كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على الشكل. ملاحظة: يمكن أن يرجع null لأنواع معينة من الأشكال التي لا تملك خصائص تأثير. للقراءة فقط [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | يرجع كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة للشكل. ملاحظة: يمكن أن يرجع null لأنواع معينة من الأشكال التي لا تملك خصائص تعبئة. للقراءة فقط [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | يرجع أو يعيّن خصائص إطار الشكل. قابل للقراءة والكتابة [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | يرجع أو يعيّن ارتفاع الشكل، مقاساً بالنقاط. قابل للقراءة والكتابة Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | يحدد ما إذا كان الشكل مخفياً. قابل للقراءة والكتابة Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | يرجع أو يعيّن الارتباط التشعبي المحدد للنقر بالماوس. قابل للقراءة والكتابة [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | يرجع مدير الارتباط التشعبي. للقراءة فقط [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | يرجع أو يعيّن الارتباط التشعبي المحدد للتحويم بالماوس. قابل للقراءة والكتابة [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | يرجع أو يعيّن خيار 'وضع علامة كزخرفة'. قابل للقراءة والكتابة Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | يحدد ما إذا كان الشكل ضمن مجموعة. للقراءة فقط Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | يحدد ما إذا كان الشكل هو TextHolder_PPT. للقراءة فقط Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | يرجع كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل. ملاحظة: يمكن أن يرجع null لأنواع معينة من الأشكال التي لا تملك خصائص خط. للقراءة فقط [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | يرجع أو يعيّن اسم الشكل. يجب أن لا يكون فارغاً. استخدم سلسلة فارغة إذا لزم الأمر. قابل للقراءة والكتابة String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | يرجع معرفًا فريدًا نطاقه الشريحة يبقى ثابتًا طوال عمر الشكل ويسمح لـ PowerPoint أو كود التفاعل بالإشارة إلى الشكل بأمان من أي مكان في المستند. للقراءة فقط UInt32. انظر أيضاً [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | يرجع كائن GroupShape الأب إذا كان الشكل ضمن مجموعة. وإلا يرجع null. للقراءة فقط [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | يرجع العنصر النائب للشكل. يرجع null إذا لم يكن للشكل عنصر نائب. للقراءة فقط [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | يرجع العرض التقديمي الأب للشرحة. للقراءة فقط [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | يرجع أو يعيّن خصائص إطار الشكل الخام. قابل للقراءة والكتابة [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | يرجع أو يعيّن عدد درجات دوران الشكل المحدد حول المحور z. القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ القيمة السالبة تشير إلى دوران عكس اتجاه عقارب الساعة. قابل للقراءة والكتابة Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | يرجع أقفال الشكل. للقراءة فقط [`IBaseShapeLock`](../ibaseshapelock). |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | يرجع كائن نمط الشكل. للقراءة فقط [`IShapeStyle`](../ishapestyle). |
| virtual [ShapeType](../../aspose.slides/geometryshape/shapetype) { get; set; } | يرجع أو يعيّن نوع الإعداد المسبق للهندسة. ملاحظة: عند تغيير القيمة سيتم إعادة تعيين جميع قيم التعديل إلى قيمها الافتراضية. قابل للقراءة والكتابة [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | يرجع الشريحة الأب للشكل. للقراءة فقط [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | يرجع كائن ThreeDFormat الذي يحتوي على خصائص التأثير ثلاثي الأبعاد للشكل. ملاحظة: يمكن أن يرجع null لأنواع معينة من الأشكال التي لا تملك خصائص ثلاثية الأبعاد. للقراءة فقط [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | يرجع معرفًا داخليًا نطاقه العرض التقديمي مخصصًا للاستخدام من قبل الإضافات أو كود آخر. لأنه يمكن إعادة تعيين هذه القيمة من قبل المستخدم أو برمجياً، لا يجب اعتبارها مفتاحًا فريدًا دائمًا. للقراءة فقط UInt32. انظر أيضاً [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | يرجع أو يعيّن عرض الشكل، مقاساً بالنقاط. قابل للقراءة والكتابة Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | يرجع أو يعيّن إحداثي x لزاوية الشكل العليا اليسرى، مقاساً بالنقاط. قابل للقراءة والكتابة Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | يرجع أو يعيّن إحداثي y لزاوية الشكل العليا اليسرى، مقاساً بالنقاط. قابل للقراءة والكتابة Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | يرجع موضع الشكل في ترتيب z. Shapes[0] يرجع الشكل في خلفية ترتيب z، وShapes[Shapes.Count - 1] يرجع الشكل في مقدمة ترتيب z. للقراءة فقط Int32. |

## الأساليب

| الاسم | الوصف |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى عنصر محدد. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | ينشئ ويُرجِع مصفوفة من عناصر الشكل. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | يرجع شكل عنصر نائب أساسي (الشكل من التخطيط و/أو الشريحة الرئيسية التي يُستَدم منه الشكل الحالي). يُرجَع null إذا لم يكن الشكل الحالي مستدمًا. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | يرجع نسخة من مسار الشكل الهندسي. الإحداثيات نسبية إلى الزاوية اليسرى العليا للشكل. |
| [GetImage](../../aspose.slides/shape/getimage)() | يرجع صورة مصغرة للشكل. يُستخدم النوع ShapeThumbnailBounds.Shape كحدود الصورة المصغرة بشكل افتراضي. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | يرجع صورة مصغرة للشكل. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | يحصل على حدود الشكل البصرية المحسوبة من محتواه المُصوَّر. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | يقوم بتحديث هندسة الشكل من كائن [`IGeometryPath`](../igeometrypath). يجب أن تكون الإحداثيات نسبية إلى الزاوية اليسرى العليا للشكل. يغيّر نوع الشكل ([`ShapeType`](./shapetype)) إلى Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | يقوم بتحديث هندسة الشكل من مصفوفة [`IGeometryPath`](../igeometrypath). يجب أن تكون الإحداثيات نسبية إلى الزاوية اليسرى العليا للشكل. يغيّر نوع الشكل ([`ShapeType`](./shapetype)) إلى Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | يحفظ محتوى الشكل كملف SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | يحفظ محتوى الشكل كملف SVG. |

### انظر أيضًا

* الفئة [Shape](../shape)
* الواجهة [IGeometryShape](../igeometryshape)
* نطاق الاسم [Aspose.Slides](../../aspose.slides)
* التجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->