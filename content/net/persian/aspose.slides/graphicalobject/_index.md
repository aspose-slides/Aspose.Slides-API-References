---
title: GraphicalObject
second_title: Aspose.Sildes برای .NET مرجع API
description: یک شیء گرافیکی انتزاعی را نشان می‌دهد.
type: docs
weight: 5070
url: /fa/aspose.slides/graphicalobject/
---
## GraphicalObject کلاس

یک شیء گرافیکی انتزاعی را نشان می‌دهد.

```csharp
public class GraphicalObject : Shape, IGraphicalObject
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | مقدار متن جایگزین مرتبط با یک شکل را باز می‌گرداند یا تنظیم می‌کند. Read/write String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | عنوان متن جایگزین مرتبط با یک شکل را باز می‌گرداند یا تنظیم می‌کند. Read/write String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | این ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه-سفید رندر می‌شود. Read/write [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال روی شکل را باز می‌گرداند. Read-only Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی شکل را باز می‌گرداند. Read-only [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat که اثرات پیکسل اعمال‌شده بر شکل را شامل می‌شود را باز می‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی اثر ندارند می‌تواند null برگرداند. Read-only [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شیء FillFormat که ویژگی‌های قالب‌بندی پرکننده برای یک شکل را شامل می‌شود را باز می‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی پرکننده ندارند می‌تواند null برگرداند. Read-only [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ویژگی‌های فریم شکل را باز می‌گرداند یا تنظیم می‌کند. Read/write [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | قفل‌های شکل را باز می‌گرداند. Read-only [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع شکل را بر حسب نقطه دریافت یا تنظیم می‌کند. Read/write Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | تعیین می‌کند که آیا شکل مخفی است یا نه. Read/write Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | پیوند فراخوانی با کلیک موس را باز می‌گرداند یا تنظیم می‌کند. Read/write [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر پیوند را باز می‌گرداند. Read-only [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | پیوند موس‌روی (hover) را باز می‌گرداند یا تنظیم می‌کند. Read/write [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه «Mark as decorative» را دریافت یا تنظیم می‌کند. Reed/write Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | تعیین می‌کند که آیا شکل در یک گروه قرار دارد یا نه. Read-only Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | تعیین می‌کند که آیا شکل TextHolder_PPT است یا نه. Read-only Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat که ویژگی‌های قالب‌بندی خط برای یک شکل را شامل می‌شود را باز می‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی خط ندارند می‌تواند null برگرداند. Read-only [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک شکل را باز می‌گرداند یا تنظیم می‌کند. مقدار نباید null باشد؛ در صورت نیاز می‌توانید مقدار رشتهٔ خالی را استفاده کنید. Read/write String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | شناسهٔ یکتای اسلاید-محور که برای طول عمر شکل ثابت می‌ماند و امکان ارجاع قابل اطمینان از هر نقطه‌ای از سند را می‌دهد را باز می‌گرداند. Read-only UInt32. برای جزئیات بیشتر به [`UniqueId`](../shape/uniqueid) مراجعه کنید. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | شیء GroupShape والد را در صورتی که شکل در یک گروه باشد باز می‌گرداند. در غیر این صورت null بر می‌گرداند. Read-only [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | جای‌دار (placeholder) شکل را باز می‌گرداند. اگر شکل جای‌دار نداشته باشد null برمی‌گردد. Read-only [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائهٔ والد اسلاید را باز می‌گرداند. Read-only [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ویژگی‌های فریم خام شکل را باز می‌گرداند یا تنظیم می‌کند. Read/write [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجاتی که شکل مشخص در اطراف محور z می‌چرخد را باز می‌گرداند یا تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد، مقدار منفی نشان‌دهنده چرخش پادساعت‌گرد است. Read/write Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | قفل‌های شکل را باز می‌گرداند. Read-only [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 ویژگی) |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد شکل را باز می‌گرداند. Read-only [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat که ویژگی‌های اثر 3-بعدی برای یک شکل را شامل می‌شود را باز می‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی 3-بعدی ندارند می‌تواند null برگرداند. Read-only [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | شناسهٔ داخلی و دامنه ارائهٔ اسلاید-محور که برای افزونه‌ها یا کدهای دیگر استفاده می‌شود را باز می‌گرداند. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویس دوباره اختصاص یابد، نباید به‌عنوان کلید یکتای ثابت در نظر گرفته شود. Read-only UInt32. برای جزئیات بیشتر به [`OfficeInteropShapeId`](../shape/officeinteropshapeid) مراجعه کنید. |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض شکل را بر حسب نقطه دریافت یا تنظیم می‌کند. Read/write Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشهٔ بالا-چپ شکل را بر حسب نقطه دریافت یا تنظیم می‌کند. Read/write Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشهٔ بالا-چپ شکل را بر حسب نقطه دریافت یا تنظیم می‌کند. Read/write Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک شکل در ترتیب z را باز می‌گرداند. Shapes[0] شکل را در پشت ترتیب z برمی‌گرداند و Shapes[Shapes.Count - 1] شکل را در جلو ترتیب z برمی‌گرداند. Read-only Int32. |

## متدها

| نام | توضیح |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | اگر جای‌دار وجود نداشته باشد، یک جای‌دار جدید اضافه می‌کند و ویژگی‌های جای‌دار را به مقدار مشخص‌شده تنظیم می‌کند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک شکل جای‌دار پایه (شکل از لایه یا اسلاید اصلی که شکل جاری از آن ارث‌بری می‌کند) را باز می‌گرداند. اگر شکل جاری ارث‌بری نشود، null برمی‌گردد. |
| [GetImage](../../aspose.slides/shape/getimage)() | تصویر کوچک شکل (thumbnail) را باز می‌گرداند. به‌طور پیش‌فرض نوع ShapeThumbnailBounds.Shape برای مرزهای تصویر کوچک استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تصویر کوچک شکل را باز می‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | مرزهای بصری شکل را که از محتوای رندر شده محاسبه می‌شود، دریافت می‌کند. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | تعریف می‌کند که این شکل یک جای‌دار نیست. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتوای Shape را به‌صورت فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | محتوای Shape را به‌صورت فایل SVG ذخیره می‌کند. |

### مراجع

* کلاس [Shape](../shape)
* رابط [IGraphicalObject](../igraphicalobject)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->