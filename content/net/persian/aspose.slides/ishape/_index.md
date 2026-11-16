---
title: IShape
second_title: مرجع API Aspose.Sildes برای .NET
description: یک شکل را در یک اسلاید نشان می‌دهد.
type: docs
weight: 6970
url: /fa/aspose.slides/ishape/
---
## IShape واسط

یک شکل را در یک اسلاید نشان می‌دهد.

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## خصوصیات

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | مقدار متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | اجازه می‌دهد رابط IHyperlinkContainer پایه را دریافت کند. فقط-خواندنی [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | اجازه می‌دهد رابط ISlideComponent پایه را دریافت کند. فقط-خواندنی [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | خصوصیت مشخص می‌کند شکل در حالت نمایش سیاه‌وسفید چگونه رندر شود. خواندنی/قابل نوشتن [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | تعداد نقاط اتصال در شکل را برمی‌گرداند. فقط-خواندنی Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | داده‌های سفارشی شکل را برمی‌گرداند. فقط-خواندنی [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | شیء EffectFormat که اثرات پیکسلی اعمال‌شده بر یک شکل را شامل می‌شود را برمی‌گرداند. فقط-خواندنی [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | شیء FillFormat که خصوصیات قالب‌بندی پرشده برای یک شکل را شامل می‌شود را برمی‌گرداند. فقط-خواندنی [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | خصوصیات چارچوب شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | ارتفاع شکل که بر حسب پوینت اندازه‌گیری می‌شود را دریافت یا تنظیم می‌کند. خواندنی/قابل نوشتن Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | تعیین می‌کند آیا شکل مخفی است یا نه. خواندنی/قابل نوشتن Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | دریافت یا تنظیم گزینه 'Mark as decorative'. خواندنی/قابل نوشتن Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | تعیین می‌کند آیا شکل گروه‌بندی شده است یا نه. فقط-خواندنی Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | تعیین می‌کند آیا شکل TextHolder است یا نه. فقط-خواندنی Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | شیء LineFormat که خصوصیات قالب‌بندی خط برای یک شکل را شامل می‌شود را برمی‌گرداند. فقط-خواندنی [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | شناسه یکتا در محدوده اسلاید که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop اجازه می‌دهد از هر نقطه‌ای در سند به شکل ارجاع دهند را برمی‌گرداند. فقط-خواندنی UInt32. همچنین ببینید [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | اگر شکل گروه‌بندی شده باشد شیء GroupShape والد را برمی‌گرداند. در غیراین صورت null برمی‌گرداند. فقط-خواندنی [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | متغیر نگهدارنده (placeholder) برای یک شکل را برمی‌گرداند. فقط-خواندنی [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | خصوصیات چارچوب خام شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | تعداد درجاتی که شکل مشخص حول محور z چرخانده شده است را برمی‌گرداند یا تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعتگرد؛ مقدار منفی نشان‌دهنده چرخش پادساعتگرد است. خواندنی/قابل نوشتن Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط-خواندنی [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | شیء ThreeDFormat که خصوصیات قالب‌بندی خط برای یک شکل را شامل می‌شود را برمی‌گرداند. فقط-خواندنی [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | شناسه داخلی در محدوده ارائه که برای استفاده توسط افزونه‌ها یا کدهای دیگر منظور شده است را برمی‌گرداند. از آنجا که این مقدار می‌تواند توسط کاربر یا برنامه‌نویس تغییر یابد، نباید به عنوان کلید یکتا ثابت در نظر گرفته شود. فقط-خواندنی UInt32. همچنین ببینید [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/ishape/width) { get; set; } | عرض شکل که بر حسب پوینت اندازه‌گیری می‌شود را دریافت یا تنظیم می‌کند. خواندنی/قابل نوشتن Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | مختصات x گوشه بالا-چپ شکل که بر حسب پوینت اندازه‌گیری می‌شود را دریافت یا تنظیم می‌کند. خواندنی/قابل نوشتن Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | مختصات y گوشه بالا-چپ شکل که بر حسب پوینت اندازه‌گیری می‌شود را دریافت یا تنظیم می‌کند. خواندنی/قابل نوشتن Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل در انتهای ترتیب z را برمی‌گرداند و Shapes[Shapes.Count - 1] شکل در جلوی ترتیب z را برمی‌گرداند. فقط-خواندنی Int32. |

## متدها

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | اگر placeholder وجود نداشته باشد، یک placeholder جدید اضافه می‌کند و خصوصیات placeholder را به مقدار مشخص شده تنظیم می‌کند. |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | یک شکل placeholder پایه (شکلی از چیدمان و/یا اسلاید اصلی که شکل فعلی از آن به ارث می‌رسد) را برمی‌گرداند. اگر شکل فعلی ارث‌برده نشده باشد null برمی‌گردد. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | تصویر کوچک (thumbnail) شکل را برمی‌گرداند. نوع حدود تصویر کوچک ShapeThumbnailBounds.Shape به طور پیش‌فرض استفاده می‌شود. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | تصویر کوچک شکل را برمی‌گرداند. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | مشخص می‌کند که این شکل placeholder نیست. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | محتوای Shape را به عنوان فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | محتوای Shape را به عنوان فایل SVG ذخیره می‌کند. |

### مراجع

* واسط [IHyperlinkContainer](../ihyperlinkcontainer)
* واسط [ISlideComponent](../islidecomponent)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مجوعه [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->