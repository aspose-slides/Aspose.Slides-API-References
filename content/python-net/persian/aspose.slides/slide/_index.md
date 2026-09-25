---
title: Slide class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/slide/
---
## کلاس Slide

یک اسلاید در یک ارائه را نشان می‌دهد.

**ارث‌بری:**[`Slide`](/slides/python-net/fa/aspose.slides/slide) → [`BaseSlide`](/slides/python-net/fa/aspose.slides/baseslide)

نوع Slide اعضای زیر را در دسترس می‌گذارد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`shapes`](/slides/python-net/fa/aspose.slides/slide/shapes/) | شکل‌های یک اسلاید را بر می‌گرداند.<br/>            فقط خواندنی [`IShapeCollection`](/slides/python-net/fa/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/fa/aspose.slides/slide/controls/) | مجموعه کنترل‌های ActiveX روی یک اسلاید را بر می‌گرداند.<br/>            فقط خواندنی [`IControlCollection`](/slides/python-net/fa/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/fa/aspose.slides/slide/name/) | نام یک اسلاید را بر می‌گرداند یا تنظیم می‌کند.<br/>            خواندن/نوشتن **str**. |
| [`slide_id`](/slides/python-net/fa/aspose.slides/slide/slide_id/) | شناسه یک اسلاید را بر می‌گرداند.<br/>            فقط خواندنی **int**. |
| [`custom_data`](/slides/python-net/fa/aspose.slides/slide/custom_data/) | داده‌های سفارشی اسلاید را بر می‌گرداند.<br/>            فقط خواندنی [`ICustomData`](/slides/python-net/fa/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/fa/aspose.slides/slide/timeline/) | شیء زمان‌بندی انیمیشن را بر می‌گرداند.<br/>            فقط خواندنی [`IAnimationTimeLine`](/slides/python-net/fa/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/fa/aspose.slides/slide/slide_show_transition/) | شیء Transition را بر می‌گرداند که شامل اطلاعات درباره<br/>            چگونگی پیشرفت اسلاید مشخص شده در حین نمایش اسلاید است.<br/>            فقط خواندنی [`ISlideShowTransition`](/slides/python-net/fa/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/fa/aspose.slides/slide/background/) | پس‌زمینه اسلاید را بر می‌گرداند.<br/>            فقط خواندنی [`IBackground`](/slides/python-net/fa/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/fa/aspose.slides/slide/hyperlink_queries/) | دسترسی آسان به پیوندهای داخل‌شده را فراهم می‌کند.<br/>            فقط خواندنی [`IHyperlinkQueries`](/slides/python-net/fa/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/fa/aspose.slides/slide/show_master_shapes/) | مشخص می‌کند آیا شکل‌ها در اسلاید اصلی باید در اسلایدها نشان داده شوند یا نه.<br/>            خواندن/نوشتن **bool**. |
| [`presentation`](/slides/python-net/fa/aspose.slides/slide/presentation/) | رابط IPresentation را بر می‌گرداند.<br/>            فقط خواندنی [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/fa/aspose.slides/slide/header_footer_manager/) | مدیر HeaderFooter اسلاید را بر می‌گرداند.<br/>            فقط خواندنی [`ISlideHeaderFooterManager`](/slides/python-net/fa/aspose.slides/islideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/fa/aspose.slides/slide/theme_manager/) | مدیر تم‌های جایگزین را بر می‌گرداند.<br/>            فقط خواندنی [`IOverrideThemeManager`](/slides/python-net/fa/aspose.slides.theme/ioverridethememanager). |
| [`slide_number`](/slides/python-net/fa/aspose.slides/slide/slide_number/) | شماره یک اسلاید را بر می‌گرداند.<br/>            شاخص اسلاید در مجموعه [`Presentation.slides`](/slides/python-net/fa/aspose.slides/presentation/slides) همیشه برابر است با SlideNumber - Presentation.FirstSlideNumber.<br/>            خواندن/نوشتن **int**. |
| [`hidden`](/slides/python-net/fa/aspose.slides/slide/hidden/) | تعیین می‌کند آیا اسلاید مشخص شده در حین نمایش اسلاید مخفی باشد یا نه.<br/>            خواندن/نوشتن **bool**. |
| [`layout_slide`](/slides/python-net/fa/aspose.slides/slide/layout_slide/) | اسلاید چیدمان را برای اسلاید فعلی بر می‌گرداند یا تنظیم می‌کند.<br/>            خواندن/نوشتن [`ILayoutSlide`](/slides/python-net/fa/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/fa/aspose.slides/slide/notes_slide_manager/) | دسترسی به اسلاید یادداشت‌ها را امکان‌پذیر می‌کند، اضافه و حذف آن.<br/>            فقط خواندنی [`INotesSlideManager`](/slides/python-net/fa/aspose.slides/inotesslidemanager). |
| [`slide`](/slides/python-net/fa/aspose.slides/slide/slide/) |  |

## متدها

| متد | توضیح |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/fa/aspose.slides/slide/join_portions_with_same_formatting/#) | بخش‌های متنی (runs) با قالب‌بندی یکسان را در تمام پاراگراف‌ها در تمام شکل‌های قابل قبول ادغام می‌کند. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/fa/aspose.slides/slide/join_portions_with_same_formatting/#ishapecollection) | بخش‌های متنی (runs) با قالب‌بندی یکسان را در تمام پاراگراف‌ها در تمام شکل‌های قابل قبول ادغام می‌کند. |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/fa/aspose.slides/slide/get_image/#float-float) | یک شیء Thumbnail Image با مقیاس سفارشی بر می‌گرداند. |
| [`get_image(self)`](/slides/python-net/fa/aspose.slides/slide/get_image/#) | یک شیء Thumbnail Image (۲۰٪ اندازه واقعی) بر می‌گرداند. |
| [`get_image(self, image_size)`](/slides/python-net/fa/aspose.slides/slide/get_image/#asposeslidessize) | یک شیء Thumbnail Image با اندازه مشخص بر می‌گرداند. |
| [`get_image(self, options)`](/slides/python-net/fa/aspose.slides/slide/get_image/#asposeslidesexportitiffoptions) | یک شیء تصویر tiff Thumbnail با پارامترهای مشخص بر می‌گرداند. |
| [`get_image(self, options)`](/slides/python-net/fa/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions) | یک شیء Thumbnail Image بر می‌گرداند. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/fa/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-float-float) | یک شیء Thumbnail Image با مقیاس سفارشی بر می‌گرداند. |
| [`get_image(self, options, image_size)`](/slides/python-net/fa/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-asposeslidessize) | یک شیء Thumbnail Image با اندازه مشخص بر می‌گرداند. |
| [`write_as_svg(self, stream)`](/slides/python-net/fa/aspose.slides/slide/write_as_svg/#iorawiobase) | محتوای اسلاید را به‌صورت فایل SVG ذخیره می‌کند. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fa/aspose.slides/slide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | محتوای اسلاید را به‌صورت فایل SVG ذخیره می‌کند. |
| [`equals(self, slide)`](/slides/python-net/fa/aspose.slides/slide/equals/#ibaseslide) | تعیین می‌کند آیا دو نمونه IBaseSlide برابر هستند.<br/>            مقدار برگردانده شده بر اساس ساختار اسلاید و محتویات ثابت محاسبه می‌شود.<br/>            دو اسلاید برابر هستند اگر تمام شکل‌ها، سبک‌ها، متن‌ها، انیمیشن و سایر تنظیمات و غیره برابر باشند. مقایسه مقادیر شناسه‌های منحصر به فرد مانند SlideId و محتویات پویا مانند مقدار تاریخ جاری در جای‌دار تاریخ را در نظر نمی‌گیرد. |
| [`create_theme_effective(self)`](/slides/python-net/fa/aspose.slides/slide/create_theme_effective/#) | یک تم مؤثر برای این اسلاید را بر می‌گرداند. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/fa/aspose.slides/slide/find_shape_by_alt_text/#str) | اولین رخداد یک شکل با متن جایگزین مشخص را پیدا می‌کند. |
| [`write_as_emf(self, stream)`](/slides/python-net/fa/aspose.slides/slide/write_as_emf/#iorawiobase) | محتوای اسلاید را به‌صورت فایل EMF ذخیره می‌کند. |
| [`remove(self)`](/slides/python-net/fa/aspose.slides/slide/remove/#) | اسلاید را از ارائه حذف می‌کند. |
| [`reset(self)`](/slides/python-net/fa/aspose.slides/slide/reset/#) | موقعیت، اندازه و قالب‌بندی هر شکلی که یک نمونه اولیه در LayoutSlide دارد را بازنشانی می‌کند. |
| [`get_slide_comments(self, author)`](/slides/python-net/fa/aspose.slides/slide/get_slide_comments/#icommentauthor) | تمام نظرات اسلاید اضافه شده توسط نویسنده خاص را بر می‌گرداند. |

### موارد مرتبط
* کلاس [`BaseSlide`](/slides/python-net/fa/aspose.slides/baseslide)
* کلاس [`Slide`](/slides/python-net/fa/aspose.slides/slide)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)