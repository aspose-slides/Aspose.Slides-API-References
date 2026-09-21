---
title: ISlideCollection class
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/islidecollection/
---
## کلاس ISlideCollection

نمایانگر مجموعه‌ای از اسلایدها است.

نوع ISlideCollection اعضای زیر را در اختیار می‌گذارد:

عنصری را که در ایندکس مشخص شده قرار دارد دریافت می‌کند. فقط خواندنی [`ISlide`](/slides/python-net/fa/aspose.slides/islide).

## ایندکس‌گذار

| نام | توضیح |
| :- | :- |
| [`[index]`](/slides/python-net/fa/aspose.slides/islidecollection/__getitem__/) |  |

## متدها

| متد | توضیح |
| :- | :- |
| [`add_clone(self, source_slide)`](/slides/python-net/fa/aspose.slides/islidecollection/add_clone/#islide) | یک کپی از اسلاید مشخص‌شده را به انتهای مجموعه اضافه می‌کند. |
| [`add_clone(self, source_slide, section)`](/slides/python-net/fa/aspose.slides/islidecollection/add_clone/#islide-isection) | یک کپی از اسلاید مشخص‌شده را به انتهای بخش مشخص‌شده اضافه می‌کند. |
| [`add_clone(self, source_slide, dest_layout)`](/slides/python-net/fa/aspose.slides/islidecollection/add_clone/#islide-ilayoutslide) | یک کپی از اسلاید مشخص‌شده را به انتهای مجموعه اضافه می‌کند. |
| [`add_clone(self, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/fa/aspose.slides/islidecollection/add_clone/#islide-imasterslide-bool) | یک کپی از اسلاید منبع مشخص‌شده را به انتهای مجموعه اضافه می‌کند.<br/>            طرح مناسب به‌صورت خودکار از master مشخص‌شده انتخاب خواهد شد (طرح مناسب همان طرحی است که Type یا Name مشابه طرح اسلاید منبع دارد). اگر طرح مناسب وجود نداشته باشد، طرح اسلاید منبع کلون می‌شود (اگر allowCloneMissingLayout true باشد) یا PptxEditException پرتاب می‌شود (اگر allowCloneMissingLayout false باشد). |
| [`insert_clone(self, index, source_slide)`](/slides/python-net/fa/aspose.slides/islidecollection/insert_clone/#int-islide) | یک کپی از اسلاید مشخص‌شده را در موقعیت مشخص‌شده مجموعه وارد می‌کند. |
| [`insert_clone(self, index, source_slide, dest_layout)`](/slides/python-net/fa/aspose.slides/islidecollection/insert_clone/#int-islide-ilayoutslide) | یک کپی از اسلاید مشخص‌شده را در موقعیت مشخص‌شده مجموعه وارد می‌کند. |
| [`insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/fa/aspose.slides/islidecollection/insert_clone/#int-islide-imasterslide-bool) | یک کپی از اسلاید منبع مشخص‌شده را در موقعیت مشخص‌شده مجموعه وارد می‌کند.<br/>            طرح مناسب به‌صورت خودکار از master مشخص‌شده انتخاب خواهد شد (طرح مناسب همان طرحی است که Type یا Name مشابه طرح اسلاید منبع دارد). اگر طرح مناسب وجود نداشته باشد، طرح اسلاید منبع کلون می‌شود (اگر allowCloneMissingLayout true باشد) یا PptxEditException پرتاب می‌شود (اگر allowCloneMissingLayout false باشد). |
| [`to_array(self)`](/slides/python-net/fa/aspose.slides/islidecollection/to_array/#) | یک آرایه شامل تمام اسلایدها ایجاد و بر می‌گرداند. |
| [`to_array(self, start_index, count)`](/slides/python-net/fa/aspose.slides/islidecollection/to_array/#int-int) | یک آرایه شامل تمام اسلایدهای بازهٔ مشخص‌شده ایجاد و بر می‌گرداند. |
| [`reorder(self, index, slide)`](/slides/python-net/fa/aspose.slides/islidecollection/reorder/#int-islide) | اسلاید را از مجموعه به موقعیت مشخص‌شده جابه‌جا می‌کند. |
| [`reorder(self, index, slides)`](/slides/python-net/fa/aspose.slides/islidecollection/reorder/#int-listislide) | اسلایدها را از مجموعه به موقعیت مشخص‌شده جابه‌جا می‌کند.<br/>            اسلایدها شروع از ایندکس به ترتیب ظهور در لیست قرار می‌گیرند. |
| [`add_from_pdf(self, path)`](/slides/python-net/fa/aspose.slides/islidecollection/add_from_pdf/#str) | اسلایدها را از سند PDF ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [`add_from_pdf(self, path, pdf_import_options)`](/slides/python-net/fa/aspose.slides/islidecollection/add_from_pdf/#str-asposeslidesimportingpdfimportoptions) | اسلایدها را از سند PDF ایجاد کرده و با در نظر گرفتن گزینه‌های واردات PDF به انتهای مجموعه اضافه می‌کند. |
| [`add_from_pdf(self, pdf_stream, pdf_import_options)`](/slides/python-net/fa/aspose.slides/islidecollection/add_from_pdf/#iorawiobase-asposeslidesimportingpdfimportoptions) | اسلایدها را از سند PDF ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [`add_from_pdf(self, pdf_stream)`](/slides/python-net/fa/aspose.slides/islidecollection/add_from_pdf/#iorawiobase) | اسلایدها را از سند PDF ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [`add_from_html(self, html_text, resolver, uri)`](/slides/python-net/fa/aspose.slides/islidecollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | اسلایدها را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [`add_from_html(self, html_text)`](/slides/python-net/fa/aspose.slides/islidecollection/add_from_html/#str) | اسلایدها را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [`add_from_html(self, html_stream, resolver, uri)`](/slides/python-net/fa/aspose.slides/islidecollection/add_from_html/#iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | اسلایدها را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [`add_from_html(self, html_stream)`](/slides/python-net/fa/aspose.slides/islidecollection/add_from_html/#iorawiobase) | اسلایدها را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [`insert_from_html(self, index, html_text, resolver, uri)`](/slides/python-net/fa/aspose.slides/islidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده به مجموعه وارد می‌کند. |
| [`insert_from_html(self, index, html_text)`](/slides/python-net/fa/aspose.slides/islidecollection/insert_from_html/#int-str) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده به مجموعه وارد می‌کند. |
| [`insert_from_html(self, index, html_stream, resolver, uri)`](/slides/python-net/fa/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده به مجموعه وارد می‌کند. |
| [`insert_from_html(self, index, html_stream)`](/slides/python-net/fa/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده به مجموعه وارد می‌کند. |
| [`insert_from_html(self, index, html_text, use_slide_with_index_as_start)`](/slides/python-net/fa/aspose.slides/islidecollection/insert_from_html/#int-str-bool) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده به مجموعه وارد می‌کند. |
| [`insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/fa/aspose.slides/islidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str-bool) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده به مجموعه وارد می‌کند. |
| [`insert_from_html(self, index, html_stream, use_slide_with_index_as_start)`](/slides/python-net/fa/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-bool) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده به مجموعه وارد می‌کند. |
| [`insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/fa/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده به مجموعه وارد می‌کند. |
| [`add_empty_slide(self, layout)`](/slides/python-net/fa/aspose.slides/islidecollection/add_empty_slide/#ilayoutslide) | یک اسلاید خالی جدید به انتهای مجموعه اضافه می‌کند. |
| [`insert_empty_slide(self, index, layout)`](/slides/python-net/fa/aspose.slides/islidecollection/insert_empty_slide/#int-ilayoutslide) | یک کپی از اسلاید مشخص‌شده را در موقعیت مشخص‌شده مجموعه وارد می‌کند. |
| [`remove(self, value)`](/slides/python-net/fa/aspose.slides/islidecollection/remove/#islide) | اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند. |
| [`remove_at(self, index)`](/slides/python-net/fa/aspose.slides/islidecollection/remove_at/#int) | عنصر موجود در ایندکس مشخص‌شده در مجموعه را حذف می‌کند. |
| [`index_of(self, slide)`](/slides/python-net/fa/aspose.slides/islidecollection/index_of/#islide) | یک ایندکس از اسلاید مشخص‌شده در مجموعه بر می‌گرداند. |


### همچنین ببینید
* کلاس [`ISlide`](/slides/python-net/fa/aspose.slides/islide)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)