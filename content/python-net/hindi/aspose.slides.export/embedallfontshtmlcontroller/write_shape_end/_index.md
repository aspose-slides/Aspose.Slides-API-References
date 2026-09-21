---
title: write_shape_end method
second_title: Aspose.Slides Python के लिए .NET API रेफ़रेंस
description: 
type: docs
url: /hi/aspose.slides.export/embedallfontshtmlcontroller/write_shape_end/
weight: 60
---
## write_shape_end(self, generator, shape) {#ihtmlgenerator-ishape}
shape की रेंडरिंग से पहले कॉल किया जाता है। प्रत्येक shape के लिए एक बार कॉल किया जाता है। यदि यह फ़ंक्शन generator को कुछ लिखता है, तो वर्तमान slide इमेज जनरेशन समाप्त हो जाएगी, जोड़ी गई HTML फ्रैगमेंट सम्मिलित होगी और नई इमेज पिछले के ऊपर शुरू होगी।


```python
def write_shape_end(self, generator, shape):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/hi/aspose.slides.export/ihtmlgenerator) | आउटपुट ऑब्जेक्ट। |
| shape | [`IShape`](/slides/python-net/hi/aspose.slides/ishape) | आखिरी बार रेंडर किया गया shape। |



### संबंधित देखें
* क्लास [`EmbedAllFontsHtmlController`](/slides/python-net/hi/aspose.slides.export/embedallfontshtmlcontroller)
* क्लास [`IHtmlGenerator`](/slides/python-net/hi/aspose.slides.export/ihtmlgenerator)
* क्लास [`IShape`](/slides/python-net/hi/aspose.slides/ishape)
* मॉड्यूल [`aspose.slides.export`](/slides/python-net/hi/aspose.slides.export)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)