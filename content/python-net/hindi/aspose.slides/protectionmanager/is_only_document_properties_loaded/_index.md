---
title: is_only_document_properties_loaded property
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/protectionmanager/is_only_document_properties_loaded/
weight: 90
---
## is_only_document_properties_loaded प्रॉपर्टी
यह प्रॉपर्टी समझ में आती है, यदि प्रेजेंटेशन फ़ाइल पासवर्ड-सुरक्षित है और डॉक्यूमेंट 
            प्रॉपर्टीज़ इस फ़ाइल की सार्वजनिक हैं।
true का मान यह दर्शाता है कि केवल डॉक्यूमेंट प्रॉपर्टीज़ एन्क्रिप्टेड 
            प्रेजेंटेशन फ़ाइल से बिना पासवर्ड उपयोग के लोड की जाती हैं।
false का मान यह दर्शाता है कि पूरा एन्क्रिप्टेड प्रेजेंटेशन सही 
            पासवर्ड के उपयोग से लोड होता है, केवल डॉक्यूमेंट प्रॉपर्टीज़ नहीं लोड होते।
यदि प्रेजेंटेशन एन्क्रिप्टेड नहीं है तो प्रॉपर्टी मान हमेशा false रहता है।
यदि एन्क्रिप्टेड फ़ाइल की डॉक्यूमेंट प्रॉपर्टीज़ सार्वजनिक नहीं हैं तो प्रॉपर्टी मान हमेशा false रहता है।
यदि Presentation.EncryptDocumentProperties true है तो IsOnlyDocumentPropertiesLoaded 
            प्रॉपर्टी मान हमेशा false रहता है।
केवल-पढ़ने योग्य **bool**।

### परिभाषा:
```python
@property
def is_only_document_properties_loaded(self):
    ...
```


### संबंधित देखें
* क्लास [`ProtectionManager`](/slides/python-net/hi/aspose.slides/protectionmanager)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)