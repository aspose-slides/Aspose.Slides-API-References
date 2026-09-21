---
title: ShapeCollection class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/shapecollection/
---
## کلاس ShapeCollection

نمایش یک مجموعه از اشکال.

نوع ShapeCollection اعضای زیر را ارائه می‌دهد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`parent_group`](/slides/python-net/fa/aspose.slides/shapecollection/parent_group/) | شیء گروه شکل والد برای مجموعهٔ اشکال را دریافت می‌کند.<br/>            فقط‌خواندنی [`IGroupShape`](/slides/python-net/fa/aspose.slides/igroupshape). |

عنصری را در ایندکس مشخص دریافت می‌کند.
            فقط‌خواندنی [`IShape`](/slides/python-net/fa/aspose.slides/ishape).

## فهرست‌ساز

| نام | توضیح |
| :- | :- |
| [`[index]`](/slides/python-net/fa/aspose.slides/shapecollection/__getitem__/) |  |

## متدها

| متد | توضیح |
| :- | :- |
| [`add_chart(self, type, x, y, width, height)`](/slides/python-net/fa/aspose.slides/shapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌های نمونهٔ سری و تنظیمات اولیه می‌کند، و<br/>            به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [`add_chart(self, type, x, y, width, height, init_with_sample)`](/slides/python-net/fa/aspose.slides/shapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float-bool) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌های نمونهٔ سری و تنظیمات اولیه می‌کند، و<br/>            به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [`insert_chart(self, type, x, y, width, height, index)`](/slides/python-net/fa/aspose.slides/shapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌های نمونهٔ سری و تنظیمات اولیه می‌کند،<br/>            و در ایندکس مشخص به مجموعهٔ اشکال اضافه می‌کند. |
| [`insert_chart(self, type, x, y, width, height, index, init_with_sample)`](/slides/python-net/fa/aspose.slides/shapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int-bool) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌های نمونهٔ سری و تنظیمات اولیه می‌کند،<br/>            و در ایندکس مشخص به مجموعهٔ اشکال اضافه می‌کند. |
| [`add_zoom_frame(self, x, y, width, height, slide)`](/slides/python-net/fa/aspose.slides/shapecollection/add_zoom_frame/#float-float-float-float-islide) | یک فریم Zoom جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [`add_zoom_frame(self, x, y, width, height, slide, image)`](/slides/python-net/fa/aspose.slides/shapecollection/add_zoom_frame/#float-float-float-float-islide-ippimage) | یک فریم Zoom جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide)`](/slides/python-net/fa/aspose.slides/shapecollection/insert_zoom_frame/#int-float-float-float-float-islide) | یک فریم Zoom جدید ایجاد می‌کند و در ایندکس مشخص به مجموعهٔ اشکال اضافه می‌کند. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide, image)`](/slides/python-net/fa/aspose.slides/shapecollection/insert_zoom_frame/#int-float-float-float-float-islide-ippimage) | یک فریم Zoom جدید با تصویر پیش‌تعریف شده ایجاد می‌کند و در ایندکس مشخص به مجموعهٔ اشکال<br/>            اضافه می‌کند. |
| [`add_section_zoom_frame(self, x, y, width, height, section)`](/slides/python-net/fa/aspose.slides/shapecollection/add_section_zoom_frame/#float-float-float-float-isection) | یک فریم Zoom بخش جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [`add_section_zoom_frame(self, x, y, width, height, section, image)`](/slides/python-net/fa/aspose.slides/shapecollection/add_section_zoom_frame/#float-float-float-float-isection-ippimage) | یک فریم Zoom بخش جدید با تصویر پیش‌تعریف شده ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section)`](/slides/python-net/fa/aspose.slides/shapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection) | یک فریم Zoom بخش جدید ایجاد می‌کند و در ایندکس مشخص به مجموعهٔ اشکال اضافه می‌کند. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section, image)`](/slides/python-net/fa/aspose.slides/shapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection-ippimage) | یک فریم Zoom بخش جدید با تصویر پیش‌تعریف شده ایجاد می‌کند و در ایندکس مشخص به مجموعهٔ اشکال<br/>            اضافه می‌کند. |
| [`add_ole_object_frame(self, x, y, width, height, data_info)`](/slides/python-net/fa/aspose.slides/shapecollection/add_ole_object_frame/#float-float-float-float-ioleembeddeddatainfo) | یک فریم شیء OLE جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [`add_ole_object_frame(self, x, y, width, height, class_name, path)`](/slides/python-net/fa/aspose.slides/shapecollection/add_ole_object_frame/#float-float-float-float-str-str) | یک فریم شیء OLE جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [`insert_ole_object_frame(self, index, x, y, width, height, data_info)`](/slides/python-net/fa/aspose.slides/shapecollection/insert_ole_object_frame/#int-float-float-float-float-ioleembeddeddatainfo) | یک فریم شیء OLE جدید ایجاد می‌کند و در ایندکس مشخص به مجموعهٔ اشکال اضافه می‌کند. |
| [`insert_ole_object_frame(self, index, x, y, width, height, class_name, path)`](/slides/python-net/fa/aspose.slides/shapecollection/insert_ole_object_frame/#int-float-float-float-float-str-str) | یک فریم شیء OLE جدید ایجاد می‌کند و در ایندکس مشخص به مجموعهٔ اشکال اضافه می‌کند. |
| [`add_video_frame(self, x, y, width, height, fname)`](/slides/python-net/fa/aspose.slides/shapecollection/add_video_frame/#float-float-float-float-str) | یک فریم ویدئویی جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [`add_video_frame(self, x, y, width, height, video)`](/slides/python-net/fa/aspose.slides/shapecollection/add_video_frame/#float-float-float-float-ivideo) | یک فریم ویدئویی جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio_stream)`](/slides/python-net/fa/aspose.slides/shapecollection/add_audio_frame_embedded/#float-float-float-float-iorawiobase) | یک فریم صوتی جدید با فایل WAV جاسازی شده ایجاد می‌کند و به انتهای<br/>            مجموعهٔ اشکال اضافه می‌کند. صداهای جاسازی شده به مجموعهٔ Presentation.Audios اضافه می‌شوند. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio)`](/slides/python-net/fa/aspose.slides/shapecollection/add_audio_frame_embedded/#float-float-float-float-iaudio) | یک فریم صوتی جدید ایجاد می‌کند و با استفاده از شیء صوتی موجود در فهرست Presentation.Audios به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream)`](/slides/python-net/fa/aspose.slides/shapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iorawiobase) | یک فریم صوتی جدید با فایل WAV جاسازی شده ایجاد می‌کند و در ایندکس مشخص به مجموعهٔ<br/>            اشکال اضافه می‌کند. صداهای جاسازی شده به مجموعهٔ Presentation.Audios<br/>            اضافه می‌شوند. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio)`](/slides/python-net/fa/aspose.slides/shapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iaudio) | یک فریم صوتی جدید ایجاد می‌کند و با استفاده از شیء صوتی موجود در فهرست Presentation.Audios در ایندکس مشخص به مجموعهٔ اشکال اضافه می‌کند. |
| [`to_array(self)`](/slides/python-net/fa/aspose.slides/shapecollection/to_array/#) | یک آرایه که شامل تمام اشکال است را ایجاد و برمی‌گرداند. |
| [`to_array(self, start_index, count)`](/slides/python-net/fa/aspose.slides/shapecollection/to_array/#int-int) | یک آرایه که شامل تمام اشکال در بازهٔ مشخص شده است را ایجاد و برمی‌گرداند. |
| [`reorder(self, index, shape)`](/slides/python-net/fa/aspose.slides/shapecollection/reorder/#int-ishape) | شکل مشخص‌شده را به موقعیت جدیدی داخل مجموعهٔ اشکال منتقل می‌کند. |
| [`reorder(self, index, shapes)`](/slides/python-net/fa/aspose.slides/shapecollection/reorder/#int-listishape) | اشکال مشخص‌شده را داخل مجموعهٔ اشکال جابجا می‌کند، به طوری که از ایندکس داده شده شروع می‌شود. |
| [`add_auto_shape(self, shape_type, x, y, width, height)`](/slides/python-net/fa/aspose.slides/shapecollection/add_auto_shape/#shapetype-float-float-float-float) | یک شکل خودکار جدید با قالب‌بندی پیش‌فرض ایجاد می‌کند و به انتهای<br/>            مجموعهٔ اشکال اضافه می‌کند. |
| [`add_auto_shape(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/fa/aspose.slides/shapecollection/add_auto_shape/#shapetype-float-float-float-float-bool) | یک شکل خودکار جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌کند، به‌صورت اختیاری<br/>            با قالب‌بندی پیش‌فرض قالب‌بندی می‌شود. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height)`](/slides/python-net/fa/aspose.slides/shapecollection/insert_auto_shape/#int-shapetype-float-float-float-float) | یک شکل خودکار جدید ایجاد می‌کند و در ایندکس مشخص به مجموعهٔ اشکال اضافه می‌کند،<br/>            با قالب‌بندی پیش‌فرض قالب‌بندی می‌شود. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/fa/aspose.slides/shapecollection/insert_auto_shape/#int-shapetype-float-float-float-float-bool) | یک شکل خودکار جدید ایجاد می‌کند و در ایندکس مشخص به مجموعهٔ اشکال اضافه می‌کند،<br/>            به‌صورت اختیاری با استایل پیش‌فرض قالب‌بندی می‌شود. |
| [`add_group_shape(self)`](/slides/python-net/fa/aspose.slides/shapecollection/add_group_shape/#) | یک گروه شکل خالی جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌کند.<br/>            چارچوب گروه به‌صورت خودکار برای جا دادن هر شکلی که به آن اضافه می‌شود تنظیم می‌شود. |
| [`add_group_shape(self, svg_image, x, y, width, height)`](/slides/python-net/fa/aspose.slides/shapecollection/add_group_shape/#isvgimage-float-float-float-float) | یک گروه شکل جدید ایجاد می‌کند، تصویر SVG مشخص‌شده را به اشکال فردی تبدیل می‌کند،<br/>            و گروه حاصل را به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [`add_connector(self, shape_type, x, y, width, height)`](/slides/python-net/fa/aspose.slides/shapecollection/add_connector/#shapetype-float-float-float-float) | یک شکل اتصال‌دهنده جدید با استایل پیش‌فرض قالب ایجاد می‌کند و به انتهای<br/>            مجموعهٔ اشکال اضافه می‌کند. |
| [`add_connector(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/fa/aspose.slides/shapecollection/add_connector/#shapetype-float-float-float-float-bool) | یک شکل اتصال‌دهنده جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌کند،<br/>            به‌صورت اختیاری با استایل پیش‌فرض قالب‌بندی می‌شود. |
| [`insert_connector(self, index, shape_type, x, y, width, height)`](/slides/python-net/fa/aspose.slides/shapecollection/insert_connector/#int-shapetype-float-float-float-float) | یک شکل اتصال‌دهنده جدید ایجاد می‌کند و در ایندکس مشخص به مجموعهٔ اشکال اضافه می‌کند،<br/>            با استایل پیش‌فرض قالب‌بندی می‌شود. |
| [`insert_connector(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/fa/aspose.slides/shapecollection/insert_connector/#int-shapetype-float-float-float-float-bool) | یک شکل اتصال‌دهنده جدید ایجاد می‌کند و در ایندکس مشخص به مجموعهٔ اشکال اضافه می‌کند،<br/>            به‌صورت اختیاری با استایل پیش‌فرض قالب‌بندی می‌شود. |
| [`add_clone(self, source_shape, x, y, width, height)`](/slides/python-net/fa/aspose.slides/shapecollection/add_clone/#ishape-float-float-float-float) | یک نسخهٔ کپی از شکل مشخص‌شده ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [`add_clone(self, source_shape, x, y)`](/slides/python-net/fa/aspose.slides/shapecollection/add_clone/#ishape-float-float) | یک نسخهٔ کپی از شکل مشخص‌شده ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌کند.<br/>            شکل جدید عرض و ارتفاع `source_shape` را حفظ می‌کند. |
| [`add_clone(self, source_shape)`](/slides/python-net/fa/aspose.slides/shapecollection/add_clone/#ishape) | یک نسخهٔ کپی از شکل مشخص‌شده ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌کند.<br/>            شکل تکثیر شده موقعیت و اندازهٔ اصلی را حفظ می‌کند. |
| [`insert_clone(self, index, source_shape, x, y, width, height)`](/slides/python-net/fa/aspose.slides/shapecollection/insert_clone/#int-ishape-float-float-float-float) | یک نسخهٔ کپی از شکل مشخص‌شده ایجاد می‌کند و در ایندکس مشخص به مجموعهٔ اشکال اضافه می‌کند. |
| [`insert_clone(self, index, source_shape, x, y)`](/slides/python-net/fa/aspose.slides/shapecollection/insert_clone/#int-ishape-float-float) | یک نسخهٔ کپی از شکل مشخص‌شده ایجاد می‌کند و در ایندکس مشخص به مجموعهٔ اشکال اضافه می‌کند.<br/>            شکل جدید عرض و ارتفاع `source_shape` را حفظ می‌کند. |
| [`insert_clone(self, index, source_shape)`](/slides/python-net/fa/aspose.slides/shapecollection/insert_clone/#int-ishape) | یک نسخهٔ کپی از شکل مشخص‌شده ایجاد می‌کند و در ایندکس مشخص به مجموعهٔ اشکال اضافه می‌کند.<br/>            شکل تکثیر شده موقعیت و اندازهٔ اصلی را حفظ می‌کند. |
| [`add_smart_art(self, x, y, width, height, layout_type)`](/slides/python-net/fa/aspose.slides/shapecollection/add_smart_art/#float-float-float-float-asposeslidessmartartsmartartlayouttype) | یک نمودار SmartArt ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [`add_summary_zoom_frame(self, x, y, width, height)`](/slides/python-net/fa/aspose.slides/shapecollection/add_summary_zoom_frame/#float-float-float-float) | یک فریم Summary Zoom جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [`insert_summary_zoom_frame(self, index, x, y, width, height)`](/slides/python-net/fa/aspose.slides/shapecollection/insert_summary_zoom_frame/#int-float-float-float-float) | یک فریم Summary Zoom جدید ایجاد می‌کند و در ایندکس مشخص به مجموعهٔ اشکال اضافه می‌کند. |
| [`insert_video_frame(self, index, x, y, width, height, fname)`](/slides/python-net/fa/aspose.slides/shapecollection/insert_video_frame/#int-float-float-float-float-str) | یک فریم ویدئویی جدید ایجاد می‌کند و در ایندکس مشخص به مجموعهٔ اشکال اضافه می‌کند. |
| [`add_audio_frame_cd(self, x, y, width, height)`](/slides/python-net/fa/aspose.slides/shapecollection/add_audio_frame_cd/#float-float-float-float) | یک فریم صوتی جدید که به تراک CD لینک دارد ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [`insert_audio_frame_cd(self, index, x, y, width, height)`](/slides/python-net/fa/aspose.slides/shapecollection/insert_audio_frame_cd/#int-float-float-float-float) | یک فریم صوتی جدید که به تراک CD لینک دارد ایجاد می‌کند و در ایندکس مشخص به مجموعهٔ اشکال<br/>            اضافه می‌کند. |
| [`add_audio_frame_linked(self, x, y, width, height, fname)`](/slides/python-net/fa/aspose.slides/shapecollection/add_audio_frame_linked/#float-float-float-float-str) | یک فریم صوتی جدید که به فایل صوتی خارجی لینک دارد ایجاد می‌کند و به انتهای<br/>            مجموعهٔ اشکال اضافه می‌کند. |
| [`insert_audio_frame_linked(self, index, x, y, width, height, fname)`](/slides/python-net/fa/aspose.slides/shapecollection/insert_audio_frame_linked/#int-float-float-float-float-str) | یک فریم صوتی جدید که به فایل صوتی خارجی لینک دارد ایجاد می‌کند و در ایندکس مشخص به مجموعهٔ اشکال<br/>            اضافه می‌کند. |
| [`index_of(self, shape)`](/slides/python-net/fa/aspose.slides/shapecollection/index_of/#ishape) | ایندکس صفر-پایهٔ اولین رخداد شکل مشخص‌شده در مجموعه را برمی‌گرداند. |
| [`add_math_shape(self, x, y, width, height)`](/slides/python-net/fa/aspose.slides/shapecollection/add_math_shape/#float-float-float-float) | یک شکل خودکار مستطیلی جدید برای میزبانی محتوای ریاضی ایجاد می‌کند و به<br/>            انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [`insert_group_shape(self, index)`](/slides/python-net/fa/aspose.slides/shapecollection/insert_group_shape/#int) | یک گروه شکل خالی جدید ایجاد می‌کند و در ایندکس مشخص به مجموعهٔ اشکال اضافه می‌کند.<br/>            چارچوب گروه به‌صورت خودکار برای جا دادن هر شکلی که به آن اضافه می‌شود تنظیم می‌شود. |
| [`add_picture_frame(self, shape_type, x, y, width, height, image)`](/slides/python-net/fa/aspose.slides/shapecollection/add_picture_frame/#shapetype-float-float-float-float-ippimage) | یک فریم تصویر جدید حاوی تصویر مشخص‌شده ایجاد می‌کند و به انتهای<br/>            مجموعهٔ اشکال اضافه می‌کند. |
| [`insert_picture_frame(self, index, shape_type, x, y, width, height, image)`](/slides/python-net/fa/aspose.slides/shapecollection/insert_picture_frame/#int-shapetype-float-float-float-float-ippimage) | یک فریم تصویر جدید حاوی تصویر مشخص‌شده ایجاد می‌کند و در ایندکس مشخص به مجموعهٔ<br/>            اشکال اضافه می‌کند. |
| [`add_table(self, x, y, column_widths, row_heights)`](/slides/python-net/fa/aspose.slides/shapecollection/add_table/#float-float-listfloat-listfloat) | یک جدول جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [`insert_table(self, index, x, y, column_widths, row_heights)`](/slides/python-net/fa/aspose.slides/shapecollection/insert_table/#int-float-float-listfloat-listfloat) | یک جدول جدید ایجاد می‌کند و در ایندکس مشخص به مجموعهٔ اشکال اضافه می‌کند. |
| [`remove_at(self, index)`](/slides/python-net/fa/aspose.slides/shapecollection/remove_at/#int) | شکل موجود در ایندکس مشخص را از مجموعهٔ اشکال حذف می‌کند. |
| [`remove(self, shape)`](/slides/python-net/fa/aspose.slides/shapecollection/remove/#ishape) | اولین رخداد شکل مشخص‌شده را از مجموعهٔ اشکال حذف می‌کند. |
| [`clear(self)`](/slides/python-net/fa/aspose.slides/shapecollection/clear/#) | تمام اشکال را از مجموعهٔ اشکال حذف می‌کند. |

### موارد مرتبط
* کلاس [`IShape`](/slides/python-net/fa/aspose.slides/ishape)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)