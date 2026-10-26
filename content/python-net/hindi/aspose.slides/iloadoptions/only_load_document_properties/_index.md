---
title: only_load_document_properties property
second_title: Aspose.Slides for Python के लिए .NET API रेफ़रेंस
description: 
type: docs
url: /hi/aspose.slides/iloadoptions/only_load_document_properties/
weight: 100
---
## only_load_document_properties प्रॉपर्टी
यह प्रॉपर्टी तब समझ में आती है जब प्रेजेंटेशन फ़ाइल पासवर्ड से सुरक्षित हो।
            true का मान यह दर्शाता है कि केवल दस्तावेज़ प्रॉपर्टीज़ को एक एन्क्रिप्टेड प्रेजेंटेशन फ़ाइल से लोड किया जाना चाहिए और पासवर्ड को अनदेखा किया जाना चाहिए।
            false का मान यह दर्शाता है कि पूरे एन्क्रिप्टेड प्रेजेंटेशन को सही पासवर्ड का उपयोग करके लोड किया जाना चाहिए।
            यदि प्रेजेंटेशन एन्क्रिप्टेड नहीं है तो प्रॉपर्टी मान हमेशा अनदेखा किया जाता है।
            यदि एन्क्रिप्टेड फ़ाइल के दस्तावेज़ प्रॉपर्टीज़ सार्वजनिक नहीं हैं और प्रॉपर्टी मान true है तो दस्तावेज़ प्रॉपर्टीज़ लोड नहीं की जा सकतीं और अपवाद फेंका जाएगा।
            पढ़ने-लिखने योग्य **bool**.

### परिभाषा:
```python
@property
def only_load_document_properties(self):
    ...

@only_load_document_properties.setter
def only_load_document_properties(self, value):
    ...
```

### संदर्भ
* क्लास [`ILoadOptions`](/slides/python-net/hi/aspose.slides/iloadoptions)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)