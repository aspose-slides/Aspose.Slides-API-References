---
title: SummaryZoomSection
second_title: Aspose.Sildes برای .NET مرجع API
description: شیء Summary Zoom Section را در یک فریم Summary Zoom نشان می‌دهد.
type: docs
weight: 10780
url: /fa/aspose.slides/summaryzoomsection/
---
## خلاصه‌نویسی کلاس SummaryZoomSection

نمایشی از شیء Summary Zoom Section در یک فریم Summary Zoom.

```csharp
public class SummaryZoomSection : SectionZoomFrame, ISummaryZoomSection
```

## ویژگی‌ها

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | بازگرداندن یا تنظیم متن جایگزین مرتبط با یک شکل. Read/write String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | بازگرداندن یا تنظیم عنوان متن جایگزین مرتبط با یک شکل. Read/write String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه-سفید رندر می‌شود. Read/write [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال روی شکل را باز می‌گرداند. Read-only Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی شکل را باز می‌گرداند. Read-only [`ICustomData`](../icustomdata). |
| [Description](../../aspose.slides/summaryzoomsection/description) { get; set; } | توضیح متنی شیء Summary Zoom Section را باز می‌گرداند. |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat را که شامل اثرات پیکسل اعمال شده به یک شکل است، باز می‌گرداند. توجه: برای برخی انواع شکل‌ها که خاصیت اثر ندارند ممکن است مقدار null بازگردد. Read-only [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شیء FillFormat را که شامل ویژگی‌های قالب‌بندی پر کردن برای یک شکل است، باز می‌گرداند. توجه: برای برخی انواع شکل‌ها که خاصیت پر ندارند ممکن است مقدار null بازگردد. Read-only [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ویژگی‌های فریم شکل را باز می‌گرداند یا تنظیم می‌کند. Read/write [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | قفل‌های شکل را باز می‌گرداند. Read-only [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع شکل را که بر حسب نقطه اندازه‌گیری می‌شود، دریافت یا تنظیم می‌کند. Read/write Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | تعیین می‌کند که شکل مخفی باشد یا نه. Read/write Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | پیوند یاب تعریف‌شده برای کلیک ماوس را باز می‌گرداند یا تنظیم می‌کند. Read/write [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر پیوند یاب را باز می‌گرداند. Read-only [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | پیوند یاب تعریف‌شده برای حرکت ماوس را باز می‌گرداند یا تنظیم می‌کند. Read/write [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | نوع تصویر یک شیء Zoom را دریافت یا تنظیم می‌کند. Read/write [`ZoomImageType`](../zoomimagetype). مقدار پیش‌فرض: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه «علامت‌گذاری به‌عنوان تزئینی» را دریافت یا تنظیم می‌کند. Reed/write Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | تعیین می‌کند که شکل گروه‌بندی شده باشد یا نه. Read-only Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | تعیین می‌کند که شکل TextHolder_PPT باشد یا نه. Read-only Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat را که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است، باز می‌گرداند. توجه: برای برخی انواع شکل‌ها که خاصیت خط ندارند ممکن است مقدار null بازگردد. Read-only [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک شکل را دریافت یا تنظیم می‌کند. مقدار Null مجاز نیست. در صورت نیاز می‌توانید مقدار رشتهٔ خالی استفاده کنید. Read/write String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | شناسهٔ یکتای محدوده اسلاید که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop اجازه می‌دهد به‌صورت قابل اعتماد به شکل از هر نقطه‌ای در سند ارجاع دهند. Read-only UInt32. همچنین ببینید [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | شیء Parent GroupShape را در صورت گروه‌بندی شکل باز می‌گرداند. در غیر اینصورت مقدار null باز می‌گردد. Read-only [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | مکان‌گیر (placeholder) برای یک شکل را باز می‌گرداند. اگر شکل مکان‌گیر نداشته باشد مقدار null باز می‌گردد. Read-only [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائهٔ والد اسلاید را باز می‌گرداند. Read-only [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ویژگی‌های فریم شکل خام را دریافت یا تنظیم می‌کند. Read/write [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | رفتار ناوبری در نمایش اسلاید را دریافت یا تنظیم می‌کند. Read/write Boolean. مقدار پیش‌فرض: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجاتی که شکل مشخص به‌ دور محور z می‌گردد را دریافت یا تنظیم می‌کند. مقدار مثبت نشان‌دهندهٔ چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهندهٔ چرخش پادساعت‌گرد است. Read/write Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | قفل‌های شکل را باز می‌گرداند. Read-only [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 ویژگی) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | مقدار مشخص می‌کند که Zoom از پس‌زمینه اسلاید مقصد استفاده کند یا نه. Read/write Boolean. مقدار پیش‌فرض: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد یک شکل را باز می‌گرداند. Read-only [`IBaseSlide`](../ibaseslide). |
| [TargetSection](../../aspose.slides/sectionzoomframe/targetsection) { get; set; } | شیء Section که شیء Section Zoom به آن پیوند دارد را دریافت یا تنظیم می‌کند. Read/write [`ISection`](../isection). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat را که شامل ویژگی‌های اثر سه‌بعدی برای یک شکل است، باز می‌گرداند. توجه: برای برخی انواع شکل‌ها که خاصیت سه‌بعدی ندارند ممکن است مقدار null بازگردد. Read-only [`IThreeDFormat`](../ithreedformat). |
| [Title](../../aspose.slides/summaryzoomsection/title) { get; set; } | عنوان متنی شیء Summary Zoom Section را باز می‌گرداند یا تنظیم می‌کند. |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | مدت زمان انتقال بین Zoom و اسلاید را دریافت یا تنظیم می‌کند. Read/write Single. مقدار پیش‌فرض: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | شناسهٔ داخلی محدودهٔ ارائه که برای افزودنی‌ها یا کدهای دیگر در نظر گرفته شده است را باز می‌گرداند. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویس دوباره اختصاص یابد، نباید به‌عنوان کلید یکتای ثابت در نظر گرفته شود. Read-only UInt32. همچنین ببینید [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض شکل را که بر حسب نقطه اندازه‌گیری می‌شود، دریافت یا تنظیم می‌کند. Read/write Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشهٔ بالایی-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود، دریافت یا تنظیم می‌کند. Read/write Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشهٔ بالایی-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود، دریافت یا تنظیم می‌کند. Read/write Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | تصویر برای شیء Zoom را دریافت یا تنظیم می‌کند. Read/write [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک شکل در ترتیب z را باز می‌گرداند. Shapes[0] شکل پشت‌ترین در ترتیب z را برمی‌گرداند و Shapes[Shapes.Count - 1] شکل جلوی‌ترین را برمی‌گرداند. Read-only Int32. |

## متدها

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | اگر مکان‌گیر وجود نداشته باشد، یک مکان‌گیر جدید اضافه می‌کند و ویژگی‌های مکان‌گیر را به مکان‌گیر مشخص شده تنظیم می‌کند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک شکل مکان‌گیر پایه (شکل از طرح‌بندی و/یا اسلاید مادر که شکل جاری از آن به ارث می‌برد) را باز می‌گرداند. اگر شکل جاری ارث‌بری نباشد مقدار null بازگردانده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)() | تصویر کوچک (thumbnail) شکل را باز می‌گرداند. پیش‌فرضاً نوع ShapeThumbnailBounds.Shape استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تصویر کوچک شکل را باز می‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | حدهای بصری شکل را که از محتویات رندر شده محاسبه می‌شوند، دریافت می‌کند. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | تعریف می‌کند که این شکل مکان‌گیر نیست. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتوای Shape را به‌عنوان فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | محتوای Shape را به‌عنوان فایل SVG ذخیره می‌کند. |

### مباحث مرتبط

* class [SectionZoomFrame](../sectionzoomframe)
* interface [ISummaryZoomSection](../isummaryzoomsection)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->