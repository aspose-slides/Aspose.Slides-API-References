---
title: AutoShape
second_title: مرجع API Aspose.Sildes برای .NET
description: یک AutoShape را نشان می‌دهد.
type: docs
weight: 900
url: /fa/aspose.slides/autoshape/
---
## کلاس AutoShape

یک AutoShape را نشان می‌دهد.

```csharp
public sealed class AutoShape : GeometryShape, IAutoShape
```

## ویژگی‌ها

| نام | توضیحات |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | یک مجموعه از مقادیر تنظیم شکل را برمی‌گرداند. فقط-خواندنی [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. قابل‌نوشتن String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. قابل‌نوشتن String. |
| [AutoShapeLock](../../aspose.slides/autoshape/autoshapelock) { get; } | قفل‌های autoshape را برمی‌گرداند. فقط-خواندنی [`IAutoShapeLock`](../iautoshapelock). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه-سفید رندر شود. قابل‌نوشتن [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال روی شکل را برمی‌گرداند. فقط-خواندنی Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی شکل را برمی‌گرداند. فقط-خواندنی [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat که شامل افکت‌های پیکسلی اعمال‌شده به یک شکل است را برمی‌گرداند. توجه: ممکن است برای برخی انواع شکل‌ها که ویژگی‌های افکت ندارند، مقدار null را برگرداند. فقط-خواندنی [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شیء FillFormat که شامل ویژگی‌های قالب‌بندی پر کردن برای یک شکل است را برمی‌گرداند. توجه: ممکن است برای برخی انواع شکل‌ها که ویژگی‌های پر کردن ندارند، مقدار null را برگرداند. فقط-خواندنی [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ویژگی‌های فریم شکل را برمی‌گرداند یا تنظیم می‌کند. قابل‌نوشتن [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. قابل‌نوشتن Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | مشخص می‌کند که آیا شکل مخفی است یا نه. قابل‌نوشتن Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | پیوند (hyperlink) تعریف‌شده برای کلیک ماوس را برمی‌گرداند یا تنظیم می‌کند. قابل‌نوشتن [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر پیوند (hyperlink) را برمی‌گرداند. فقط-خواندنی [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | پیوند تعریف‌شده برای حرکت ماوس روی آن را برمی‌گرداند یا تنظیم می‌کند. قابل‌نوشتن [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه «Mark as decorative» را برمی‌گرداند یا تنظیم می‌کند. قابل‌نوشتن Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | مشخص می‌کند که آیا شکل گروه‌بندی شده است یا نه. فقط-خواندنی Boolean. |
| [IsTextBox](../../aspose.slides/autoshape/istextbox) { get; } | مشخص می‌کند آیا شکل یک جعبه متن است یا نه. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | مشخص می‌کند که آیا شکل TextHolder_PPT است یا نه. فقط-خواندنی Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است را برمی‌گرداند. توجه: ممکن است برای برخی انواع شکل‌ها که ویژگی‌های خط ندارند، مقدار null را برگرداند. فقط-خواندنی [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند. نباید null باشد. در صورت نیاز از مقدار رشته خالی استفاده کنید. قابل‌نوشتن String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | یک شناسهٔ یکتا در محدودهٔ اسلاید که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop امکان ارجاع قابل اعتماد به شکل را از هر نقطه‌ای در سند می‌دهد را برمی‌گرداند. فقط-خواندنی UInt32. همچنین ببینید [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | اگر شکل گروه‌بندی شده باشد شیء GroupShape والد را برمی‌گرداند. در غیر این صورت null برمی‌گرداند. فقط-خواندنی [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | متغیر نگهدارنده (placeholder) یک شکل را برمی‌گرداند. اگر شکل هیچ placeholder نداشته باشد، null برمی‌گرداند. فقط-خواندنی [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائه والد اسلاید را برمی‌گرداند. فقط-خواندنی [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ویژگی‌های فریم خام شکل را برمی‌گرداند یا تنظیم می‌کند. قابل‌نوشتن [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجه‌های چرخش شکل مشخص شده حول محور z را برمی‌گرداند یا تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پاد ساعت‌گرد است. قابل‌نوشتن Single. |
| [ShapeLock](../../aspose.slides/autoshape/shapelock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط-خواندنی [`IAutoShapeLock`](../iautoshapelock). (2 ویژگی) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | شیء استایل شکل را برمی‌گرداند. فقط-خواندنی [`IShapeStyle`](../ishapestyle). |
| virtual [ShapeType](../../aspose.slides/geometryshape/shapetype) { get; set; } | نوع پیش‌تنظیم هندسه را برمی‌گرداند یا تنظیم می‌کند. توجه: با تغییر مقدار، تمام مقادیر تنظیم مجدداً به مقادیر پیش‌فرضشان باز می‌گردند. قابل‌نوشتن [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد یک شکل را برمی‌گرداند. فقط-خواندنی [`IBaseSlide`](../ibaseslide). |
| [TextFrame](../../aspose.slides/autoshape/textframe) { get; } | شیء TextFrame برای AutoShape را برمی‌گرداند. فقط-خواندنی [`ITextFrame`](../itextframe). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat که ویژگی‌های اثر 3D برای یک شکل را دارد را برمی‌گرداند. توجه: ممکن است برای برخی انواع شکل‌ها که ویژگی‌های 3D ندارند، مقدار null را برگرداند. فقط-خواندنی [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | یک شناسهٔ داخلی در محدودهٔ ارائه که برای استفاده توسط افزونه‌ها یا کدهای دیگر هدف‌گذاری شده است را برمی‌گرداند. چون این مقدار ممکن است توسط کاربر یا به‌صورت برنامه‌نویسی مجدداً اختصاص یابد، نباید به عنوان یک کلید یکتا پایدار در نظر گرفته شود. فقط-خواندنی UInt32. همچنین ببینید [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [UseBackgroundFill](../../aspose.slides/autoshape/usebackgroundfill) { get; set; } | مشخص می‌کند که آیا این autoshape باید با پر کردن پس‌زمینه اسلاید پر شود به‌جای اینکه توسط سبک یا قالب پر کردن مشخص شود. قابل‌نوشتن Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. قابل‌نوشتن Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشهٔ بالای چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. قابل‌نوشتن Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشهٔ بالای چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. قابل‌نوشتن Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل را در انتهای ترتیب z برمی‌گرداند و Shapes[Shapes.Count - 1] شکل را در جلوی ترتیب z برمی‌گرداند. فقط-خواندنی Int32. |

## متدها

| نام | توضیحات |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | اگر placeholder وجود نداشته باشد، یک placeholder جدید اضافه می‌کند و ویژگی‌های placeholder را به مورد مشخص شده تنظیم می‌کند. |
| [AddTextFrame](../../aspose.slides/autoshape/addtextframe)(string) | یک TextFrame جدید به یک شکل اضافه می‌کند. اگر شکل قبلاً TextFrame داشته باشد، به سادگی متن آن را تغییر می‌دهد. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | آرایه‌ای از عناصر شکل را ایجاد و برمی‌گرداند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک شکل placeholder پایه را برمی‌گرداند (شکلی از طرح‌بندی و/یا اسلاید اصلی که شکل فعلی از آن به ارث برده شده است). اگر شکل فعلی به ارث نرسیده باشد، null برمی‌گرداند. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | کپی مسیر شکل هندسی را برمی‌گرداند. مختصات‌ها نسبت به گوشهٔ بالای چپ شکل هستند. |
| [GetImage](../../aspose.slides/shape/getimage)() | تصویر بند انگشتی شکل را برمی‌گرداند. نوع ShapeThumbnailBounds.Shape برای مرزبندی تصویر بند انگشتی به‌صورت پیش‌فرض استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تصویر بند انگشتی شکل را برمی‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | مرزهای بصری شکل را که از محتوای رندر شده محاسبه می‌شود، برمی‌گرداند. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | تعریف می‌کند که این شکل یک placeholder نیست. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | هندسه شکل را از شیء [`IGeometryPath`](../igeometrypath) به‌روزرسانی می‌کند. مختصات‌ها باید نسبت به گوشهٔ بالای چپ شکل باشند. نوع شکل ([`ShapeType`](../geometryshape/shapetype)) را به Custom تغییر می‌دهد. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | هندسه شکل را از آرایه‌ای از [`IGeometryPath`](../igeometrypath) به‌روزرسانی می‌کند. مختصات‌ها باید نسبت به گوشهٔ بالای چپ شکل باشند. نوع شکل ([`ShapeType`](../geometryshape/shapetype)) را به Custom تغییر می‌دهد. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتوای Shape را به‌عنوان فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | محتوای Shape را به‌عنوان فایل SVG ذخیره می‌کند. |

### موارد مرتبط

* کلاس [GeometryShape](../geometryshape)
* رابط [IAutoShape](../iautoshape)
* فضای نام [Aspose.Slides](../../aspose.slides)
* مجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->