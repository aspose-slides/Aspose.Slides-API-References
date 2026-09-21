---
title: Presentation class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/presentation/
---
## کلاس Presentation

نمایانگر یک ارائه Microsoft PowerPoint است.

نوع Presentation اعضای زیر را در اختیار می‌گذارد:

## سازندگان

| سازنده | توضیح |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fa/aspose.slides/presentation/__init__/#) | این سازنده یک ارائه جدید را از ابتدا ایجاد می‌کند.<br/>            ارائه ایجاد شده دارای یک اسلاید خالی است. |
| [`__init__(self, load_options)`](/slides/python-net/fa/aspose.slides/presentation/__init__/#loadoptions) | این سازنده یک ارائه جدید را از ابتدا ایجاد می‌کند.<br/>            ارائه ایجاد شده دارای یک اسلاید خالی است. |
| [`__init__(self, stream)`](/slides/python-net/fa/aspose.slides/presentation/__init__/#iorawiobase) | این سازنده مکانیزم اصلی برای خواندن یک Presentation موجود است. |
| [`__init__(self, stream, load_options)`](/slides/python-net/fa/aspose.slides/presentation/__init__/#iorawiobase-loadoptions) | این سازنده مکانیزم اصلی برای خواندن یک Presentation موجود است. |
| [`__init__(self, file)`](/slides/python-net/fa/aspose.slides/presentation/__init__/#str) | این سازنده مسیر فایل منبع را می‌گیرد که از آن محتویات Presentation خوانده می‌شود. |
| [`__init__(self, file, load_options)`](/slides/python-net/fa/aspose.slides/presentation/__init__/#str-loadoptions) | این سازنده مسیر فایل منبع را می‌گیرد که از آن محتویات Presentation خوانده می‌شود. |

## خصوصیات

| خصوصیت | توضیح |
| :- | :- |
| [`current_date_time`](/slides/python-net/fa/aspose.slides/presentation/current_date_time/) | مقدار تاریخ و زمان را برمی‌گرداند یا تنظیم می‌کند که محتویات فیلدهای datetime را جایگزین می‌کند.<br/>            به‌طور پیش‌فرض زمان ایجاد این شیء Presentation.<br/>            قابل خواندن/نوشتن **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/fa/aspose.slides/presentation/header_footer_manager/) | مدیر HeaderFooter واقعی را برمی‌گرداند.<br/>            فقط-خواندنی [`IPresentationHeaderFooterManager`](/slides/python-net/fa/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/fa/aspose.slides/presentation/protection_manager/) | مدیر مجوزهای این ارائه را دریافت می‌کند.<br/>            فقط-خواندنی [`IProtectionManager`](/slides/python-net/fa/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/fa/aspose.slides/presentation/slides/) | لیستی از تمام اسلایدهای تعریف‌شده در ارائه را برمی‌گرداند.<br/fa/>            فقط-خواندنی [`ISlideCollection`](/slides/python-net/fa/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/fa/aspose.slides/presentation/sections/) | لیستی از تمام بخش‌های اسلایدهای تعریف‌شده در ارائه را برمی‌گرداند.<br/>            فقط-خواندنی [`ISectionCollection`](/slides/python-net/fa/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/fa/aspose.slides/presentation/slide_size/) | شیء اندازه اسلاید را برمی‌گرداند.<br/>            فقط-خواندنی [`ISlideSize`](/slides/python-net/fa/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/fa/aspose.slides/presentation/notes_size/) | شیء اندازه اسلاید یادداشت‌ها را برمی‌گرداند.<br/>            فقط-خواندنی [`INotesSize`](/slides/python-net/fa/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/fa/aspose.slides/presentation/layout_slides/) | لیستی از تمام اسلایدهای طرح‌بندی تعریف‌شده در ارائه را برمی‌گرداند.<br/>            فقط-خواندنی [`IGlobalLayoutSlideCollection`](/slides/python-net/fa/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/fa/aspose.slides/presentation/masters/) | لیستی از تمام اسلایدهای استاد (master) تعریف‌شده در ارائه را برمی‌گرداند.<br/>            فقط-خواندنی [`IMasterSlideCollection`](/slides/python-net/fa/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/fa/aspose.slides/presentation/master_notes_slide_manager/) | مدیر استاد یادداشت‌ها را برمی‌گرداند.<br/>            فقط-خواندنی [`IMasterNotesSlideManager`](/slides/python-net/fa/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/fa/aspose.slides/presentation/master_handout_slide_manager/) | مدیر استاد توزیع (handout) را برمی‌گرداند.<br/>            فقط-خواندنی [`IMasterHandoutSlideManager`](/slides/python-net/fa/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/fa/aspose.slides/presentation/fonts_manager/) | مدیر قلم‌ها را برمی‌گرداند.<br/>            فقط-خواندنی [`IFontsManager`](/slides/python-net/fa/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/fa/aspose.slides/presentation/default_text_style/) | سبک متن پیش فرض برای شکل‌ها را برمی‌گرداند.<br/>            فقط-خواندنی [`ITextStyle`](/slides/python-net/fa/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/fa/aspose.slides/presentation/comment_authors/) | مجموعه نظردهندگان را برمی‌گرداند.<br/>            فقط-خواندنی [`ICommentAuthorCollection`](/slides/python-net/fa/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/fa/aspose.slides/presentation/document_properties/) | شیء DocumentProperties را برمی‌گرداند که شامل ویژگی‌های استاندارد و سفارشی سند است.<br/>            فقط-خواندنی [`IDocumentProperties`](/slides/python-net/fa/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/fa/aspose.slides/presentation/images/) | مجموعه تمام تصاویر در ارائه را برمی‌گرداند.<br/>            فقط-خواندنی [`IImageCollection`](/slides/python-net/fa/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/fa/aspose.slides/presentation/audios/) | مجموعه تمام فایل‌های صوتی توکار در ارائه را برمی‌گرداند.<br/>            فقط-خواندنی [`IAudioCollection`](/slides/python-net/fa/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/fa/aspose.slides/presentation/videos/) | مجموعه تمام فایل‌های ویدئویی توکار در ارائه را برمی‌گرداند.<br/>            فقط-خواندنی [`IVideoCollection`](/slides/python-net/fa/aspose.slides/ivideocollection). |
| [`slide_show_settings`](/slides/python-net/fa/aspose.slides/presentation/slide_show_settings/) | تنظیمات نمایش اسلاید برای ارائه را برمی‌گرداند. |
| [`digital_signatures`](/slides/python-net/fa/aspose.slides/presentation/digital_signatures/) | مجموعه امضاهایی که برای امضای ارائه استفاده می‌شوند را برمی‌گرداند.<br/>            فقط-خواندنی [`IDigitalSignatureCollection`](/slides/python-net/fa/aspose.slides/idigitalsignaturecollection). |
| [`custom_data`](/slides/python-net/fa/aspose.slides/presentation/custom_data/) | داده‌های سفارشی ارائه را برمی‌گرداند.<br/>            فقط-خواندنی [`ICustomData`](/slides/python-net/fa/aspose.slides/icustomdata). |
| [`all_custom_xml_parts`](/slides/python-net/fa/aspose.slides/presentation/all_custom_xml_parts/) | تمام بخش‌های داده سفارشی در ارائه را برمی‌گرداند.<br/>            فقط-خواندنی [`ICustomXmlPart`](/slides/python-net/fa/aspose.slides/icustomxmlpart)[]. |
| [`vba_project`](/slides/python-net/fa/aspose.slides/presentation/vba_project/) | پروژه VBA با ماکروهای ارائه را دریافت یا تنظیم می‌کند.<br/>            قابل خواندن/نوشتن [`IVbaProject`](/slides/python-net/fa/aspose.slides.vba/ivbaproject). |
| [`hyperlink_queries`](/slides/python-net/fa/aspose.slides/presentation/hyperlink_queries/) | دسترسی آسان به تمام پیوندهای موجود در تمام اسلایدهای ارائه (نه در استاد، طرح‌بندی یا اسلایدهای یادداشت) را فراهم می‌کند.<br/>            فقط-خواندنی [`IHyperlinkQueries`](/slides/python-net/fa/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/fa/aspose.slides/presentation/view_properties/) | ویژگی‌های نمای کلی ارائه را دریافت می‌کند.<br/>            فقط-خواندنی [`IViewProperties`](/slides/python-net/fa/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/fa/aspose.slides/presentation/first_slide_number/) | شماره اولین اسلاید در ارائه را نشان می‌دهد |
| [`sensitivity_labels`](/slides/python-net/fa/aspose.slides/presentation/sensitivity_labels/) | مجموعه برچسب‌های حساسیتی اعمال‌شده بر سند ارائه را برمی‌گرداند.<br/>            فقط-خواندنی [`ISensitivityLabelCollection`](/slides/python-net/fa/aspose.slides/isensitivitylabelcollection). |
| [`source_format`](/slides/python-net/fa/aspose.slides/presentation/source_format/) | اطلاعاتی درباره قالبی که ارائه از آن بارگذاری شده را برمی‌گرداند.<br/>            فقط-خواندنی [`SourceFormat`](/slides/python-net/fa/aspose.slides/sourceformat). |
| [`master_theme`](/slides/python-net/fa/aspose.slides/presentation/master_theme/) | تم استاد را برمی‌گرداند.<br/>            فقط-خواندنی [`IMasterTheme`](/slides/python-net/fa/aspose.slides.theme/imastertheme). |
| [`presentation`](/slides/python-net/fa/aspose.slides/presentation/presentation/) |  |

## متدها

| متد | توضیح |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/fa/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat) | تمام اسلایدهای یک ارائه را به فایلی با قالب مشخص ذخیره می‌کند. |
| [`save(self, stream, format)`](/slides/python-net/fa/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat) | تمام اسلایدهای یک ارائه را به جریان (stream) با قالب مشخص ذخیره می‌کند. |
| [`save(self, fname, format, options)`](/slides/python-net/fa/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) |  |
| [`save(self, stream, format, options)`](/slides/python-net/fa/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | تمام اسلایدهای یک ارائه را به جریان (stream) با قالب مشخص و گزینه‌های اضافی ذخیره می‌کند. |
| [`save(self, options)`](/slides/python-net/fa/aspose.slides/presentation/save/#asposeslidesexportxamlixamloptions) | تمام اسلایدهای یک ارائه را به مجموعه‌ای از فایل‌ها که نمایندۀ XAML هستند ذخیره می‌کند. |
| [`save(self, fname, slides, format)`](/slides/python-net/fa/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat) | اسلایدهای مشخصی از یک ارائه را به فایلی با قالب مشخص ذخیره می‌کند، با حفظ شماره صفحه. |
| [`save(self, fname, slides, format, options)`](/slides/python-net/fa/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | اسلایدهای مشخصی از یک ارائه را به فایلی با قالب مشخص ذخیره می‌کند، با حفظ شماره صفحه. |
| [`save(self, stream, slides, format)`](/slides/python-net/fa/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | اسلایدهای مشخصی از یک ارائه را به جریان (stream) با قالب مشخص و حفظ شماره صفحه ذخیره می‌کند. |
| [`save(self, stream, slides, format, options)`](/slides/python-net/fa/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | اسلایدهای مشخصی از یک ارائه را به جریان (stream) با قالب مشخص و حفظ شماره صفحه ذخیره می‌کند. |
| [`get_images(self, options)`](/slides/python-net/fa/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions) | یک شیء Image برای تمام اسلایدهای یک ارائه برمی‌گرداند. |
| [`get_images(self, options, slides)`](/slides/python-net/fa/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint) | یک شیء تصویر بندانگشتی برای اسلایدهای مشخصی از یک ارائه برمی‌گرداند. |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/fa/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-float-float) | یک شیء تصویر بندانگشتی برای تمام اسلایدهای یک ارائه با مقیاس سفارشی برمی‌گرداند. |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/fa/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | یک شیء تصویر بندانگشتی برای اسلایدهای مشخصی از یک ارائه با مقیاس سفارشی برمی‌گرداند. |
| [`get_images(self, options, image_size)`](/slides/python-net/fa/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-asposepydrawingsize) | یک شیء تصویر بندانگشتی برای تمام اسلایدهای یک ارائه با اندازه مشخص برمی‌گرداند. |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/fa/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-asposepydrawingsize) | یک شیء تصویر بندانگشتی برای اسلایدهای مشخصی از یک ارائه با اندازه مشخص برمی‌گرداند. |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/fa/aspose.slides/presentation/highlight_text/#str-asposepydrawingcolor) | تمام تطبیق‌های متن نمونه را با رنگ مشخص برجسته می‌کند. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/fa/aspose.slides/presentation/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | تمام تطبیق‌های متن نمونه را با رنگ مشخص برجسته می‌کند. |
| [`get_slide_by_id(self, id)`](/slides/python-net/fa/aspose.slides/presentation/get_slide_by_id/#int) | اسلاید، MasterSlide یا LayoutSlide را بر اساس Id برمی‌گرداند. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/fa/aspose.slides/presentation/join_portions_with_same_formatting/#) | اجراهای (runs) با فرمت یکسان را در تمام پاراگراف‌ها در تمام اشکال قابل قبول در تمام اسلایدها ترکیب می‌کند. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/fa/aspose.slides/presentation/highlight_regex/#str-asposepydrawingcolor) | تمام تطبیق‌های عبارت منظم را با رنگ مشخص برجسته می‌کند. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/fa/aspose.slides/presentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | تمام رخدادهای متن مشخص را با متن دیگری جایگزین می‌کند. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/fa/aspose.slides/presentation/replace_regex/#str-str) | تمام تطبیق‌های عبارت منظم را با رشته مشخص جایگزین می‌کند. |


### موارد مرتبط
* module [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)