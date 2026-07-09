---
title: InkActions
second_title: مرجع API Aspose.Sildes برای .NET
description: نمایانگر ریشهٔ اقدامات جوهر است.
type: docs
weight: 7560
url: /fa/aspose.slides.ink/inkactions/
---
## InkActions کلاس

ریشهٔ اقدامات جوهر را نشان می‌دهد.

```csharp
public class InkActions : GraphicalObject, IInkActions
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | خاصیت نحوه نمایش یک شکل در حالت سیاه-سفید را مشخص می‌کند. قابل خواندن/نوشتن [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال در شکل را برمی‌گرداند. فقط خواندنی Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی شکل را برمی‌گرداند. فقط خواندنی [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat را برمی‌گرداند که شامل اثرات پیکسل اعمال‌شده به یک شکل است. نکته: ممکن است برای برخی انواع شکل‌ها که ویژگی اثر ندارند مقدار null برگرداند. فقط خواندنی [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شیء FillFormat را برمی‌گرداند که شامل ویژگی‌های قالب‌بندی پر کردن برای یک شکل است. نکته: ممکن است برای برخی انواع شکل‌ها که ویژگی پر کردن ندارند مقدار null برگرداند. فقط خواندنی [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ویژگی‌های فریم شکل را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط خواندنی [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع شکل بر حسب نقطه را برمی‌گیرد یا تنظیم می‌کند. قابل خواندن/نوشتن Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | مشخص می‌کند که آیا شکل مخفی است یا نه. قابل خواندن/نوشتن Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | پیوندهای تعریف‌شده برای کلیک ماوس را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر پیوندها را برمی‌گرداند. فقط خواندنی [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | پیوند تعریف‌شده برای عبور ماوس را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه 'Mark as decorative' را برمی‌گیرد یا تنظیم می‌کند. قابل خواندن/نوشتن Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | مشخص می‌کند که آیا شکل گروه‌بندی شده است یا نه. فقط خواندنی Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | مشخص می‌کند که آیا شکل TextHolder_PPT است یا نه. فقط خواندنی Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat را برمی‌گرداند که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است. نکته: ممکن است برای برخی انواع شکل‌ها که ویژگی خط ندارند مقدار null برگرداند. فقط خواندنی [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند. نباید null باشد. در صورت نیاز از مقدار رشتهٔ خالی استفاده کنید. قابل خواندن/نوشتن String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | شناسهٔ یکتا مختص اسلاید که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop امکان ارجاع قابل اطمینان به شکل را از هرجای سند می‌دهد را برمی‌گرداند. فقط خواندنی UInt32. همچنین به [`UniqueId`](../../aspose.slides/shape/uniqueid) مراجعه کنید. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | اگر شکل گروه‌بندی شده باشد شیء GroupShape والد را برمی‌گرداند. در غیر این صورت null برمی‌گرداند. فقط خواندنی [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | نگهدارنده (placeholder) برای یک شکل را برمی‌گرداند. اگر شکل نگهدارنده‌ای نداشته باشد null برمی‌گرداند. فقط خواندنی [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائهٔ والد اسلاید را برمی‌گرداند. فقط خواندنی [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ویژگی‌های فریم خام شکل را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجه‌هایی که شکل مشخص شده حول محور z چرخانده می‌شود را برمی‌گرداند یا تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پادساعت‌گرد است. قابل خواندن/نوشتن Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط خواندنی [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 ویژگی) |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد یک شکل را برمی‌گرداند. فقط خواندنی [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat که ویژگی‌های اثر 3D برای یک شکل را دارد را برمی‌گرداند. نکته: ممکن است برای برخی انواع شکل‌ها که ویژگی 3D ندارند مقدار null برگرداند. فقط خواندنی [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | شناسهٔ داخلی مختص ارائه که برای استفاده توسط افزونه‌ها یا کدهای دیگر در نظر گرفته شده است را برمی‌گرداند. از آنجا که این مقدار می‌تواند توسط کاربر یا برنامه‌نویسی دوباره مقداردهی شود، نباید به‌عنوان کلید یکتا دائمی در نظر گرفته شود. فقط خواندنی UInt32. همچنین به [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid) مراجعه کنید. |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض شکل بر حسب نقطه را برمی‌گیرد یا تنظیم می‌کند. قابل خواندن/نوشتن Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشهٔ بالا-چپ شکل بر حسب نقطه را برمی‌گیرد یا تنظیم می‌کند. قابل خواندن/نوشتن Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشهٔ بالا-چپ شکل بر حسب نقطه را برمی‌گیرد یا تنظیم می‌کند. قابل خواندن/نوشتن Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک شکل را در ترتیب z برمی‌گرداند. Shapes[0] شکل در انتهای پشت ترتیب z را برمی‌گرداند و Shapes[Shapes.Count - 1] شکل در جلوی ترتیب z را برمی‌گرداند. فقط خواندنی Int32. |

## متدها

| نام | توضیح |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | اگر placeholder وجود نداشته باشد، یک placeholder جدید اضافه می‌کند و ویژگی‌های placeholder را به مقدار مشخص شده تنظیم می‌کند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک شکل placeholder پایه (شکل از طرح‌بندی و/یا اسلاید اصلی که شکل فعلی از آن به ارث برده شده است) را برمی‌گرداند. اگر شکل فعلی به ارث نرسیده باشد null برگردانده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)() | تصویر کوچک شکل را برمی‌گرداند. به‌طور پیش‌فرض نوع ShapeThumbnailBounds.Shape برای محدوده تصویر کوچک شکل استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تصویر کوچک شکل را برمی‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | حدود بصری شکل که از محتوای رندر شده آن محاسبه می‌شود را برمی‌گیرد. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | این را تعریف می‌کند که این شکل یک placeholder نیست. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتوای Shape را به‌عنوان فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | محتوای Shape را به‌عنوان فایل SVG ذخیره می‌کند. |

### همچنین ببینید

* کلاس [GraphicalObject](../../aspose.slides/graphicalobject)
* اینترفیس [IInkActions](../iinkactions)
* فضای نام [Aspose.Slides.Ink](../../aspose.slides.ink)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->