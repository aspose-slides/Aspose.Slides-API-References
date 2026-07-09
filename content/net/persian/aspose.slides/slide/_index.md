---
title: Slide
second_title: Aspose.Sildes برای .NET مرجع API
description: یک اسلاید را در یک ارائه نشان می‌دهد.
type: docs
weight: 9960
url: /fa/aspose.slides/slide/
---
## کلاس Slide

یک اسلاید را در یک ارائه نشان می‌دهد.

```csharp
public sealed class Slide : BaseSlide, ISlide
```

## خصوصیات

| نام | توضیح |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | پس‌زمینه اسلاید را برمی‌گرداند. فقط-خواندنی [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | مجموعه‌ی کنترل‌های ActiveX روی اسلاید را برمی‌گرداند. فقط-خواندنی [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | داده‌های سفارشی اسلاید را برمی‌گرداند. فقط-خواندنی [`ICustomData`](../icustomdata). |
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | مدیر HeaderFooter اسلاید را برمی‌گرداند. فقط-خواندنی [`ISlideHeaderFooterManager`](../islideheaderfootermanager). |
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | تعیین می‌کند که اسلاید مشخص شده هنگام نمایش اسلاید پنهان باشد یا نه. خواندن/نوشتن Boolean. |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | دسترسی آسان به پیوندهای مرجع موجود را فراهم می‌کند. فقط-خواندنی [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | طرح‌بندی اسلاید فعلی را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [`ILayoutSlide`](../ilayoutslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | نام اسلاید را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن String. |
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | دسترسی به اسلاید یادداشت‌ها، افزودن و حذف آن را فراهم می‌کند. فقط-خواندنی [`INotesSlideManager`](../inotesslidemanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | رابط IPresentation را برمی‌گرداند. فقط-خواندنی [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | اشکال اسلاید را برمی‌گرداند. فقط-خواندنی [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | مشخص می‌کند که آیا اشکال روی اسلاید اصلی باید در اسلایدها نمایش داده شوند یا نه. خواندن/نوشتن Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | شناسه اسلاید را برمی‌گرداند. فقط-خواندنی UInt32. |
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | شماره اسلاید را برمی‌گرداند. ایندکس اسلاید در مجموعه [`Slides`](../presentation/slides) همواره برابر با SlideNumber - Presentation.FirstSlideNumber است. خواندن/نوشتن Int32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | شی Transition که شامل اطلاعاتی دربارهٔ پیشرفت اسلاید در حین نمایش اسلاید است را برمی‌گرداند. فقط-خواندنی [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | مدیر تم overriding را برمی‌گرداند. فقط-خواندنی [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | شی animation timeline را برمی‌گرداند. فقط-خواندنی [`IAnimationTimeLine`](../ianimationtimeline). |

## متدها

| نام | توضیح |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | یک تم مؤثر برای این اسلاید برمی‌گرداند. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | تعیین می‌کند که آیا دو نمونهٔ IBaseSlide برابر هستند یا نه. مقدار برگشتی بر اساس ساختار اسلاید و محتوای ثابت محاسبه می‌شود. دو اسلاید برابر هستند اگر تمام اشکال، سبک‌ها، متن‌ها, animation و سایر تنظیمات و موارد مشابه برابر باشند. مقایسه شناسه‌های منحصر به فرد مانند SlideId و محتوای پویا مانند مقدار تاریخ جاری در Date Placeholder را در نظر نمی‌گیرد. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | اولین رخداد شکلی با متن جایگزین مشخص شده را پیدا می‌کند. |
| [GetImage](../../aspose.slides/slide/getimage#getimage)() | شی Thumbnail Image (20٪ اندازه‌ی واقعی) را برمی‌گرداند. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_1)(IRenderingOptions) | شی Thumbnail Image را برمی‌گرداند. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_4)(ITiffOptions) | شی تصویر TIFF جزئیات‌دار با پارامترهای مشخص شده را برمی‌گرداند. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_6)(Size) | شی Thumbnail Image با اندازه‌ی مشخص شده را برمی‌گرداند. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_5)(float, float) | شی Thumbnail Image با مقیاس‌گذاری سفارشی را برمی‌گرداند. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_3)(IRenderingOptions, Size) | شی Thumbnail Image با اندازه‌ی مشخص شده را برمی‌گرداند. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_2)(IRenderingOptions, float, float) | شی Thumbnail Image با مقیاس‌گذاری سفارشی را برمی‌گرداند. |
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | تمام نظرات اسلاید اضافه شده توسط نویسنده خاص را برمی‌گرداند. |
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | اجرای ترکیب‌بندی قسمت‌های متن با قالب‌بندی یکسان در تمام پاراگراف‌های تمام اشکال قابل قبول. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | اجرای ترکیب‌بندی قسمت‌های متن با قالب‌بندی یکسان در تمام پاراگراف‌های تمام اشکال قابل قبول. |
| [Remove](../../aspose.slides/slide/remove)() | اسلاید را از ارائه حذف می‌کند. |
| [Reset](../../aspose.slides/slide/reset)() | موقعیت، اندازه و قالب‌بندی هر شکلی که نمونه‌ای در LayoutSlide دارد را بازنشانی می‌کند. |
| [WriteAsEmf](../../aspose.slides/slide/writeasemf)(Stream) | محتوای اسلاید را به عنوان فایل EMF ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | محتوای اسلاید را به عنوان فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | محتوای اسلاید را به عنوان فایل SVG ذخیره می‌کند. |

### موارد مرتبط

* کلاس [BaseSlide](../baseslide)
* رابط [ISlide](../islide)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مجتمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->