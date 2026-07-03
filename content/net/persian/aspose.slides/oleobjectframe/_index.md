---
title: OleObjectFrame
second_title: مرجع API Aspose.Sildes برای .NET
description: شیء OLE را بر روی یک اسلاید نشان می‌دهد.
type: docs
weight: 9230
url: /fa/aspose.slides/oleobjectframe/
---
## کلاس OleObjectFrame

شیء OLE را بر روی یک اسلاید نشان می‌دهد.

```csharp
public class OleObjectFrame : GraphicalObject, IOleObjectFrame
```

## خصوصیات

| نام | توضیح |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن String. |
| [AsIGraphicalObject](../../aspose.slides/oleobjectframe/asigraphicalobject) { get; } | اجازه می‌دهد رابط IGraphicalObject پایه را دریافت کند. فقط-خواندنی [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | خصوصیت تعیین می‌کند که یک شکل چگونه در حالت نمایش سیاه‌وسفید رندرن می‌شود. قابل خواندن/قابل نوشتن [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال روی شکل را برمی‌گرداند. فقط-خواندنی Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی شکل را برمی‌گرداند. فقط-خواندنی [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat را برمی‌گرداند که شامل اثرات پیکسل اعمال‌شده بر یک شکل است. توجه: ممکن است برای برخی انواع شکل‌ها که خاصیت اثر ندارند، مقدار null برگرداند. فقط-خواندنی [`IEffectFormat`](../ieffectformat). |
| [EmbeddedData](../../aspose.slides/oleobjectframe/embeddeddata) { get; } | اطلاعات درباره داده‌های جاسازی شده OLE را دریافت یا تنظیم می‌کند. قابل خواندن/قابل نوشتن [`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo). |
| [EmbeddedFileLabel](../../aspose.slides/oleobjectframe/embeddedfilelabel) { get; } | نام فایل شیء OLE جاسازی‌شده را برمی‌گرداند. |
| [EmbeddedFileName](../../aspose.slides/oleobjectframe/embeddedfilename) { get; } | مسیر شیء OLE جاسازی‌شده را برمی‌گرداند. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شیء FillFormat را برمی‌گرداند که شامل ویژگی‌های قالب‌بندی پر برای یک شکل است. توجه: ممکن است برای برخی انواع شکل‌ها که خاصیت پر ندارند، مقدار null برگرداند. فقط-خواندنی [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ویژگی‌های فریم شکل را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط-خواندنی [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع شکل را که بر حسب نقاط اندازه‌گیری می‌شود، دریافت یا تنظیم می‌کند. قابل خواندن/قابل نوشتن Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | مشخص می‌کند آیا شکل مخفی است یا خیر. قابل خواندن/قابل نوشتن Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | پیوندیابی تعریف‌شده برای کلیک ماوس را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر پیوندها را برمی‌گرداند. فقط-خواندنی [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | پیوندی که برای حرکت ماوس فوق تعریف شده است را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه 'Mark as decorative' را دریافت یا تنظیم می‌کند. قابل خواندن/قابل نوشتن Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | مشخص می‌کند آیا شکل گروه‌بندی شده است یا خیر. فقط-خواندنی Boolean. |
| [IsObjectIcon](../../aspose.slides/oleobjectframe/isobjecticon) { get; set; } | مشخص می‌کند آیا شیء به‌صورت آیکون قابل مشاهده است یا خیر. قابل خواندن/قابل نوشتن Boolean. |
| [IsObjectLink](../../aspose.slides/oleobjectframe/isobjectlink) { get; } | مشخص می‌کند آیا شیء به یک فایل خارجی پیوند داده شده است یا خیر. فقط-خواندنی Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | مشخص می‌کند آیا شکل TextHolder_PPT است یا خیر. فقط-خواندنی Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat را برمی‌گرداند که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است. توجه: ممکن است برای برخی انواع شکل‌ها که خاصیت خط ندارند، مقدار null برگرداند. فقط-خواندنی [`ILineFormat`](../ilineformat). |
| [LinkFileName](../../aspose.slides/oleobjectframe/linkfilename) { get; } | مسیر کامل به فایل پیوندخورده را برمی‌گرداند. از نام فایل کوتاه استفاده می‌شود. فقط-خواندنی String. |
| [LinkPathLong](../../aspose.slides/oleobjectframe/linkpathlong) { get; set; } | مسیر کامل به فایل پیوندخورده را برمی‌گرداند. از نام فایل بلند استفاده می‌شود. قابل خواندن/قابل نوشتن String. |
| [LinkPathRelative](../../aspose.slides/oleobjectframe/linkpathrelative) { get; } | مسیر نسبی به فایل پیوندخورده را در صورت وجود برمی‌گرداند؛ در غیر این صورت رشته خالی برمی‌گرداند. فقط-خواندنی String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند. نباید null باشد. در صورت نیاز می‌توان از رشته خالی استفاده کرد. قابل خواندن/قابل نوشتن String. |
| [ObjectName](../../aspose.slides/oleobjectframe/objectname) { get; set; } | نام یک شیء را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن String. |
| [ObjectProgId](../../aspose.slides/oleobjectframe/objectprogid) { get; set; } | ProgID یک شیء را برمی‌گرداند. فقط-خواندنی String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | شناسه یکتا محدود به اسلاید را برمی‌گرداند که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop اجازه می‌دهد به‌طور قابل اطمینان از هر نقطه‌ای در سند به شکل ارجاع دهند. فقط-خواندنی UInt32. همچنین ببینید [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | اگر شکل گروه‌بندی شده باشد، شیء والد GroupShape را برمی‌گرداند؛ در غیر این صورت مقدار null برمی‌گرداند. فقط-خواندنی [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | متغیر placeholder برای یک شکل را برمی‌گرداند. اگر شکل placeholder نداشته باشد، مقدار null برمی‌گرداند. فقط-خواندنی [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائه والد اسلاید را برمی‌گرداند. فقط-خواندنی [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ویژگی‌های فریم خام شکل را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجاتی که شکل مشخص حول محور z چرخیده است را برمی‌گرداند یا تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پادساعت‌گرد است. قابل خواندن/قابل نوشتن Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط-خواندنی [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 خصوصیت) |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد یک شکل را برمی‌گرداند. فقط-خواندنی [`IBaseSlide`](../ibaseslide). |
| [SubstitutePictureFormat](../../aspose.slides/oleobjectframe/substitutepictureformat) { get; } | شیء خواص پر کردن تصویر OleObject را برمی‌گرداند. فقط-خواندنی [`IPictureFillFormat`](../ipicturefillformat). |
| [SubstitutePictureTitle](../../aspose.slides/oleobjectframe/substitutepicturetitle) { get; set; } | عنوان برای آیکون OleObject را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن String. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat را برمی‌گرداند که شامل ویژگی‌های اثر 3D برای یک شکل است. توجه: ممکن است برای برخی انواع شکل‌ها که خاصیت 3D ندارند، مقدار null برگرداند. فقط-خواندنی [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | یک شناسه داخلی محدود به ارائه را برمی‌گرداند که برای استفاده توسط افزونه‌ها یا کدهای دیگر در نظر گرفته شده است. از آنجا که این مقدار می‌تواند توسط کاربر یا برنامه‌نویسی مجدداً اختصاص یابد، نباید به‌عنوان کلید یکتا دائم در نظر گرفته شود. فقط-خواندنی UInt32. همچنین ببینید [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [UpdateAutomatic](../../aspose.slides/oleobjectframe/updateautomatic) { get; set; } | مشخص می‌کند آیا شیء جاسازی‌شده پیوندخورده به‌طور خودکار هنگام باز شدن یا چاپ ارائه به‌روزرسانی می‌شود یا خیر. قابل خواندن/قابل نوشتن Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض شکل را که بر حسب نقاط اندازه‌گیری می‌شود، دریافت یا تنظیم می‌کند. قابل خواندن/قابل نوشتن Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشه بالایی چپ شکل را که بر حسب نقاط اندازه‌گیری می‌شود، دریافت یا تنظیم می‌کند. قابل خواندن/قابل نوشتن Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشه بالایی چپ شکل را که بر حسب نقاط اندازه‌گیری می‌شود، دریافت یا تنظیم می‌کند. قابل خواندن/قابل نوشتن Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل در انتهای ز-نظم (پشت) را برمی‌گرداند و Shapes[Shapes.Count - 1] شکل در جلوی ز-نظم (جلو) را برمی‌گرداند. فقط-خواندنی Int32. |

## متدها

| نام | توضیح |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | اگر placeholder وجود نداشته باشد، یک placeholder جدید اضافه می‌کند و ویژگی‌های placeholder را به مورد مشخص شده تنظیم می‌کند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک شکل placeholder پایه را برمی‌گرداند (شکلی از طرح‌بندی و/یا اسلاید اصلی که شکل جاری از آن به ارث برده است). اگر شکل جاری به ارث نرود، مقدار null برگردانده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)() | تصویر بند انگشتی شکل را برمی‌گرداند. به‌صورت پیش‌فرض، نوع ShapeThumbnailBounds.Shape برای حدود تصویر بند انگشتی استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تصویر بند انگشتی شکل را برمی‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | حدود بصری شکل را که از محتوای رندره شده محاسبه می‌شود، دریافت می‌کند. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | مشخص می‌کند که این شکل placeholder نیست. |
| [SetEmbeddedData](../../aspose.slides/oleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | اطلاعات درباره داده‌های جاسازی شده OLE را تنظیم می‌کند. این متد ویژگی‌های شیء را برای بازتاب داده‌های جدید تغییر می‌دهد و پرچم IsObjectLink را به false تنظیم می‌کند، که نشان می‌دهد شیء OLE جاسازی شده است. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتوای Shape را به‌صورت فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | محتوای Shape را به‌صورت فایل SVG ذخیره می‌کند. |

### مثال‌ها

مثال زیر نشان می‌دهد چگونه به چارچوب‌های شیء OLE دسترسی پیدا کنیم.

```csharp
[C#]
// فایل PPTX را به یک شیء ارائه بارگذاری می‌کند
using (Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx"))
{
    // به اولین اسلاید دسترسی می‌یابد
    ISlide sld = pres.Slides[0];
    // شکل را به OleObjectFrame تبدیل می‌کند
    OleObjectFrame oleObjectFrame = sld.Shapes[0] as OleObjectFrame;
    // شیء OLE را می‌خواند و بر روی دیسک می‌نویسد
    if (oleObjectFrame != null)
    {
        // داده‌های فایل جاسازی شده را دریافت می‌کند
        byte[] data = oleObjectFrame.EmbeddedData.EmbeddedFileData;
        // پسوند فایل جاسازی شده را دریافت می‌کند
        string fileExtention = oleObjectFrame.EmbeddedData.EmbeddedFileExtension;
        // مسیر برای ذخیره‌سازی فایل استخراج‌شده ایجاد می‌کند
        string extractedPath = "excelFromOLE_out" + fileExtention;
        // داده‌های استخراج‌شده را ذخیره می‌کند
        using (FileStream fstr = new FileStream(extractedPath, FileMode.Create, FileAccess.Write))
        {
            fstr.Write(data, 0, data.Length);
        }
    }
}
```

### See Also

* class [GraphicalObject](../graphicalobject)
* interface [IOleObjectFrame](../ioleobjectframe)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->