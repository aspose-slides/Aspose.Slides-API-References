---
title: SmartArtShape
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: يمثل شكل SmartArt
type: docs
weight: 10660
url: /ar/aspose.slides.smartart/smartartshape/
---
## SmartArtShape فئة

يمثل شكل SmartArt

```csharp
public class SmartArtShape : GeometryShape, ISmartArtShape
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | تعيد مجموعة من قيم تعديل الشكل. للقراءة فقط [`IAdjustValueCollection`](../../aspose.slides/iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | تعيد أو تعيين النص البديل المرتبط بالشكل. قراءة/كتابة String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | تعيد أو تعيين عنوان النص البديل المرتبط بالشكل. قراءة/كتابة String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | تحدد الخاصية كيفية عرض الشكل في وضع العرض بالأبيض والأسود. قراءة/كتابة [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعيد عدد مواقع الاتصال على الشكل. للقراءة فقط Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | تعيد البيانات المخصصة للشكل. للقراءة فقط [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | تعيد كائن EffectFormat الذي يحتوي على تأثيرات بكسل مطبقة على الشكل. ملاحظة: يمكن أن تُعيد null لبعض أنواع الأشكال التي لا تحتوي على خصائص تأثير. للقراءة فقط [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | تعيد كائن FillFormat الذي يحتوي على خصائص تنسيق الملء للشكل. ملاحظة: يمكن أن تُعيد null لبعض أنواع الأشكال التي لا تحتوي على خصائص ملء. للقراءة فقط [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | تعيد أو تعيين خصائص إطار الشكل. قراءة/كتابة [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | تحصل أو تعين ارتفاع الشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | تحدد ما إذا كان الشكل مخفيًا. قراءة/كتابة Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | تعيد أو تعيين الارتباط الفائق المحدد للنقر بالماوس. قراءة/كتابة [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | تعيد مدير الارتباط الفائق. للقراءة فقط [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | تعيد أو تعيين الارتباط الفائق المحدد للتنقل فوق الفأرة. قراءة/كتابة [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | تحصل أو تعين خيار 'وضع علامة كديكور'. قراءة/كتابة Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | تحدد ما إذا كان الشكل مجموعة. للقراءة فقط Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | تحدد ما إذا كان الشكل TextHolder_PPT. للقراءة فقط Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | تعيد كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل. ملاحظة: يمكن أن تُعيد null لبعض أنواع الأشكال التي لا تحتوي على خصائص خط. للقراءة فقط [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | تعيد أو تعيين اسم الشكل. يجب أن لا يكون فارغًا. استخدم قيمة سلسلة فارغة إذا لزم الأمر. قراءة/كتابة String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | تعيد معرف فريد محصور بالشرائح يبقى ثابتًا طوال عمر الشكل ويسمح لبرنامج PowerPoint أو كود التفاعل بالإشارة إلى الشكل من أي مكان في المستند بثقة. للقراءة فقط UInt32. انظر أيضًا [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | تعيد كائن GroupShape الأب إذا كان الشكل مجموعة. وإلا تعيد null. للقراءة فقط [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | تعيد العنصر النائب للشكل. تعيد null إذا لم يكن للشكل عنصر نائب. للقراءة فقط [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | تعيد العرض التقديمي الأب للشرائح. للقراءة فقط [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | تعيد أو تعيين خصائص إطار الشكل الخام. قراءة/كتابة [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعيد أو تعيين عدد درجات تدوير الشكل المحدد حول محور z. القيمة الموجبة تشير إلى التدوير باتجاه عقارب الساعة؛ القيمة السالبة تشير إلى التدوير عكس عقارب الساعة. قراءة/كتابة Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | تعيد أقفال الشكل. للقراءة فقط [`IBaseShapeLock`](../../aspose.slides/ibaseshapelock). |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | تعيد كائن نمط الشكل. للقراءة فقط [`IShapeStyle`](../../aspose.slides/ishapestyle). |
| override [ShapeType](../../aspose.slides.smartart/smartartshape/shapetype) { get; set; } | تعيد أو تعيين نوع الإعداد المسبق للهندسة. ملاحظة: عند تغيير القيمة سيتم إعادة تعيين جميع قيم الضبط إلى القيم الافتراضية. قراءة/كتابة [`ShapeType`](../../aspose.slides/shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | تعيد شريحة الأب للشكل. للقراءة فقط [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [TextFrame](../../aspose.slides.smartart/smartartshape/textframe) { get; } | تعيد نص شكل SmartArt. للقراءة فقط [`ITextFrame`](../../aspose.slides/itextframe). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | تعيد كائن ThreeDFormat الذي يحتوي على خصائص تأثير ثلاثي الأبعاد للشكل. ملاحظة: يمكن أن تُعيد null لبعض أنواع الأشكال التي لا تحتوي على خصائص ثلاثية الأبعاد. للقراءة فقط [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | تعيد معرف داخلي محصور بالعرض التقديمي مخصص للاستخدام من الإضافات أو الكود الآخر. بما أن هذه القيمة قد يعيد تعيينها المستخدم أو برمجيًا، فلا يجب اعتبارها مفتاحًا فريدًا دائمًا. للقراءة فقط UInt32. انظر أيضًا [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | تحصل أو تعين عرض الشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | تحصل أو تعين إحداثي x للزاوية العليا اليسرى للشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | تحصل أو تعين إحداثي y للزاوية العليا اليسرى للشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | تعيد موضع الشكل في ترتيب z. Shapes[0] تعيد الشكل في خلفية ترتيب z، و Shapes[Shapes.Count - 1] تعيد الشكل في مقدمة ترتيب z. للقراءة فقط Int32. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى العنصر المحدد. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | ينشئ ويعيد مصفوفة من عناصر الشكل. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | تعيد شكل عنصر نائب أساسي (شكل من التخطيط و/أو شريحة القالب التي ورث منها الشكل الحالي). تُعيد null إذا لم يكن الشكل الحالي مُورّثًا. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | تعيد نسخة من مسار الشكل الهندسي. الإحداثيات نسبية إلى الزاوية العليا اليسرى للشكل. |
| [GetImage](../../aspose.slides/shape/getimage)() | تعيد مصغرة الشكل. يُستخدم النوع ShapeThumbnailBounds.Shape كحدود مصغرة الشكل افتراضيًا. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تعيد مصغرة الشكل. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | تحصل على حدود الشكل البصرية المحسوبة من محتواه المُعرض. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | تحديث هندسة الشكل من كائن [`IGeometryPath`](../../aspose.slides/igeometrypath). يجب أن تكون الإحداثيات نسبية إلى الزاوية العليا اليسرى للشكل. يغيّر نوع الشكل ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) إلى Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | تحديث هندسة الشكل من مصفوفة [`IGeometryPath`](../../aspose.slides/igeometrypath). يجب أن تكون الإحداثيات نسبية إلى الزاوية العليا اليسرى للشكل. يغيّر نوع الشكل ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) إلى Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | يحفظ محتوى الشكل كملف SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | يحفظ محتوى الشكل كملف SVG. |

### انظر أيضًا

* فئة [GeometryShape](../../aspose.slides/geometryshape)
* واجهة [ISmartArtShape](../ismartartshape)
* مساحة اسم [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->