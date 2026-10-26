---
title: add_chart_from_workbook method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.importing/excelworkbookimporter/add_chart_from_workbook/
weight: 10
---
## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-int-bool}
یک نمودار را از کتاب کار اکسل مشخص‌شده بازیابی می‌کند و آن را در انتهای مجموعهٔ اشکال داده‌شده، در مختصات تعیین‌شده اضافه می‌نماید.

### بازگشت

نموداری که به مجموعهٔ اشکال اضافه شده است.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/fa/aspose.slides/ishapecollection) | مجموعهٔ اشکالی که نمودار به آن اضافه خواهد شد. |
| x | **float** | مختصات X برای قرار دادن نمودار. |
| y | **float** | مختصات Y برای قرار دادن نمودار. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/fa/aspose.slides.excel/iexceldataworkbook) | کتاب کار اکسل. |
| worksheet_name | **str** | نام صفحهٔ کاری که نمودار در آن قرار دارد. |
| chart_index | **int** | شاخص صفر-پایهٔ شکل نموداری که باید درج شود. <br/><br/>            این شاخص می‌تواند با استفاده از روش **Aspose.Slides.Excel.IExcelDataWorkbook.GetChartsFromWorksheet(Syste** به‌دست آید. |
| embed_all_workbook | **bool** | اگر `true` باشد، کل کتاب کار در نمودار جاسازی می‌شود؛ <br/><br/>            اگر `false` باشد، تنها داده‌های نمودار جاسازی می‌شوند. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | در صورتی که هر یک از پارامترهای ضروری None یا خالی باشد، یا نمودار در کتاب کار یافت نشود، این استثنا رخ می‌دهد. |


## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str-bool}
یک نمودار را از کتاب کار اکسل مشخص‌شده بازیابی می‌کند و آن را در انتهای مجموعهٔ اشکال داده‌شده، در مختصات تعیین‌شده اضافه می‌نماید.

### بازگشت

نموداری که به مجموعهٔ اشکال اضافه شده است.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/fa/aspose.slides/ishapecollection) | مجموعهٔ اشکالی که نمودار به آن اضافه خواهد شد. |
| x | **float** | مختصات X برای قرار دادن نمودار. |
| y | **float** | مختصات Y برای قرار دادن نمودار. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/fa/aspose.slides.excel/iexceldataworkbook) | کتاب کار اکسل. |
| worksheet_name | **str** | نام صفحهٔ کاری که نمودار در آن قرار دارد. |
| chart_name | **str** | نام نموداری که باید اضافه شود. |
| embed_all_workbook | **bool** | اگر `true` باشد، کل کتاب کار در نمودار جاسازی می‌شود؛ <br/><br/>            اگر `false` باشد، تنها داده‌های نمودار جاسازی می‌شوند. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | در صورتی که هر یک از پارامترهای ضروری None یا خالی باشد، یا نمودار در کتاب کار یافت نشود، این استثنا رخ می‌دهد. |


## add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-iorawiobase-str-str-bool}
یک نمودار را از کتاب کار اکسل مشخص‌شده بازیابی می‌کند و آن را در انتهای مجموعهٔ اشکال داده‌شده، در مختصات تعیین‌شده اضافه می‌نماید.

### بازگشت

نموداری که به مجموعهٔ اشکال اضافه شده است.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/fa/aspose.slides/ishapecollection) | مجموعهٔ اشکالی که نمودار به آن اضافه خواهد شد. |
| x | **float** | مختصات X برای قرار دادن نمودار. |
| y | **float** | مختصات Y برای قرار دادن نمودار. |
| workbook_stream | **io.RawIOBase** | جریانی که شامل داده‌های کتاب کار است. |
| worksheet_name | **str** | نام صفحهٔ کاری که نمودار در آن قرار دارد. |
| chart_name | **str** | نام نموداری که باید اضافه شود. |
| embed_all_workbook | **bool** | اگر `true` باشد، کل کتاب کار در نمودار جاسازی می‌شود؛ <br/><br/>            اگر `false` باشد، تنها داده‌های نمودار جاسازی می‌شوند. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | در صورتی که هر یک از پارامترهای ضروری None یا خالی باشد، یا نمودار در کتاب کار یافت نشود، این استثنا رخ می‌دهد. |
| **RuntimeError(Proxy error(InvalidOperationException))** | در صورتی که داده‌های ورودی در قالب پشتیبانی‌نشده‌ای باشند، این استثنا رخ می‌دهد. |


## add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook) {#ishapecollection-float-float-str-str-str-bool}
یک نمودار را از کتاب کار اکسل مشخص‌شده بازیابی می‌کند و آن را در انتهای مجموعهٔ اشکال داده‌شده، در مختصات تعیین‌شده اضافه می‌نماید.

### بازگشت

نموداری که به مجموعهٔ اشکال اضافه شده است.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/fa/aspose.slides/ishapecollection) | مجموعهٔ اشکالی که نمودار به آن اضافه خواهد شد. |
| x | **float** | مختصات X برای قرار دادن نمودار. |
| y | **float** | مختصات Y برای قرار دادن نمودار. |
| workbook_path | **str** | مسیر فایل کتاب کاری که شامل نمودار است. |
| worksheet_name | **str** | نام صفحهٔ کاری که نمودار در آن قرار دارد. |
| chart_name | **str** | نام نموداری که باید اضافه شود. |
| embed_workbook | **bool** | اگر `true` باشد، کتاب کار در نمودار جاسازی می‌شود؛ <br/><br/>            اگر `false` باشد، نمودار به کتاب کار خارجی لینک می‌شود. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | در صورتی که هر یک از پارامترهای ضروری None یا خالی باشد، یا نمودار در کتاب کار یافت نشود، این استثنا رخ می‌دهد. |
| **RuntimeError(Proxy error(IOException))** | هنگام دسترسی به فایل، خطای I/O رخ می‌دهد. |
| **RuntimeError(Proxy error(InvalidOperationException))** | در صورتی که داده‌های ورودی در قالب پشتیبانی‌نشده‌ای باشند، این استثنا رخ می‌دهد. |



### موارد مرتبط
* کلاس [`ExcelWorkbookImporter`](/slides/python-net/fa/aspose.slides.importing/excelworkbookimporter)
* کلاس [`IExcelDataWorkbook`](/slides/python-net/fa/aspose.slides.excel/iexceldataworkbook)
* کلاس [`IShapeCollection`](/slides/python-net/fa/aspose.slides/ishapecollection)
* ماژول [`aspose.slides.importing`](/slides/python-net/fa/aspose.slides.importing)
* کتابخانه [`Aspose.Slides`](/slides/python-net)