---
title: GraphicalObject
second_title: مرجع API Aspose.Sildes برای .NET
description: نمایانگر شی گرافیکی انتزاعی.
type: docs
weight: 5090
url: /fa/aspose.slides/graphicalobject/
---
## GraphicalObject کلاس

نمایش یک شی گرافیکی انتزاعی.

```csharp
public class GraphicalObject : Shape, IGraphicalObject
```

## خواص

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | مقدار متن جایگزین مرتبط با یک شکل را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | عنوان متن جایگزین مرتبط با یک شکل را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | ویژگی تعیین می‌کند که یک شکل در حالت نمایش سیاه-سفید چگونه رندر می‌شود. خواندنی/نوشتنی [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال بر روی شکل را بر می‌گرداند. فقط‌خواندنی Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی شکل را بر می‌گرداند. فقط‌خواندنی [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat را بر می‌گرداند که شامل جلوه‌های پیکسل‌ایی اعمال‌شده بر یک شکل است. نکته: ممکن است برای برخی انواع شکل‌ها که ویژگی‌های اثر ندارند مقدار null بازگرداند. فقط‌خواندنی [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شیء FillFormat را بر می‌گرداند که شامل ویژگی‌های قالب‌بندی پرکننده برای یک شکل است. نکته: ممکن است برای برخی انواع شکل‌ها که ویژگی‌های پرکننده ندارند مقدار null بازگرداند. فقط‌خواندنی [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ویژگی‌های قاب شکل را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | قفل‌های شکل را بر می‌گرداند. فقط‌خواندنی [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع شکل را بر حسب پوینت می‌گیرد یا تنظیم می‌کند. خواندنی/نوشتنی Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | مشخص می‌کند آیا شکل مخفی است یا نه. خواندنی/نوشتنی Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | پیوند فرامتن تعریف‌شده برای کلیک ماوس را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر پیوند فرامتن را بر می‌گرداند. فقط‌خواندنی [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | پیوند فرامتن تعریف‌شده برای حرکت ماوس بر روی شی را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه 'Mark as decorative' را می‌گیرد یا تنظیم می‌کند. خواندنی/نوشتنی Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | مشخص می‌کند آیا شکل گروه‌بندی شده است یا نه. فقط‌خواندنی Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | مشخص می‌کند آیا شکل TextHolder_PPT است یا نه. فقط‌خواندنی Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat را بر می‌گرداند که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است. نکته: ممکن است برای برخی انواع شکل‌ها که ویژگی‌های خط ندارند مقدار null بازگرداند. فقط‌خواندنی [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک شکل را بر می‌گرداند یا تنظیم می‌کند. نباید خالی باشد. در صورت نیاز مقدار رشته خالی را استفاده کنید. خواندنی/نوشتنی String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | یک شناسه یکتا محدود به اسلاید را بر می‌گرداند که در طول عمر شکل ثابت می‌ماند و به PowerPoint یا کد interop امکان ارجاع قابل اعتماد به شکل را از هر نقطه‌ای در سند می‌دهد. فقط‌خواندنی UInt32. همچنین ببینید [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | اگر شکل گروه‌بندی شده باشد شیء GroupShape والد را بر می‌گرداند. در غیر این صورت مقدار null برگردانده می‌شود. فقط‌خواندنی [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | محل نگهدارنده (placeholder) یک شکل را بر می‌گرداند. اگر شکل هیچ placeholder نداشته باشد مقدار null برگردانده می‌شود. فقط‌خواندنی [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائه (presentation) والد یک اسلاید را بر می‌گرداند. فقط‌خواندنی [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ویژگی‌های خام قاب شکل را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجاتی که شکل مشخص شده حول محور z چرخانده می‌شود را بر می‌گرداند یا تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پاد ساعت‌گرد است. خواندنی/نوشتنی Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | قفل‌های شکل را بر می‌گرداند. فقط‌خواندنی [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 ویژگی) |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد یک شکل را بر می‌گرداند. فقط‌خواندنی [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat را بر می‌گرداند که شامل ویژگی‌های اثر 3بعدی برای یک شکل است. نکته: ممکن است برای برخی انواع شکل‌ها که ویژگی‌های 3d ندارند مقدار null بازگرداند. فقط‌خواندنی [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | یک شناسه داخلی محدود به ارائه (presentation) که برای استفاده افزونه‌ها یا کدهای دیگر در نظر گرفته شده است را بر می‌گرداند. چون این مقدار می‌تواند توسط کاربر یا برنامه دوباره اختصاص یابد، نباید به عنوان کلید یکتا دائمی در نظر گرفته شود. فقط‌خواندنی UInt32. همچنین ببینید [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض شکل را بر حسب پوینت می‌گیرد یا تنظیم می‌کند. خواندنی/نوشتنی Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشه بالا-چپ شکل را بر حسب پوینت می‌گیرد یا تنظیم می‌کند. خواندنی/نوشتنی Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشه بالا-چپ شکل را بر حسب پوینت می‌گیرد یا تنظیم می‌کند. خواندنی/نوشتنی Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک شکل در ترتیب Z را بر می‌گرداند. Shapes[0] شکل را در پشت ترتیب Z برمی‌گرداند و Shapes[Shapes.Count - 1] شکل را در جلو ترتیب Z برمی‌گرداند. فقط‌خواندنی Int32. |

## متدها

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | یک placeholder جدید اضافه می‌کند اگر موجود نباشد و ویژگی‌های placeholder را به مقدار مشخص شده تنظیم می‌کند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک شکل placeholder پایه را برمی‌گرداند (شکلی از طرح‌بندی و/یا اسلاید اصلی که شکل فعلی از آن به ارث برده است). اگر شکل فعلی به ارث نرسیده باشد مقدار null برگردانده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)() | تصویر بندانگشتی شکل را برمی‌گرداند. نوع ShapeThumbnailBounds.Shape برای محدوده تصویر بندانگشتی به‌صورت پیش‌فرض استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تصویر بندانگشتی شکل را برمی‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | مرزهای تصویری شکل را که از محتوی رندرش محاسبه شده است، می‌گیرد. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | تعریف می‌کند که این شکل placeholder نیست. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتویات Shape را به‌عنوان فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | محتویات Shape را به‌عنوان فایل SVG ذخیره می‌کند. |

### همچنین ببینید

* کلاس [Shape](../shape)
* اینترفیس [IGraphicalObject](../igraphicalobject)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->