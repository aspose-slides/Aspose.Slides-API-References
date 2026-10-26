---
title: QueueUserWorkItem()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: काम को कतार में जोड़ता है।
type: docs
weight: 1
url: /hi/system.threading/threadpoolimpl/queueuserworkitem/
---
## ThreadPoolImpl::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) विधि


काम को कतार में जोड़ता है।

```cpp
bool System::Threading::ThreadPoolImpl::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```


### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | चलाने के लिए कॉलबैक फ़ंक्शन। |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | कॉलबैक फ़ंक्शन तर्क। |

### रिटर्न मान

हमेशा true लौटाता है।

## संबंधित देखें

* टाइपडिफ [WaitCallback](../../waitcallback/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [Object](../../../system/object/)
* क्लास [ThreadPoolImpl](../)
* नेमस्पेस [System::Threading](../../)
* लाइब्रेरी [Aspose.Slides](../../../)