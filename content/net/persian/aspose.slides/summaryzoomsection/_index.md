---
title: SummaryZoomSection
second_title: مرجع API Aspose.Sildes برای .NET
description: شیء Summary Zoom Section را در یک چارچوب Summary Zoom نشان می‌دهد.
type: docs
weight: 10800
url: /fa/aspose.slides/summaryzoomsection/
---
## کلاس SummaryZoomSection

شیء Summary Zoom Section را در یک قاب Summary Zoom نمایش می‌دهد.

```csharp
public class SummaryZoomSection : SectionZoomFrame, ISummaryZoomSection
```

## ویژگی‌ها

| نام | توضیحات |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | مقدار یا تنظیم متن جایگزین مرتبط با یک شکل. خواندنی/قابل نوشتن String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | مقدار یا تنظیم عنوان متن جایگزین مرتبط با یک شکل. خواندنی/قابل نوشتن String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه-سفید رندر خواهد شد. خواندنی/قابل نوشتن [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال روی شکل را برمی‌گرداند. فقط-خواندنی Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی شکل را برمی‌گرداند. فقط-خواندنی [`ICustomData`](../icustomdata). |
| [Description](../../aspose.slides/summaryzoomsection/description) { get; set; } | توضیح متنی شیء Summary Zoom Section را برمی‌گرداند. |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat را که شامل افکت‌های پیکسل اعمال‌شده به یک شکل است برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی افکت ندارند می‌تواند null برگرداند. فقط-خواندنی [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شیء FillFormat را که شامل ویژگی‌های قالب‌بندی پر کردن برای یک شکل است برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی پر کردن ندارند می‌تواند null برگرداند. فقط-خواندنی [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ویژگی‌های فریم شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط-خواندنی [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع شکل را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | مشخص می‌کند که آیا شکل مخفی است یا نه. خواندنی/قابل نوشتن Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | لینک‌فشاری که برای کلیک ماوس تعریف شده را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیرهای لینک‌فشاری را برمی‌گرداند. فقط-خواندنی [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | لینک‌فشاری که برای حرکت ماوس بر روی آن تعریف شده را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | نوع تصویر یک شیء زوم را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن [`ZoomImageType`](../zoomimagetype). مقدار پیش‌فرض: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | دریافت یا تنظیم گزینه 'Mark as decorative'. خواندنی/قابل نوشتن Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | مشخص می‌کند که آیا شکل گروه‌بندی شده است یا نه. فقط-خواندنی Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | مشخص می‌کند که آیا شکل TextHolder_PPT است یا نه. فقط-خواندنی Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat را که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی خط ندارند می‌تواند null برگرداند. فقط-خواندنی [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند. نباید null باشد. در صورت نیاز از مقدار رشتهٔ خالی استفاده کنید. خواندنی/قابل نوشتن String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | یک شناسهٔ یکتا در محدودهٔ اسلاید که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop اجازه می‌دهد تا شکل را به‌صورت قابل اطمینان از هرجایی در سند ارجاع دهند، برمی‌گرداند. فقط-خواندنی UInt32. همچنین به [`UniqueId`](../shape/uniqueid) مراجعه کنید. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | اگر شکل گروه‌بندی شده باشد، شیء GroupShape والد را برمی‌گرداند. در غیر اینصورت null برمی‌گرداند. فقط-خواندنی [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | متغیر نگهدارنده (placeholder) یک شکل را برمی‌گرداند. اگر شکل هیچ placeholderی نداشته باشد null برمی‌گرداند. فقط-خواندنی [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائهٔ والد یک اسلاید را برمی‌گرداند. فقط-خواندنی [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ویژگی‌های فریم خام شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | رفتار ناوبری در نمایش اسلایدها را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن Boolean. مقدار پیش‌فرض: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجه‌ای که شکل مشخص حول محور z چرخانده می‌شود را برمی‌گرداند یا تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پاد ساعت‌گرد است. خواندنی/قابل نوشتن Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط-خواندنی [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 ویژگی) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | مقداری که مشخص می‌کند Zoom از پس‌زمینه اسلاید مقصد استفاده کند یا نه را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن Boolean. مقدار پیش‌فرض: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد یک شکل را برمی‌گرداند. فقط-خواندنی [`IBaseSlide`](../ibaseslide). |
| [TargetSection](../../aspose.slides/sectionzoomframe/targetsection) { get; set; } | شیء بخش (section) که شیء Section Zoom به آن پیوند دارد را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن [`ISection`](../isection). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat را که شامل ویژگی‌های اثر سه‌بعدی برای یک شکل است برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی 3d ندارند می‌تواند null برگرداند. فقط-خواندنی [`IThreeDFormat`](../ithreedformat). |
| [Title](../../aspose.slides/summaryzoomsection/title) { get; set; } | عنوان متنی شیء Summary Zoom Section را برمی‌گرداند. |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | مدت زمان انتقال بین Zoom و اسلاید را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن Single. مقدار پیش‌فرض: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | یک شناسهٔ داخلی در محدودهٔ ارائه که برای استفاده توسط افزونه‌ها یا کدهای دیگر هدف‌گذاری شده است را برمی‌گرداند. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویسی دوباره تخصیص یابد، نباید به‌عنوان کلید یکتای دائم در نظر گرفته شود. فقط-خواندنی UInt32. همچنین به [`OfficeInteropShapeId`](../shape/officeinteropshapeid) مراجعه کنید. |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض شکل را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشهٔ بالایی سمت چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشهٔ بالایی سمت چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | تصویر برای شیء زوم را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل در پایین‌ترین ترتیب z را برمی‌گرداند و Shapes[Shapes.Count - 1] شکل در بالاترین ترتیب z را برمی‌گرداند. فقط-خواندنی Int32. |

## متدها

| نام | توضیحات |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | یک placeholder جدید اضافه می‌کند اگر وجود نداشته باشد و ویژگی‌های placeholder را به مورد مشخص تنظیم می‌کند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک شکل placeholder پایه برمی‌گرداند (شکل از چیدمان و/یا اسلاید اصلی که شکل فعلی از آن ارث‌بر گرفته است). اگر شکل فعلی ارث‌بر گرفته نشده باشد null برمی‌گرداند. |
| [GetImage](../../aspose.slides/shape/getimage)() | تصویر کوچک شکل را برمی‌گرداند. به‌صورت پیش‌فرض نوع ShapeThumbnailBounds.Shape برای محدودهٔ تصویر کوچک استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تصویر کوچک شکل را برمی‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | حدود بصری شکل را که از محتوای رندر شده آن محاسبه می‌شود، برمی‌گرداند. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | تعریف می‌کند که این شکل placeholder نیست. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتویات Shape را به‌عنوان فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | محتویات Shape را به‌عنوان فایل SVG ذخیره می‌کند. |

### موارد مرتبط

* کلاس [SectionZoomFrame](../sectionzoomframe)
* رابط [ISummaryZoomSection](../isummaryzoomsection)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->