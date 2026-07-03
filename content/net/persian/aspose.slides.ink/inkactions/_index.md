---
title: InkActions
second_title: Aspose.Sildes برای مرجع API .NET
description: نمایانگر ریشهٔ اقدامات جوهر است.
type: docs
weight: 7560
url: /fa/aspose.slides.ink/inkactions/
---
## InkActions کلاس

نمایانگر ریشهٔ اقدامات جوهر است.

```csharp
public class InkActions : GraphicalObject, IInkActions
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه-سفید رندر می‌شود. خواندنی/نوشتنی [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال روی شکل را برمی‌گرداند. فقط خواندنی Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی شکل را برمی‌گرداند. فقط خواندنی [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat را برمی‌گرداند که شامل اثرات پیکسلی اعمال‌شده به یک شکل است. توجه: ممکن است برای برخی انواع شکل‌ها که ویژگی اثر ندارند مقدار null بازگرداند. فقط خواندنی [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شیء FillFormat را برمی‌گرداند که شامل ویژگی‌های قالب‌بندی پرشده برای یک شکل است. توجه: ممکن است برای برخی انواع شکل‌ها که ویژگی پرشده ندارند مقدار null بازگرداند. فقط خواندنی [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ویژگی‌های فریم شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط خواندنی [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع شکل را برمی‌گرداند یا تنظیم می‌کند، بر پایه نقاط. خواندنی/نوشتنی Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | تعیین می‌کند آیا شکل مخفی است یا نه. خواندنی/نوشتنی Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | پیوندهای تعریف‌شده برای کلیک ماوس را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیریت‌کنندهٔ پیوند را برمی‌گرداند. فقط خواندنی [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | پیوند تعریف‌شده برای حرکت ماوس را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینهٔ «علامت‌گذاری به عنوان تزئینی» را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | تعیین می‌کند آیا شکل گروه‌بندی شده است یا نه. فقط خواندنی Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | تعیین می‌کند آیا شکل TextHolder_PPT است یا نه. فقط خواندنی Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat را برمی‌گرداند که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است. توجه: ممکن است برای برخی انواع شکل‌ها که ویژگی خط ندارند مقدار null بازگرداند. فقط خواندنی [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند. نباید null باشد. در صورت نیاز از رشتهٔ خالی استفاده کنید. خواندنی/نوشتنی String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | شناسهٔ یکتای محدودهٔ اسلاید را برمی‌گرداند که در طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop امکان ارجاع قابل اعتماد به شکل را از هر بخشی از سند می‌دهد. فقط خواندنی UInt32. همچنین به [`UniqueId`](../../aspose.slides/shape/uniqueid) مراجعه کنید. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | شیء GroupShape والد را برمی‌گرداند اگر شکل گروه‌بندی شده باشد. در غیر این صورت مقدار null باز می‌گردد. فقط خواندنی [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | جایگیر شکل را برمی‌گرداند. اگر شکل جایگیر نداشته باشد مقدار null باز می‌گردد. فقط خواندنی [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائهٔ والد اسلاید را برمی‌گرداند. فقط خواندنی [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ویژگی‌های فریم خام شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجه‌های چرخش شکل مشخص‌شده حول محور z را برمی‌گرداند یا تنظیم می‌کند. مقدار مثبت نشان‌دهندهٔ چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهندهٔ چرخش ضد ساعت‌گرد است. خواندنی/نوشتنی Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط خواندنی [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 ویژگی) |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد شکل را برمی‌گرداند. فقط خواندنی [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat را برمی‌گرداند که شامل ویژگی‌های اثر 3D برای یک شکل است. توجه: ممکن است برای برخی انواع شکل‌ها که ویژگی 3D ندارند مقدار null بازگرداند. فقط خواندنی [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | شناسهٔ داخلی محدودهٔ ارائه را برمی‌گرداند که برای استفاده توسط افزونه‌ها یا کدهای دیگر در نظر گرفته شده است. از آنجایی که این مقدار می‌تواند توسط کاربر یا برنامه‌نویس تغییر یابد، نباید به عنوان کلید یکتای دائم در نظر گرفته شود. فقط خواندنی UInt32. همچنین به [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid) مراجعه کنید. |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض شکل را برمی‌گرداند یا تنظیم می‌کند، بر پایه نقاط. خواندنی/نوشتنی Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشهٔ بالا-چپ شکل را برمی‌گرداند یا تنظیم می‌کند، بر پایه نقاط. خواندنی/نوشتنی Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشهٔ بالا-چپ شکل را برمی‌گرداند یا تنظیم می‌کند، بر پایه نقاط. خواندنی/نوشتنی Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل در پشت ترتیب z را باز می‌گرداند و Shapes[Shapes.Count - 1] شکل در جلو ترتیب z را باز می‌گرداند. فقط خواندنی Int32. |

## متدها

| نام | توضیح |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | اگر جایگیری وجود نداشته باشد یک جایگیر جدید اضافه می‌کند و ویژگی‌های جایگیر را به مقدار مشخص شده تنظیم می‌کند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک شکل جایگیر پایه را برمی‌گرداند (شکل از طرح‌بندی و/یا اسلاید اصلی که شکل فعلی از آن ارث‌بری می‌کند). اگر شکل فعلی ارث‌بری نشده باشد مقدار null برگردانده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)() | تصویر بندانگشتی شکل را برمی‌گرداند. نوع ShapeThumbnailBounds.Shape به عنوان پیش‌فرض استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تصویر بندانگشتی شکل را برمی‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | مرزهای بصری شکل را که از محتوای رندر شده محاسبه می‌شود، برمی‌گرداند. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | تعریف می‌کند که این شکل جایگیر نیست. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتوای شکل را به عنوان فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | محتوای شکل را به عنوان فایل SVG ذخیره می‌کند. |

### موارد مرتبط

* کلاس [GraphicalObject](../../aspose.slides/graphicalobject)
* رابط [IInkActions](../iinkactions)
* فضای‌نام [Aspose.Slides.Ink](../../aspose.slides.ink)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->