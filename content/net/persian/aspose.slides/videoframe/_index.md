---
title: VideoFrame
second_title: Aspose.Sildes برای .NET مرجع API
description: یک کلیپ ویدئویی را بر روی یک اسلاید نمایش می‌دهد.
type: docs
weight: 11740
url: /fa/aspose.slides/videoframe/
---
## VideoFrame کلاس

یک کلیپ ویدئویی را بر روی یک اسلاید نمایش می‌دهد.

```csharp
public class VideoFrame : PictureFrame, IVideoFrame
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | مجموعه‌ای از مقادیر تنظیمات شکل را برمی‌گرداند. فقط خواندنی [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. قابلیت خواندن و نوشتن رشته. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. قابلیت خواندن و نوشتن رشته. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه-سفید رندر می‌شود. قابلیت خواندن و نوشتن [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/videoframe/captiontracks) { get; } | مجموعه زیرنویس‌های بسته مرتبط با چهارچوب ویدئو را دریافت می‌کند. این ویژگی فقط خواندنی است و یک [`ICaptionsCollection`](../icaptionscollection) حاوی تمام مسیرهای زیرنویس را برمی‌گرداند. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال روی شکل را برمی‌گرداند. فقط خواندنی Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی شکل را برمی‌گرداند. فقط خواندنی [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat که حاوی اثرات پیکسل اعمال‌شده به یک شکل است را برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی‌های اثر ندارند ممکن است مقدار null برگردانده شود. فقط خواندنی [`IEffectFormat`](../ieffectformat). |
| [EmbeddedVideo](../../aspose.slides/videoframe/embeddedvideo) { get; set; } | شیء ویدئوی جاسازی‌شده را برمی‌گرداند یا تنظیم می‌کند. قابلیت خواندن و نوشتن [`IVideo`](../ivideo). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شیء FillFormat که حاوی خصوصیات قالب‌بندی پر کردن برای یک شکل است را برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی‌های پر کردن ندارند ممکن است مقدار null برگردانده شود. فقط خواندنی [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ویژگی‌های چارچوب شکل را برمی‌گرداند یا تنظیم می‌کند. قابلیت خواندن و نوشتن [`IShapeFrame`](../ishapeframe). |
| [FullScreenMode](../../aspose.slides/videoframe/fullscreenmode) { get; set; } | مشخص می‌کند آیا یک ویدئو به حالت تمام‌صفحه نمایش داده شود یا نه. قابلیت خواندن و نوشتن Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع شکل را که به پوینت اندازه‌گیری می‌شود دریافت یا تنظیم می‌کند. قابلیت خواندن و نوشتن Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | مشخص می‌کند آیا شکل پنهان باشد یا نه. قابلیت خواندن و نوشتن Boolean. |
| [HideAtShowing](../../aspose.slides/videoframe/hideatshowing) { get; set; } | مشخص می‌کند آیا VideoFrame پنهان باشد یا نه. قابلیت خواندن و نوشتن Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | پیوندهای تعریف‌شده برای کلیک ماوس را برمی‌گرداند یا تنظیم می‌کند. قابلیت خواندن و نوشتن [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر پیوندهای فرامدی را برمی‌گرداند. فقط خواندنی [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | پیوندهای تعریف‌شده برای عبور ماوس را برمی‌گرداند یا تنظیم می‌کند. قابلیت خواندن و نوشتن [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | مشخص می‌کند آیا PictureFrame شیء Cameo است یا خیر. فقط خواندنی Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه «علامت‌گذاری به‌عنوان تزئینی» را دریافت یا تنظیم می‌کند. قابلیت خواندن و نوشتن Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | مشخص می‌کند آیا شکل گروه‌بندی شده است یا نه. فقط خواندنی Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | مشخص می‌کند آیا شکل TextHolder_PPT است یا نه. فقط خواندنی Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat که حاوی خصوصیات قالب‌بندی خط برای یک شکل است را برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی‌های خط ندارند ممکن است مقدار null برگردانده شود. فقط خواندنی [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/videoframe/linkpathlong) { get; set; } | نام فایل ویدئویی که به VideoFrame لینک شده است را برمی‌گرداند یا تنظیم می‌کند. قابلیت خواندن و نوشتن رشته. |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند. باید غیرnull باشد. در صورت نیاز می‌توانید از رشته خالی استفاده کنید. قابلیت خواندن و نوشتن رشته. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | یک شناسه یکتا در سطح اسلاید را برمی‌گرداند که برای طول عمر شکل ثابت می‌ماند و اجازه می‌دهد PowerPoint یا کدهای interop به‌صورت قابل اعتماد به شکل از هر جایی در سند ارجاع دهند. فقط خواندنی UInt32. همچنین رجوع کنید به [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | اگر شکل گروه‌بندی شده باشد شیء GroupShape والد را برمی‌گرداند. در غیر این صورت null برمی‌گرداند. فقط خواندنی [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | شیء PictureFillFormat برای یک چارچوب تصویر را برمی‌گرداند. فقط خواندنی [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط خواندنی [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | محل نگهداری (placeholder) یک شکل را برمی‌گرداند. اگر شکل هیچ placeholder نداشته باشد null برمی‌گرداند. فقط خواندنی [`IPlaceholder`](../iplaceholder). |
| [PlayLoopMode](../../aspose.slides/videoframe/playloopmode) { get; set; } | مشخص می‌کند آیا ویدئو به‌صورت حلقه‌ای پخش شود یا نه. قابلیت خواندن و نوشتن Boolean. |
| [PlayMode](../../aspose.slides/videoframe/playmode) { get; set; } | حالت پخش ویدئو را برمی‌گرداند یا تنظیم می‌کند. قابلیت خواندن و نوشتن [`VideoPlayModePreset`](../videoplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائه اصلی (presentation) والد یک اسلاید را برمی‌گرداند. فقط خواندنی [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ویژگی‌های خام چارچوب شکل را برمی‌گرداند یا تنظیم می‌کند. قابلیت خواندن و نوشتن [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | مقیاس ارتفاع (نسبت به اندازه تصویر اصلی) چارچوب تصویر را برمی‌گرداند یا تنظیم می‌کند. مقدار 1.0 معادل 100٪ است. قابلیت خواندن و نوشتن Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | مقیاس عرض (نسبت به اندازه تصویر اصلی) چارچوب تصویر را برمی‌گرداند یا تنظیم می‌کند. مقدار 1.0 معادل 100٪ است. قابلیت خواندن و نوشتن Single. |
| [RewindVideo](../../aspose.slides/videoframe/rewindvideo) { get; set; } | مشخص می‌کند آیا ویدئو به‌صورت خودکار به شروع بازگردانده شود به محض اتمام پخش. قابلیت خواندن و نوشتن Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجه‌های چرخش شکل مشخص شده حول محور z را برمی‌گرداند یا تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پادساعت‌گرد است. قابلیت خواندن و نوشتن Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط خواندنی [`IPictureFrameLock`](../ipictureframelock). (2 ویژگی) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | شیء سبک شکل را برمی‌گرداند. فقط خواندنی [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | نوع AutoShape برای یک PictureFrame را برمی‌گرداند یا تنظیم می‌کند. تمام اقلام قابل‌استفاده مجموعه [`ShapeType`](../shapetype)، به‌جز انواع خطوط، موجود است: |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد یک شکل را برمی‌گرداند. فقط خواندنی [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat که ویژگی‌های اثر 3D برای یک شکل است را برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی‌های 3D ندارند ممکن است مقدار null برگردانده شود. فقط خواندنی [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/videoframe/trimfromend) { get; set; } | قطع انتها [ms] |
| [TrimFromStart](../../aspose.slides/videoframe/trimfromstart) { get; set; } | قطع آغاز [ms] |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | یک شناسه داخلی در سطح ارائه (presentation) را برمی‌گرداند که برای استفاده توسط افزونه‌ها یا کدهای دیگر منظور شده است. از آنجا که این مقدار می‌تواند توسط کاربر یا برنامه‌نویسی دوباره اختصاص یابد، نباید به‌عنوان کلید یکتای پایدار در نظر گرفته شود. فقط خواندنی UInt32. همچنین رجوع کنید به [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/videoframe/volume) { get; set; } | حجم صدا را برمی‌گرداند یا تنظیم می‌کند. قابلیت خواندن و نوشتن [`AudioVolumeMode`](../audiovolumemode). |
| [VolumeValue](../../aspose.slides/videoframe/volumevalue) { get; set; } | حجم دقیق ویدئو را به‌صورت درصد برمی‌گرداند یا تنظیم می‌کند. مقدار به‌صورت درصد از 0 تا 100 بیان می‌شود. از این ویژگی برای خواندن یا تنظیم مقادیر حجمی که دقیق‌تر از سطوح پیش‌تعریف‌شده موجود در ویژگی [`Volume`](./volume) هستند استفاده کنید. قابلیت خواندن و نوشتن Single. |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض شکل را که به پوینت اندازه‌گیری می‌شود دریافت یا تنظیم می‌کند. قابلیت خواندن و نوشتن Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشه بالا-چپ شکل را که به پوینت اندازه‌گیری می‌شود دریافت یا تنظیم می‌کند. قابلیت خواندن و نوشتن Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشه بالا-چپ شکل را که به پوینت اندازه‌گیری می‌شود دریافت یا تنظیم می‌کند. قابلیت خواندن و نوشتن Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل پشت‌صحنهٔ ترتیب z را برمی‌گرداند و Shapes[Shapes.Count - 1] شکل جلوی ترتیب z را برمی‌گرداند. فقط خواندنی Int32. |

## متدها

| نام | توضیح |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | اگر placeholder وجود نداشته باشد یک placeholder جدید اضافه می‌کند و ویژگی‌های placeholder را به‌یک مورد مشخص تنظیم می‌کند. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | آرایه‌ای از عناصر شکل را ایجاد و برمی‌گرداند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک شکل placeholder پایه را برمی‌گرداند (شکلی از چیدمان و/یا اسلاید اصلی که شکل فعلی از آن به ارث برده شده است). اگر شکل فعلی ارث‌برده نشده باشد null برمی‌گردد. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | کپی مسیر شکل هندسی را برمی‌گرداند. مختصات نسبت به گوشهٔ بالای چپ شکل هستند. |
| [GetImage](../../aspose.slides/shape/getimage)() | بندانگشتی شکل را برمی‌گرداند. نوع محدودهٔ بندانگشتی شکل ShapeThumbnailBounds.Shape به‌طور پیش‌فرض استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | بندانگشتی شکل را برمی‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | حدود بصری شکل را که از محتوای رندرش محاسبه شده است دریافت می‌کند. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | تعریف می‌کند که این شکل یک placeholder نیست. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | هندسهٔ شکل را از شیء [`IGeometryPath`](../igeometrypath) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشهٔ بالای چپ شکل باشد. نوع شکل ([`ShapeType`](../geometryshape/shapetype)) به Custom تغییر می‌یابد. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | هندسهٔ شکل را از آرایه‌ای از [`IGeometryPath`](../igeometrypath) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشهٔ بالای چپ شکل باشد. نوع شکل ([`ShapeType`](../geometryshape/shapetype)) به Custom تغییر می‌یابد. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتویات Shape را به‌صورت فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | محتویات Shape را به‌صورت فایل SVG ذخیره می‌کند. |

### موارد مرتبط

* کلاس [PictureFrame](../pictureframe)
* رابط [IVideoFrame](../ivideoframe)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مونتاژ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->