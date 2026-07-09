---
title: OleObjectFrame
second_title: مرجع API Aspose.Sildes برای .NET
description: یک شیء OLE را در یک اسلاید نشان می‌دهد.
type: docs
weight: 9230
url: /fa/aspose.slides/oleobjectframe/
---
## کلاس OleObjectFrame

یک شیء OLE را بر روی یک اسلاید نشان می‌دهد.

```csharp
public class OleObjectFrame : GraphicalObject, IOleObjectFrame
```

## خصوصیات

| نام | توضیح |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [AsIGraphicalObject](../../aspose.slides/oleobjectframe/asigraphicalobject) { get; } | اجازه می‌دهد رابط IGraphicalObject پایه را به‌دست آورد. فقط-خواندنی [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | ویژگی مشخص می‌کند شکل چگونه در حالت نمایش سیاه-سفید رندر می‌شود. قابل خواندن/نوشتن [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال روی شکل را برمی‌گرداند. فقط-خواندنی Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | دادهٔ سفارشی شکل را برمی‌گرداند. فقط-خواندنی [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat را برمی‌گرداند که شامل افکت‌های پیکسلی اعمال شده بر یک شکل است. نکته: می‌تواند برای برخی انواع شکل‌هایی که ویژگی افکت ندارند، null برگرداند. فقط-خواندنی [`IEffectFormat`](../ieffectformat). |
| [EmbeddedData](../../aspose.slides/oleobjectframe/embeddeddata) { get; } | اطلاعات دربارهٔ دادهٔ جاسازی‌شدهٔ OLE را دریافت یا تنظیم می‌کند. قابل خواندن/نوشتن [`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo). |
| [EmbeddedFileLabel](../../aspose.slides/oleobjectframe/embeddedfilelabel) { get; } | نام فایل شیء OLE جاسازی‌شده را برمی‌گرداند. |
| [EmbeddedFileName](../../aspose.slides/oleobjectframe/embeddedfilename) { get; } | مسیر شیء OLE جاسازی‌شده را برمی‌گرداند. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شیء FillFormat را برمی‌گرداند که شامل ویژگی‌های قالب‌بندی پر برای یک شکل است. نکته: می‌تواند برای برخی انواع شکل‌هایی که ویژگی پر ندارند، null برگرداند. فقط-خواندنی [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ویژگی‌های چارچوب شکل را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط-خواندنی [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع شکل را بر حسب نقاط دریافت یا تنظیم می‌کند. قابل خواندن/نوشتن Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | تعیین می‌کند آیا شکل مخفی است یا خیر. قابل خواندن/نوشتن Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | پیوند فرامشی تعریف‌شده برای کلیک ماوس را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر پیوند فرامشی را برمی‌گرداند. فقط-خواندنی [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | پیوند فرامشی تعریف‌شده برای عبور ماوس را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه «علامت‌گذاری به‌عنوان تزئینی» را دریافت یا تنظیم می‌کند. قابل خواندن/نوشتن Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | تعیین می‌کند آیا شکل گروه‌بندی شده است یا خیر. فقط-خواندنی Boolean. |
| [IsObjectIcon](../../aspose.slides/oleobjectframe/isobjecticon) { get; set; } | تعیین می‌کند آیا شیء به‌صورت نماد قابل مشاهده است یا خیر. قابل خواندن/نوشتن Boolean. |
| [IsObjectLink](../../aspose.slides/oleobjectframe/isobjectlink) { get; } | تعیین می‌کند آیا شیء به‌فایل خارجی لینک شده است یا خیر. فقط-خواندنی Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | تعیین می‌کند آیا شکل TextHolder_PPT است یا خیر. فقط-خواندنی Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat را برمی‌گرداند که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است. نکته: می‌تواند برای برخی انواع شکل‌هایی که ویژگی خط ندارند، null برگرداند. فقط-خواندنی [`ILineFormat`](../ilineformat). |
| [LinkFileName](../../aspose.slides/oleobjectframe/linkfilename) { get; } | مسیر کامل به فایلی که لینک شده است را برمی‌گرداند. نام کوتاه فایل استفاده می‌شود. فقط-خواندنی String. |
| [LinkPathLong](../../aspose.slides/oleobjectframe/linkpathlong) { get; set; } | مسیر کامل به فایلی که لینک شده است را برمی‌گرداند. نام طولانی فایل استفاده می‌شود. قابل خواندن/نوشتن String. |
| [LinkPathRelative](../../aspose.slides/oleobjectframe/linkpathrelative) { get; } | مسیر نسبی به فایلی که لینک شده است را در صورت وجود برمی‌گرداند، در غیر این صورت رشتهٔ خالی برمی‌گرداند. فقط-خواندنی String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند. نباید null باشد. در صورت نیاز می‌توان مقدار رشتهٔ خالی را استفاده کرد. قابل خواندن/نوشتن String. |
| [ObjectName](../../aspose.slides/oleobjectframe/objectname) { get; set; } | نام یک شیء را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [ObjectProgId](../../aspose.slides/oleobjectframe/objectprogid) { get; set; } | ProgID یک شیء را برمی‌گرداند. فقط-خواندنی String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | شناسهٔ یکتا scoped به اسلاید را برمی‌گرداند که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کد interop امکان ارجاع مطمئن به شکل را از هرجای سند می‌دهد. فقط-خواندنی UInt32. همچنین ببینید [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | شیء GroupShape والد را برمی‌گرداند اگر شکل گروه‌بندی شده باشد. در غیر این صورت null برمی‌گردد. فقط-خواندنی [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | جایگزار (placeholder) یک شکل را برمی‌گرداند. اگر شکل جایگزینی نداشته باشد، null برمی‌گردد. فقط-خواندنی [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائهٔ والد اسلاید را برمی‌گرداند. فقط-خواندنی [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ویژگی‌های چارچوب شکل خام را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجاتی که شکل مشخص در اطراف محور Z می‌چرخد را برمی‌گرداند یا تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد و مقدار منفی نشان‌دهنده چرخش پاد ساعت‌گرد است. قابل خواندن/نوشتن Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط-خواندنی [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 ویژگی) |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد یک شکل را برمی‌گرداند. فقط-خواندنی [`IBaseSlide`](../ibaseslide). |
| [SubstitutePictureFormat](../../aspose.slides/oleobjectframe/substitutepictureformat) { get; } | شیء خصوصیات پر کردن تصویر OleObject را برمی‌گرداند. فقط-خواندنی [`IPictureFillFormat`](../ipicturefillformat). |
| [SubstitutePictureTitle](../../aspose.slides/oleobjectframe/substitutepicturetitle) { get; set; } | عنوان برای نماد OleObject را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat را برمی‌گرداند که شامل ویژگی‌های افکت ۳بعدی برای یک شکل است. نکته: می‌تواند برای برخی انواع شکل‌هایی که ویژگی ۳بعدی ندارند، null برگرداند. فقط-خواندنی [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | شناسهٔ داخلی scoped به ارائه را برمی‌گرداند که برای استفاده توسط افزونه‌ها یا کدهای دیگر در نظر گرفته شده است. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویس تغییر یابد، نمی‎بایست به عنوان کلید یکتا دائمی در نظر گرفته شود. فقط-خواندنی UInt32. همچنین ببینید [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [UpdateAutomatic](../../aspose.slides/oleobjectframe/updateautomatic) { get; set; } | تعیین می‌کند آیا شیء جاسازی-شده لینک‌شده به‌صورت خودکار هنگام باز یا چاپ ارائه بروز می‌شود یا نه. قابل خواندن/نوشتن Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض یک شکل را بر حسب نقاط دریافت یا تنظیم می‌کند. قابل خواندن/نوشتن Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشهٔ بالا-چپ شکل را بر حسب نقاط دریافت یا تنظیم می‌کند. قابل خواندن/نوشتن Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشهٔ بالا-چپ شکل را بر حسب نقاط دریافت یا تنظیم می‌کند. قابل خواندن/نوشتن Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک شکل در ترتیب Z را برمی‌گرداند. Shapes[0] شکل پشت‌ترین در ترتیب Z را برمی‌گرداند و Shapes[Shapes.Count - 1] شکل جلوی‌ترین را برمی‌گرداند. فقط-خواندنی Int32. |

## متدها

| نام | توضیح |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | اگر جایگزین وجود نداشته باشد یک جایگزین جدید اضافه می‌کند و ویژگی‌های جایگزین را به مقدار مشخص‌شده تنظیم می‌کند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک شکل جایگزین پایه را برمی‌گرداند (شکلی ازچیدمان و/یا اسلاید اصلی که شکل فعلی از آن ارث‌بری می‌کند). اگر شکل فعلی ارث‌بری نشود، null برگردانده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)() | تصویر کوچک شکل را برمی‌گرداند. به‌صورت پیش‌فرض از نوع ShapeThumbnailBounds.Shape برای محدوده تصویر کوچک استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تصویر کوچک شکل را برمی‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | حدود بصری شکل را که از محتوا رندرشده محاسبه می‌شود، دریافت می‌کند. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | تعریف می‌کند که این شکل یک جایگزین نیست. |
| [SetEmbeddedData](../../aspose.slides/oleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | اطلاعات دربارهٔ دادهٔ جاسازی‌شدهٔ OLE را تنظیم می‌کند. این متد ویژگی‌های شیء را برای بازتاب دادهٔ جدید تغییر می‌دهد و پرچم IsObjectLink را به false تنظیم می‌کند، که نشان می‌دهد شیء OLE جاسازی‌شده است. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتوای Shape را به‌عنوان فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | محتوای Shape را به‌عنوان فایل SVG ذخیره می‌کند. |

### مثال‌ها

مثال زیر نشان می‌دهد چگونه به فریم‌های شیء OLE دسترسی پیدا کنید.

```csharp
[C#]
// فایل PPTX را به یک شیء Presentation بارگذاری می‌کند
using (Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx"))
{
    // به اولین اسلاید دسترسی می‌یابد
    ISlide sld = pres.Slides[0];
    // شکل را به OleObjectFrame تبدیل می‌کند
    OleObjectFrame oleObjectFrame = sld.Shapes[0] as OleObjectFrame;
    // شیء OLE را می‌خواند و بر روی دیسک می‌نویسد
    if (oleObjectFrame != null)
    {
        // داده‌های فایل جاسازی‌شده را دریافت می‌کند
        byte[] data = oleObjectFrame.EmbeddedData.EmbeddedFileData;
        // پسوند فایل جاسازی‌شده را دریافت می‌کند
        string fileExtention = oleObjectFrame.EmbeddedData.EmbeddedFileExtension;
        // مسیر ذخیره‌سازی فایل استخراج‌شده را ایجاد می‌کند
        string extractedPath = "excelFromOLE_out" + fileExtention;
        // داده‌های استخراج‌شده را ذخیره می‌کند
        using (FileStream fstr = new FileStream(extractedPath, FileMode.Create, FileAccess.Write))
        {
            fstr.Write(data, 0, data.Length);
        }
    }
}
```

### موارد مرتبط

* کلاس [GraphicalObject](../graphicalobject)
* اینترفیس [IOleObjectFrame](../ioleobjectframe)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مونتاژ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->