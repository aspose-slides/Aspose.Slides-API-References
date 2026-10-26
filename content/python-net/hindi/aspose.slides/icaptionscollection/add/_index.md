---
title: add method
second_title: Aspose.Slides Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/icaptionscollection/add/
weight: 10
---
## add(self, label, file_path) {#str-str}
WebVTT बंद कैप्शन को संग्रह के अंत में जोड़ता है।

### Returns

जोड़ा गया [`ICaptions`](/slides/python-net/hi/aspose.slides/icaptions) इंस्टेंस।



```python
def add(self, label, file_path):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| label | **str** | बंद कैप्शन का लेबल। |
| file_path | **str** | WebVTT फ़ाइल का पथ। |

### Exceptions

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | यदि `file_path` `None` है तो थ्रो किया जाता है। |
| **RuntimeError(Proxy error(ArgumentException))** | यदि `file_path` खाली है तो थ्रो किया जाता है। |


## add(self, label, stream) {#str-iorawiobase}
WebVTT बंद कैप्शन को स्ट्रिम से संग्रह के अंत में जोड़ता है।

### Returns

जोड़ा गया [`ICaptions`](/slides/python-net/hi/aspose.slides/icaptions) इंस्टेंस।



```python
def add(self, label, stream):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| label | **str** | बंद कैप्शन का लेबल। |
| stream | **io.RawIOBase** | WebVTT फ़ॉर्मेट में डेटा वाली इनपुट स्ट्रिम। |

### Exceptions

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | यदि `stream` `None` है तो थ्रो किया जाता है। |
| **RuntimeError(Proxy error(ArgumentException))** | यदि इनपुट डेटा WebVTT फ़ॉर्मेट में नहीं है तो थ्रो किया जाता है। |



### See Also
* क्लास [`ICaptions`](/slides/python-net/hi/aspose.slides/icaptions)
* क्लास [`ICaptionsCollection`](/slides/python-net/hi/aspose.slides/icaptionscollection)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)