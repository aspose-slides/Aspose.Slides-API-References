---
title: SetSocketOption()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्दिष्ट सॉकेट विकल्प को निर्दिष्ट मान पर सेट करता है।
type: docs
weight: 716
url: /hi/system.net.sockets/socket/setsocketoption/
---
## Socket::SetSocketOption(SocketOptionLevel, SocketOptionName, int32_t) विधि

निर्दिष्ट सॉकेट विकल्प को निर्दिष्ट मान पर सेट करता है।

```cpp
void System::Net::Sockets::Socket::SetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, int32_t optionValue)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | सॉकेट विकल्प स्तर। |
| optionName | [SocketOptionName](../../socketoptionname/) | विकल्प का वह नाम जिसे अद्यतन करना आवश्यक है। |
| optionValue | **int32_t** | निर्दिष्ट विकल्प के लिए सेट किया जाना आवश्यक मान। |

## Socket::SetSocketOption(SocketOptionLevel, SocketOptionName, System::ArrayPtr\<uint8_t\>) विधि

निर्दिष्ट सॉकेट विकल्प को निर्दिष्ट मान पर सेट करता है।

```cpp
void System::Net::Sockets::Socket::SetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, System::ArrayPtr<uint8_t> optionValue)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | सॉकेट विकल्प स्तर। |
| optionName | [SocketOptionName](../../socketoptionname/) | विकल्प का वह नाम जिसे अद्यतन करना आवश्यक है। |
| optionValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | निर्दिष्ट विकल्प के लिए सेट किया जाना आवश्यक मान। |

## Socket::SetSocketOption(SocketOptionLevel, SocketOptionName, bool) विधि

निर्दिष्ट सॉकेट विकल्प को निर्दिष्ट मान पर सेट करता है।

```cpp
void System::Net::Sockets::Socket::SetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, bool optionValue)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | सॉकेट विकल्प स्तर। |
| optionName | [SocketOptionName](../../socketoptionname/) | विकल्प का वह नाम जिसे अद्यतन करना आवश्यक है। |
| optionValue | **bool** | निर्दिष्ट विकल्प के लिए सेट किया जाना आवश्यक मान। |

## Socket::SetSocketOption(SocketOptionLevel, SocketOptionName, System::SharedPtr\<Object\>) विधि

निर्दिष्ट सॉकेट विकल्प को निर्दिष्ट मान पर सेट करता है।

```cpp
void System::Net::Sockets::Socket::SetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, System::SharedPtr<Object> optionValue)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | सॉकेट विकल्प स्तर। |
| optionName | [SocketOptionName](../../socketoptionname/) | विकल्प का वह नाम जिसे अद्यतन करना आवश्यक है। |
| optionValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | निर्दिष्ट विकल्प के लिए सेट किया जाना आवश्यक मान। |

## देखें

* Enum [SocketOptionLevel](../../socketoptionlevel/)
* Enum [SocketOptionName](../../socketoptionname/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Socket](../)
* Class [Object](../../../system/object/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)