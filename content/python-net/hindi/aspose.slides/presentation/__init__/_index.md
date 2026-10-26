---
title: Presentation constructor
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/presentation/__init__/
weight: 10
---
## __init__(self) {#}
यह कंस्ट्रक्टर नई प्रस्तुति को शून्य से बनाता है।
बनाई गई प्रस्तुति में एक खाली स्लाइड होती है।

```python
def __init__(self):
    ...
```

## __init__(self, load_options) {#loadoptions}
यह कंस्ट्रक्टर नई प्रस्तुति को शून्य से बनाता है।
बनाई गई प्रस्तुति में एक खाली स्लाइड होती है।

```python
def __init__(self, load_options):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| load_options | [`LoadOptions`](/slides/python-net/hi/aspose.slides/loadoptions) | अतिरिक्त लोड विकल्प। |

## __init__(self, stream) {#iorawiobase}
यह कंस्ट्रक्टर मौजूदा प्रस्तुति को पढ़ने के प्राथमिक तंत्र है।

```python
def __init__(self, stream):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream | **io.RawIOBase** | इनपुट स्ट्रीम। |

## __init__(self, file) {#str}
यह कंस्ट्रक्टर स्रोत फ़ाइल पथ प्राप्त करता है जिससे
प्रस्तुति की सामग्री पढ़ी जाती है।

```python
def __init__(self, file):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file | **str** | इनपुट फ़ाइल। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | जब इनपुट फ़ाइल की लंबाई शून्य हो तो थ्रो किया जाता है |

## __init__(self, stream, load_options) {#iorawiobase-loadoptions}
यह कंस्ट्रक्टर मौजूदा प्रस्तुति को पढ़ने के प्राथमिक तंत्र है।

```python
def __init__(self, stream, load_options):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream | **io.RawIOBase** | इनपुट स्ट्रीम। |
| load_options | [`LoadOptions`](/slides/python-net/hi/aspose.slides/loadoptions) | अतिरिक्त लोड विकल्प। |

## __init__(self, file, load_options) {#str-loadoptions}
यह कंस्ट्रक्टर स्रोत फ़ाइल पथ प्राप्त करता है जिससे
प्रस्तुति की सामग्री पढ़ी जाती है।

```python
def __init__(self, file, load_options):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file | **str** | इनपुट फ़ाइल। |
| load_options | [`LoadOptions`](/slides/python-net/hi/aspose.slides/loadoptions) | अतिरिक्त लोड विकल्प। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | जब इनपुट फ़ाइल की लंबाई शून्य हो तो थ्रो किया जाता है |

### संबंधित देखें
* क्लास [`LoadOptions`](/slides/python-net/hi/aspose.slides/loadoptions)
* क्लास [`Presentation`](/slides/python-net/hi/aspose.slides/presentation)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)