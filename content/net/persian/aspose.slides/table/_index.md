---
title: Table
second_title: مرجع API Aspose.Sildes برای .NET
description: یک جدول را روی اسلاید نشان می‌دهد.
type: docs
weight: 10860
url: /fa/aspose.slides/table/
---
## کلاس Table

یک جدول را روی اسلاید نشان می‌دهد.

```csharp
public sealed class Table : GraphicalObject, ITable
```

## ویژگی‌ها

| نام | توضیحات |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | مقدار متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه‌وسفید رندر می‌شود. خواندن/نوشتن [`BlackWhiteMode`](../blackwhitemode). |
| [Columns](../../aspose.slides/table/columns) { get; } | کلکسیون ستون‌ها را برمی‌گرداند. فقط‌خواندنی [`IColumnCollection`](../icolumncollection). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال شکل را برمی‌گرداند. فقط‌خواندنی Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی شکل را برمی‌گرداند. فقط‌خواندنی [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat را که شامل افکت‌های پیکسل اعمال‌شده به شکل است، برمی‌گرداند. نکته: برای انواع خاصی از شکل‌ها که ویژگی‌های افکت ندارند می‌تواند مقدار null بازگرداند. فقط‌خواندنی [`IEffectFormat`](../ieffectformat). |
| override [FillFormat](../../aspose.slides/table/fillformat) { get; } | شیء TableFormat.FillFormat که حاوی قالب‌بندی پرکننده برای جدول است را برمی‌گرداند. فقط‌خواندنی [`IFillFormat`](../ifillformat). |
| [FirstCol](../../aspose.slides/table/firstcol) { get; set; } | تعیین می‌کند آیا ستون اول جدول باید با قالب‌بندی خاص رسم شود. خواندن/نوشتن Boolean. |
| [FirstRow](../../aspose.slides/table/firstrow) { get; set; } | تعیین می‌کند آیا ردیف اول جدول باید با قالب‌بندی خاص رسم شود. خواندن/نوشتن Boolean. |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ویژگی‌های فریم شکل را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط‌خواندنی [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع شکل را که برحسب پوینت اندازه‌گیری شده، برمی‌گیرد یا تنظیم می‌کند. خواندن/نوشتن Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | تعیین می‌کند آیا شکل مخفی است. خواندن/نوشتن Boolean. |
| [HorizontalBanding](../../aspose.slides/table/horizontalbanding) { get; set; } | تعیین می‌کند آیا ردیف‌های زوج باید با قالب‌بندی متفاوت رسم شوند. خواندن/نوشتن Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | پیوند فراموشی تعریف‌شده برای کلیک ماوس را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر پیوند فراموشی را برمی‌گرداند. فقط‌خواندنی [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | پیوند فراموشی تعریف‌شده برای مرور ماوس را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه 'Mark as decorative' را برمی‌گیرد یا تنظیم می‌کند. خواندن/نوشتن Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | تعیین می‌کند آیا شکل گروه‌بندی شده است. فقط‌خواندنی Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | تعیین می‌کند آیا شکل TextHolder_PPT است. فقط‌خواندنی Boolean. |
| [Item](../../aspose.slides/table/item) { get; } | سلول موجود در ستون و ردیف مشخص‌شده را برمی‌گرداند. فقط‌خواندنی [`Cell`](../cell). |
| [LastCol](../../aspose.slides/table/lastcol) { get; set; } | تعیین می‌کند آیا ستون آخر جدول باید با قالب‌بندی خاص رسم شود. خواندن/نوشتن Boolean. |
| [LastRow](../../aspose.slides/table/lastrow) { get; set; } | تعیین می‌کند آیا ردیف آخر جدول باید با قالب‌بندی خاص رسم شود. خواندن/نوشتن Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است را برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی خط ندارند می‌تواند مقدار null بازگرداند. فقط‌خواندنی [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند. باید خالی نباشد. در صورت لزوم از رشته خالی استفاده کنید. خواندن/نوشتن String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | شناسه یکتای scoped به اسلاید را برمی‌گرداند که در طول دوره حیات شکل ثابت می‌ماند و به PowerPoint یا کدهای interop امکان ارجاع قابل اطمینان به شکل از هر نقطه‌ای در سند را می‌دهد. فقط‌خواندنی UInt32. همچنین به [`UniqueId`](../shape/uniqueid) مراجعه کنید. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | اگر شکل گروه‌بندی شده باشد، شیء GroupShape والد را برمی‌گرداند. در غیر این صورت null برمی‌گرداند. فقط‌خواندنی [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | محافظ مکان (placeholder) یک شکل را برمی‌گرداند. اگر شکل هیچ placeholderی نداشته باشد null برمی‌گرداند. فقط‌خواندنی [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائه (presentation) والد اسلاید را برمی‌گرداند. فقط‌خواندنی [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ویژگی‌های فریم خام شکل را برمی‌گیرد یا تنظیم می‌کند. خواندن/نوشتن [`IShapeFrame`](../ishapeframe). |
| [RightToLeft](../../aspose.slides/table/righttoleft) { get; set; } | تعیین می‌کند آیا جدول ترتیب خواندن راست به چپ دارد. خواندن-نوشتن Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجه‌های چرخش شکل مشخص‌شده حول محور z را برمی‌گرداند یا تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پاد ساعت‌گرد است. خواندن/نوشتن Single. |
| [Rows](../../aspose.slides/table/rows) { get; } | کلکسیون ردیف‌ها را برمی‌گرداند. فقط‌خواندنی [`IRowCollection`](../irowcollection). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط‌خواندنی [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 ویژگی) |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد شکل را برمی‌گرداند. فقط‌خواندنی [`IBaseSlide`](../ibaseslide). |
| [StylePreset](../../aspose.slides/table/stylepreset) { get; set; } | سبک جدول پیش‌ساخته را برمی‌گیرد یا تنظیم می‌کند. خواندن/نوشتن [`TableStylePreset`](../tablestylepreset). |
| [TableFormat](../../aspose.slides/table/tableformat) { get; } | شیء TableFormat که شامل ویژگی‌های قالب‌بندی برای این جدول است را برمی‌گرداند. فقط‌خواندنی [`ITableFormat`](../itableformat). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat که ویژگی‌های اثر 3D برای یک شکل را دارد را برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی‌های 3D ندارند می‌تواند مقدار null بازگرداند. فقط‌خواندنی [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | شناسه داخلی scoped به ارائه که برای استفاده توسط افزونه‌ها یا کدهای دیگر در نظر گرفته شده است را برمی‌گرداند. از آنجا که این مقدار می‌تواند توسط کاربر یا برنامه‌نویسی دوباره اختصاص داده شود، نباید به‌عنوان کلید یکتای دائمی در نظر گرفته شود. فقط‌خواندنی UInt32. همچنین به [`OfficeInteropShapeId`](../shape/officeinteropshapeid) مراجعه کنید. |
| [VerticalBanding](../../aspose.slides/table/verticalbanding) { get; set; } | تعیین می‌کند آیا ستون‌های زوج باید با قالب‌بندی متفاوت رسم شوند. خواندن/نوشتن Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض شکل را که برحسب پوینت اندازه‌گیری شده، برمی‌گیرد یا تنظیم می‌کند. خواندن/نوشتن Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات X گوشه بالا-چپ شکل که برحسب پوینت اندازه‌گیری شده را برمی‌گیرد یا تنظیم می‌کند. خواندن/نوشتن Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات Y گوشه بالا-چپ شکل که برحسب پوینت اندازه‌گیری شده را برمی‌گیرد یا تنظیم می‌کند. خواندن/نوشتن Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل در انتهای پشت ترتیب z را برمی‌گرداند و Shapes[Shapes.Count - 1] شکل در جلوی ترتیب z را برمی‌گرداند. فقط‌خواندنی Int32. |

## متدها

| نام | توضیحات |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | اگر placeholderی وجود نداشته باشد، یک placeholder جدید اضافه می‌کند و ویژگی‌های placeholder را به مورد مشخص تنظیم می‌کند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک شکل placeholder پایه را برمی‌گرداند (شکل از طرح‌بندی و/یا اسلاید اصلی که شکل فعلی از آن به ارث برده شده است). اگر شکل فعلی به ارث نبرده باشد، مقدار null برگردانده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)() | تصویر کوچک شکل را برمی‌گرداند. به‌طور پیش‌فرض نوع ShapeThumbnailBounds.Shape برای حدود تصویر کوچک استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تصویر کوچک شکل را برمی‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | حدود بصری شکل را که از محتوای رندر شده محاسبه می‌شود، به‌دست می‌آورد. |
| [MergeCells](../../aspose.slides/table/mergecells)(ICell, ICell, bool) | سلول‌های همسایه را ادغام می‌کند. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | مشخص می‌کند که این شکل placeholder نیست. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat)(IParagraphFormat) | ویژگی‌های قالب‌بندی پاراگراف تعریف‌شده را به تمام پاراگراف‌های سلول‌های جدول اعمال می‌کند. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_1)(IPortionFormat) | ویژگی‌های قالب‌بندی بخش تعریف‌شده را به تمام بخش‌های سلول‌های جدول اعمال می‌کند. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_2)(ITextFrameFormat) | ویژگی‌های قالب‌بندی فریم متن تعریف‌شده را به تمام فریم‌های متن سلول‌های جدول اعمال می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتوای Shape را به عنوان فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | محتوای Shape را به عنوان فایل SVG ذخیره می‌کند. |

### مراجع

* کلاس [GraphicalObject](../graphicalobject)
* رابط [ITable](../itable)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مونتاژ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->