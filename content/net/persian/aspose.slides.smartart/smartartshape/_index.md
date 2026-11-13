---
title: SmartArtShape
second_title: Aspose.Sildes برای .NET مرجع API
description: نمایانگر شکل SmartArt
type: docs
weight: 10680
url: /fa/aspose.slides.smartart/smartartshape/
---
## SmartArtShape کلاس

Represents SmartArt shape

```csharp
public class SmartArtShape : GeometryShape, ISmartArtShape
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | مجموعه‌ای از مقادیر تنظیم شکل را برمی‌گرداند. فقط-خواندنی [`IAdjustValueCollection`](../../aspose.slides/iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی-نوشتنی String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی-نوشتنی String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | خواص مشخص می‌کند که یک شکل در حالت نمایش سیاه-سرمیز چگونه رندر می‌شود. خواندنی-نوشتنی [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال روی شکل را برمی‌گرداند. فقط-خواندنی Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی شکل را برمی‌گرداند. فقط-خواندنی [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat را برمی‌گرداند که شامل افکت‌های پیکسلی اعمال‌شده به یک شکل است. توجه: برای برخی انواع شکل‌ها که ویژگی افکت ندارند ممکن است مقدار null برگردد. فقط-خواندنی [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شیء FillFormat را برمی‌گرداند که شامل ویژگی‌های قالب‌بندی پر کردن برای یک شکل است. توجه: برای برخی انواع شکل‌ها که ویژگی پر کردن ندارند ممکن است مقدار null برگردد. فقط-خواندنی [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ویژگی‌های چارچوب شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی-نوشتنی [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع شکل برحسب نقاط را برمی‌گیرد یا تنظیم می‌کند. خواندنی-نوشتنی Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | مشخص می‌کند که آیا شکل مخفی است یا خیر. خواندنی-نوشتنی Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | پیوندی که برای کلیک موس تعریف شده است را برمی‌گرداند یا تنظیم می‌کند. خواندنی-نوشتنی [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر پیوندها را برمی‌گرداند. فقط-خواندنی [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | پیوندی که برای حرکت موس فوق تعریف شده است را برمی‌گرداند یا تنظیم می‌کند. خواندنی-نوشتنی [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه 'علامت به عنوان تزئینی' را برمی‌گیرد یا تنظیم می‌کند. خواندنی-نوشتنی Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | تعیین می‌کند که آیا شکل گروه‌بندی شده است یا خیر. فقط-خواندنی Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | تعیین می‌کند که آیا شکل TextHolder_PPT است یا خیر. فقط-خواندنی Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat را برمی‌گرداند که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است. توجه: برای برخی انواع شکل‌ها که ویژگی خط ندارند ممکن است مقدار null برگردد. فقط-خواندنی [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند. نباید null باشد. در صورت نیاز می‌توان از رشته خالی استفاده کرد. خواندنی-نوشتنی String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | شناسهٔ یکتا منحصر به اسلاید که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop امکان ارجاع قابل اطمینان به شکل از هر نقطه‌ای در سند را می‌دهد. فقط-خواندنی UInt32. همچنین ببینید [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | اگر شکل گروه‌بندی شده باشد شیء GroupShape والد را برمی‌گرداند. در غیر این صورت مقدار null برگردانده می‌شود. فقط-خواندنی [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | محل نگهدارندهٔ شکل را برمی‌گرداند. اگر شکل مکان‌نگهدار نداشته باشد مقدار null برگردانده می‌شود. فقط-خواندنی [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائهٔ والد اسلاید را برمی‌گرداند. فقط-خواندنی [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ویژگی‌های خام چارچوب شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی-نوشتنی [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجه‌های چرخش شکل مشخص‌شده حول محور z را برمی‌گرداند یا تنظیم می‌کند. مقدار مثبت نشانگر چرخش ساعت‌گرد و مقدار منفی نشانگر چرخش پاد ساعت‌گرد است. خواندنی-نوشتنی Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط-خواندنی [`IBaseShapeLock`](../../aspose.slides/ibaseshapelock). |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | شیء سبک شکل را برمی‌گرداند. فقط-خواندنی [`IShapeStyle`](../../aspose.slides/ishapestyle). |
| override [ShapeType](../../aspose.slides.smartart/smartartshape/shapetype) { get; set; } | نوع پیش‌تنظیم هندسه را برمی‌گرداند یا تنظیم می‌کند. توجه: هنگام تغییر مقدار، تمام مقادیر تنظیم به مقدار پیش‌فرض خود بازمی‌گردند. خواندنی-نوشتنی [`ShapeType`](../../aspose.slides/shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد شکل را برمی‌گرداند. فقط-خواندنی [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [TextFrame](../../aspose.slides.smartart/smartartshape/textframe) { get; } | متن شکل SmartArt را برمی‌گرداند. فقط-خواندنی [`ITextFrame`](../../aspose.slides/itextframe). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat را برمی‌گرداند که شامل ویژگی‌های اثر 3D برای یک شکل است. توجه: برای برخی انواع شکل‌ها که ویژگی 3D ندارند ممکن است مقدار null برگردد. فقط-خواندنی [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | شناسهٔ داخلی محدودهٔ ارائه که برای استفاده توسط افزونه‌ها یا کدهای دیگر در نظر گرفته شده است را برمی‌گرداند. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویسی دوباره اختصاص یابد، نباید به‌عنوان کلید یکتای دائمی درنظر گرفته شود. فقط-خواندنی UInt32. همچنین ببینید [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض شکل برحسب نقاط را برمی‌گیرد یا تنظیم می‌کند. خواندنی-نوشتنی Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشهٔ بالای چپ شکل برحسب نقاط را برمی‌گیرد یا تنظیم می‌کند. خواندنی-نوشتنی Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشهٔ بالای چپ شکل برحسب نقاط را برمی‌گیرد یا تنظیم می‌کند. خواندنی-نوشتنی Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکلی را که در انتهای ترتیب z است برمی‌گرداند و Shapes[Shapes.Count - 1] شکلی را که در جلوترین موقعیت ترتیب z است برمی‌گرداند. فقط-خواندنی Int32. |

## متدها

| نام | توضیح |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | در صورت عدم وجود، یک مکان‌نگهدار جدید اضافه می‌کند و ویژگی‌های مکان‌نگهدار را به مورد مشخص‌شده تنظیم می‌کند. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | آرایه‌ای از عناصر شکل را ایجاد و برمی‌گرداند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک شکل مکان‌نگهدار پایه را برمی‌گرداند (شکلی از طرح‌بندی و/یا اسلاید اصلی که شکل فعلی از آن به ارث می‌برد). اگر شکل فعلی به ارث نبرده باشد مقدار null برگردانده می‌شود. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | کپی مسیر شکل هندسی را برمی‌گرداند. مختصات‌ها نسبت به گوشهٔ چپ-بالا شکل هستند. |
| [GetImage](../../aspose.slides/shape/getimage)() | تصویر کوچک شکل را برمی‌گرداند. به طور پیش‌فرض نوع محدودهٔ تصویر کوچک ShapeThumbnailBounds.Shape استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تصویر کوچک شکل را برمی‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | مرزهای بصری شکل را که از محتویات رندر شده محاسبه شده‌اند، برمی‌گیرد. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | مشخص می‌کند که این شکل مکان‌نگهدار نیست. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | هندسه شکل را از شیء [`IGeometryPath`](../../aspose.slides/igeometrypath) به‌روز می‌کند. مختصات‌ها باید نسبت به گوشهٔ چپ-بالای شکل باشند. نوع شکل ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) را به Custom تغییر می‌دهد. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | هندسه شکل را از آرایه‌ای از [`IGeometryPath`](../../aspose.slides/igeometrypath) به‌روز می‌کند. مختصات‌ها باید نسبت به گوشهٔ چپ-بالای شکل باشند. نوع شکل ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) را به Custom تغییر می‌دهد. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتویات Shape را به عنوان فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISSVGOptions) | محتویات Shape را به عنوان فایل SVG ذخیره می‌کند. |

### سایر موارد

* کلاس [GeometryShape](../../aspose.slides/geometryshape)
* اینترفیس [ISmartArtShape](../ismartartshape)
* فضای‌نام [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->