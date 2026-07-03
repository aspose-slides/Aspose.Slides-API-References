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

## خصوصیات

| نام | توضیح |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | مجموعه‌ای از مقادیر تنظیم شکل را برمی‌گرداند. فقط‌خواندنی [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | مقدار متنی جایگزین مرتبط با شکل را برمی‌گرداند یا تنظیم می‌کند. قابل‌نوشتن رشته. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | عنوان متن جایگزین مرتبط با شکل را برمی‌گرداند یا تنظیم می‌کند. قابل‌نوشتن رشته. |
| [AutoShapeLock](../../aspose.slides/autoshape/autoshapelock) { get; } | قفل‌های AutoShape را برمی‌گرداند. فقط‌خواندنی [`IAutoShapeLock`](../iautoshapelock). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | ویژگی مشخص می‌کند شکل چگونه در حالت نمایش سیاه-سفید رندر می‌شود. قابل‌نوشتن [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال روی شکل را برمی‌گرداند. فقط‌خواندنی Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی شکل را برمی‌گرداند. فقط‌خواندنی [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat که شامل افکت‌های پیکسل اعمال‌شده به شکل است را برمی‌گرداند. توجه: برای برخی انواع شکل‌ها که ویژگی افکت ندارند ممکن است null برگرداند. فقط‌خواندنی [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شیء FillFormat که شامل ویژگی‌های فرمت پر کردن برای یک شکل است را برمی‌گرداند. توجه: برای برخی انواع شکل‌ها که ویژگی پر کردن ندارند ممکن است null برگرداند. فقط‌خواندنی [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ویژگی‌های فریم شکل را برمی‌گرداند یا تنظیم می‌کند. قابل‌نوشتن [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع شکل را که به پوینت اندازه‌گیری می‌شود برمی‌گرداند یا تنظیم می‌کند. قابل‌نوشتن Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | مشخص می‌کند آیا شکل مخفی است یا خیر. قابل‌نوشتن Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | هایپرلینکی که برای کلیک ماوس تعریف شده است را برمی‌گرداند یا تنظیم می‌کند. قابل‌نوشتن [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر هایپرلینک را برمی‌گرداند. فقط‌خواندنی [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | هایپرلینکی که برای حرکت ماوس بر روی آن تعریف شده است را برمی‌گرداند یا تنظیم می‌کند. قابل‌نوشتن [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه 'علامت به‌عنوان تزئینی' را برمی‌گرداند یا تنظیم می‌کند. قابل‌نوشتن Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | مشخص می‌کند آیا شکل گروه‌بندی شده است یا خیر. فقط‌خواندنی Boolean. |
| [IsTextBox](../../aspose.slides/autoshape/istextbox) { get; } | مشخص می‌کند آیا شکل یک جعبه متن است یا خیر. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | مشخص می‌کند آیا شکل TextHolder_PPT است یا خیر. فقط‌خواندنی Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat که شامل ویژگی‌های فرمت خط برای یک شکل است را برمی‌گرداند. توجه: برای برخی انواع شکل‌ها که ویژگی خط ندارند ممکن است null برگرداند. فقط‌خواندنی [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند. نمی‌تواند خالی باشد. در صورت نیاز می‌توانید مقدار رشتهٔ خالی استفاده کنید. قابل‌نوشتن رشته. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | شناسهٔ یکتا در محدوده اسلاید که در طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای بین‌فوکسی امکان ارجاع قابل‌اعتماد به شکل را از هر نقطه‌ای در سند می‌دهد را برمی‌گرداند. فقط‌خواندنی UInt32. همچنین ببینید [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | اگر شکل گروه‌بندی شده باشد شیء GroupShape والد را برمی‌گرداند. در غیر این صورت null برمی‌گرداند. فقط‌خواندنی [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | محل‌دار (placeholder) یک شکل را برمی‌گرداند. اگر شکل هیچ placeholder نداشته باشد null برمی‌گرداند. فقط‌خواندنی [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائهٔ والد اسلاید را برمی‌گرداند. فقط‌خواندنی [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ویژگی‌های فریم خام شکل را برمی‌گرداند یا تنظیم می‌کند. قابل‌نوشتن [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجه‌های چرخش شکل مشخص حول محور z را برمی‌گرداند یا تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعتگرد؛ مقدار منفی نشان‌دهنده چرخش پادساعتگرد است. قابل‌نوشتن Single. |
| [ShapeLock](../../aspose.slides/autoshape/shapelock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط‌خواندنی [`IAutoShapeLock`](../iautoshapelock). (۲ ویژگی) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | شیء سبک شکل را برمی‌گرداند. فقط‌خواندنی [`IShapeStyle`](../ishapestyle). |
| virtual [ShapeType](../../aspose.slides/geometryshape/shapetype) { get; set; } | نوع پیش‌تنظیم هندسه را برمی‌گرداند یا تنظیم می‌کند. توجه: با تغییر مقدار، تمام مقادیر تنظیم به مقادیر پیش‌فرض خود باز می‌گردند. قابل‌نوشتن [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد یک شکل را برمی‌گرداند. فقط‌خواندنی [`IBaseSlide`](../ibaseslide). |
| [TextFrame](../../aspose.slides/autoshape/textframe) { get; } | شیء TextFrame برای AutoShape را برمی‌گرداند. فقط‌خواندنی [`ITextFrame`](../itextframe). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat که ویژگی‌های اثر ۳بعدی برای یک شکل را دارد را برمی‌گرداند. توجه: برای برخی انواع شکل‌ها که ویژگی ۳بعدی ندارند ممکن است null برگرداند. فقط‌خواندنی [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | شناسهٔ داخلی در محدوده ارائه که برای استفاده توسط افزونه‌ها یا کدهای دیگر در نظر گرفته شده است را برمی‌گرداند. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویس تغییر داده شود، نباید به عنوان کلید یکتا پایدار در نظر گرفته شود. فقط‌خواندنی UInt32. همچنین ببینید [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [UseBackgroundFill](../../aspose.slides/autoshape/usebackgroundfill) { get; set; } | مشخص می‌کند آیا این AutoShape باید با پر رنگ پس‌زمینه اسلاید پر شود به جای اینکه توسط سبک یا فرمت پر کردن مشخص شود. قابل‌نوشتن Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض شکل را که به پوینت اندازه‌گیری می‌شود برمی‌گرداند یا تنظیم می‌کند. قابل‌نوشتن Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشهٔ بالایی چپ شکل را که به پوینت اندازه‌گیری می‌شود برمی‌گرداند یا تنظیم می‌کند. قابل‌نوشتن Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشهٔ بالایی چپ شکل را که به پوینت اندازه‌گیری می‌شود برمی‌گرداند یا تنظیم می‌کند. قابل‌نوشتن Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل در پشت‌ترین موقعیت z را برمی‌گرداند و Shapes[Shapes.Count - 1] شکل در جلوی‌ترین موقعیت را برمی‌گرداند. فقط‌خواندنی Int32. |

## متدها

| نام | توضیح |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | یک placeholder جدید اضافه می‌کند اگر موجود نباشد و خصوصیات placeholder را به مورد مشخص شده تنظیم می‌کند. |
| [AddTextFrame](../../aspose.slides/autoshape/addtextframe)(string) | یک TextFrame جدید به شکل اضافه می‌کند. اگر شکل از قبل TextFrame داشته باشد، متن آن را به سادگی تغییر می‌دهد. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | آرایه‌ای از عناصر شکل را ایجاد و برمی‌گرداند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک شکل placeholder پایه را برمی‌گرداند (شکلی از طرح‌بندی و/یا اسلاید اصلی که شکل جاری از آن به ارث برده شده است). اگر شکل جاری به ارث نبرده باشد، null برمی‌گرداند. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | کپی مسیر شکل هندسی را برمی‌گرداند. مختصات نسبت به گوشهٔ بالا سمت چپ شکل است. |
| [GetImage](../../aspose.slides/shape/getimage)() | تصویر بند انگشتی شکل را برمی‌گرداند. نوع ShapeThumbnailBounds.Shape به‌صورت پیش‌فرض استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تصویر بند انگشتی شکل را برمی‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | حدود بصری شکل را که از محتوای رندر شده آن محاسبه شده است، برمی‌گرداند. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | تعریف می‌کند که این شکل یک placeholder نیست. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | هندسه شکل را از شیء [`IGeometryPath`](../igeometrypath) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشهٔ بالا سمت چپ شکل باشد. نوع شکل ([`ShapeType`](../geometryshape/shapetype)) را به Custom تغییر می‌دهد. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | هندسه شکل را از آرایه‌ای از [`IGeometryPath`](../igeometrypath) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشهٔ بالا سمت چپ شکل باشد. نوع شکل ([`ShapeType`](../geometryshape/shapetype)) را به Custom تغییر می‌دهد. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتویات Shape را به‌صورت فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | محتویات Shape را به‌صورت فایل SVG ذخیره می‌کند. |

### مراجع

* کلاس [GeometryShape](../geometryshape)
* رابط [IAutoShape](../iautoshape)
* فضای نام [Aspose.Slides](../../aspose.slides)
* مجوعه [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->