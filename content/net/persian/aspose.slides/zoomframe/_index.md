---
title: ZoomFrame
second_title: Aspose.Sildes برای .NET مرجع API
description: نمایانگر یک شیء Slide Zoom در یک اسلاید است.
type: docs
weight: 11840
url: /fa/aspose.slides/zoomframe/
---
## کلاس ZoomFrame

نمایانگر یک شیء Slide Zoom در یک اسلاید است.

```csharp
public class ZoomFrame : ZoomObject, IZoomFrame
```

## خصوصیات

| نام | توضیح |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. Read/write String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. Read/write String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | این ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه و سفید رندر می‌شود. Read/write [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال روی شکل را برمی‌گرداند. Read-only Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی شکل را برمی‌گرداند. Read-only [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat را که شامل افکت‌های پیکسلی اعمال شده بر شکل است برمی‌گرداند. Note: can return null for certain types of shapes which don't have effect properties. Read-only [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شیء FillFormat را که شامل خصوصیات قالب‌بندی پر کردن برای یک شکل است برمی‌گرداند. Note: can return null for certain types of shapes which don't have fill properties. Read-only [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | خصوصیات چارچوب شکل را برمی‌گرداند یا تنظیم می‌کند. Read/write [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | قفل‌های شکل را برمی‌گرداند. Read-only [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع شکل را که بر حسب نقطه اندازه‌گیری می‌شود برمی‌گرداند یا تنظیم می‌کند. Read/write Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | تعیین می‌کند که آیا شکل مخفی است یا نه. Read/write Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | پیوند ارجاعی تعریف شده برای کلیک ماوس را برمی‌گرداند یا تنظیم می‌کند. Read/write [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر پیوندها را برمی‌گرداند. Read-only [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | پیوند تعریف شده برای حرکت ماوس روی شیء را برمی‌گرداند یا تنظیم می‌کند. Read/write [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | نوع تصویر یک شیء زوم را برمی‌گرداند یا تنظیم می‌کند. Read/write [`ZoomImageType`](../zoomimagetype). مقدار پیش‌فرض: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه «Mark as decorative» را برمی‌گرداند یا تنظیم می‌کند. Read/write Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | تعیین می‌کند که آیا شکل گروه‌بندی شده است یا نه. Read-only Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | تعیین می‌کند که آیا شکل TextHolder_PPT است. Read-only Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat را که شامل خصوصیات قالب‌بندی خط برای یک شکل است برمی‌گرداند. Note: can return null for certain types of shapes which don't have line properties. Read-only [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند. نمی‌تواند null باشد. در صورت نیاز مقدار رشته خالی را استفاده کنید. Read/write String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | شناسه منحصر به‌فردی scoped به اسلاید که برای طول عمر شکل ثابت می‌ماند و امکان ارجاع قابل اطمینان به شکل از هر نقطه‌ای از سند را می‌دهد را برمی‌گرداند. Read-only UInt32. همچنین به [`UniqueId`](../shape/uniqueid) مراجعه کنید. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | اگر شکل گروه‌بندی شده باشد شیء GroupShape والد را برمی‌گرداند. در غیر این صورت null برمی‌گرداند. Read-only [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | محل نگهداری (placeholder) برای یک شکل را برمی‌گرداند. اگر شکل محل نگهداری نداشته باشد null برمی‌گرداند. Read-only [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائه‌دهنده اصلی اسلاید را برمی‌گرداند. Read-only [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | خصوصیات چارچوب شکل خام را برمی‌گرداند یا تنظیم می‌کند. Read/write [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | رفتار ناوبری در نمایش اسلاید را برمی‌گرداند یا تنظیم می‌کند. Read/write Boolean. مقدار پیش‌فرض: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجاتی که شکل مشخص‌شده حول محور z چرخانده می‌شود را برمی‌گرداند یا تنظیم می‌کند. مقدار مثبت به معنای چرخش ساعت‌گرد؛ مقدار منفی به معنای چرخش ضدساعت‌گرد است. Read/write Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | قفل‌های شکل را برمی‌گرداند. Read-only [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 خصوصیت) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | مقداری که مشخص می‌کند آیا Zoom پس‌زمینه اسلاید مقصد را استفاده می‌کند یا نه را برمی‌گرداند یا تنظیم می‌کند. Read/write Boolean. مقدار پیش‌فرض: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد یک شکل را برمی‌گرداند. Read-only [`IBaseSlide`](../ibaseslide). |
| [TargetSlide](../../aspose.slides/zoomframe/targetslide) { get; set; } | شیء اسلایدی که شیء Slide Zoom به آن لینک می‌شود را برمی‌گرداند یا تنظیم می‌کند. Read/write [`ISlide`](../islide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat را که شامل خصوصیات اثر 3-بعدی برای یک شکل است برمی‌گرداند. Note: can return null for certain types of shapes which don't have 3d properties. Read-only [`IThreeDFormat`](../ithreedformat). |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | مدت زمان انتقال بین Zoom و اسلاید را برمی‌گرداند یا تنظیم می‌کند. Read/write Single. مقدار پیش‌فرض: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | شناسه داخلی scoped به ارائه که برای افزونه‌ها یا کدهای دیگر در نظر گرفته شده است را برمی‌گرداند. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویس دوباره اختصاص یابد، نباید به عنوان کلید یکتا در نظر گرفته شود. Read-only UInt32. همچنین به [`OfficeInteropShapeId`](../shape/officeinteropshapeid) مراجعه کنید. |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض شکل را که بر حسب نقطه اندازه‌گیری می‌شود برمی‌گرداند یا تنظیم می‌کند. Read/write Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مقدار x-مختصات گوشه بالا-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود برمی‌گرداند یا تنظیم می‌کند. Read/write Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مقدار y-مختصات گوشه بالا-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود برمی‌گرداند یا تنظیم می‌کند. Read/write Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | تصویر برای شیء زوم را برمی‌گرداند یا تنظیم می‌کند. Read/write [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک شکل در ترتیب z-order را برمی‌گرداند. Shapes[0] شکل در پشت‌ترین موقعیت z-order را برمی‌گرداند و Shapes[Shapes.Count - 1] شکل در جلوی‌ترین موقعیت را برمی‌گرداند. Read-only Int32. |

## متدها

| نام | توضیح |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | اگر placeholder وجود نداشته باشد، یک placeholder جدید اضافه می‌کند و خصوصیات placeholder را به مورد مشخص شده تنظیم می‌کند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک شکل placeholder پایه را برمی‌گرداند (شکلی که از طرح‌بندی و/یا اسلاید اصلی که شکل فعلی از آن ارث‌بری می‌کند استخراج شده است). اگر شکل فعلی ارث‌بری نشود مقدار null برگردانده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)() | تصویر بندانگشتی شکل را برمی‌گرداند. نوع ShapeThumbnailBounds.Shape به‌عنوان مقدار پیش‌فرض استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تصویر بندانگشتی شکل را برمی‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | مرزهای بصری شکل را که از محتوای رندر شده محاسبه می‌شود، دریافت می‌کند. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | تعریف می‌کند که این شکل یک placeholder نیست. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتوای Shape را به‌عنوان فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | محتوای Shape را به‌عنوان فایل SVG ذخیره می‌کند. |

### همچنین ببینید

* کلاس [ZoomObject](../zoomobject)
* رابط [IZoomFrame](../izoomframe)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* تجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->