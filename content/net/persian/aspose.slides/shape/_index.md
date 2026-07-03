---
title: Shape
second_title: Aspose.Sildes برای .NET مرجع API
description: نمایانگر یک shape بر روی اسلاید است.
type: docs
weight: 9830
url: /fa/aspose.slides/shape/
---
## کلاس Shape

نمایانگر یک shape بر روی اسلاید است.

```csharp
public class Shape : IShape
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | متن جایگزین مرتبط با یک shape را بر می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | عنوان متن جایگزین مرتبط با یک shape را بر می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | ویژگی مشخص می‌کند که یک shape چگونه در حالت نمایش سیاه-سفارشی رندر می‌شود. خواندن/نوشتن [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال روی shape را بر می‌گرداند. فقط-خواندنی Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی shape را بر می‌گرداند. فقط-خواندنی [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat را بر می‌گرداند که شامل اثرات پیکسل اعمال شده بر یک shape است. توجه: برای برخی انواع shape که ویژگی اثر ندارند، ممکن است null برگردد. فقط-خواندنی [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شیء FillFormat را بر می‌گرداند که شامل ویژگی‌های قالب‌بندی پر کننده برای یک shape است. توجه: برای برخی انواع shape که ویژگی پر کننده ندارند، ممکن است null برگردد. فقط-خواندنی [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | خواص فریم shape را بر می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع shape را که بر حسب نقطه است، دریافت یا تنظیم می‌کند. خواندن/نوشتن Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | مشخص می‌کند که آیا shape مخفی است یا نه. خواندن/نوشتن Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | پیوندی که برای کلیک ماوس تعریف شده است را بر می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر پیوند را بر می‌گرداند. فقط-خواندنی [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | پیوندی که برای حرکت ماوس بر روی آن تعریف شده است را بر می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه 'Mark as decorative' را دریافت یا تنظیم می‌کند. خواندن/نوشتن Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | مشخص می‌کند که آیا shape گروه‌بندی شده است یا نه. فقط-خواندنی Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | مشخص می‌کند که آیا shape TextHolder_PPT است یا نه. فقط-خواندنی Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat را بر می‌گرداند که شامل ویژگی‌های قالب‌بندی خط برای یک shape است. توجه: برای برخی انواع shape که ویژگی خط ندارند، ممکن است null برگردد. فقط-خواندنی [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک shape را بر می‌گرداند یا تنظیم می‌کند. نباید null باشد. در صورت نیاز می‌توانید مقدار رشتهٔ خالی را استفاده کنید. خواندن/نوشتن String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | شناسهٔ یکتای scoped به اسلاید را که در طول عمر shape ثابت می‌ماند و به PowerPoint یا کد interop اجازه می‌دهد به طور قابل اعتماد از هر نقطه‌ای در سند به shape ارجاع دهد، بر می‌گرداند. فقط-خواندنی UInt32. همچنین ببینید [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | اگر shape گروه‌بندی شده باشد، شیء GroupShape والد را بر می‌گرداند؛ در غیر این صورت null برمی‌گردد. فقط-خواندنی [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | placeholder یک shape را بر می‌گرداند. اگر shape placeholder نداشته باشد، null برمی‌گردد. فقط-خواندنی [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائه والد اسلاید را بر می‌گرداند. فقط-خواندنی [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | خواص فریم خام shape را بر می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجه‌های چرخش shape مشخص شده حول محور z را بر می‌گرداند یا تنظیم می‌کند. مقدار مثبت نشان‌دهندهٔ چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهندهٔ چرخش پادساعت‌گرد است. خواندن/نوشتن Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | قفل‌های shape را بر می‌گرداند. فقط-خواندنی [`IBaseShapeLock`](../ibaseshapelock). |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد یک shape را بر می‌گرداند. فقط-خواندنی [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat را بر می‌گرداند که شامل ویژگی‌های اثر 3D برای یک shape است. توجه: برای برخی انواع shape که ویژگی 3D ندارند، ممکن است null برگردد. فقط-خواندنی [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | شناسهٔ داخلی scoped به ارائه که برای استفاده توسط افزونه‌ها یا کدهای دیگر هدف‌گذاری شده است را بر می‌گرداند. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویس بازنویسی شود، نباید به عنوان کلید یکتای دائمی در نظر گرفته شود. فقط-خواندنی UInt32. همچنین ببینید [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض shape را که بر حسب نقطه است، دریافت یا تنظیم می‌کند. خواندن/نوشتن Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشهٔ بالایی چپ shape را که بر حسب نقطه است، دریافت یا تنظیم می‌کند. خواندن/نوشتن Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشهٔ بالایی چپ shape را که بر حسب نقطه است، دریافت یا تنظیم می‌کند. خواندن/نوشتن Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک shape در ترتیب z را بر می‌گرداند. Shapes[0] شکل در انتهای عقب ترتیب z را بر می‌گرداند و Shapes[Shapes.Count - 1] شکل در جلوی ترتیب z را بر می‌گرداند. فقط-خواندنی Int32. |

## متدها

| نام | توضیح |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | اگر placeholder موجود نباشد، یک placeholder جدید اضافه می‌کند و ویژگی‌های placeholder را به مقدار مشخص شده تنظیم می‌کند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک شکل placeholder پایه را بر می‌گرداند (شکلی از طرح‌بندی و/یا اسلاید اصلی که شکل جاری از آن به ارث می‌برد). اگر شکل جاری به ارث نبرده باشد، null برگردانده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage#getimage)() | تصویر بندانگشتی shape را بر می‌گرداند. نوع ShapeThumbnailBounds.Shape به‌طور پیش‌فرض برای مرزهای تصویر بندانگشتی استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | تصویر بندانگشتی shape را بر می‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | مرزهای بصری shape را که از محتوای رندر شده محاسبه می‌شود، دریافت می‌کند. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | مشخص می‌کند که این shape placeholder نیست. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg#writeassvg)(Stream) | محتوای Shape را به صورت فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | محتوای Shape را به صورت فایل SVG ذخیره می‌کند. |

### مراجع

* رابط [IShape](../ishape)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مجموعه [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->