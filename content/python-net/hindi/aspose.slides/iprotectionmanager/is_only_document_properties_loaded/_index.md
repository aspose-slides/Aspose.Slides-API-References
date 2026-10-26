---
title: is_only_document_properties_loaded property
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/iprotectionmanager/is_only_document_properties_loaded/
weight: 90
---
## is_only_document_properties_loaded गुण
यह प्रॉपर्टी तब समझ में आती है, जब प्रस्तुति फ़ाइल पासवर्ड द्वारा संरक्षित हो और इस फ़ाइल के दस्तावेज़ गुण सार्वजनिक हों।
true का मान मतलब केवल दस्तावेज़ गुण एन्क्रिप्टेड प्रस्तुति फ़ाइल से पासवर्ड के बिना लोड होते हैं।
false का मान मतलब पूरी एन्क्रिप्टेड प्रस्तुति सही पासवर्ड के उपयोग से लोड होती है, केवल दस्तावेज़ गुण नहीं लोड होते।
यदि प्रस्तुति एन्क्रिप्टेड नहीं है तो प्रॉपर्टी का मान हमेशा false रहता है।
यदि एन्क्रिप्टेड फ़ाइल के दस्तावेज़ गुण सार्वजनिक नहीं हैं तो प्रॉपर्टी का मान हमेशा false रहता है।
यदि PresentationEx.EncryptDocumentProperties true है तो IsOnlyDocumentPropertiesLoaded प्रॉपर्टी का मान हमेशा false रहता है।
केवल-पढ़ने योग्य **bool**।

### परिभाषा:
```python
@property
def is_only_document_properties_loaded(self):
    ...
```

### देखें भी
* क्लास [`IProtectionManager`](/slides/python-net/hi/aspose.slides/iprotectionmanager)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)