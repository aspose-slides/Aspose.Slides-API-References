---
title: GeometryShape
second_title: Aspose.Sildes برای .NET مرجع API
description: نمایانگر کلاس پایه برای تمام اشکال هندسی است.
type: docs
weight: 4970
url: /fa/aspose.slides/geometryshape/
---
## GeometryShape کلاس

نمایانگر کلاس پایه برای تمام اشکال هندسی است.

```csharp
public abstract class GeometryShape : Shape, IGeometryShape
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | مجموعه‌ای از مقادیر تنظیم shape را برمی‌گرداند. فقط خواندنی [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | متن جایگزین مرتبط با یک shape را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | عنوان متن جایگزین مرتبط با یک shape را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | این ویژگی مشخص می‌کند که یک shape چگونه در حالت نمایش سیاه-سفید رندر می‌شود. قابل خواندن/نوشتن [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال در shape را برمی‌گرداند. فقط خواندنی Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی shape را برمی‌گرداند. فقط خواندنی [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat را که شامل افکت‌های پیکسلی اعمال شده به یک shape است برمی‌گرداند. توجه: می‌تواند برای برخی از انواع shape که ویژگی‌های افکت ندارند، null برگرداند. فقط خواندنی [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شیء FillFormat را که شامل ویژگی‌های فرمت پر کردن برای یک shape است برمی‌گرداند. توجه: می‌تواند برای برخی از انواع shape که ویژگی‌های پر کردن ندارند، null برگرداند. فقط خواندنی [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ویژگی‌های چارچوب shape را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع shape را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | مشخص می‌کند که آیا shape مخفی است یا نه. قابل خواندن/نوشتن Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | پیوند (hyperlink) تعریف‌شده برای کلیک ماوس را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر hyperlink را برمی‌گرداند. فقط خواندنی [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | پیوند (hyperlink) تعریف‌شده برای حرکت ماوس بر روی آن را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه «علامت‌گذاری به عنوان تزئینی» را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | مشخص می‌کند که آیا shape گروه‌بندی شده است یا نه. فقط خواندنی Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | مشخص می‌کند که آیا shape از نوع TextHolder_PPT است یا نه. فقط خواندنی Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat را که شامل ویژگی‌های فرمت خط برای یک shape است برمی‌گرداند. توجه: می‌تواند برای برخی از انواع shape که ویژگی‌های خط ندارند، null برگرداند. فقط خواندنی [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک shape را برمی‌گرداند یا تنظیم می‌کند. باید null نباشد. در صورت نیاز مقدار رشته خالی استفاده شود. قابل خواندن/نوشتن String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | شناسهٔ یکتا در سطح اسلاید که در طول عمر shape ثابت می‌ماند و به PowerPoint یا کد interop امکان ارجاع معتبر به shape را از هرجای سند می‌دهد. فقط خواندنی UInt32. همچنین ببینید [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | شیء parent GroupShape را اگر shape گروه‌بندی شده باشد برمی‌گرداند. در غیر این صورت null برمی‌گرداند. فقط خواندنی [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | محل‌نگهدار (placeholder) برای shape را برمی‌گرداند. اگر shape محل‌نگهداری نداشته باشد، null برمی‌گرداند. فقط خواندنی [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائهٔ والد اسلاید را برمی‌گرداند. فقط خواندنی [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ویژگی‌های چارچوب خام shape را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجاتی که shape مشخص حول محور z می‌چرخد را برمی‌گرداند یا تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعتگرد؛ مقدار منفی نشان‌دهنده چرخش پادساعتگرد است. قابل خواندن/نوشتن Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | قفل‌های shape را برمی‌گرداند. فقط خواندنی [`IBaseShapeLock`](../ibaseshapelock). |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | شیء style shape را برمی‌گرداند. فقط خواندنی [`IShapeStyle`](../ishapestyle). |
| virtual [ShapeType](../../aspose.slides/geometryshape/shapetype) { get; set; } | نوع پیش‌تنظیم geometry را برمی‌گرداند یا تنظیم می‌کند. توجه: با تغییر مقدار، همهٔ مقادیر تنظیم به مقادیر پیش‌فرض خود باز می‌گردند. قابل خواندن/نوشتن [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد shape را برمی‌گرداند. فقط خواندنی [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat را که شامل ویژگی‌های افکت 3-بعدی برای یک shape است برمی‌گرداند. توجه: می‌تواند برای برخی از انواع shape که ویژگی‌های 3-بعدی ندارند، null برگرداند. فقط خواندنی [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | شناسهٔ داخلی scoped به ارائه که برای افزونه‌ها یا کدهای دیگر مورد استفاده قرار می‌گیرد. چون این مقدار می‌تواند توسط کاربر یا برنامه بازنویسی شود، نباید به عنوان کلید یکتای پایدار در نظر گرفته شود. فقط خواندنی UInt32. همچنین ببینید [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض shape را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشهٔ بالا-چپ shape را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشهٔ بالا-چپ shape را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت shape در ترتیب z را برمی‌گرداند. Shapes[0] shape را در پشت‌ترین موقعیت z-order برمی‌گرداند و Shapes[Shapes.Count - 1] shape را در جلویی‌ترین موقعیت برمی‌گرداند. فقط خواندنی Int32. |

## متدها

| نام | توضیح |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | در صورت عدم وجود، یک placeholder جدید اضافه می‌کند و ویژگی‌های placeholder را به مقدار مشخص‌شده تنظیم می‌کند. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | آرایه‌ای از عناصر shape را ایجاد و برمی‌گرداند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک shape پایهٔ placeholder (shape ای از لایه یا اسلاید اصلی که shape فعلی از آن به ارث می‌برد) را برمی‌گرداند. اگر shape فعلی ارث‌برنده نباشد، null برگردانده می‌شود. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | کپی مسیر geometry shape را برمی‌گرداند. مختصات نسبت به گوشهٔ بالا-چپ shape هستند. |
| [GetImage](../../aspose.slides/shape/getimage)() | تصویر بندانگشتی shape را برمی‌گرداند. نوع ShapeThumbnailBounds.Shape به‌صورت پیش‌فرض استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تصویر بندانگشتی shape را برمی‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | حدود بصری shape را که از محتوای رندرش محاسبه شده است، به‌دست می‌آورد. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | تعریف می‌کند که این shape یک placeholder نیست. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | هندسه shape را از شیء [`IGeometryPath`](../igeometrypath) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشهٔ بالا-چپ shape باشد. نوع shape ([`ShapeType`](./shapetype)) به Custom تغییر می‌یابد. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | هندسه shape را از آرایه‌ای از [`IGeometryPath`](../igeometrypath) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشهٔ بالا-چپ shape باشد. نوع shape ([`ShapeType`](./shapetype)) به Custom تغییر می‌یابد. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتوای Shape را به‌صورت فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | محتوای Shape را به‌صورت فایل SVG ذخیره می‌کند. |

### موارد مرتبط

* کلاس [Shape](../shape)
* رابط [IGeometryShape](../igeometryshape)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مجتمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->