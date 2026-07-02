---
title: GroupShape
second_title: مرجع API Aspose.Sildes برای .NET
description: نمایانگر گروهی از اشکال در یک اسلاید.
type: docs
weight: 5090
url: /fa/aspose.slides/groupshape/
---
## کلاس GroupShape

نمایانگر گروهی از اشکال در یک اسلاید.

```csharp
public class GroupShape : Shape, IGroupShape
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | مقدار یا تنظیم متن جایگزین مرتبط با یک شکل. قابل‌خواندن/قابل‌نوشتن String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | مقدار یا تنظیم عنوان متن جایگزین مرتبط با یک شکل. قابل‌خواندن/قابل‌نوشتن String. |
| [AsIShape](../../aspose.slides/groupshape/asishape) { get; } | اجازه می‌دهد رابط پایه IShape دریافت شود. فقط‌خواندنی [`IShape`](../ishape). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | خصوصیت تعیین می‌کند شکل در حالت نمایش سیاه-سفید چگونه رندر شود. قابل‌خواندن/قابل‌نوشتن [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال روی شکل را باز می‌گرداند. فقط‌خواندنی Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی شکل را باز می‌گرداند. فقط‌خواندنی [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat را که حاوی افکت‌های پیکسل اعمال‌شده به یک شکل است، باز می‌گرداند. توجه: ممکن است برای برخی انواع شکل‌ها که خصوصیات افکت ندارند، مقدار null برگردد. فقط‌خواندنی [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شیء FillFormat را که حاوی خصوصیات قالب‌بندی پرکننده برای یک شکل است، باز می‌گرداند. توجه: ممکن است برای برخی انواع شکل‌ها که خصوصیات پرکننده ندارند، مقدار null برگردد. فقط‌خواندنی [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | خصوصیات قاب شکل را باز می‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [`IShapeFrame`](../ishapeframe). |
| [GroupShapeLock](../../aspose.slides/groupshape/groupshapelock) { get; } | قفل‌های شکل را باز می‌گرداند. فقط‌خواندنی [`IGroupShapeLock`](../igroupshapelock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع شکل را که بر حسب نقاط اندازه‌گیری می‌شود، باز می‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | تعیین می‌کند آیا شکل مخفی است یا خیر. قابل‌خواندن/قابل‌نوشتن Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | مقدار یا تنظیم پیوند فراموشی (hyperlink) تعریف‌شده برای کلیک ماوس. قابل‌خواندن/قابل‌نوشتن [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیریت‌کننده پیوند فراموشی را باز می‌گرداند. فقط‌خواندنی [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | مقدار یا تنظیم پیوند فراموشی تعریف‌شده برای حرکت ماوس بر روی شکل. قابل‌خواندن/قابل‌نوشتن [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه «علامت‌گذاری به‌عنوان تزئینی» را دریافت یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | تعیین می‌کند آیا شکل در یک گروه قرار دارد یا نه. فقط‌خواندنی Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | تعیین می‌کند آیا شکل TextHolder_PPT است یا نه. فقط‌خواندنی Boolean. |
| override [LineFormat](../../aspose.slides/groupshape/lineformat) { get; } | شیء LineFormat را که حاوی خصوصیات قالب‌بندی خط برای یک شکل است، باز می‌گرداند. توجه: برای اشیای GroupShape مقدار null برگردانده می‌شود زیرا آن‌ها خصوصیات خط ندارند. فقط‌خواندنی [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک شکل را باز می‌گرداند یا تنظیم می‌کند. نباید null باشد. در صورت نیاز می‌توانید مقدار رشته خالی را استفاده کنید. قابل‌خواندن/قابل‌نوشتن String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | شناسه منحصر به‌فرد scoped به اسلاید که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop اجازه می‌دهد به‌صورت قابل اعتماد از هر نقطه‌ای در سند به شکل ارجاع دهند. فقط‌خواندنی UInt32. همچنین ببینید [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | اگر شکل در یک گروه باشد، شیء Parent GroupShape را باز می‌گرداند. در غیر این صورت مقدار null برگردانده می‌شود. فقط‌خواندنی [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | جای‌نگهدارنده (placeholder) مربوط به شکل را باز می‌گرداند. اگر شکل جای‌نگهدارنده‌ای نداشته باشد مقدار null برگردانده می‌شود. فقط‌خواندنی [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائه (presentation) مادر اسلاید را باز می‌گرداند. فقط‌خواندنی [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | خصوصیات فریم خام شکل را باز می‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجه‌های چرخش شکل حول محور z را باز می‌گرداند یا تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پادساعت‌گرد است. قابل‌خواندن/قابل‌نوشتن Single. |
| [ShapeLock](../../aspose.slides/groupshape/shapelock) { get; } | قفل‌های شکل را باز می‌گرداند. فقط‌خواندنی [`IGroupShapeLock`](../igroupshapelock). (2 خصوصیت) |
| [Shapes](../../aspose.slides/groupshape/shapes) { get; } | مجموعهٔ اشکال داخل گروه را باز می‌گرداند. فقط‌خواندنی [`IShapeCollection`](../ishapecollection). |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد یک شکل را باز می‌گرداند. فقط‌خواندنی [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat را که خصوصیات افکت سه‌بعدی برای یک شکل را دارد، باز می‌گرداند. توجه: ممکن است برای برخی انواع شکل‌ها که خصوصیات سه‌بعدی ندارند، مقدار null برگردد. فقط‌خواندنی [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | شناسهٔ داخلی scoped به ارائه که برای استفاده توسط افزونه‌ها یا کدهای دیگر هدف‌گذاری شده است. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویس تغییر یابد، نباید به‌عنوان کلید یکتا دائمی در نظر گرفته شود. فقط‌خواندنی UInt32. همچنین ببینید [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض شکل را که بر حسب نقاط اندازه‌گیری می‌شود، باز می‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشهٔ بالایی-چپ شکل را که بر حسب نقاط اندازه‌گیری می‌شود، باز می‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشهٔ بالایی-چپ شکل را که بر حسب نقاط اندازه‌گی می‌شود، باز می‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک شکل در ترتیب z را باز می‌گرداند. Shapes[0] شکل در پشت‌ترین موقعیت z-order را برمی‌گرداند و Shapes[Shapes.Count - 1] شکل در جلوی‌ترین موقعیت را برمی‌گرداند. فقط‌خواندنی Int32. |

## متدها

| نام | توضیح |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | اگر Placeholder وجود نداشته باشد، یک Placeholder جدید اضافه می‌کند و خصوصیات Placeholder را به مقدار مشخص‌شده تنظیم می‌کند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک شکل placeholder پایه (شکل از الگو یا اسلاید اصلی که شکل فعلی از آن ارث‌بری می‌کند) را باز می‌گرداند. اگر شکل فعلی ارث‌بری نشده باشد مقدار null برگردانده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)() | تصویر بندانگشتی شکل را باز می‌گرداند. به‌طور پیش‌فرض نوع ShapeThumbnailBounds.Shape برای مرزهای تصویر بندانگشتی استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تصویر بندانگشتی شکل را باز می‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | مرزهای بصری شکل را که از محتوای رندرش محاسبه می‌شود، دریافت می‌کند. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | تعیین می‌کند که این شکل یک placeholder نیست. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتوای Shape را به‌صورت فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | محتوای Shape را به‌صورت فایل SVG ذخیره می‌کند. |

### مراجع دیگر

* کلاس [Shape](../shape)
* رابط [IGroupShape](../igroupshape)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مجموعه [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->