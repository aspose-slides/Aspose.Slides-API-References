---
title: Shape
second_title: Aspose.Sildes برای .NET مرجع API
description: نمایانگر یک Shape در اسلاید.
type: docs
weight: 9850
url: /fa/aspose.slides/shape/
---
## کلاس Shape

نمایانگر یک shape در اسلاید است.

```csharp
public class Shape : IShape
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | متن جایگزین مرتبط با یک shape را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | عنوان متن جایگزین مرتبط با یک shape را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | این ویژگی تعیین می‌کند که یک shape چگونه در حالت نمایش سیاه‌سفید رندر می‌شود. خواندن/نوشتن [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال روی shape را برمی‌گرداند. فقط خواندنی Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی shape را برمی‌گرداند. فقط خواندنی [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat که شامل افکت‌های پیکسلی اعمال‌شده به یک shape است را برمی‌گرداند. توجه: برای برخی انواع shape که ویژگی‌های افکت ندارند ممکن است مقدار null بازگردد. فقط خواندنی [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شیء FillFormat که شامل ویژگی‌های قالب‌بندی پرکننده برای یک shape است را برمی‌گرداند. توجه: برای برخی انواع shape که ویژگی‌های پرکننده ندارند ممکن است مقدار null بازگردد. فقط خواندنی [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ویژگی‌های چارچوب shape را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع shape را که بر حسب نقطه اندازه‌گیری می‌شود برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | مشخص می‌کند که shape مخفی باشد یا نه. خواندن/نوشتن Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | پیوند (hyperlink) تعریف‌شده برای کلیک موشی را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر hyperlink را برمی‌گرداند. فقط خواندنی [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | پیوند (hyperlink) تعریف‌شده برای عبور موشی را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه 'Mark as decorative' را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | مشخص می‌کند که shape گروهبندی شده است یا نه. فقط خواندنی Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | مشخص می‌کند که shape از نوع TextHolder_PPT است یا نه. فقط خواندنی Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat که شامل ویژگی‌های قالب‌بندی خط برای یک shape است را برمی‌گرداند. توجه: برای برخی انواع shape که ویژگی‌های خط ندارند ممکن است مقدار null بازگردد. فقط خواندنی [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک shape را برمی‌گرداند یا تنظیم می‌کند. باید null نباشد. در صورت نیاز می‌توانید از رشته خالی استفاده کنید. خواندن/نوشتن String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | یک شناسه یکتا scoped به اسلاید که برای طول عمر shape ثابت می‌ماند و به PowerPoint یا کدهای interop اجازه می‌دهد shape را از هر نقطه‌ای در سند به‌درستی ارجاع دهند را برمی‌گرداند. فقط خواندنی UInt32. همچنین ببینید [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | اگر shape گروهبندی شده باشد، شیء GroupShape والد را برمی‌گرداند. در غیر این صورت مقدار null برمی‌گردد. فقط خواندنی [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | placeholder مربوط به یک shape را برمی‌گرداند. اگر shape هیچ placeholder نداشته باشد، مقدار null برمی‌گردد. فقط خواندنی [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائه (presentation) والد یک اسلاید را برمی‌گرداند. فقط خواندنی [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ویژگی‌های خام چارچوب shape را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجه‌هایی که shape مشخص شده حول محور z چرخیده است را برمی‌گرداند یا تنظیم می‌کند. مقدار مثبت نشانگر چرخش ساعت‌گرد؛ مقدار منفی نشانگر چرخش پادساعت‌گرد است. خواندن/نوشتن Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | قفل‌های shape را برمی‌گرداند. فقط خواندنی [`IBaseShapeLock`](../ibaseshapelock). |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد یک shape را برمی‌گرداند. فقط خواندنی [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat که شامل ویژگی‌های اثر 3d برای یک shape است را برمی‌گرداند. توجه: برای برخی انواع shape که ویژگی‌های 3d ندارند ممکن است مقدار null بازگردد. فقط خواندنی [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | یک شناسه داخلی scoped به ارائه که برای استفاده توسط افزونه‌ها یا کدهای دیگر در نظر گرفته شده است را برمی‌گرداند. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویس تغییر یابد، نباید به‌عنوان کلید یکتای پایدار استفاده شود. فقط خواندنی UInt32. همچنین ببینید [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض shape را که بر حسب نقطه اندازه‌گیری می‌شود برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشه بالایی چپ shape را که بر حسب نقطه اندازه‌گیری می‌شود برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشه بالایی چپ shape را که بر حسب نقطه اندازه‌گیری می‌شود برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک shape در ترتیب z را برمی‌گرداند. Shapes[0] shape در انتهای ترتیب z را نشان می‌دهد و Shapes[Shapes.Count - 1] shape در جلوی ترتیب z را نشان می‌دهد. فقط خواندنی Int32. |

## متدها

| نام | توضیح |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | اگر placeholder وجود نداشته باشد، یک placeholder جدید اضافه می‌کند و ویژگی‌های placeholder را به مقدار مشخص تنظیم می‌کند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک shape placeholder پایه را برمی‌گرداند (shape ای که از layout و/یا master slide که shape فعلی از آن ارث‌بری می‌کند). اگر shape فعلی ارث‌بری نشده باشد، مقدار null برگردانده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage#getimage)() | تصویر کوچک (thumbnail) shape را برمی‌گرداند. نوع ShapeThumbnailBounds.Shape برای مرزهای تصویر کوچک به‌صورت پیش‌فرض استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | تصویر کوچک shape را برمی‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | مرزهای بصری shape را که از محتویات رندر شده محاسبه می‌شود، برمی‌گرداند. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | تعریف می‌کند که این shape placeholder نیست. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg#writeassvg)(Stream) | محتوای Shape را به‌عنوان فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | محتوای Shape را به‌عنوان فایل SVG ذخیره می‌کند. |

### مراجع

* رابط [IShape](../ishape)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مونتاژ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->