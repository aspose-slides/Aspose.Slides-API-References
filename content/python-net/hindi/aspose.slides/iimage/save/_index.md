---
title: save method
second_title: Aspose.Slides Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/iimage/save/
weight: 10
---
## save(self, filename) {#str}
छवि को फ़ाइल में सहेजता है।


```python
def save(self, filename):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| filename | **str** | फ़ाइल का पथ जहाँ छवि सहेजी जाएगी। |


## save(self, filename, format) {#str-imageformat}
निर्दिष्ट स्वरूप में छवि को फ़ाइल में सहेजता है।


```python
def save(self, filename, format):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| filename | **str** | फ़ाइल का पथ जहाँ छवि सहेजी जाएगी। |
| format | [`ImageFormat`](/slides/python-net/hi/aspose.slides/imageformat) | छवि का स्वरूप। |


## save(self, stream, format) {#iorawiobase-imageformat}
निर्दिष्ट स्वरूप में छवि को स्ट्रीम में सहेजता है।


```python
def save(self, stream, format):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream | **io.RawIOBase** | स्ट्रीम जहाँ छवि सहेजा जाएगा। |
| format | [`ImageFormat`](/slides/python-net/hi/aspose.slides/imageformat) | छवि का स्वरूप। |


## save(self, filename, format, quality) {#str-imageformat-int}
निर्दिष्ट स्वरूप और गुणवत्ता में छवि को फ़ाइल में सहेजता है।


```python
def save(self, filename, format, quality):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| filename | **str** | फ़ाइल का पथ जहाँ छवि सहेजी जाएगी। |
| format | [`ImageFormat`](/slides/python-net/hi/aspose.slides/imageformat) | छवि का स्वरूप। |
| quality | **int** | सहेजी गई छवि की गुणवत्ता (0 से 100)।  <br/><br/>यह पैरामीटर केवल [`ImageFormat.JPEG`](/slides/python-net/hi/aspose.slides/imageformat/JPEG) में सहेजने को प्रभावित करता है; अन्य सभी स्वरूपों के लिए इसे नजरअंदाज़ किया जाता है। |


## save(self, stream, format, quality) {#iorawiobase-imageformat-int}
निर्दिष्ट स्वरूप और गुणवत्ता में छवि को स्ट्रीम में सहेजता है।


```python
def save(self, stream, format, quality):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream | **io.RawIOBase** | स्ट्रीम जहाँ छवि सहेजा जाएगा। |
| format | [`ImageFormat`](/slides/python-net/hi/aspose.slides/imageformat) | छवि का स्वरूप। |
| quality | **int** | सहेजी गई छवि की गुणवत्ता (0 से 100)।  <br/><br/>यह पैरामीटर केवल [`ImageFormat.JPEG`](/slides/python-net/hi/aspose.slides/imageformat/JPEG) में सहेजने को प्रभावित करता है; अन्य सभी स्वरूपों के लिए इसे नजरअंदाज़ किया जाता है। |



### संबंधित देखें
* क्लास [`IImage`](/slides/python-net/hi/aspose.slides/iimage)
* enumeration [`ImageFormat`](/slides/python-net/hi/aspose.slides/imageformat)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)