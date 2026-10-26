---
title: set_size method
second_title: Aspose.Slides के लिए Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/islidesize/set_size/
weight: 10
---
## set_size(self, type, scale_type) {#slidesizetype-slidesizescaletype}
स्लाइड का आकार प्रकार द्वारा निर्धारित करता है और मौजूदा सामग्री को स्केल करता है।

```python
def set_size(self, type, scale_type):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| type | [`SlideSizeType`](/slides/python-net/hi/aspose.slides/slidesizetype) | लागू करने के लिए पूर्वनिर्धारित स्लाइड आकार। |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/hi/aspose.slides/slidesizescaletype) | उपयोग करने के लिए सामग्री स्केलिंग मोड। |

### टिप्पणियाँ
[`SlideSizeType.CUSTOM`](/slides/python-net/hi/aspose.slides/slidesizetype/CUSTOM) के अलावा कोई भी मान असाइन करने से चयनित प्रकार के आधार पर [`ISlideSize.size`](/slides/python-net/hi/aspose.slides/islidesize/size) समायोजित होता है, जबकि [`ISlideSize.orientation`](/slides/python-net/hi/aspose.slides/islidesize/orientation) को संरक्षित रखा जाता है।

## set_size(self, width, height, scale_type) {#float-float-slidesizescaletype}
स्लाइड आयामों को स्पष्ट रूप से सेट करता है और मौजूदा सामग्री को स्केल करता है।

```python
def set_size(self, width, height, scale_type):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| width | **float** | नई स्लाइड की चौड़ाई, पॉइंट में। |
| height | **float** | नई स्लाइड की ऊँचाई, पॉइंट में। |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/hi/aspose.slides/slidesizescaletype) | उपयोग करने के लिए सामग्री स्केलिंग मोड। |

### टिप्पणियाँ
यह [`ISlideSize.type`](/slides/python-net/hi/aspose.slides/islidesize/type) प्रॉपर्टी को [`SlideSizeType.CUSTOM`](/slides/python-net/hi/aspose.slides/slidesizetype/CUSTOM) पर रीसेट करता है और [`ISlideSize.orientation`](/slides/python-net/hi/aspose.slides/islidesize/orientation) सेट करता है।

### देखें
* वर्ग [`ISlideSize`](/slides/python-net/hi/aspose.slides/islidesize)
* एन्यूमरेशन [`SlideSizeScaleType`](/slides/python-net/hi/aspose.slides/slidesizescaletype)
* एन्यूमरेशन [`SlideSizeType`](/slides/python-net/hi/aspose.slides/slidesizetype)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)