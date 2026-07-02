---
title: Slide
second_title: Aspose.Sildes برای .NET API Reference
description: یک اسلاید را در یک ارائه نمایندگی می‌کند.
type: docs
weight: 9960
url: /fa/aspose.slides/slide/
---
## کلاس Slide

یک اسلاید را در یک ارائه نمایندگی می‌کند.

```csharp
public sealed class Slide : BaseSlide, ISlide
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | پس‌زمینه اسلاید را برمی‌گرداند. فقط-خواندنی [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | مجموعه کنترل‌های ActiveX را در یک اسلاید برمی‌گرداند. فقط-خواندنی [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | داده‌های سفارشی اسلاید را برمی‌گرداند. فقط-خواندنی [`ICustomData`](../icustomdata). |
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | مدیر HeaderFooter اسلاید را برمی‌گرداند. فقط-خواندنی [`ISlideHeaderFooterManager`](../islideheaderfootermanager). |
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | مشخص می‌کند آیا اسلاید مشخص شده در نمایش اسلاید مخفی است یا نه. خواندنی/نوشتنی Boolean. |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | دسترسی آسان به پیوندهای موجود را فراهم می‌کند. فقط-خواندنی [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | اسلاید طرح‌بندی را برای اسلاید فعلی برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`ILayoutSlide`](../ilayoutslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | نام یک اسلاید را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | دسترسی به اسلاید یادداشت‌ها را امکان‌پذیر می‌کند، افزودن و حذف آن. فقط-خواندنی [`INotesSlideManager`](../inotesslidemanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | رابط IPresentation را برمی‌گرداند. فقط-خواندنی [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | اشکال اسلاید را برمی‌گرداند. فقط-خواندنی [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | مشخص می‌کند آیا اشکال بر اسلاید اصلی باید در اسلایدها نمایش داده شوند یا نه. خواندنی/نوشتنی Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | شناسه یک اسلاید را برمی‌گرداند. فقط-خواندنی UInt32. |
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | شماره یک اسلاید را برمی‌گرداند. ایندکس اسلاید در [`Slides`](../presentation/slides) همیشه برابر با SlideNumber - Presentation.FirstSlideNumber است. خواندنی/نوشتنی Int32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | شیء Transition را برمی‌گرداند که اطلاعاتی درباره نحوه پیشرفت اسلاید مشخص شده در هنگام نمایش اسلاید دارد. فقط-خواندنی [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | مدیر تم overriding را برمی‌گرداند. فقط-خواندنی [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | شیء animation timeline را برمی‌گرداند. فقط-خواندنی [`IAnimationTimeLine`](../ianimationtimeline). |

## متدها

| نام | توضیح |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | یک تم مؤثر برای این اسلاید برمی‌گرداند. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | مشخص می‌کند آیا دو نمونهٔ IBaseSlide برابر هستند یا نه. مقدار بازگشتی بر اساس ساختار اسلاید و محتویات ایستا محاسبه می‌شود. دو اسلاید برابر هستند اگر تمام اشکال، سبک‌ها، متن‌ها، انیمیشن و سایر تنظیمات و غیره برابر باشند. مقایسه مقادیر شناسهٔ منحصر به‌فرد مانند SlideId و محتوای پویا مانند مقدار تاریخ جاری در جایگزین تاریخ را در نظر نمی‌گیرد. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | اولین رخداد شکلی با متن جایگزین مشخص‌شده را پیدا می‌کند. |
| [GetImage](../../aspose.slides/slide/getimage#getimage)() | شیء Thumbnail Image را برمی‌گرداند (20٪ از اندازه واقعی). |
| [GetImage](../../aspose.slides/slide/getimage#getimage_1)(IRenderingOptions) | شیء Thumbnail Image را برمی‌گرداند. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_4)(ITiffOptions) | شیء تصویر tiff کوچک (Thumbnail) را با پارامترهای مشخص‌شده برمی‌گرداند. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_6)(Size) | شیء Thumbnail Image را با اندازهٔ مشخص برمی‌گرداند. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_5)(float, float) | شیء Thumbnail Image را با مقیاس‌بندی سفارشی برمی‌گرداند. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_3)(IRenderingOptions, Size) | شیء Thumbnail Image را با اندازهٔ مشخص برمی‌گرداند. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_2)(IRenderingOptions, float, float) | شیء Thumbnail Image را با مقیاس‌بندی سفارشی برمی‌گرداند. |
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | تمام نظرات اسلاید اضافه‌شده توسط نویسندهٔ خاص را برمی‌گرداند. |
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | دنباله‌های متنی با قالب‌بندی یکسان در تمام پاراگراف‌های تمام اشکال قابل پذیرش را ترکیب می‌کند. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | دنباله‌های متنی با قالب‌بندی یکسان در تمام پاراگراف‌های تمام اشکال قابل پذیرش را ترکیب می‌کند. |
| [Remove](../../aspose.slides/slide/remove)() | اسلاید را از ارائه حذف می‌کند. |
| [Reset](../../aspose.slides/slide/reset)() | موقعیت، اندازه و قالب‌بندی هر شکلی که یک نمونهٔ اولیه در LayoutSlide دارد را بازنشانی می‌کند. |
| [WriteAsEmf](../../aspose.slides/slide/writeasemf)(Stream) | محتوای اسلاید را به‌عنوان فایل EMF ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | محتوای اسلاید را به‌عنوان فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | محتوای اسلاید را به‌عنوان فایل SVG ذخیره می‌کند. |

### موارد مرتبط

* کلاس [BaseSlide](../baseslide)
* رابط [ISlide](../islide)
* فضای نام [Aspose.Slides](../../aspose.slides)
* مجتمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->