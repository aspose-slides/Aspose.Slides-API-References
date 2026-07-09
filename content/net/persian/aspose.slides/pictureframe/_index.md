---
title: PictureFrame
second_title: مرجع API Aspose.Sildes برای .NET
description: یک فریم با تصویر داخل را نشان می‌دهد.
type: docs
weight: 9410
url: /fa/aspose.slides/pictureframe/
---
## کلاس PictureFrame

یک فریم با تصویر داخل را نشان می‌دهد.

```csharp
public class PictureFrame : GeometryShape, IPictureFrame
```

## خصوصیات

| نام | توضیح |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | مجموعه‌ای از مقادیر تنظیم شکل را برمی‌گرداند. فقط-خواندنی [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. قابل-خواندن/قابل-نوشتن String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. قابل-خواندن/قابل-نوشتن String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | خصوصیتی که مشخص می‌کند یک شکل چگونه در حالت نمایش سیاه-سفید رندر می‌شود. قابل-خواندن/قابل-نوشتن [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال روی شکل را برمی‌گرداند. فقط-خواندنی Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی شکل را برمی‌گرداند. فقط-خواندنی [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat را که شامل افکت‌های پیکسلی اعمال‌شده بر یک شکل است، برمی‌گرداند. نکته: ممکن است برای برخی انواع شکل‌ها که خاصیت افکت ندارند، مقدار null برگرداند. فقط-خواندنی [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شیء FillFormat را که شامل ویژگی‌های قالب‌بندی پر کردن برای یک شکل است، برمی‌گرداند. نکته: ممکن است برای برخی انواع شکل‌ها که خصوصیت پر کردن ندارند، مقدار null برگرداند. فقط-خواندنی [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ویژگی‌های فریم شکل را برمی‌گرداند یا تنظیم می‌کند. قابل-خواندن/قابل-نوشتن [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع شکل را که به نقطه اندازه‌گیری می‌شود، برمی‌گیرد یا تنظیم می‌کند. قابل-خواندن/قابل-نوشتن Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | مشخص می‌کند که آیا شکل مخفی است یا نه. قابل-خواندن/قابل-نوشتن Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | لینک‌های تعریف‌شده برای کلیک ماوس را برمی‌گرداند یا تنظیم می‌کند. قابل-خواندن/قابل-نوشتن [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر لینک‌ها را برمی‌گرداند. فقط-خواندنی [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | لینک تعریف‌شده برای عبور ماوس را برمی‌گرداند یا تنظیم می‌کند. قابل-خواندن/قابل-نوشتن [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | مشخص می‌کند که آیا PictureFrame یک شی Cameo است یا نه. فقط-خواندنی Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه «علامت‌گذاری به‌عنوان تزئینی» را می‌گیرد یا تنظیم می‌کند. قابل-خواندن/قابل-نوشتن Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | مشخص می‌کند که آیا شکل گروه‌بندی شده است یا نه. فقط-خواندنی Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | مشخص می‌کند که آیا شکل TextHolder_PPT است یا نه. فقط-خواندنی Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat را که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است، برمی‌گرداند. نکته: ممکن است برای برخی انواع شکل‌ها که خصوصیت خط ندارند، مقدار null برگرداند. فقط-خواندنی [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند. باید مقدار null نباشد. در صورت نیاز می‌توان از رشته خالی استفاده کرد. قابل-خواندن/قابل-نوشتن String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | یک شناسه یکتا محدود به اسلاید را برمی‌گرداند که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop اجازه می‌دهد به‌صورت قابل اطمینانی شکل را از هرجایی در سند ارجاع دهند. فقط-خواندنی UInt32. همچنین ببینید [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | در صورتی که شکل گروه‌بندی شده باشد، شیء GroupShape والد را برمی‌گرداند. در غیر این صورت مقدار null برمی‌گردد. فقط-خواندنی [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | شیء PictureFillFormat برای یک فریم تصویر را برمی‌گرداند. فقط-خواندنی [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط-خواندنی [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | متن جایگزین (placeholder) برای یک شکل را برمی‌گرداند. اگر شکل متن جایگزینی نداشته باشد مقدار null برمی‌گردد. فقط-خواندنی [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائه‌ی والد اسلاید را برمی‌گرداند. فقط-خواندنی [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ویژگی‌های فریم خام شکل را برمی‌گرداند یا تنظیم می‌کند. قابل-خواندن/قابل-نوشتن [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | مقیاس ارتفاع (نسبت به اندازه اصلی تصویر) فریم تصویر را برمی‌گرداند یا تنظیم می‌کند. مقدار 1.0 معادل 100٪ است. قابل-خواندن/قابل-نوشتن Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | مقیاس عرض (نسبت به اندازه اصلی تصویر) فریم تصویر را برمی‌گرداند یا تنظیم می‌کند. مقدار 1.0 معادل 100٪ است. قابل-خواندن/قابل-نوشتن Single. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجه‌های چرخش شکل مشخص‌شده حول محور z را برمی‌گرداند یا تنظیم می‌کند. مقدار مثبت نشانگر چرخش ساعتگرد؛ مقدار منفی نشانگر چرخش پادساعتگرد است. قابل-خواندن/قابل-نوشتن Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط-خواندنی [`IPictureFrameLock`](../ipictureframelock). (2 ویژگی) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | شیء سبک شکل را برمی‌گرداند. فقط-خواندنی [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | نوع AutoShape را برای PictureFrame برمی‌گرداند یا تنظیم می‌کند. تمام موارد قابل‌استفاده در مجموعه [`ShapeType`](../shapetype) مجاز هستند، به‌جز انواع خطوط: |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد یک شکل را برمی‌گرداند. فقط-خواندنی [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat را که شامل ویژگی‌های اثرهای سه‌بعدی برای یک شکل است، برمی‌گرداند. نکته: ممکن است برای برخی انواع شکل‌ها که خصوصیت 3D ندارند، مقدار null برگرداند. فقط-خواندنی [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | یک شناسه داخلی محدود به ارائه را برمی‌گرداند که برای استفاده توسط افزونه‌ها یا کدهای دیگر منظور شده است. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویس مجدداً اختصاص یابد، نباید به‌عنوان کلید یکتا ثابت در نظر گرفته شود. فقط-خواندنی UInt32. همچنین ببینید [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض شکل را که به نقطه اندازه‌گیری می‌شود، می‌گیرد یا تنظیم می‌کند. قابل-خواندن/قابل-نوشتن Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشه‌ی بالایی چپ شکل را که به نقطه اندازه‌گیری می‌شود، می‌گیرد یا تنظیم می‌کند. قابل-خواندن/قابل-نوشتن Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشه‌ی بالایی چپ شکل را که به نقطه اندازه‌گیری می‌شود، می‌گیرد یا تنظیم می‌کند. قابل-خواندن/قابل-نوشتن Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل در پشت ترتیب z را برمی‌گرداند و Shapes[Shapes.Count - 1] شکل در جلوتر ترتیب z را برمی‌گرداند. فقط-خواندنی Int32. |

## متدها

| نام | توضیح |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | در صورت عدم وجود، یک placeholder جدید اضافه می‌کند و ویژگی‌های placeholder را به مورد مشخص‌شده تنظیم می‌کند. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | آرایه‌ای از عناصر شکل را ایجاد و برمی‌گرداند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک شکل placeholder پایه را برمی‌گرداند (شکلی از طرح‌بندی و/یا اسلاید اصلی که شکل فعلی از آن ارث‌بری شده است). اگر شکل فعلی ارث‌بری نشده باشد مقدار null برگردانده می‌شود. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | کپی مسیر شکل هندسی را برمی‌گرداند. مختصات نسبت به گوشه‌ی بالایی چپ شکل است. |
| [GetImage](../../aspose.slides/shape/getimage)() | تصویر کوچک (thumbnail) شکل را برمی‌گرداند. به‌طور پیش‌فرض از نوع ShapeThumbnailBounds.Shape برای حدود تصویر کوچک استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تصویر کوچک شکل را برمی‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | حدود بصری شکل را که از محتوای رندر شده محاسبه می‌شود، می‌گیرد. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | تعریف می‌کند که این شکل یک placeholder نیست. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | هندسه شکل را از شیء [`IGeometryPath`](../igeometrypath) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشه‌ی بالایی چپ شکل باشد. نوع شکل ([`ShapeType`](../geometryshape/shapetype)) را به Custom تغییر می‌دهد. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | هندسه شکل را از آرایه‌ای از [`IGeometryPath`](../igeometrypath) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشه‌ی بالایی چپ شکل باشد. نوع شکل ([`ShapeType`](../geometryshape/shapetype)) را به Custom تغییر می‌دهد. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتوای Shape را به‌صورت فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | محتوای Shape را به‌صورت فایل SVG ذخیره می‌کند. |

### نمونه‌ها

نمونه‌های زیر نشان می‌دهند چگونه تصویرک Audio Frame را تغییر داد.

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
    // تصویر فریم صوتی را تنظیم می‌کند.
	// ارائه اصلاح‌شده را در دیسک ذخیره می‌کند
    presentation.Save("example_out.pptx", SaveFormat.Pptx);
}
```

### موارد مرتبط

* کلاس [GeometryShape](../geometryshape)
* رابط [IPictureFrame](../ipictureframe)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مجمعه [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->