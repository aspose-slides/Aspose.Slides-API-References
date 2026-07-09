---
title: AudioFrame
second_title: Aspose.Sildes برای .NET مرجع API
description: یک کلیپ صوتی را بر روی اسلاید نمایش می‌دهد.
type: docs
weight: 870
url: /fa/aspose.slides/audioframe/
---
## AudioFrame کلاس

یک کلیپ صوتی را در اسلایدی نشان می‌دهد.

```csharp
public class AudioFrame : PictureFrame, IAudioFrame
```

## خصوصیات

| نام | توضیح |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | مجموعه‌ای از مقادیر تنظیم شکل را برمی‌گرداند. فقط‌خواندنی [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن String. |
| [AudioCdEndTrack](../../aspose.slides/audioframe/audiocdendtrack) { get; set; } | اندیس آخرین ترک را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن Int32. |
| [AudioCdEndTrackTime](../../aspose.slides/audioframe/audiocdendtracktime) { get; set; } | زمان آخرین ترک را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن Int32. |
| [AudioCdStartTrack](../../aspose.slides/audioframe/audiocdstarttrack) { get; set; } | اندیس ترک شروع را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن Int32. |
| [AudioCdStartTrackTime](../../aspose.slides/audioframe/audiocdstarttracktime) { get; set; } | زمان ترک شروع را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن Int32. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه-سفید رندر شود. قابل‌خواندن/قابل‌نوشتن [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/audioframe/captiontracks) { get; } | مجموعه‌ای از زیرنویس‌های بسته مرتبط با فریم صوتی را دریافت می‌کند. این ویژگی فقط‌خواندنی است و یک [`ICaptionsCollection`](../icaptionscollection) حاوی تمام تراک‌های زیرنویس را بر می‌گرداند. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال روی شکل را برمی‌گرداند. فقط‌خواندنی Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی شکل را برمی‌گرداند. فقط‌خواندنی [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat را که شامل افکت‌های پیکسل اعمال‌شده به یک شکل است برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی‌های افکت ندارند می‌تواند مقدار null برگرداند. فقط‌خواندنی [`IEffectFormat`](../ieffectformat). |
| [Embedded](../../aspose.slides/audioframe/embedded) { get; } | تعیین می‌کند آیا صدا در ارائه جاسازی شده است یا خیر. فقط‌خواندنی Boolean. |
| [EmbeddedAudio](../../aspose.slides/audioframe/embeddedaudio) { get; set; } | شیء صوتی جاسازی‌شده را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [`IAudio`](../iaudio). |
| [FadeInDuration](../../aspose.slides/audioframe/fadeinduration) { get; set; } | مدت زمان محو‌شدن اولیه رسانه بر حسب میلی‌ثانیه را مشخص می‌کند. قابل‌خواندن/قابل‌نوشتن Single. |
| [FadeOutDuration](../../aspose.slides/audioframe/fadeoutduration) { get; set; } | مدت زمان محو‌شدن نهایی رسانه بر حسب میلی‌ثانیه را مشخص می‌کند. قابل‌خواندن/قابل‌نوشتن Single. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شیء FillFormat را که شامل ویژگی‌های قالب‌بندی پر کردن برای یک شکل است برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی‌های پر کردن ندارند می‌تواند مقدار null برگرداند. فقط‌خواندنی [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ویژگی‌های فریم شکل را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع شکل را که بر حسب نقطه اندازه‌گیری می‌شود، دریافت یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | تعیین می‌کند آیا شکل مخفی است یا خیر. قابل‌خواندن/قابل‌نوشتن Boolean. |
| [HideAtShowing](../../aspose.slides/audioframe/hideatshowing) { get; set; } | تعیین می‌کند آیا یک AudioFrame مخفی است یا خیر. قابل‌خواندن/قابل‌نوشتن Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | پیوندهای تعریف‌شده برای کلیک ماوس را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر پیوندها را برمی‌گرداند. فقط‌خواندنی [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | پیوند تعریف‌شده برای شناور ماوس را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | تعیین می‌کند آیا PictureFrame یک شیء Cameo است یا خیر. فقط‌خواندنی Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه 'Mark as decorative' را دریافت یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | تعیین می‌کند آیا شکل گروه‌بندی شده است یا خیر. فقط‌خواندنی Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | تعیین می‌کند آیا شکل TextHolder_PPT است یا نه. فقط‌خواندنی Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat را که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی‌های خط ندارند می‌تواند مقدار null برگرداند. فقط‌خواندنی [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/audioframe/linkpathlong) { get; set; } | نام فایل صوتی‌ای که به یک AudioFrame پیوند خورده است را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند. نباید null باشد. در صورت نیاز می‌توانید مقدار رشته خالی استفاده کنید. قابل‌خواندن/قابل‌نوشتن String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | یک شناسه یکتا مخصوص اسلاید را که در طول عمر شکل ثابت می‌ماند و به PowerPoint یا کد interop اجازه می‌دهد از هر جایی در سند به شکل ارجاع دهد، برمی‌گرداند. فقط‌خواندنی UInt32. همچنین ببینید [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | شیء GroupShape والد را اگر شکل گروه‌بندی شده باشد برمی‌گرداند. در غیر این صورت مقدار null برمی‌گرداند. فقط‌خواندنی [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | شیء PictureFillFormat برای یک فریم تصویر را برمی‌گرداند. فقط‌خواندنی [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط‌خواندنی [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | متغیر نگهدارنده (placeholder) برای یک شکل را برمی‌گرداند. اگر شکل متغیر نگهدارنده نداشته باشد مقدار null برمی‌گرداند. فقط‌خواندنی [`IPlaceholder`](../iplaceholder). |
| [PlayAcrossSlides](../../aspose.slides/audioframe/playacrossslides) { get; set; } | تعیین می‌کند آیا صدا در تمام اسلایدها پخش می‌شود یا خیر. قابل‌خواندن/قابل‌نوشتن Boolean. |
| [PlayLoopMode](../../aspose.slides/audioframe/playloopmode) { get; set; } | تعیین می‌کند آیا صدا به صورت حلقه‌ای پخش می‌شود یا خیر. قابل‌خواندن/قابل‌نوشتن Boolean. |
| [PlayMode](../../aspose.slides/audioframe/playmode) { get; set; } | حالت پخش صدا را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [`AudioPlayModePreset`](../audioplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائه‌گر والد یک اسلاید را برمی‌گرداند. فقط‌خواندنی [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ویژگی‌های فریم خام شکل را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | مقیاس ارتفاع (نسبت به اندازهٔ اصلی تصویر) فریم تصویر را برمی‌گرداند یا تنظیم می‌کند. مقدار 1.0 معادل 100٪ است. قابل‌خواندن/قابل‌نوشتن Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | مقیاس عرض (نسبت به اندازهٔ اصلی تصویر) فریم تصویر را برمی‌گرداند یا تنظیم می‌کند. مقدار 1.0 معادل 100٪ است. قابل‌خواندن/قابل‌نوشتن Single. |
| [RewindAudio](../../aspose.slides/audioframe/rewindaudio) { get; set; } | تعیین می‌کند آیا صدا پس از پخش به‌صورت خودکار به ابتدای خود باز می‌گردد یا خیر. قابل‌خواندن/قابل‌نوشتن Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجه‌های چرخش شکل مشخص‌شده حول محور z را برمی‌گرداند یا تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعتگرد، مقدار منفی نشان‌دهنده چرخش پادساعتگرد است. قابل‌خواندن/قابل‌نوشتن Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط‌خواندنی [`IPictureFrameLock`](../ipictureframelock). (2 ویژگی) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | شیء سبک شکل را برمی‌گرداند. فقط‌خواندنی [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | نوع AutoShape برای یک PictureFrame را برمی‌گرداند یا تنظیم می‌کند. تمام موارد قابل‌استفاده مجموعه [`ShapeType`](../shapetype)، به جز تمام انواع خطوط، مجاز هستند: |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد یک شکل را برمی‌گرداند. فقط‌خواندنی [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat را که شامل ویژگی‌های افکت 3D برای یک شکل است برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی‌های 3D ندارند می‌تواند مقدار null برگرداند. فقط‌خواندنی [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/audioframe/trimfromend) { get; set; } | مدت زمان حذف‌شده از انتهای رسانه هنگام پخش بر حسب میلی‌ثانیه را مشخص می‌کند. قابل‌خواندن/قابل‌نوشتن Single. |
| [TrimFromStart](../../aspose.slides/audioframe/trimfromstart) { get; set; } | مدت زمان حذف‌شده از ابتدای رسانه هنگام پخش بر حسب میلی‌ثانیه را مشخص می‌کند. قابل‌خواندن/قابل‌نوشتن Single. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | یک شناسه داخلی مخصوص ارائه را که برای استفاده توسط افزونه‌ها یا سایر کدها قصد دارد، برمی‌گرداند. از آنجا که این مقدار می‌تواند توسط کاربر یا برنامه‌نویس بازتعریف شود، نباید به عنوان کلید یکتا پایدار در نظر گرفته شود. فقط‌خواندنی UInt32. همچنین ببینید [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/audioframe/volume) { get; set; } | حجم صدا را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [`AudioVolumeMode`](../audiovolumemode). |
| [VolumeValue](../../aspose.slides/audioframe/volumevalue) { get; set; } | حجم صدا را به درصد برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن Single. |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض شکل را که بر حسب نقطه اندازه‌گیری می‌شود، دریافت یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشهٔ بالا-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود، دریافت یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشهٔ بالا-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود، دریافت یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل پشت‌دستهٔ ترتیب z را برمی‌گرداند و Shapes[Shapes.Count - 1] شکل جلوی‌دسته را برمی‌گرداند. فقط‌خواندنی Int32. |

## متدها

| نام | توضیح |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | اگر placeholder‌ای وجود نداشته باشد، یک placeholder جدید اضافه می‌کند و ویژگی‌های placeholder را به مقدار مشخص شده تنظیم می‌کند. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | آرایه‌ای از عناصر شکل را ایجاد و برمی‌گرداند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک شکل placeholder پایه (شکل از قالب یا اسلاید اصلی که شکل فعلی از آن به ارث برده شده) را برمی‌گرداند. اگر شکل فعلی به ارث نرسیده باشد مقدار null برگردانده می‌شود. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | کپی مسیر شکل هندسی را برمی‌گرداند. مختصات‌ها نسبت به گوشهٔ بالا-چپ شکل هستند. |
| [GetImage](../../aspose.slides/shape/getimage)() | تصویر کوچک (thumbnail) شکل را برمی‌گرداند. نوع ShapeThumbnailBounds.Shape برای محدوده تصویر کوچک به طور پیش‌فرض استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تصویر کوچک شکل را برمی‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | حدود بصری شکل را که از محتوای رندر شده محاسبه شده است، دریافت می‌کند. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | تعریف می‌کند که این شکل یک placeholder نیست. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | هندسه شکل را با استفاده از شیء [`IGeometryPath`](../igeometrypath) به‌روز می‌کند. مختصات‌ها باید نسبت به گوشهٔ بالا-چپ شکل باشند. نوع شکل ([`ShapeType`](../geometryshape/shapetype)) به Custom تغییر می‌کند. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | هندسه شکل را از آرایه‌ای از [`IGeometryPath`](../igeometrypath) به‌روز می‌کند. مختصات‌ها باید نسبت به گوشهٔ بالا-چپ شکل باشند. نوع شکل ([`ShapeType`](../geometryshape/shapetype)) به Custom تغییر می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتویات Shape را به‌صورت فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | محتویات Shape را به‌صورت فایل SVG با گزینه‌های ISSVGOptions ذخیره می‌کند. |

### مثال‌ها

مثال‌های زیر نشان می‌دهد چگونه گزینه‌های پخش صدا را تغییر داد.

```csharp
[C#]
using (Presentation pres = new Presentation("AudioFrameEmbed_out.pptx"))
{
    // شکل AudioFrame را دریافت می‌کند
    AudioFrame audioFrame = (AudioFrame)pres.Slides[0].Shapes[0];
    // حالت Play را برای پخش با کلیک تنظیم می‌کند
    audioFrame.PlayMode = AudioPlayModePreset.OnClick;
    // حجم را به Low تنظیم می‌کند
    audioFrame.Volume = AudioVolumeMode.Low;
    // پخش صدا را در تمام اسلایدها تنظیم می‌کند
    audioFrame.PlayAcrossSlides = true;
    // حلقه پخش صدا را غیرفعال می‌کند
    audioFrame.PlayLoopMode = false;
    // AudioFrame را در طول نمایش اسلاید مخفی می‌کند
    audioFrame.HideAtShowing = true;
    // صدا را پس از پخش به ابتدای خود باز می‌گرداند
    audioFrame.RewindAudio = true;
    // فایل PowerPoint را بر روی دیسک ذخیره می‌کند
    pres.Save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
}
```

### مراجع

* کلاس [PictureFrame](../pictureframe)
* واسط [IAudioFrame](../iaudioframe)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->