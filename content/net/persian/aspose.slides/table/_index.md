---
title: Table
second_title: Aspose.Sildes برای .NET مرجع API
description: نمایانگر یک جدول بر روی اسلاید است.
type: docs
weight: 10880
url: /fa/aspose.slides/table/
---
## کلاس Table

نمایش یک جدول در یک اسلاید.

```csharp
public sealed class Table : GraphicalObject, ITable
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | این ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه‌وسفید رندر می‌شود. خواندنی/نوشتنی [`BlackWhiteMode`](../blackwhitemode). |
| [Columns](../../aspose.slides/table/columns) { get; } | مجموعه ستون‌ها را برمی‌گرداند. فقط-خواندنی [`IColumnCollection`](../icolumncollection). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال روی شکل را برمی‌گرداند. فقط-خواندنی Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی شکل را برمی‌گرداند. فقط-خواندنی [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat را که شامل اثرات پیکسلی اعمال‌شده به یک شکل است برمی‌گرداند. نکته: ممکن است برای برخی انواع شکل‌ها که ویژگی اثر ندارند مقدار null برگرداند. فقط-خواندنی [`IEffectFormat`](../ieffectformat). |
| override [FillFormat](../../aspose.slides/table/fillformat) { get; } | شیء TableFormat.FillFormat را که شامل قالب‌بندی پر کردن برای Table است برمی‌گرداند. فقط-خواندنی [`IFillFormat`](../ifillformat). |
| [FirstCol](../../aspose.slides/table/firstcol) { get; set; } | تعیین می‌کند که آیا ستون اول جدول باید با قالب‌بندی ویژه‌ای رسم شود. خواندنی/نوشتنی Boolean. |
| [FirstRow](../../aspose.slides/table/firstrow) { get; set; } | تعیین می‌کند که آیا ردیف اول جدول باید با قالب‌بندی ویژه‌ای رسم شود. خواندنی/نوشتنی Boolean. |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ویژگی‌های فریم شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط-خواندنی [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | تعیین می‌کند که آیا شکل مخفی است. خواندنی/نوشتنی Boolean. |
| [HorizontalBanding](../../aspose.slides/table/horizontalbanding) { get; set; } | تعیین می‌کند که آیا ردیف‌های زوج باید با قالب‌بندی متفاوتی رسم شوند. خواندنی/نوشتنی Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | پیوندی که برای کلیک ماوس تعریف شده است را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر پیوند را برمی‌گرداند. فقط-خواندنی [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | پیوندی که برای عبور ماوس تعریف شده است را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه «Mark as decorative» را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | تعیین می‌کند که آیا شکل گروه‌بندی شده است. فقط-خواندنی Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | تعیین می‌کند که آیا شکل TextHolder_PPT است. فقط-خواندنی Boolean. |
| [Item](../../aspose.slides/table/item) { get; } | سلول در ایندکس‌های ستون و ردیف مشخص‌شده را برمی‌گرداند. فقط-خواندنی [`Cell`](../cell). |
| [LastCol](../../aspose.slides/table/lastcol) { get; set; } | تعیین می‌کند که آیا ستون آخر جدول باید با قالب‌بندی ویژه‌ای رسم شود. خواندنی/نوشتنی Boolean. |
| [LastRow](../../aspose.slides/table/lastrow) { get; set; } | تعیین می‌کند که آیا ردیف آخر جدول باید با قالب‌بندی ویژه‌ای رسم شود. خواندنی/نوشتنی Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat را که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است برمی‌گرداند. نکته: ممکن است برای برخی انواع شکل‌ها که خصوصیات خط ندارند مقدار null برگرداند. فقط-خواندنی [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند. باید مقدار null نداشته باشد. در صورت نیاز از رشته خالی استفاده کنید. خواندنی/نوشتنی String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | شناساگر یکتا با محدوده اسلاید که برای تمام طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop اجازه می‌دهد شکل را از هر جایی در سند به‌درستی ارجاع دهند، را برمی‌گرداند. فقط-خواندنی UInt32. همچنین ببینید [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | اگر شکل گروه‌بندی شده باشد، شیء GroupShape والد را برمی‌گرداند. در غیر این صورت مقدار null برمی‌گرداند. فقط-خواندنی [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | متغیر placeholder برای یک شکل را برمی‌گرداند. اگر شکل placeholder نداشته باشد مقدار null برمی‌گرداند. فقط-خواندنی [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائه (presentation) والد اسلاید را برمی‌گرداند. فقط-خواندنی [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ویژگی‌های فریم خام شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IShapeFrame`](../ishapeframe). |
| [RightToLeft](../../aspose.slides/table/righttoleft) { get; set; } | تعیین می‌کند که آیا جدول ترتیب خواندن راست به چپ دارد. خواندنی/نوشتنی Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجه‌های چرخش شکل مشخص‌شده حول محور z را برمی‌گرداند یا تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پاد ساعت‌گرد است. خواندنی/نوشتنی Single. |
| [Rows](../../aspose.slides/table/rows) { get; } | مجموعه ردیف‌ها را برمی‌گرداند. فقط-خواندنی [`IRowCollection`](../irowcollection). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط-خواندنی [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 خصوصیت) |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد یک شکل را برمی‌گرداند. فقط-خواندنی [`IBaseSlide`](../ibaseslide). |
| [StylePreset](../../aspose.slides/table/stylepreset) { get; set; } | سبک جدول داخلی را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`TableStylePreset`](../tablestylepreset). |
| [TableFormat](../../aspose.slides/table/tableformat) { get; } | شیء TableFormat را که شامل ویژگی‌های قالب‌بندی برای این جدول است برمی‌گرداند. فقط-خواندنی [`ITableFormat`](../itableformat). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat را که شامل ویژگی‌های اثر 3D برای یک شکل است برمی‌گرداند. نکته: ممکن است برای برخی انواع شکل‌ها که خصوصیات 3D ندارند مقدار null برگرداند. فقط-خواندنی [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | شناساگر داخلی با محدوده ارائه که برای استفاده افزونه‌ها یا کدهای دیگر در نظر گرفته شده است را برمی‌گرداند. از آنجا که این مقدار می‌تواند توسط کاربر یا به‌صورت برنامه‌نویسی تغییر یابد، نباید به‌عنوان کلید یکتا پایدار در نظر گرفته شود. فقط-خواندنی UInt32. همچنین ببینید [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [VerticalBanding](../../aspose.slides/table/verticalbanding) { get; set; } | تعیین می‌کند که آیا ستون‌های زوج باید با قالب‌بندی متفاوتی رسم شوند. خواندنی/نوشتنی Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشه بالا-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشه بالا-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل در انتهای پشت ترتیب z را برمی‌گرداند و Shapes[Shapes.Count - 1] شکل در جلوترین ترتیب z را برمی‌گرداند. فقط-خواندنی Int32. |

## متدها

| نام | توضیح |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | اگر placeholder‌ای وجود نداشته باشد، یک placeholder جدید اضافه می‌کند و ویژگی‌های placeholder را به مورد مشخص شده تنظیم می‌کند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک شکل placeholder پایه (شکلی از طرح‌بندی و/یا اسلاید اصلی که شکل فعلی از آن ارث‌بری می‌کند) را برمی‌گرداند. اگر شکل فعلی ارث‌بری نشده باشد مقدار null برگردانده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)() | تصویر کوچک (thumbnail) شکل را برمی‌گرداند. به‌صورت پیش‌فرض نوع ShapeThumbnailBounds.Shape برای حدود تصویر کوچک استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تصویر کوچک شکل را برمی‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | حدود بصری شکل را که از محتوای رندر شده محاسبه می‌شود، برمی‌گرداند. |
| [MergeCells](../../aspose.slides/table/mergecells)(ICell, ICell, bool) | سلول‌های همسایه را ادغام می‌کند. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | مشخص می‌کند که این شکل یک placeholder نیست. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat)(IParagraphFormat) | ویژگی‌های قالب‌بندی پاراگراف تعریف‌شده را برای تمام پاراگراف‌های سلول‌های جدول تنظیم می‌کند. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_1)(IPortionFormat) | ویژگی‌های قالب‌بندی بخش تعریف‌شده را برای تمام بخش‌های سلول‌های جدول تنظیم می‌کند. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_2)(ITextFrameFormat) | ویژگی‌های قالب‌بندی فریم متن تعریف‌شده را برای تمام فریم‌های متن سلول‌های جدول تنظیم می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتوای Shape را به‌عنوان فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | محتوای Shape را به‌عنوان فایل SVG ذخیره می‌کند. |

### همچنین

* کلاس [GraphicalObject](../graphicalobject)
* رابط [ITable](../itable)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->