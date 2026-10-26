---
title: IOControl()
second_title: Aspose.Slides for C++ API संदर्भ
description: सॉकेट के लिए निम्न-स्तरीय ऑपरेटिंग मोड सेट करता है।
type: docs
weight: 703
url: /hi/system.net.sockets/socket/iocontrol/
---
## Socket::IOControl(int32_t, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) विधि

सॉकेट के लिए निम्न-स्तरीय ऑपरेटिंग मोड सेट करता है।

```cpp
int32_t System::Net::Sockets::Socket::IOControl(int32_t ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| ioControlCode | **int32_t** | प्रदर्शन करने के लिए ऑपरेशन का नियंत्रण कोड। |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | इनपुट डेटा रखने वाला बाइट एरे। |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | आउटपुट डेटा रखने वाला बाइट एरे। |

### रिटर्न वैल्यू

**optionOutValue** पैरामीटर में बाइट्स की संख्या।

## Socket::IOControl(IOControlCode, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) विधि

सॉकेट के लिए निम्न-स्तरीय ऑपरेटिंग मोड सेट करता है।

```cpp
int32_t System::Net::Sockets::Socket::IOControl(IOControlCode ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| ioControlCode | [IOControlCode](../../iocontrolcode/) | प्रदर्शन करने के लिए ऑपरेशन का नियंत्रण कोड। |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | इनपुट डेटा रखने वाला बाइट एरे। |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | आउटपुट डेटा रखने वाला बाइट एरे। |

### रिटर्न वैल्यू

**optionOutValue** पैरामीटर में बाइट्स की संख्या।

## संबंधित देखें

* एन्यूम [IOControlCode](../../iocontrolcode/)
* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [Socket](../)
* नेमस्पेस [System::Net::Sockets](../../)
* लाइब्रेरी [Aspose.Slides](../../../)