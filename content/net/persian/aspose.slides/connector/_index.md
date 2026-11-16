---
title: Connector
second_title: مرجع API Aspose.Sildes برای .NET
description: نمایانگر یک connector است.
type: docs
weight: 2690
url: /fa/aspose.slides/connector/
---
## کلاس Connector

نمایانگر یک connector است.

```csharp
public class Connector : GeometryShape, IConnector
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | یک مجموعه از مقادیر تنظیم شکل را برمی‌گرداند. فقط‌خواندنی [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | متن جایگزین مرتبط با یک شکل را باز می‌گرداند یا تنظیم می‌کند. خواندنی/قابل‌نوشتن String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | عنوان متن جایگزین مرتبط با یک شکل را باز می‌گرداند یا تنظیم می‌کند. خواندنی/قابل‌نوشتن String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | ویژگی مشخص می‌کند که یک شکل در حالت نمایش سیاه-سفید چگونه رندر شود. خواندنی/قابل‌نوشتن [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد سایت‌های اتصال روی شکل را برمی‌گرداند. فقط‌خواندنی Int32. |
| [ConnectorLock](../../aspose.slides/connector/connectorlock) { get; } | قفل‌های connector را برمی‌گرداند. فقط‌خواندنی [`IConnectorLock`](../iconnectorlock). |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی شکل را برمی‌گرداند. فقط‌خواندنی [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat که شامل اثرات پیکسلی اعمال شده به یک شکل است را برمی‌گرداند. توجه: برای برخی انواع شکل‌ها که ویژگی اثر ندارند ممکن است null برگرداند. فقط‌خواندنی [`IEffectFormat`](../ieffectformat). |
| [EndShapeConnectedTo](../../aspose.slides/connector/endshapeconnectedto) { get; set; } | شکلی که انتهای connector به آن متصل می‌شود را باز می‌گرداند یا تنظیم می‌کند. خواندنی/قابل‌نوشتن [`IShape`](../ishape). |
| [EndShapeConnectionSiteIndex](../../aspose.slides/connector/endshapeconnectionsiteindex) { get; set; } | شاخص سایت اتصال برای شکل انتهایی را باز می‌گرداند یا تنظیم می‌کند. خواندنی/قابل‌نوشتن UInt32. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شیء FillFormat که شامل ویژگی‌های قالب‌بندی پر کردن برای یک شکل است را برمی‌گرداند. توجه: برای برخی انواع شکل‌ها که ویژگی پر ندارند ممکن است null برگرداند. فقط‌خواندنی [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ویژگی‌های فریم شکل را باز می‌گرداند یا تنظیم می‌کند. خواندنی/قابل‌نوشتن [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع شکل را که بر حسب نقطه اندازه‌گیری می‌شود، باز می‌گرداند یا تنظیم می‌کند. خواندنی/قابل‌نوشتن Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | مشخص می‌کند که آیا شکل مخفی است یا خیر. خواندنی/قابل‌نوشتن Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | پیوند تعریف‌شده برای کلیک ماوس را باز می‌گرداند یا تنظیم می‌کند. خواندنی/قابل‌نوشتن [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر پیوندها را باز می‌گرداند. فقط‌خواندنی [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | پیوند تعریف‌شده برای حرکت ماوس (mouse over) را باز می‌گرداند یا تنظیم می‌کند. خواندنی/قابل‌نوشتن [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه «علامت‌گذاری به‌عنوان تزئینی» را باز می‌گرداند یا تنظیم می‌کند. خواندنی/قابل‌نوشتن Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | مشخص می‌کند که آیا شکل گروه‌بندی شده است یا خیر. فقط‌خواندنی Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | مشخص می‌کند که آیا شکل TextHolder_PPT است یا خیر. فقط‌خواندنی Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است را برمی‌گرداند. توجه: برای برخی انواع شکل‌ها که ویژگی خط ندارند ممکن است null برگرداند. فقط‌خواندنی [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک شکل را باز می‌گرداند یا تنظیم می‌کند. مقدار نباید null باشد. در صورت نیاز می‌توانید رشته خالی استفاده کنید. خواندنی/قابل‌نوشتن String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | یک شناسه یکتا محدوده اسلاید را که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop امکان ارجاع قابل اطمینان به شکل را از هرجایی در سند می‌دهد، باز می‌گرداند. فقط‌خواندنی UInt32. همچنین ببینید [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | اگر شکل گروه‌بندی شده باشد، شیء والد GroupShape را باز می‌گرداند. در غیر این صورت null برمی‌گرداند. فقط‌خواندنی [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | جایگزین (placeholder) یک شکل را باز می‌گرداند. اگر شکل جایگزینی نداشته باشد، null برمی‌گرداند. فقط‌خواندنی [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائه (presentation) والد یک اسلاید را باز می‌گرداند. فقط‌خواندنی [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ویژگی‌های فریم خام شکل را باز می‌گرداند یا تنظیم می‌کند. خواندنی/قابل‌نوشتن [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجه‌های چرخش شکل مشخص‌شده حول محور z را باز می‌گرداند یا تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پادساعت‌گرد است. خواندنی/قابل‌نوشتن Single. |
| [ShapeLock](../../aspose.slides/connector/shapelock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط‌خواندنی [`IConnectorLock`](../iconnectorlock). (2 ویژگی) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | شیء style شکل را برمی‌گرداند. فقط‌خواندنی [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/connector/shapetype) { get; set; } | نوع AutoShape را باز می‌گرداند یا تنظیم می‌کند. خواندنی/قابل‌نوشتن [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد یک شکل را باز می‌گرداند. فقط‌خواندنی [`IBaseSlide`](../ibaseslide). |
| [StartShapeConnectedTo](../../aspose.slides/connector/startshapeconnectedto) { get; set; } | شکلی که ابتدای connector به آن متصل می‌شود را باز می‌گرداند یا تنظیم می‌کند. خواندنی/قابل‌نوشتن [`IShape`](../ishape). |
| [StartShapeConnectionSiteIndex](../../aspose.slides/connector/startshapeconnectionsiteindex) { get; set; } | شاخص سایت اتصال برای شکل آغازین را باز می‌گرداند یا تنظیم می‌کند. خواندنی/قابل‌نوشتن UInt32. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat که شامل ویژگی‌های اثر 3D برای یک شکل است را برمی‌گرداند. توجه: برای برخی انواع شکل‌ها که ویژگی 3D ندارند ممکن است null برگرداند. فقط‌خواندنی [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | یک شناسه داخلی محدوده ارائه که برای استفاده توسط افزونه‌ها یا کدهای دیگر در نظر گرفته شده است، باز می‌گرداند. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویس تغییر یابد، نباید به‌عنوان کلید یکتا دائم در نظر گرفته شود. فقط‌خواندنی UInt32. همچنین ببینید [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض شکل را که بر حسب نقطه اندازه‌گیری می‌شود، باز می‌گرداند یا تنظیم می‌کند. خواندنی/قابل‌نوشتن Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشه بالایی-چپ شکل را که بر حسب نقطه است، باز می‌گرداند یا تنظیم می‌کند. خواندنی/قابل‌نوشتن Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشه بالایی-چپ شکل را که بر حسب نقطه است، باز می‌گرداند یا تنظیم می‌کند. خواندنی/قابل‌نوشتن Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک شکل در ترتیب z را باز می‌گرداند. Shapes[0] شکل پشت ترتیب z را برمی‌گرداند و Shapes[Shapes.Count - 1] شکل جلوی ترتیب z را برمی‌گرداند. فقط‌خواندنی Int32. |

## متدها

| نام | توضیح |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | اگر placeholder وجود نداشته باشد، یک placeholder جدید اضافه می‌کند و ویژگی‌های placeholder را به مقدار مشخص تنظیم می‌کند. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | یک آرایه از عناصر شکل را ایجاد و برمی‌گرداند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک شکل placeholder پایه (شکل از طرح‌بندی و/یا اسلاید اصلی که شکل جاری از آن به ارث می‌برد) را برمی‌گرداند. اگر شکل جاری از هیچ‌کسی به ارث نبرده باشد، null برمی‌گردد. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | نسخه‌ای از مسیر شکل هندسی را برمی‌گرداند. مختصات نسبت به گوشه بالایی-چپ شکل است. |
| [GetImage](../../aspose.slides/shape/getimage)() | تصویر کوچک (thumbnail) شکل را برمی‌گرداند. به‌صورت پیش‌فرض نوع ShapeThumbnailBounds.Shape برای مرزهای تصویر کوچک استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تصویر کوچک شکل را برمی‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | مرزهای بصری شکل را که از محتوای رندر شده‌اش محاسبه می‌شود، برمی‌گرداند. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | تعریف می‌کند که این شکل placeholder نیست. |
| [Reroute](../../aspose.slides/connector/reroute)() | مسیر connector را طوری تغییر می‌دهد که کوتاه‌ترین مسیر ممکن بین شکل‌هایی که به هم متصل می‌شوند را بگیرد. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | هندسه شکل را از شیء [`IGeometryPath`](../igeometrypath) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشه بالایی-چپ شکل باشد. نوع شکل ([`ShapeType`](../geometryshape/shapetype)) را به Custom تغییر می‌دهد. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | هندسه شکل را از آرایه [`IGeometryPath`](../igeometrypath) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشه بالایی-چپ شکل باشد. نوع شکل ([`ShapeType`](../geometryshape/shapetype)) را به Custom تغییر می‌دهد. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتوای Shape را به‌صورت فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | محتوای Shape را به‌صورت فایل SVG ذخیره می‌کند. |

### موارد مرتبط

* کلاس [GeometryShape](../geometryshape)
* رابط [IConnector](../iconnector)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->