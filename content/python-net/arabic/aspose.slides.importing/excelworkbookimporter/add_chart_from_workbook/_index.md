---
title: add_chart_from_workbook method
second_title: Aspose.Slides للغة Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.importing/excelworkbookimporter/add_chart_from_workbook/
weight: 10
---
## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-int-bool}
يستخرج مخططًا من دفتر عمل Excel المحدد ويضيفه إلى نهاية مجموعة الأشكال المعطاة عند الإحداثيات المحددة.

### Returns

المخطط الذي تم إضافته إلى مجموعة الأشكال.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/ar/aspose.slides/ishapecollection) | مجموعة الأشكال التي سيُضاف إليها المخطط. |
| x | **float** | إحداثي X لتحديد موقع المخطط. |
| y | **float** | إحداثي Y لتحديد موقع المخطط. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/ar/aspose.slides.excel/iexceldataworkbook) | دفتر عمل Excel. |
| worksheet_name | **str** | اسم ورقة العمل التي تحتوي على المخطط. |
| chart_index | **int** | الفهرس الصفري للمخطط الذي سيتم إدراجه. <br/><br/>            يمكن الحصول على هذا الفهرس باستخدام طريقة **Aspose.Slides.Excel.IExcelDataWorkbook.GetChartsFromWorksheet(Syste**. |
| embed_all_workbook | **bool** | إذا كان `true`، سيتم تضمين دفتر العمل بالكامل في المخطط؛ <br/><br/>            إذا كان `false`، سيتم تضمين بيانات المخطط فقط. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | يُلقى عندما يكون أي معامل مطلوب بقيمة None أو فارغًا، أو إذا لم يتم العثور على المخطط في دفتر العمل. |


## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str-bool}
يستخرج مخططًا من دفتر عمل Excel المحدد ويضيفه إلى نهاية مجموعة الأشكال المعطاة عند الإحداثيات المحددة.

### Returns

المخطط الذي تم إضافته إلى مجموعة الأشكال.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/ar/aspose.slides/ishapecollection) | مجموعة الأشكال التي سيُضاف إليها المخطط. |
| x | **float** | إحداثي X لتحديد موقع المخطط. |
| y | **float** | إحداثي Y لتحديد موقع المخطط. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/ar/aspose.slides.excel/iexceldataworkbook) | دفتر عمل Excel. |
| worksheet_name | **str** | اسم ورقة العمل التي تحتوي على المخطط. |
| chart_name | **str** | اسم المخطط الذي سيُضاف. |
| embed_all_workbook | **bool** | إذا كان `true`، سيتم تضمين دفتر العمل بالكامل في المخطط؛ <br/><br/>            إذا كان `false`، سيتم تضمين بيانات المخطط فقط. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | يُلقى عندما يكون أي معامل مطلوب بقيمة None أو فارغًا، أو إذا لم يتم العثور على المخطط في دفتر العمل. |


## add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-iorawiobase-str-str-bool}
يستخرج مخططًا من دفتر عمل Excel المحدد ويضيفه إلى نهاية مجموعة الأشكال المعطاة عند الإحداثيات المحددة.

### Returns

المخطط الذي تم إضافته إلى مجموعة الأشكال.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/ar/aspose.slides/ishapecollection) | مجموعة الأشكال التي سيُضاف إليها المخطط. |
| x | **float** | إحداثي X لتحديد موقع المخطط. |
| y | **float** | إحداثي Y لتحديد موقع المخطط. |
| workbook_stream | **io.RawIOBase** | تدفق يحتوي على بيانات دفتر العمل. |
| worksheet_name | **str** | اسم ورقة العمل التي تحتوي على المخطط. |
| chart_name | **str** | اسم المخطط الذي سيُضاف. |
| embed_all_workbook | **bool** | إذا كان `true`، سيتم تضمين دفتر العمل بالكامل في المخطط؛ <br/><br/>            إذا كان `false`، سيتم تضمين بيانات المخطط فقط. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | يُلقى عندما يكون أي معامل مطلوب بقيمة None أو فارغًا، أو إذا لم يتم العثور على المخطط في دفتر العمل. |
| **RuntimeError(Proxy error(InvalidOperationException))** | يُلقى عندما تكون بيانات الإدخال بتنسيق غير مدعوم. |


## add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook) {#ishapecollection-float-float-str-str-str-bool}
يستخرج مخططًا من دفتر عمل Excel المحدد ويضيفه إلى نهاية مجموعة الأشكال المعطاة عند الإحداثيات المحددة.

### Returns

المخطط الذي تم إضافته إلى مجموعة الأشكال.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/ar/aspose.slides/ishapecollection) | مجموعة الأشكال التي سيُضاف إليها المخطط. |
| x | **float** | إحداثي X لتحديد موقع المخطط. |
| y | **float** | إحداثي Y لتحديد موقع المخطط. |
| workbook_path | **str** | مسار الملف إلى دفتر العمل الذي يحتوي على المخطط. |
| worksheet_name | **str** | اسم ورقة العمل التي تحتوي على المخطط. |
| chart_name | **str** | اسم المخطط الذي سيُضاف. |
| embed_workbook | **bool** | إذا كان `true`، سيتم تضمين دفتر العمل في المخطط؛ <br/><br/>            إذا كان `false`، سيتصل المخطط ب دفتر العمل الخارجي. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | يُلقى عندما يكون أي معامل مطلوب بقيمة None أو فارغًا، أو إذا لم يتم العثور على المخطط في دفتر العمل. |
| **RuntimeError(Proxy error(IOException))** | يُلقى عندما يحدث خطأ إدخال/إخراج أثناء الوصول إلى الملف. |
| **RuntimeError(Proxy error(InvalidOperationException))** | يُلقى عندما تكون بيانات الإدخال بتنسيق غير مدعوم. |



### See Also
* الفئة [`ExcelWorkbookImporter`](/slides/python-net/ar/aspose.slides.importing/excelworkbookimporter)
* الفئة [`IExcelDataWorkbook`](/slides/python-net/ar/aspose.slides.excel/iexceldataworkbook)
* الفئة [`IShapeCollection`](/slides/python-net/ar/aspose.slides/ishapecollection)
* الوحدة [`aspose.slides.importing`](/slides/python-net/ar/aspose.slides.importing)
* المكتبة [`Aspose.Slides`](/slides/python-net)