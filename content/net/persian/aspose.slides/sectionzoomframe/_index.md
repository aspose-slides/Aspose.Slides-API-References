---
title: SectionZoomFrame
second_title: Aspose.Sildes برای .NET مرجع API
description: یک شی Section Zoom را در اسلایدی نمایش می‌دهد.
type: docs
weight: 9780
url: /fa/aspose.slides/sectionzoomframe/
---
## کلاس SectionZoomFrame

یک شی Section Zoom را در اسلاید نمایش می‌دهد.

```csharp
public class SectionZoomFrame : ZoomObject, ISectionZoomFrame
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | متن جایگزین مرتبط با یک شکل را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | عنوان متن جایگزین مرتبط با یک شکل را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه-سفید رندر می‌شود. قابل خواندن/قابل نوشتن [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال در شکل را باز می‌گرداند. فقط خواندنی Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی شکل را باز می‌گرداند. فقط خواندنی [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شی EffectFormat را که شامل افکت‌های پیکسلی اعمال‌شده به یک شکل است باز می‌گرداند. توجه: برای برخی انواع شکل‌ها که ویژگی افکت ندارند می‌تواند مقدار null بازگرداند. فقط خواندنی [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شی FillFormat را که شامل ویژگی‌های قالب‌بندی پر کردن برای یک شکل است باز می‌گرداند. توجه: می‌تواند مقدار null بازگرداند برای برخی شکل‌هایی که ویژگی پر کردن ندارند. فقط خواندنی [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ویژگی‌های چارچوب شکل را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | قفل‌های شکل را باز می‌گرداند. فقط خواندنی [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع شکل را که بر حسب نقطه اندازه‌گیری می‌شود باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | مشخص می‌کند که آیا شکل مخفی است یا نه. قابل خواندن/قابل نوشتن Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | پیوند فرامتن تعریف‌شده برای کلیک ماوس را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر پیوند فرامتن را باز می‌گرداند. فقط خواندنی [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | پیوند فرامتن تعریف‌شده برای حرکت ماوس روی را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | نوع تصویر شی Zoom را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن [`ZoomImageType`](../zoomimagetype). مقدار پیش‌فرض: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه «علامت به عنوان تزئینی» را دریافت یا تنظیم می‌کند. قابل خواندن/قابل نوشتن Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | مشخص می‌کند که آیا شکل گروه‌بندی شده است یا نه. فقط خواندنی Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | مشخص می‌کند که شکل TextHolder_PPT است یا نه. فقط خواندنی Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شی LineFormat را که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است باز می‌گرداند. توجه: برای برخی انواع شکل‌ها که ویژگی خط ندارند می‌تواند مقدار null بازگرداند. فقط خواندنی [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک شکل را باز می‌گرداند یا تنظیم می‌کند. باید خالی نباشد. در صورت نیاز از مقدار رشتهٔ خالی استفاده کنید. قابل خواندن/قابل نوشتن String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | شناسهٔ یکتای مخصوص اسلاید که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop اجازه می‌دهد که شکل را از هرجای سند به‌صورت قابل اطمینان ارجاع دهند. فقط خواندنی UInt32. همچنین ببینید [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | شی GroupShape والد را اگر شکل گروه‌بندی شده باشد باز می‌گرداند. در غیر این صورت مقدار null باز می‌گردد. فقط خواندنی [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | متغیر نگهدارنده (placeholder) برای یک شکل را باز می‌گرداند. اگر شکل هیچ placeholderی نداشته باشد مقدار null باز می‌گردد. فقط خواندنی [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | نمایش‌نامهٔ والد اسلاید را باز می‌گرداند. فقط خواندنی [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ویژگی‌های چارچوب شکل خام را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | رفتار ناوبری در نمایش اسلاید را دریافت یا تنظیم می‌کند. قابل خواندن/قابل نوشتن Boolean. مقدار پیش‌فرض: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجه‌های چرخش شکل مشخص‌شده حول محور z را باز می‌گرداند یا تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پاد ساعت‌گرد است. قابل خواندن/قابل نوشتن Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | قفل‌های شکل را باز می‌گرداند. فقط خواندنی [`IGraphicalObjectLock`](../igraphicalobjectlock). (۲ ویژگی) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | مقداری که مشخص می‌کند آیا Zoom از پس‌زمینه اسلاید مقصد استفاده می‌کند را دریافت یا تنظیم می‌کند. قابل خواندن/قابل نوشتن Boolean. مقدار پیش‌فرض: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد یک شکل را باز می‌گرداند. فقط خواندنی [`IBaseSlide`](../ibaseslide). |
| [TargetSection](../../aspose.slides/sectionzoomframe/targetsection) { get; set; } | شی بخش (section) که شی Section Zoom به آن لینک می‌دهد را دریافت یا تنظیم می‌کند. قابل خواندن/قابل نوشتن [`ISection`](../isection). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شی ThreeDFormat را که ویژگی‌های اثر 3D برای یک شکل است باز می‌گرداند. توجه: برای برخی انواع شکل‌ها که ویژگی 3D ندارند می‌تواند مقدار null بازگرداند. فقط خواندنی [`IThreeDFormat`](../ithreedformat). |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | مدت زمان انتقال بین Zoom و اسلاید را دریافت یا تنظیم می‌کند. قابل خواندن/قابل نوشتن Single. مقدار پیش‌فرض: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | شناسهٔ داخلی مخصوص ارائه که برای استفاده توسط افزونه‌ها یا کدهای دیگر در نظر گرفته شده است. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویس تغییر یابد، نباید به‌عنوان کلید یکتا پایدار در نظر گرفته شود. فقط خواندنی UInt32. همچنین ببینید [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض شکل را که بر حسب نقطه اندازه‌گیری می‌شود دریافت یا تنظیم می‌کند. قابل خواندن/قابل نوشتن Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشهٔ بالا-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود دریافت یا تنظیم می‌کند. قابل خواندن/قابل نوشتن Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشهٔ بالا-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود دریافت یا تنظیم می‌کند. قابل خواندن/قابل نوشتن Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | تصویر برای شی Zoom را دریافت یا تنظیم می‌کند. قابل خواندن/قابل نوشتن [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک شکل در ترتیب z را باز می‌گرداند. Shapes[0] شکل در پشت ترتیب z را برمی‌گرداند و Shapes[Shapes.Count - 1] شکل در جلو ترتیب z را برمی‌گرداند. فقط خواندنی Int32. |

## متدها

| نام | توضیح |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | یک placeholder جدید اضافه می‌کند اگر وجود نداشته باشد و ویژگی‌های placeholder را به یک مورد مشخص تنظیم می‌کند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک شکل placeholder پایه را باز می‌گرداند (شکلی از طرح‌بندی و/یا اسلاید اصلی که شکل فعلی از آن به ارث می‌برد). اگر شکل فعلی ارث‌برده نشده باشد مقدار null بازگردانده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)() | تصویر کوچک (thumbnail) شکل را باز می‌گرداند. به‌طور پیش‌فرض از نوع ShapeThumbnailBounds.Shape برای مرزهای تصویر کوچک استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تصویر کوچک شکل را باز می‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | مرزهای بصری شکل را که از محتوای رندر شده‌اش محاسبه می‌شود دریافت می‌کند. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | مشخص می‌کند که این شکل placeholder نیست. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتویات Shape را به‌عنوان فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | محتویات Shape را به‌عنوان فایل SVG ذخیره می‌کند. |

### مراجع

* کلاس [ZoomObject](../zoomobject)
* رابط [ISectionZoomFrame](../isectionzoomframe)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* اجزاء [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->