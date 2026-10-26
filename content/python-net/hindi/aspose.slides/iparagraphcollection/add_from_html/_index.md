---
title: add_from_html method
second_title: Aspose.Slides फ़ॉर पाइथन वाया .NET API रेफ़रेंस
description: 
type: docs
url: /hi/aspose.slides/iparagraphcollection/add_from_html/
weight: 20
---
## add_from_html(self, text) {#str}
निर्दिष्ट html स्ट्रिंग से पाठ को संग्रह में जोड़ता है।

```python
def add_from_html(self, text):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| text | **str** | HTML पाठ। |

## add_from_html(self, text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
निर्दिष्ट html स्ट्रिंग से पाठ को संग्रह में जोड़ता है।

```python
def add_from_html(self, text, resolver, uri):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| text | **str** | HTML पाठ। |
| resolver | [`IExternalResourceResolver`](/slides/python-net/hi/aspose.slides.importing/iexternalresourceresolver) | Resolver कॉलबैक ऑब्जेक्ट जो URIs को हल करता है और संदर्भित ऑब्जेक्ट्स को लाता है। |
| uri | **str** | HTML दस्तावेज़ जोड़ने के लिए URI। सापेक्ष लिंक को हल करने के लिए उपयोग किया जाता है। |

### टिप्पणी

Resolver निर्दिष्ट करने से संभावित रूप से एक सुरक्षा खामी उत्पन्न हो सकती है। सावधानी से उपयोग करें।

### संबंधित देखें
* क्लास [`IExternalResourceResolver`](/slides/python-net/hi/aspose.slides.importing/iexternalresourceresolver)
* क्लास [`IParagraphCollection`](/slides/python-net/hi/aspose.slides/iparagraphcollection)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)