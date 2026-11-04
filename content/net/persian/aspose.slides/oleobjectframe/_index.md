---
title: OleObjectFrame
second_title: مرجع API Aspose.Sildes برای .NET
description: نمایش یک شیء OLE روی اسلاید.
type: docs
weight: 9250
url: /fa/aspose.slides/oleobjectframe/
---
## OleObjectFrame کلاس

نمایش یک شیء OLE روی اسلاید.

```csharp
public class OleObjectFrame : GraphicalObject, IOleObjectFrame
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | مقدار یا تنظیم متن جایگزین مرتبط با یک شکل. قابل خواندن/نوشتنی String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | مقدار یا تنظیم عنوان متن جایگزین مرتبط با یک شکل. قابل خواندن/نوشتنی String. |
| [AsIGraphicalObject](../../aspose.slides/oleobjectframe/asigraphicalobject) { get; } | امکان دریافت رابط پایه IGraphicalObject. فقط خواندنی [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | ویژگی تعیین می‌کند شکل در حالت نمایش سیاه-سفید چگونه رندر شود. قابل خواندن/نوشتنی [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال روی شکل را برمی‌گرداند. فقط خواندنی Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی شکل را برمی‌گرداند. فقط خواندنی [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat را که شامل اثرات پیکسلی اعمال شده به شکل است برمی‌گرداند. توجه: برای برخی انواع شکل‌ها که ویژگی اثر ندارند می‌تواند null بازگرداند. فقط خواندنی [`IEffectFormat`](../ieffectformat). |
| [EmbeddedData](../../aspose.slides/oleobjectframe/embeddeddata) { get; } | دریافت یا تنظیم اطلاعات درباره داده‌های توکار OLE. قابل خواندن/نوشتنی [`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo). |
| [EmbeddedFileLabel](../../aspose.slides/oleobjectframe/embeddedfilelabel) { get; } | نام فایل شیء OLE توکار را برمی‌گرداند |
| [EmbeddedFileName](../../aspose.slides/oleobjectframe/embeddedfilename) { get; } | مسیر شیء OLE توکار را برمی‌گرداند |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شیء FillFormat را که شامل ویژگی‌های قالب‌بندی پرکننده برای یک شکل است برمی‌گرداند. توجه: برای برخی انواع شکل‌ها که ویژگی پرکننده ندارند می‌تواند null بازگرداند. فقط خواندنی [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ویژگی‌های قاب شکل را مقدار یا تنظیم می‌کند. قابل خواندن/نوشتنی [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط خواندنی [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع شکل را برحسب پوینت تنظیم یا دریافت می‌کند. قابل خواندن/نوشتنی Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | تعیین می‌کند آیا شکل مخفی باشد یا نه. قابل خواندن/نوشتنی Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | پیوندهای تعریف‌شده برای کلیک ماوس را مقدار یا تنظیم می‌کند. قابل خواندن/نوشتنی [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر پیوندها را برمی‌گرداند. فقط خواندنی [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | پیوند تعریف‌شده برای حرکت ماوس را مقدار یا تنظیم می‌کند. قابل خواندن/نوشتنی [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه «علامت‌گذاری به‌عنوان تزئینی» را دریافت یا تنظیم می‌کند. قابل خواندن/نوشتنی Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | تعیین می‌کند آیا شکل گروه‌بندی شده است یا نه. فقط خواندنی Boolean. |
| [IsObjectIcon](../../aspose.slides/oleobjectframe/isobjecticon) { get; set; } | تعیین می‌کند آیا شیء به‌صورت نماد قابل مشاهده است یا نه. قابل خواندن/نوشتنی Boolean. |
| [IsObjectLink](../../aspose.slides/oleobjectframe/isobjectlink) { get; } | تعیین می‌کند آیا شیء به فایل خارجی پیوند دارد یا نه. فقط خواندنی Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | تعیین می‌کند آیا شکل TextHolder_PPT است یا نه. فقط خواندنی Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat را که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است برمی‌گرداند. توجه: برای برخی انواع شکل‌ها که ویژگی خط ندارند می‌تواند null بازگرداند. فقط خواندنی [`ILineFormat`](../ilineformat). |
| [LinkFileName](../../aspose.slides/oleobjectframe/linkfilename) { get; } | مسیر کامل فایل پیوندی را برمی‌گرداند. نام کوتاه فایل استفاده می‌شود. فقط خواندنی String. |
| [LinkPathLong](../../aspose.slides/oleobjectframe/linkpathlong) { get; set; } | مسیر کامل فایل پیوندی را برمی‌گرداند. نام بلند فایل استفاده می‌شود. قابل خواندن/نوشتنی String. |
| [LinkPathRelative](../../aspose.slides/oleobjectframe/linkpathrelative) { get; } | مسیر نسبی فایل پیوندی را در صورت وجود برمی‌گرداند، در غیر این صورت رشتهٔ خالی را برمی‌گرداند. فقط خواندنی String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام شکل را مقدار یا تنظیم می‌کند. نباید null باشد. در صورت نیاز می‌توانید مقدار رشتهٔ خالی استفاده کنید. قابل خواندن/نوشتنی String. |
| [ObjectName](../../aspose.slides/oleobjectframe/objectname) { get; set; } | نام شیء را مقدار یا تنظیم می‌کند. قابل خواندن/نوشتنی String. |
| [ObjectProgId](../../aspose.slides/oleobjectframe/objectprogid) { get; set; } | ProgID شیء را برمی‌گرداند. فقط خواندنی String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | شناسهٔ یکتا محدود به اسلاید که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop امکان ارجاع قابل اطمینان به شکل را از هرجای سند می‌دهد. فقط خواندنی UInt32. همچنین نگاه کنید به [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | شیء GroupShape والد را در صورت گروه‌بندی شکل برمی‌گرداند. در غیر این صورت null. فقط خواندنی [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | محل‌نگهدارندهٔ شکل را برمی‌گرداند. اگر شکل محل‌نگهدارنده نداشته باشد null برمی‌گرداند. فقط خواندنی [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائهٔ والد اسلاید را برمی‌گرداند. فقط خواندنی [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ویژگی‌های خام قاب شکل را مقدار یا تنظیم می‌کند. قابل خواندن/نوشتنی [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجه‌های چرخش مشخص‌شدهٔ شکل حول محور z را مقدار یا تنظیم می‌کند. مقدار مثبت نشانگر چرخش ساعت‌گرد؛ مقدار منفی نشانگر چرخش پادساعت‌گرد است. قابل خواندن/نوشتنی Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط خواندنی [`IGraphicalObjectLock`](../igraphicalobjectlock). (۲ ویژگی) |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد یک شکل را برمی‌گرداند. فقط خواندنی [`IBaseSlide`](../ibaseslide). |
| [SubstitutePictureFormat](../../aspose.slides/oleobjectframe/substitutepictureformat) { get; } | شیء ویژگی‌های پرکننده تصویر OleObject را برمی‌گرداند. فقط خواندنی [`IPictureFillFormat`](../ipicturefillformat). |
| [SubstitutePictureTitle](../../aspose.slides/oleobjectframe/substitutepicturetitle) { get; set; } | عنوان نماد OleObject را مقدار یا تنظیم می‌کند. قابل خواندن/نوشتنی String. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat را که شامل ویژگی‌های اثر 3D برای یک شکل است برمی‌گرداند. توجه: برای برخی انواع شکل‌ها که ویژگی 3D ندارند می‌تواند null بازگرداند. فقط خواندنی [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | شناسهٔ داخلی محدود به ارائه که برای استفاده افزونه‌ها یا کدهای دیگر در نظر گرفته شده است. از آنجا که این مقدار می‌تواند توسط کاربر یا برنامه‌نویس تغییر یابد، نباید به عنوان کلید یکتای پایدار در نظر گرفته شود. فقط خواندنی UInt32. همچنین نگاه کنید به [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [UpdateAutomatic](../../aspose.slides/oleobjectframe/updateautomatic) { get; set; } | تعیین می‌کند آیا شیء توکار پیوند شده هنگام باز یا چاپ ارائه به‌صورت خودکار به‌روز شود یا نه. قابل خواندن/نوشتنی Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض شکل را برحسب پوینت مقدار یا تنظیم می‌کند. قابل خواندن/نوشتنی Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشهٔ بالا-چپ شکل را برحسب پوینت مقدار یا تنظیم می‌کند. قابل خواندن/نوشتنی Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشهٔ بالا-چپ شکل را برحسب پوینت مقدار یا تنظیم می‌کند. قابل خواندن/نوشتنی Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل در پشت‌ترین موقعیت z را برمی‌گرداند و Shapes[Shapes.Count - 1] شکل در جلوی‌ترین موقعیت z را برمی‌گرداند. فقط خواندنی Int32. |

## متدها

| نام | توضیح |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | اگر placeholder ای وجود نداشته باشد، یک placeholder جدید اضافه کرده و ویژگی‌های placeholder را به مقدار مشخص‌شده تنظیم می‌کند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک شکل placeholder پایه (شکل از طرح‌بندی و/یا اسلاید اصلی که شکل فعلی از آن به ارث می‌برد) را برمی‌گرداند. اگر شکل فعلی ارث‌برده نشود، null برمی‌گردد. |
| [GetImage](../../aspose.slides/shape/getimage)() | تصویر بندانگشتی شکل را برمی‌گرداند. به‌طور پیش‌فرض نوع ShapeThumbnailBounds.Shape استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تصویر بندانگشتی شکل را برمی‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | مرزهای بصری شکل را که از محتوای رندر‌شده محاسبه می‌شود، دریافت می‌کند. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | تعریف می‌کند که این شکل placeholder نیست. |
| [SetEmbeddedData](../../aspose.slides/oleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | اطلاعات درباره داده‌های توکار OLE را تنظیم می‌کند. این متد ویژگی‌های شیء را طوری تغییر می‌دهد که داده‌های جدید منعکس شوند و پرچم IsObjectLink را به false تنظیم می‌کند، نشان می‌دهد که شیء OLE توکار است. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتویات Shape را به‌صورت فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | محتویات Shape را به‌صورت فایل SVG ذخیره می‌کند. |

### مثال‌ها

مثال زیر نشان می‌دهد چگونه به فریم‌های شیء OLE دسترسی پیدا کنید.

```csharp
[C#]
// PPTX را به یک شیء ارائه بارگذاری می‌کند
using (Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx"))
{
    // به اولین اسلاید دسترسی می‌یابد
    ISlide sld = pres.Slides[0];
    // شکل را به OleObjectFrame تبدیل می‌کند
    OleObjectFrame oleObjectFrame = sld.Shapes[0] as OleObjectFrame;
    // شیء OLE را می‌خواند و بر روی دیسک می‌نویسد
    if (oleObjectFrame != null)
    {
        // داده‌های فایل توکار را دریافت می‌کند
        byte[] data = oleObjectFrame.EmbeddedData.EmbeddedFileData;
        // پسوند فایل توکار را دریافت می‌کند
        string fileExtention = oleObjectFrame.EmbeddedData.EmbeddedFileExtension;
        // مسیری برای ذخیره‌سازی فایل استخراج‌شده ایجاد می‌کند
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
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->