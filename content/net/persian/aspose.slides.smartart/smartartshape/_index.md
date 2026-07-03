---
title: SmartArtShape
second_title: Aspose.Sildes برای .NET مرجع API
description: نمایندهٔ شکل SmartArt
type: docs
weight: 10660
url: /fa/aspose.slides.smartart/smartartshape/
---
## SmartArtShape کلاس

Represents SmartArt shape

```csharp
public class SmartArtShape : GeometryShape, ISmartArtShape
```

## خواص

| Name | Description |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | مجموعه‌ای از مقادیر تنظیم شکل را برمی‌گرداند. فقط‌خواندنی [`IAdjustValueCollection`](../../aspose.slides/iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | متن جایگزین ارتباطی با یک شکل را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | عنوان متن جایگزین ارتباطی با یک شکل را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | خصوصیتی که تعیین می‌کند یک شکل در حالت نمایش سیاه‌وسفید چگونه نمایش داده شود. قابل‌خواندن/قابل‌نوشتن [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال روی شکل را برمی‌گرداند. فقط‌خواندنی Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی شکل را برمی‌گرداند. فقط‌خواندنی [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat که شامل اثرهای پیکسلی اعمال‌شده به یک شکل است را برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی اثر ندارند می‌تواند مقدار null برگرداند. فقط‌خواندنی [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شیء FillFormat که شامل ویژگی‌های قالب‌گذاری پرکردن برای یک شکل است را برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی پرکردن ندارند می‌تواند مقدار null برگرداند. فقط‌خواندنی [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ویژگی‌های چارچوب شکل را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | تعیین می‌کند آیا شکل مخفی است یا نه. قابل‌خواندن/قابل‌نوشتن Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | لینک‌موقتی تعریف‌شده برای کلیک ماوس را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر لینک‌موقت را برمی‌گرداند. فقط‌خواندنی [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | لینک‌موقتی تعریف‌شده برای حرکت ماوس فوق را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه 'Mark as decorative' را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | تعیین می‌کند آیا شکل گروه‌بندی شده است یا نه. فقط‌خواندنی Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | تعیین می‌کند آیا شکل TextHolder_PPT است یا نه. فقط‌خواندنی Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat که شامل ویژگی‌های قالب‌گذاری خط برای یک شکل است را برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی خط ندارند می‌تواند مقدار null برگرداند. فقط‌خواندنی [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند. نباید null باشد. در صورت نیاز می‌توانید مقدار رشته خالی استفاده کنید. قابل‌خواندن/قابل‌نوشتن String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | شناسه یکتا با دامنه اسلاید که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کد interop امکان ارجاع قابل اعتماد به شکل از هر نقطه‌ای در سند را می‌دهد را برمی‌گرداند. فقط‌خواندنی UInt32. همچنین نگاه کنید به [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | اگر شکل گروه‌بندی شده باشد شیء GroupShape والد را برمی‌گرداند. در غیر این صورت مقدار null برمی‌گردد. فقط‌خواندنی [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | متغیر نگه‌دارنده (placeholder) برای یک شکل را برمی‌گرداند. اگر شکل هیچ placeholder‌ای نداشته باشد مقدار null برمی‌گردد. فقط‌خواندنی [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائه والد اسلاید را برمی‌گرداند. فقط‌خواندنی [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ویژگی‌های خام چارچوب شکل را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجه‌هایی که شکل مشخص‌شده حول محور z چرخانده می‌شود را برمی‌گرداند یا تنظیم می‌کند. مقدار مثبت نشانگر چرخش ساعت‌گرد؛ مقدار منفی نشانگر چرخش پادساعت‌گرد است. قابل‌خواندن/قابل‌نوشتن Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط‌خواندنی [`IBaseShapeLock`](../../aspose.slides/ibaseshapelock). |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | شیء سبک شکل را برمی‌گرداند. فقط‌خواندنی [`IShapeStyle`](../../aspose.slides/ishapestyle). |
| override [ShapeType](../../aspose.slides.smartart/smartartshape/shapetype) { get; set; } | نوع پیش‌تنظیم هندسه را برمی‌گرداند یا تنظیم می‌کند. نکته: با تغییر مقدار، تمام مقادیر تنظیم به مقادیر پیش‌فرض خود بازنشانی می‌شوند. قابل‌خواندن/قابل‌نوشتن [`ShapeType`](../../aspose.slides/shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد یک شکل را برمی‌گرداند. فقط‌خواندنی [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [TextFrame](../../aspose.slides.smartart/smartartshape/textframe) { get; } | متن شکل SmartArt را برمی‌گرداند. فقط‌خواندنی [`ITextFrame`](../../aspose.slides/itextframe). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat که شامل ویژگی‌های اثر 3D برای یک شکل است را برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی 3D ندارند می‌تواند مقدار null برگرداند. فقط‌خواندنی [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | شناسه داخلی با دامنه ارائه که برای استفاده توسط افزونه‌ها یا کدهای دیگر در نظر گرفته شده است را برمی‌گرداند. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویسی بازنویسی شود، نباید به عنوان کلید یکتا دائمی محسوب شود. فقط‌خواندنی UInt32. همچنین ببینید [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشهٔ بالا-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشهٔ بالا-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل را در عقب ترتیب z برمی‌گرداند و Shapes[Shapes.Count - 1] شکل را در جلوی ترتیب z برمی‌گرداند. فقط‌خواندنی Int32. |

## متدها

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | اگر placeholder وجود نداشته باشد، یک placeholder جدید اضافه می‌کند و ویژگی‌های placeholder را به مورد مشخص تنظیم می‌کند. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | آرایه‌ای از عناصر شکل را ایجاد و برمی‌گرداند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک شکل placeholder پایه (شکل از طرح‌بندی و/یا اسلاید اصلی که شکل جاری از آن به ارث برده شده) را برمی‌گرداند. اگر شکل جاری به ارث نبرده باشد مقدار null برمی‌گردد. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | یک نسخه از مسیر شکل هندسی را برمی‌گرداند. مختصات نسبت به گوشهٔ بالا-چپ شکل هستند. |
| [GetImage](../../aspose.slides/shape/getimage)() | تصویر کوچک (thumbnail) شکل را برمی‌گرداند. نوع محدوده تصویر کوچک ShapeThumbnailBounds.Shape به‌طور پیش‌فرض استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تصویر کوچک شکل را برمی‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | حدود بصری شکل را که از محتوی رندر شده محاسبه می‌شود، برمی‌گرداند. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | تعریف می‌کند که این شکل placeholder نیست. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | هندسه شکل را از شیء [`IGeometryPath`](../../aspose.slides/igeometrypath) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشهٔ بالا-چپ شکل باشد. نوع شکل ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) را به Custom تغییر می‌دهد. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | هندسه شکل را از آرایه‌ای از [`IGeometryPath`](../../aspose.slides/igeometrypath) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشهٔ بالا-چپ شکل باشد. نوع شکل ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) را به Custom تغییر می‌دهد. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتویات شکل را به‌صورت فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | محتویات شکل را به‌صورت فایل SVG ذخیره می‌کند. |

### موارد مرتبط

* کلاس [GeometryShape](../../aspose.slides/geometryshape)
* رابط [ISmartArtShape](../ismartartshape)
* فضای نام [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* مونتاژ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->