---
title: Ink
second_title: مرجع API Aspose.Sildes برای .NET
description: یک شیء جوهر را بر روی اسلاید نشان می‌دهد.
type: docs
weight: 7570
url: /fa/aspose.slides.ink/ink/
---
## کلاس Ink

یک شیء جوهر را روی یک اسلاید نشان می‌دهد.

```csharp
public class Ink : GraphicalObject, IInk
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | مشخص می‌کند که یک شکل در حالت نمایش سیاه-وسفید چگونه رندر شود. خواندن/نوشتن [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال روی شکل را برمی‌گرداند. فقط خواندنی Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی شکل را برمی‌گرداند. فقط خواندنی [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat که شامل اثرات پیکسل اعمال شده بر شکل است را برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی‌های اثر ندارند، می‌تواند null برگرداند. فقط خواندنی [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شیء FillFormat که شامل ویژگی‌های فرمت پر کردن برای یک شکل است را برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی‌های پر کردن ندارند، می‌تواند null برگرداند. فقط خواندنی [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ویژگی‌های قاب شکل را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط خواندنی [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع شکل را به نقطه (point) برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | تعیین می‌کند که آیا شکل مخفی است یا نه. خواندن/نوشتن Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | هایپرلینک تعریف‌شده برای کلیک ماوس را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر هایپرلینک را برمی‌گرداند. فقط خواندنی [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | هایپرلینک تعریف‌شده برای حرکت ماوس را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه «علامت‌گذاری به عنوان تزئینی» را دریافت یا تنظیم می‌کند. خواندن/نوشتن Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | تعیین می‌کند که آیا شکل گروه‌بندی شده است یا نه. فقط خواندنی Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | تعیین می‌کند که آیا شکل TextHolder_PPT است یا نه. فقط خواندنی Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat که شامل ویژگی‌های فرمت خط برای یک شکل است را برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی‌های خط ندارند، می‌تواند null برگرداند. فقط خواندنی [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند. نمی‌تواند null باشد. در صورت نیاز مقدار رشته خالی را استفاده کنید. خواندن/نوشتن String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | شناسه منحصربه‌فرد scoped به اسلاید که برای طول عمر شکل ثابت می‌ماند و امکان ارجاع قابل اعتماد به شکل از هرجایی در سند را فراهم می‌کند را برمی‌گرداند. فقط خواندنی UInt32. همچنین ببینید [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | شیء GroupShape والد را اگر شکل گروه‌بندی شده باشد برمی‌گرداند. در غیر این صورت null برمی‌گرداند. فقط خواندنی [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | جای‌گر (placeholder) شکل را برمی‌گرداند. اگر شکل جای‌گری نداشته باشد، null برمی‌گرداند. فقط خواندنی [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائه (presentation) والد اسلاید را برمی‌گرداند. فقط خواندنی [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ویژگی‌های فریم خام شکل را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجه‌هایی که شکل مشخص شده حول محور z چرخانده می‌شود را برمی‌گرداند یا تنظیم می‌کند. مقدار مثبت نشانگر چرخش ساعتگرد، مقدار منفی نشانگر چرخش پادساعتگرد است. خواندن/نوشتن Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط خواندنی [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (۲ ویژگی) |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد شکل را برمی‌گرداند. فقط خواندنی [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat که شامل ویژگی‌های اثر سه‌بعدی برای یک شکل است را برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی‌های سه‌بعدی ندارند، می‌تواند null برگرداند. فقط خواندنی [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Traces](../../aspose.slides.ink/ink/traces) { get; } | همه ردپاهایی که در عنصر IInk [`IInkTrace`](../iinktrace) موجود هستند را دریافت می‌کند. فقط خواندنی. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | شناسه داخلی scoped به ارائه که برای افزودنی‌ها یا کدهای دیگر استفاده می‌شود را برمی‌گرداند. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویس تغییر یابد، نباید به عنوان کلید یکتا دائمی در نظر گرفته شود. فقط خواندنی UInt32. همچنین ببینید [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض شکل را به نقطه (point) برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشه بالا-چپ شکل را به نقطه (point) برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشه بالا-چپ شکل را به نقطه (point) برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل را در پشت ترتیب z برمی‌گرداند و Shapes[Shapes.Count - 1] شکل را در جلوی ترتیب z برمی‌گرداند. فقط خواندنی Int32. |
| static [InkEffectImages](../../aspose.slides.ink/ink/inkeffectimages) { get; } | مجموعه‌ای از تصاویر سفارشی که برای شبیه‌سازی اثرات بصری براش‌های جوهر استفاده می‌شود را دریافت می‌کند. این تصاویر هنگام رندر جوهر با مقادیر خاص [`InkEffectType`](../inkeffecttype) مانند Galaxy، Rainbow و غیره به کار می‌روند. با فراهم کردن تصاویر خود می‌توانید نحوه نمایش هر اثر جوهر را کنترل کنید. |

## متدها

| نام | توضیح |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | اگر placeholder‌ای موجود نباشد، یک placeholder جدید اضافه می‌کند و ویژگی‌های placeholder را به مقدار مشخص‌شده تنظیم می‌کند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک شکل placeholder پایه (شکل از چینش یا اسلاید اصلی که شکل کنونی از آن به ارث می‌برد) را برمی‌گرداند. اگر شکل کنونی ارث‌برنده نباشد، null برمی‌گردد. |
| [GetImage](../../aspose.slides/shape/getimage)() | تصویر بندانگشتی شکل را برمی‌گرداند. به طور پیش‌فرض نوع ShapeThumbnailBounds.Shape برای حدود تصویر بندانگشتی استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تصویر بندانگشتی شکل را برمی‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | حدود بصری شکل را که از محتوای رندر شده‌اش محاسبه می‌شود دریافت می‌کند. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | تعیین می‌کند که این شکل یک placeholder نیست. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتویات Shape را به صورت فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | محتویات Shape را به صورت فایل SVG ذخیره می‌کند. |

### موارد مرتبط

* class [GraphicalObject](../../aspose.slides/graphicalobject)
* interface [IInk](../iink)
* namespace [Aspose.Slides.Ink](../../aspose.slides.ink)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->