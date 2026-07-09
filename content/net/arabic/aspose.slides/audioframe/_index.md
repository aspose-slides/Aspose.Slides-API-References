---
title: AudioFrame
second_title: مرجع API لـ Aspose.Sildes للـ .NET
description: يمثل مقطع صوتي على شريحة.
type: docs
weight: 870
url: /ar/aspose.slides/audioframe/
---
## فئة AudioFrame

يمثل مقطع صوتي على الشريحة.

```csharp
public class AudioFrame : PictureFrame, IAudioFrame
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | تُرجع مجموعة قيم تعديل الشكل. قراءة فقط [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | تُرجع أو تُعيّن النص البديل المرتبط بالشكل. قراءة/كتابة String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | تُرجع أو تُعيّن عنوان النص البديل المرتبط بالشكل. قراءة/كتابة String. |
| [AudioCdEndTrack](../../aspose.slides/audioframe/audiocdendtrack) { get; set; } | تُرجع أو تُعيّن فهرس المقطع الأخير. قراءة/كتابة Int32. |
| [AudioCdEndTrackTime](../../aspose.slides/audioframe/audiocdendtracktime) { get; set; } | تُرجع أو تُعيّن وقت المقطع الأخير. قراءة/كتابة Int32. |
| [AudioCdStartTrack](../../aspose.slides/audioframe/audiocdstarttrack) { get; set; } | تُرجع أو تُعيّن فهرس المقطع الابتدائي. قراءة/كتابة Int32. |
| [AudioCdStartTrackTime](../../aspose.slides/audioframe/audiocdstarttracktime) { get; set; } | تُرجع أو تُعيّن وقت المقطع الابتدائي. قراءة/كتابة Int32. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | تحدد كيفية عرض الشكل في وضع العرض بالأبيض والأسود. قراءة/كتابة [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/audioframe/captiontracks) { get; } | يحصل على مجموعة الشرح المغلق المرتبط بإطار الصوت. هذه الخاصية قراءة فقط وتُرجع [`ICaptionsCollection`](../icaptionscollection) يحتوي على جميع مسارات الترجمة. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تُرجع عدد مواقع الاتصال على الشكل. قراءة فقط Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | تُرجع بيانات الشكل المخصصة. قراءة فقط [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | تُرجع كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على الشكل. ملاحظة: قد يُعيد null لبعض أنواع الأشكال التي لا تحتوي على خصائص تأثير. قراءة فقط [`IEffectFormat`](../ieffectformat). |
| [Embedded](../../aspose.slides/audioframe/embedded) { get; } | تحدد ما إذا كان الصوت مدمجًا في العرض التقديمي. قراءة فقط Boolean. |
| [EmbeddedAudio](../../aspose.slides/audioframe/embeddedaudio) { get; set; } | تُرجع أو تُعيّن كائن الصوت المدمج. قراءة/كتابة [`IAudio`](../iaudio). |
| [FadeInDuration](../../aspose.slides/audioframe/fadeinduration) { get; set; } | تُحدد مدة الإبهار الأولي للوسائط بالمللي ثانية. قراءة/كتابة Single. |
| [FadeOutDuration](../../aspose.slides/audioframe/fadeoutduration) { get; set; } | تُحدد مدة التلاشي النهائي للوسائط بالمللي ثانية. قراءة/كتابة Single. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | تُرجع كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة للشكل. ملاحظة: قد يُعيد null لبعض أنواع الأشكال التي لا تحتوي على خصائص تعبئة. قراءة فقط [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | تُرجع أو تُعيّن خصائص إطار الشكل. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | يحصل أو يضبط ارتفاع الشكل بوحدات النقاط. قراءة/كتابة Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | تحدد ما إذا كان الشكل مخفيًا. قراءة/كتابة Boolean. |
| [HideAtShowing](../../aspose.slides/audioframe/hideatshowing) { get; set; } | تحدد ما إذا كان AudioFrame مخفيًا. قراءة/كتابة Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | تُرجع أو تُعيّن الارتباط التشعبي المحدد للنقر بالفأرة. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | تُرجع مدير الارتباط التشعبي. قراءة فقط [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | تُرجع أو تُعيّن الارتباط التشعبي المحدد عند مرور الفأرة. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | تحدد ما إذا كان PictureFrame كائن Cameo أم لا. قراءة فقط Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | يحصل أو يضبط خيار "تمييم كزخرفة". قراءة/كتابة Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | تحدد ما إذا كان الشكل مجموعة. قراءة فقط Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | تحدد ما إذا كان الشكل TextHolder_PPT. قراءة فقط Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | تُرجع كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل. ملاحظة: قد يُعيد null لبعض أنواع الأشكال التي لا تحتوي على خصائص خط. قراءة فقط [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/audioframe/linkpathlong) { get; set; } | تُرجع أو تُعيّن اسم ملف الصوت المرتبط بـ AudioFrame. قراءة/كتابة String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | تُرجع أو تُعيّن اسم الشكل. يجب ألا يكون فارغًا. استخدم سلسلة فارغة إذا لزم الأمر. قراءة/كتابة String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | تُرجع معرفًا فريدًا يمتد طوال عمر الشكل داخل الشريحة، ويسمح لـ PowerPoint أو كود التفاعل بالإشارة إلى الشكل من أي مكان في المستند. قراءة فقط UInt32. انظر أيضًا [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | تُرجع كائن GroupShape الأصل إذا كان الشكل مجموعة. وإلا تُعيد null. قراءة فقط [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | تُرجع كائن PictureFillFormat لإطار الصورة. قراءة فقط [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | تُرجع أقفال الشكل. قراءة فقط [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | تُرجع العنصر النائب للشكل. تُعيد null إذا كان الشكل لا يملك عنصرًا نائبًا. قراءة فقط [`IPlaceholder`](../iplaceholder). |
| [PlayAcrossSlides](../../aspose.slides/audioframe/playacrossslides) { get; set; } | تحدد ما إذا كان الصوت يُشغّل عبر الشرائح. قراءة/كتابة Boolean. |
| [PlayLoopMode](../../aspose.slides/audioframe/playloopmode) { get; set; } | تحدد ما إذا كان الصوت مكرّرًا. قراءة/كتابة Boolean. |
| [PlayMode](../../aspose.slides/audioframe/playmode) { get; set; } | تُرجع أو تُعيّن وضع تشغيل الصوت. قراءة/كتابة [`AudioPlayModePreset`](../audioplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | تُرجع العرض التقديمي الأصل للشرحة. قراءة فقط [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | تُرجع أو تُعيّن الخصائص الأولية لإطار الشكل. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | تُرجع أو تُعيّن مقياس الارتفاع (نسبةً إلى حجم الصورة الأصلي) لإطار الصورة. القيمة 1.0 تمثل 100٪. قراءة/كتابة Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | تُرجع أو تُعيّن مقياس العرض (نسبةً إلى حجم الصورة الأصلي) لإطار الصورة. القيمة 1.0 تمثل 100٪. قراءة/كتابة Single. |
| [RewindAudio](../../aspose.slides/audioframe/rewindaudio) { get; set; } | تحدد ما إذا كان يتم إرجاع الصوت تلقائيًا إلى البداية بعد التشغيل. قراءة/كتابة Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تُرجع أو تُعيّن عدد درجات دوران الشكل حول المحور z. القيمة الموجبة تدل على دوران مع عقارب الساعة؛ السالبة تدل على دوران عكس عقارب الساعة. قراءة/كتابة Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | تُرجع أقفال الشكل. قراءة فقط [`IPictureFrameLock`](../ipictureframelock). (خاصيتان) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | تُرجع كائن نمط الشكل. قراءة فقط [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | تُرجع أو تُعيّن نوع AutoShape لإطار الصورة. جميع العناصر المسموح بها من المجموعة [`ShapeType`](../shapetype) ما عدا جميع أنواع الخطوط: |
| [Slide](../../aspose.slides/shape/slide) { get; } | تُرجع الشريحة الأصلية للشكل. قراءة فقط [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | تُرجع كائن ThreeDFormat الذي يحتوي خصائص تأثير ثلاثية الأبعاد للشكل. ملاحظة: قد يُعيد null لبعض أنواع الأشكال التي لا تمتلك خصائص ثلاثية الأبعاد. قراءة فقط [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/audioframe/trimfromend) { get; set; } | تُحدد مدة الإزالة من نهاية الوسائط أثناء التشغيل، بالمللي ثانية. قراءة/كتابة Single. |
| [TrimFromStart](../../aspose.slides/audioframe/trimfromstart) { get; set; } | تُحدد مدة الإزالة من بداية الوسائط أثناء التشغيل، بالمللي ثانية. قراءة/كتابة Single. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | تُرجع معرفًا داخليًا يمتد على مستوى العرض التقديمي مخصصًا للإضافات أو الكود الآخر. بما أن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، فلا ينبغي اعتبارها مفتاحًا فريدًا دائمًا. قراءة فقط UInt32. انظر أيضًا [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/audioframe/volume) { get; set; } | تُرجع أو تُعيّن مستوى صوت الصوت. قراءة/كتابة [`AudioVolumeMode`](../audiovolumemode). |
| [VolumeValue](../../aspose.slides/audioframe/volumevalue) { get; set; } | تُرجع أو تُعيّن حجم صوت الصوت كنسبة مئوية. قراءة/كتابة Single. |
| [Width](../../aspose.slides/shape/width) { get; set; } | يحصل أو يضبط عرض الشكل بوحدات النقاط. قراءة/كتابة Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | يحصل أو يضبط إحداثي x لزاوية الشكل العليا اليسرى بوحدات النقاط. قراءة/كتابة Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | يحصل أو يضبط إحداثي y لزاوية الشكل العليا اليسرى بوحدات النقاط. قراءة/كتابة Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | تُرجع موضع الشكل في ترتيب z. Shapes[0] تُعيد الشكل الموجود في الخلف، وShapes[Shapes.Count - 1] تُعيد الشكل الموجود في المقدمة. قراءة فقط Int32. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | يضيف عنصر نائب جديد إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى العنصر المحدد. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | ينشئ ويُرجع مصفوفة من عناصر الشكل. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | يُرجع شكل عنصر نائب أساسي (شكل من تخطيط أو شريحة رئيسية يُورث منها الشكل الحالي). يُعيد null إذا لم يكن الشكل الحالي موروثًا. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | يُرجع نسخة من مسار الشكل الهندسي. الإحداثيات نسبية إلى الزاوية العُليا اليسرى للشكل. |
| [GetImage](../../aspose.slides/shape/getimage)() | يُرجع صورة مصغرة للشكل. يُستخدم النوع ShapeThumbnailBounds.Shape كقائمة حدود الصورة المصغرة افتراضيًا. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | يُرجع صورة مصغرة للشكل. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | يحصل على الحدود البصرية للشكل المحسوبة من محتواه المُعرض. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | يُحدّث هندسة الشكل من كائن [`IGeometryPath`](../igeometrypath). يجب أن تكون الإحداثيات نسبية إلى الزاوية العُليا اليسرى للشكل. يغيّر نوع الشكل ([`ShapeType`](../geometryshape/shapetype)) إلى Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | يُحدّث هندسة الشكل من مصفوفة [`IGeometryPath`](../igeometrypath). يجب أن تكون الإحداثيات نسبية إلى الزاوية العُليا اليسرى للشكل. يغيّر نوع الشكل ([`ShapeType`](../geometryshape/shapetype)) إلى Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | يحفظ محتوى الشكل كملف SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | يحفظ محتوى الشكل كملف SVG. |

### أمثلة

توضح الأمثلة التالية كيفية تغيير خيارات تشغيل الصوت.

```csharp
[C#]
using (Presentation pres = new Presentation("AudioFrameEmbed_out.pptx"))
{
    // يحصل على شكل AudioFrame
    AudioFrame audioFrame = (AudioFrame)pres.Slides[0].Shapes[0];
    // يحدد وضع التشغيل للتشغيل عند النقر
    audioFrame.PlayMode = AudioPlayModePreset.OnClick;
    // يحدد مستوى الصوت إلى منخفض
    audioFrame.Volume = AudioVolumeMode.Low;
    // يحدد تشغيل الصوت عبر الشرائح
    audioFrame.PlayAcrossSlides = true;
    // يعطل التكرار للصوت
    audioFrame.PlayLoopMode = false;
    // يخفي AudioFrame أثناء عرض الشرائح
    audioFrame.HideAtShowing = true;
    // يعيد تشغيل الصوت إلى البداية بعد التشغيل
    audioFrame.RewindAudio = true;
    // يحفظ ملف PowerPoint على القرص
    pres.Save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
}
```

### انظر أيضًا

* فئة [PictureFrame](../pictureframe)
* واجهة [IAudioFrame](../iaudioframe)
* نطاق [Aspose.Slides](../../aspose.slides)
* تجميعة [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->