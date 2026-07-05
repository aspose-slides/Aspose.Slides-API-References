---
title: PictureFrame
second_title: Aspose.Sildes لـ .NET مرجع API
description: يمثل إطارًا يحتوي على صورة داخله.
type: docs
weight: 9410
url: /ar/aspose.slides/pictureframe/
---
## PictureFrame فئة

يمثل إطارًا يحتوي على صورة داخله.

```csharp
public class PictureFrame : GeometryShape, IPictureFrame
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | إرجاع مجموعة من قيم تعديل الشكل. قراءة فقط [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | إرجاع أو تعيين النص البديل المرتبط بالشكل. قراءة/كتابة سلسلة. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | إرجاع أو تعيين عنوان النص البديل المرتبط بالشكل. قراءة/كتابة سلسلة. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | خاصية تحدد كيفية عرض الشكل في وضع اللونين الأسود والأبيض. قراءة/كتابة [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | إرجاع عدد نقاط الاتصال على الشكل. قراءة فقط Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | إرجاع البيانات المخصصة للشكل. قراءة فقط [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | إرجاع كائن EffectFormat الذي يحتوي على التأثيرات البكسلية المطبقة على الشكل. ملاحظة: قد يُرجع قيمة null لبعض أنواع الأشكال التي لا تملك خصائص تأثير. قراءة فقط [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | إرجاع كائن FillFormat الذي يحتوي على خصائص تنسيق الملء للشكل. ملاحظة: قد يُرجع قيمة null لبعض أنواع الأشكال التي لا تملك خصائص ملء. قراءة فقط [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | إرجاع أو تعيين خصائص إطار الشكل. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | إرجاع أو تعيين ارتفاع الشكل، مقاس بالنقاط. قراءة/كتابة Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | تحديد ما إذا كان الشكل مخفيًا. قراءة/كتابة Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | إرجاع أو تعيين الارتباط التشعبي المعرفة للنقر بالفأرة. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | إرجاع مدير الارتباط التشعبي. قراءة فقط [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | إرجاع أو تعيين الارتباط التشعبي المعرفة عندما يمر الفأرة فوقه. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | تحديد ما إذا كان PictureFrame كائن Cameo أم لا. قراءة فقط Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | إرجاع أو تعيين خيار 'علامة كزخرفة'. قراءة/كتابة Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | تحديد ما إذا كان الشكل مجموعًا. قراءة فقط Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | تحديد ما إذا كان الشكل TextHolder_PPT. قراءة فقط Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | إرجاع كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل. ملاحظة: قد يُرجع قيمة null لبعض أنواع الأشكال التي لا تملك خصائص خط. قراءة فقط [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | إرجاع أو تعيين اسم الشكل. يجب أن لا يكون فارغًا. استخدم قيمة سلسلة فارغة إذا لزم الأمر. قراءة/كتابة سلسلة. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | إرجاع معرف فريد محصور بالشرائح يبقى ثابتًا طوال عمر الشكل ويسمح لـ PowerPoint أو كود التفاعل بالإشارة إلى الشكل بثقة من أي مكان في المستند. قراءة فقط UInt32. انظر أيضًا [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | إرجاع كائن GroupShape الأب إذا كان الشكل مجموعًا. خلاف ذلك يرجع null. قراءة فقط [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | إرجاع كائن PictureFillFormat لإطار الصورة. قراءة فقط [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | إرجاع أقفال الشكل. قراءة فقط [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | إرجاع العنصر النائب للشكل. يرجع null إذا لم يكن للشكل عنصر نائب. قراءة فقط [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | إرجاع العرض التقديمي الأب للشرحة. قراءة فقط [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | إرجاع أو تعيين خصائص إطار الشكل الخام. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | إرجاع أو تعيين مقياس الارتفاع (نسبةً إلى حجم الصورة الأصلي) لإطار الصورة. القيمة 1.0 تعادل 100٪. قراءة/كتابة Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | إرجاع أو تعيين مقياس العرض (نسبةً إلى حجم الصورة الأصلي) لإطار الصورة. القيمة 1.0 تعادل 100٪. قراءة/كتابة Single. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | إرجاع أو تعيين عدد الدرجات التي يدور بها الشكل المحدد حول محور z. القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ القيمة السالبة تشير إلى دوران عكس اتجاه العقارب. قراءة/كتابة Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | إرجاع أقفال الشكل. قراءة فقط [`IPictureFrameLock`](../ipictureframelock). (خاصيتان) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | إرجاع كائن نمط الشكل. قراءة فقط [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | إرجاع أو تعيين نوع AutoShape لـ PictureFrame. جميع العناصر المسموح بها في المجموعة [`ShapeType`](../shapetype)، باستثناء جميع أنواع الخطوط: |
| [Slide](../../aspose.slides/shape/slide) { get; } | إرجاع الشريحة الأم للشكل. قراءة فقط [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | إرجاع كائن ThreeDFormat الذي يحتوي على خصائص تأثير ثلاثي الأبعاد للشكل. ملاحظة: قد يُرجع null لبعض أنواع الأشكال التي لا تمتلك خصائص ثلاثية الأبعاد. قراءة فقط [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | إرجاع معرف داخلي محصور بالعرض التقديمي يُقصد به الاستخدام من قبل الإضافات أو كود آخر. بما أن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، لا ينبغي اعتبارها مفتاحًا فريدًا دائمًا. قراءة فقط UInt32. انظر أيضًا [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | إرجاع أو تعيين عرض الشكل، مقاس بالنقاط. قراءة/كتابة Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | إرجاع أو تعيين إحداثي x للزاوية العلوية اليسرى للشكل، مقاس بالنقاط. قراءة/كتابة Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | إرجاع أو تعيين إحداثي y للزاوية العلوية اليسرى للشكل، مقاس بالنقاط. قراءة/كتابة Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | إرجاع موضع الشكل في ترتيب z. Shapes[0] يُرجع الشكل في خلفية ترتيب z، و Shapes[Shapes.Count - 1] يُرجع الشكل في مقدمة ترتيب z. قراءة فقط Int32. |

## الأساليب

| الاسم | الوصف |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى عنصر محدد. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | ينشئ ويُرجع مصفوفة من عناصر الشكل. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | إرجاع شكل عنصر نائب أساسي (شكل من التخطيط و/أو شريحة القالب التي يُورث منها الشكل الحالي). يُرجع null إذا لم يكن الشكل الحالي مُورّثًا. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | إرجاع نسخة من مسار الشكل الهندسي. الإحداثيات نسبية لزاوية الشكل العلوية اليسرى. |
| [GetImage](../../aspose.slides/shape/getimage)() | إرجاع صورة مصغرة للشكل. يتم استخدام النوع ShapeThumbnailBounds.Shape لحدود الصورة المصغرة بشكل افتراضي. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | إرجاع صورة مصغرة للشكل. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | إرجاع الحدود البصرية للشكل محسوبة من محتواه المرسوم. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | يُحدّث هندسة الشكل من كائن [`IGeometryPath`](../igeometrypath). يجب أن تكون الإحداثيات نسبية لزاوية الشكل العلوية اليسرى. يغيّر نوع الشكل ([`ShapeType`](../geometryshape/shapetype)) إلى مخصص. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | يُحدّث هندسة الشكل من مصفوفة [`IGeometryPath`](../igeometrypath). يجب أن تكون الإحداثيات نسبية لزاوية الشكل العلوية اليسرى. يغيّر نوع الشكل ([`ShapeType`](../geometryshape/shapetype)) إلى مخصص. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | يحفظ محتوى الشكل كملف SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | يحفظ محتوى الشكل كملف SVG. |

### أمثلة

تظهر الأمثلة التالية كيفية تغيير مصغّر إطار الصوت.

```csharp
[C#]
using (var presentation = new Presentation())
{
    var slide = presentation.Slides[0];
    // يضيف إطار صوت إلى الشريحة بموقع وحجم محددين.
    var audioStream = new FileStream("sample2.mp3", FileMode.Open, FileAccess.Read);
    var audioFrame = slide.Shapes.AddAudioFrameEmbedded(150, 100, 50, 50, audioStream);
    audioStream.Dispose();
    // يضيف صورة إلى موارد العرض.
    var imageStream = File.OpenRead("eagle.jpeg");
    var audioImage = presentation.Images.AddImage(imageStream);
    imageStream.Dispose();
    // يضبط الصورة لإطار الصوت.
	// يحفظ العرض المعدل إلى القرص
    presentation.Save("example_out.pptx", SaveFormat.Pptx);
}
```

### انظر أيضاً

* فئة [GeometryShape](../geometryshape)
* واجهة [IPictureFrame](../ipictureframe)
* مساحة الاسم [Aspose.Slides](../../aspose.slides)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->