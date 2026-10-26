---
title: add_chart_from_workbook method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.importing/excelworkbookimporter/add_chart_from_workbook/
weight: 10
---
## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-int-bool}
निर्दिष्ट Excel workbook से एक chart प्राप्त करता है और निर्दिष्ट निर्देशांकों पर दिए गए shape संग्रह के अंत में इसे जोड़ता है।

### रिटर्न

shape संग्रह में जोड़ा गया chart।



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/hi/aspose.slides/ishapecollection) | chart जोड़े जाने वाला shape संग्रह। |
| x | **float** | chart को स्थित करने के लिए X निर्देशांक। |
| y | **float** | chart को स्थित करने के लिए Y निर्देशांक। |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/hi/aspose.slides.excel/iexceldataworkbook) | Excel workbook। |
| worksheet_name | **str** | chart शामिल करने वाले worksheet का नाम। |
| chart_index | **int** | इंसर्ट करने वाले chart shape का शून्य-आधारित सूचकांक। <br/><br/> यह सूचकांक **Aspose.Slides.Excel.IExcelDataWorkbook.GetChartsFromWorksheet(Syste** मेथड का उपयोग करके प्राप्त किया जा सकता है। |
| embed_all_workbook | **bool** | `true` होने पर, संपूर्ण workbook chart में एम्बेड किया जाएगा; <br/><br/> `false` होने पर, केवल chart डेटा एम्बेड किया जाएगा। |

### अपवाद

| Exception | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | जब कोई आवश्यक पैरामीटर None, खाली हो, या workbook में chart नहीं मिला हो, तब फेंका जाता है। |


## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str-bool}
निर्दिष्ट Excel workbook से एक chart प्राप्त करता है और निर्दिष्ट निर्देशांकों पर दिए गए shape संग्रह के अंत में इसे जोड़ता है।

### रिटर्न

shape संग्रह में जोड़ा गया chart।



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/hi/aspose.slides/ishapecollection) | chart जोड़े जाने वाला shape संग्रह। |
| x | **float** | chart को स्थित करने के लिए X निर्देशांक। |
| y | **float** | chart को स्थित करने के लिए Y निर्देशांक। |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/hi/aspose.slides.excel/iexceldataworkbook) | Excel workbook। |
| worksheet_name | **str** | chart शामिल करने वाले worksheet का नाम। |
| chart_name | **str** | जोड़ा जाने वाले chart का नाम। |
| embed_all_workbook | **bool** | `true` होने पर, संपूर्ण workbook chart में एम्बेड किया जाएगा; <br/><br/> `false` होने पर, केवल chart डेटा एम्बेड किया जाएगा। |

### अपवाद

| Exception | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | जब कोई आवश्यक पैरामीटर None, खाली हो, या workbook में chart नहीं मिला हो, तब फेंका जाता है। |


## add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-iorawiobase-str-str-bool}
निर्दिष्ट Excel workbook से एक chart प्राप्त करता है और निर्दिष्ट निर्देशांकों पर दिए गए shape संग्रह के अंत में इसे जोड़ता है।

### रिटर्न

shape संग्रह में जोड़ा गया chart।



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/hi/aspose.slides/ishapecollection) | chart जोड़े जाने वाला shape संग्रह। |
| x | **float** | chart को स्थित करने के लिए X निर्देशांक। |
| y | **float** | chart को स्थित करने के लिए Y निर्देशांक। |
| workbook_stream | **io.RawIOBase** | workbook डेटा सम्मिलित करने वाली स्ट्रीम। |
| worksheet_name | **str** | chart शामिल करने वाले worksheet का नाम। |
| chart_name | **str** | जोड़ा जाने वाले chart का नाम। |
| embed_all_workbook | **bool** | `true` होने पर, संपूर्ण workbook chart में एम्बेड किया जाएगा; <br/><br/> `false` होने पर, केवल chart डेटा एम्बेड किया जाएगा। |

### अपवाद

| Exception | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | जब कोई आवश्यक पैरामीटर None, खाली हो, या workbook में chart नहीं मिला हो, तब फेंका जाता है। |
| **RuntimeError(Proxy error(InvalidOperationException))** | जब इनपुट डेटा असमर्थित प्रारूप में हो, तब फेंका जाता है। |


## add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook) {#ishapecollection-float-float-str-str-str-bool}
निर्दिष्ट Excel workbook से एक chart प्राप्त करता है और निर्दिष्ट निर्देशांकों पर दिए गए shape संग्रह के अंत में इसे जोड़ता है।

### रिटर्न

shape संग्रह में जोड़ा गया chart।



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/hi/aspose.slides/ishapecollection) | chart जोड़े जाने वाला shape संग्रह। |
| x | **float** | chart को स्थित करने के लिए X निर्देशांक। |
| y | **float** | chart को स्थित करने के लिए Y निर्देशांक। |
| workbook_path | **str** | chart सम्मिलित करने वाला workbook फ़ाइल पथ। |
| worksheet_name | **str** | chart शामिल करने वाले worksheet का नाम। |
| chart_name | **str** | जोड़ा जाने वाले chart का नाम। |
| embed_workbook | **bool** | `true` होने पर, workbook chart में एम्बेड होगा; <br/><br/> `false` होने पर, chart बाहरी workbook की ओर लिंक करेगा। |

### अपवाद

| Exception | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | जब कोई आवश्यक पैरामीटर None, खाली हो, या workbook में chart नहीं मिला हो, तब फेंका जाता है। |
| **RuntimeError(Proxy error(IOException))** | फ़ाइल तक पहुँचते समय I/O त्रुटि होने पर फेंका जाता है। |
| **RuntimeError(Proxy error(InvalidOperationException))** | जब इनपुट डेटा असमर्थित प्रारूप में हो, तब फेंका जाता है। |



### संबंधित देखें
* क्लास [`ExcelWorkbookImporter`](/slides/python-net/hi/aspose.slides.importing/excelworkbookimporter)
* क्लास [`IExcelDataWorkbook`](/slides/python-net/hi/aspose.slides.excel/iexceldataworkbook)
* क्लास [`IShapeCollection`](/slides/python-net/hi/aspose.slides/ishapecollection)
* मॉड्यूल [`aspose.slides.importing`](/slides/python-net/hi/aspose.slides.importing)
* लायब्रेरी [`Aspose.Slides`](/slides/python-net)