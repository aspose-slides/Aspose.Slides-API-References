---
title: write_shape_start method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.export/ihtmlformattingcontroller/write_shape_start/
weight: 40
---
## write_shape_start(self, generator, shape) {#ihtmlgenerator-ishape}
shape के रेंडरिंग से पहले बुलाया जाता है। प्रत्येक shape के लिए एक बार बुलाया जाता है। यदि यह फ़ंक्शन generator में कुछ भी लिखता है, तो वर्तमान स्लाइड इमेज जेनरेशन समाप्त हो जाएगी, जोड़ा गया html फ्रैगमेंट सम्मिलित किया जाएगा और नई इमेज पिछले के ऊपर शुरू होगी।

```python
def write_shape_start(self, generator, shape):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/hi/aspose.slides.export/ihtmlgenerator) | आउटपुट ऑब्जेक्ट। |
| shape | [`IShape`](/slides/python-net/hi/aspose.slides/ishape) | रेंडर करने वाली Shape। |

### देखें
* क्लास [`IHtmlFormattingController`](/slides/python-net/hi/aspose.slides.export/ihtmlformattingcontroller)
* क्लास [`IHtmlGenerator`](/slides/python-net/hi/aspose.slides.export/ihtmlgenerator)
* क्लास [`IShape`](/slides/python-net/hi/aspose.slides/ishape)
* मॉड्यूल [`aspose.slides.export`](/slides/python-net/hi/aspose.slides.export)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)