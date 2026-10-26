---
title: NetworkStream()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक नया उदाहरण बनाता है।
type: docs
weight: 170
url: /hi/system.net.sockets/networkstream/networkstream/
---
## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>) कंस्ट्रक्टर

एक नया उदाहरण बनाता है।

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | डेटा भेजने और प्राप्त करने के लिए उपयोग किया जाने वाला सॉकेट। |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, System::IO::FileAccess, bool) कंस्ट्रक्टर

एक नया उदाहरण बनाता है।

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, System::IO::FileAccess access, bool ownsSocket)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | डेटा भेजने और प्राप्त करने के लिए उपयोग किया जाने वाला सॉकेट। |
| access | [System::IO::FileAccess](../../../system.io/fileaccess/) | निर्दिष्ट सॉकेट पर इंस्टेंस को दिया गया एक्सेस प्रकार निर्दिष्ट करता है। |
| ownsSocket | **bool** | एक मान जो यह दर्शाता है कि जब मान true हो तो वर्तमान इंस्टेंस निर्दिष्ट सॉकेट का स्वामित्व लेता है। |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, bool) कंस्ट्रक्टर

एक नया उदाहरण बनाता है।

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, bool ownsSocket)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | डेटा भेजने और प्राप्त करने के लिए उपयोग किया जाने वाला सॉकेट। |
| ownsSocket | **bool** | एक मान जो यह दर्शाता है कि जब मान true हो तो वर्तमान इंस्टेंस निर्दिष्ट सॉकेट का स्वामित्व लेता है। |

## संबंधित देखें

* एनम [FileAccess](../../../system.io/fileaccess/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [Socket](../../socket/)
* क्लास [NetworkStream](../)
* नेमस्पेस [System::Net::Sockets](../../)
* लाइब्रेरी [Aspose.Slides](../../../)