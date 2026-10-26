---
title: only_load_document_properties property
second_title: Aspose.Slides Python के लिए .NET के माध्यम से API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/loadoptions/only_load_document_properties/
weight: 110
---
## only_load_document_properties प्रॉपर्टी
यह प्रॉपर्टी तब समझ में आती है जब प्रेजेंटेशन फ़ाइल पासवर्ड संरक्षित हो।
            true मान का अर्थ है कि केवल दस्तावेज़ प्रॉपर्टी को एन्क्रिप्टेड 
            प्रेजेंटेशन फ़ाइल से लोड किया जाना चाहिए और पासवर्ड को अनदेखा किया जाना चाहिए।
            false मान का अर्थ है कि सही पासवर्ड के उपयोग से पूरी एन्क्रिप्टेड प्रेजेंटेशन को लोड किया जाना चाहिए।
            यदि प्रेजेंटेशन एन्क्रिप्टेड नहीं है तो प्रॉपर्टी मान हमेशा अनदेखा किया जाता है।
            यदि एन्क्रिप्टेड फ़ाइल की दस्तावेज़ प्रॉपर्टी सार्वजनिक नहीं हैं और प्रॉपर्टी मान true है तो
            दस्तावेज़ प्रॉपर्टी लोड नहीं की जा सकेगी और अपवाद उत्पन्न होगा।
            पढ़ें/लिखें **bool**।

### Definition:
```python
@property
def only_load_document_properties(self):
    ...

@only_load_document_properties.setter
def only_load_document_properties(self, value):
    ...
```


### देखें भी
* क्लास [`LoadOptions`](/slides/python-net/hi/aspose.slides/loadoptions)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)