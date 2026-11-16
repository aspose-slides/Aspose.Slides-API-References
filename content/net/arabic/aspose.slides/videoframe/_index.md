---
title: VideoFrame
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: يمثل مقطع فيديو على شريحة.
type: docs
weight: 11740
url: /ar/aspose.slides/videoframe/
---
## فئة VideoFrame

يمثل مقطع فيديو على شريحة.

```csharp
public class VideoFrame : PictureFrame, IVideoFrame
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | يرجع مجموعة من قيم تعديل الشكل. للقراءة فقط [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | يرجع أو يضبط النص البديل المرتبط بشكل. للقراءة/الكتابة String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | يرجع أو يضبط عنوان النص البديل المرتبط بشكل. للقراءة/الكتابة String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | تحدد الخاصية كيفية عرض الشكل في وضع العرض بالأبيض والأسود. للقراءة/الكتابة [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/videoframe/captiontracks) { get; } | يحصل على مجموعة الترجمات المغلقة المرتبطة بإطار الفيديو. هذه الخاصية للقراءة فقط وتُرجع [`ICaptionsCollection`](../icaptionscollection) يحتوي على جميع مسارات الترجمة. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | يرجع عدد نقاط الاتصال على الشكل. للقراءة فقط Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | يرجع البيانات المخصصة للشكل. للقراءة فقط [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | يرجع كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على الشكل. ملاحظة: يمكن أن يُرجع null لبعض أنواع الأشكال التي لا تملك خصائص تأثير. للقراءة فقط [`IEffectFormat`](../ieffectformat). |
| [EmbeddedVideo](../../aspose.slides/videoframe/embeddedvideo) { get; set; } | يرجع أو يضبط كائن الفيديو المضمّن. للقراءة/الكتابة [`IVideo`](../ivideo). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | يرجع كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة للشكل. ملاحظة: يمكن أن يُرجع null لبعض الأنواع التي لا تملك خصائص تعبئة. للقراءة فقط [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | يرجع أو يضبط خصائص إطار الشكل. للقراءة/الكتابة [`IShapeFrame`](../ishapeframe). |
| [FullScreenMode](../../aspose.slides/videoframe/fullscreenmode) { get; set; } | يحدد ما إذا كان الفيديو يُعرض في وضع ملء الشاشة. للقراءة/الكتابة Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | يحصل أو يضبط ارتفاع الشكل، بالقياس بالنقاط. للقراءة/الكتابة Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | يحدد ما إذا كان الشكل مخفيًا. للقراءة/الكتابة Boolean. |
| [HideAtShowing](../../aspose.slides/videoframe/hideatshowing) { get; set; } | يحدد ما إذا كان VideoFrame مخفيًا. للقراءة/الكتابة Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | يرجع أو يضبط الارتباط التشعبي المحدد للنقر بالفأرة. للقراءة/الكتابة [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | يرجع مدير الارتباط التشعبي. للقراءة فقط [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | يرجع أو يضبط الارتباط التشعبي المحدد لتمرير الفأرة. للقراءة/الكتابة [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | يحدد ما إذا كان PictureFrame كائن Cameo أم لا. للقراءة فقط Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | يحصل أو يضبط خيار 'Mark as decorative'. للقراءة/الكتابة Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | يحدد ما إذا كان الشكل مجموعة. للقراءة فقط Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | يحدد ما إذا كان الشكل هو TextHolder_PPT. للقراءة فقط Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | يرجع كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل. ملاحظة: يمكن أن يُرجع null لبعض الأنواع التي لا تملك خصائص خط. للقراءة فقط [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/videoframe/linkpathlong) { get; set; } | يرجع أو يضبط اسم ملف الفيديو المرتبط بـ VideoFrame. للقراءة/الكتابة String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | يرجع أو يضبط اسم الشكل. يجب ألا يكون فارغًا. استخدم قيمة سلسلة فارغة إذا لزم الأمر. للقراءة/الكتابة String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | يرجع معرفًا فريدًا على مستوى الشريحة يبقى ثابتًا طوال عمر الشكل ويسمح لـ PowerPoint أو كود التفاعل بالإشارة إلى الشكل من أي مكان في المستند. للقراءة فقط UInt32. انظر أيضًا [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | يرجع كائن GroupShape الأب إذا كان الشكل مجموعة. وإلا يرجع null. للقراءة فقط [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | يرجع كائن PictureFillFormat لإطار الصورة. للقراءة فقط [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | يرجع أقفال الشكل. للقراءة فقط [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | يرجع العنصر النائب للشكل. يُرجع null إذا لم يكن للشكل عنصر نائب. للقراءة فقط [`IPlaceholder`](../iplaceholder). |
| [PlayLoopMode](../../aspose.slides/videoframe/playloopmode) { get; set; } | يحدد ما إذا كان الفيديو متكررًا. للقراءة/الكتابة Boolean. |
| [PlayMode](../../aspose.slides/videoframe/playmode) { get; set; } | يرجع أو يضبط وضع تشغيل الفيديو. للقراءة/الكتابة [`VideoPlayModePreset`](../videoplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | يرجع العرض التقديمي الأب للشريحة. للقراءة فقط [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | يرجع أو يضبط خصائص إطار الشكل الخام. للقراءة/الكتابة [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | يرجع أو يضبط مقياس الارتفاع (النسبة إلى حجم الصورة الأصلية) لإطار الصورة. القيمة 1.0 تمثل 100٪. للقراءة/الكتابة Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | يرجع أو يضبط مقياس العرض (النسبة إلى حجم الصورة الأصلية) لإطار الصورة. القيمة 1.0 تمثل 100٪. للقراءة/الكتابة Single. |
| [RewindVideo](../../aspose.slides/videoframe/rewindvideo) { get; set; } | يحدد ما إذا كان الفيديو يُعاد تلقائيًا إلى البداية بمجرد انتهاء تشغيل الفيلم. للقراءة/الكتابة Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | يرجع أو يضبط عدد درجات دوران الشكل المحدد حول المحور z. القيمة الموجبة تشير إلى دوران مع اتجاه عقارب الساعة؛ القيمة السلبية تشير إلى دوران عكس اتجاه عقارب الساعة. للقراءة/الكتابة Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | يرجع أقفال الشكل. للقراءة فقط [`IPictureFrameLock`](../ipictureframelock). (خاصيتان) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | يرجع كائن نمط الشكل. للقراءة فقط [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | يرجع أو يضبط نوع AutoShape لإطار الصورة. هناك جميع العناصر المسموح بها في المجموعة [`ShapeType`](../shapetype)، باستثناء جميع أنواع الخطوط: |
| [Slide](../../aspose.slides/shape/slide) { get; } | يرجع الشريحة الأب للشكل. للقراءة فقط [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | يرجع كائن ThreeDFormat الذي يحتوي على خصائص التأثير ثلاثي الأبعاد للشكل. ملاحظة: قد يرجع null لبعض الأنواع التي لا تملك خصائص ثلاثية الأبعاد. للقراءة فقط [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/videoframe/trimfromend) { get; set; } | تقليل النهاية [ms] |
| [TrimFromStart](../../aspose.slides/videoframe/trimfromstart) { get; set; } | تقليل البداية [ms] |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | يرجع معرفًا داخليًا على مستوى العرض مخصصًا لاستخدام الإضافات أو الكود الآخر. نظرًا لأن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، يجب عدم اعتبارها مفتاحًا فريدًا دائمًا. للقراءة فقط UInt32. انظر أيضًا [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/videoframe/volume) { get; set; } | يرجع أو يضبط حجم الصوت. للقراءة/الكتابة [`AudioVolumeMode`](../audiovolumemode). |
| [VolumeValue](../../aspose.slides/videoframe/volumevalue) { get; set; } | يرجع أو يضبط حجم الفيديو الدقيق كنسبة مئوية. يتم التعبير عن القيمة كنسبة مئوية من 0 إلى 100. استخدم هذه الخاصية لقراءة أو ضبط قيم الصوت بدقة أكبر من المستويات المحددة مسبقًا المتاحة عبر الخاصية [`Volume`](./volume). للقراءة/الكتابة Single. |
| [Width](../../aspose.slides/shape/width) { get; set; } | يحصل أو يضبط عرض الشكل، بالقياس بالنقاط. للقراءة/الكتابة Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | يحصل أو يضبط إحداثي x للزاوية العليا اليسرى للشكل، بالقياس بالنقاط. للقراءة/الكتابة Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | يحصل أو يضبط إحداثي y للزاوية العليا اليسرى للشكل، بالقياس بالنقاط. للقراءة/الكتابة Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | يرجع موضع الشكل في ترتيب z. Shapes[0] تُرجع الشكل في الخلفية، وShapes[Shapes.Count - 1] تُرجع الشكل في المقدمة. للقراءة فقط Int32. |

## الأساليب

| الاسم | الوصف |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى العنصر المحدد. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | ينشئ ويُرجع مصفوفة من عناصر الشكل. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | يرجع شكل عنصر نائب أساسي (شكل من تخطيط أو شريحة رئيسية يرث منها الشكل الحالي). يُرجع null إذا لم يكن الشكل الحالي مُوروثًا. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | يرجع نسخة من مسار الشكل الهندسي. الإحداثيات نسبية للزاوية اليسرى العليا للشكل. |
| [GetImage](../../aspose.slides/shape/getimage)() | يرجع صورة مصغرة للشكل. يُستخدم النوع ShapeThumbnailBounds.Shape كقيمة افتراضية لحدود الصورة المصغرة. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | يرجع صورة مصغرة للشكل. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | يحصل على حدود الشكل البصرية المحسوبة من محتواه المُظهر. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | يحدّث هندسة الشكل من كائن [`IGeometryPath`](../igeometrypath). يجب أن تكون الإحداثيات نسبية للزاوية اليسرى العليا للشكل. يغيّر نوع الشكل ([`ShapeType`](../geometryshape/shapetype)) إلى Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | يحدّث هندسة الشكل من مصفوفة [`IGeometryPath`](../igeometrypath). يجب أن تكون الإحداثيات نسبية للزاوية اليسرى العليا للشكل. يغيّر نوع الشكل ([`ShapeType`](../geometryshape/shapetype)) إلى Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | يحفظ محتوى الشكل كملف SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | يحفظ محتوى الشكل كملف SVG. |

### انظر أيضا

* فئة [PictureFrame](../pictureframe)
* واجهة [IVideoFrame](../ivideoframe)
* مساحة الاسم [Aspose.Slides](../../aspose.slides)
* تجميعة [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->