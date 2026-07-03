---
title: PictureFrame
second_title: مرجع API Aspose.Sildes برای .NET
description: قاب دارای یک تصویر درون‌ساز را نمایش می‌دهد.
type: docs
weight: 9410
url: /fa/aspose.slides/pictureframe/
---
## کلاس PictureFrame

نمایانگر قاب دارای یک تصویر درون‌ساز است.

```csharp
public class PictureFrame : GeometryShape, IPictureFrame
```

## خصوصیات

| نام | توضیح |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | مجموعه‌ای از مقادیر تنظیم شکل را برمی‌گرداند. فقط-خواندنی [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | متن جایگزین مرتبط با شکل را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن رشته. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | عنوان متن جایگزین مرتبط با شکل را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن رشته. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | خصوصیت مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه‌وسفید رندر شود. خواندن/نوشتن [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال روی شکل را برمی‌گرداند. فقط-خواندنی Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی شکل را برمی‌گرداند. فقط-خواندنی [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat را که شامل افکت‌های پیکسلی اعمال شده به یک شکل است برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی اثر ندارند ممکن است مقدار null بازگردد. فقط-خواندنی [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شیء FillFormat را که شامل ویژگی‌های فرمت پر کردن برای یک شکل است برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی پر کردن ندارند ممکن است مقدار null بازگردد. فقط-خواندنی [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | خصوصیات قاب شکل را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع شکل را که بر حسب پوینت اندازه‌گیری می‌شود برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | مشخص می‌کند که آیا شکل مخفی است یا نه. خواندن/نوشتن Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | پیوند تعریف شده برای کلیک موس را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر پیوند را برمی‌گرداند. فقط-خواندنی [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | پیوند تعریف شده برای وقتی ماوس روی آن قرار دارد را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | تعیین می‌کند که آیا PictureFrame یک شیء Cameo است یا نه. فقط-خواندنی Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه 'Mark as decorative' را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | تعیین می‌کند که آیا شکل گروه‌بندی شده است یا نه. فقط-خواندنی Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | تعیین می‌کند که آیا شکل TextHolder_PPT است. فقط-خواندنی Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat را که شامل ویژگی‌های فرمت خط برای یک شکل است برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی خط ندارند ممکن است مقدار null بازگردد. فقط-خواندنی [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند. باید مقدار null نباشد. در صورت نیاز می‌توانید از رشته خالی استفاده کنید. خواندن/نوشتن رشته. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | شناسه یکتا با حوزه اسلاید را برمی‌گرداند که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop امکان ارجاع قابل اعتماد به شکل را از هر نقطه‌ای در سند می‌دهد. فقط-خواندنی UInt32. همچنین ببینید [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | اگر شکل گروه‌بندی شده باشد شیء GroupShape والد را برمی‌گرداند. در غیر این صورت مقدار null برمی‌گرداند. فقط-خواندنی [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | شیء PictureFillFormat برای یک قاب تصویر را برمی‌گرداند. فقط-خواندنی [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط-خواندنی [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | متغیر نگهدارنده (placeholder) برای یک شکل را برمی‌گرداند. اگر شکل متغیر نگهدارنده‌ای نداشته باشد مقدار null برمی‌گردد. فقط-خواندنی [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائه (presentation) والد اسلاید را برمی‌گرداند. فقط-خواندنی [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | خصوصیات خام قاب شکل را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | مقیاس ارتفاع (نسبت به اندازه تصویر اصلی) قاب تصویر را برمی‌گرداند یا تنظیم می‌کند. مقدار 1.0 برابر با 100٪ است. خواندن/نوشتن Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | مقیاس عرض (نسبت به اندازه تصویر اصلی) قاب تصویر را برمی‌گرداند یا تنظیم می‌کند. مقدار 1.0 برابر با 100٪ است. خواندن/نوشتن Single. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجه‌های چرخش شکل مشخص شده حول محور z را برمی‌گرداند یا تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پادساعت‌گرد است. خواندن/نوشتن Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط-خواندنی [`IPictureFrameLock`](../ipictureframelock). (2 خصوصیت) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | شیء سبک (style) شکل را برمی‌گرداند. فقط-خواندنی [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | نوع AutoShape برای یک PictureFrame را برمی‌گرداند یا تنظیم می‌کند. تمام موارد قابل‌استفاده در مجموعه [`ShapeType`](../shapetype) به جز انواع خطوط وجود دارد: |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد یک شکل را برمی‌گرداند. فقط-خواندنی [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat که شامل ویژگی‌های اثر سه‌بعدی برای یک شکل است را برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی سه‌بعدی ندارند ممکن است مقدار null بازگردد. فقط-خواندنی [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | شناسه داخلی با حوزه ارائه که برای استفاده توسط افزونه‌ها یا کدهای دیگر در نظر گرفته شده است را برمی‌گرداند. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویس تغییر یابد، نباید به عنوان کلید یکتا ثابت استفاده شود. فقط-خواندنی UInt32. همچنین ببینید [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض شکل را که بر حسب پوینت اندازه‌گیری می‌شود برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشه بالا-چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشه بالا-چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل را در عقب ترتیب z برمی‌گرداند و Shapes[Shapes.Count - 1] شکل را در جلوی ترتیب z برمی‌گرداند. فقط-خواندنی Int32. |

## متدها

| نام | توضیح |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | اگر placeholder وجود نداشته باشد یک placeholder جدید اضافه می‌کند و خصوصیات placeholder را به مورد مشخص شده تنظیم می‌کند. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | یک آرایه از عناصر شکل ایجاد و برمی‌گرداند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک شکل placeholder پایه را برمی‌گرداند (شکلی که از طرح بندی و/یا اسلاید مادر که شکل فعلی از آن به ارث برده شده است). اگر شکل فعلی ارث‌بری نشده باشد مقدار null برگردانده می‌شود. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | یک نسخه از مسیر شکل هندسی را برمی‌گرداند. مختصات نسبت به گوشهٔ بالا-چپ شکل است. |
| [GetImage](../../aspose.slides/shape/getimage)() | تصویر کوچک (thumbnail) شکل را برمی‌گرداند. به‌طور پیش‌فرض نوع ShapeThumbnailBounds.Shape برای حدود تصویر کوچک استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تصویر کوچک شکل را برمی‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | حدود بصری شکل که از محتوای رندر شده محاسبه می‌شود را برمی‌گرداند. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | تعریف می‌کند که این شکل placeholder نیست. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | هندسهٔ شکل را از شیء [`IGeometryPath`](../igeometrypath) به‌روز می‌کند. مختصات باید نسبت به گوشهٔ بالا-چپ شکل باشد. نوع شکل ([`ShapeType`](../geometryshape/shapetype)) را به Custom تغییر می‌دهد. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | هندسهٔ شکل را از آرایهٔ [`IGeometryPath`](../igeometrypath) به‌روز می‌کند. مختصات باید نسبت به گوشهٔ بالا-چپ شکل باشد. نوع شکل ([`ShapeType`](../geometryshape/shapetype)) را به Custom تغییر می‌دهد. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتویات Shape را به‌صورت فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | محتویات Shape را به‌صورت فایل SVG ذخیره می‌کند. |

### مثال‌ها

مثال‌های زیر نشان می‌دهد چگونه تصویر کوچک Audio Frame را تغییر دهید.

```csharp
[C#]
using (var presentation = new Presentation())
{
    var slide = presentation.Slides[0];
    // یک فریم صوتی را با موقعیت و اندازهٔ مشخص به اسلاید اضافه می‌کند.
    var audioStream = new FileStream("sample2.mp3", FileMode.Open, FileAccess.Read);
    var audioFrame = slide.Shapes.AddAudioFrameEmbedded(150, 100, 50, 50, audioStream);
    audioStream.Dispose();
    // یک تصویر را به منابع ارائه اضافه می‌کند.
    var imageStream = File.OpenRead("eagle.jpeg");
    var audioImage = presentation.Images.AddImage(imageStream);
    imageStream.Dispose();
    // تصویر فریم صوتی را تنظیم می‌کند.
    audioFrame.PictureFormat.Picture.Image = audioImage;
	//ارائهٔ اصلاح‌شده را روی دیسک ذخیره می‌کند
    presentation.Save("example_out.pptx", SaveFormat.Pptx);
}
```

### مراجع

* کلاس [GeometryShape](../geometryshape)
* رابط [IPictureFrame](../ipictureframe)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->