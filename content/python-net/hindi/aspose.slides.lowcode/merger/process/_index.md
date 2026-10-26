---
title: process method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.lowcode/merger/process/
weight: 10
---
## process(input_file_names, output_file_name) {#liststr-str}
कई PowerPoint प्रस्तुतियों को समान प्रारूप में एकल प्रस्तुति फ़ाइल में मिलाता है।

```python
@staticmethod
def process(input_file_names, output_file_name):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| input_file_names | **List[str]** | इनपुट प्रस्तुति फ़ाइल नामों की एक सरणी। |
| output_file_name | **str** | परिणामी मर्ज की गई प्रस्तुति फ़ाइल का आउटपुट फ़ाइल नाम। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | जब इनपुट फ़ाइल नाम अवैध हों या स्वरूप मेल न खाएँ तो फेंके जाता है। |

## process(input_file_names, output_stream) {#liststr-iorawiobase}
कई PowerPoint प्रस्तुतियों को समान प्रारूप में एकल प्रस्तुति फ़ाइल में मिलाता है।

```python
@staticmethod
def process(input_file_names, output_stream):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| input_file_names | **List[str]** | इनपुट प्रस्तुति फ़ाइल नामों की एक सरणी। |
| output_stream | **io.RawIOBase** | आउटपुट स्ट्रीम। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | जब इनपुट फ़ाइल नाम अवैध हों या स्वरूप मेल न खाएँ तो फेंके जाता है। |

## process(input_file_names, output_file_name, options) {#liststr-str-asposeslidesexportisaveoptions}
कई PowerPoint प्रस्तुतियों को समान प्रारूप में एकल प्रस्तुति फ़ाइल में मिलाता है।

```python
@staticmethod
def process(input_file_names, output_file_name, options):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| input_file_names | **List[str]** | इनपुट प्रस्तुति फ़ाइल नामों की एक सरणी। |
| output_file_name | **str** | परिणामी मर्ज की गई प्रस्तुति फ़ाइल का आउटपुट फ़ाइल नाम। |
| options | [`ISaveOptions`](/slides/python-net/hi/aspose.slides.export/isaveoptions) | अतिरिक्त विकल्प जो परिभाषित करते हैं कि मर्ज की गई प्रस्तुति कैसे सहेजी जाती है। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | जब इनपुट फ़ाइल नाम अवैध हों या स्वरूप मेल न खाएँ तो फेंके जाता है। |

## process(input_file_names, output_stream, options) {#liststr-iorawiobase-asposeslidesexportisaveoptions}
कई PowerPoint प्रस्तुतियों को समान प्रारूप में एकल प्रस्तुति फ़ाइल में मिलाता है।

```python
@staticmethod
def process(input_file_names, output_stream, options):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| input_file_names | **List[str]** | इनपुट प्रस्तुति फ़ाइल नामों की एक सरणी। |
| output_stream | **io.RawIOBase** | आउटपुट स्ट्रीम। |
| options | [`ISaveOptions`](/slides/python-net/hi/aspose.slides.export/isaveoptions) | अतिरिक्त विकल्प जो परिभाषित करते हैं कि मर्ज की गई प्रस्तुति कैसे सहेजी जाती है। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | जब इनपुट फ़ाइल नाम अवैध हों या स्वरूप मेल न खाएँ तो फेंके जाता है। |

### देखें
* क्लास [`ISaveOptions`](/slides/python-net/hi/aspose.slides.export/isaveoptions)
* क्लास [`Merger`](/slides/python-net/hi/aspose.slides.lowcode/merger)
* मॉड्यूल [`aspose.slides.lowcode`](/slides/python-net/hi/aspose.slides.lowcode)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)