---
title: GraphicalObject
second_title: Aspose.Sildes برای مرجع API .NET
description: یک شیء گرافیکی انتزاعی را نشان می‌دهد.
type: docs
weight: 5070
url: /fa/aspose.slides/graphicalobject/
---
## کلاس GraphicalObject

یک شیء گرافیکی انتزاعی را نمایش می‌دهد.

```csharp
public class GraphicalObject : Shape, IGraphicalObject
```

## خصوصیات

| نام | توضیح |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | مقدار یا تنظیم متن جایگزین مرتبط با یک شکل. قابل خواندن/نوشتن String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | مقدار یا تنظیم عنوان متن جایگزین مرتبط با یک شکل. قابل خواندن/نوشتن String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | این ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه و سفید رندر خواهد شد. قابل خواندن/نوشتن [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال در شکل را برمی‌گرداند. فقط خواندنی Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی شکل را برمی‌گرداند. فقط خواندنی [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat را برمی‌گرداند که شامل افکت‌های پیکسلی اعمال‌شده به یک شکل است. نکته: برای برخی انواع شکل‌ها که ویژگی‌های افکت ندارند ممکن است مقدار null برگرداند. فقط خواندنی [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شیء FillFormat را برمی‌گرداند که شامل ویژگی‌های قالب‌بندی پرکننده برای یک شکل است. نکته: برای برخی انواع شکل‌ها که ویژگی پرکننده ندارند ممکن است مقدار null برگرداند. فقط خواندنی [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ویژگی‌های قاب شکل را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط خواندنی [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع شکل را بر می‌گیرد یا تنظیم می‌کند، به واحد نقطه اندازه‌گیری می‌شود. قابل خواندن/نوشتن Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | مشخص می‌کند آیا شکل مخفی است یا نه. قابل خواندن/نوشتن Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | لینک ابرمتنی تعریف‌شده برای کلیک ماوس را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر لینک ابرمتنی را برمی‌گرداند. فقط خواندنی [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | لینک ابرمتنی تعریف‌شده برای حرکت ماوس روی شی را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | دریافت یا تنظیم گزینه 'علامت به عنوان تزئینی'. قابل خواندن/نوشتن Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | مشخص می‌کند آیا شکل گروه‌بندی شده است یا نه. فقط خواندنی Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | مشخص می‌کند آیا شکل TextHolder_PPT است یا نه. فقط خواندنی Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat را برمی‌گرداند که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است. نکته: برای برخی انواع شکل‌ها که ویژگی خط ندارند ممکن است مقدار null برگرداند. فقط خواندنی [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند. نباید مقدار null داشته باشد. در صورت ضرورت از رشته خالی استفاده کنید. قابل خواندن/نوشتن String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | یک شناسهٔ یکتا مربوط به اسلاید را برمی‌گرداند که در طول عمر شکل ثابت می‌ماند و به پاورپوینت یا کد اینترآپ اجازه می‌دهد به‌صورت قابل اعتماد از هر نقطه‌ای در سند به شکل مراجعه کند. فقط خواندنی UInt32. همچنین ببینید [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | شیء GroupShape والد را برمی‌گرداند اگر شکل گروه‌بندی شده باشد. در غیر این صورت مقدار null برمی‌گرداند. فقط خواندنی [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | متغیر placeholder برای یک شکل را برمی‌گرداند. اگر شکل placeholder نداشته باشد مقدار null برمی‌گرداند. فقط خواندنی [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائه (presentation) والد اسلاید را برمی‌گرداند. فقط خواندنی [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ویژگی‌های اصلی قاب شکل را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجه‌های چرخش شکل مشخص‌شده حول محور z را برمی‌گرداند یا تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعتگرد؛ مقدار منفی نشان‌دهنده چرخش پادساعتگرد است. قابل خواندن/نوشتن Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط خواندنی [`IGraphicalObjectLock`](../igraphicalobjectlock). (۲ ویژگی) |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد یک شکل را برمی‌گرداند. فقط خواندنی [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat را برمی‌گرداند که شامل ویژگی‌های اثر ۳بعدی برای یک شکل است. نکته: برای برخی انواع شکل‌ها که ویژگی‌های ۳بعدی ندارند ممکن است مقدار null برگرداند. فقط خواندنی [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | یک شناسهٔ داخلی مربوط به ارائه را برمی‌گرداند که برای استفاده توسط افزونه‌ها یا کدهای دیگر در نظر گرفته شده است. از آنجا که این مقدار می‌تواند توسط کاربر یا برنامه‌نویس دوباره اختصاص داده شود، نباید به‌عنوان کلید یکتا ثابت در نظر گرفته شود. فقط خواندنی UInt32. همچنین ببینید [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض شکل را بر می‌گیرد یا تنظیم می‌کند، به نقطه اندازه‌گیری می‌شود. قابل خواندن/نوشتن Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشهٔ فوق‌چپ شکل را بر می‌گیرد یا تنظیم می‌کند، به نقطه اندازه‌گیری می‌شود. قابل خواندن/نوشتن Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشهٔ فوق‌چپ شکل را بر می‌گیرد یا تنظیم می‌کند، به نقطه اندازه‌گیری می‌شود. قابل خواندن/نوشتن Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل در پشت‌ترین موقعیت z را برمی‌گرداند و Shapes[Shapes.Count - 1] شکل در جلوی‌ترین موقعیت z را برمی‌گرداند. فقط خواندنی Int32. |

## متدها

| نام | توضیح |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | در صورت عدم وجود، یک placeholder جدید اضافه می‌کند و ویژگی‌های placeholder را به مقدار مشخصی تنظیم می‌کند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک شکل placeholder پایه را برمی‌گرداند (شکل از قالب و/یا اسلاید اصلی که شکل فعلی از آن ارث برده است). اگر شکل فعلی ارث‌بری نداشته باشد مقدار null برگردانده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)() | تصویر بندانگشتی شکل را برمی‌گرداند. به‌طور پیش‌فرض نوع ShapeThumbnailBounds.Shape برای مرزهای تصویر بندانگشتی استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تصویر بندانگشتی شکل را برمی‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | مرزهای بصری شکل را که از محتویات رندر شده محاسبه می‌شود، برمی‌گرداند. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | تعریف می‌کند که این شکل placeholder نیست. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتویات Shape را به عنوان فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | محتویات Shape را به عنوان فایل SVG ذخیره می‌کند. |

### موارد مرتبط

* کلاس [Shape](../shape)
* رابط [IGraphicalObject](../igraphicalobject)
* فضای نام [Aspose.Slides](../../aspose.slides)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->