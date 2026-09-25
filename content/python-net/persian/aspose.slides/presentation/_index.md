---
title: Presentation class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/presentation/
---
## کلاس Presentation

یک ارائهٔ Microsoft PowerPoint را نمایندگی می‌کند.

نوع Presentation اعضای زیر را در اختیار می‌گذارد:

## سازنده‌ها

| سازنده | شرح |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fa/aspose.slides/presentation/__init__/#) | این سازنده یک ارائهٔ جدید را از ابتدا ایجاد می‌کند.<br/>            ارائهٔ ایجاد شده یک اسلاید خالی دارد. |
| [`__init__(self, load_options)`](/slides/python-net/fa/aspose.slides/presentation/__init__/#loadoptions) | این سازنده یک ارائهٔ جدید را از ابتدا ایجاد می‌کند.<br/>            ارائهٔ ایجاد شده یک اسلاید خالی دارد. |
| [`__init__(self, stream)`](/slides/python-net/fa/aspose.slides/presentation/__init__/#iorawiobase) | این سازنده مکانیزم اصلی برای خواندن یک Presentation موجود است. |
| [`__init__(self, stream, load_options)`](/slides/python-net/fa/aspose.slides/presentation/__init__/#iorawiobase-loadoptions) | این سازنده مکانیزم اصلی برای خواندن یک Presentation موجود است. |
| [`__init__(self, file)`](/slides/python-net/fa/aspose.slides/presentation/__init__/#str) | این سازنده مسیر فایل منبعی را دریافت می‌کند که<br/>             محتوای Presentation از آن خوانده می‌شود. |
| [`__init__(self, file, load_options)`](/slides/python-net/fa/aspose.slides/presentation/__init__/#str-loadoptions) | این سازنده مسیر فایل منبعی را دریافت می‌کند که<br/>            محتوای Presentation از آن خوانده می‌شود. |

## ویژگی‌ها

| ویژگی | شرح |
| :- | :- |
| [`current_date_time`](/slides/python-net/fa/aspose.slides/presentation/current_date_time/) | مقدار تاریخ و زمان را برمی‌گرداند یا تنظیم می‌کند که محتویات فیلدهای datetime را جایگزین می‌کند.<br/>            زمان ایجاد این شیء Presentation به صورت پیش‌فرض.<br/>            خواندنی/نوشتنی **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/fa/aspose.slides/presentation/header_footer_manager/) | مدیر HeaderFooter واقعی را برمی‌گرداند.<br/>            فقط-خواندنی [`IPresentationHeaderFooterManager`](/slides/python-net/fa/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/fa/aspose.slides/presentation/protection_manager/) | مدیر مجوزهای این ارائه را دریافت می‌کند.<br/>            فقط-خواندنی [`IProtectionManager`](/slides/python-net/fa/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/fa/aspose.slides/presentation/slides/) | فهرستی از تمام اسلایدهای تعریف‌شده در ارائه را برمی‌گرداند.<br/fa/>            فقط-خواندنی [`ISlideCollection`](/slides/python-net/fa/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/fa/aspose.slides/presentation/sections/) | فهرستی از تمام بخش‌های اسلایدهای تعریف‌شده در ارائه را برمی‌گرداند.<br/>            فقط-خواندنی [`ISectionCollection`](/slides/python-net/fa/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/fa/aspose.slides/presentation/slide_size/) | شیء اندازهٔ اسلاید را برمی‌گرداند.<br/>            فقط-خواندنی [`ISlideSize`](/slides/python-net/fa/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/fa/aspose.slides/presentation/notes_size/) | شیء اندازهٔ اسلاید یادداشت‌ها را برمی‌گرداند.<br/>            فقط-خواندنی [`INotesSize`](/slides/python-net/fa/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/fa/aspose.slides/presentation/layout_slides/) | فهرستی از تمام اسلایدهای layout که در ارائه تعریف شده‌اند را برمی‌گرداند.<br/>            فقط-خواندنی [`IGlobalLayoutSlideCollection`](/slides/python-net/fa/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/fa/aspose.slides/presentation/masters/) | فهرستی از تمام اسلایدهای master که در ارائه تعریف شده‌اند را برمی‌گرداند.<br/>            فقط-خواندنی [`IMasterSlideCollection`](/slides/python-net/fa/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/fa/aspose.slides/presentation/master_notes_slide_manager/) | مدیر notes master را برمی‌گرداند.<br/>            فقط-خواندنی [`IMasterNotesSlideManager`](/slides/python-net/fa/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/fa/aspose.slides/presentation/master_handout_slide_manager/) | مدیر handout master را برمی‌گرداند.<br/>            فقط-خواندنی [`IMasterHandoutSlideManager`](/slides/python-net/fa/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/fa/aspose.slides/presentation/fonts_manager/) | مدیر قلم‌ها (fonts) را برمی‌گرداند.<br/>            فقط-خواندنی [`IFontsManager`](/slides/python-net/fa/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/fa/aspose.slides/presentation/default_text_style/) | سبک متن پیش‌فرض برای اشکال را برمی‌گرداند.<br/>            فقط-خواندنی [`ITextStyle`](/slides/python-net/fa/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/fa/aspose.slides/presentation/comment_authors/) | مجموعهٔ نویسندگان نظرات را برمی‌گرداند.<br/>            فقط-خواندنی [`ICommentAuthorCollection`](/slides/python-net/fa/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/fa/aspose.slides/presentation/document_properties/) | شیء DocumentProperties را برمی‌گرداند که شامل ویژگی‌های استاندارد و سفارشی سند است.<br/>            فقط-خواندنی [`IDocumentProperties`](/slides/python-net/fa/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/fa/aspose.slides/presentation/images/) | مجموعهٔ تمام تصاویر موجود در ارائه را برمی‌گرداند.<br/>            فقط-خواندنی [`IImageCollection`](/slides/python-net/fa/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/fa/aspose.slides/presentation/audios/) | مجموعهٔ تمام فایل‌های صوتی جاسازی‌شده در ارائه را برمی‌گرداند.<br/>            فقط-خواندنی [`IAudioCollection`](/slides/python-net/fa/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/fa/aspose.slides/presentation/videos/) | مجموعهٔ تمام فایل‌های ویدئویی جاسازی‌شده در ارائه را برمی‌گرداند.<br/>            فقط-خواندنی [`IVideoCollection`](/slides/python-net/fa/aspose.slides/ivideocollection). |
| [`slide_show_settings`](/slides/python-net/fa/aspose.slides/presentation/slide_show_settings/) | تنظیمات نمایش اسلاید برای ارائه را برمی‌گرداند. |
| [`digital_signatures`](/slides/python-net/fa/aspose.slides/presentation/digital_signatures/) | مجموعهٔ امضاهای استفاده‌شده برای امضای ارائه را برمی‌گرداند.<br/>            فقط-خواندنی [`IDigitalSignatureCollection`](/slides/python-net/fa/aspose.slides/idigitalsignaturecollection). |
| [`custom_data`](/slides/python-net/fa/aspose.slides/presentation/custom_data/) | داده‌های سفارشی ارائه را برمی‌گرداند.<br/>            فقط-خواندنی [`ICustomData`](/slides/python-net/fa/aspose.slides/icustomdata). |
| [`all_custom_xml_parts`](/slides/python-net/fa/aspose.slides/presentation/all_custom_xml_parts/) | تمام بخش‌های دادهٔ سفارشی در ارائه را برمی‌گرداند.<br/>            فقط-خواندنی [`ICustomXmlPart`](/slides/python-net/fa/aspose.slides/icustomxmlpart)[]. |
| [`vba_project`](/slides/python-net/fa/aspose.slides/presentation/vba_project/) | پروژه VBA را که شامل ماکروهای ارائه است دریافت یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی [`IVbaProject`](/slides/python-net/fa/aspose.slides.vba/ivbaproject). |
| [`hyperlink_queries`](/slides/python-net/fa/aspose.slides/presentation/hyperlink_queries/) | دسترسی آسان به تمام پیوندهای موجود در تمام اسلایدهای ارائه فراهم می‌کند (نه در اسلایدهای master، layout، notes).<br/>            فقط-خواندنی [`IHyperlinkQueries`](/slides/python-net/fa/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/fa/aspose.slides/presentation/view_properties/) | ویژگی‌های نمای کلی ارائه را دریافت می‌کند.<br/>            فقط-خواندنی [`IViewProperties`](/slides/python-net/fa/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/fa/aspose.slides/presentation/first_slide_number/) | شمارهٔ اولین اسلاید در ارائه را نشان می‌دهد |
| [`sensitivity_labels`](/slides/python-net/fa/aspose.slides/presentation/sensitivity_labels/) | مجموعهٔ برچسب‌های حساسیتی که به سند ارائه اعمال شده‌اند را برمی‌گرداند.<br/>            فقط-خواندنی [`ISensitivityLabelCollection`](/slides/python-net/fa/aspose.slides/isensitivitylabelcollection). |
| [`source_format`](/slides/python-net/fa/aspose.slides/presentation/source_format/) | اطلاعاتی دربارهٔ فرمتی که ارائه از آن بارگذاری شده است را برمی‌گرداند.<br/>            فقط-خواندنی [`SourceFormat`](/slides/python-net/fa/aspose.slides/sourceformat). |
| [`master_theme`](/slides/python-net/fa/aspose.slides/presentation/master_theme/) | تم master را برمی‌گرداند.<br/>            فقط-خواندنی [`IMasterTheme`](/slides/python-net/fa/aspose.slides.theme/imastertheme). |
| [`presentation`](/slides/python-net/fa/aspose.slides/presentation/presentation/) |  |

## متدها

| متد | شرح |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/fa/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat) | تمام اسلایدهای یک ارائه را در قالب مشخص به یک فایل ذخیره می‌کند. |
| [`save(self, stream, format)`](/slides/python-net/fa/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat) | تمام اسلایدهای یک ارائه را در قالب مشخص به یک جریان ذخیره می‌کند. |
| [`save(self, fname, format, options)`](/slides/python-net/fa/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) |  |
| [`save(self, stream, format, options)`](/slides/python-net/fa/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | تمام اسلایدهای یک ارائه را در قالب مشخص به یک جریان ذخیره می‌کند و گزینه‌های اضافی را اعمال می‌نماید. |
| [`save(self, options)`](/slides/python-net/fa/aspose.slides/presentation/save/#asposeslidesexportxamlixamloptions) | تمام اسلایدهای یک ارائه را به مجموعه‌ای از فایل‌ها که نمایانگر XAML markup هستند، ذخیره می‌کند. |
| [`save(self, fname, slides, format)`](/slides/python-net/fa/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat) | اسلایدهای مشخص‌شدهٔ یک ارائه را در قالب مشخص به یک فایل ذخیره می‌کند در حالی که شماره صفحه حفظ می‌شود. |
| [`save(self, fname, slides, format, options)`](/slides/python-net/fa/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | اسلایدهای مشخص‌شدهٔ یک ارائه را در قالب مشخص به یک فایل ذخیره می‌کند در حالی که شماره صفحه حفظ می‌شود. |
| [`save(self, stream, slides, format)`](/slides/python-net/fa/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | اسلایدهای مشخص‌شدهٔ یک ارائه را در قالب مشخص به یک جریان ذخیره می‌کند در حالی که شماره صفحه حفظ می‌شود. |
| [`save(self, stream, slides, format, options)`](/slides/python-net/fa/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | اسلایدهای مشخص‌شدهٔ یک ارائه را در قالب مشخص به یک جریان ذخیره می‌کند در حالی که شماره صفحه حفظ می‌شود. |
| [`get_images(self, options)`](/slides/python-net/fa/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions) | شیء Image را برای تمام اسلایدهای یک ارائه برمی‌گرداند. |
| [`get_images(self, options, slides)`](/slides/python-net/fa/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint) | شیء Thumbnail Image را برای اسلایدهای مشخص‌شدهٔ یک ارائه برمی‌گرداند. |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/fa/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-float-float) | شیء Thumbnail Image را برای تمام اسلایدهای یک ارائه با مقیاس‌گذاری سفارشی برمی‌گرداند. |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/fa/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | شیء Thumbnail Image را برای اسلایدهای مشخص‌شدهٔ یک ارائه با مقیاس‌گذاری سفارشی برمی‌گرداند. |
| [`get_images(self, options, image_size)`](/slides/python-net/fa/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-asposeslidessize) | شیء Thumbnail Image را برای تمام اسلایدهای یک ارائه با اندازهٔ مشخص برمی‌گرداند. |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/fa/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-asposeslidessize) | شیء Thumbnail Image را برای اسلایدهای مشخص‌شدهٔ یک ارائه با اندازهٔ مشخص برمی‌گرداند. |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/fa/aspose.slides/presentation/highlight_text/#str-asposeslidescolor) | تمام موارد متن نمونه را با رنگ مشخص برجسته می‌کند. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/fa/aspose.slides/presentation/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | تمام موارد متن نمونه را با رنگ مشخص برجسته می‌کند. |
| [`get_slide_by_id(self, id)`](/slides/python-net/fa/aspose.slides/presentation/get_slide_by_id/#int) | یک Slide، MasterSlide یا LayoutSlide را بر اساس Id برمی‌گرداند. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/fa/aspose.slides/presentation/join_portions_with_same_formatting/#) | قسمت‌های متن (runs) با فرمت یکسان را در تمام پاراگراف‌ها در تمام اشکال قابل قبول در همه اسلایدها ترکیب می‌کند. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/fa/aspose.slides/presentation/highlight_regex/#str-asposeslidescolor) | تمام موارد عبارت منظم را با رنگ مشخص برجسته می‌کند. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/fa/aspose.slides/presentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | تمام موارد متن مشخص‌شده را با متن دیگر مشخص جایگزین می‌کند. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/fa/aspose.slides/presentation/replace_regex/#str-str) | تمام موارد عبارت منظم را با رشتهٔ مشخص جایگزین می‌کند. |

### موارد مرتبط
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)