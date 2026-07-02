---
title: IShape
second_title: Aspose.Sildes برای .NET مرجع API
description: نمایانگر یک شکل بر روی اسلاید است.
type: docs
weight: 6950
url: /fa/aspose.slides/ishape/
---
## IShape رابط

نمایانگر یک شکل بر روی یک اسلاید است.

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | متن جایگزین مرتبط با یک شکل را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | عنوان متن جایگزین مرتبط با یک شکل را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | دسترسی به رابط پایه IHyperlinkContainer را فراهم می‌کند. فقط خواندنی [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | دسترسی به رابط پایه ISlideComponent را فراهم می‌کند. فقط خواندنی [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | خاصیت نحوه نمایش یک شکل در حالت سیاه-سفید را مشخص می‌کند. خواندنی/نوشتنی [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | تعداد نقاط اتصال روی شکل را بازمی‌گرداند. فقط خواندنی Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | داده‌های سفارشی شکل را بازمی‌گرداند. فقط خواندنی [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | شیء EffectFormat را که شامل افکت‌های پیکسلی اعمال‌شده به یک شکل است، بازمی‌گرداند. فقط خواندنی [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | شیء FillFormat را که شامل ویژگی‌های فرمت‌گذاری پر کردن برای یک شکل است، بازمی‌گرداند. فقط خواندنی [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | خواص فریم شکل را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | ارتفاع شکل را که به نقطه اندازه‌گیری می‌شود، دریافت یا تنظیم می‌کند. خواندنی/نوشتنی Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | مشخص می‌کند آیا شکل مخفی است یا نه. خواندنی/نوشتنی Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | گزینه 'Mark as decorative' را دریافت یا تنظیم می‌کند. خواندنی/نوشتنی Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | مشخص می‌کند آیا شکل گروه‌بندی شده است یا نه. فقط خواندنی Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | مشخص می‌کند آیا شکل TextHolder است یا نه. فقط خواندنی Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | شیء LineFormat را که شامل ویژگی‌های فرمت‌گذاری خط برای یک شکل است، بازمی‌گرداند. فقط خواندنی [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | نام یک شکل را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | یک شناسه یکتا محدوده‌ اسلاید را بازمی‌گرداند که در طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop امکان ارجاع قابل اطمینان به شکل را از هرجایی در سند می‌دهد. فقط خواندنی UInt32. همچنین ببینید [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | شیء GroupShape والد را اگر شکل گروه‌بندی شده باشد، بازمی‌گرداند. در غیر اینصورت null برمی‌گرداند. فقط خواندنی [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | placeholder مربوط به یک شکل را بازمی‌گرداند. فقط خواندنی [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | خواص فریم خام شکل را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | تعداد درجات چرخش شکل مشخص‌شده حول محور z را بازمی‌گرداند یا تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعتگرد؛ مقدار منفی نشان‌دهنده چرخش پادساعهگرد است. خواندنی/نوشتنی Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | قفل‌های شکل را بازمی‌گرداند. فقط خواندنی [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | شیء ThreeDFormat را که شامل ویژگی‌های فرمت‌گذاری خط برای یک شکل است، بازمی‌گرداند. فقط خواندنی [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | یک شناسه داخلی محدوده‌ی ارائه را که برای استفاده توسط افزونه‌ها یا کدهای دیگر در نظر گرفته شده است، بازمی‌گرداند. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویس دوباره تخصیص یابد، نباید به‌عنوان کلید یکتای پایدار در نظر گرفته شود. فقط خواندنی UInt32. همچنین ببینید [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/ishape/width) { get; set; } | عرض شکل را که به نقطه اندازه‌گیری می‌شود، دریافت یا تنظیم می‌کند. خواندنی/نوشتنی Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | مختصات x گوشه‌ی بالا-چپ شکل را که به نقطه اندازه‌گیری می‌شود، دریافت یا تنظیم می‌کند. خواندنی/نوشتنی Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | مختصات y گوشه‌ی بالا-چپ شکل را که به نقطه اندازه‌گیری می‌شود، دریافت یا تنظیم می‌کند. خواندنی/نوشتنی Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | موقعیت یک شکل در ترتیب z را بازمی‌گرداند. Shapes[0] شکل واقع در پشت‌ترین لایه z را برمی‌گرداند و Shapes[Shapes.Count - 1] شکل واقع در جلوی‌ترین لایه z را برمی‌گرداند. فقط خواندنی Int32. |

## متدها

| نام | توضیح |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | اگر هیچ placeholder‌ای وجود نداشته باشد، یک placeholder جدید اضافه می‌کند و ویژگی‌های placeholder را به مقدار مشخص شده تنظیم می‌کند. |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | یک placeholder پایه‌ی شکل را بازمی‌گرداند (شکل از طرح‌بندی و/یا اسلاید اصلی که شکل جاری از آن به ارث برده است). اگر شکل جاری به ارث نرسیده باشد، null برمی‌گردد. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | تصویر کوچک (thumbnail) شکل را بازمی‌گرداند. نوع ShapeThumbnailBounds.Shape به‌صورت پیش‌فرض استفاده می‌شود. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | تصویر کوچک شکل را بازمی‌گرداند. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | تعریف می‌کند که این شکل placeholder نیست. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | محتویات Shape را به‌عنوان فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | محتویات Shape را به‌عنوان فایل SVG ذخیره می‌کند. |

### موارد مرتبط

* رابط [IHyperlinkContainer](../ihyperlinkcontainer)
* رابط [ISlideComponent](../islidecomponent)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->