---
title: Connector
second_title: Aspose.Sildes برای .NET مرجع API
description: یک connector را نشان می‌دهد.
type: docs
weight: 2670
url: /fa/aspose.slides/connector/
---
## کلاس Connector

یک connector را نشان می‌دهد.

```csharp
public class Connector : GeometryShape, IConnector
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | یک مجموعه از مقادیر تنظیمات shape را برمی‌گرداند. فقط-خواندنی [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | متن جایگزین مربوط به یک shape را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | عنوان متن جایگزین مربوط به یک shape را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | ویژگی مشخص می‌کند که یک shape چگونه در حالت نمایش سیاه-سفید نمایش داده شود. خواندنی/نوشتنی [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال روی shape را برمی‌گرداند. فقط-خواندنی Int32. |
| [ConnectorLock](../../aspose.slides/connector/connectorlock) { get; } | قفل‌های connector را برمی‌گرداند. فقط-خواندنی [`IConnectorLock`](../iconnectorlock). |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی shape را برمی‌گرداند. فقط-خواندنی [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat را که شامل اثرات پیکسل اعمال‌شده به یک shape است، برمی‌گرداند. نکته: ممکن است برای برخی انواع shape که ویژگی اثر ندارند، مقدار null برگرداند. فقط-خواندنی [`IEffectFormat`](../ieffectformat). |
| [EndShapeConnectedTo](../../aspose.slides/connector/endshapeconnectedto) { get; set; } | shape ای که انتهای connector به آن وصل می‌شود را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IShape`](../ishape). |
| [EndShapeConnectionSiteIndex](../../aspose.slides/connector/endshapeconnectionsiteindex) { get; set; } | اندیس نقطه اتصال برای shape انتهایی را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی UInt32. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شیء FillFormat را که شامل ویژگی‌های قالب‌بندی پر کردن برای یک shape است، برمی‌گرداند. نکته: ممکن است برای برخی انواع shape که ویژگی پر کردن ندارند، مقدار null برگرداند. فقط-خواندنی [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ویژگی‌های فریم shape را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع shape را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | تعیین می‌کند که shape مخفی باشد یا نه. خواندنی/نوشتنی Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | لینک تعریف‌شده برای کلیک ماوس را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر لینک‌ها را برمی‌گرداند. فقط-خواندنی [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | لینک تعریف‌شده برای حرکت ماوس بر روی آن را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه ‘Mark as decorative’ را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | تعیین می‌کند که shape گروه‌بندی شده باشد یا نه. فقط-خواندنی Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | تعیین می‌کند که shape از نوع TextHolder_PPT باشد یا نه. فقط-خواندنی Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat را که شامل ویژگی‌های قالب‌بندی خط برای یک shape است، برمی‌گرداند. نکته: ممکن است برای برخی انواع shape که ویژگی خط ندارند، مقدار null برگرداند. فقط-خواندنی [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک shape را برمی‌گرداند یا تنظیم می‌کند. نباید null باشد. در صورت نیاز می‌توانید از رشتهٔ خالی استفاده کنید. خواندنی/نوشتنی String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | شناسهٔ یکتای scoped به اسلاید که برای طول عمر shape ثابت می‌ماند و به PowerPoint یا کد interop اجازه می‌دهد از هر جایی در سند به shape ارجاع داده شود، را برمی‌گرداند. فقط-خواندنی UInt32. همچنین ببینید [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | اگر shape گروه‌بندی شده باشد، شیء Parent GroupShape را برمی‌گرداند. در غیر این صورت مقدار null برمی‌گرداند. فقط-خواندنی [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | placeholder مربوط به یک shape را برمی‌گرداند. اگر shape هیچ placeholder ای نداشته باشد، مقدار null برمی‌گرداند. فقط-خواندنی [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائهٔ والد اسلاید را برمی‌گرداند. فقط-خواندنی [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ویژگی‌های فریم خام shape را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجه‌هایی که shape مشخص‌شده حول محور z چرخانده می‌شود را برمی‌گرداند یا تنظیم می‌کند. مقدار مثبت نشانگر چرخش ساعتگرد؛ مقدار منفی نشانگر چرخش پاد ساعتگرد. خواندنی/نوشتنی Single. |
| [ShapeLock](../../aspose.slides/connector/shapelock) { get; } | قفل‌های shape را برمی‌گرداند. فقط-خواندنی [`IConnectorLock`](../iconnectorlock). (2 ویژگی) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | شیء سبک shape را برمی‌گرداند. فقط-خواندنی [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/connector/shapetype) { get; set; } | نوع AutoShape را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد shape را برمی‌گرداند. فقط-خواندنی [`IBaseSlide`](../ibaseslide). |
| [StartShapeConnectedTo](../../aspose.slides/connector/startshapeconnectedto) { get; set; } | shape ای که ابتدای connector به آن وصل می‌شود را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IShape`](../ishape). |
| [StartShapeConnectionSiteIndex](../../aspose.slides/connector/startshapeconnectionsiteindex) { get; set; } | اندیس نقطه اتصال برای shape شروع را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی UInt32. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat را که شامل ویژگی‌های اثر 3D برای یک shape است، برمی‌گرداند. نکته: ممکن است برای برخی انواع shape که ویژگی 3D ندارند، مقدار null برگرداند. فقط-خواندنی [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | شناسهٔ داخلی scoped به ارائه، که برای استفاده توسط افزونه‌ها یا کدهای دیگر منظور شده است، را برمی‌گرداند. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویس دوباره اختصاص داده شود، نباید به عنوان کلید یکتای پایدار در نظر گرفته شود. فقط-خواندنی UInt32. همچنین ببینید [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض shape را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشهٔ بالای چپ shape را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشهٔ بالای چپ shape را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک shape در ترتیب z را برمی‌گرداند. Shapes[0] shape در پشت ترتیب z را برمی‌گرداند و Shapes[Shapes.Count - 1] shape در جلو ترتیب z را برمی‌گرداند. فقط-خواندنی Int32. |

## متدها

| نام | توضیح |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | اگر placeholder وجود نداشته باشد، یک placeholder جدید اضافه می‌کند و ویژگی‌های placeholder را به مقدار مشخص‌شده تنظیم می‌کند. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | آرایه‌ای از عناصر shape را ایجاد و برمی‌گرداند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک shape placeholder پایه را برمی‌گرداند (shape ای از طرح‌بندی و/یا اسلاید اصلی که shape فعلی از آن به ارث برده شده است). اگر shape فعلی ارث‌بری نداشته باشد، مقدار null برمی‌گردد. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | کپی مسیر shape هندسی را برمی‌گرداند. مختصات نسبت به گوشهٔ بالای چپ shape است. |
| [GetImage](../../aspose.slides/shape/getimage)() | تصویر کوچک (thumbnail) shape را برمی‌گرداند. نوع bounds تصویر کوچک ShapeThumbnailBounds.Shape به صورت پیش‌فرض استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تصویر کوچک shape را برمی‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | حدود بصری shape را که از محتوای رندرش محاسبه شده است، برمی‌گیرد. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | تعریف می‌کند که این shape یک placeholder نیست. |
| [Reroute](../../aspose.slides/connector/reroute)() | connector را بازنشر می‌دهد تا کوتاه‌ترین مسیر ممکن بین shape‌هایی که به هم وصل می‌کند را بگیرد. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | هندسه shape را از شیء [`IGeometryPath`](../igeometrypath) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشهٔ بالای چپ shape باشد. نوع shape ([`ShapeType`](../geometryshape/shapetype)) را به Custom تغییر می‌دهد. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | هندسه shape را از آرایه‌ای از [`IGeometryPath`](../igeometrypath) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشهٔ بالای چپ shape باشد. نوع shape ([`ShapeType`](../geometryshape/shapetype)) را به Custom تغییر می‌دهد. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتویات Shape را به‌عنوان فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | محتویات Shape را به‌عنوان فایل SVG ذخیره می‌کند. |

### موارد مرتبط

* کلاس [GeometryShape](../geometryshape)
* رابط [IConnector](../iconnector)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مجتمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->