---
title: save method
second_title: Aspose.Slides Python के लिए .NET के माध्यम से API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/presentation/save/
weight: 90
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
प्रस्तुति की सभी स्लाइडों को XAML मार्कअप का प्रतिनिधित्व करने वाली फ़ाइलों के सेट में सहेजता है।

```python
def save(self, options):
    ...
```

| परामीटर | प्रकार | विवरण |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/hi/aspose.slides.export.xaml/ixamloptions) | XAML फ़ॉर्मेट विकल्प। |

## save(self, fname, format) {#str-asposeslidesexportsaveformat}
प्रस्तुति की सभी स्लाइडों को निर्दिष्ट फ़ॉर्मेट वाली फ़ाइल में सहेजता है।

```python
def save(self, fname, format):
    ...
```

| परामीटर | प्रकार | विवरण |
| :- | :- | :- |
| fname | **str** | बनायी गई फ़ाइल का पथ। |
| format | [`SaveFormat`](/slides/python-net/hi/aspose.slides.export/saveformat) | निर्यात किए गए डेटा का फ़ॉर्मेट। |

## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
प्रस्तुति की सभी स्लाइडों को निर्दिष्ट फ़ॉर्मेट में स्ट्रीम पर सहेजता है।

```python
def save(self, stream, format):
    ...
```

| परामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream | **io.RawIOBase** | आउटपुट स्ट्रीम। |
| format | [`SaveFormat`](/slides/python-net/hi/aspose.slides.export/saveformat) | निर्यात किए गए डेटा का फ़ॉर्मेट। |

## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}

```python
def save(self, fname, format, options):
    ...
```

| परामीटर | प्रकार | विवरण |
| :- | :- | :- |
| fname | **str** |  |
| format | [`SaveFormat`](/slides/python-net/hi/aspose.slides.export/saveformat) |  |
| options | [`ISaveOptions`](/slides/python-net/hi/aspose.slides.export/isaveoptions) |  |

## save(self, stream, format, options) {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
प्रस्तुति की सभी स्लाइडों को निर्दिष्ट फ़ॉर्मेट में और अतिरिक्त विकल्पों के साथ स्ट्रीम पर सहेजता है।

```python
def save(self, stream, format, options):
    ...
```

| परामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream | **io.RawIOBase** | आउटपुट स्ट्रीम। |
| format | [`SaveFormat`](/slides/python-net/hi/aspose.slides.export/saveformat) | निर्यात किए गए डेटा का फ़ॉर्मेट। |
| options | [`ISaveOptions`](/slides/python-net/hi/aspose.slides.export/isaveoptions) | अतिरिक्त फ़ॉर्मेट विकल्प। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | यदि आप एन्क्रिप्टेड फ़ाइल को Office 2007-2010 के गैर-फ़ॉर्मेट में सहेजने का प्रयास करते हैं। |

## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
निर्दिष्ट स्लाइडों को पृष्ठ क्रमांक बनाए रखते हुए निर्दिष्ट फ़ॉर्मेट वाली फ़ाइल में सहेजता है।

```python
def save(self, fname, slides, format):
    ...
```

| परामीटर | प्रकार | विवरण |
| :- | :- | :- |
| fname | **str** | बनायी गई फ़ाइल का पथ। |
| slides | **List[int]** | स्लाइड पोज़ीशन का एरे, 1 से शुरू। |
| format | [`SaveFormat`](/slides/python-net/hi/aspose.slides.export/saveformat) | निर्यात किए गए डेटा का फ़ॉर्मेट। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | जब stream या slides पैरामीटर None हो। |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | जब slides पैरामीटर में गलत पृष्ठ संख्याएँ हों। |
| **RuntimeError(Proxy error(InvalidOperationException))** | जब असमर्थित SaveFormat उपयोग किया जाए, जैसे PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP। |

## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
निर्दिष्ट स्लाइडों को पृष्ठ क्रमांक बनाए रखते हुए निर्दिष्ट फ़ॉर्मेट में स्ट्रीम पर सहेजता है।

```python
def save(self, stream, slides, format):
    ...
```

| परामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream | **io.RawIOBase** | आउटपुट स्ट्रीम। |
| slides | **List[int]** | स्लाइड पोज़ीशन का एरे, 1 से शुरू। |
| format | [`SaveFormat`](/slides/python-net/hi/aspose.slides.export/saveformat) | निर्यात किए गए डेटा का फ़ॉर्मेट। |

## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
निर्दिष्ट स्लाइडों को पृष्ठ क्रमांक बनाए रखते हुए निर्दिष्ट फ़ॉर्मेट वाली फ़ाइल में सहेजता है।

```python
def save(self, fname, slides, format, options):
    ...
```

| परामीटर | प्रकार | विवरण |
| :- | :- | :- |
| fname | **str** | बनायी गई फ़ाइल का पथ। |
| slides | **List[int]** | स्लाइड पोज़ीशन का एरे, 1 से शुरू। |
| format | [`SaveFormat`](/slides/python-net/hi/aspose.slides.export/saveformat) | निर्यात किए गए डेटा का फ़ॉर्मेट। |
| options | [`ISaveOptions`](/slides/python-net/hi/aspose.slides.export/isaveoptions) | अतिरिक्त फ़ॉर्मेट विकल्प। |

## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
निर्दिष्ट स्लाइडों को पृष्ठ क्रमांक बनाए रखते हुए निर्दिष्ट फ़ॉर्मेट में स्ट्रीम पर सहेजता है।

```python
def save(self, stream, slides, format, options):
    ...
```

| परामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream | **io.RawIOBase** | आउटपुट स्ट्रीम। |
| slides | **List[int]** | स्लाइड पोज़ीशन का एरे, 1 से शुरू। |
| format | [`SaveFormat`](/slides/python-net/hi/aspose.slides.export/saveformat) | निर्यात किए गए डेटा का फ़ॉर्मेट। |
| options | [`ISaveOptions`](/slides/python-net/hi/aspose.slides.export/isaveoptions) | अतिरिक्त फ़ॉर्मेट विकल्प। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | जब stream या slides पैरामीटर None हो। |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | जब slides पैरामीटर में गलत पृष्ठ संख्याएँ हों। |
| **RuntimeError(Proxy error(InvalidOperationException))** | जब असमर्थित SaveFormat उपयोग किया जाए, जैसे PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP। |

### संबंधित देखें
* क्लास [`ISaveOptions`](/slides/python-net/hi/aspose.slides.export/isaveoptions)
* क्लास [`IXamlOptions`](/slides/python-net/hi/aspose.slides.export.xaml/ixamloptions)
* क्लास [`Presentation`](/slides/python-net/hi/aspose.slides/presentation)
* एन्यूमरेशन [`SaveFormat`](/slides/python-net/hi/aspose.slides.export/saveformat)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)