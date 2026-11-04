---
title: Slide
second_title: Aspose.Sildes برای .NET مرجع API
description: نمایانگر یک اسلاید در یک ارائه است.
type: docs
weight: 9980
url: /fa/aspose.slides/slide/
---
## کلاس Slide

نمایانگر یک اسلاید در یک ارائه است.

```csharp
public sealed class Slide : BaseSlide, ISlide
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | پس‌زمینه اسلاید را برمی‌گرداند. فقط خواندنی [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | کلکسیون کنترل‌های ActiveX روی یک اسلاید را برمی‌گرداند. فقط خواندنی [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | داده‌های سفارشی اسلاید را برمی‌گرداند. فقط خواندنی [`ICustomData`](../icustomdata). |
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | مدیر HeaderFooter اسلاید را برمی‌گرداند. فقط خواندنی [`ISlideHeaderFooterManager`](../islideheaderfootermanager). |
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | مشخص می‌کند آیا اسلاید تعیین‌شده در حین نمایش اسلاید مخفی باشد یا نه. خواندنی/نوشتنی Boolean. |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | دسترسی آسان به پیوندهای موجود را فراهم می‌کند. فقط خواندنی [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | اسلاید چیدمان را برای اسلاید جاری برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`ILayoutSlide`](../ilayoutslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | نام یک اسلاید را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | دسترسی به اسلاید یادداشت‌ها را فراهم می‌کند، امکان افزودن و حذف آن را می‌دهد. فقط خواندنی [`INotesSlideManager`](../inotesslidemanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | اینترفیس IPresentation را برمی‌گرداند. فقط خواندنی [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | شکل‌های یک اسلاید را برمی‌گرداند. فقط خواندنی [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | مشخص می‌کند آیا شکل‌های اسلاید مستر باید در اسلایدها نشان داده شوند یا نه. خواندنی/نوشتنی Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | شناسه یک اسلاید را برمی‌گرداند. فقط خواندنی UInt32. |
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | شماره‌ای از اسلاید را برمی‌گرداند. اندیس اسلاید در مجموعه [`Slides`](../presentation/slides) همیشه برابر است با SlideNumber - Presentation.FirstSlideNumber. خواندنی/نوشتنی Int32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | شیء Transition را برمی‌گرداند که شامل اطلاعات درباره نحوه پیشروی اسلاید تعیین‌شده در حین نمایش اسلاید است. فقط خواندنی [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | مدیر تم بازنویسی شده را برمی‌گرداند. فقط خواندنی [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | شیء animation timeline را برمی‌گرداند. فقط خواندنی [`IAnimationTimeLine`](../ianimationtimeline). |

## متدها

| نام | توضیح |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | یک تم مؤثر برای این اسلاید برمی‌گرداند. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | مشخص می‌کند آیا دو نمونه IBaseSlide برابر هستند یا نه. مقدار بازگشتی بر اساس ساختار اسلاید و محتوای ثابت محاسبه می‌شود. دو اسلاید برابرند اگر تمام شکل‌ها، سبک‌ها، متن‌ها، انیمیشن‌ها و سایر تنظیمات و غیره برابر باشند. مقایسه مقادیر شناسه منحصربه‌فرد مانند SlideId و محتوای پویا مانند مقدار تاریخ فعلی در جای‌نگهدار تاریخ را در نظر نمی‌گیرد. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | اولین رخداد شکلی با متن جایگزین مشخص‌شده را پیدا می‌کند. |
| [GetImage](../../aspose.slides/slide/getimage#getimage)() | یک شیء Thumbnail Image (۲۰٪ از اندازه واقعی) را برمی‌گرداند. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_1)(IRenderingOptions) | یک شیء Thumbnail Image را برمی‌گرداند. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_4)(ITiffOptions) | یک شیء تصویر tiff بندانگشتی را با پارامترهای مشخص برمی‌گرداند. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_6)(Size) | یک شیء Thumbnail Image با اندازه مشخص را برمی‌گرداند. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_5)(float, float) | یک شیء Thumbnail Image با مقیاس سفارشی را برمی‌گرداند. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_3)(IRenderingOptions, Size) | یک شیء Thumbnail Image با اندازه مشخص را برمی‌گرداند. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_2)(IRenderingOptions, float, float) | یک شیء Thumbnail Image با مقیاس سفارشی را برمی‌گرداند. |
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | تمام نظرات اسلاید اضافه‌شده توسط نویسنده خاص را برمی‌گرداند. |
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | دنباله‌های متن با قالب‌بندی یکسان را در تمام پاراگراف‌ها در تمام اشکال قابل قبول ترکیب می‌کند. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | دنباله‌های متن با قالب‌بندی یکسان را در تمام پاراگراف‌ها در تمام اشکال قابل قبول ترکیب می‌کند. |
| [Remove](../../aspose.slides/slide/remove)() | اسلاید را از ارائه حذف می‌کند. |
| [Reset](../../aspose.slides/slide/reset)() | موقعیت، اندازه و قالب‌بندی هر شکلی که یک نمونه اولیه در LayoutSlide دارد را بازنشانی می‌کند. |
| [WriteAsEmf](../../aspose.slides/slide/writeasemf)(Stream) | محتوای اسلاید را به‌عنوان یک فایل EMF ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | محتوای اسلاید را به‌عنوان یک فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | محتوای اسلاید را به‌عنوان یک فایل SVG ذخیره می‌کند. |

### مراجع

* کلاس [BaseSlide](../baseslide)
* رابط [ISlide](../islide)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مجوعه [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->