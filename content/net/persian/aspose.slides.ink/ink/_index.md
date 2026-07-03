---
title: Ink
second_title: Aspose.Sildes برای .NET مرجع API
description: یک شیء جوهر را بر روی یک اسلاید نشان می‌دهد.
type: docs
weight: 7550
url: /fa/aspose.slides.ink/ink/
---
## کلاس Ink

یک شیء جوهر را بر روی یک اسلاید نشان می‌دهد.

```csharp
public class Ink : GraphicalObject, IInk
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | این ویژگی مشخص می‌کند که یک شکل در حالت نمایش سیاه-سفید چگونه رندر می‌شود. قابل خواندن/نوشتن [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال در شکل را برمی‌گرداند. فقط خواندنی Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی شکل را برمی‌گرداند. فقط خواندنی [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat را که شامل اثرات پیکسلی اعمال شده به یک شکل است برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی اثر ندارند، می‌تواند مقدار null برگرداند. فقط خواندنی [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شیء FillFormat را که شامل ویژگی‌های قالب‌بندی پر برای یک شکل است برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی پر ندارند، می‌تواند مقدار null برگرداند. فقط خواندنی [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ویژگی‌های فریم شکل را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط خواندنی [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع شکل را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | مشخص می‌کند که آیا شکل مخفی است یا نه. قابل خواندن/نوشتن Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | پیوند فراموشی تعریف‌شده برای کلیک موس را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر پیوند فراموشی را برمی‌گرداند. فقط خواندنی [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | پیوند فراموشی تعریف‌شده برای عبور موس را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه «علامت به‌عنوان تزئینی» را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | تعیین می‌کند که آیا شکل گروهبندی شده است یا نه. فقط خواندنی Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | تعیین می‌کند که آیا شکل TextHolder_PPT است یا نه. فقط خواندنی Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat را که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی خط ندارند، می‌تواند مقدار null برگرداند. فقط خواندنی [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند. نباید null باشد. در صورت نیاز می‌توانید مقدار رشته خالی را استفاده کنید. قابل خواندن/نوشتن String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | یک شناسه یکتای محدوده اسلاید را که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop امکان ارجاع قابل اعتماد به شکل از هر نقطه‌ای در سند را می‌دهد، برمی‌گرداند. فقط خواندنی UInt32. همچنین ببینید [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | اگر شکل گروهبندی شده باشد شیء GroupShape والد را برمی‌گرداند. در غیر این صورت مقدار null را برمی‌گرداند. فقط خواندنی [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | پلان‌هولدر یک شکل را برمی‌گرداند. اگر شکل پلان‌هولدر نداشته باشد مقدار null را برمی‌گرداند. فقط خواندنی [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائه مادر یک اسلاید را برمی‌گرداند. فقط خواندنی [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ویژگی‌های فریم خام شکل را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجه‌هایی که شکل مشخص حول محور z چرخیده است را برمی‌گرداند یا تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پاد ساعت‌گرد است. قابل خواندن/نوشتن Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط خواندنی [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (۲ ویژگی) |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد یک شکل را برمی‌گرداند. فقط خواندنی [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat را که شامل ویژگی‌های اثر 3D برای یک شکل است برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی 3D ندارند، می‌تواند مقدار null برگرداند. فقط خواندنی [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Traces](../../aspose.slides.ink/ink/traces) { get; } | همه ردهای موجود در عنصر IInk [`IInkTrace`](../iinktrace) را برمی‌گرداند. فقط خواندنی. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | یک شناسه داخلی محدوده ارائه که برای استفاده افزونه‌ها یا کدهای دیگر در نظر گرفته شده است برمی‌گرداند. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویس مجدداً مقداردهی شود، نباید به عنوان کلید یکتا دائمی در نظر گرفته شود. فقط خواندنی UInt32. همچنین ببینید [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض شکل را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشه فوقانی چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشه فوقانی چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک شکل در ترتیب Z را برمی‌گرداند. Shapes[0] شکل در انتهای عقب ترتیب Z را برمی‌گرداند و Shapes[Shapes.Count - 1] شکل در جلوترین ترتیب Z را برمی‌گرداند. فقط خواندنی Int32. |
| static [InkEffectImages](../../aspose.slides.ink/ink/inkeffectimages) { get; } | مجموعه‌ای از تصاویر سفارشی که برای شبیه‌سازی اثرات بصری براش‌های جوهر استفاده می‌شود را برمی‌گرداند. این تصاویر هنگام رندرینگ جوهر با مقادیر خاص [`InkEffectType`](../inkeffecttype)، مانند Galaxy، Rainbow و غیره استفاده می‌شوند. با ارائه تصاویر خود می‌توانید کنترل کنید که هر اثر جوهر چگونه ظاهر می‌شود. |

## متدها

| نام | توضیح |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | اگر موجود نباشد، یک پلان‌هولدر جدید اضافه می‌کند و ویژگی‌های پلان‌هولدر را به مورد مشخص شده تنظیم می‌کند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک شکل پلان‌هولدر پایه را برمی‌گرداند (شکلی از لایه یا اسلاید اصلی که شکل فعلی از آن به ارث برده شده است). اگر شکل فعلی به ارث نرسیده باشد، مقدار null برگردانده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)() | تصویر بندانگشتی شکل را برمی‌گرداند. نوع ShapeThumbnailBounds.Shape به صورت پیش‌فرض استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تصویر بندانگشتی شکل را برمی‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | مرزهای بصری شکل را که از محتوای رندر شده محاسبه می‌شود، برمی‌گرداند. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | تعریف می‌کند که این شکل پلان‌هولدر نیست. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتوای Shape را به صورت فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | محتوای Shape را به صورت فایل SVG ذخیره می‌کند. |

### موارد مرتبط

* کلاس [GraphicalObject](../../aspose.slides/graphicalobject)
* رابط [IInk](../iink)
* فضای نام [Aspose.Slides.Ink](../../aspose.slides.ink)
* مونتاژ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->