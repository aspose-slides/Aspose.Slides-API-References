---
title: SummaryZoomFrame
second_title: مرجع API Aspose.Sildes برای .NET
description: یک شیء Summary Zoom را در یک اسلاید نمایان می‌کند.
type: docs
weight: 10790
url: /fa/aspose.slides/summaryzoomframe/
---
## کلاس SummaryZoomFrame

یک شیء Summary Zoom را در یک اسلاید توصیف می‌کند.

```csharp
public class SummaryZoomFrame : GraphicalObject, ISummaryZoomFrame
```

## خصوصیات

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | مقدار متن جایگزین مرتبط با یک شکل را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | عنوان متن جایگزین مرتبط با یک شکل را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه-سفید رندر می‌شود. خواندنی/نوشتنی [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد سایت‌های اتصال روی شکل را بازمی‌گرداند. فقط-خواندنی Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی شکل را بازمی‌گرداند. فقط-خواندنی [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat را که شامل افکت‌های پیکسلی اعمال‌شده به یک شکل است، بازمی‌گرداند. توجه: ممکن است برای برخی انواع شکل‌ها که ویژگی اثر ندارند، مقدار null برگرداند. فقط-خواندنی [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شیء FillFormat را که شامل ویژگی‌های قالب‌بندی پر کردن برای یک شکل است، بازمی‌گرداند. توجه: ممکن است برای برخی انواع شکل‌ها که ویژگی پر کردن ندارند، مقدار null برگرداند. فقط-خواندنی [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ویژگی‌های فریم شکل را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | قفل‌های شکل را بازمی‌گرداند. فقط-خواندنی [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع شکل را که بر حسب نقطه‌ها اندازه‌گیری می‌شود، بازمی‌گیرد یا تنظیم می‌کند. خواندنی/نوشتنی Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | مشخص می‌کند که آیا شکل مخفی است یا نه. خواندنی/نوشتنی Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | پیوندهای تعریف‌شده برای کلیک ماوس را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر پیوندها را بازمی‌گرداند. فقط-خواندنی [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | پیوندهای تعریف‌شده برای عبور ماوس را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه 'علامت به عنوان تزئینی' را دریافت یا تنظیم می‌کند. خواندنی/نوشتنی Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | مشخص می‌کند که آیا شکل گروه‌بندی شده است یا نه. فقط-خواندنی Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | مشخص می‌کند که آیا شکل TextHolder_PPT است یا نه. فقط-خواندنی Boolean. |
| [Layout](../../aspose.slides/summaryzoomframe/layout) { get; } | چیدمان بخش‌های Summary Zoom را در فریم دریافت می‌کند. مقدار پیش‌فرض GridLayout است. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat را که شامل ویژگی‌های قالب‌بندی خطوط برای یک شکل است، بازمی‌گرداند. توجه: ممکن است برای برخی انواع شکل‌ها که ویژگی خط ندارند، مقدار null برگرداند. فقط-خواندنی [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک شکل را بازمی‌گرداند یا تنظیم می‌کند. نباید null باشد. در صورت نیاز می‌توانید مقدار رشته خالی استفاده کنید. خواندنی/نوشتنی String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | یک شناسه منحصر به‌فرد scoped به اسلاید را که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop امکان ارجاع قابل اعتماد به شکل را از هرجایی در سند می‌دهد، بازمی‌گرداند. فقط-خواندنی UInt32. همچنین ببینید [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | اگر شکل گروه‌بندی شده باشد، شیء GroupShape والد را بازمی‌گرداند. در غیر این صورت مقدار null را برمی‌گرداند. فقط-خواندنی [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | محل نگهداری (placeholder) برای یک شکل را بازمی‌گرداند. اگر شکل هیچ placeholder ای نداشته باشد، مقدار null برمی‌گرداند. فقط-خواندنی [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائه (presentation) والد اسلاید را بازمی‌گرداند. فقط-خواندنی [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ویژگی‌های فریم شکل خام را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجاتی که شکل مشخص شده حول محور z چرخانده می‌شود را بازمی‌گرداند یا تنظیم می‌کند. مقدار مثبت نشانگر چرخش ساعت‌گرد؛ مقدار منفی نشانگر چرخش پادساعت‌گرد است. خواندنی/نوشتنی Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | قفل‌های شکل را بازمی‌گرداند. فقط-خواندنی [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 ویژگی) |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد شکل را بازمی‌گرداند. فقط-خواندنی [`IBaseSlide`](../ibaseslide). |
| [SummaryZoomCollection](../../aspose.slides/summaryzoomframe/summaryzoomcollection) { get; } | [`ISummaryZoomSectionCollection`](../isummaryzoomsectioncollection) را برای شیء Summary Zoom Frame دریافت می‌کند. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat که شامل ویژگی‌های اثر 3d برای یک شکل است را بازمی‌گرداند. توجه: ممکن است برای برخی انواع شکل‌ها که ویژگی 3d ندارند، مقدار null برگرداند. فقط-خواندنی [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | یک شناسه داخلی scoped به ارائه را که برای استفاده توسط افزودنی‌ها یا کدهای دیگر در نظر گرفته شده است، بازمی‌گرداند. از آنجا که این مقدار می‌تواند توسط کاربر یا برنامه‌نویس مجدداً اختصاص یابد، نباید به عنوان کلید منحصر به‌فرد پایدار محسوب شود. فقط-خواندنی UInt32. همچنین ببینید [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض شکل را که بر حسب نقطه‌ها اندازه‌گیری می‌شود، بازمی‌گیرد یا تنظیم می‌کند. خواندنی/نوشتنی Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشه بالایی چپ شکل را که بر حسب نقطه‌ها اندازه‌گیری می‌شود، بازمی‌گیرد یا تنظیم می‌کند. خواندنی/نوشتنی Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشه بالایی چپ شکل را که بر حسب نقطه‌ها اندازه‌گیری می‌شود، بازمی‌گیرد یا تنظیم می‌کند. خواندنی/نوشتنی Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک شکل در ترتیب z را بازمی‌گرداند. Shapes[0] شکل در پشت ترتیب z را برمی‌گرداند و Shapes[Shapes.Count - 1] شکل در جلوی ترتیب z را برمی‌گرداند. فقط-خواندنی Int32. |

## متدها

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | اگر placeholder ای وجود نداشته باشد، یک placeholder جدید اضافه می‌کند و ویژگی‌های placeholder را به یک مقدار مشخص تنظیم می‌کند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک شکل placeholder پایه (شکل از طرح بندی و/یا اسلاید اصلی که شکل فعلی از آن ارث‌بری می‌کند) را بازمی‌گرداند. اگر شکل فعلی ارث‌بری نشده باشد، مقدار null برگردانده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)() | تصویر کوچک شکل را بازمی‌گرداند. به‌طور پیش‌فرض نوع ShapeThumbnailBounds.Shape برای محدوده تصویر کوچک استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تصویر کوچک شکل را بازمی‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | حدود بصری شکل را که از محتوای رندر شده محاسبه می‌شود، دریافت می‌کند. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | تعریف می‌کند که این شکل یک placeholder نیست. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتوای Shape را به‌عنوان فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | محتوای Shape را به‌عنوان فایل SVG ذخیره می‌کند. |

### مراجع

* کلاس [GraphicalObject](../graphicalobject)
* رابط [ISummaryZoomFrame](../isummaryzoomframe)
* فضای نام [Aspose.Slides](../../aspose.slides)
* مجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->