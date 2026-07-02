---
title: VideoFrame
second_title: Aspose.Sildes برای مرجع API .NET
description: یک کلیپ ویدئویی را بر روی یک اسلاید نمایش می‌دهد.
type: docs
weight: 11720
url: /fa/aspose.slides/videoframe/
---
## کلاس VideoFrame

Represents a video clip on a slide.

```csharp
public class VideoFrame : PictureFrame, IVideoFrame
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | مجموعه‌ای از مقادیر تنظیم شکل را بر می‌گرداند. فقط‌قابل‌خواندن [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | متن جایگزین مرتبط با یک شکل را بر می‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | عنوان متن جایگزین مرتبط با یک شکل را بر می‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | ویژگی تعیین می‌کند که یک شکل چگونه در حالت نمایش سیاه-سفید رندر شود. قابل‌خواندن/قابل‌نوشتن [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/videoframe/captiontracks) { get; } | مجموعه‌ی زیرنویس‌های بسته مرتبط با فریم ویدئویی را دریافت می‌کند. این ویژگی فقط‌قابل‌خواندن است و یک [`ICaptionsCollection`](../icaptionscollection) حاوی تمام مسیرهای زیرنویس را بر می‌گرداند. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال روی شکل را بر می‌گرداند. فقط‌قابل‌خواندن Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی شکل را بر می‌گرداند. فقط‌قابل‌خواندن [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat را که شامل افکت‌های پیکسل اعمال‌شده به یک شکل است بر می‌گرداند. توجه: ممکن است برای برخی انواع شکل‌ها که ویژگی‌های افکت ندارند مقدار null را برگرداند. فقط‌قابل‌خواندن [`IEffectFormat`](../ieffectformat). |
| [EmbeddedVideo](../../aspose.slides/videoframe/embeddedvideo) { get; set; } | شیء ویدئوی جاسازی‌شده را بر می‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [`IVideo`](../ivideo). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شیء FillFormat را که شامل ویژگی‌های قالب‌بندی پرکننده برای یک شکل است بر می‌گرداند. توجه: ممکن است برای برخی انواع شکل‌ها که ویژگی‌های پرکننده ندارند مقدار null را برگرداند. فقط‌قابل‌خواندن [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ویژگی‌های فریم شکل را بر می‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [`IShapeFrame`](../ishapeframe). |
| [FullScreenMode](../../aspose.slides/videoframe/fullscreenmode) { get; set; } | تعیین می‌کند آیا ویدئو در حالت تمام‌صفحه نمایش داده شود یا نه. قابل‌خواندن/قابل‌نوشتن Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع شکل را که بر حسب پوینت اندازه‌گیری می‌شود دریافت یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | تعیین می‌کند آیا شکل مخفی باشد یا نه. قابل‌خواندن/قابل‌نوشتن Boolean. |
| [HideAtShowing](../../aspose.slides/videoframe/hideatshowing) { get; set; } | تعیین می‌کند آیا VideoFrame مخفی باشد یا نه. قابل‌خواندن/قابل‌نوشتن Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | پیوندهای ابرمتنی تعریف‌شده برای کلیک ماوس را بر می‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر پیوندهای ابرمتنی را بر می‌گرداند. فقط‌قابل‌خواندن [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | پیوندهای ابرمتنی تعریف‌شده برای عبور ماوس را بر می‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | تعیین می‌کند آیا PictureFrame شیء Cameo است یا نه. فقط‌قابل‌خواندن Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه 'علامت‌گذاری به‌عنوان تزئینی' را دریافت یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | تعیین می‌کند آیا شکل گروه‌بندی شده است یا نه. فقط‌قابل‌خواندن Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | تعیین می‌کند آیا شکل TextHolder_PPT است یا نه. فقط‌قابل‌خواندن Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat را که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است بر می‌گرداند. توجه: ممکن است برای برخی انواع شکل‌ها که ویژگی‌های خط ندارند مقدار null را برگرداند. فقط‌قابل‌خواندن [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/videoframe/linkpathlong) { get; set; } | نام فایل ویدئویی که به VideoFrame پیوست است را بر می‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک شکل را بر می‌گرداند یا تنظیم می‌کند. نباید مقدار null باشد. در صورت نیاز می‌توان از رشته خالی استفاده کرد. قابل‌خواندن/قابل‌نوشتن String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | شناسه‌ی یکتای محدوده اسلایدی که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop امکان ارجاع مطمئن به شکل از هر مکانی در سند را می‌دهد را بر می‌گرداند. فقط‌قابل‌خواندن UInt32. همچنین ببینید [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | اگر شکل گروه‌بندی شده باشد شیء GroupShape والد را بر می‌گرداند. در غیر این صورت مقدار null را برمی‌گرداند. فقط‌قابل‌خواندن [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | شیء PictureFillFormat را برای فریم تصویر بر می‌گرداند. فقط‌قابل‌خواندن [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | قفل‌های شکل را بر می‌گرداند. فقط‌قابل‌خواندن [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | متغیر جایگزین برای یک شکل را بر می‌گرداند. اگر شکل متغیر جایگزینی نداشته باشد مقدار null بر می‌گردد. فقط‌قابل‌خواندن [`IPlaceholder`](../iplaceholder). |
| [PlayLoopMode](../../aspose.slides/videoframe/playloopmode) { get; set; } | تعیین می‌کند آیا ویدئو به‌صورت حلقه‌ای پخش شود یا نه. قابل‌خواندن/قابل‌نوشتن Boolean. |
| [PlayMode](../../aspose.slides/videoframe/playmode) { get; set; } | حالت پخش ویدئو را بر می‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [`VideoPlayModePreset`](../videoplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائه (presentation) والد یک اسلاید را بر می‌گرداند. فقط‌قابل‌خواندن [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ویژگی‌های فریم شکل خام را بر می‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | مقیاس ارتفاع (نسبت به اندازهٔ اصلی تصویر) فریم تصویر را بر می‌گرداند یا تنظیم می‌کند. مقدار 1.0 معادل 100٪ است. قابل‌خواندن/قابل‌نوشتن Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | مقیاس عرض (نسبت به اندازهٔ اصلی تصویر) فریم تصویر را بر می‌گرداند یا تنظیم می‌کند. مقدار 1.0 معادل 100٪ است. قابل‌خواندن/قابل‌نوشتن Single. |
| [RewindVideo](../../aspose.slides/videoframe/rewindvideo) { get; set; } | تعیین می‌کند آیا پس از پایان پخش فیلم، ویدئو به‌صورت خودکار به ابتدا بازگردد یا نه. قابل‌خواندن/قابل‌نوشتن Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجه‌های چرخش شکل مشخص‌شده حول محور z را بر می‌گرداند یا تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعتگرد، مقدار منفی نشان‌دهنده چرخش پادساعتگرد است. قابل‌خواندن/قابل‌نوشتن Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | قفل‌های شکل را بر می‌گرداند. فقط‌قابل‌خواندن [`IPictureFrameLock`](../ipictureframelock). (2 ویژگی) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | شیء سبک شکل را بر می‌گرداند. فقط‌قابل‌خواندن [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | نوع AutoShape برای یک PictureFrame را بر می‌گرداند یا تنظیم می‌کند. تمام موارد قابل‌استفاده مجموعه [`ShapeType`](../shapetype) هستند، به‌جز تمام انواع خطوط: |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد یک شکل را بر می‌گرداند. فقط‌قابل‌خواندن [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat را که شامل ویژگی‌های افکت سه‌بعدی برای یک شکل است بر می‌گرداند. توجه: ممکن است برای برخی انواع شکل‌ها که ویژگی‌های سه‌بعدی ندارند مقدار null را برگرداند. فقط‌قابل‌خواندن [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/videoframe/trimfromend) { get; set; } | پایان برش [ms] |
| [TrimFromStart](../../aspose.slides/videoframe/trimfromstart) { get; set; } | شروع برش [ms] |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | شناسه داخلی محدوده‌ی ارائه را بر می‌گرداند که برای استفاده افزونه‌ها یا کدهای دیگر منظور شده است. از آنجا که این مقدار می‌تواند توسط کاربر یا برنامه‌نویس دوباره اختصاص داده شود، نباید به عنوان کلید یکتای دائم در نظر گرفته شود. فقط‌قابل‌خواندن UInt32. همچنین ببینید [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/videoframe/volume) { get; set; } | حجم صدا را بر می‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [`AudioVolumeMode`](../audiovolumemode). |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض شکل را که بر حسب پوینت اندازه‌گیری می‌شود دریافت یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشه بالا-چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود دریافت یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشه بالا-چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود دریافت یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک شکل در ترتیب z را بر می‌گرداند. Shapes[0] شکل در انتهای زیرپشت ترتیب z را برمی‌گرداند و Shapes[Shapes.Count - 1] شکل در جلوی ترتیب z را برمی‌گرداند. فقط‌قابل‌خواندن Int32. |

## متدها

| نام | توضیح |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | اگر جایگرینی وجود نداشته باشد، یک جایگیر جدید اضافه می‌کند و ویژگی‌های جایگرین را به مورد مشخص‌شده تنظیم می‌کند. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | آرایه‌ای از عناصر شکل ایجاد و بر می‌گرداند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک شکل جایگذار پایه (شکلی از طرح‌بندی و/یا اسلاید اصلی که شکل فعلی از آن به ارث برده شده است) را بر می‌گرداند. اگر شکل فعلی ارث‌بری نشده باشد مقدار null برگردانده می‌شود. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | نسخه‌ای از مسیر شکل هندسی را بر می‌گرداند. مختصات‌ها نسبت به گوشهٔ بالا-چپ شکل هستند. |
| [GetImage](../../aspose.slides/shape/getimage)() | تصویر کوچک (thumbnail) شکل را بر می‌گرداند. به‌‌طور پیش‌فرض نوع ShapeThumbnailBounds.Shape برای مرزبندی تصویر کوچک استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تصویر کوچک شکل را بر می‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | مرزهای بصری شکل را که از محتوای رندر شده محاسبه می‌شود دریافت می‌کند. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | تعریف می‌کند که این شکل جایگرین نیست. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | هندسهٔ شکل را از شیء [`IGeometryPath`](../igeometrypath) به‌روزرسانی می‌کند. مختصات‌ها باید نسبت به گوشهٔ بالا-چپ شکل باشند. نوع شکل ([`ShapeType`](../geometryshape/shapetype)) را به Custom تغییر می‌دهد. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | هندسهٔ شکل را از آرایه‌ای از [`IGeometryPath`](../igeometrypath) به‌روزرسانی می‌کند. مختصات‌ها باید نسبت به گوشهٔ بالا-چپ شکل باشند. نوع شکل ([`ShapeType`](../geometryshape/shapetype)) را به Custom تغییر می‌دهد. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتوای شکل را به‌عنوان فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | محتوای شکل را به‌عنوان فایل SVG ذخیره می‌کند. |

### موارد مرتبط

* کلاس [PictureFrame](../pictureframe)
* رابط [IVideoFrame](../ivideoframe)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مجمعه [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->