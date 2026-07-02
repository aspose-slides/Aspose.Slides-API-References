---
title: SmartArt
second_title: مرجع API Aspose.Sildes برای .NET
description: نمودار SmartArt را نمایندگی می‌کند
type: docs
weight: 10600
url: /fa/aspose.slides.smartart/smartart/
---
## کلاس SmartArt

نمودار SmartArt را نمایندگی می‌کند

```csharp
public class SmartArt : GraphicalObject, ISmartArt
```

## ویژگی‌ها

| نام | توضیحات |
| --- | --- |
| [AllNodes](../../aspose.slides.smartart/smartart/allnodes) { get; } | مجموعه‌ای از تمام گره‌های موجود در شیء SmartArt را بر می‌گرداند. فقط-خواندنی [`ISmartArtNodeCollection`](../ismartartnodecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | متن جایگزین مرتبط با یک شکل را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | عنوان متن جایگزین مرتبط با یک شکل را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | ویژگی مشخص می‌کند شکل چگونه در حالت نمایش سیاه-سفید رندر می‌شود. خواندنی/نوشتنی [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ColorStyle](../../aspose.slides.smartart/smartart/colorstyle) { get; set; } | سبک رنگ شیء SmartArt را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`SmartArtColorType`](../smartartcolortype). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال روی شکل را بر می‌گرداند. فقط-خواندنی Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی شکل را بر می‌گرداند. فقط-خواندنی [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat را بر می‌گرداند که شامل اثرات پیکسلی اعمال شده بر یک شکل است. توجه: برای برخی انواع شکل‌ها که ویژگی اثر ندارند، می‌تواند null برگرداند. فقط-خواندنی [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شیء FillFormat را بر می‌گرداند که شامل ویژگی‌های قالب‌بندی پر کردن برای یک شکل است. توجه: برای برخی انواع شکل‌ها که ویژگی پر کردن ندارند، می‌تواند null برگرداند. فقط-خواندنی [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ویژگی‌های قاب شکل را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | قفل‌های شکل را بر می‌گرداند. فقط-خواندنی [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع شکل را بر می‌گرداند یا تنظیم می‌کند، به نقاط اندازه‌گیری می‌شود. خواندنی/نوشتنی Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | مشخص می‌کند آیا شکل مخفی است یا خیر. خواندنی/نوشتنی Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | پیوندهای تعریف‌شده برای کلیک ماوس را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر پیوندها را بر می‌گرداند. فقط-خواندنی [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | پیوند تعریف‌شده برای عبور ماوس را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه 'Mark as decorative' را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | تعیین می‌کند آیا شکل گروه‌بندی شده است یا خیر. فقط-خواندنی Boolean. |
| [IsReversed](../../aspose.slides.smartart/smartart/isreversed) { get; set; } | وضعیت نمودار SmartArt را نسبت به جهت چپ-به-راست (LTR) یا راست-به-چپ (RTL) باز می‌گرداند یا تنظیم می‌کند، اگر نمودار از معکوس کردن پشتیبانی کند. خواندنی/نوشتنی Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | تعیین می‌کند آیا شکل TextHolder_PPT است یا خیر. فقط-خواندنی Boolean. |
| [Layout](../../aspose.slides.smartart/smartart/layout) { get; set; } | چیدمان شیء SmartArt را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`SmartArtLayoutType`](../smartartlayouttype). |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat را بر می‌گرداند که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است. توجه: برای برخی انواع شکل‌ها که ویژگی خط ندارند، می‌تواند null برگرداند. فقط-خواندنی [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک شکل را بر می‌گرداند یا تنظیم می‌کند. نباید null باشد. در صورت نیاز می‌توان مقدار رشتهٔ خالی استفاده کرد. خواندنی/نوشتنی String. |
| [Nodes](../../aspose.slides.smartart/smartart/nodes) { get; } | مجموعه‌ای از گره‌های ریشه در شیء SmartArt را بر می‌گرداند. فقط-خواندنی [`ISmartArtNodeCollection`](../ismartartnodecollection). |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | شناسهٔ یکتا scoped به اسلاید را بر می‌گرداند که در طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop امکان ارجاع قابل اطمینان به شکل را از هرجای سند می‌دهد. فقط-خواندنی UInt32. همچنین ببینید [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | در صورتی که شکل گروه‌بندی شده باشد، شیء GroupShape والد را بر می‌گرداند. در غیر این صورت null بر می‌گرداند. فقط-خواندنی [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | جای‌دار شکل را بر می‌گرداند. اگر شکل جای‌دار نداشته باشد، null بر می‌گرداند. فقط-خواندنی [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائهٔ والد اسلاید را بر می‌گرداند. فقط-خواندنی [`IPresentation`](../../aspose.slides/ipresentation). |
| [QuickStyle](../../aspose.slides.smartart/smartart/quickstyle) { get; set; } | سبک سریع شیء SmartArt را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`SmartArtQuickStyleType`](../smartartquickstyletype). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ویژگی‌های چارچوب خام شکل را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجه‌های چرخش شکل مشخص شده حول محور z را بر می‌گرداند یا تنظیم می‌کند. مقدار مثبت نشانگر چرخش ساعت‌گرد، مقدار منفی نشانگر چرخش ضد ساعت‌گرد است. خواندنی/نوشتنی Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | قفل‌های شکل را بر می‌گرداند. فقط-خواندنی [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (۲ ویژگی) |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد یک شکل را بر می‌گرداند. فقط-خواندنی [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat را بر می‌گرداند که شامل ویژگی‌های اثر سه‌بعدی برای یک شکل است. توجه: برای برخی انواع شکل‌ها که ویژگی سه‌بعدی ندارند، می‌تواند null برگرداند. فقط-خواندنی [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | شناسهٔ داخلی scoped به ارائه که برای استفاده افزونه‌ها یا کدهای دیگر در نظر گرفته شده است را بر می‌گرداند. از آنجا که این مقدار می‌تواند توسط کاربر یا برنامه‌نویسی مجدداً اختصاص داده شود، نباید به عنوان کلید یکتای دائمی در نظر گرفته شود. فقط-خواندنی UInt32. همچنین ببینید [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض شکل را بر می‌گرداند یا تنظیم می‌کند، به نقاط اندازه‌گیری می‌شود. خواندنی/نوشتنی Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشهٔ بالا-چپ شکل را بر می‌گرداند یا تنظیم می‌کند، به نقاط اندازه‌گیری می‌شود. خواندنی/نوشتنی Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشهٔ بالا-چپ شکل را بر می‌گرداند یا تنظیم می‌کند، به نقاط اندازه‌گیری می‌شود. خواندنی/نوشتنی Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک شکل در ترتیب z را بر می‌گرداند. Shapes[0] شکل در پشت ترتیب z را بر می‌گرداند و Shapes[Shapes.Count - 1] شکل در جلو ترتیب z را بر می‌گرداند. فقط-خواندنی Int32. |

## متد‌ها

| نام | توضیحات |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | اگر جای‌داری وجود نداشته باشد، یک جای‌دار جدید اضافه می‌کند و ویژگی‌های جای‌دار را به مقدار مشخص‌شده تنظیم می‌کند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک شکل جای‌دار پایه (شکلی از طرح‌بندی و/یا اسلاید اصلی که شکل جاری از آن ارث می‌برد) را بر می‌گرداند. اگر شکل جاری ارث نبرده باشد، null بر می‌گرداند. |
| [GetImage](../../aspose.slides/shape/getimage)() | تصویر کوچک شکل را بر می‌گرداند. به طور پیش‌فرض از نوع ShapeThumbnailBounds.Shape برای تعیین حدود تصویر کوچک استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تصویر کوچک شکل را بر می‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | حدود بصری شکل را که از محتوای رندر شده محاسبه می‌شود، بر می‌گرداند. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | مشخص می‌کند که این شکل جای‌دار نیست. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتوای شکل را به عنوان فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | محتوای شکل را به عنوان فایل SVG ذخیره می‌کند. |

### موارد مرتبط

* کلاس [GraphicalObject](../../aspose.slides/graphicalobject)
* رابط [ISmartArt](../ismartart)
* فضای‌نام [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* مجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->