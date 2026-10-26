---
title: get_Current()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: वर्तमान थ्रेड के लिए सिंक्रनाइज़ेशन कॉन्टेक्स्ट प्राप्त करता है।
type: docs
weight: 40
url: /hi/system.threading/synchronizationcontext/get_current/
---
## SynchronizationContext::get_Current() विधि

वर्तमान थ्रेड के लिए सिंक्रनाइज़ेशन कॉन्टेक्स्ट प्राप्त करता है।

```cpp
static const SharedPtr<SynchronizationContext> & System::Threading::SynchronizationContext::get_Current()
```

### रिटर्न मान

SharedPtr<SynchronizationContext> वर्तमान थ्रेड के सिंक्रनाइज़ेशन कॉन्टेक्स्ट की एक साझा पॉइंटर।

## टिप्पणी

यदि वर्तमान थ्रेड के लिए कोई सिंक्रनाइज़ेशन कॉन्टेक्स्ट सेट नहीं किया गया है तो null लौटाता है।

## संदर्भ

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [SynchronizationContext](../)
* नामस्थान [System::Threading](../../)
* Library [Aspose.Slides](../../../)