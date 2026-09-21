---
title: add_table_from_workbook method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.importing/excelworkbookimporter/add_table_from_workbook/
weight: 20
---
## add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str}
یک جدول را از کتاب‌کار Excel مشخص‌شده بازیابی می‌کند و آن را در انتهای مجموعهٔ اشکال داده‌شده در مختصات تعیین‌شده اضافه می‌نماید.

### بازگرداندن

جدولی که به مجموعهٔ اشکال اضافه شده است.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/fa/aspose.slides/ishapecollection) | مجموعهٔ اشکالی که جدول به آن اضافه خواهد شد. |
| x | **float** | مختصات X برای موقعیت‌دهی جدول. |
| y | **float** | مختصات Y برای موقعیت‌دهی جدول. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/fa/aspose.slides.excel/iexceldataworkbook) | کتاب‌کار Excel. |
| worksheet_name | **str** | نام برگه‌کاری که جدول را در بر دارد. |
| cell_range | **str** | بازهٔ سلولی که جدول را تعریف می‌کند (به عنوان مثال، "A1:D10"). |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | زمانی پرتاب می‌شود که هر یک از پارامترهای ضروری مقدار None یا خالی داشته باشد، یا وقتی برگه‌کار یا بازهٔ سلول مشخص‌شده نامعتبر باشد. |
| **RuntimeError(Proxy error(InvalidOperationException))** | زمانی پرتاب می‌شود که داده‌های ورودی در قالب پشتیبانی‌نشده‌ای باشند. |


## add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range) {#ishapecollection-float-float-str-str-str}
یک جدول را از فایل کتاب‌کار Excel مشخص‌شده بازیابی می‌کند و آن را در انتهای مجموعهٔ اشکال داده‌شده در مختصات تعیین‌شده اضافه می‌نماید.

### بازگرداندن

جدولی که به مجموعهٔ اشکال اضافه شده است.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/fa/aspose.slides/ishapecollection) | مجموعهٔ اشکالی که جدول به آن اضافه خواهد شد. |
| x | **float** | مختصات X برای موقعیت‌دهی جدول. |
| y | **float** | مختصات Y برای موقعیت‌دهی جدول. |
| workbook_path | **str** | مسیر به فایل کتاب‌کار Excel. |
| worksheet_name | **str** | نام برگه‌کاری که جدول را در بر دارد. |
| cell_range | **str** | بازهٔ سلولی که جدول را تعریف می‌کند (به عنوان مثال، "A1:D10"). |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | زمانی پرتاب می‌شود که هر یک از پارامترهای ضروری مقدار None یا خالی داشته باشد، یا وقتی برگه‌کار یا بازهٔ سلول مشخص‌شده نامعتبر باشد. |
| **RuntimeError(Proxy error(IOException))** | زمانی پرتاب می‌شود که هنگام دسترسی به فایل کتاب‌کار خطای ورودی/خروجی رخ دهد. |
| **RuntimeError(Proxy error(InvalidOperationException))** | زمانی پرتاب می‌شود که داده‌های ورودی در قالب پشتیبانی‌نشده‌ای باشند. |


## add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range) {#ishapecollection-float-float-iorawiobase-str-str}
یک جدول را از فایل کتاب‌کار Excel مشخص‌شده بازیابی می‌کند و آن را در انتهای مجموعهٔ اشکال داده‌شده در مختصات تعیین‌شده اضافه می‌نماید.

### بازگرداندن

جدولی که به مجموعهٔ اشکال اضافه شده است.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/fa/aspose.slides/ishapecollection) | مجموعهٔ اشکالی که جدول به آن اضافه خواهد شد. |
| x | **float** | مختصات X برای موقعیت‌دهی جدول. |
| y | **float** | مختصات Y برای موقعیت‌دهی جدول. |
| workbook_stream | **io.RawIOBase** | یک جریان حاوی داده‌های کتاب‌کار. |
| worksheet_name | **str** | نام برگه‌کاری که جدول را در بر دارد. |
| cell_range | **str** | بازهٔ سلولی که جدول را تعریف می‌کند (به عنوان مثال، "A1:D10"). |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | زمانی پرتاب می‌شود که هر یک از پارامترهای ضروری مقدار None یا خالی داشته باشد، یا وقتی برگه‌کار یا بازهٔ سلول مشخص‌شده نامعتبر باشد. |
| **RuntimeError(Proxy error(InvalidOperationException))** | زمانی پرتاب می‌شود که داده‌های ورودی در قالب پشتیبانی‌نشده‌ای باشند. |



### موارد مرتبط
* کلاس [`ExcelWorkbookImporter`](/slides/python-net/fa/aspose.slides.importing/excelworkbookimporter)
* کلاس [`IExcelDataWorkbook`](/slides/python-net/fa/aspose.slides.excel/iexceldataworkbook)
* کلاس [`IShapeCollection`](/slides/python-net/fa/aspose.slides/ishapecollection)
* کلاس [`ITable`](/slides/python-net/fa/aspose.slides/itable)
* ماژول [`aspose.slides.importing`](/slides/python-net/fa/aspose.slides.importing)
* کتابخانه [`Aspose.Slides`](/slides/python-net)