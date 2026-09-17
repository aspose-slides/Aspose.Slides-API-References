---
title: add_table_from_workbook method
second_title: مرجع API Aspose.Slides للغة Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides.importing/excelworkbookimporter/add_table_from_workbook/
weight: 20
---
## add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str}
يجلب جدولًا من دفتر عمل Excel المحدد ويضيفه إلى نهاية مجموعة الأشكال المعطاة عند الإحداثيات المحددة.

### القيمة المرجعة

الجدول الذي تم إضافته إلى مجموعة الأشكال.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range):
    ...
```


| معلمة | نوع | وصف |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/ar/aspose.slides/ishapecollection) | مجموعة الأشكال التي سيُضاف إليها الجدول. |
| x | **float** | إحداثي X لتحديد موقع الجدول. |
| y | **float** | إحداثي Y لتحديد موقع الجدول. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/ar/aspose.slides.excel/iexceldataworkbook) | دفتر عمل Excel. |
| worksheet_name | **str** | اسم ورقة العمل التي تحتوي على الجدول. |
| cell_range | **str** | نطاق الخلايا الذي يحدد الجدول (مثال: "A1:D10"). |

### الاستثناءات

| استثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | يُرمى عندما يكون أي معلم مطلوب None أو فارغ، أو عندما تكون ورقة العمل أو نطاق الخلايا المحدد غير صالح. |
| **RuntimeError(Proxy error(InvalidOperationException))** | يُرمى عندما تكون البيانات المدخلة بتنسيق غير مدعوم. |


## add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range) {#ishapecollection-float-float-str-str-str}
يجلب جدولًا من ملف دفتر عمل Excel المحدد ويضيفه إلى نهاية مجموعة الأشكال المعطاة عند الإحداثيات المحددة.

### القيمة المرجعة

الجدول الذي تم إضافته إلى مجموعة الأشكال.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range):
    ...
```


| معلمة | نوع | وصف |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/ar/aspose.slides/ishapecollection) | مجموعة الأشكال التي سيُضاف إليها الجدول. |
| x | **float** | إحداثي X لتحديد موقع الجدول. |
| y | **float** | إحداثي Y لتحديد موقع الجدول. |
| workbook_path | **str** | المسار إلى ملف دفتر عمل Excel. |
| worksheet_name | **str** | اسم ورقة العمل التي تحتوي على الجدول. |
| cell_range | **str** | نطاق الخلايا الذي يحدد الجدول (مثال: "A1:D10"). |

### الاستثناءات

| استثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | يُرمى عندما يكون أي معلم مطلوب None أو فارغ، أو عندما تكون ورقة العمل أو نطاق الخلايا المحدد غير صالح. |
| **RuntimeError(Proxy error(IOException))** | يُرمى عندما يحدث خطأ إدخال/إخراج أثناء الوصول إلى ملف دفتر العمل. |
| **RuntimeError(Proxy error(InvalidOperationException))** | يُرمى عندما تكون البيانات المدخلة بتنسيق غير مدعوم. |


## add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range) {#ishapecollection-float-float-iorawiobase-str-str}
يجلب جدولًا من ملف دفتر عمل Excel المحدد ويضيفه إلى نهاية مجموعة الأشكال المعطاة عند الإحداثيات المحددة.

### القيمة المرجعة

الجدول الذي تم إضافته إلى مجموعة الأشكال.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range):
    ...
```


| معلمة | نوع | وصف |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/ar/aspose.slides/ishapecollection) | مجموعة الأشكال التي سيُضاف إليها الجدول. |
| x | **float** | إحداثي X لتحديد موقع الجدول. |
| y | **float** | إحداثي Y لتحديد موقع الجدول. |
| workbook_stream | **io.RawIOBase** | دفق يحتوي على بيانات دفتر العمل. |
| worksheet_name | **str** | اسم ورقة العمل التي تحتوي على الجدول. |
| cell_range | **str** | نطاق الخلايا الذي يحدد الجدول (مثال: "A1:D10"). |

### الاستثناءات

| استثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | يُرمى عندما يكون أي معلم مطلوب None أو فارغ، أو عندما تكون ورقة العمل أو نطاق الخلايا المحدد غير صالح. |
| **RuntimeError(Proxy error(InvalidOperationException))** | يُرمى عندما تكون البيانات المدخلة بتنسيق غير مدعوم. |



### انظر أيضًا
* الفئة [`ExcelWorkbookImporter`](/slides/python-net/ar/aspose.slides.importing/excelworkbookimporter)
* الفئة [`IExcelDataWorkbook`](/slides/python-net/ar/aspose.slides.excel/iexceldataworkbook)
* الفئة [`IShapeCollection`](/slides/python-net/ar/aspose.slides/ishapecollection)
* الفئة [`ITable`](/slides/python-net/ar/aspose.slides/itable)
* الوحدة [`aspose.slides.importing`](/slides/python-net/ar/aspose.slides.importing)
* المكتبة [`Aspose.Slides`](/slides/python-net)