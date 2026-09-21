---
title: get_cell method
second_title: Aspose.Slides for Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.excel/iexceldataworkbook/get_cell/
weight: 10
---
## get_cell(self, worksheet_index, cell_name) {#int-str}
निर्दिष्ट कार्यपत्रक से उसके इंडेक्स और Excel-स्टाइल सेल नाम (जैसे, "B2") का उपयोग करके एक सेल प्राप्त करता है।

### रिटर्न

निर्दिष्ट स्थान पर स्थित सेल।



```python
def get_cell(self, worksheet_index, cell_name):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| worksheet_index | **int** | कार्यपत्रक का शून्य-आधारित इंडेक्स। |
| cell_name | **str** | Excel-स्टाइल सेल संदर्भ (जैसे, "A1", "C5")। |


## get_cell(self, worksheet_name, cell_name) {#str-str}
निर्दिष्ट कार्यपत्रक से Excel-स्टाइल सेल नाम (जैसे, "B2") का उपयोग करके एक सेल प्राप्त करता है।

### रिटर्न

निर्दिष्ट स्थान पर स्थित सेल।



```python
def get_cell(self, worksheet_name, cell_name):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| worksheet_name | **str** | कार्यपत्रक का नाम। |
| cell_name | **str** | Excel-स्टाइल सेल संदर्भ (जैसे, "A1", "C5")। |


## get_cell(self, worksheet_index, row, column) {#int-int-int}
निर्दिष्ट कार्यपत्रक से उसके इंडेक्स और सेल समन्वयों का उपयोग करके एक सेल प्राप्त करता है।

### रिटर्न

निर्दिष्ट स्थान पर स्थित सेल।



```python
def get_cell(self, worksheet_index, row, column):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| worksheet_index | **int** | कार्यपत्रक का शून्य-आधारित इंडेक्स। |
| row | **int** | सेल की शून्य-आधारित पंक्ति इंडेक्स। |
| column | **int** | सेल की शून्य-आधारित स्तंभ इंडेक्स। |


## get_cell(self, worksheet_name, row, column) {#str-int-int}
निर्दिष्ट कार्यपत्रक से उसके नाम और सेल समन्वयों का उपयोग करके एक सेल प्राप्त करता है।

### रिटर्न

निर्दिष्ट स्थान पर स्थित सेल।



```python
def get_cell(self, worksheet_name, row, column):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| worksheet_name | **str** | कार्यपत्रक का नाम। |
| row | **int** | सेल की शून्य-आधारित पंक्ति इंडेक्स। |
| column | **int** | सेल की शून्य-आधारित स्तंभ इंडेक्स। |



### संबंधित देखें
* क्लास [`IExcelDataCell`](/slides/python-net/hi/aspose.slides.excel/iexceldatacell)
* क्लास [`IExcelDataWorkbook`](/slides/python-net/hi/aspose.slides.excel/iexceldataworkbook)
* मॉड्यूल [`aspose.slides.excel`](/slides/python-net/hi/aspose.slides.excel)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)