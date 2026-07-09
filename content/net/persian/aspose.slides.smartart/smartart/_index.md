---
title: SmartArt
second_title: Aspose.Sildes برای .NET API مرجع
description: نمایانگر یک نمودار SmartArt
type: docs
weight: 10600
url: /fa/aspose.slides.smartart/smartart/
---
## کلاس SmartArt

نمایانگر یک نمودار SmartArt

```csharp
public class SmartArt : GraphicalObject, ISmartArt
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [AllNodes](../../aspose.slides.smartart/smartart/allnodes) { get; } | مجموعه‌ای از تمام گره‌ها در شیء SmartArt را برمی‌گرداند. فقط‌خواندنی [`ISmartArtNodeCollection`](../ismartartnodecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/نوشتن String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/نوشتن String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه-سفید رندر می‌شود. قابل‌خواندن/نوشتن [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ColorStyle](../../aspose.slides.smartart/smartart/colorstyle) { get; set; } | سبک رنگی شیء SmartArt را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/نوشتن [`SmartArtColorType`](../smartartcolortype). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال روی شکل را برمی‌گرداند. فقط‌خواندنی Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی شکل را برمی‌گرداند. فقط‌خواندنی [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat حاوی افکت‌های پیکسلی اعمال‌شده بر شکل را برمی‌گرداند. توجه: ممکن است برای برخی انواع شکل‌هایی که ویژگی افکت ندارند مقدار null برگرداند. فقط‌خواندنی [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شیء FillFormat حاوی ویژگی‌های قالب‌بندی پر کننده برای یک شکل را برمی‌گرداند. توجه: ممکن است برای برخی انواع شکل‌هایی که ویژگی پر کردن ندارند مقدار null برگرداند. فقط‌خواندنی [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ویژگی‌های چارچوب شکل را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/نوشتن [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط‌خواندنی [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع شکل را بر حسب نقاط می‌گیرد یا تنظیم می‌کند. قابل‌خواندن/نوشتن Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | تعیین می‌کند که شکل مخفی باشد یا نه. قابل‌خواندن/نوشتن Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | پیوندهای ابرمتنی تعریف‌شده برای کلیک ماوس را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/نوشتن [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر پیوندهای ابرمتنی را برمی‌گرداند. فقط‌خواندنی [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | پیوندهای ابرمتنی تعریف‌شده برای حرکت ماوس بر روی شکل را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/نوشتن [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه «علامت‌گذاری به عنوان تزئینی» را می‌گیرد یا تنظیم می‌کند. قابل‌خواندن/نوشتن Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | تعیین می‌کند که شکل گروه‌بندی شده باشد یا نه. فقط‌خواندنی Boolean. |
| [IsReversed](../../aspose.slides.smartart/smartart/isreversed) { get; set; } | وضعیت نمودار SmartArt را نسبت به جهت چپ-به-راست (LTR) یا راست-به-چپ (RTL) برمی‌گرداند یا تنظیم می‌کند، در صورتی که نمودار از وارون‌سازی پشتیبانی کند. قابل‌خواندن/نوشتن Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | تعیین می‌کند که شکل TextHolder_PPT باشد یا نه. فقط‌خواندنی Boolean. |
| [Layout](../../aspose.slides.smartart/smartart/layout) { get; set; } | طرح‌بندی شیء SmartArt را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/نوشتن [`SmartArtLayoutType`](../smartartlayouttype). |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat حاوی ویژگی‌های قالب‌بندی خط برای یک شکل را برمی‌گرداند. توجه: ممکن است برای برخی انواع شکل‌هایی که ویژگی خط ندارند مقدار null برگرداند. فقط‌خواندنی [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند. نباید null باشد. در صورت نیاز می‌توان از رشته خالی استفاده کرد. قابل‌خواندن/نوشتن String. |
| [Nodes](../../aspose.slides.smartart/smartart/nodes) { get; } | مجموعه گره‌های ریشه در شیء SmartArt را برمی‌گرداند. فقط‌خواندنی [`ISmartArtNodeCollection`](../ismartartnodecollection). |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | شناسهٔ یکتا مختص اسلاید را برمی‌گرداند که در طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop اجازه می‌دهد شکل را از هر نقطه‌ای در سند به‌درستی ارجاع دهد. فقط‌خواندنی UInt32. همچنین ببینید [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | شیء GroupShape والد را اگر شکل گروه‌بندی شده باشد برمی‌گرداند. در غیر این صورت null برمی‌گرداند. فقط‌خواندنی [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | جای‌گیرِ شکل را برمی‌گرداند. اگر شکل جای‌گیر نداشته باشد null برمی‌گرداند. فقط‌خواندنی [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائهٔ والد اسلاید را برمی‌گرداند. فقط‌خواندنی [`IPresentation`](../../aspose.slides/ipresentation). |
| [QuickStyle](../../aspose.slides.smartart/smartart/quickstyle) { get; set; } | سبک سریع شیء SmartArt را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/نوشتن [`SmartArtQuickStyleType`](../smartartquickstyletype). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ویژگی‌های چارچوب خام شکل را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/نوشتن [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجاتی که شکل مشخص در اطراف محور z چرخش دارد را برمی‌گرداند یا تنظیم می‌کند. مقدار مثبت نشان‌دهندهٔ چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهندهٔ چرخش پادساعت‌گرد است. قابل‌خواندن/نوشتن Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط‌خواندنی [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 ویژگی) |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد شکل را برمی‌گرداند. فقط‌خواندنی [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat که ویژگی‌های اثر 3-بعدی برای یک شکل را دارد را برمی‌گرداند. توجه: ممکن است برای برخی انواع شکل‌هایی که ویژگی 3-بعدی ندارند مقدار null برگرداند. فقط‌خواندنی [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | شناسهٔ داخلی متمرکز بر ارائه که برای افزونه‌ها یا کدهای دیگر در دسترس است را برمی‌گرداند. از آنجایی که این مقدار می‌تواند توسط کاربر یا برنامه‌نویس تغییر یابد، نباید به‌عنوان کلید یکتا دائمی در نظر گرفته شود. فقط‌خواندنی UInt32. همچنین ببینید [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض شکل را بر حسب نقاط می‌گیرد یا تنظیم می‌کند. قابل‌خواندن/نوشتن Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشهٔ بالا-چپ شکل را بر حسب نقاط می‌گیرد یا تنظیم می‌کند. قابل‌خواندن/نوشتن Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشهٔ بالا-چپ شکل را بر حسب نقاط می‌گیرد یا تنظیم می‌کند. قابل‌خواندن/نوشتن Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل را در پشت‌ترین موقعیت z برمی‌گرداند و Shapes[Shapes.Count - 1] شکل را در جلوی‌ترین موقعیت برمی‌گرداند. فقط‌خواندنی Int32. |

## متدها

| نام | توضیح |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | اگر جای‌گیر وجود نداشته باشد، جای‌گیر جدیدی اضافه می‌کند و ویژگی‌های جای‌گیر را به مقدار مشخص‌شده تنظیم می‌کند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک شکل جای‌گیر پایه (شکل از طرح‌بندی و/یا اسلاید اصلی که شکل فعلی از آن ارث می‌برد) را برمی‌گرداند. اگر شکل فعلی ارث‌برده نشده باشد، مقدار null برگردانده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)() | تصویر بندانگشتی شکل را برمی‌گرداند. به‌طور پیش‌فرض از نوع ShapeThumbnailBounds.Shape استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تصویر بندانگشتی شکل را برمی‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | حدود بصری شکل را که از محتوای رندر‌شده محاسبه می‌شود، برمی‌گرداند. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | تعریف می‌کند که این شکل جای‌گیر نیست. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتوای Shape را به‌صورت فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | محتوای Shape را به‌صورت فایل SVG ذخیره می‌کند. |

### موارد مرتبط

* کلاس [GraphicalObject](../../aspose.slides/graphicalobject)
* رابط [ISmartArt](../ismartart)
* فضای‌نام‌[Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->