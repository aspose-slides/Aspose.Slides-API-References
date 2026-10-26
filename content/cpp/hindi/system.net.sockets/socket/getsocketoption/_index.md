---
title: GetSocketOption()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट विकल्प नाम के अनुरूप मान लौटाता है।
type: docs
weight: 729
url: /hi/system.net.sockets/socket/getsocketoption/
---
## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName) विधि

निर्दिष्ट विकल्प नाम के अनुरूप मान लौटाता है।

```cpp
System::SharedPtr<Object> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | सॉकेट विकल्प स्तर। |
| optionName | [SocketOptionName](../../socketoptionname/) | विकल्प नाम। |

### वापसी मान

निर्दिष्ट विकल्प नाम के अनुरूप मान लौटाता है।

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, System::ArrayPtr\<uint8_t\>) विधि

निर्दिष्ट विकल्प नाम के अनुरूप मान प्राप्त करता है।

```cpp
void System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, System::ArrayPtr<uint8_t> optionValue)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | सॉकेट विकल्प स्तर। |
| optionName | [SocketOptionName](../../socketoptionname/) | विकल्प नाम। |
| optionValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | आउटपुट पैरामीटर जहाँ अनुरूप मान असाइन किया जाएगा। |

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, int32_t) विधि

निर्दिष्ट विकल्प नाम के अनुरूप मान लौटाता है।

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, int32_t optionLength)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | सॉकेट विकल्प स्तर। |
| optionName | [SocketOptionName](../../socketoptionname/) | विकल्प नाम। |
| optionLength | **int32_t** | विकल्प लंबाई। |

### वापसी मान

निर्दिष्ट विकल्प नाम के अनुरूप मान लौटाता है।

## देखें

* एन्युम [SocketOptionLevel](../../socketoptionlevel/)
* एन्युम [SocketOptionName](../../socketoptionname/)
* टाइपडेफ [SharedPtr](../../../system/sharedptr/)
* टाइपडेफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [Object](../../../system/object/)
* क्लास [Socket](../)
* नेमस्पेस [System::Net::Sockets](../../)
* लाइब्रेरी [Aspose.Slides](../../../)