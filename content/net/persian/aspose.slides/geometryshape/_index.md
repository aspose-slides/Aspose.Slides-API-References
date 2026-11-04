---
title: GeometryShape
second_title: مرجع API Aspose.Sildes برای .NET
description: کلاس والد برای تمام اشکال هندسی را نشان می‌دهد.
type: docs
weight: 4990
url: /fa/aspose.slides/geometryshape/
---
## GeometryShape کلاس

کلاس پایه برای تمام اشکال هندسی را نمایندگی می‌کند.

```csharp
public abstract class GeometryShape : Shape, IGeometryShape
```

## ویژگی‌ها

| نام | توضیحات |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | یک مجموعه از مقادیر تنظیمات شکل را برمی‌گرداند. فقط-خواندنی [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | متن جایگزین مرتبط با شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | عنوان متن جایگزین مرتبط با شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | خاصیت مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه-سفید رندر می‌شود. خواندنی/نوشتنی [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال روی شکل را برمی‌گرداند. فقط-خواندنی Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی شکل را برمی‌گرداند. فقط-خواندنی [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat را برمی‌گرداند که شامل اثرات پیکسلی اعمال‌شده بر یک شکل است. توجه: برای برخی انواع شکل‌ها که ویژگی اثر ندارند می‌تواند مقدار null برگرداند. فقط-خواندنی [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شیء FillFormat را برمی‌گرداند که شامل ویژگی‌های قالب‌بندی پر شدن برای یک شکل است. توجه: برای برخی انواع شکل‌ها که ویژگی پر شدن ندارند می‌تواند مقدار null برگرداند. فقط-خواندنی [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ویژگی‌های فریم شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع شکل را برمی‌گرداند یا تنظیم می‌کند، به نقطه اندازه‌گیری می‌شود. خواندنی/نوشتنی Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | تعیین می‌کند که آیا شکل مخفی است یا نه. خواندنی/نوشتنی Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | پیوند (hyperlink) تعریف‌شده برای کلیک ماوس را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر پیوند را برمی‌گرداند. فقط-خواندنی [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | پیوند تعریف‌شده برای حرکت ماوس بر روی آن را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه 'Mark as decorative' را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | تعیین می‌کند که آیا شکل گروه‌بندی شده است یا نه. فقط-خواندنی Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | تعیین می‌کند که آیا شکل TextHolder_PPT است یا نه. فقط-خواندنی Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat را برمی‌گرداند که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است. توجه: برای برخی انواع شکل‌ها که ویژگی خط ندارند می‌تواند مقدار null برگرداند. فقط-خواندنی [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند. نباید مقدار null باشد. در صورت نیاز از رشته خالی استفاده کنید. خواندنی/نوشتنی String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | یک شناسه یکتا مخصوص اسلاید را برمی‌گرداند که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کد interop امکان ارجاع قابل اطمینان به شکل از هر نقطه‌ای از سند را می‌دهد. فقط-خواندنی UInt32. همچنین ببینید [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | اگر شکل گروه‌بندی شده باشد شیء GroupShape والد را برمی‌گرداند. در غیر این صورت مقدار null برگردانده می‌شود. فقط-خواندنی [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | نگهدارنده (placeholder) یک شکل را برمی‌گرداند. اگر شکل هیچ نگهدارنده‌ای نداشته باشد مقدار null برمی‌گردد. فقط-خواندنی [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائه (presentation) والد یک اسلاید را برمی‌گرداند. فقط-خواندنی [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ویژگی‌های فریم خام شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجه‌ای که شکل مشخص حول محور z چرخانده می‌شود را برمی‌گرداند یا تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پادساعت‌گرد است. خواندنی/نوشتنی Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط-خواندنی [`IBaseShapeLock`](../ibaseshapelock). |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | شیء سبک (style) شکل را برمی‌گرداند. فقط-خواندنی [`IShapeStyle`](../ishapestyle). |
| virtual [ShapeType](../../aspose.slides/geometryshape/shapetype) { get; set; } | نوع پیش‌ تنظیم هندسی را برمی‌گرداند یا تنظیم می‌کند. توجه: با تغییر مقدار، تمام مقادیر تنظیمات به مقادیر پیش‌فرض خود بازنشانی می‌شوند. خواندنی/نوشتنی [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد یک شکل را برمی‌گرداند. فقط-خواندنی [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat را برمی‌گرداند که شامل ویژگی‌های اثر ۳بعدی برای یک شکل است. توجه: برای برخی انواع شکل‌ها که ویژگی ۳بعدی ندارند می‌تواند مقدار null برگرداند. فقط-خواندنی [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | یک شناسه داخلی مخصوص ارائه را برمی‌گرداند که برای استفاده توسط افزودنی‌ها یا کدهای دیگر منظور شده است. از آنجا که این مقدار می‌تواند توسط کاربر یا برنامه‌نویسی مجدداً اختصاص یابد، نباید به عنوان یک کلید یکتا دائم در نظر گرفته شود. فقط-خواندنی UInt32. همچنین ببینید [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض شکل را برمی‌گرداند یا تنظیم می‌کند، به نقطه اندازه‌گیری می‌شود. خواندنی/نوشتنی Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشهٔ بالا-چپ شکل را برمی‌گرداند یا تنظیم می‌کند، به نقطه اندازه‌گیری می‌شود. خواندنی/نوشتنی Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشهٔ بالا-چپ شکل را برمی‌گرداند یا تنظیم می‌کند، به نقطه اندازه‌گیری می‌شود. خواندنی/نوشتنی Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل در پشت ترتیب z را برمی‌گرداند و Shapes[Shapes.Count - 1] شکل در جلوی ترتیب z را برمی‌گرداند. فقط-خواندنی Int32. |

## متدها

| نام | توضیحات |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | اگر نگهدارنده‌ای وجود نداشته باشد، یک نگهدارنده جدید اضافه می‌کند و ویژگی‌های نگهدارنده را به مقدار مشخص شده تنظیم می‌کند. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | آرایه‌ای از عناصر شکل ایجاد و برمی‌گرداند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک شکل نگهدارنده پایه را برمی‌گرداند (شکلی از چیدمان و/یا اسلاید اصلی که شکل جاری از آن به ارث برده است). اگر شکل جاری ارث‌بری نکند مقدار null برگردانده می‌شود. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | کپی مسیر شکل هندسی را برمی‌گرداند. مختصات‌ها نسبت به گوشهٔ بالا-چپ شکل هستند. |
| [GetImage](../../aspose.slides/shape/getimage)() | تصویر کوچک (thumbnail) شکل را برمی‌گرداند. به‌ طور پیش‌فرض نوع محدودهٔ تصویر کوچک ShapeThumbnailBounds.Shape استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تصویر کوچک شکل را برمی‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | محدودهٔ بصری شکل را که از محتوای رندرش محاسبه می‌شود، به‌دست می‌آورد. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | تعریف می‌کند که این شکل یک نگهدارنده نیست. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | هندسه شکل را از شیء [`IGeometryPath`](../igeometrypath) به‌روزرسانی می‌کند. مختصات‌ها باید نسبت به گوشهٔ بالا-چپ شکل باشند. نوع شکل ([`ShapeType`](./shapetype)) به سفارشی تغییر می‌یابد. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | هندسه شکل را از آرایه‌ای از [`IGeometryPath`](../igeometrypath) به‌روزرسانی می‌کند. مختصات‌ها باید نسبت به گوشهٔ بالا-چپ شکل باشند. نوع شکل ([`ShapeType`](./shapetype)) به سفارشی تغییر می‌یابد. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتویات Shape را به‌عنوان فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | محتویات Shape را به‌عنوان فایل SVG ذخیره می‌کند. |

### همچنین ببینید

* کلاس [Shape](../shape)
* رابط [IGeometryShape](../igeometryshape)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->