---
title: SmartArtShape
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: يمثل شكل SmartArt
type: docs
weight: 10680
url: /ar/aspose.slides.smartart/smartartshape/
---
## SmartArtShape فئة

Represents SmartArt shape

```csharp
public class SmartArtShape : GeometryShape, ISmartArtShape
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | يُرجع مجموعة من قيم تعديل الشكل. قراءة فقط [`IAdjustValueCollection`](../../aspose.slides/iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | يُرجع أو يضبط النص البديل المرتبط بالشكل. قراءة/كتابة String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | يُرجع أو يضبط عنوان النص البديل المرتبط بالشكل. قراءة/كتابة String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | المِلْكِيَّة تُحدِّد كيف سيُظهر الشكل في وضع العرض بالأبيض والأسود.. قراءة/كتابة [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | يُرجع عدد مواقع الاتصال على الشكل. قراءة فقط Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | يُرجع البيانات المخصصة للشكل. قراءة فقط [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | يُرجع كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على الشكل. ملاحظة: قد يُعيد null لبعض الأنواع من الأشكال التي لا تحتوي على خصائص تأثير. قراءة فقط [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | يُرجع كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة للشكل. ملاحظة: قد يُعيد null لبعض الأنواع من الأشكال التي لا تحتوي على خصائص تعبئة. قراءة فقط [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | يُرجع أو يضبط خصائص إطار الشكل. قراءة/كتابة [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | يُرجع أو يضبط ارتفاع الشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | يحدّد ما إذا كان الشكل مخفيًا. قراءة/كتابة Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | يُرجع أو يضبط الارتباط التشعبي المحدد للنقر بالماوس. قراءة/كتابة [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | يُرجع مدير الارتباط التشعبي. قراءة فقط [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | يُرجع أو يضبط الارتباط التشعبي المحدد للتحويم بالفأرة. قراءة/كتابة [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | يُرجع أو يضبط خيار 'وضع علامة كديكوري' قراءة/كتابة Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | يحدّد ما إذا كان الشكل مجمعًا. قراءة فقط Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | يحدّد ما إذا كان الشكل TextHolder_PPT. قراءة فقط Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | يُرجع كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل. ملاحظة: قد يُعيد null لبعض الأنواع من الأشكال التي لا تحتوي على خصائص خط. قراءة فقط [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | يُرجع أو يضبط اسم الشكل. يجب ألا يكون فارغًا. استخدم قيمة سلسلة فارغة إذا لزم الأمر. قراءة/كتابة String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | يُرجع معرفًا فريدًا محصورًا بالشريحة يظل ثابتًا طوال عمر الشكل ويسمح لبرنامج PowerPoint أو كود التفاعل بالإشارة إلى الشكل من أي مكان في المستند بثقة. قراءة فقط UInt32. انظر أيضًا [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | يُرجع كائن GroupShape الأب إذا كان الشكل مجمعًا. وإلا يُعيد null. قراءة فقط [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | يُرجع العنصر النائب للشكل. يُعيد null إذا كان الشكل ليس له عنصر نائب. قراءة فقط [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | يُرجع العرض الأب للشرائح. قراءة فقط [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | يُرجع أو يضبط خصائص إطار الشكل الخام. قراءة/كتابة [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | يُرجع أو يضبط عدد درجات دوران الشكل المحدد حول المحور z. القيمة الموجبة تُشير إلى دوران باتجاه عقارب الساعة؛ القيمة السالبة تُشير إلى دوران عكس اتجاه عقارب الساعة. قراءة/كتابة Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | يُرجع قفل الشكل. قراءة فقط [`IBaseShapeLock`](../../aspose.slides/ibaseshapelock). |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | يُرجع كائن نمط الشكل. قراءة فقط [`IShapeStyle`](../../aspose.slides/ishapestyle). |
| override [ShapeType](../../aspose.slides.smartart/smartartshape/shapetype) { get; set; } | يُرجع أو يضبط نوع الشكل الهندسي المُحدد مسبقًا. ملاحظة: عند تغيير القيمة ستُعاد جميع قيم التعديل إلى القيم الافتراضية. قراءة/كتابة [`ShapeType`](../../aspose.slides/shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | يُرجع الشريحة الأب للشكل. قراءة فقط [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [TextFrame](../../aspose.slides.smartart/smartartshape/textframe) { get; } | يُرجع نص شكل SmartArt. قراءة فقط [`ITextFrame`](../../aspose.slides/itextframe). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | يُرجع كائن ThreeDFormat الذي يحتوي على خصائص تأثير ثلاثي الأبعاد للشكل. ملاحظة: قد يُعيد null لبعض الأنواع من الأشكال التي لا تحتوي على خصائص ثلاثية الأبعاد. قراءة فقط [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | يُرجع معرفًا داخليًا محصورًا بالعرض مخصصًا للاستخدام من قبل الإضافات أو الكود الآخر. لأن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، فلا ينبغي اعتبارها مفتاحًا فريدًا دائمًا. قراءة فقط UInt32. انظر أيضًا [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | يُرجع أو يضبط عرض الشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | يُرجع أو يضبط إحداثي x للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | يُرجع أو يضبط إحداثي y للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | يُرجع موضع الشكل في ترتيب z. Shapes[0] يُعيد الشكل في مؤخرة ترتيب z، و Shapes[Shapes.Count - 1] يُعيد الشكل في مقدمة ترتيب z. قراءة فقط Int32. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى العنصر المحدد. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | ينشئ ويُرجع مصفوفة من عناصر الشكل. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | يُرجع شكل عنصر نائب أساسي (شكل من التخطيط و/أو شريحة القالب التي يُورث منها الشكل الحالي). يُرجع null إذا لم يكن الشكل الحالي مُورثًا. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | يُرجع نسخة من مسار الشكل الهندسي. الإحداثيات نسبية للزاوية العلوية اليسرى للشكل. |
| [GetImage](../../aspose.slides/shape/getimage)() | يُرجع صورة مصغرة للشكل. يُستخدم النوع ShapeThumbnailBounds.Shape كحدود الصورة المصغرة بشكل افتراضي. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | يُرجع صورة مصغرة للشكل. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | يُرجع الحدود البصرية للشكل المحسوبة من محتواه المُصوّر. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | يحدّد أن هذا الشكل ليس عنصرًا نائبًا. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | يُحدّث هندسة الشكل من كائن [`IGeometryPath`](../../aspose.slides/igeometrypath). يجب أن تكون الإحداثيات نسبية للزاوية العلوية اليسرى للشكل. يغيّر نوع الشكل ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) إلى Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | يُحدّث هندسة الشكل من مصفوفة [`IGeometryPath`](../../aspose.slides/igeometrypath). يجب أن تكون الإحداثيات نسبية للزاوية العلوية اليسرى للشكل. يغيّر نوع الشكل ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) إلى Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | يحفظ محتوى الشكل كملف SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | يحفظ محتوى الشكل كملف SVG. |

### انظر أيضاً

* فئة [GeometryShape](../../aspose.slides/geometryshape)
* واجهة [ISmartArtShape](../ismartartshape)
* مساحة اسم [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->