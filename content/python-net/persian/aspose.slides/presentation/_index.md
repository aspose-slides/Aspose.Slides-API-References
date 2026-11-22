---
title: Presentation class
second_title: Aspose.Slides برای Python از طریق .NET API Reference
description: 
type: docs
url: /fa/aspose.slides/presentation/
---
## کلاس Presentation

یک ارائه Microsoft PowerPoint را نمایندگی می‌کند.

The Presentation type exposes the following members:

## سازنده‌ها

| سازنده | توضیح |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fa/aspose.slides/presentation/__init__/#) | این سازنده یک ارائه جدید از ابتدا ایجاد می‌کند.<br/> ارائه ایجاد شده دارای یک اسلاید خالی است. |
| [`__init__(self, load_options)`](/slides/python-net/fa/aspose.slides/presentation/__init__/#loadoptions) | این سازنده یک ارائه جدید از ابتدا ایجاد می‌کند.<br/> ارائه ایجاد شده دارای یک اسلاید خالی است. |
| [`__init__(self, stream)`](/slides/python-net/fa/aspose.slides/presentation/__init__/#iorawiobase) | این سازنده مکانیزم اصلی برای خواندن یک Presentation موجود است. |
| [`__init__(self, stream, load_options)`](/slides/python-net/fa/aspose.slides/presentation/__init__/#iorawiobase-loadoptions) | این سازنده مکانیزم اصلی برای خواندن یک Presentation موجود است. |
| [`__init__(self, file)`](/slides/python-net/fa/aspose.slides/presentation/__init__/#str) | این سازنده مسیر فایل منبع را دریافت می‌کند که از آن<br/> محتویات Presentation خوانده می‌شود. |
| [`__init__(self, file, load_options)`](/slides/python-net/fa/aspose.slides/presentation/__init__/#str-loadoptions) | این سازنده مسیر فایل منبع را دریافت می‌کند که از آن<br/> محتویات Presentation خوانده می‌شود. |

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`current_date_time`](/slides/python-net/fa/aspose.slides/presentation/current_date_time/) | تاریخ و زمان را برمی‌گرداند یا تنظیم می‌کند که محتویات فیلدهای datetime را جایگزین می‌کند.<br/> زمان ایجاد این شیء Presentation به‌طور پیش‌فرض.<br/> خواندن/نوشتن **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/fa/aspose.slides/presentation/header_footer_manager/) | مدیر HeaderFooter فعلی را برمی‌گرداند.<br/> فقط‌خواندنی [`IPresentationHeaderFooterManager`](/slides/python-net/fa/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/fa/aspose.slides/presentation/protection_manager/) | مدیر مجوزهای این ارائه را دریافت می‌کند.<br/> فقط‌خواندنی [`IProtectionManager`](/slides/python-net/fa/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/fa/aspose.slides/presentation/slides/) | فهرستی از تمام اسلایدهایی که در ارائه تعریف شده‌اند را بر می‌گرداند.<br/fa/> فقط‌خواندنی [`ISlideCollection`](/slides/python-net/fa/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/fa/aspose.slides/presentation/sections/) | فهرستی از تمام بخش‌های اسلاید که در ارائه تعریف شده‌اند را بر می‌گرداند.<br/> فقط‌خواندنی [`ISectionCollection`](/slides/python-net/fa/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/fa/aspose.slides/presentation/slide_size/) | شیء اندازه اسلاید را بر می‌گرداند.<br/> فقط‌خواندنی [`ISlideSize`](/slides/python-net/fa/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/fa/aspose.slides/presentation/notes_size/) | شیء اندازه اسلاید یادداشت‌ها را بر می‌گرداند.<br/> فقط‌خواندنی [`INotesSize`](/slides/python-net/fa/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/fa/aspose.slides/presentation/layout_slides/) | فهرستی از تمام اسلایدهای طرح‌بندی که در ارائه تعریف شده‌اند را بر می‌گرداند.<br/> فقط‌خواندنی [`IGlobalLayoutSlideCollection`](/slides/python-net/fa/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/fa/aspose.slides/presentation/masters/) | فهرستی از تمام اسلایدهای اصلی که در ارائه تعریف شده‌اند را بر می‌گرداند.<br/> فقط‌خواندنی [`IMasterSlideCollection`](/slides/python-net/fa/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/fa/aspose.slides/presentation/master_notes_slide_manager/) | مدیر اصلی یادداشت‌ها را بر می‌گرداند.<br/> فقط‌خواندنی [`IMasterNotesSlideManager`](/slides/python-net/fa/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/fa/aspose.slides/presentation/master_handout_slide_manager/) | مدیر اصلی توزیع کننده را بر می‌گرداند.<br/> فقط‌خواندنی [`IMasterHandoutSlideManager`](/slides/python-net/fa/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/fa/aspose.slides/presentation/fonts_manager/) | مدیر قلم‌ها را بر می‌گرداند.<br/> فقط‌خواندنی [`IFontsManager`](/slides/python-net/fa/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/fa/aspose.slides/presentation/default_text_style/) | سبک متنی پیش‌فرض برای شکل‌ها را بر می‌گرداند.<br/> فقط‌خواندنی [`ITextStyle`](/slides/python-net/fa/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/fa/aspose.slides/presentation/comment_authors/) | مجموعهٔ نویسندگان نظرات را بر می‌گرداند.<br/> فقط‌خواندنی [`ICommentAuthorCollection`](/slides/python-net/fa/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/fa/aspose.slides/presentation/document_properties/) | شیء DocumentProperties را بر می‌گرداند که شامل ویژگی‌های استاندارد و سفارشی سند است.<br/> فقط‌خواندنی [`IDocumentProperties`](/slides/python-net/fa/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/fa/aspose.slides/presentation/images/) | مجموعهٔ تمام تصاویر در ارائه را بر می‌گرداند.<br/> فقط‌خواندنی [`IImageCollection`](/slides/python-net/fa/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/fa/aspose.slides/presentation/audios/) | مجموعهٔ تمام فایل‌های صوتی توکار در ارائه را بر می‌گرداند.<br/> فقط‌خواندنی [`IAudioCollection`](/slides/python-net/fa/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/fa/aspose.slides/presentation/videos/) | مجموعهٔ تمام فایل‌های ویدئویی توکار در ارائه را بر می‌گرداند.<br/> فقط‌خواندنی [`IVideoCollection`](/slides/python-net/fa/aspose.slides/ivideocollection). |
| [`slide_show_settings`](/slides/python-net/fa/aspose.slides/presentation/slide_show_settings/) | تنظیمات نمایش اسلاید برای ارائه را بر می‌گرداند. |
| [`digital_signatures`](/slides/python-net/fa/aspose.slides/presentation/digital_signatures/) | مجموعهٔ امضاهایی که برای امضای ارائه استفاده شده‌اند را بر می‌گرداند.<br/> فقط‌خواندنی [`IDigitalSignatureCollection`](/slides/python-net/fa/aspose.slides/idigitalsignaturecollection). |
| [`custom_data`](/slides/python-net/fa/aspose.slides/presentation/custom_data/) | داده‌های سفارشی ارائه را بر می‌گرداند.<br/> فقط‌خواندنی [`ICustomData`](/slides/python-net/fa/aspose.slides/icustomdata). |
| [`all_custom_xml_parts`](/slides/python-net/fa/aspose.slides/presentation/all_custom_xml_parts/) | تمام بخش‌های دادهٔ سفارشی در ارائه را بر می‌گرداند.<br/> فقط‌خواندنی [`ICustomXmlPart`](/slides/python-net/fa/aspose.slides/icustomxmlpart)[]. |
| [`vba_project`](/slides/python-net/fa/aspose.slides/presentation/vba_project/) | پروژه VBA همراه با ماکروهای ارائه را دریافت یا تنظیم می‌کند.<br/> خواندن/نوشتن [`IVbaProject`](/slides/python-net/fa/aspose.slides.vba/ivbaproject). |
| [`hyperlink_queries`](/slides/python-net/fa/aspose.slides/presentation/hyperlink_queries/) | دسترسی آسان به تمام پیوندهای موجود در تمام اسلایدهای ارائه فراهم می‌کند (نه در اسلایدهای اصلی، طرح‌بندی یا یادداشت).<br/> فقط‌خواندنی [`IHyperlinkQueries`](/slides/python-net/fa/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/fa/aspose.slides/presentation/view_properties/) | ویژگی‌های نمای کلی ارائه را دریافت می‌کند.<br/> فقط‌خواندنی [`IViewProperties`](/slides/python-net/fa/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/fa/aspose.slides/presentation/first_slide_number/) | شمارهٔ اولین اسلاید در ارائه را نمایندگی می‌کند |
| [`sensitivity_labels`](/slides/python-net/fa/aspose.slides/presentation/sensitivity_labels/) | مجموعهٔ برچسب‌های حساسیتی که به سند ارائه اعمال شده‌اند را بر می‌گرداند.<br/> فقط‌خواندنی [`ISensitivityLabelCollection`](/slides/python-net/fa/aspose.slides/isensitivitylabelcollection). |
| [`source_format`](/slides/python-net/fa/aspose.slides/presentation/source_format/) | اطلاعاتی دربارهٔ فرمتیکه ارائه بارگذاری شده است را بر می‌گرداند.<br/> فقط‌خواندنی [`SourceFormat`](/slides/python-net/fa/aspose.slides/sourceformat). |
| [`master_theme`](/slides/python-net/fa/aspose.slides/presentation/master_theme/) | قالب اصلی را بر می‌گرداند.<br/> فقط‌خواندنی [`IMasterTheme`](/slides/python-net/fa/aspose.slides.theme/imastertheme). |
| [`presentation`](/slides/python-net/fa/aspose.slides/presentation/presentation/) |  |

## متدها

| متد | توضیح |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/fa/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat) | تمام اسلایدهای یک ارائه را در فایلی با فرمت مشخص ذخیره می‌کند. |
| [`save(self, stream, format)`](/slides/python-net/fa/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat) | تمام اسلایدهای یک ارائه را در یک جریان با فرمت مشخص ذخیره می‌کند. |
| [`save(self, fname, format, options)`](/slides/python-net/fa/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) |  |
| [`save(self, stream, format, options)`](/slides/python-net/fa/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | تمام اسلایدهای یک ارائه را در یک جریان با فرمت مشخص و با گزینه‌های اضافی ذخیره می‌کند. |
| [`save(self, options)`](/slides/python-net/fa/aspose.slides/presentation/save/#asposeslidesexportxamlixamloptions) | تمام اسلایدهای یک ارائه را در مجموعه‌ای از فایل‌ها که نشانگر XAML هستند ذخیره می‌کند. |
| [`save(self, fname, slides, format)`](/slides/python-net/fa/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat) | اسلایدهای مشخص شدهٔ یک ارائه را در فایلی با فرمت مشخص و حفظ شماره صفحه ذخیره می‌کند. |
| [`save(self, fname, slides, format, options)`](/slides/python-net/fa/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | اسلایدهای مشخص شدهٔ یک ارائه را در فایلی با فرمت مشخص و حفظ شماره صفحه ذخیره می‌کند. |
| [`save(self, stream, slides, format)`](/slides/python-net/fa/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | اسلایدهای مشخص شدهٔ یک ارائه را در یک جریان با فرمت مشخص و حفظ شماره صفحه ذخیره می‌کند. |
| [`save(self, stream, slides, format, options)`](/slides/python-net/fa/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | اسلایدهای مشخص شدهٔ یک ارائه را در یک جریان با فرمت مشخص و حفظ شماره صفحه ذخیره می‌کند. |
| [`get_images(self, options)`](/slides/python-net/fa/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions) | یک شیء Image برای تمام اسلایدهای یک ارائه را برمی‌گرداند. |
| [`get_images(self, options, slides)`](/slides/python-net/fa/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint) | یک شیء Thumbnail Image برای اسلایدهای مشخص شدهٔ یک ارائه را برمی‌گرداند. |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/fa/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-float-float) | یک شیء Thumbnail Image برای تمام اسلایدهای یک ارائه با مقیاس سفارشی را برمی‌گرداند. |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/fa/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | یک شیء Thumbnail Image برای اسلایدهای مشخص شدهٔ یک ارائه با مقیاس سفارشی را برمی‌گرداند. |
| [`get_images(self, options, image_size)`](/slides/python-net/fa/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-asposeslidessize) | یک شیء Thumbnail Image برای تمام اسلایدهای یک ارائه با اندازهٔ مشخص را برمی‌گرداند. |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/fa/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-asposeslidessize) | یک شیء Thumbnail Image برای اسلایدهای مشخص شدهٔ یک ارائه با اندازهٔ مشخص را برمی‌گرداند. |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/fa/aspose.slides/presentation/highlight_text/#str-asposeslidescolor) | تمام موارد متنی نمونه را با رنگ مشخص برجسته می‌کند. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/fa/aspose.slides/presentation/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | تمام موارد متنی نمونه را با رنگ مشخص برجسته می‌کند. |
| [`get_slide_by_id(self, id)`](/slides/python-net/fa/aspose.slides/presentation/get_slide_by_id/#int) | یک Slide، MasterSlide یا LayoutSlide را بر اساس شناسه برمی‌گرداند. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/fa/aspose.slides/presentation/join_portions_with_same_formatting/#) | بخش‌های متنی با قالب‌بندی یکسان را در تمام پاراگراف‌ها در تمام شکل‌های قابل قبول در تمامی اسلایدها ترکیب می‌کند. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/fa/aspose.slides/presentation/highlight_regex/#str-asposeslidescolor) | تمام موارد منطبق با عبارت منظم را با رنگ مشخص برجسته می‌کند. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/fa/aspose.slides/presentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | تمام موارد متن مشخص شده را با متن دیگری که مشخص شده جایگزین می‌کند. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/fa/aspose.slides/presentation/replace_regex/#str-str) | تمام موارد منطبق با عبارت منظم را با رشتهٔ مشخص شده جایگزین می‌کند. |
| [`refresh_charts_data(self, skip_failed_charts)`](/slides/python-net/fa/aspose.slides/presentation/refresh_charts_data/#bool) | داده‌های تمام نمودارها در ارائه را از کتاب‌های کار منبعشان بازخوانی می‌کند. |

### همچنین ببینید
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)