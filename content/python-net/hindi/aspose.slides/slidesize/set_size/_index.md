---
title: set_size method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/slidesize/set_size/
weight: 10
---
## set_size(self, type, scale_type) {#slidesizetype-slidesizescaletype}
टाइप द्वारा स्लाइड आकार सेट करता है और मौजूदा सामग्री को स्केल करता है।

```python
def set_size(self, type, scale_type):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| type | [`SlideSizeType`](/slides/python-net/hi/aspose.slides/slidesizetype) | लागू करने के लिए पूर्वनिर्धारित स्लाइड आकार। |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/hi/aspose.slides/slidesizescaletype) | उपयोग करने के लिए सामग्री स्केलिंग मोड। |

### टिप्पणी

[`SlideSizeType.CUSTOM`](/slides/python-net/hi/aspose.slides/slidesizetype/CUSTOM) के अलावा कोई भी मान असाइन करने पर चयनित प्रकार के आधार पर [`SlideSize.size`](/slides/python-net/hi/aspose.slides/slidesize/size) को समायोजित करता है, जबकि [`SlideSize.orientation`](/slides/python-net/hi/aspose.slides/slidesize/orientation) को संरक्षित रखता है।

## set_size(self, width, height, scale_type) {#float-float-slidesizescaletype}
स्लाइड आयामों को स्पष्ट रूप से सेट करता है और मौजूदा सामग्री को स्केल करता है।

```python
def set_size(self, width, height, scale_type):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| width | **float** | नए स्लाइड की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए स्लाइड की ऊँचाई, पॉइंट्स में। |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/hi/aspose.slides/slidesizescaletype) | उपयोग करने के लिए सामग्री स्केलिंग मोड। |

### टिप्पणी

यह [`SlideSize.type`](/slides/python-net/hi/aspose.slides/slidesize/type) प्रॉपर्टी को [`SlideSizeType.CUSTOM`](/slides/python-net/hi/aspose.slides/slidesizetype/CUSTOM) पर रीसेट करता है और [`SlideSize.orientation`](/slides/python-net/hi/aspose.slides/slidesize/orientation) को सेट करता है।

### देखें
* क्लास [`SlideSize`](/slides/python-net/hi/aspose.slides/slidesize)
* एन्यूमरेशन [`SlideSizeScaleType`](/slides/python-net/hi/aspose.slides/slidesizescaletype)
* एन्यूमरेशन [`SlideSizeType`](/slides/python-net/hi/aspose.slides/slidesizetype)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)