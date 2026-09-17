---
title: process method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.lowcode/merger/process/
weight: 10
---
## process(input_file_names, output_file_name) {#liststr-str}
يدمج عدة عروض تقديمية من PowerPoint بنفس التنسيق في ملف عرض تقديمي واحد.


```python
@staticmethod
def process(input_file_names, output_file_name):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| input_file_names | **List[str]** | مصفوفة بأسماء ملفات العروض التقديمية المدخلة. |
| output_file_name | **str** | اسم ملف الإخراج للملف المدمج الناتج. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | يُرمى عندما تكون أسماء ملفات الإدخال غير صالحة أو لا تتطابق الصيغ. |


## process(input_file_names, output_stream) {#liststr-iorawiobase}
يدمج عدة عروض تقديمية من PowerPoint بنفس التنسيق في ملف عرض تقديمي واحد.


```python
@staticmethod
def process(input_file_names, output_stream):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| input_file_names | **List[str]** | مصفوفة بأسماء ملفات العروض التقديمية المدخلة. |
| output_stream | **io.RawIOBase** | تيار الإخراج. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | يُرمى عندما تكون أسماء ملفات الإدخال غير صالحة أو لا تتطابق الصيغ. |


## process(input_file_names, output_file_name, options) {#liststr-str-asposeslidesexportisaveoptions}
يدمج عدة عروض تقديمية من PowerPoint بنفس التنسيق في ملف عرض تقديمي واحد.


```python
@staticmethod
def process(input_file_names, output_file_name, options):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| input_file_names | **List[str]** | مصفوفة بأسماء ملفات العروض التقديمية المدخلة. |
| output_file_name | **str** | اسم ملف الإخراج للملف المدمج الناتج. |
| options | [`ISaveOptions`](/slides/python-net/ar/aspose.slides.export/isaveoptions) | الخيارات الإضافية التي تحدد كيفية حفظ العرض المدمج. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | يُرمى عندما تكون أسماء ملفات الإدخال غير صالحة أو لا تتطابق الصيغ. |


## process(input_file_names, output_stream, options) {#liststr-iorawiobase-asposeslidesexportisaveoptions}
يدمج عدة عروض تقديمية من PowerPoint بنفس التنسيق في ملف عرض تقديمي واحد.


```python
@staticmethod
def process(input_file_names, output_stream, options):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| input_file_names | **List[str]** | مصفوفة بأسماء ملفات العروض التقديمية المدخلة. |
| output_stream | **io.RawIOBase** | تيار الإخراج. |
| options | [`ISaveOptions`](/slides/python-net/ar/aspose.slides.export/isaveoptions) | الخيارات الإضافية التي تحدد كيفية حفظ العرض المدمج. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | يُرمى عندما تكون أسماء ملفات الإدخال غير صالحة أو لا تتطابق الصيغ. |



### انظر أيضًا
* فئة [`ISaveOptions`](/slides/python-net/ar/aspose.slides.export/isaveoptions)
* فئة [`Merger`](/slides/python-net/ar/aspose.slides.lowcode/merger)
* وحدة [`aspose.slides.lowcode`](/slides/python-net/ar/aspose.slides.lowcode)
* مكتبة [`Aspose.Slides`](/slides/python-net)