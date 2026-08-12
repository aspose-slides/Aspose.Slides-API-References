---
title: Enter()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट वस्तु पर एक विशिष्ट लॉक प्राप्त करता है।
type: docs
weight: 1
url: /hi/system.threading/monitor/enter/
---
## Monitor::Enter(const SharedPtr\<Object\>\&) मेथड

एक विशिष्ट Object पर विशिष्ट लॉक प्राप्त करता है।

```cpp
static void System::Threading::Monitor::Enter(const SharedPtr<Object> &obj)
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | वह Object जिस पर मॉनिटर लॉक प्राप्त किया जाना है। |

## Monitor::Enter(const System::SharedPtr\<Object\>\&, bool\&) मेथड

निर्दिष्ट Object पर एक विशिष्ट लॉक प्राप्त करता है, और यह एटॉमिक रूप से एक मान सेट करता है जो यह दर्शाता है कि लॉक लिया गया है या नहीं।

```cpp
static void System::Threading::Monitor::Enter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [Object](../../../system/object/)
* क्लास [Monitor](../)
* नेमस्पेस [System::Threading](../../)
* लाइब्रेरी [Aspose.Slides](../../../)