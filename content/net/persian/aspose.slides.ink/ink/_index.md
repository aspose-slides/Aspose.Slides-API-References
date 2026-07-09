---
title: Ink
second_title: Aspose.Sildes برای مرجع API .NET
description: یک شیء جوهر را بر روی اسلاید نمایندگی می‌کند.
type: docs
weight: 7550
url: /fa/aspose.slides.ink/ink/
---
## کلاس Ink

یک شیء جوهر روی اسلاید را نمایندگی می‌کند.

```csharp
public class Ink : GraphicalObject, IInk
```

## ویژگی‌ها

| نام | توضیحات |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | ویژگی تعیین می‌کند که یک شکل چگونه در حالت نمایش سیاه-سفید رندر شود. خواندنی/قابل نوشتن [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال روی شکل را برمی‌گرداند. فقط خواندنی Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی شکل را برمی‌گرداند. فقط خواندنی [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat را برمی‌گرداند که شامل افکت‌های پیکسلی اعمال شده به یک شکل است. نکته: ممکن است برای برخی انواع شکل‌ها که ویژگی افکت ندارند، مقدار null بازگرداند. فقط خواندنی [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شیء FillFormat را برمی‌گرداند که شامل ویژگی‌های قالب‌بندی پر کردن برای یک شکل است. نکته: ممکن است برای برخی انواع شکل‌ها که ویژگی پر کردن ندارند، مقدار null بازگرداند. فقط خواندنی [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ویژگی‌های فریم شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط خواندنی [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع شکل را به نقطه می‌گیرد یا تنظیم می‌کند. خواندنی/قابل نوشتن Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | تعیین می‌کند که آیا شکل مخفی است یا خیر. خواندنی/قابل نوشتن Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | پیوند (hyperlink) تعریف‌شده برای کلیک ماوس را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر پیوند (hyperlink) را برمی‌گرداند. فقط خواندنی [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | پیوند تعریف‌شده برای قرار گرفتن ماوس بر روی عنصر را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه «Mark as decorative» را می‌گیرد یا تنظیم می‌کند. خواندنی/قابل نوشتن Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | تعیین می‌کند که آیا شکل گروه‌بندی شده است یا خیر. فقط خواندنی Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | تعیین می‌کند که آیا شکل TextHolder_PPT است یا خیر. فقط خواندنی Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat را برمی‌گرداند که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است. نکته: ممکن است برای برخی انواع شکل‌ها که ویژگی خط ندارند، مقدار null بازگرداند. فقط خواندنی [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند. نمی‌تواند null باشد. در صورت نیاز از رشته خالی استفاده کنید. خواندنی/قابل نوشتن String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | یک شناسه یکتای scoped به اسلاید برمی‌گرداند که در طول عمر شکل ثابت می‌ماند و امکان ارجاع قابل اطمینان به شکل را از هر جایی در سند برای PowerPoint یا کدهای interop فراهم می‌کند. فقط خواندنی UInt32. همچنین ببینید [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | اگر شکل گروه‌بندی شده باشد، شیء GroupShape پدر را برمی‌گرداند. در غیر این صورت null برمی‌گردد. فقط خواندنی [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | placeholder برای یک شکل را برمی‌گرداند. اگر شکل هیچ placeholderی نداشته باشد، null برمی‌گردد. فقط خواندنی [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائه (presentation) پدر اسلاید را برمی‌گرداند. فقط خواندنی [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ویژگی‌های فریم خام شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجه‌های چرخش شکل مشخص شده حول محور z را برمی‌گرداند یا تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پادساعت‌گرد است. خواندنی/قابل نوشتن Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط خواندنی [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 ویژگی) |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید پدر یک شکل را برمی‌گرداند. فقط خواندنی [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat که شامل ویژگی‌های اثر 3D برای یک شکل است را برمی‌گرداند. نکته: ممکن است برای برخی انواع شکل‌ها که ویژگی 3D ندارند، مقدار null بازگرداند. فقط خواندنی [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Traces](../../aspose.slides.ink/ink/traces) { get; } | تمام ردپای موجود در عنصر IInk [`IInkTrace`](../iinktrace) را می‌گیرد. فقط خواندنی. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | شناسه داخلی scoped به ارائه که برای افزونه‌ها یا کدهای دیگر در نظر گرفته شده است را برمی‌گرداند. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویس بازتخصیص یابد، نباید به عنوان کلید یکتا دائمی در نظر گرفته شود. فقط خواندنی UInt32. همچنین ببینید [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض شکل را به نقطه می‌گیرد یا تنظیم می‌کند. خواندنی/قابل نوشتن Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشه بالا-چپ شکل را به نقطه می‌گیرد یا تنظیم می‌کند. خواندنی/قابل نوشتن Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشه بالا-چپ شکل را به نقطه می‌گیرد یا تنظیم می‌کند. خواندنی/قابل نوشتن Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل را در انتهای پشت ترتیب z برمی‌گرداند و Shapes[Shapes.Count - 1] شکل را در انتهای جلو برمی‌گرداند. فقط خواندنی Int32. |
| static [InkEffectImages](../../aspose.slides.ink/ink/inkeffectimages) { get; } | مجموعه‌ای از تصاویر سفارشی که برای شبیه‌سازی افکت‌های بصری قلم جوهر استفاده می‌شوند را می‌گیرد. این تصاویر هنگام رندر جوهر با مقادیر خاص [`InkEffectType`](../inkeffecttype)، مانند Galaxy، Rainbow و غیره استفاده می‌شوند. با ارائه تصاویر خود می‌توانید کنترل کنید هر افکت جوهر چگونه ظاهر می‌شود. |

## متدها

| نام | توضیحات |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | اگر placeholder ای موجود نباشد، یک placeholder جدید اضافه می‌کند و ویژگی‌های placeholder را به مقدار مشخص‌شده تنظیم می‌کند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک شکل placeholder پایه (شکل از طرح‌بندی و/یا اسلاید اصلی که شکل فعلی از آن به ارث می‌رسد) را برمی‌گرداند. اگر شکل فعلی ارث‌برده نشده باشد، مقدار null برگردانده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)() | تصویر بندانگشتی شکل را برمی‌گرداند. به‌طور پیش‌فرض نوع ShapeThumbnailBounds.Shape برای محدوده تصویر بندانگشتی استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تصویر بندانگشتی شکل را برمی‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | محدوده‌های بصری شکل را که از محتوای رندر شده محاسبه می‌شود، می‌گیرد. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | تعیین می‌کند این شکل یک placeholder نیست. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتوای Shape را به‌عنوان فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | محتوای Shape را به‌عنوان فایل SVG ذخیره می‌کند. |

### همچنین ببینید

* کلاس [GraphicalObject](../../aspose.slides/graphicalobject)
* رابط [IInk](../iink)
* فضای نام [Aspose.Slides.Ink](../../aspose.slides.ink)
* مجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->