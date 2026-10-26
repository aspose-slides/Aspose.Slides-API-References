---
title: Table
second_title: Aspose.Sildes برای .NET مرجع API
description: یک جدول را در اسلاید نشان می‌دهد.
type: docs
weight: 10860
url: /fa/aspose.slides/table/
---
## Table کلاس

یک جدول را در یک اسلاید نشان می‌دهد.

```csharp
public sealed class Table : GraphicalObject, ITable
```

## خصوصیات

| نام | توضیحات |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | متن جایگزین مرتبط با یک شکل را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | عنوان متن جایگزین مرتبط با یک شکل را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه-سفید رندر خواهد شد. قابل خواندن/قابل نوشتن [`BlackWhiteMode`](../blackwhitemode). |
| [Columns](../../aspose.slides/table/columns) { get; } | مجموعه ستون‌ها را باز می‌گرداند. فقط خواندنی [`IColumnCollection`](../icolumncollection). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال بر روی شکل را باز می‌گرداند. فقط خواندنی Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی شکل را باز می‌گرداند. فقط خواندنی [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat را که شامل افکت‌های پیکسلی اعمال شده به یک شکل است باز می‌گرداند. توجه: می‌تواند برای برخی انواع شکل‌ها که ویژگی افکت ندارند مقدار null برگرداند. فقط خواندنی [`IEffectFormat`](../ieffectformat). |
| override [FillFormat](../../aspose.slides/table/fillformat) { get; } | شیء TableFormat.FillFormat را که شامل فرمت پر کردن جدول است باز می‌گرداند. فقط خواندنی [`IFillFormat`](../ifillformat). |
| [FirstCol](../../aspose.slides/table/firstcol) { get; set; } | تعیین می‌کند که آیا ستون اول جدول باید با قالب‌بندی ویژه‌ای رسم شود یا خیر. قابل خواندن/قابل نوشتن Boolean. |
| [FirstRow](../../aspose.slides/table/firstrow) { get; set; } | تعیین می‌کند که آیا ردیف اول جدول باید با قالب‌بندی ویژه‌ای رسم شود یا خیر. قابل خواندن/قابل نوشتن Boolean. |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ویژگی‌های فریم شکل را باز می‌گیرد یا تنظیم می‌کند. قابل خواندن/قابل نوشتن [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | قفل‌های شکل را باز می‌گیرد. فقط خواندنی [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع شکل را که بر حسب نقطه اندازه‌گیری می‌شود، باز می‌گیرد یا تنظیم می‌کند. قابل خواندن/قابل نوشتن Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | تعیین می‌کند که آیا شکل مخفی است یا خیر. قابل خواندن/قابل نوشتن Boolean. |
| [HorizontalBanding](../../aspose.slides/table/horizontalbanding) { get; set; } | تعیین می‌کند که آیا ردیف‌های زوج باید با قالب‌بندی متفاوتی رسم شوند یا خیر. قابل خواندن/قابل نوشتن Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | هایپرلینک تعریف‌شده برای کلیک ماوس را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر هایپرلینک را باز می‌گرداند. فقط خواندنی [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | هایپرلینک تعریف‌شده برای حرکت ماوس روی شی را باز می‌گیرد یا تنظیم می‌کند. قابل خواندن/قابل نوشتن [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه 'Mark as decorative' را باز می‌گیرد یا تنظیم می‌کند. قابل خواندن/قابل نوشتن Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | تعیین می‌کند که آیا شکل گروه‌بندی شده است یا خیر. فقط خواندنی Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | تعیین می‌کند که آیا شکل TextHolder_PPT است یا خیر. فقط خواندنی Boolean. |
| [Item](../../aspose.slides/table/item) { get; } | سلول در ستون و ردیف مشخص‌شده را باز می‌گرداند. فقط خواندنی [`Cell`](../cell). |
| [LastCol](../../aspose.slides/table/lastcol) { get; set; } | تعیین می‌کند که آیا ستون آخر جدول باید با قالب‌بندی ویژه‌ای رسم شود یا خیر. قابل خواندن/قابل نوشتن Boolean. |
| [LastRow](../../aspose.slides/table/lastrow) { get; set; } | تعیین می‌کند که آیا ردیف آخر جدول باید با قالب‌بندی ویژه‌ای رسم شود یا خیر. قابل خواندن/قابل نوشتن Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat را که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است باز می‌گرداند. توجه: می‌تواند برای برخی انواع شکل‌ها که ویژگی خط ندارند مقدار null برگرداند. فقط خواندنی [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک شکل را باز می‌گرداند یا تنظیم می‌کند. باید مقدار null نداشته باشد. در صورت نیاز مقدار رشته خالی استفاده شود. قابل خواندن/قابل نوشتن String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | یک شناسه یکتا scoped به اسلاید را که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کد interop اجازه می‌دهد تا شکل را به‌طور قابل اعتماد از هرجا در سند ارجاع دهد، باز می‌گرداند. فقط خواندنی UInt32. همچنین به [`UniqueId`](../shape/uniqueid) مراجعه کنید. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | اگر شکل گروه‌بندی شده باشد، شیء GroupShape والد را باز می‌گرداند. در غیر این صورت null باز می‌گرداند. فقط خواندنی [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | محل نگهداری (placeholder) یک شکل را باز می‌گرداند. اگر شکل هیچ placeholder نداشته باشد null باز می‌گرداند. فقط خواندنی [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائه والد یک اسلاید را باز می‌گرداند. فقط خواندنی [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ویژگی‌های فریم شکل خام را باز می‌گیرد یا تنظیم می‌کند. قابل خواندن/قابل نوشتن [`IShapeFrame`](../ishapeframe). |
| [RightToLeft](../../aspose.slides/table/righttoleft) { get; set; } | تعیین می‌کند که آیا جدول ترتیب خواندن راست به چپ دارد یا خیر. قابل خواندن/قابل نوشتن Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجه‌هایی که شکل مشخص‌شده حول محور z چرخانده می‌شود را باز می‌گرداند یا تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد و مقدار منفی نشان‌دهنده چرخش پاد ساعت‌گرد است. قابل خواندن/قابل نوشتن Single. |
| [Rows](../../aspose.slides/table/rows) { get; } | مجموعه ردیف‌ها را باز می‌گرداند. فقط خواندنی [`IRowCollection`](../irowcollection). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | قفل‌های شکل را باز می‌گیرد. فقط خواندنی [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 ویژگی) |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد یک شکل را باز می‌گیرد. فقط خواندنی [`IBaseSlide`](../ibaseslide). |
| [StylePreset](../../aspose.slides/table/stylepreset) { get; set; } | سبک جدول داخلی را باز می‌گیرد یا تنظیم می‌کند. قابل خواندن/قابل نوشتن [`TableStylePreset`](../tablestylepreset). |
| [TableFormat](../../aspose.slides/table/tableformat) { get; } | شیء TableFormat را که شامل ویژگی‌های قالب‌بندی برای این جدول است باز می‌گرداند. فقط خواندنی [`ITableFormat`](../itableformat). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat را که شامل ویژگی‌های افکت 3D برای یک شکل است باز می‌گرداند. توجه: می‌تواند برای برخی انواع شکل‌ها که ویژگی 3D ندارند مقدار null برگرداند. فقط خواندنی [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | یک شناسه داخلی scoped به ارائه که برای استفاده توسط افزونه‌ها یا کدهای دیگر در نظر گرفته شده است، باز می‌گرداند. چون این مقدار می‌تواند توسط کاربر یا به‌صورت برنامه‌ای مجدداً اختصاص یابد، نباید به عنوان کلید یکتای دائم استفاده شود. فقط خواندنی UInt32. همچنین به [`OfficeInteropShapeId`](../shape/officeinteropshapeid) مراجعه کنید. |
| [VerticalBanding](../../aspose.slides/table/verticalbanding) { get; set; } | تعیین می‌کند که آیا ستون‌های زوج باید با قالب‌بندی متفاوتی رسم شوند یا خیر. قابل خواندن/قابل نوشتن Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض شکل را که بر حسب نقطه اندازه‌گیری می‌شود، باز می‌گیرد یا تنظیم می‌کند. قابل خواندن/قابل نوشتن Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشه بالایی-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود، باز می‌گیرد یا تنظیم می‌کند. قابل خواندن/قابل نوشتن Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشه بالایی-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود، باز می‌گیرد یا تنظیم می‌کند. قابل خواندن/قابل نوشتن Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک شکل در ترتیب z را باز می‌گرداند. Shapes[0] شکل در انتهای ترتیب z را برمی‌گرداند و Shapes[Shapes.Count - 1] شکل در جلوی ترتیب z را برمی‌گرداند. فقط خواندنی Int32. |

## متدها

| نام | توضیحات |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | اگر placeholderی وجود نداشته باشد، یک placeholder جدید اضافه می‌کند و ویژگی‌های placeholder را به مقدار مشخص شده تنظیم می‌کند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک شکل placeholder پایه را باز می‌گرداند (شکلی از طرح‌بندی و/یا اسلاید اصلی که شکل جاری از آن به ارث می‌برد). اگر شکل جاری به ارث نبرده باشد، مقدار null باز می‌گردد. |
| [GetImage](../../aspose.slides/shape/getimage)() | تصویر کوچک شکل را باز می‌گرداند. نوع ShapeThumbnailBounds.Shape به‌طور پیش‌فرض برای مرزهای تصویر کوچک استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تصویر کوچک شکل را باز می‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | مرزهای بصری شکل را که از محتوای رندرش محاسبه می‌شود، باز می‌گیرد. |
| [MergeCells](../../aspose.slides/table/mergecells)(ICell, ICell, bool) | سلول‌های همسایه را ادغام می‌کند. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | تعریف می‌کند که این شکل placeholder نیست. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat)(IParagraphFormat) | ویژگی‌های قالب‌بندی پاراگراف تعریف‌شده را برای تمام پاراگراف‌های سلول‌های جدول اعمال می‌کند. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_1)(IPortionFormat) | ویژگی‌های قالب‌بندی قسمت (portion) تعریف‌شده را برای تمام قسمت‌های سلول‌های جدول اعمال می‌کند. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_2)(ITextFrameFormat) | ویژگی‌های قالب‌بندی فریم متن تعریف‌شده را برای تمام فریم‌های متن سلول‌های جدول اعمال می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتوای Shape را به‌عنوان فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | محتوای Shape را به‌عنوان فایل SVG ذخیره می‌کند. |

### همچنین ببینید

* کلاس [GraphicalObject](../graphicalobject)
* interface [ITable](../itable)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->