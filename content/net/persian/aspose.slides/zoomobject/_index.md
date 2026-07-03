---
title: ZoomObject
second_title: مرجع API Aspose.Sildes برای .NET
description: یک شی Zoom را در اسلاید نمایش می‌دهد.
type: docs
weight: 11870
url: /fa/aspose.slides/zoomobject/
---
## کلاس ZoomObject

نمایش یک شی Zoom در اسلاید.

```csharp
public class ZoomObject : GraphicalObject, IZoomObject
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | ویژگی نحوه نمایش یک شکل در حالت سیاه-سفید را مشخص می‌کند. خواندنی/نوشتنی [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال روی شکل را برمی‌گرداند. فقط خواندنی Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی شکل را برمی‌گرداند. فقط خواندنی [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat را برمی‌گرداند که شامل افکت‌های پیکسلی اعمال شده بر یک شکل است. نکته: ممکن است برای برخی انواع شکل‌ها که ویژگی افکت ندارند، مقدار null بازگرداند. فقط خواندنی [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شیء FillFormat را برمی‌گرداند که شامل ویژگی‌های قالب‌بندی پر برای یک شکل است. نکته: ممکن است برای برخی انواع شکل‌ها که ویژگی پر ندارند، مقدار null بازگرداند. فقط خواندنی [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ویژگی‌های فریم شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط خواندنی [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع شکل را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | مشخص می‌کند آیا شکل مخفی است یا نه. خواندنی/نوشتنی Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | پیوندهای تعریف شده برای کلیک ماوس را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر پیوندها را برمی‌گرداند. فقط خواندنی [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | پیوندهای تعریف شده برای حرکت ماوس را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | نوع تصویر شی Zoom را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`ZoomImageType`](../zoomimagetype). مقدار پیش‌فرض: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه 'Mark as decorative' را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | مشخص می‌کند آیا شکل گروه‌بندی شده است یا نه. فقط خواندنی Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | مشخص می‌کند آیا شکل TextHolder_PPT است یا نه. فقط خواندنی Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat را برمی‌گرداند که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است. نکته: ممکن است برای برخی انواع شکل‌ها که ویژگی خط ندارند، مقدار null بازگرداند. فقط خواندنی [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند. نباید مقدار null باشد. در صورت نیاز می‌توانید مقدار رشتهٔ خالی استفاده کنید. خواندنی/نوشتنی String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | شناسهٔ یکتا برای اسلاید که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop امکان ارجاع قابل اعتماد به شکل را از هر نقطه‌ای در سند می‌دهد. فقط خواندنی UInt32. همچنین ببینید [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | در صورتی که شکل گروه‌بندی شده باشد، شیء GroupShape والد را برمی‌گرداند. در غیر این صورت مقدار null را برمی‌گرداند. فقط خواندنی [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | محل‌نگهدارندهٔ شکل را برمی‌گرداند. اگر شکل هیچ محل‌نگهدارنده‌ای نداشته باشد، مقدار null را برمی‌گرداند. فقط خواندنی [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائهٔ والد اسلاید را برمی‌گرداند. فقط خواندنی [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ویژگی‌های فریم خام شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | رفتار ناوبری در اسلایدنمایی را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Boolean. مقدار پیش‌فرض: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجه‌های چرخش شکل مشخص‌شده حول محور z را برمی‌گرداند یا تنظیم می‌کند. مقدار مثبت نشانگر چرخش ساعت‌گرد؛ مقدار منفی نشانگر چرخش پادساعت‌گرد است. خواندنی/نوشتنی Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط خواندنی [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 ویژگی) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | مقداری که مشخص می‌کند آیا Zoom پس‌زمینهٔ اسلاید مقصد را استفاده می‌کند یا نه را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Boolean. مقدار پیش‌فرض: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد یک شکل را برمی‌گرداند. فقط خواندنی [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat را برمی‌گرداند که شامل ویژگی‌های افکت 3D برای یک شکل است. نکته: ممکن است برای برخی انواع شکل‌ها که ویژگی 3D ندارند، مقدار null بازگرداند. فقط خواندنی [`IThreeDFormat`](../ithreedformat). |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | مدت زمان انتقال بین Zoom و اسلاید را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Single. مقدار پیش‌فرض: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | شناسهٔ داخلی در سطح ارائه که برای استفاده افزونه‌ها یا کدهای دیگر در نظر گرفته شده است، را برمی‌گرداند. از آنجا که این مقدار می‌تواند توسط کاربر یا برنامه‌نویس مجدداً تخصیص داده شود، نباید به عنوان کلید یکتا دائمی در نظر گرفته شود. فقط خواندنی UInt32. همچنین ببینید [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض شکل را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشهٔ بالایی سمت چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشهٔ بالایی سمت چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | تصویر برای شی Zoom را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل در پشت ترتیب z را برمی‌گرداند و Shapes[Shapes.Count - 1] شکل در جلوی ترتیب z را برمی‌گرداند. فقط خواندنی Int32. |

## متدها

| نام | توضیح |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | در صورتی که هیچ placeholderی وجود نداشته باشد، یکی جدید اضافه می‌کند و ویژگی‌های placeholder را به مقداری مشخص تنظیم می‌کند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک شکل placeholder پایه را برمی‌گرداند (شکلی از طرح‌بندی و/یا اسلاید اصلی که شکل فعلی از آن به ارث برده شده است). اگر شکل فعلی به ارث نبرده باشد، مقدار null بازگردانده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)() | تصویر بندانگشتی شکل را برمی‌گرداند. نوع ShapeThumbnailBounds.Shape به‌صورت پیش‌فرض استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تصویر بندانگشتی شکل را برمی‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | حدود بصری شکل را که از محتوای رندر شده محاسبه می‌شود، برمی‌گرداند. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | مشخص می‌کند که این شکل placeholder نیست. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتوای Shape را به‌صورت فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | محتوای Shape را به‌صورت فایل SVG ذخیره می‌کند. |

### موارد مرتبط

* کلاس [GraphicalObject](../graphicalobject)
* رابط [IZoomObject](../izoomobject)
* فضای نام [Aspose.Slides](../../aspose.slides)
* اسمبل [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->