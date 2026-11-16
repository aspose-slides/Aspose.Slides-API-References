---
title: LegacyDiagram
second_title: Aspose.Sildes برای .NET مرجع API
description: نمایانگر یک شیء دیاگرام legacy است.
type: docs
weight: 7690
url: /fa/aspose.slides/legacydiagram/
---
## LegacyDiagram کلاس

نمایانگر یک شیء دیاگرام legacy است.

```csharp
public class LegacyDiagram : GraphicalObject, ILegacyDiagram
```

## خصوصیات

| نام | توضیح |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | متن جایگزین مرتبط با یک شکل را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | عنوان متن جایگزین مرتبط با یک شکل را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [AsIGraphicalObject](../../aspose.slides/legacydiagram/asigraphicalobject) { get; } | امکان دریافت رابط پایه IGraphicalObject را فراهم می‌کند. فقط-خواندنی [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | خصوصیت مشخص می‌کند شکل چگونه در حالت نمایش سیاه-سفید رندرسازی می‌شود. خواندنی/نوشتنی [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال روی شکل را بازمی‌گرداند. فقط-خواندنی Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده سفارشی شکل را بازمی‌گرداند. فقط-خواندنی [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat را که شامل افکت‌های پیکسلی اعمال‌شده به یک شکل است بازمی‌گرداند. توجه: برای برخی انواع شکل که خصوصیات افکت ندارند می‌تواند مقدار null را برگرداند. فقط-خواندنی [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شیء FillFormat را که شامل خصوصیات قالب‌بندی پر برای یک شکل است بازمی‌گرداند. توجه: برای برخی انواع شکل که خصوصیات پر ندارند می‌تواند مقدار null را برگرداند. فقط-خواندنی [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | خصوصیات فریم شکل را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | قفل‌های شکل را بازمی‌گرداند. فقط-خواندنی [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع شکل را که بر حسب نقطه اندازه‌گیری می‌شود، بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | مشخص می‌کند آیا شکل مخفی است یا نه. خواندنی/نوشتنی Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | پیوند Hyperlink تعریف‌شده برای کلیک ماوس را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر Hyperlink را بازمی‌گرداند. فقط-خواندنی [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | پیوند Hyperlink تعریف‌شده برای عبور ماوس را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه 'Mark as decorative' را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | مشخص می‌کند آیا شکل گروه‌بندی شده است یا نه. فقط-خواندنی Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | مشخص می‌کند آیا شکل TextHolder_PPT است یا نه. فقط-خواندنی Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat را که شامل خصوصیات قالب‌بندی خط برای یک شکل است بازمی‌گرداند. توجه: برای برخی انواع شکل که خصوصیات خط ندارند می‌تواند مقدار null را برگرداند. فقط-خواندنی [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک شکل را بازمی‌گرداند یا تنظیم می‌کند. باید مقدار null نباشد. در صورت نیاز می‌توانید از رشته خالی استفاده کنید. خواندنی/نوشتنی String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | شناسه یکتا مختص اسلاید را که در طول عمر شکل ثابت می‌ماند و به PowerPoint یا کد interop امکان ارجاع قابل اعتماد به شکل را از هر نقطه‌ای در سند می‌دهد، بازمی‌گرداند. فقط-خواندنی UInt32. همچنین [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | اگر شکل گروه‌بندی شده باشد شیء GroupShape والد را بازمی‌گرداند. در غیر این صورت مقدار null را بر می‌گرداند. فقط-خواندنی [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | محافظ شکل را بازمی‌گرداند. اگر شکل هیچ placeholder نداشته باشد مقدار null را بر می‌گرداند. فقط-خواندنی [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائه والد اسلاید را بازمی‌گرداند. فقط-خواندنی [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | خصوصیات فریم خام شکل را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجاتی که شکل مشخص شده حول محور z چرخانده می‌شود را بازمی‌گرداند یا تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعتگرد؛ مقدار منفی نشان‌دهنده چرخش ضد ساعتگرد است. خواندنی/نوشتنی Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | قفل‌های شکل را بازمی‌گرداند. فقط-خواندنی [`IGraphicalObjectLock`](../igraphicalobjectlock). (۲ خصوصیت) |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد شکل را بازمی‌گرداند. فقط-خواندنی [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat را که خصوصیات افکت 3d برای یک شکل است بازمی‌گرداند. توجه: برای برخی انواع شکل که خصوصیات 3d ندارند می‌تواند مقدار null را برگرداند. فقط-خواندنی [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | شناسه داخلی مختص ارائه را که برای استفاده افزونه‌ها یا کدهای دیگر در نظر گرفته شده است، بازمی‌گرداند. از آنجا که این مقدار می‌تواند توسط کاربر یا به‌صورت برنامه‌نویسی تغییر یابد، نباید به‌عنوان کلید یکتای ثابت در نظر گرفته شود. فقط-خواندنی UInt32. همچنین [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض شکل را که بر حسب نقطه اندازه‌گیری می‌شود، بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشهٔ بالایی-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود، بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشهٔ بالایی-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود، بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک شکل در ترتیب z را بازمی‌گرداند. Shapes[0] شکل را در پشت ترتیب z برمی‌گرداند و Shapes[Shapes.Count - 1] شکل را در جلوی ترتیب z برمی‌گرداند. فقط-خواندنی Int32. |

## متدها

| نام | توضیح |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | اگر placeholder‌ای وجود نداشته باشد یک placeholder جدید اضافه می‌کند و خصوصیات placeholder را به یک مورد مشخص تنظیم می‌کند. |
| [ConvertToGroupShape](../../aspose.slides/legacydiagram/converttogroupshape)() | دیاگرام legacy را به گروه شکل قابل ویرایش تبدیل می‌کند. شیء GroupShape ایجاد-شده به گروه شکل والد در همان موقعیت اضافه می‌شود. |
| [ConvertToSmartArt](../../aspose.slides/legacydiagram/converttosmartart)() | دیاگرام legacy را به شیء SmartArt قابل ویرایش تبدیل می‌کند. شیء SmartArt ایجاد-شده به گروه شکل والد در همان موقعیت اضافه می‌شود. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک شکل placeholder پایه را بازمی‌گرداند (شکل از طرح‌بندی و/یا اسلاید اصلی که شکل کنونی از آن ارث می‌برد). اگر شکل کنونی ارث‌بری نشده باشد مقدار null برگردانده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)() | تصویر کوچک (thumbnail) شکل را بازمی‌گرداند. نوع محدوده تصویر کوچک ShapeThumbnailBounds.Shape به‌صورت پیش‌فرض استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تصویر کوچک شکل را بازمی‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | مرزهای بصری شکل که از محتوای رندر شده محاسبه می‌شود را بازمی‌گرداند. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | تعریف می‌کند که این شکل placeholder نیست. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتویات Shape را به‌صورت فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | محتویات Shape را به‌صورت فایل SVG ذخیره می‌کند. |

### همچنین ببینید

* کلاس [GraphicalObject](../graphicalobject)
* رابط [ILegacyDiagram](../ilegacydiagram)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مجموعه [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->