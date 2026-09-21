---
title: Slide class
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/slide/
---
## Slide class

یک اسلاید در ارائه را نمایندگی می‌کند.

**Inheritance:**[`Slide`](/slides/python-net/fa/aspose.slides/slide) → [`BaseSlide`](/slides/python-net/fa/aspose.slides/baseslide)

نوع Slide اعضای زیر را در دسترس قرار می‌دهد:

## Properties

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/fa/aspose.slides/slide/shapes/) | اشکال یک اسلاید را برمی‌گرداند.<br/>            فقط-خواندنی [`IShapeCollection`](/slides/python-net/fa/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/fa/aspose.slides/slide/controls/) | مجموعه کنترل‌های ActiveX روی یک اسلاید را برمی‌گرداند.<br/>            فقط-خواندنی [`IControlCollection`](/slides/python-net/fa/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/fa/aspose.slides/slide/name/) | نام یک اسلاید را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن/قابل‌نوشتن **str**. |
| [`slide_id`](/slides/python-net/fa/aspose.slides/slide/slide_id/) | شناسه یک اسلاید را برمی‌گرداند.<br/>            فقط-خواندنی **int**. |
| [`custom_data`](/slides/python-net/fa/aspose.slides/slide/custom_data/) | داده‌های سفارشی اسلاید را برمی‌گرداند.<br/>            فقط-خواندنی [`ICustomData`](/slides/python-net/fa/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/fa/aspose.slides/slide/timeline/) | شیء زمانبندی انیمیشن را برمی‌گرداند.<br/>            فقط-خواندنی [`IAnimationTimeLine`](/slides/python-net/fa/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/fa/aspose.slides/slide/slide_show_transition/) | شیء Transition را که شامل اطلاعاتی درباره<br/>            نحوه پیشرفت اسلاید مشخص در حین نمایش اسلاید است، برمی‌گرداند.<br/>            فقط-خواندنی [`ISlideShowTransition`](/slides/python-net/fa/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/fa/aspose.slides/slide/background/) | پس‌زمینه اسلاید را برمی‌گرداند.<br/>            فقط-خواندنی [`IBackground`](/slides/python-net/fa/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/fa/aspose.slides/slide/hyperlink_queries/) | دسترسی آسان به پیوندهای موجود را فراهم می‌کند.<br/>            فقط-خواندنی [`IHyperlinkQueries`](/slides/python-net/fa/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/fa/aspose.slides/slide/show_master_shapes/) | مشخص می‌کند آیا اشکال روی اسلاید اصلی باید روی اسلایدها نشان داده شوند یا نه.<br/>            قابل‌خواندن/قابل‌نوشتن **bool**. |
| [`presentation`](/slides/python-net/fa/aspose.slides/slide/presentation/) | رابط IPresentation را برمی‌گرداند.<br/>            فقط-خواندنی [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/fa/aspose.slides/slide/header_footer_manager/) | مدیر HeaderFooter اسلاید را برمی‌گرداند.<br/>            فقط-خواندنی [`ISlideHeaderFooterManager`](/slides/python-net/fa/aspose.slides/islideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/fa/aspose.slides/slide/theme_manager/) | مدیر تم‌نقض‌کننده را برمی‌گرداند.<br/>            فقط-خواندنی [`IOverrideThemeManager`](/slides/python-net/fa/aspose.slides.theme/ioverridethememanager). |
| [`slide_number`](/slides/python-net/fa/aspose.slides/slide/slide_number/) | شماره اسلاید را برمی‌گرداند.<br/>            اندیس اسلاید در مجموعه [`Presentation.slides`](/slides/python-net/fa/aspose.slides/presentation/slides) همواره برابر با SlideNumber - Presentation.FirstSlideNumber است.<br/>            قابل‌خواندن/قابل‌نوشتن **int**. |
| [`hidden`](/slides/python-net/fa/aspose.slides/slide/hidden/) | مشخص می‌کند آیا اسلاید مشخص در حین نمایش اسلاید مخفی باشد یا نه.<br/>            قابل‌خواندن/قابل‌نوشتن **bool**. |
| [`layout_slide`](/slides/python-net/fa/aspose.slides/slide/layout_slide/) | اسلاید طرح‌بندی برای اسلاید فعلی را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن/قابل‌نوشتن [`ILayoutSlide`](/slides/python-net/fa/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/fa/aspose.slides/slide/notes_slide_manager/) | دسترسی به اسلاید یادداشت‌ها را امکان‌پذیر می‌کند، افزودن و حذف آن.<br/>            فقط-خواندنی [`INotesSlideManager`](/slides/python-net/fa/aspose.slides/inotesslidemanager). |
| [`slide`](/slides/python-net/fa/aspose.slides/slide/slide/) |  |

## Methods

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/fa/aspose.slides/slide/join_portions_with_same_formatting/#) | بخش‌ها را با قالب‌بندی یکسان در تمام پاراگراف‌ها در تمام اشکال قابل قبول ترکیب می‌کند. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/fa/aspose.slides/slide/join_portions_with_same_formatting/#ishapecollection) | بخش‌ها را با قالب‌بندی یکسان در تمام پاراگراف‌ها در تمام اشکال قابل قبول ترکیب می‌کند. |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/fa/aspose.slides/slide/get_image/#float-float) | یک شیء Thumbnail Image را با مقیاس‌گذاری دلخواه برمی‌گرداند. |
| [`get_image(self)`](/slides/python-net/fa/aspose.slides/slide/get_image/#) | یک شیء Thumbnail Image را برمی‌گرداند (۲۰٪ از اندازه واقعی). |
| [`get_image(self, image_size)`](/slides/python-net/fa/aspose.slides/slide/get_image/#asposepydrawingsize) | یک شیء Thumbnail Image را با اندازه‌ مشخص برمی‌گرداند. |
| [`get_image(self, options)`](/slides/python-net/fa/aspose.slides/slide/get_image/#asposeslidesexportitiffoptions) | یک شیء Thumbnail tiff image را با پارامترهای مشخص برمی‌گرداند. |
| [`get_image(self, options)`](/slides/python-net/fa/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions) | یک شیء Thumbnail Image را برمی‌گرداند. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/fa/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-float-float) | یک شیء Thumbnail Image را با مقیاس‌گذاری دلخواه برمی‌گرداند. |
| [`get_image(self, options, image_size)`](/slides/python-net/fa/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-asposepydrawingsize) | یک شیء Thumbnail Image را با اندازه‌ مشخص برمی‌گرداند. |
| [`write_as_svg(self, stream)`](/slides/python-net/fa/aspose.slides/slide/write_as_svg/#iorawiobase) | محتوای اسلاید را به‌صورت فایل SVG ذخیره می‌کند. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fa/aspose.slides/slide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | محتوای اسلاید را به‌صورت فایل SVG ذخیره می‌کند. |
| [`equals(self, slide)`](/slides/python-net/fa/aspose.slides/slide/equals/#ibaseslide) | مشخص می‌کند آیا دو نمونه IBaseSlide برابر هستند یا نه.<br/>            مقدار بازگردانده‌شده براساس ساختار اسلاید و محتوای ثابت محاسبه می‌شود.<br/>            دو اسلاید برابر هستند اگر تمام اشکال، سبک‌ها، متن‌ها، انیمیشن و سایر تنظیمات و غیره برابر باشند. مقایسه مقادیر شناسهٔ یکتا مانند SlideId و محتوای پویا مانند مقدار تاریخ فعلی در جای‌گذاری تاریخ را در نظر نمی‌گیرد. |
| [`create_theme_effective(self)`](/slides/python-net/fa/aspose.slides/slide/create_theme_effective/#) | یک تم مؤثر برای این اسلاید را برمی‌گرداند. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/fa/aspose.slides/slide/find_shape_by_alt_text/#str) | اولین رخداد یک شکل با متن جایگزین مشخص را پیدا می‌کند. |
| [`write_as_emf(self, stream)`](/slides/python-net/fa/aspose.slides/slide/write_as_emf/#iorawiobase) | محتوای اسلاید را به‌صورت فایل EMF ذخیره می‌کند. |
| [`remove(self)`](/slides/python-net/fa/aspose.slides/slide/remove/#) | اسلاید را از ارائه حذف می‌کند. |
| [`reset(self)`](/slides/python-net/fa/aspose.slides/slide/reset/#) | موقعیت، اندازه و قالب‌بندی هر شکلی که یک نمونه در LayoutSlide دارد را بازنشانی می‌کند. |
| [`get_slide_comments(self, author)`](/slides/python-net/fa/aspose.slides/slide/get_slide_comments/#icommentauthor) | تمام نظرات اسلاید اضافه‌شده توسط نویسندهٔ خاص را برمی‌گرداند. |

### موارد مرتبط
* کلاس [`BaseSlide`](/slides/python-net/fa/aspose.slides/baseslide)
* کلاس [`Slide`](/slides/python-net/fa/aspose.slides/slide)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)