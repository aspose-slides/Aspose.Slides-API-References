---
title: ZoomFrame
second_title: مرجع API Aspose.Sildes برای .NET
description: نمایانگر یک شیء Slide Zoom در یک اسلاید.
type: docs
weight: 11840
url: /fa/aspose.slides/zoomframe/
---
## کلاس ZoomFrame

نمایانگر یک شیء Slide Zoom در یک اسلاید.

```csharp
public class ZoomFrame : ZoomObject, IZoomFrame
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | این ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه-سفید رندر می‌شود. خواندنی/نوشتنی [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال در شکل را برمی‌گرداند. فقط‌خواندنی Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی شکل را برمی‌گرداند. فقط‌خواندنی [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat را که شامل افکت‌های پیکسلی اعمال‌شده بر شکل است برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی افکت ندارند می‌تواند مقدار null بازگرداند. فقط‌خواندنی [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شیء FillFormat را که شامل ویژگی‌های قالب‌بندی پرشده برای یک شکل است برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی پرشده ندارند می‌تواند مقدار null بازگرداند. فقط‌خواندنی [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ویژگی‌های چارچوب شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط‌خواندنی [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع شکل را که به نقطه اندازه‌گیری می‌شود برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | مشخص می‌کند که آیا شکل مخفی است یا خیر. خواندنی/نوشتنی Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | پیوند تعریف‌شده برای کلیک ماوس را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر پیوندها را برمی‌گرداند. فقط‌خواندنی [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | پیوند تعریف‌شده برای حرکت ماوس روی شیء را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | نوع تصویر یک شیء زوم را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`ZoomImageType`](../zoomimagetype). مقدار پیش‌فرض: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه “علامت‌گذاری به عنوان تزئینی” را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | مشخص می‌کند که آیا شکل گروه‌بندی شده است یا خیر. فقط‌خواندنی Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | مشخص می‌کند که آیا شکل TextHolder_PPT است یا خیر. فقط‌خواندنی Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat را که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی خط ندارند می‌تواند مقدار null بازگرداند. فقط‌خواندنی [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند. نباید null باشد. در صورت نیاز می‌توانید مقدار رشته خالی استفاده کنید. خواندنی/نوشتنی String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | شناسه یکتا scoped به اسلاید را که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کد interop اجازه می‌دهد به‌صورت قابل اعتماد به شکل از هر نقطه‌ای در سند ارجاع دهد، برمی‌گرداند. فقط‌خواندنی UInt32. همچنین ببینید [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | اگر شکل گروه‌بندی شده باشد شیء GroupShape والد را برمی‌گرداند. در غیر این صورت null باز می‌گردد. فقط‌خواندنی [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | محل نگهدارنده (placeholder) برای یک شکل را برمی‌گرداند. اگر شکل هیچ placeholder نداشته باشد null باز می‌گردد. فقط‌خواندنی [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائه والد اسلاید را برمی‌گرداند. فقط‌خواندنی [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ویژگی‌های چارچوب خام شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | رفتار ناوبری در ارائه اسلایدی را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Boolean. مقدار پیش‌فرض: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجه‌های چرخش شکل مشخص around محور z را برمی‌گرداند یا تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پادساعت‌گرد است. خواندنی/نوشتنی Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط‌خواندنی [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 ویژگی) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | مقداری که مشخص می‌کند آیا Zoom پس‌زمینه اسلاید مقصد را استفاده می‌کند یا خیر را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Boolean. مقدار پیش‌فرض: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد یک شکل را برمی‌گرداند. فقط‌خواندنی [`IBaseSlide`](../ibaseslide). |
| [TargetSlide](../../aspose.slides/zoomframe/targetslide) { get; set; } | شیء اسلایدی که شیء Slide Zoom به آن لینک می‌شود را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`ISlide`](../islide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat را که شامل ویژگی‌های اثر 3D برای یک شکل است برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی 3D ندارند می‌تواند مقدار null بازگرداند. فقط‌خواندنی [`IThreeDFormat`](../ithreedformat). |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | مدت زمان انتقال بین Zoom و اسلاید را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Single. مقدار پیش‌فرض: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | شناسه داخلی scoped به ارائه که برای استفاده توسط افزونه‌ها یا کدهای دیگر در نظر گرفته شده را برمی‌گرداند. از آنجا که این مقدار می‌تواند توسط کاربر یا برنامه‌نویسی تغییر یابد، نباید به‌عنوان کلید یکتای پایدار درنظر گرفته شود. فقط‌خواندنی UInt32. همچنین ببینید [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض شکل را که به نقطه اندازه‌گیری می‌شود برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشه بالایی چپ شکل را که به نقطه اندازه‌گیری می‌شود برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشه بالایی چپ شکل را که به نقطه اندازه‌گیری می‌شود برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | تصویر برای شیء زوم را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل در انتهای پشت ترتیب z را باز می‌گرداند و Shapes[Shapes.Count - 1] شکل در جلوی ترتیب z را باز می‌گرداند. فقط‌خواندنی Int32. |

## متدها

| نام | توضیح |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | یک placeholder جدید اضافه می‌کند اگر وجود نداشته باشد و ویژگی‌های placeholder را به مقدار مشخص‌شده تنظیم می‌کند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک شکل placeholder پایه را باز می‌گرداند (شکلی از طرح‌بندی و/یا اسلاید اصلی که شکل فعلی از آن به ارث برده شده). اگر شکل فعلی ارث‌بری نشده باشد null برگردانده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)() | تصویر کوچک (thumbnail) شکل را برمی‌گرداند. نوع ShapeThumbnailBounds.Shape به‌صورت پیش‌فرض استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تصویر کوچک شکل را برمی‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | مرزهای بصری شکل را که از محتوای رندر شده محاسبه می‌شود دریافت می‌کند. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | تعریف می‌کند که این شکل یک placeholder نیست. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتوای Shape را به صورت فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | محتوای Shape را به صورت فایل SVG با گزینه‌های ISVGOptions ذخیره می‌کند. |

### موارد مرتبط

* کلاس [ZoomObject](../zoomobject)
* رابط [IZoomFrame](../izoomframe)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->