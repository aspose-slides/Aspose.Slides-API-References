---
title: add method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/customxmlpartcollection/add/
weight: 10
---
## add(self, xml_string) {#str}
नया कस्टम XML भाग जोड़ता है।

### Returns
कस्टम XML भाग बनाया गया।

```python
def add(self, xml_string):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| xml_string | **str** | नए भाग को जोड़ने के लिए XML स्ट्रिंग। |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlString `None` है। |
| **RuntimeError(Proxy error(ArgumentException))** | xmlString खाली है या xml-data अमान्य है। |

## add(self, xml_data) {#bytes}
नया कस्टम XML भाग जोड़ता है।

### Returns
कस्टम XML भाग बनाया गया।

```python
def add(self, xml_data):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| xml_data | **bytes** | नए भाग को जोड़ने के लिए XML डेटा। |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlData `None` है। |
| **RuntimeError(Proxy error(ArgumentException))** | xmlData खाली है या अमान्य है। |

## add(self, input_stream) {#iorawiobase}
नया कस्टम XML भाग जोड़ता है।

### Returns
कस्टम XML भाग बनाया गया।

```python
def add(self, input_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| input_stream | **io.RawIOBase** | नए भाग को जोड़ने के लिए XML डेटा वाला इनपुट स्ट्रीम। |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | inputStream `None` है। |
| **RuntimeError(Proxy error(ArgumentException))** | inputStream में डेटा खाली है या अमान्य है। |

### संबंधित देखें
* क्लास [`CustomXmlPartCollection`](/slides/python-net/hi/aspose.slides/customxmlpartcollection)
* क्लास [`ICustomXmlPart`](/slides/python-net/hi/aspose.slides/icustomxmlpart)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)