---
title: SetSynchronizationContext()
second_title: C++ के लिए Aspose.Slides API रेफ़रेंस
description: वर्तमान थ्रेड के लिए सिंक्रोनाइज़ेशन कॉन्टेक्स्ट को सेट करता है।
type: docs
weight: 53
url: /hi/system.threading/synchronizationcontext/setsynchronizationcontext/
---
## SynchronizationContext::SetSynchronizationContext(const SharedPtr\<SynchronizationContext\>\&) विधि

वर्तमान थ्रेड के लिए सिंक्रोनाइज़ेशन कॉन्टेक्स्ट को सेट करता है।

```cpp
static void System::Threading::SynchronizationContext::SetSynchronizationContext(const SharedPtr<SynchronizationContext> &syncContext)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| syncContext | const [SharedPtr](../../../system/sharedptr/)\<[SynchronizationContext](../)\>\& | वर्तमान थ्रेड के लिए सेट करने हेतु सिंक्रोनाइज़ेशन कॉन्टेक्स्ट। |

## टिप्पणी

nullptr पास करने से वर्तमान थ्रेड के लिए सिंक्रोनाइज़ेशन कॉन्टेक्स्ट साफ़ हो जाएगा। 

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [SynchronizationContext](../)
* नेमस्पेस [System::Threading](../../)
* लाइब्रेरी [Aspose.Slides](../../../)