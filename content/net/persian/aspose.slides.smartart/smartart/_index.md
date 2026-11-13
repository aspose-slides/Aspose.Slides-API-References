---
title: SmartArt
second_title: Aspose.Sildes برای .NET مرجع API
description: نمایانگر یک نمودار SmartArt
type: docs
weight: 10620
url: /fa/aspose.slides.smartart/smartart/
---
## کلاس SmartArt

نمایانگر یک نمودار SmartArt

```csharp
public class SmartArt : GraphicalObject, ISmartArt
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [AllNodes](../../aspose.slides.smartart/smartart/allnodes) { get; } | مجموعه‌ای از تمام گره‌ها در شیء SmartArt را برمی‌گرداند. فقط‌خواندنی [`ISmartArtNodeCollection`](../ismartartnodecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | این ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه‌وسفید رندر می‌شود. قابل‌خواندن/قابل‌نوشتن [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ColorStyle](../../aspose.slides.smartart/smartart/colorstyle) { get; set; } | سبک رنگی شیء SmartArt را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [`SmartArtColorType`](../smartartcolortype). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال روی شکل را برمی‌گرداند. فقط‌خواندنی Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی شکل را برمی‌گرداند. فقط‌خواندنی [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat را برمی‌گرداند که شامل افکت‌های پیکسل اعمال شده به یک شکل است. توجه: برای برخی انواع شکل‌ها که خصوصیات افکت ندارند می‌تواند null برگرداند. فقط‌خواندنی [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شیء FillFormat را برمی‌گرداند که شامل خصوصیات قالب‌بندی پر برای یک شکل است. توجه: برای برخی انواع شکل‌ها که خصوصیات پر ندارند می‌تواند null برگرداند. فقط‌خواندنی [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | خصوصیات قاب شکل را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط‌خواندنی [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع شکل را برمی‌گرداند یا تنظیم می‌کند، به پوینت اندازه‌گیری می‌شود. قابل‌خواندن/قابل‌نوشتن Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | تعیین می‌کند آیا شکل مخفی است یا خیر. قابل‌خواندن/قابل‌نوشتن Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | پیوندهای فراگیر تعریف‌شده برای کلیک ماوس را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر پیوندهای فراگیر را برمی‌گرداند. فقط‌خواندنی [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | پیوندهای فراگیر تعریف‌شده برای مرور ماوس را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه 'علامت‌گذاری به‌عنوان تزئینی' را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | تعیین می‌کند آیا شکل گروه‌بندی شده است یا خیر. فقط‌خواندنی Boolean. |
| [IsReversed](../../aspose.slides.smartart/smartart/isreversed) { get; set; } | وضعیت نمودار SmartArt را نسبت به (چپ به راست) LTR یا (راست به چپ) RTL برمی‌گرداند یا تنظیم می‌کند، در صورتیکه نمودار از معکوس شدن پشتیبانی کند. قابل‌خواندن/قابل‌نوشتن Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | تعیین می‌کند آیا شکل TextHolder_PPT است یا خیر. فقط‌خواندنی Boolean. |
| [Layout](../../aspose.slides.smartart/smartart/layout) { get; set; } | چیدمان شیء SmartArt را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [`SmartArtLayoutType`](../smartartlayouttype). |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat را برمی‌گرداند که شامل خصوصیات قالب‌بندی خط برای یک شکل است. توجه: برای برخی انواع شکل‌ها که خصوصیات خط ندارند می‌تواند null برگرداند. فقط‌خواندنی [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند. نباید خالی (null) باشد. در صورت نیاز مقدار رشته خالی استفاده کنید. قابل‌خواندن/قابل‌نوشتن String. |
| [Nodes](../../aspose.slides.smartart/smartart/nodes) { get; } | مجموعه‌ای از گره‌های ریشه در شیء SmartArt را برمی‌گرداند. فقط‌خواندنی [`ISmartArtNodeCollection`](../ismartartnodecollection). |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | شناسه‌ی یکتا scoped به اسلاید را برمی‌گرداند که در طول عمر شکل ثابت می‌ماند و به PowerPoint یا کد interop اجازه می‌دهد تا به‌طور قابل اعتماد از هر نقطه‌ای در سند به شکل ارجاع دهد. فقط‌خواندنی UInt32. همچنین ببینید [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | در صورت گروه‌بندی شده بودن شکل، شیء GroupShape والد را برمی‌گرداند. در غیر این صورت null برمی‌گرداند. فقط‌خواندنی [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | محتواى placeholder برای یک شکل را برمی‌گرداند. اگر شکل هیچ placeholder نداشته باشد null برمی‌گرداند. فقط‌خواندنی [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائه (presentation) والد اسلاید را برمی‌گرداند. فقط‌خواندنی [`IPresentation`](../../aspose.slides/ipresentation). |
| [QuickStyle](../../aspose.slides.smartart/smartart/quickstyle) { get; set; } | سبک سریع شیء SmartArt را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [`SmartArtQuickStyleType`](../smartartquickstyletype). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | خصوصیات خام قاب شکل را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجه‌های چرخش شکل مشخص‌شده حول محور z را برمی‌گرداند یا تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پادساعت‌گرد است. قابل‌خواندن/قابل‌نوشتن Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط‌خواندنی [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (۲ ویژگی) |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد یک شکل را برمی‌گرداند. فقط‌خواندنی [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat را برمی‌گرداند که شامل خصوصیات افکت ۳‌بعدی برای یک شکل است. توجه: برای برخی انواع شکل‌ها که خصوصیات ۳‌بعدی ندارند می‌تواند null برگرداند. فقط‌خواندنی [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | شناسه داخلی scoped به ارائه (presentation) که برای استفاده افزونه‌ها یا کدهای دیگر هدف‌گذاری شده است، برمی‌گرداند. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویس تغییر یابد، نباید به عنوان کلید یکتا دائمی در نظر گرفته شود. فقط‌خواندنی UInt32. همچنین ببینید [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض شکل را برمی‌گرداند یا تنظیم می‌کند، به پوینت اندازه‌گیری می‌شود. قابل‌خواندن/قابل‌نوشتن Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشه بالایی سمت چپ شکل را برمی‌گرداند یا تنظیم می‌کند، به پوینت اندازه‌گیری می‌شود. قابل‌خواندن/قابل‌نوشتن Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشه بالایی سمت چپ شکل را برمی‌گرداند یا تنظیم می‌کند، به پوینت اندازه‌گیری می‌شود. قابل‌خواندن/قابل‌نوشتن Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل در پشت‌ترین موقعیت z را برمی‌گرداند، و Shapes[Shapes.Count - 1] شکل در جلوی ترین موقعیت z را برمی‌گرداند. فقط‌خواندنی Int32. |

## متدها

| نام | توضیح |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | اگر placeholder ای وجود نداشته باشد یک placeholder جدید اضافه می‌کند و خصوصیات placeholder را به مقدار مشخص‌شده تنظیم می‌کند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک شکل placeholder پایه را برمی‌گرداند (شکل از طرح‌بندی و/یا اسلاید اصلی که شکل فعلی از آن ارث‌بری می‌کند). اگر شکل فعلی ارث‌بری نشده باشد null برمی‌گرداند. |
| [GetImage](../../aspose.slides/shape/getimage)() | تصویر کوچک (thumbnail) شکل را برمی‌گرداند. نوع ShapeThumbnailBounds.Shape به‌صورت پیش‌فرض استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تصویر کوچک شکل را برمی‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | محدوده بصری شکل که از محتوای رندر شده محاسبه می‌شود را برمی‌گرداند. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | تعریف می‌کند که این شکل placeholder نیست. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتوای Shape را به‌صورت فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | محتوای Shape را به‌صورت فایل SVG ذخیره می‌کند. |

### همچنین ببینید

* کلاس [GraphicalObject](../../aspose.slides/graphicalobject)
* رابط [ISmartArt](../ismartart)
* فضای نام [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* مجتمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->