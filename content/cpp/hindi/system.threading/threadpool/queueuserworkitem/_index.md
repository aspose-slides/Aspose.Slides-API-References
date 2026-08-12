---
title: QueueUserWorkItem()
second_title: Aspose.Slides for C++ API संदर्भ
description: कार्य आइटम को कतार में रखता है जिसमें कोई पैरामीटर न रखने वाला कॉलबैक मौजूद है।
type: docs
weight: 14
url: /hi/system.threading/threadpool/queueuserworkitem/
---
## ThreadPool::QueueUserWorkItem(WaitCallback) विधि

कार्य आइटम को कतार में रखता है जिसमें कोई पैरामीटर न रखने वाला कॉलबैक मौजूद है।

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | जॉब के रूप में उपयोग किए जाने वाला कॉलबैक फ़ंक्शन। |

### रिटर्न वैल्यू

हमेशा true लौटाता है।

## ThreadPool::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) विधि

कार्य आइटम को कतार में रखता है जिसमें कोई पैरामीटर न रखने वाला कॉलबैक मौजूद है।

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | जॉब के रूप में उपयोग किए जाने वाला कॉलबैक फ़ंक्शन। |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | जॉब फ़ंक्शन पैरामीटर। |

### रिटर्न वैल्यू

हमेशा true लौटाता है।

## और देखें

* Typedef [WaitCallback](../../waitcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [ThreadPool](../)
* क्लास [Object](../../../system/object/)
* नेमस्पेस [System::Threading](../../)
* Library [Aspose.Slides](../../../)