---
title: PictureFrame
second_title: مرجع API Aspose.Sildes برای .NET
description: یک چارچوب را نشان می‌دهد که داخل آن یک تصویر قرار دارد.
type: docs
weight: 9430
url: /fa/aspose.slides/pictureframe/
---
## PictureFrame کلاس

یک چارچوب را نشان می‌دهد که داخل آن یک تصویر قرار دارد.

```csharp
public class PictureFrame : GeometryShape, IPictureFrame
```

## ویژگی‌ها

| Name | Description |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | یک مجموعه از مقادیر تنظیم شکل را برمی‌گرداند. فقط خواندنی [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | مشخص می‌کند که یک شکل در حالت نمایش سیاه-سفید چگونه رندر می‌شود. قابل خواندن/نوشتن [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال روی شکل را برمی‌گرداند. فقط خواندنی Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | دادهٔ سفارشی شکل را برمی‌گرداند. فقط خواندنی [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat را برمی‌گرداند که شامل افکت‌های پیکسل اعمال‌شده به یک شکل است. توجه: ممکن است برای برخی انواع شکل‌ها که ویژگی‌های افکت ندارند مقدار null بازگرداند. فقط خواندنی [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شیء FillFormat را برمی‌گرداند که شامل ویژگی‌های قالب‌گیری پر کردن برای یک شکل است. توجه: ممکن است برای برخی انواع شکل‌ها که ویژگی‌های پر کردن ندارند مقدار null بازگرداند. فقط خواندنی [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ویژگی‌های چارچوب شکل را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع شکل را بر حسب نقطه برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | تعیین می‌کند که شکل مخفی باشد یا نه. قابل خواندن/نوشتن Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | پیوندهای ابرمتنی تعریف‌شده برای کلیک ماوس را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر پیوندهای ابرمتنی را برمی‌گرداند. فقط خواندنی [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | پیوند ابرمتنی تعریف‌شده برای حرکت ماوس بر روی آن را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | تعیین می‌کند که آیا PictureFrame شیء Cameo است یا خیر. فقط خواندنی Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه 'علامت‌گذاری به عنوان تزئینی' را می‌گیرد یا تنظیم می‌کند. قابل خواندن/نوشتن Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | تعیین می‌کند که آیا شکل گروه‌بندی شده است یا خیر. فقط خواندنی Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | تعیین می‌کند که آیا شکل TextHolder_PPT است. فقط خواندنی Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat را برمی‌گرداند که شامل ویژگی‌های قالب‌گیری خط برای یک شکل است. توجه: ممکن است برای برخی انواع شکل‌ها که ویژگی‌های خط ندارند مقدار null بازگرداند. فقط خواندنی [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند. باید تهی (null) نباشد. اگر نیاز باشد مقدار رشتهٔ خالی استفاده شود. قابل خواندن/نوشتن String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | شناسهٔ یکتای دامنه اسلاید را برمی‌گرداند که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop اجازه می‌دهد شکل را از هرجایی در سند به‌دست آورند. فقط خواندنی UInt32. همچنین ببینید [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | اگر شکل گروه‌بندی شده باشد، شیء GroupShape والد را برمی‌گرداند. در غیر این صورت مقدار null برمی‌گرداند. فقط خواندنی [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | شیء PictureFillFormat برای یک قاب تصویر را برمی‌گرداند. فقط خواندنی [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط خواندنی [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | متغیر جایگزین برای یک شکل را برمی‌گرداند. اگر شکل هیچ متغیر جایگزینی نداشته باشد مقدار null برمی‌گرداند. فقط خواندنی [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائه (Presentation) والد یک اسلاید را برمی‌گرداند. فقط خواندنی [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ویژگی‌های چارچوب شکل خام را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | مقیاس ارتفاع (نسبت به اندازهٔ تصویر اصلی) قاب تصویر را برمی‌گرداند یا تنظیم می‌کند. مقدار 1.0 معادل 100٪ است. قابل خواندن/نوشتن Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | مقیاس عرض (نسبت به اندازهٔ تصویر اصلی) قاب تصویر را برمی‌گرداند یا تنظیم می‌کند. مقدار 1.0 معادل 100٪ است. قابل خواندن/نوشتن Single. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجاتی که شکل مشخص حول محور z چرخانده می‌شود را برمی‌گرداند یا تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعتگرد؛ مقدار منفی نشان‌دهنده چرخش پادساعتگرد است. قابل خواندن/نوشتن Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط خواندنی [`IPictureFrameLock`](../ipictureframelock). (2 properties) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | شیء سبک شکل را برمی‌گرداند. فقط خواندنی [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | نوع AutoShape برای یک PictureFrame را برمی‌گرداند یا تنظیم می‌کند. همهٔ موارد مجاز مجموعه [`ShapeType`](../shapetype) هستند، به‌جز تمام انواع خطوط: |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد یک شکل را برمی‌گرداند. فقط خواندنی [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat را برمی‌گرداند که شامل ویژگی‌های اثر 3D برای یک شکل است. توجه: ممکن است برای برخی انواع شکل‌ها که ویژگی‌های 3D ندارند مقدار null بازگرداند. فقط خواندنی [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | شناسهٔ داخلی دامنهٔ ارائه که برای استفاده توسط افزودنی‌ها یا کدهای دیگر در نظر گرفته شده است. چون این مقدار می‌تواند توسط کاربر یا به‌صورت برنامه‌نویسی تغییر یابد، نباید به‌عنوان کلید یکتای دائمی در نظر گرفته شود. فقط خواندنی UInt32. همچنین ببینید [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض شکل را بر حسب نقطه برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشهٔ بالا-چپ شکل را بر حسب نقطه برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشهٔ بالا-چپ شکل را بر حسب نقطه برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل پشت‌ترین در ترتیب z را برمی‌گرداند و Shapes[Shapes.Count - 1] شکل جلوی‌ترین را برمی‌گرداند. فقط خواندنی Int32. |

## متدها

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | اگر جایگزینی وجود نداشته باشد یک جایگزین جدید اضافه می‌کند و ویژگی‌های جایگزین را به مورد مشخص تنظیم می‌کند. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | آرایه‌ای از عناصر شکل را ایجاد و برمی‌گرداند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک شکل جایگزین پایه را برمی‌گرداند (شکلی از طرح‌بندی و/یا اسلاید اصلی که شکل جاری از آن به ارث برده است). اگر شکل جاری به ارث نبرده باشد مقدار null برگردانده می‌شود. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | کپی مسیر شکل هندسی را برمی‌گرداند. مختصات‌ها نسبت به گوشهٔ بالا-چپ شکل هستند. |
| [GetImage](../../aspose.slides/shape/getimage)() | تصویر کوچک شکل را برمی‌گرداند. نوع مرزهای تصویر کوچک ShapeThumbnailBounds.Shape به‌صورت پیش‌فرض استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تصویر کوچک شکل را برمی‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | مرزهای بصری شکل را که از محتوای رندر شدهٔ آن محاسبه شده است، به‌دست می‌آورد. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | تعریف می‌کند که این شکل یک جایگزین نیست. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | هندسهٔ شکل را از شیء [`IGeometryPath`](../igeometrypath) به‌روزرسانی می‌کند. مختصات‌ها باید نسبت به گوشهٔ بالا-چپ شکل باشند. نوع شکل ([`ShapeType`](../geometryshape/shapetype)) را به Custom تغییر می‌دهد. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | هندسهٔ شکل را از آرایه‌ای از [`IGeometryPath`](../igeometrypath) به‌روزرسانی می‌کند. مختصات‌ها باید نسبت به گوشهٔ بالا-چپ شکل باشند. نوع شکل ([`ShapeType`](../geometryshape/shapetype)) را به Custom تغییر می‌دهد. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتویات Shape را به‌صورت فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISSVGOptions) | محتویات Shape را به‌صورت فایل SVG ذخیره می‌کند. |

### مثال‌ها

مثال‌های زیر نشان می‌دهند که چگونه تصویر کوچک Audio Frame را تغییر دهید.

```csharp
[C#]
using (var presentation = new Presentation())
{
    var slide = presentation.Slides[0];
    // یک فریم صوتی را به اسلاید با موقعیت و اندازه مشخص اضافه می‌کند.
    var audioStream = new FileStream("sample2.mp3", FileMode.Open, FileAccess.Read);
    var audioFrame = slide.Shapes.AddAudioFrameEmbedded(150, 100, 50, 50, audioStream);
    audioStream.Dispose();
    // یک تصویر را به منابع ارائه اضافه می‌کند.
    var imageStream = File.OpenRead("eagle.jpeg");
    var audioImage = presentation.Images.AddImage(imageStream);
    imageStream.Dispose();
    // تصویر را برای فریم صوتی تنظیم می‌کند.
    audioFrame.PictureFormat.Picture.Image = audioImage;
	//ارائهٔ اصلاح شده را روی دیسک ذخیره می‌کند
    presentation.Save("example_out.pptx", SaveFormat.Pptx);
}
```

### همچنین ببینید

* کلاس [GeometryShape](../geometryshape)
* رابط [IPictureFrame](../ipictureframe)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مجوعه [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->