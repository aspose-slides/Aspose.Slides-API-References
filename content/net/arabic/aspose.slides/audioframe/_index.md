---
title: AudioFrame
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: يمثل مقطعًا صوتيًا على شريحة.
type: docs
weight: 870
url: /ar/aspose.slides/audioframe/
---
## AudioFrame فئة

يمثل مقطع صوتي على الشريحة.

```csharp
public class AudioFrame : PictureFrame, IAudioFrame
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | إرجاع مجموعة قيم تعديل الشكل. للقراءة فقط [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | إرجاع أو تعيين النص البديل المرتبط بالشكل. قابل للقراءة والكتابة String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | إرجاع أو تعيين عنوان النص البديل المرتبط بالشكل. قابل للقراءة والكتابة String. |
| [AudioCdEndTrack](../../aspose.slides/audioframe/audiocdendtrack) { get; set; } | إرجاع أو تعيين فهرس المسار الأخير. قابل للقراءة والكتابة Int32. |
| [AudioCdEndTrackTime](../../aspose.slides/audioframe/audiocdendtracktime) { get; set; } | إرجاع أو تعيين زمن المسار الأخير. قابل للقراءة والكتابة Int32. |
| [AudioCdStartTrack](../../aspose.slides/audioframe/audiocdstarttrack) { get; set; } | إرجاع أو تعيين فهرس مسار البداية. قابل للقراءة والكتابة Int32. |
| [AudioCdStartTrackTime](../../aspose.slides/audioframe/audiocdstarttracktime) { get; set; } | إرجاع أو تعيين زمن مسار البداية. قابل للقراءة والكتابة Int32. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | تحدد الخاصية كيفية عرض الشكل في وضع العرض بالأبيض والأسود. قابل للقراءة والكتابة [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/audioframe/captiontracks) { get; } | يجلب مجموعة الترجمات المغلقة المرتبطة بإطار الصوت. هذه الخاصية للقراءة فقط وتُرجع [`ICaptionsCollection`](../icaptionscollection) يحتوي على جميع مسارات الترجمات. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | إرجاع عدد مواقع الاتصال على الشكل. للقراءة فقط Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | إرجاع بيانات الشكل المخصصة. للقراءة فقط [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | إرجاع كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على الشكل. ملاحظة: قد يُرجع null لبعض أنواع الأشكال التي لا تمتلك خصائص تأثير. للقراءة فقط [`IEffectFormat`](../ieffectformat). |
| [Embedded](../../aspose.slides/audioframe/embedded) { get; } | تحديد ما إذا كان الصوت مدمجًا في العرض التقديمي. للقراءة فقط Boolean. |
| [EmbeddedAudio](../../aspose.slides/audioframe/embeddedaudio) { get; set; } | إرجاع أو تعيين كائن الصوت المدمج. قابل للقراءة والكتابة [`IAudio`](../iaudio). |
| [FadeInDuration](../../aspose.slides/audioframe/fadeinduration) { get; set; } | تحدد مدة الوقت للظهور التدريجي الأولي للوسائط بالمللي ثانية. قابل للقراءة والكتابة Single. |
| [FadeOutDuration](../../aspose.slides/audioframe/fadeoutduration) { get; set; } | تحدد مدة الوقت للاندماج التدريجي النهائي للوسائط بالمللي ثانية. قابل للقراءة والكتابة Single. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | إرجاع كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة للشكل. ملاحظة: قد يُرجع null لبعض أنواع الأشكال التي لا تمتلك خصائص تعبئة. للقراءة فقط [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | إرجاع أو تعيين خصائص إطار الشكل. قابل للقراءة والكتابة [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | يُجلب أو يُعيّن ارتفاع الشكل، مقاسًا بالنقاط. قابل للقراءة والكتابة Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | تحديد ما إذا كان الشكل مخفيًا. قابل للقراءة والكتابة Boolean. |
| [HideAtShowing](../../aspose.slides/audioframe/hideatshowing) { get; set; } | تحديد ما إذا كان AudioFrame مخفيًا. قابل للقراءة والكتابة Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | إرجاع أو تعيين الرابط التشعبي المعرفة للنقر بالماوس. قابل للقراءة والكتابة [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | إرجاع مدير الروابط التشعبية. للقراءة فقط [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | إرجاع أو تعيين الرابط التشعبي المعرفة للتقويم بالماوس. قابل للقراءة والكتابة [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | تحديد ما إذا كان PictureFrame كائن Cameo أم لا. للقراءة فقط Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | يُجلب أو يُعيّن خيار 'وضع علامة كديكور'. قابل للقراءة والكتابة Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | تحديد ما إذا كان الشكل مجمعًا. للقراءة فقط Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | تحديد ما إذا كان الشكل TextHolder_PPT. للقراءة فقط Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | إرجاع كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل. ملاحظة: قد يُرجع null لبعض أنواع الأشكال التي لا تمتلك خصائص خط. للقراءة فقط [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/audioframe/linkpathlong) { get; set; } | إرجاع أو تعيين اسم ملف صوت مرتبط بـ AudioFrame. قابل للقراءة والكتابة String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | إرجاع أو تعيين اسم الشكل. يجب ألا يكون null. استخدم قيمة سلسلة فارغة إذا لزم الأمر. قابل للقراءة والكتابة String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | إرجاع معرف فريد محصور بالعرض يُبقى ثابتًا طوال عمر الشكل ويسمح لــ PowerPoint أو شفرة interop بالإشارة إلى الشكل من أي مكان في المستند. للقراءة فقط UInt32. أنظر أيضًا [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | إرجاع كائن GroupShape الأب إذا كان الشكل مجمعًا. وإلا يُرجع null. للقراءة فقط [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | إرجاع كائن PictureFillFormat لإطار الصورة. للقراءة فقط [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | إرجاع أقفال الشكل. للقراءة فقط [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | إرجاع العنصر النائب للشكل. يُرجع null إذا لم يكن لل shape عنصر نائب. للقراءة فقط [`IPlaceholder`](../iplaceholder). |
| [PlayAcrossSlides](../../aspose.slides/audioframe/playacrossslides) { get; set; } | تحديد ما إذا كان الصوت يُشغل عبر الشرائح. قابل للقراءة والكتابة Boolean. |
| [PlayLoopMode](../../aspose.slides/audioframe/playloopmode) { get; set; } | تحديد ما إذا كان الصوت متكررًا. قابل للقراءة والكتابة Boolean. |
| [PlayMode](../../aspose.slides/audioframe/playmode) { get; set; } | إرجاع أو تعيين وضع تشغيل الصوت. قابل للقراءة والكتابة [`AudioPlayModePreset`](../audioplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | إرجاع العرض التقديمي الأب للشريحة. للقراءة فقط [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | إرجاع أو تعيين خصائص إطار الشكل الخام. قابل للقراءة والكتابة [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | إرجاع أو تعيين مقياس الارتفاع (نسبةً إلى حجم الصورة الأصلي) لإطار الصورة. القيمة 1.0 تعادل 100٪. قابل للقراءة والكتابة Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | إرجاع أو تعيين مقياس العرض (نسبةً إلى حجم الصورة الأصلي) لإطار الصورة. القيمة 1.0 تعادل 100٪. قابل للقراءة والكتابة Single. |
| [RewindAudio](../../aspose.slides/audioframe/rewindaudio) { get; set; } | تحديد ما إذا كان الصوت يُعيد تلقائيًا إلى البداية بعد التشغيل. قابل للقراءة والكتابة Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | إرجاع أو تعيين عدد الدرجات التي يدور بها الشكل المحدد حول المحور z. القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ القيمة السالبة تشير إلى دوران عكس اتجاه العقارب. قابل للقراءة والكتابة Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | إرجاع أقفال الشكل. للقراءة فقط [`IPictureFrameLock`](../ipictureframelock). (2 properties) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | إرجاع كائن نمط الشكل. للقراءة فقط [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | إرجاع أو تعيين نوع AutoShape لإطار الصورة. جميع العناصر المسموح بها في المجموعة [`ShapeType`](../shapetype)، ما عدا جميع أنواع الخطوط: |
| [Slide](../../aspose.slides/shape/slide) { get; } | إرجاع الشريحة الأب للشكل. للقراءة فقط [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | إرجاع كائن ThreeDFormat الذي يحتوي على خصائص تأثير 3D للشكل. ملاحظة: قد يُرجع null لبعض أنواع الأشكال التي لا تمتلك خصائص 3D. للقراءة فقط [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/audioframe/trimfromend) { get; set; } | تحدد مدة الوقت لإزالة الجزء الأخير من الوسائط أثناء التشغيل، بالمللي ثانية. قابل للقراءة والكتابة Single. |
| [TrimFromStart](../../aspose.slides/audioframe/trimfromstart) { get; set; } | تحدد مدة الوقت لإزالة الجزء الأول من الوسائط أثناء التشغيل، بالمللي ثانية. قابل للقراءة والكتابة Single. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | إرجاع معرف داخلي محصور بالعرض مخصص للاستخدام من قبل الإضافات أو شفرة أخرى. بما أن هذه القيمة يمكن أن يعيد المستخدم أو البرنامج تعيينها، لا يجب التعامل معها كمفتاح فريد دائم. للقراءة فقط UInt32. أنظر أيضًا [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/audioframe/volume) { get; set; } | إرجاع أو تعيين مستوى صوت الصوت. قابل للقراءة والكتابة [`AudioVolumeMode`](../audiovolumemode). |
| [VolumeValue](../../aspose.slides/audioframe/volumevalue) { get; set; } | إرجاع أو تعيين مستوى صوت الصوت بالنسبة المئوية. قابل للقراءة والكتابة Single. |
| [Width](../../aspose.slides/shape/width) { get; set; } | يُجلب أو يُعيّن عرض الشكل، مقاسًا بالنقاط. قابل للقراءة والكتابة Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | يُجلب أو يُعيّن الإحداثي السيني لزاوية الشكل العلوية اليسرى، مقاسًا بالنقاط. قابل للقراءة والكتابة Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | يُجلب أو يُعيّن الإحداثي الصادي لزاوية الشكل العلوية اليسرى، مقاسًا بالنقاط. قابل للقراءة والكتابة Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | إرجاع موضع الشكل في ترتيب z. Shapes[0] تُرجع الشكل الخلفي في ترتيب z، وShapes[Shapes.Count - 1] تُرجع الشكل الأمامي في ترتيب z. للقراءة فقط Int32. |

## الأساليب

| الاسم | الوصف |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | يضيف عنصر نائب جديد إذا لم يكن موجودًا ويعيّن خصائص العنصر النائب إلى العنصر المحدد. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | ينشئ ويُرجع مصفوفة عناصر الشكل. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | يُرجع شكل عنصر نائب أساسي (شكل من التخطيط و/أو الشريحة الأساسية التي يُرث منها الشكل الحالي). يُرجع null إذا لم يكن الشكل الحالي مُرثًا. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | يُرجع نسخة من مسار الشكل الهندسي. الإحداثيات نسبية للزاوية العلوية اليسرى للشكل. |
| [GetImage](../../aspose.slides/shape/getimage)() | يُرجع صورة مصغرة للشكل. النوع الافتراضي هو ShapeThumbnailBounds.Shape. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | يُرجع صورة مصغرة للشكل. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | يحصل على حدود الشكل البصرية محسوبة من المحتوى المرسوم. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | يُحدّث هندسة الشكل من كائن [`IGeometryPath`](../igeometrypath). يجب أن تكون الإحداثيات نسبية للزاوية العلوية اليسرى للشكل. يغيّر نوع الشكل ([`ShapeType`](../geometryshape/shapetype)) إلى Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | يُحدّث هندسة الشكل من مصفوفة [`IGeometryPath`](../igeometrypath). يجب أن تكون الإحداثيات نسبية للزاوية العلوية اليسرى للشكل. يغيّر نوع الشكل ([`ShapeType`](../geometryshape/shapetype)) إلى Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | يحفظ محتوى Shape كملف SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | يحفظ محتوى Shape كملف SVG. |

### أمثلة

المثال التالي يوضح كيفية تغيير خيارات تشغيل الصوت.

```csharp
[C#]
using (Presentation pres = new Presentation("AudioFrameEmbed_out.pptx"))
{
    // يجلب شكل AudioFrame
    AudioFrame audioFrame = (AudioFrame)pres.Slides[0].Shapes[0];
    // يضبط وضع التشغيل لتشغيله عند النقر
    audioFrame.PlayMode = AudioPlayModePreset.OnClick;
    // يضبط مستوى الصوت إلى منخفض
    audioFrame.Volume = AudioVolumeMode.Low;
    // يضبط تشغيل الصوت عبر الشرائح
    audioFrame.PlayAcrossSlides = true;
    // يعطل التكرار للصوت
    audioFrame.PlayLoopMode = false;
    // يخفي AudioFrame أثناء عرض الشرائح
    audioFrame.HideAtShowing = true;
    // يعيد تشغيل الصوت إلى البداية بعد الانتهاء
    audioFrame.RewindAudio = true;
    // يحفظ ملف PowerPoint على القرص
    pres.Save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
}
```

### أنظر أيضًا

* فئة [PictureFrame](../pictureframe)
* واجهة [IAudioFrame](../iaudioframe)
* مساحة الاسم [Aspose.Slides](../../aspose.slides)
* تجميعة [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->