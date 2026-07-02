---
title: SectionZoomFrame
second_title: Aspose.Sildes برای .NET مرجع API
description: نمایانگر یک شی Section Zoom در یک اسلاید است.
type: docs
weight: 9780
url: /fa/aspose.slides/sectionzoomframe/
---
## SectionZoomFrame کلاس

نمایانگر یک شی Section Zoom در یک اسلاید.

```csharp
public class SectionZoomFrame : ZoomObject, ISectionZoomFrame
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. Read/write String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. Read/write String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه‌وسفید رندر می‌شود. Read/write [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال روی شکل را برمی‌گرداند. Read-only Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی شکل را برمی‌گرداند. Read-only [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat که شامل اثرات پیکسلی اعمال‌شده به یک شکل است را برمی‌گرداند. توجه: ممکن است برای برخی انواع شکل‌ها که خصوصیات اثر ندارند مقدار null برگرداند. Read-only [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شیء FillFormat که شامل خصوصیات قالب‌بندی پرکردن برای یک شکل است را برمی‌گرداند. توجه: ممکن است برای برخی انواع شکل‌ها که خصوصیات پرکردن ندارند مقدار null برگرداند. Read-only [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ویژگی‌های چارچوب شکل را برمی‌گرداند یا تنظیم می‌کند. Read/write [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | قفل‌های شکل را برمی‌گرداند. Read-only [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گیرد یا تنظیم می‌کند. Read/write Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | تعیین می‌کند آیا شکل مخفی است یا خیر. Read/write Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | پیوند (hyperlink) تعریف‌شده برای کلیک ماوس را برمی‌گرداند یا تنظیم می‌کند. Read/write [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر پیوند (hyperlink) را برمی‌گرداند. Read-only [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | پیوند تعریف‌شده برای عبور ماوس (mouse over) را برمی‌گرداند یا تنظیم می‌کند. Read/write [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | نوع تصویر یک شی Zoom را برمی‌گیرد یا تنظیم می‌کند. Read/write [`ZoomImageType`](../zoomimagetype). مقدار پیش‌فرض: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه «Mark as decorative» را برمی‌گیرد یا تنظیم می‌کند Reed/write Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | تعیین می‌کند آیا شکل گروه‌بندی شده است یا خیر. Read-only Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | تعیین می‌کند آیا شکل TextHolder_PPT است یا خیر. Read-only Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat که شامل خصوصیات قالب‌بندی خط برای یک شکل است را برمی‌گرداند. توجه: ممکن است برای برخی انواع شکل‌ها که خصوصیات خط ندارند مقدار null برگرداند. Read-only [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند. نباید مقدار null باشد. در صورت نیاز از رشته خالی استفاده کنید. Read/write String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | یک شناسه یکتا محدود به اسلاید که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کد interop امکان ارجاع قابل اعتماد به شکل را از هر نقطه‌ای در سند می‌دهد را برمی‌گرداند. Read-only UInt32. همچنین نگاه کنید به [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | اگر شکل گروه‌بندی شده باشد، شیء GroupShape والد را برمی‌گرداند. در غیر این صورت null برمی‌گرداند. Read-only [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | متغیر نگهدارنده (placeholder) برای یک شکل را برمی‌گرداند. اگر شکل هیچ placeholder نداشته باشد، null برمی‌گرداند. Read-only [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائه (presentation) والد اسلاید را برمی‌گرداند. Read-only [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ویژگی‌های چارچوب خام شکل را برمی‌گرداند یا تنظیم می‌کند. Read/write [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | رفتار ناوبری در اسلایدشو را برمی‌گیرد یا تنظیم می‌کند. Read/write Boolean. مقدار پیش‌فرض: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجه‌های چرخش شکل مشخص‌شده حول محور z را برمی‌گرداند یا تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پادساعت‌گرد است. Read/write Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | قفل‌های شکل را برمی‌گرداند. Read-only [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 ویژگی) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | مقداری که تعیین می‌کند آیا Zoom پس‌زمینه اسلاید مقصد را استفاده می‌کند یا خیر را برمی‌گیرد یا تنظیم می‌کند. Read/write Boolean. مقدار پیش‌فرض: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد یک شکل را برمی‌گرداند. Read-only [`IBaseSlide`](../ibaseslide). |
| [TargetSection](../../aspose.slides/sectionzoomframe/targetsection) { get; set; } | شیء بخش (section) که شی Section Zoom به آن لینک می‌کند را برمی‌گیرد یا تنظیم می‌کند. Read/write [`ISection`](../isection). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat که شامل خصوصیات اثر ۳بعدی برای یک شکل است را برمی‌گرداند. توجه: ممکن است برای برخی انواع شکل‌ها که خصوصیات ۳بعدی ندارند مقدار null برگرداند. Read-only [`IThreeDFormat`](../ithreedformat). |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | مدت زمان انتقال بین Zoom و اسلاید را برمی‌گیرد یا تنظیم می‌کند. Read/write Single. مقدار پیش‌فرض: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | یک شناسه داخلی محدود به ارائه (presentation) را برمی‌گرداند که برای استفاده افزونه‌ها یا کدهای دیگر منظور شده است. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویسی دوباره اختصاص داده شود، نباید به عنوان کلید یکتای دائمی در نظر گرفته شود. Read-only UInt32. همچنین نگاه کنید به [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گیرد یا تنظیم می‌کند. Read/write Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشهٔ بالا-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گیرد یا تنظیم می‌کند. Read/write Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشهٔ بالا-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گیرد یا تنظیم می‌کند. Read/write Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | تصویر برای شی Zoom را برمی‌گیرد یا تنظیم می‌کند. Read/write [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل موجود در انتهای ترتیب z را برمی‌گرداند و Shapes[Shapes.Count - 1] شکل موجود در جلوی ترتیب z را برمی‌گرداند. Read-only Int32. |

## متدها

| نام | توضیح |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | یک placeholder جدید اضافه می‌کند اگر وجود نداشته باشد و خصوصیات placeholder را به یک مورد مشخص تنظیم می‌کند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک شکل placeholder پایه را برمی‌گرداند (شکلی از طرح‌بندی و/یا اسلاید اصلی که شکل جاری از آن به ارث برده است). اگر شکل جاری به ارث نباشد، مقدار null برمی‌گردد. |
| [GetImage](../../aspose.slides/shape/getimage)() | تصویر بندانگشتی شکل را برمی‌گرداند. به‌طور پیش‌فرض نوع ShapeThumbnailBounds.Shape برای حدود تصویر بندانگشتی استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تصویر بندانگشتی شکل را برمی‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | حدود بصری شکل که از محتویات رندر شده محاسبه می‌شود را برمی‌گیرد. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | تعریف می‌کند که این شکل placeholder نیست. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتوای Shape را به‌عنوان فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | محتوای Shape را به‌عنوان فایل SVG ذخیره می‌کند. |

### همچنین ببینید

* کلاس [ZoomObject](../zoomobject)
* رابط [ISectionZoomFrame](../isectionzoomframe)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->