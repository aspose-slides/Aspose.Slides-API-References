---
title: add_table_from_workbook method
second_title: Aspose.Slides for Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.importing/excelworkbookimporter/add_table_from_workbook/
weight: 20
---
## add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str}
निर्दिष्ट Excel वर्कबुक से एक तालिका प्राप्त करता है और निर्दिष्ट निर्देशांक पर दिए गए रूप संग्रह के अंत में इसे जोड़ता है।

### परिणाम

रूप संग्रह में जोड़ी गई तालिका।



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/hi/aspose.slides/ishapecollection) | रूप संग्रह जहाँ तालिका जोड़ी जाएगी। |
| x | **float** | तालिका को स्थित करने के लिए X निर्देशांक। |
| y | **float** | तालिका को स्थित करने के लिए Y निर्देशांक। |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/hi/aspose.slides.excel/iexceldataworkbook) | Excel वर्कबुक। |
| worksheet_name | **str** | उस कार्यपत्रक का नाम जिसमें तालिका सम्मिलित है। |
| cell_range | **str** | सेल रेंज जो तालिका को परिभाषित करती है (उदाहरण के लिए, "A1:D10")। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | जब कोई आवश्यक पैरामीटर None या खाली हो, या निर्दिष्ट कार्यपत्रक या सेल रेंज अमान्य हो, तब थ्रो किया जाता है। |
| **RuntimeError(Proxy error(InvalidOperationException))** | जब इनपुट डेटा असमर्थित प्रारूप में हो, तब थ्रो किया जाता है। |


## add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range) {#ishapecollection-float-float-str-str-str}
निर्दिष्ट Excel वर्कबुक फ़ाइल से एक तालिका प्राप्त करता है और निर्दिष्ट निर्देशांक पर दिए गए रूप संग्रह के अंत में इसे जोड़ता है।

### परिणाम

रूप संग्रह में जोड़ी गई तालिका।



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/hi/aspose.slides/ishapecollection) | रूप संग्रह जहाँ तालिका जोड़ी जाएगी। |
| x | **float** | तालिका को स्थित करने के लिए X निर्देशांक। |
| y | **float** | तालिका को स्थित करने के लिए Y निर्देशांक। |
| workbook_path | **str** | Excel वर्कबुक फ़ाइल का पथ। |
| worksheet_name | **str** | उस कार्यपत्रक का नाम जिसमें तालिका सम्मिलित है। |
| cell_range | **str** | सेल रेंज जो तालिका को परिभाषित करती है (उदाहरण के लिए, "A1:D10")। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | जब कोई आवश्यक पैरामीटर None या खाली हो, या निर्दिष्ट कार्यपत्रक या सेल रेंज अमान्य हो, तब थ्रो किया जाता है। |
| **RuntimeError(Proxy error(IOException))** | वर्कबुक फ़ाइल तक पहुँचते समय I/O त्रुटि होने पर थ्रो किया जाता है। |
| **RuntimeError(Proxy error(InvalidOperationException))** | जब इनपुट डेटा असमर्थित प्रारूप में हो, तब थ्रो किया जाता है। |


## add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range) {#ishapecollection-float-float-iorawiobase-str-str}
निर्दिष्ट Excel वर्कबुक फ़ाइल से एक तालिका प्राप्त करता है और निर्दिष्ट निर्देशांक पर दिए गए रूप संग्रह के अंत में इसे जोड़ता है।

### परिणाम

रूप संग्रह में जोड़ी गई तालिका।



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/hi/aspose.slides/ishapecollection) | रूप संग्रह जहाँ तालिका जोड़ी जाएगी। |
| x | **float** | तालिका को स्थित करने के लिए X निर्देशांक। |
| y | **float** | तालिका को स्थित करने के लिए Y निर्देशांक। |
| workbook_stream | **io.RawIOBase** | वर्कबुक डेटा वाला एक स्ट्रीम। |
| worksheet_name | **str** | उस कार्यपत्रक का नाम जिसमें तालिका सम्मिलित है। |
| cell_range | **str** | सेल रेंज जो तालिका को परिभाषित करती है (उदाहरण के लिए, "A1:D10")। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | जब कोई आवश्यक पैरामीटर None या खाली हो, या निर्दिष्ट कार्यपत्रक या सेल रेंज अमान्य हो, तब थ्रो किया जाता है। |
| **RuntimeError(Proxy error(InvalidOperationException))** | जब इनपुट डेटा असमर्थित प्रारूप में हो, तब थ्रो किया जाता है। |



### संबंधित देखें
* क्लास [`ExcelWorkbookImporter`](/slides/python-net/hi/aspose.slides.importing/excelworkbookimporter)
* क्लास [`IExcelDataWorkbook`](/slides/python-net/hi/aspose.slides.excel/iexceldataworkbook)
* क्लास [`IShapeCollection`](/slides/python-net/hi/aspose.slides/ishapecollection)
* क्लास [`ITable`](/slides/python-net/hi/aspose.slides/itable)
* मॉड्यूल [`aspose.slides.importing`](/slides/python-net/hi/aspose.slides.importing)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)