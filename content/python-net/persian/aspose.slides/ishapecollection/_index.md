---
title: IShapeCollection class
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/ishapecollection/
---
## IShapeCollection کلاس

نمایش‌دهندهٔ مجموعه‌ای از اشکال است.

نوع IShapeCollection اعضای زیر را ارائه می‌دهد:

## خواص

| Property | Description |
| :- | :- |
| [`parent_group`](/slides/python-net/fa/aspose.slides/ishapecollection/parent_group/) | شیء گروه والد برای مجموعهٔ اشکال را دریافت می‌کند.<br/>            فقط‌خواندنی [`IGroupShape`](/slides/python-net/fa/aspose.slides/igroupshape). |

عنصر موجود در ایندکس مشخص را دریافت می‌کند.
            فقط‌خواندنی [`IShape`](/slides/python-net/fa/aspose.slides/ishape).

## ایندکس‌گر

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/fa/aspose.slides/ishapecollection/__getitem__/) |  |

## متدها

| Method | Description |
| :- | :- |
| [`add_chart(self, type, x, y, width, height)`](/slides/python-net/fa/aspose.slides/ishapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌ها و تنظیمات نمونه سری‌ها مقداردهی اولیه می‌کند و <br/>            آن را به انتهای مجموعهٔ اشکال اضافه می‌‎دارد. |
| [`add_chart(self, type, x, y, width, height, init_with_sample)`](/slides/python-net/fa/aspose.slides/ishapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float-bool) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌ها و تنظیمات نمونه سری‌ها مقداردهی اولیه می‌کند و <br/>            آن را به انتهای مجموعهٔ اشکال اضافه می‌‎دارد. |
| [`insert_chart(self, type, x, y, width, height, index)`](/slides/python-net/fa/aspose.slides/ishapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌ها و تنظیمات نمونه سری‌ها مقداردهی اولیه می‌کند و <br/>            آن را در ایندکس مشخص به مجموعهٔ اشکال وارد می‌کند. |
| [`insert_chart(self, type, x, y, width, height, index, init_with_sample)`](/slides/python-net/fa/aspose.slides/ishapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int-bool) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌ها و تنظیمات نمونه سری‌ها مقداردهی اولیه می‌کند و <br/>            آن را در ایندکس مشخص به مجموعهٔ اشکال وارد می‌کند. |
| [`add_ole_object_frame(self, x, y, width, height, data_info)`](/slides/python-net/fa/aspose.slides/ishapecollection/add_ole_object_frame/#float-float-float-float-ioleembeddeddatainfo) | یک فریم شیء OLE جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌‎دارد. |
| [`add_ole_object_frame(self, x, y, width, height, class_name, path)`](/slides/python-net/fa/aspose.slides/ishapecollection/add_ole_object_frame/#float-float-float-float-str-str) | یک فریم شیء OLE جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌‎دارد. |
| [`insert_ole_object_frame(self, index, x, y, width, height, data_info)`](/slides/python-net/fa/aspose.slides/ishapecollection/insert_ole_object_frame/#int-float-float-float-float-ioleembeddeddatainfo) | یک فریم شیء OLE جدید ایجاد می‌کند و آن را در ایندکس مشخص به مجموعهٔ اشکال وارد می‌کند. |
| [`insert_ole_object_frame(self, index, x, y, width, height, class_name, path)`](/slides/python-net/fa/aspose.slides/ishapecollection/insert_ole_object_frame/#int-float-float-float-float-str-str) | یک فریم شیء OLE جدید ایجاد می‌کند و آن را در ایندکس مشخص به مجموعهٔ اشکال وارد می‌کند. |
| [`add_zoom_frame(self, x, y, width, height, slide)`](/slides/python-net/fa/aspose.slides/ishapecollection/add_zoom_frame/#float-float-float-float-islide) | یک فریم زوم جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌‎دارد. |
| [`add_zoom_frame(self, x, y, width, height, slide, image)`](/slides/python-net/fa/aspose.slides/ishapecollection/add_zoom_frame/#float-float-float-float-islide-ippimage) | یک فریم زوم جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌‎دارد. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide)`](/slides/python-net/fa/aspose.slides/ishapecollection/insert_zoom_frame/#int-float-float-float-float-islide) | یک فریم زوم جدید ایجاد می‌کند و آن را به مجموعهٔ اشکال در ایندکس مشخص وارد می‌کند. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide, image)`](/slides/python-net/fa/aspose.slides/ishapecollection/insert_zoom_frame/#int-float-float-float-float-islide-ippimage) | یک فریم زوم جدید با تصویری از پیش تعریف شده ایجاد می‌کند و آن را به مجموعهٔ اشکال وارد می‌کند <br/>            در ایندکس مشخص. |
| [`add_section_zoom_frame(self, x, y, width, height, section)`](/slides/python-net/fa/aspose.slides/ishapecollection/add_section_zoom_frame/#float-float-float-float-isection) | یک فریم زوم بخش جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌‎دارد. |
| [`add_section_zoom_frame(self, x, y, width, height, section, image)`](/slides/python-net/fa/aspose.slides/ishapecollection/add_section_zoom_frame/#float-float-float-float-isection-ippimage) | یک فریم زوم بخش جدید با تصویری از پیش تعریف شده ایجاد می‌کند و به انتهای مجموعهٔ <br/>            اشکال اضافه می‌‎دارد. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section)`](/slides/python-net/fa/aspose.slides/ishapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection) | یک فریم زوم بخش جدید ایجاد می‌کند و آن را به مجموعهٔ اشکال <br/>            در ایندکس مشخص وارد می‌کند. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section, image)`](/slides/python-net/fa/aspose.slides/ishapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection-ippimage) | یک فریم زوم بخش جدید ایجاد می‌کند و آن را به مجموعهٔ اشکال <br/>            در ایندکس مشخص وارد می‌کند. |
| [`add_video_frame(self, x, y, width, height, fname)`](/slides/python-net/fa/aspose.slides/ishapecollection/add_video_frame/#float-float-float-float-str) | یک فریم ویدئویی جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌‎دارد. |
| [`add_video_frame(self, x, y, width, height, video)`](/slides/python-net/fa/aspose.slides/ishapecollection/add_video_frame/#float-float-float-float-ivideo) | یک فریم ویدئویی جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌‎دارد. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio_stream)`](/slides/python-net/fa/aspose.slides/ishapecollection/add_audio_frame_embedded/#float-float-float-float-iorawiobase) | یک فریم صوتی جدید با فایل WAV توکار ایجاد می‌کند و به انتهای مجموعهٔ اشکال <br/>            اضافه می‌‎دارد. صداهای توکار به مجموعه Presentation.Audios اضافه می‌شوند. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio)`](/slides/python-net/fa/aspose.slides/ishapecollection/add_audio_frame_embedded/#float-float-float-float-iaudio) | یک فریم صوتی جدید ایجاد می‌کند و با استفاده از یک شیء صوتی موجود از فهرست Presentation.Audios به انتهای مجموعهٔ اشکال <br/>            اضافه می‌‎دارد. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream)`](/slides/python-net/fa/aspose.slides/ishapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iorawiobase) | یک فریم صوتی جدید با فایل WAV توکار ایجاد می‌کند و آن را به مجموعهٔ اشکال <br/>            در ایندکس مشخص وارد می‌کند. صداهای توکار به مجموعه Presentation.Audios <br/>            اضافه می‌شوند. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio)`](/slides/python-net/fa/aspose.slides/ishapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iaudio) | یک فریم صوتی جدید ایجاد می‌کند و آن را به مجموعهٔ اشکال در ایندکس مشخص وارد می‌کند <br/>            با استفاده از یک شیء صوتی موجود از فهرست Presentation.Audios. |
| [`to_array(self)`](/slides/python-net/fa/aspose.slides/ishapecollection/to_array/#) | یک آرایه حاوی تمام اشکال را ایجاد و بر می‌گرداند. |
| [`to_array(self, start_index, count)`](/slides/python-net/fa/aspose.slides/ishapecollection/to_array/#int-int) | آرایه‌ای شامل تمام اشکال در محدودهٔ مشخص شده ایجاد و بر می‌گرداند. |
| [`reorder(self, index, shape)`](/slides/python-net/fa/aspose.slides/ishapecollection/reorder/#int-ishape) | شیء مشخص شده را به موقعیتی جدید در داخل مجموعهٔ اشکال جابجا می‌کند. |
| [`reorder(self, index, shapes)`](/slides/python-net/fa/aspose.slides/ishapecollection/reorder/#int-listishape) | اشکال مشخص شده را در داخل مجموعهٔ اشکال جابجا می‌کند و آنها را از ایندکس داده‌شده شروع می‌کند. |
| [`add_auto_shape(self, shape_type, x, y, width, height)`](/slides/python-net/fa/aspose.slides/ishapecollection/add_auto_shape/#shapetype-float-float-float-float) | یک شکل خودکار جدید با قالب‌بندی پیش‌فرض ایجاد می‌کند و به انتهای مجموعهٔ اشکال <br/>            اضافه می‌‎دارد. |
| [`add_auto_shape(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/fa/aspose.slides/ishapecollection/add_auto_shape/#shapetype-float-float-float-float-bool) | یک شکل خودکار جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌‎دارد، در صورت تمایل آن را با قالب‌بندی پیش‌فرض الگو مقداردهی اولیه می‌کند. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height)`](/slides/python-net/fa/aspose.slides/ishapecollection/insert_auto_shape/#int-shapetype-float-float-float-float) | یک شکل خودکار جدید ایجاد می‌کند و آن را به مجموعهٔ اشکال در ایندکس مشخص وارد می‌کند، <br/>            قالب‌بندی پیش‌فرض الگو را اعمال می‌کند. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/fa/aspose.slides/ishapecollection/insert_auto_shape/#int-shapetype-float-float-float-float-bool) | یک شکل خودکار جدید ایجاد می‌کند و آن را به مجموعهٔ اشکال در ایندکس مشخص وارد می‌کند، <br/>            در صورت تمایل با استایل پیش‌فرض الگو مقداردهی اولیه می‌کند. |
| [`add_group_shape(self)`](/slides/python-net/fa/aspose.slides/ishapecollection/add_group_shape/#) | یک گروه شکل خالی جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌‎دارد.<br/>            چارچوب گروه به‌صورت خودکار برای جاگیری هر شکلی که به آن اضافه شود، تنظیم می‌شود. |
| [`add_group_shape(self, svg_image, x, y, width, height)`](/slides/python-net/fa/aspose.slides/ishapecollection/add_group_shape/#isvgimage-float-float-float-float) | یک گروه شکل جدید ایجاد می‌کند، تصویر SVG مشخص‌شده را به اشکال جداگانه تبدیل می‌کند،<br/>            و گروه حاصل را به انتهای مجموعهٔ اشکال اضافه می‌‎دارد. |
| [`add_connector(self, shape_type, x, y, width, height)`](/slides/python-net/fa/aspose.slides/ishapecollection/add_connector/#shapetype-float-float-float-float) | یک شکل اتصال جدید با استایل پیش‌فرض الگو ایجاد می‌کند و به انتهای مجموعهٔ اشکال <br/>            اضافه می‌‎داند. |
| [`add_connector(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/fa/aspose.slides/ishapecollection/add_connector/#shapetype-float-float-float-float-bool) | یک شکل اتصال جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌‎دارد،<br/>            در صورت تمایل استایل پیش‌فرض الگو را اعمال می‌کند. |
| [`insert_connector(self, index, shape_type, x, y, width, height)`](/slides/python-net/fa/aspose.slides/ishapecollection/insert_connector/#int-shapetype-float-float-float-float) | یک شکل اتصال جدید ایجاد می‌کند و آن را به مجموعهٔ اشکال در ایندکس مشخص وارد می‌کند،<br/>            استایل پیش‌فرض الگو را اعمال می‌کند. |
| [`insert_connector(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/fa/aspose.slides/ishapecollection/insert_connector/#int-shapetype-float-float-float-float-bool) | یک شکل اتصال جدید ایجاد می‌کند و آن را به مجموعهٔ اشکال در ایندکس مشخص وارد می‌کند،<br/>            در صورت تمایل استایل پیش‌فرض الگو را اعمال می‌کند. |
| [`add_clone(self, source_shape, x, y, width, height)`](/slides/python-net/fa/aspose.slides/ishapecollection/add_clone/#ishape-float-float-float-float) | یک کپی از شکل مشخص‌شده ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌‎دارد. |
| [`add_clone(self, source_shape, x, y)`](/slides/python-net/fa/aspose.slides/ishapecollection/add_clone/#ishape-float-float) | یک کپی از شکل مشخص‌شده ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌‎دارد.<br/>            شکل جدید عرض و ارتفاع `source_shape` را حفظ می‌کند. |
| [`add_clone(self, source_shape)`](/slides/python-net/fa/aspose.slides/ishapecollection/add_clone/#ishape) | یک کپی از شکل مشخص‌شده ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌‎دارد.<br/>            شکل کلون شده موقعیت و اندازهٔ اصلی را حفظ می‌کند. |
| [`insert_clone(self, index, source_shape, x, y, width, height)`](/slides/python-net/fa/aspose.slides/ishapecollection/insert_clone/#int-ishape-float-float-float-float) | یک کپی از شکل مشخص‌شده ایجاد می‌کند و آن را به مجموعهٔ اشکال در ایندکس مشخص وارد می‌کند. |
| [`insert_clone(self, index, source_shape, x, y)`](/slides/python-net/fa/aspose.slides/ishapecollection/insert_clone/#int-ishape-float-float) | یک کپی از شکل مشخص‌شده ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌‎دارد.<br/>            شکل جدید عرض و ارتفاع `source_shape` را حفظ می‌کند. |
| [`insert_clone(self, index, source_shape)`](/slides/python-net/fa/aspose.slides/ishapecollection/insert_clone/#int-ishape) | یک کپی از شکل مشخص‌شده ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌‎دارد.<br/>            شکل کلون شده موقعیت و اندازهٔ اصلی را حفظ می‌کند. |
| [`add_smart_art(self, x, y, width, height, layout_type)`](/slides/python-net/fa/aspose.slides/ishapecollection/add_smart_art/#float-float-float-float-asposeslidessmartartsmartartlayouttype) | یک نمودار SmartArt ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌‎دارد. |
| [`add_summary_zoom_frame(self, x, y, width, height)`](/slides/python-net/fa/aspose.slides/ishapecollection/add_summary_zoom_frame/#float-float-float-float) | یک فریم خلاصه زوم جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌‎دارد. |
| [`insert_summary_zoom_frame(self, index, x, y, width, height)`](/slides/python-net/fa/aspose.slides/ishapecollection/insert_summary_zoom_frame/#int-float-float-float-float) | یک فریم خلاصه زوم جدید ایجاد می‌کند و آن را به مجموعهٔ اشکال در ایندکس مشخص وارد می‌کند. |
| [`insert_video_frame(self, index, x, y, width, height, fname)`](/slides/python-net/fa/aspose.slides/ishapecollection/insert_video_frame/#int-float-float-float-float-str) | یک فریم ویدئویی جدید ایجاد می‌کند و آن را به مجموعهٔ اشکال در ایندکس مشخص وارد می‌کند. |
| [`add_audio_frame_cd(self, x, y, width, height)`](/slides/python-net/fa/aspose.slides/ishapecollection/add_audio_frame_cd/#float-float-float-float) | یک فریم صوتی جدید مرتبط با یک ردیف CD ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌‎دارد. |
| [`insert_audio_frame_cd(self, index, x, y, width, height)`](/slides/python-net/fa/aspose.slides/ishapecollection/insert_audio_frame_cd/#int-float-float-float-float) | یک فریم صوتی جدید مرتبط با یک ردیف CD ایجاد می‌کند و آن را به مجموعهٔ اشکال <br/>            در ایندکس مشخص وارد می‌کند. |
| [`add_audio_frame_linked(self, x, y, width, height, fname)`](/slides/python-net/fa/aspose.slides/ishapecollection/add_audio_frame_linked/#float-float-float-float-str) | یک فریم صوتی جدید مرتبط با یک فایل صوتی خارجی ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌‎دارد. |
| [`insert_audio_frame_linked(self, index, x, y, width, height, fname)`](/slides/python-net/fa/aspose.slides/ishapecollection/insert_audio_frame_linked/#int-float-float-float-float-str) | یک فریم صوتی جدید مرتبط با یک فایل صوتی خارجی ایجاد می‌کند و آن را به مجموعهٔ اشکال <br/>            در ایندکس مشخص وارد می‌کند. |
| [`index_of(self, shape)`](/slides/python-net/fa/aspose.slides/ishapecollection/index_of/#ishape) | اندیس صفر-مبنای اولین رخداد شکل مشخص‌شده در مجموعه را بر می‌گرداند. |
| [`add_math_shape(self, x, y, width, height)`](/slides/python-net/fa/aspose.slides/ishapecollection/add_math_shape/#float-float-float-float) | یک شکل خودکار مستطیلی جدید برای میزبانی محتوای ریاضی ایجاد می‌کند و به انتهای مجموعهٔ اشکال <br/>            اضافه می‌‎دارد. |
| [`insert_group_shape(self, index)`](/slides/python-net/fa/aspose.slides/ishapecollection/insert_group_shape/#int) | یک گروه شکل خالی جدید ایجاد می‌کند و آن را به مجموعهٔ اشکال در ایندکس مشخص وارد می‌کند.<br/>            چارچوب گروه به‌صورت خودکار برای جاگیری هر شکلی که به آن اضافه شود، تنظیم می‌شود. |
| [`add_picture_frame(self, shape_type, x, y, width, height, image)`](/slides/python-net/fa/aspose.slides/ishapecollection/add_picture_frame/#shapetype-float-float-float-float-ippimage) | یک فریم تصویر جدید حاوی تصویر مشخص‌شده ایجاد می‌کند و به انتهای مجموعهٔ اشکال <br/>            اضافه می‌‎دارد. |
| [`insert_picture_frame(self, index, shape_type, x, y, width, height, image)`](/slides/python-net/fa/aspose.slides/ishapecollection/insert_picture_frame/#int-shapetype-float-float-float-float-ippimage) | یک فریم تصویر جدید حاوی تصویر مشخص‌شده ایجاد می‌کند و آن را به مجموعهٔ <br/>            اشکال در ایندکس مشخص وارد می‌کند. |
| [`add_table(self, x, y, column_widths, row_heights)`](/slides/python-net/fa/aspose.slides/ishapecollection/add_table/#float-float-listfloat-listfloat) | یک جدول جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌‎دارد. |
| [`insert_table(self, index, x, y, column_widths, row_heights)`](/slides/python-net/fa/aspose.slides/ishapecollection/insert_table/#int-float-float-listfloat-listfloat) | یک جدول جدید ایجاد می‌کند و آن را به مجموعهٔ اشکال در ایندکس مشخص وارد می‌کند. |
| [`remove_at(self, index)`](/slides/python-net/fa/aspose.slides/ishapecollection/remove_at/#int) | شکل موجود در ایندکس مشخص را از مجموعهٔ اشکال حذف می‌کند. |
| [`remove(self, shape)`](/slides/python-net/fa/aspose.slides/ishapecollection/remove/#ishape) | اولین رخداد شکل مشخص‌شده را از مجموعهٔ اشکال حذف می‌کند. |
| [`clear(self)`](/slides/python-net/fa/aspose.slides/ishapecollection/clear/#) | تمام اشکال را از مجموعهٔ اشکال حذف می‌کند. |


### موارد مرتبط
* کلاس [`IShape`](/slides/python-net/fa/aspose.slides/ishape)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)