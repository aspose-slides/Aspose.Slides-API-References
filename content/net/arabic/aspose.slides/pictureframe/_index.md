---
title: PictureFrame
second_title: Aspose.Sildes لـ .NET مرجع واجهة برمجة التطبيقات
description: يمثل إطارًا يحتوي على صورة بالداخل.
type: docs
weight: 9430
url: /ar/aspose.slides/pictureframe/
---
## فئة PictureFrame

يمثل إطارًا يحتوي على صورة بالداخل.

```csharp
public class PictureFrame : GeometryShape, IPictureFrame
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | يُرجع مجموعة من قيم تعديل الشكل. قراءة فقط [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | يُرجع أو يُعيّن النص البديل المرتبط بالشكل. قراءة/كتابة String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | يُرجع أو يُعيّن عنوان النص البديل المرتبط بالشكل. قراءة/كتابة String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | الخاصية تحدد كيفية عرض الشكل في وضع العرض بالأبيض والأسود. قراءة/كتابة [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | يُرجع عدد مواقع الاتصال على الشكل. قراءة فقط Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | يُرجع البيانات المخصصة للشكل. قراءة فقط [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | يُرجع كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على الشكل. ملاحظة: يمكن أن يُرجع null لأنواع معينة من الأشكال التي لا تحتوي على خصائص التأثير. قراءة فقط [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | يُرجع كائن FillFormat الذي يحتوي على خصائص تعبئة الشكل. ملاحظة: يمكن أن يُرجع null لأنواع معينة من الأشكال التي لا تحتوي على خصائص التعبئة. قراءة فقط [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | يُرجع أو يُعيّن خصائص إطار الشكل. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | يحدد أو يعيّن ارتفاع الشكل بوحدات النقاط. قراءة/كتابة Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | يحدد ما إذا كان الشكل مخفيًا. قراءة/كتابة Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | يُرجع أو يُعيّن الارتباط التشعبي المحدد للنقر بالفأرة. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | يُرجع مدير الارتباط التشعبي. قراءة فقط [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | يُرجع أو يُعيّن الارتباط التشعبي المحدد للتحويم بالفأرة. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | يحدد ما إذا كان PictureFrame كائن Cameo أم لا. قراءة فقط Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | يحدد أو يعيّن خيار "علامة كزخرفة". قراءة/كتابة Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | يحدد ما إذا كان الشكل مُجمّعًا. قراءة فقط Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | يحدد ما إذا كان الشكل TextHolder_PPT. قراءة فقط Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | يُرجع كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل. ملاحظة: يمكن أن يُرجع null لأنواع معينة من الأشكال التي لا تحتوي على خصائص الخط. قراءة فقط [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | يُرجع أو يُعيّن اسم الشكل. يجب أن لا يكون فارغًا. استخدم سلسلة فارغة إذا لزم الأمر. قراءة/كتابة String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | يُرجع معرفًا فريدًا محدودًا بالشريحة يظل ثابتًا طوال عمر الشكل ويسمح لبرنامج PowerPoint أو كود interop بالإشارة إلى الشكل من أي مكان في المستند. قراءة فقط UInt32. راجع أيضًا [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | يُرجع كائن GroupShape الأصل إذا كان الشكل مُجمّعًا. وإلا يُرجع null. قراءة فقط [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | يُرجع كائن PictureFillFormat لإطار الصورة. قراءة فقط [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | يُرجع أقفال الشكل. قراءة فقط [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | يُرجع العنصر النائب للشكل. يُرجع null إذا لم يكن للشكل عنصر نائب. قراءة فقط [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | يُرجع العرض التقديمي الأصلي لل شريحة. قراءة فقط [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | يُرجع أو يُعيّن الخصائص الخام لإطار الشكل. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | يُرجع أو يُعيّن مقياس ارتفاع (نسبيًا إلى حجم الصورة الأصلي) لإطار الصورة. القيمة 1.0 تمثل 100٪. قراءة/كتابة Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | يُرجع أو يُعيّن مقياس العرض (نسبيًا إلى حجم الصورة الأصلي) لإطار الصورة. القيمة 1.0 تمثل 100٪. قراءة/كتابة Single. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | يُرجع أو يُعيّن عدد درجات دوران الشكل المحدد حول محور z. القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ القيمة السالبة تشير إلى دوران عكس اتجاهها. قراءة/كتابة Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | يُرجع أقفال الشكل. قراءة فقط [`IPictureFrameLock`](../ipictureframelock). (2 properties) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | يُرجع كائن نمط الشكل. قراءة فقط [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | يُرجع أو يُعيّن نوع AutoShape لإطار الصورة. هناك جميع العناصر المسموح بها في المجموعة [`ShapeType`](../shapetype)، باستثناء جميع أنواع الخطوط: |
| [Slide](../../aspose.slides/shape/slide) { get; } | يُرجع الشريحة الأصلية للشكل. قراءة فقط [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | يُرجع كائن ThreeDFormat الذي يحتوي على خصائص التأثير الثلاثي الأبعاد للشكل. ملاحظة: يمكن أن يُرجع null لأنواع معينة من الأشكال التي لا تحتوي على خصائص ثلاثية الأبعاد. قراءة فقط [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | يُرجع معرفًا داخليًا محدودًا بالعرض التقديمي مخصصًا للاستخدام من قبل الإضافات أو الكود الآخر. نظرًا لأنه يمكن إعادة تعيين هذه القيمة من قبل المستخدم أو برمجيًا، يجب عدم اعتبارها مفتاحًا فريدًا دائمًا. قراءة فقط UInt32. راجع أيضًا [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | يحدد أو يعيّن عرض الشكل بوحدات النقاط. قراءة/كتابة Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | يحدد أو يعيّن الإحداثي x للزاوية العليا اليسرى للشكل بوحدات النقاط. قراءة/كتابة Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | يحدد أو يعيّن الإحداثي y للزاوية العليا اليسرى للشكل بوحدات النقاط. قراءة/كتابة Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | يُرجع موضع الشكل في ترتيب z. Shapes[0] يُرجع الشكل في خلفية ترتيب z، و Shapes[Shapes.Count - 1] يُرجع الشكل في مقدمة ترتيب z. قراءة فقط Int32. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى العنصر المحدد. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | يخلق ويُرجع مصفوفة من عناصر الشكل. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | يُرجع عنصرًا نائبًا أساسيًا (الشكل من التخطيط أو الشريحة الأساسية التي يُورّث منها الشكل الحالي). يُرجع null إذا لم يكن الشكل الحالي مورّثًا. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | يُرجع نسخة من مسار الشكل الهندسي. الإحداثيات نسبية للزاوية العلوية اليسرى للشكل. |
| [GetImage](../../aspose.slides/shape/getimage)() | يُرجع صورة مصغرة للشكل. يُستخدم النوع ShapeThumbnailBounds.Shape كقيمة افتراضية. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | يُرجع صورة مصغرة للشكل. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | يحصل على الحدود البصرية للشكل المحسوبة من محتواه المرسوم. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | يُحدّث هندسة الشكل من كائن [`IGeometryPath`](../igeometrypath). يجب أن تكون الإحداثيات نسبية للزاوية العلوية اليسرى للشكل. يغيّر نوع الشكل ([`ShapeType`](../geometryshape/shapetype)) إلى Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | يُحدّث هندسة الشكل من مصفوفة [`IGeometryPath`](../igeometrypath). يجب أن تكون الإحداثيات نسبية للزاوية العلوية اليسرى للشكل. يغيّر نوع الشكل ([`ShapeType`](../geometryshape/shapetype)) إلى Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | يحفظ محتوى الشكل كملف SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | يحفظ محتوى الشكل كملف SVG. |

### أمثلة

توضح الأمثلة التالية كيفية تغيير الصورة المصغرة لإطار الصوت.

```csharp
[C#]
using (var presentation = new Presentation())
{
    var slide = presentation.Slides[0];
    // يضيف إطار صوت إلى الشريحة بموقع وحجم محددين.
    var audioStream = new FileStream("sample2.mp3", FileMode.Open, FileAccess.Read);
    var audioFrame = slide.Shapes.AddAudioFrameEmbedded(150, 100, 50, 50, audioStream);
    audioStream.Dispose();
    // يضيف صورة إلى موارد العرض التقديمي.
    var imageStream = File.OpenRead("eagle.jpeg");
    var audioImage = presentation.Images.AddImage(imageStream);
    imageStream.Dispose();
    // يحدد الصورة لإطار الصوت.
	//يحفظ العرض التقديمي المعدل إلى القرص
    presentation.Save("example_out.pptx", SaveFormat.Pptx);
}
```

### انظر أيضا

* الفئة [GeometryShape](../geometryshape)
* الواجهة [IPictureFrame](../ipictureframe)
* الفضاء الاسمي [Aspose.Slides](../../aspose.slides)
* التجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->