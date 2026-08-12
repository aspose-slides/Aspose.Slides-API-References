---
title: ReceiveMessageFrom()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट एंडपॉइंट से डेटा प्राप्त करता है और इसे निर्दिष्ट बाइट एरे में लिखता है।
type: docs
weight: 677
url: /hi/system.net.sockets/socket/receivemessagefrom/
---
## Socket::ReceiveMessageFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) method


निर्दिष्ट एंडपॉइंट से डेटा प्राप्त करता है और इसे निर्दिष्ट बाइट एरे में लिखता है।

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | प्राप्त डेटा जहाँ असाइन किया जाएगा वह बाइट एरे। |
| offset | **int32_t** | निर्दिष्ट एरे में बाइट्स में ऑफ़सेट। |
| size | **int32_t** | निर्दिष्ट बाइट एरे को 'offset' इंडेक्स से असाइन किए जाने वाले बाइट्स की संख्या। |
| socketFlags | [SocketFlags](../../socketflags/)\& | प्राप्ति व्यवहार। |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | रिमोट एंडपॉइंट। |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | पैकेट के बारे में जानकारी जहाँ असाइन की जाएगी वह आउटपुट पैरामीटर। |

### रिटर्न मान

प्राप्त बाइट्स की संख्या।

## Socket::ReceiveMessageFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) method


निर्दिष्ट एंडपॉइंट से डेटा प्राप्त करता है और इसे निर्दिष्ट बाइट एरे में लिखता है।

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | प्राप्त डेटा जहाँ असाइन किया जाएगा वह बाइट एरे। |
| offset | **int32_t** | निर्दिष्ट एरे में बाइट्स में ऑफ़सेट। |
| size | **int32_t** | निर्दिष्ट बाइट एरे को 'offset' इंडेक्स से असाइन किए जाने वाले बाइट्स की संख्या। |
| socketFlags | [SocketFlags](../../socketflags/)\& | प्राप्ति व्यवहार। |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | रिमोट एंडपॉइंट। |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | पैकेट के बारे में जानकारी जहाँ असाइन की जाएगी वह आउटपुट पैरामीटर। |

### रिटर्न मान

प्राप्त बाइट्स की संख्या।

## Socket::ReceiveMessageFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) method


निर्दिष्ट एंडपॉइंट से डेटा प्राप्त करता है और इसे निर्दिष्ट बाइट एरे में लिखता है।

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | प्राप्त डेटा जहाँ असाइन किया जाएगा वह बाइट एरे। |
| offset | **int32_t** | निर्दिष्ट एरे में बाइट्स में ऑफ़सेट। |
| size | **int32_t** | निर्दिष्ट बाइट एरे को 'offset' इंडेक्स से असाइन किए जाने वाले बाइट्स की संख्या। |
| socketFlags | [SocketFlags](../../socketflags/)\& | प्राप्ति व्यवहार। |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | रिमोट एंडपॉइंट। |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | पैकेट के बारे में जानकारी जहाँ असाइन की जाएगी वह आउटपुट पैरामीटर। |

### रिटर्न मान

प्राप्त बाइट्स की संख्या।

## संबंधित देखें

* एन्युम [SocketFlags](../../socketflags/)
* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [EndPoint](../../../system.net/endpoint/)
* क्लास [IPPacketInformation](../../ippacketinformation/)
* क्लास [Socket](../)
* नेमस्पेस [System::Net::Sockets](../../)
* लाइब्रेरी [Aspose.Slides](../../../)