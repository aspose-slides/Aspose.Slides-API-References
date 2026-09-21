---
title: add method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/captionscollection/add/
weight: 10
---
## add(self, label, file_path) {#str-str}
संग्रह के अंत में WebVTT बंद कैप्शन जोड़ता है।

### रिटर्न

जोड़ा गया [`ICaptions`](/slides/python-net/hi/aspose.slides/icaptions) उदाहरण।



```python
def add(self, label, file_path):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| label | **str** | बंद कैप्शन का लेबल। |
| file_path | **str** | WebVTT फ़ाइल का पथ। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | यदि `file_path` `None` है तो उत्पन्न होता है। |
| **RuntimeError(Proxy error(ArgumentException))** | यदि `file_path` खाली है तो उत्पन्न होता है। |


## add(self, label, stream) {#str-iorawiobase}
स्ट्रीम से संग्रह के अंत में WebVTT बंद कैप्शन जोड़ता है।

### रिटर्न

जोड़ा गया [`ICaptions`](/slides/python-net/hi/aspose.slides/icaptions) उदाहरण।



```python
def add(self, label, stream):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| label | **str** | बंद कैप्शन का लेबल। |
| stream | **io.RawIOBase** | WebVTT स्वरूप में डेटा वाली इनपुट स्ट्रीम। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | यदि `stream` `None` है तो उत्पन्न होता है। |
| **RuntimeError(Proxy error(ArgumentException))** | यदि इनपुट डेटा WebVTT स्वरूप में नहीं है तो उत्पन्न होता है। |



### संबंधित
* वर्ग [`CaptionsCollection`](/slides/python-net/hi/aspose.slides/captionscollection)
* वर्ग [`ICaptions`](/slides/python-net/hi/aspose.slides/icaptions)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)