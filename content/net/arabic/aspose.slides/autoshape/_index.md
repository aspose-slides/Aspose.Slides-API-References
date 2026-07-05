---
title: AutoShape
second_title: Aspose.Sildes لـ .NET مرجع واجهة برمجة التطبيقات
description: يمثل AutoShape.
type: docs
weight: 900
url: /ar/aspose.slides/autoshape/
---
## AutoShape فئة

تمثل AutoShape.

```csharp
public sealed class AutoShape : GeometryShape, IAutoShape
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | يرجع مجموعة من قيم تعديل الشكل. للقراءة فقط [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | يرجع أو يضبط النص البديل المرتبط بالشكل. قراءة/كتابة String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | يرجع أو يضبط عنوان النص البديل المرتبط بالشكل. قراءة/كتابة String. |
| [AutoShapeLock](../../aspose.slides/autoshape/autoshapelock) { get; } | يرجع أقفال الـ AutoShape. للقراءة فقط [`IAutoShapeLock`](../iautoshapelock). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | تحدد الخاصية كيفية عرض الشكل في وضعية أبيض-أسود. قراءة/كتابة [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | يرجع عدد نقاط الاتصال على الشكل. للقراءة فقط Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | يرجع البيانات المخصصة للشكل. للقراءة فقط [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | يرجع كائن EffectFormat الذي يحتوي على تأثيرات بكسل مطبقة على الشكل. ملاحظة: يمكن أن يرجع null لبعض أنواع الأشكال التي لا تملك خصائص تأثير. للقراءة فقط [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | يرجع كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة للشكل. ملاحظة: يمكن أن يرجع null لبعض أنواع الأشكال التي لا تملك خصائص تعبئة. للقراءة فقط [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | يرجع أو يضبط خصائص إطار الشكل. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | يرجع أو يضبط ارتفاع الشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | يحدد ما إذا كان الشكل مخفيًا. قراءة/كتابة Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | يررج أو يضبط الارتباط التشعبي المحدد لنقر الفأرة. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | يررج مدير الارتباط التشعبي. للقراءة فقط [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | يررج أو يضبط الارتباط التشعبي المحدد لتمرير الفأرة. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | يررج أو يضبط خيار 'تحديد كديكوري'. قراءة/كتابة Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | يحدد ما إذا كان الشكل مجموعة. للقراءة فقط Boolean. |
| [IsTextBox](../../aspose.slides/autoshape/istextbox) { get; } | يحدد ما إذا كان الشكل مربع نص. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | يحدد ما إذا كان الشكل TextHolder_PPT. للقراءة فقط Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | يررج كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل. ملاحظة: يمكن أن يرجع null لبعض أنواع الأشكال التي لا تملك خصائص خط. للقراءة فقط [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | يررج أو يضبط اسم الشكل. يجب ألا يكون فارغًا. استخدم قيمة سلسلة فارغة إذا لزم الأمر. قراءة/كتابة String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | يررج معرفًا فريدًا نطاقه على الشريحة يبقى ثابتًا طوال عمر الشكل ويسمح لPowerPoint أو كود التفاعل بالإشارة إلى الشكل من أي مكان في المستند. للقراءة فقط UInt32. انظر أيضًا [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | يررج كائن GroupShape الأب إذا كان الشكل مجموعة. وإلا يرجع null. للقراءة فقط [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | يررج العنصر النائب للشكل. يرجع null إذا لم يكن لل形形 عنصر نائب. للقراءة فقط [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | يررج العرض التقديمي الأب للشريحة. للقراءة فقط [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | يررج أو يضبط خصائص إطار الشكل الخام. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | يررج أو يضبط عدد الدرجات التي يدور فيها الشكل حول محور z. القيمة الموجبة تدل على دوران باتجاه عقربة الساعة؛ القيمة السالبة تدل على دوران عكس عقربة الساعة. قراءة/كتابة Single. |
| [ShapeLock](../../aspose.slides/autoshape/shapelock) { get; } | يررج أقفال الشكل. للقراءة فقط [`IAutoShapeLock`](../iautoshapelock). (2 خصائص) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | يررج كائن نمط الشكل. للقراءة فقط [`IShapeStyle`](../ishapestyle). |
| virtual [ShapeType](../../aspose.slides/geometryshape/shapetype) { get; set; } | يررج أو يضبط نوع الشكل المسبق التحديد للجغرافيا. ملاحظة: عند تغيير القيمة سيتم إعادة تعيين جميع قيم التعديل إلى القيم الافتراضية. قراءة/كتابة [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | يررج الشريحة الأب للشكل. للقراءة فقط [`IBaseSlide`](../ibaseslide). |
| [TextFrame](../../aspose.slides/autoshape/textframe) { get; } | يررج كائن TextFrame لـ AutoShape. للقراءة فقط [`ITextFrame`](../itextframe). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | يررج كائن ThreeDFormat الذي يحتوي على خصائص تأثير ثلاثي الأبعاد للشكل. ملاحظة: يمكن أن يرجع null لبعض أنواع الأشكال التي لا تملك خصائص ثلاثية الأبعاد. للقراءة فقط [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | يررج معرفًا داخليًا نطاقه على العرض التقديمي مخصص لاستخدام الإضافات أو كود آخر. لأن هذا القيم يمكن إعادة تعيينه من قبل المستخدم أو برمجيًا، لا يجب اعتباره مفتاحًا فريدًا دائمًا. للقراءة فقط UInt32. انظر أيضًا [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [UseBackgroundFill](../../aspose.slides/autoshape/usebackgroundfill) { get; set; } | يحدد ما إذا كان يجب ملء هذا الـ AutoShape بخلفية الشريحة بدلًا من ما يحدده النمط أو تنسيق الملء. قراءة/كتابة Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | يررج أو يضبط عرض الشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | يررج أو يضبط إحداثي x للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | يررج أو يضبط إحداثي y للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | يررج موضع الشكل في ترتيب z. Shapes[0] يرجع الشكل في خلفية ترتيب z، و Shapes[Shapes.Count - 1] يرجع الشكل في مقدمة ترتيب z. للقراءة فقط Int32. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى العنصر المحدد. |
| [AddTextFrame](../../aspose.slides/autoshape/addtextframe)(string) | يضيف TextFrame جديد إلى الشكل. إذا كان الشكل يمتلك TextFrame بالفعل فسيغير نصه فقط. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | ينشئ ويرجع مصفوفة من عناصر الشكل. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | يررج شكل عنصر نائب أساسي (شكل من تخطيط أو شريحة رئيسية يتم وراثة الشكل الحالي منها). يرجع null إذا لم يكن الشكل الحالي موروثًا. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | يررج نسخة من مسار الشكل الهندسي. الإحداثيات نسبية إلى الزاوية اليسرى العلوية للشكل. |
| [GetImage](../../aspose.slides/shape/getimage)() | يررج صورة مصغرة للشكل. نوع حدود صورة مصغرة ShapeThumbnailBounds.Shape يُستخدم افتراضيًا. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | يررج صورة مصغرة للشكل. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | يررج الحدود البصرية للشكل محسوبة من محتواه المرسوم. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | يحدّث هندسة الشكل من كائن [`IGeometryPath`](../igeometrypath). يجب أن تكون الإحداثيات نسبية إلى الزاوية اليسرى العلوية للشكل. يغيّر نوع الشكل ([`ShapeType`](../geometryshape/shapetype)) إلى Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | يحدّث هندسة الشكل من مصفوفة من [`IGeometryPath`](../igeometrypath). يجب أن تكون الإحداثيات نسبية إلى الزاوية اليسرى العلوية للشكل. يغيّر نوع الشكل ([`ShapeType`](../geometryshape/shapetype)) إلى Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | يحفظ محتوى الشكل كملف SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | يحفظ محتوى الشكل كملف SVG. |

### انظر أيضًا

* فئة [GeometryShape](../geometryshape)
* واجهة [IAutoShape](../iautoshape)
* مساحة الاسم [Aspose.Slides](../../aspose.slides)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->