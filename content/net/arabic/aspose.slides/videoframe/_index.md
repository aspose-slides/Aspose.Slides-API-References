---
title: VideoFrame
second_title: مرجع Aspose.Sildes for .NET API
description: يمثل مقطع فيديو على شريحة.
type: docs
weight: 11720
url: /ar/aspose.slides/videoframe/
---
## VideoFrame فئة

Represents a video clip on a slide.

```csharp
public class VideoFrame : PictureFrame, IVideoFrame
```

## الخصائص

| Name | Description |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | إرجاع مجموعة من قيم تعديل الشكل. للقراءة فقط [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | إرجاع أو تعيين النص البديل المرتبط بالشكل. قراءة/كتابة String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | إرجاع أو تعيين عنوان النص البديل المرتبط بالشكل. قراءة/كتابة String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | تحدد الخاصية كيفية عرض الشكل في وضع العرض بالأبيض والأسود. قراءة/كتابة [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/videoframe/captiontracks) { get; } | تحصل على مجموعة الترجمات المغلقة المرتبطة بإطار الفيديو. هذه الخاصية للقراءة فقط وتُرجع [`ICaptionsCollection`](../icaptionscollection) يحتوي على جميع مسارات الترجمات. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | إرجاع عدد نقاط الاتصال على الشكل. للقراءة فقط Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | إرجاع البيانات المخصصة للشكل. للقراءة فقط [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | إرجاع كائن EffectFormat الذي يحتوي على التأثيرات البكسلية المطبقة على الشكل. ملاحظة: قد يُرجع قيمة فارغة (null) لبعض أنواع الأشكال التي لا تمتلك خصائص تأثير. للقراءة فقط [`IEffectFormat`](../ieffectformat). |
| [EmbeddedVideo](../../aspose.slides/videoframe/embeddedvideo) { get; set; } | إرجاع أو تعيين كائن الفيديو المضمن. قراءة/كتابة [`IVideo`](../ivideo). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | إرجاع كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة للشكل. ملاحظة: قد يُرجع قيمة فارغة (null) لبعض أنواع الأشكال التي لا تمتلك خصائص تعبئة. للقراءة فقط [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | إرجاع أو تعيين خصائص إطار الشكل. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [FullScreenMode](../../aspose.slides/videoframe/fullscreenmode) { get; set; } | تحدد ما إذا كان يتم عرض الفيديو في وضع ملء الشاشة. قراءة/كتابة Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | تحصل أو تعين ارتفاع الشكل بوحدة النقاط. قراءة/كتابة Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | تحدد ما إذا كان الشكل مخفيًا. قراءة/كتابة Boolean. |
| [HideAtShowing](../../aspose.slides/videoframe/hideatshowing) { get; set; } | تحدد ما إذا كان إطار الفيديو مخفيًا. قراءة/كتابة Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | إرجاع أو تعيين الارتباط التشعبي المحدد للنقر بالفأرة. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | إرجاع مدير الارتباط التشعبي. للقراءة فقط [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | إرجاع أو تعيين الارتباط التشعبي المحدد لتمرير الفأرة فوقه. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | تحدد ما إذا كان إطار الصورة كائن Cameo أم لا. للقراءة فقط Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | تحصل أو تعين خيار “تمييز كديكوري” قراءة/كتابة Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | تحدد ما إذا كان الشكل مجموعة. للقراءة فقط Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | تحدد ما إذا كان الشكل TextHolder_PPT. للقراءة فقط Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | إرجاع كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل. ملاحظة: قد يُرجع قيمة فارغة (null) لبعض أنواع الأشكال التي لا تمتلك خصائص خط. للقراءة فقط [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/videoframe/linkpathlong) { get; set; } | إرجاع أو تعيين اسم ملف الفيديو المرتبط بإطار الفيديو. قراءة/كتابة String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | إرجاع أو تعيين اسم الشكل. يجب ألا يكون فارغًا. استخدم سلسلة فارغة إذا لزم الأمر. قراءة/كتابة String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | إرجاع معرف فريد محصور بالشرائح يظل ثابتًا طوال عمر الشكل ويسمح لبرنامج PowerPoint أو كود التفاعل بالإشارة إلى الشكل من أي مكان في المستند. للقراءة فقط UInt32. أنظر أيضًا [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | إرجاع كائن GroupShape الأب إذا كان الشكل مجموعة. وإلا يُرجع قيمة فارغة (null). للقراءة فقط [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | إرجاع كائن PictureFillFormat لإطار الصورة. للقراءة فقط [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | إرجاع أقفال الشكل. للقراءة فقط [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | إرجاع العنصر النائب للشكل. يُرجع قيمة فارغة إذا لم يكن للشكل عنصر نائب. للقراءة فقط [`IPlaceholder`](../iplaceholder). |
| [PlayLoopMode](../../aspose.slides/videoframe/playloopmode) { get; set; } | تحدد ما إذا كان الفيديو متكررًا. قراءة/كتابة Boolean. |
| [PlayMode](../../aspose.slides/videoframe/playmode) { get; set; } | إرجاع أو تعيين وضع تشغيل الفيديو. قراءة/كتابة [`VideoPlayModePreset`](../videoplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | إرجاع عرض الشرائح الأب للشفرة. للقراءة فقط [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | إرجاع أو تعيين خصائص إطار الشكل الخام. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | إرجاع أو تعيين مقياس الارتفاع (نسبةً إلى حجم الصورة الأصلي) لإطار الصورة. القيمة 1.0 تعادل 100٪. قراءة/كتابة Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | إرجاع أو تعيين مقياس العرض (نسبةً إلى حجم الصورة الأصلي) لإطار الصورة. القيمة 1.0 تعادل 100٪. قراءة/كتابة Single. |
| [RewindVideo](../../aspose.slides/videoframe/rewindvideo) { get; set; } | تحدد ما إذا كان الفيديو يُعاد تلقائيًا إلى البداية بمجرد انتهاء تشغيله. قراءة/كتابة Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | إرجاع أو تعيين عدد الدرجات التي يدور بها الشكل حول المحور Z. القيمة الموجبة تعني دوران باتجاه عقارب الساعة؛ السالبة تعني دوران عكس اتجاهها. قراءة/كتابة Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | إرجاع أقفال الشكل. للقراءة فقط [`IPictureFrameLock`](../ipictureframelock). (2 properties) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | إرجاع كائن نمط الشكل. للقراءة فقط [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | إرجاع أو تعيين نوع AutoShape لإطار الصورة. جميع العناصر المسموح بها في المجموعة [`ShapeType`](../shapetype) ما عدا جميع أنواع الخطوط: |
| [Slide](../../aspose.slides/shape/slide) { get; } | إرجاع الشريحة الأب للشكل. للقراءة فقط [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | إرجاع كائن ThreeDFormat لخصائص تأثير ثلاثي الأبعاد للشكل. ملاحظة: قد يُرجع قيمة فارغة (null) لبعض أنواع الأشكال التي لا تمتلك خصائص ثلاثية الأبعاد. للقراءة فقط [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/videoframe/trimfromend) { get; set; } | تقليم النهاية [ms] |
| [TrimFromStart](../../aspose.slides/videoframe/trimfromstart) { get; set; } | تقليم البداية [ms] |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | إرجاع معرف داخلي محصور بالمستند يُقصد به الاستخدام من قِبل الإضافات أو الكود الآخر. لأن هذا القيمة قد تُعاد تعيينها من قبل المستخدم أو برمجيًا، لا يجب معاملتها كمفتاح فريد دائم. للقراءة فقط UInt32. أنظر أيضًا [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/videoframe/volume) { get; set; } | إرجاع أو تعيين حجم الصوت. قراءة/كتابة [`AudioVolumeMode`](../audiovolumemode). |
| [Width](../../aspose.slides/shape/width) { get; set; } | تحصل أو تعين عرض الشكل بوحدة النقاط. قراءة/كتابة Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | تحصل أو تعين الإحداثي السيني للزاوية اليسرى العليا للشكل بوحدة النقاط. قراءة/كتابة Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | تحصل أو تعين الإحداثي الصادي للزاوية اليسرى العليا للشكل بوحدة النقاط. قراءة/كتابة Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | إرجاع موضع الشكل في ترتيب Z. Shapes[0] تُرجع الشكل في مؤخرة ترتيب Z، و Shapes[Shapes.Count - 1] تُرجع الشكل في مقدمة ترتيب Z. للقراءة فقط Int32. |

## الطرق

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | يضيف عنصر نائب جديد إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى العنصر المحدد. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | ينشئ ويُرجع مصفوفة من عناصر الشكل. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | إرجاع شكل عنصر نائب أساسي (شكل من التخطيط و/أو الشريحة الأساسية الذي يتم وراثة الشكل الحالي منه). يتم إرجاع قيمة فارغة (null) إذا لم يكن الشكل الحالي مُورثًا. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | إرجاع نسخة من مسار الشكل الهندسي. الإحداثيات نسبةً إلى الزاوية اليسرى العليا للشكل. |
| [GetImage](../../aspose.slides/shape/getimage)() | إرجاع صورة مصغرة للشكل. يُستخدم النوع ShapeThumbnailBounds.Shape لحدود الصورة المصغرة كإعداد افتراضي. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | إرجاع صورة مصغرة للشكل. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | تحصل على حدود الشكل البصرية المحسوبة من محتواه المُرْسوم. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | يعرّف أن هذا الشكل ليس عنصرًا نائبًا. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | يُحدّث هندسة الشكل من كائن [`IGeometryPath`](../igeometrypath). يجب أن تكون الإحداثيات نسبةً إلى الزاوية اليسرى العليا للشكل. يُغيّر نوع الشكل ([`ShapeType`](../geometryshape/shapetype)) إلى مخصص. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | يُحدّث هندسة الشكل من مصفوفة [`IGeometryPath`](../igeometrypath). يجب أن تكون الإحداثيات نسبةً إلى الزاوية اليسرى العليا للشكل. يُغيّر نوع الشكل ([`ShapeType`](../geometryshape/shapetype)) إلى مخصص. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | حفظ محتوى الشكل كملف SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | حفظ محتوى الشكل كملف SVG. |

### انظر أيضًا

* فئة [PictureFrame](../pictureframe)
* واجهة [IVideoFrame](../ivideoframe)
* مساحة الأسماء [Aspose.Slides](../../aspose.slides)
* تجميعة [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->