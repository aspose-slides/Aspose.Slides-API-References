---
title: add method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/icustomxmlpartcollection/add/
weight: 10
---
## add(self, xml_data) {#bytes}
नया कस्टम xml भाग जोड़ता है।

### रिटर्न

Created custom xml part.



```python
def add(self, xml_data):
    ...
```


| परामीटर | प्रकार | विवरण |
| :- | :- | :- |
| xml_data | **bytes** | नए भाग को जोड़ने हेतु xml डेटा। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlData `None` है। |
| **RuntimeError(Proxy error(ArgumentException))** | xmlData खाली है या अवैध है। |


## add(self, xml_string) {#str}
नया कस्टम xml भाग जोड़ता है।

### रिटर्न

Created custom xml part.



```python
def add(self, xml_string):
    ...
```


| परामीटर | प्रकार | विवरण |
| :- | :- | :- |
| xml_string | **str** | नए भाग को जोड़ने हेतु xml स्ट्रिंग। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlString `None` है। |
| **RuntimeError(Proxy error(ArgumentException))** | xmlString खाली है या xml-data अवैध है। |


## add(self, input_stream) {#iorawiobase}
नया कस्टम xml भाग जोड़ता है।

### रिटर्न

Created custom xml part.



```python
def add(self, input_stream):
    ...
```


| परामीटर | प्रकार | विवरण |
| :- | :- | :- |
| input_stream | **io.RawIOBase** | नए भाग को जोड़ने हेतु xml डेटा वाला inputStream। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | inputStream `None` है। |
| **RuntimeError(Proxy error(ArgumentException))** | Data in inputStream खाली है या Sinvalid। |



### देखें
* कक्षा [`ICustomXmlPart`](/slides/python-net/hi/aspose.slides/icustomxmlpart)
* कक्षा [`ICustomXmlPartCollection`](/slides/python-net/hi/aspose.slides/icustomxmlpartcollection)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)