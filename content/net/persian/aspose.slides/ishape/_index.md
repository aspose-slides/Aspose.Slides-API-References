---
title: IShape
second_title: Aspose.Sildes برای مرجع API .NET
description: نمایانگر یک شکل بر روی اسلاید.
type: docs
weight: 6950
url: /fa/aspose.slides/ishape/
---
## IShape رابط

نمایش یک شکل روی اسلاید.

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | دسترسی به رابط پایه IHyperlinkContainer را فراهم می‌کند. فقط خواندنی [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | دسترسی به رابط پایه ISlideComponent را فراهم می‌کند. فقط خواندنی [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | خاصیتی که نحوه نمایش یک شکل در حالت سیاه-سفید را مشخص می‌کند. قابل خواندن/نوشتن [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | تعداد نقاط اتصال بر روی شکل را برمی‌گرداند. فقط خواندنی Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | داده‌های سفارشی شکل را برمی‌گرداند. فقط خواندنی [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | شیء EffectFormat که شامل اثرات پیکسل اعمال شده بر یک شکل است را برمی‌گرداند. فقط خواندنی [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | شیء FillFormat که شامل ویژگی‌های قالب‌بندی پرکنش برای یک شکل است را برمی‌گرداند. فقط خواندنی [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | خواص قاب شکل را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | ارتفاع شکل را که برحسب نقطه اندازه‌گیری می‌شود برمی‌گیرد یا تنظیم می‌کند. قابل خواندن/نوشتن Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | تعیین می‌کند آیا شکل مخفی است یا نه. قابل خواندن/نوشتن Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | گزینه 'Mark as decorative' را می‌گیرد یا تنظیم می‌کند. قابل خواندن/نوشتن Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | تعیین می‌کند آیا شکل گروه‌بندی شده است یا نه. فقط خواندنی Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | تعیین می‌کند آیا شکل یک TextHolder است یا نه. فقط خواندنی Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | شیء LineFormat که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است را برمی‌گرداند. فقط خواندنی [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | یک شناسه یکتا scoped به اسلاید را برمی‌گرداند که در طول عمر شکل ثابت می‌ماند و به PowerPoint یا کد interop امکان ارجاع قابل اطمینان به شکل را از هر نقطه‌ای در سند می‌دهد. فقط خواندنی UInt32. همچنین ببینید [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | اگر شکل گروه‌بندی شده باشد، شیء GroupShape والد را برمی‌گرداند. در غیر این صورت null برمی‌گرداند. فقط خواندنی [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | متغیر جایگزین (placeholder) برای یک شکل را برمی‌گرداند. فقط خواندنی [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | خواص قاب شکل خام را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | تعداد درجه‌هایی که شکل مشخص شده حول محور z چرخیده است را برمی‌گرداند یا تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پاد ساعت‌گرد است. قابل خواندن/نوشتن Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط خواندنی [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | شیء ThreeDFormat که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است را برمی‌گرداند. فقط خواندنی [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | یک شناسه داخلی scoped به ارائه را برمی‌گرداند که برای استفاده توسط افزونه‌ها یا کدهای دیگر در نظر گرفته شده است. از آنجا که این مقدار می‌تواند توسط کاربر یا برنامه‌نویس دوباره اختصاص داده شود، نباید به عنوان یک کلید یکتا دائم در نظر گرفته شود. فقط خواندنی UInt32. همچنین ببینید [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/ishape/width) { get; set; } | عرض شکل را که برحسب نقطه اندازه‌گیری می‌شود می‌گیرد یا تنظیم می‌کند. قابل خواندن/نوشتن Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | مختصات x گوشه بالایی-چپ شکل که برحسب نقطه اندازه‌گیری می‌شود را می‌گیرد یا تنظیم می‌کند. قابل خواندن/نوشتن Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | مختصات y گوشه بالایی-چپ شکل که برحسب نقطه اندازه‌گیری می‌شود را می‌گیرد یا تنظیم می‌کند. قابل خواندن/نوشتن Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل را که در انتهای ترتیب z قرار دارد برمی‌گرداند و Shapes[Shapes.Count - 1] شکل را که در جلوی ترتیب z است برمی‌گرداند. فقط خواندنی Int32. |

## متدها

| نام | توضیح |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | یک placeholder جدید اضافه می‌کند اگر وجود نداشته باشد و ویژگی‌های placeholder را به مقدار مشخص شده تنظیم می‌کند. |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | یک شکل placeholder پایه را برمی‌گرداند (شکلی از چیدمان و/یا اسلاید اصلی که شکل فعلی از آن ارث‌بری شده است). اگر شکل فعلی ارث‌بری نشده باشد، null برمی‌گردد. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | تصویر کوچک (thumbnail) شکل را برمی‌گرداند. نوع ShapeThumbnailBounds.Shape به‌طور پیش‌فرض استفاده می‌شود. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | تصویر کوچک (thumbnail) شکل را برمی‌گرداند. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | تعریف می‌کند که این شکل placeholder نیست. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | محتویات Shape را به‌عنوان فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | محتویات Shape را به‌عنوان فایل SVG ذخیره می‌کند. |

### موارد مرتبط

* رابط [IHyperlinkContainer](../ihyperlinkcontainer)
* رابط [ISlideComponent](../islidecomponent)
* فضای نام [Aspose.Slides](../../aspose.slides)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->