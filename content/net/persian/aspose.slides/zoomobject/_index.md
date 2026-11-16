---
title: ZoomObject
second_title: مرجع API Aspose.Sildes برای .NET
description: یک شی Zoom را در یک اسلاید نمایش می‌دهد.
type: docs
weight: 11890
url: /fa/aspose.slides/zoomobject/
---
## کلاس ZoomObject

یک شی Zoom را در یک اسلاید نشان می‌دهد.

```csharp
public class ZoomObject : GraphicalObject, IZoomObject
```

## خصوصیات

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | مقدار یا تنظیم متن جایگزین مرتبط با یک شکل. خواندن/نوشتن String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | مقدار یا تنظیم عنوان متن جایگزین مرتبط با یک شکل. خواندن/نوشتن String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | ویژگی مشخص می‌کند که یک شکل در حالت نمایش سیاه-سفید چگونه رندر می‌شود. خواندن/نوشتن [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال روی شکل را بر می‌گرداند. فقط-خواندنی Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی شکل را بر می‌گرداند. فقط-خواندنی [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat را که شامل افکت‌های پیکسل اعمال شده به یک شکل است بر می‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی افکت ندارند ممکن است مقدار null بازگردد. فقط-خواندنی [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شیء FillFormat را که شامل ویژگی‌های قالب‌بندی پر کردن برای یک شکل است بر می‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی پر کردن ندارند ممکن است مقدار null بازگردد. فقط-خواندنی [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | مقدار یا تنظیم ویژگی‌های فریم شکل. خواندن/نوشتن [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | قفل‌های شکل را بر می‌گرداند. فقط-خواندنی [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع شکل را بر حسب پوینت تنظیم یا دریافت می‌کند. خواندن/نوشتن Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | تعیین می‌کند که شکل مخفی باشد یا نه. خواندن/نوشتن Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | مقدار یا تنظیم پیوند فراموشی تعریف شده برای کلیک ماوس. خواندن/نوشتن [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر پیوند فراموشی را بر می‌گرداند. فقط-خواندنی [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | مقدار یا تنظیم پیوند فراموشی تعریف شده برای حرکت ماوس. خواندن/نوشتن [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | نوع تصویر شی Zoom را تنظیم یا دریافت می‌کند. خواندن/نوشتن [`ZoomImageType`](../zoomimagetype). مقدار پیش‌فرض: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه «Mark as decorative» را تنظیم یا دریافت می‌کند. خواندن/نوشتن Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | تعیین می‌کند که شکل گروه‌بندی شده است یا نه. فقط-خواندنی Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | تعیین می‌کند که شکل TextHolder_PPT است یا نه. فقط-خواندنی Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat را که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است بر می‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی خط ندارند ممکن است مقدار null بازگردد. فقط-خواندنی [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک شکل را تنظیم یا دریافت می‌کند. نباید null باشد. در صورت نیاز می‌توانید رشته خالی استفاده کنید. خواندن/نوشتن String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | شناسهٔ یکتا scoped به اسلاید که در طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop امکان ارجاع معتبر به شکل را از هر نقطه‌ای می‌دهد. فقط-خواندنی UInt32. همچنین ببینید [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | شیء والد GroupShape را اگر شکل گروه‌بندی شده باشد بر می‌گرداند. در غیر این صورت null باز می‌گردد. فقط-خواندنی [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | مکان‌نگهدارندهٔ یک شکل را بر می‌گرداند. اگر شکل مکان‌نگهدارنده نداشته باشد null باز می‌گردد. فقط-خواندنی [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائهٔ والد اسلاید را بر می‌گرداند. فقط-خواندنی [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ویژگی‌های خام فریم شکل را تنظیم یا دریافت می‌کند. خواندن/نوشتن [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | رفتار ناوبری در نمایش اسلاید را تنظیم یا دریافت می‌کند. خواندن/نوشتن Boolean. مقدار پیش‌فرض: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجه‌های چرخش شکل حول محور z را تنظیم یا دریافت می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پادساعت‌گرد است. خواندن/نوشتن Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | قفل‌های شکل را بر می‌گرداند. فقط-خواندنی [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 ویژگی) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | مقدار یا تنظیم اینکه Zoom از پس‌زمینهٔ اسلاید مقصد استفاده کند یا نه. خواندن/نوشتن Boolean. مقدار پیش‌فرض: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد یک شکل را بر می‌گرداند. فقط-خواندنی [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat را که شامل ویژگی‌های اثر 3D برای یک شکل است بر می‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی 3D ندارند ممکن است مقدار null بازگردد. فقط-خواندنی [`IThreeDFormat`](../ithreedformat). |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | مدت زمان انتقال بین Zoom و اسلاید را تنظیم یا دریافت می‌کند. خواندن/نوشتن Single. مقدار پیش‌فرض: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | شناسهٔ داخلی scoped به ارائه که برای افزودنی‌ها یا کدهای دیگر استفاده می‌شود. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویس تغییر یابد، نباید به عنوان کلید یکتا دائمی در نظر گرفته شود. فقط-خواندنی UInt32. همچنین ببینید [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض شکل را بر حسب پوینت تنظیم یا دریافت می‌کند. خواندن/نوشتن Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشهٔ بالا-چپ شکل را بر حسب پوینت تنظیم یا دریافت می‌کند. خواندن/نوشتن Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشهٔ بالا-چپ شکل را بر حسب پوینت تنظیم یا دریافت می‌کند. خواندن/نوشتن Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | تصویر برای شی Zoom را تنظیم یا دریافت می‌کند. خواندن/نوشتن [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک شکل در ترتیب z را بر می‌گرداند. Shapes[0] شکل در عقب‌ترین موقعیت را بر می‌گرداند و Shapes[Shapes.Count - 1] شکل در جلوی‌ترین موقعیت را بر می‌گرداند. فقط-خواندنی Int32. |

## متدها

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | اگر وجود نداشته باشد، یک مکان‌نگهدارندهٔ جدید اضافه می‌کند و ویژگی‌های مکان‌نگهدارنده را به مقدار مشخص‌شده تنظیم می‌کند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک شکل مکان‌نگهدارندهٔ پایه (شکل از طرح‌بندی و/یا اسلاید اصلی که شکل فعلی از آن ارث می‌برد) را برمی‌گرداند. اگر شکل فعلی ارث‌برده نشده باشد، مقدار null بازگردانده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)() | تصویر کوچک شکل را برمی‌گرداند. به‌طور پیش‌فرض نوع Bounds ShapeThumbnailBounds.Shape استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تصویر کوچک شکل را برمی‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | مرزهای بصری شکل را که از محتوای رندر شدهٔ آن محاسبه می‌شود، دریافت می‌کند. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | تعریف می‌کند که این شکل مکان‌نگهدارنده نیست. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتوای Shape را به‌عنوان فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | محتوای Shape را به‌عنوان فایل SVG ذخیره می‌کند. |

### موارد مرتبط

* کلاس [GraphicalObject](../graphicalobject)
* رابط [IZoomObject](../izoomobject)
* فضای نام [Aspose.Slides](../../aspose.slides)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->