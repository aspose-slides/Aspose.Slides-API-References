---
title: SlideCollection class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/slidecollection/
---
## SlideCollection کلاس

نمایش‌دهندهٔ مجموعه‌ای از اسلایدها.

نوع SlideCollection اعضای زیر را عرضه می‌کند:

عنصری را که در ایندکس مشخص شده است برمی‌گرداند.  
خواندنی-تنها [`Slide`](/slides/python-net/fa/aspose.slides/slide).

## Indexer

| نام | توضیح |
| :- | :- |
| [`[index]`](/slides/python-net/fa/aspose.slides/slidecollection/__getitem__/) |  |

## Methods

| متد | توضیح |
| :- | :- |
| [`add_clone(self, source_slide)`](/slides/python-net/fa/aspose.slides/slidecollection/add_clone/#islide) | یک کپی از اسلاید مشخص‌شده را به انتهای مجموعه اضافه می‌کند. |
| [`add_clone(self, source_slide, section)`](/slides/python-net/fa/aspose.slides/slidecollection/add_clone/#islide-isection) | یک کپی از اسلاید مشخص‌شده را به انتهای بخش مشخص‌شده اضافه می‌کند. |
| [`add_clone(self, source_slide, dest_layout)`](/slides/python-net/fa/aspose.slides/slidecollection/add_clone/#islide-ilayoutslide) | یک کپی از اسلاید مشخص‌شده را به انتهای مجموعه اضافه می‌کند. |
| [`add_clone(self, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/fa/aspose.slides/slidecollection/add_clone/#islide-imasterslide-bool) | یک کپی از اسلاید منبع مشخص‌شده را به انتهای مجموعه اضافه می‌کند.<br/>            طرح مناسب به‌صورت خودکار از مستر مشخص‌شده انتخاب می‌شود (طرح مناسب، طرحی با همان Type یا Name است که در طرح اسلاید منبع وجود دارد). اگر طرح مناسبی وجود نداشته باشد، طرح اسلاید منبع کلون می‌شود (اگر allowCloneMissingLayout درست باشد) یا PptxEditException پرتاب می‌شود (اگر allowCloneMissingLayout نادرست باشد). |
| [`insert_clone(self, index, source_slide)`](/slides/python-net/fa/aspose.slides/slidecollection/insert_clone/#int-islide) | یک کپی از اسلاید مشخص‌شده را در موقعیت مشخص‌شده‌ی مجموعه درج می‌کند. |
| [`insert_clone(self, index, source_slide, dest_layout)`](/slides/python-net/fa/aspose.slides/slidecollection/insert_clone/#int-islide-ilayoutslide) | یک کپی از اسلاید مشخص‌شده را در موقعیت مشخص‌شده‌ی مجموعه درج می‌کند. |
| [`insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/fa/aspose.slides/slidecollection/insert_clone/#int-islide-imasterslide-bool) | یک کپی از اسلاید منبع مشخص‌شده را در موقعیت مشخص‌شده‌ی مجموعه درج می‌کند.<br/>            طرح مناسب به‌صورت خودکار از مستر مشخص‌شده انتخاب می‌شود (طرح مناسب، طرحی با همان Type یا Name است که در طرح اسلاید منبع وجود دارد). اگر طرح مناسبی وجود نداشته باشد، طرح اسلاید منبع کلون می‌شود (اگر allowCloneMissingLayout درست باشد) یا PptxEditException پرتاب می‌شود (اگر allowCloneMissingLayout نادرست باشد). |
| [`to_array(self)`](/slides/python-net/fa/aspose.slides/slidecollection/to_array/#) | آرایه‌ای حاوی تمام اسلایدها ایجاد و برمی‌گرداند. |
| [`to_array(self, start_index, count)`](/slides/python-net/fa/aspose.slides/slidecollection/to_array/#int-int) | آرایه‌ای حاوی تمام اسلایدهای بازهٔ مشخص‌شده ایجاد و برمی‌گرداند.<br/>            ایندکس اولین اسلاید برای افزودن. تعداد اسلایدهای برای افزودن. |
| [`reorder(self, index, slide)`](/slides/python-net/fa/aspose.slides/slidecollection/reorder/#int-islide) | اسلاید را از مجموعه به موقعیت مشخص‌شده حرکت می‌دهد. |
| [`reorder(self, index, slides)`](/slides/python-net/fa/aspose.slides/slidecollection/reorder/#int-listislide) | اسلایدها را از مجموعه به موقعیت مشخص‌شده حرکت می‌دهد.<br/>            اسلایدها از ایندکس شروع شده به ترتیب ظاهر شدن در لیست قرار می‌گیرند. |
| [`add_from_pdf(self, path)`](/slides/python-net/fa/aspose.slides/slidecollection/add_from_pdf/#str) | اسلایدها را از سند PDF ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [`add_from_pdf(self, path, pdf_import_options)`](/slides/python-net/fa/aspose.slides/slidecollection/add_from_pdf/#str-asposeslidesimportingpdfimportoptions) | اسلایدها را از سند PDF ایجاد کرده و با در نظر گرفتن گزینه‌های واردات PDF به انتهای مجموعه اضافه می‌کند. |
| [`add_from_pdf(self, pdf_stream)`](/slides/python-net/fa/aspose.slides/slidecollection/add_from_pdf/#iorawiobase) | اسلایدها را از سند PDF ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [`add_from_pdf(self, pdf_stream, pdf_import_options)`](/slides/python-net/fa/aspose.slides/slidecollection/add_from_pdf/#iorawiobase-asposeslidesimportingpdfimportoptions) | اسلایدها را از سند PDF ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [`add_from_html(self, html_text, resolver, uri)`](/slides/python-net/fa/aspose.slides/slidecollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | اسلایدها را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [`add_from_html(self, html_text)`](/slides/python-net/fa/aspose.slides/slidecollection/add_from_html/#str) | اسلایدها را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [`add_from_html(self, html_stream, resolver, uri)`](/slides/python-net/fa/aspose.slides/slidecollection/add_from_html/#iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | اسلایدها را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [`add_from_html(self, html_stream)`](/slides/python-net/fa/aspose.slides/slidecollection/add_from_html/#iorawiobase) | اسلایدها را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [`insert_from_html(self, index, html_text, resolver, uri)`](/slides/python-net/fa/aspose.slides/slidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده به مجموعه وارد می‌کند. |
| [`insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/fa/aspose.slides/slidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str-bool) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده به مجموعه وارد می‌کند. |
| [`insert_from_html(self, index, html_text)`](/slides/python-net/fa/aspose.slides/slidecollection/insert_from_html/#int-str) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده به مجموعه وارد می‌کند. |
| [`insert_from_html(self, index, html_text, use_slide_with_index_as_start)`](/slides/python-net/fa/aspose.slides/slidecollection/insert_from_html/#int-str-bool) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده به مجموعه وارد می‌کند. |
| [`insert_from_html(self, index, html_stream, resolver, uri)`](/slides/python-net/fa/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده به مجموعه وارد می‌کند. |
| [`insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/fa/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده به مجموعه وارد می‌کند. |
| [`insert_from_html(self, index, html_stream)`](/slides/python-net/fa/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده به مجموعه وارد می‌کند. |
| [`insert_from_html(self, index, html_stream, use_slide_with_index_as_start)`](/slides/python-net/fa/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-bool) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده به مجموعه وارد می‌کند. |
| [`add_empty_slide(self, layout)`](/slides/python-net/fa/aspose.slides/slidecollection/add_empty_slide/#ilayoutslide) | یک اسلاید خالی جدید به انتهای مجموعه اضافه می‌کند. |
| [`insert_empty_slide(self, index, layout)`](/slides/python-net/fa/aspose.slides/slidecollection/insert_empty_slide/#int-ilayoutslide) | یک کپی از اسلاید مشخص‌شده را در موقعیت مشخص‌شده‌ی مجموعه درج می‌کند. |
| [`remove(self, value)`](/slides/python-net/fa/aspose.slides/slidecollection/remove/#islide) | اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند. |
| [`remove_at(self, index)`](/slides/python-net/fa/aspose.slides/slidecollection/remove_at/#int) | عنصر موجود در ایندکس مشخص‌شده‌ی مجموعه را حذف می‌کند. |
| [`index_of(self, slide)`](/slides/python-net/fa/aspose.slides/slidecollection/index_of/#islide) | ایندکس اسلاید مشخص‌شده در مجموعه را باز می‌گرداند. |

### موارد مرتبط
* کلاس [`Slide`](/slides/python-net/fa/aspose.slides/slide)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)