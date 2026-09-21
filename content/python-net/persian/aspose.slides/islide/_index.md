---
title: ISlide class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/islide/
---
## ISlide کلاس

یک اسلاید در یک ارائه را نمایندگی می‌کند.

نوع ISlide اعضای زیر را نمایش می‌دهد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/fa/aspose.slides/islide/header_footer_manager/) | مدیر HeaderFooter اسلاید را برمی‌گرداند.<br/>            فقط‌خواندنی [`ISlideHeaderFooterManager`](/slides/python-net/fa/aspose.slides/islideheaderfootermanager). |
| [`slide_number`](/slides/python-net/fa/aspose.slides/islide/slide_number/) | عدد اسلاید را برمی‌گرداند.<br/>            اندیس اسلاید در مجموعه [`IPresentation.slides`](/slides/python-net/fa/aspose.slides/ipresentation/slides) همیشه برابر با SlideNumber - 1 است.<br/>            قابل خواندن و نوشتن **int**. |
| [`hidden`](/slides/python-net/fa/aspose.slides/islide/hidden/) | مشخص می‌کند آیا اسلاید مشخص شده در نمایش اسلاید پنهان است یا خیر.<br/>            قابل خواندن و نوشتن **bool**. |
| [`layout_slide`](/slides/python-net/fa/aspose.slides/islide/layout_slide/) | طرح اسلاید برای اسلاید جاری را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن و نوشتن [`ILayoutSlide`](/slides/python-net/fa/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/fa/aspose.slides/islide/notes_slide_manager/) | دسترسی به اسلاید یادداشت‌ها را امکان‌پذیر می‌کند، افزودن و حذف آن.<br/>            فقط‌خواندنی [`INotesSlideManager`](/slides/python-net/fa/aspose.slides/inotesslidemanager). |
| [`shapes`](/slides/python-net/fa/aspose.slides/islide/shapes/) |  |
| [`controls`](/slides/python-net/fa/aspose.slides/islide/controls/) |  |
| [`name`](/slides/python-net/fa/aspose.slides/islide/name/) |  |
| [`slide_id`](/slides/python-net/fa/aspose.slides/islide/slide_id/) |  |
| [`custom_data`](/slides/python-net/fa/aspose.slides/islide/custom_data/) |  |
| [`timeline`](/slides/python-net/fa/aspose.slides/islide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/fa/aspose.slides/islide/slide_show_transition/) |  |
| [`background`](/slides/python-net/fa/aspose.slides/islide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/fa/aspose.slides/islide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/fa/aspose.slides/islide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/fa/aspose.slides/islide/slide/) |  |
| [`presentation`](/slides/python-net/fa/aspose.slides/islide/presentation/) |  |
| [`theme_manager`](/slides/python-net/fa/aspose.slides/islide/theme_manager/) |  |

## متدها

| متد | توضیح |
| :- | :- |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/fa/aspose.slides/islide/get_image/#float-float) | یک شیء تصویر با مقیاس‌گذاری سفارشی برمی‌گرداند. |
| [`get_image(self)`](/slides/python-net/fa/aspose.slides/islide/get_image/#) | یک شیء تصویر بندانگشتی (۲۰٪ از اندازه واقعی) برمی‌گرداند. |
| [`get_image(self, image_size)`](/slides/python-net/fa/aspose.slides/islide/get_image/#asposepydrawingsize) | یک شیء تصویر با اندازه مشخص برمی‌گرداند. |
| [`get_image(self, options)`](/slides/python-net/fa/aspose.slides/islide/get_image/#asposeslidesexportitiffoptions) | یک شیء بیت‌مپ tiff بندانگشتی با پارامترهای مشخص برمی‌گرداند. |
| [`get_image(self, options)`](/slides/python-net/fa/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions) | یک شیء Bitmap بندانگشتی برمی‌گرداند. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/fa/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-float-float) | یک شیء Bitmap بندانگشتی با مقیاس‌گذاری سفارشی برمی‌گرداند. |
| [`get_image(self, options, image_size)`](/slides/python-net/fa/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-asposepydrawingsize) | یک شیء Bitmap بندانگشتی با اندازه مشخص برمی‌گرداند. |
| [`write_as_svg(self, stream)`](/slides/python-net/fa/aspose.slides/islide/write_as_svg/#iorawiobase) | محتویات اسلاید را به عنوان فایل SVG ذخیره می‌کند. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fa/aspose.slides/islide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | محتویات اسلاید را به عنوان فایل SVG ذخیره می‌کند. |
| [`get_slide_comments(self, author)`](/slides/python-net/fa/aspose.slides/islide/get_slide_comments/#icommentauthor) | تمام نظرات اسلاید اضافه شده توسط نویسنده خاص را برمی‌گرداند. |
| [`write_as_emf(self, stream)`](/slides/python-net/fa/aspose.slides/islide/write_as_emf/#iorawiobase) | محتویات اسلاید را به عنوان فایل EMF ذخیره می‌کند. |
| [`remove(self)`](/slides/python-net/fa/aspose.slides/islide/remove/#) | اسلاید را از ارائه حذف می‌کند. |
| [`reset(self)`](/slides/python-net/fa/aspose.slides/islide/reset/#) | موقعیت، اندازه و قالب‌بندی هر شکلی که یک نمونه روی LayoutSlide دارد را بازنشانی می‌کند. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/fa/aspose.slides/islide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/fa/aspose.slides/islide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/fa/aspose.slides/islide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/fa/aspose.slides/islide/create_theme_effective/#) |  |


### همچنین ببینید
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)