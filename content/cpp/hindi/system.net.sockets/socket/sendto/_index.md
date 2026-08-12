---
title: SendTo()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट डेटा को निर्दिष्ट एंडपॉइंट पर भेजता है।
type: docs
weight: 651
url: /hi/system.net.sockets/socket/sendto/
---
## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) मेथड

निर्दिष्ट डेटा को निर्दिष्ट एंडपॉइंट पर भेजता है।

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | भेजे जाने वाला डेटा। |
| offset | **int32_t** | निर्दिष्ट एरे में बाइट्स में ऑफ़सेट। |
| size | **int32_t** | निर्दिष्ट एरे में बाइट्स की संख्या, जो 'offset' पैरामीटर से शुरू होती है। |
| socketFlags | [SocketFlags](../../socketflags/) | भेजने का व्यवहार। |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | रिमोट एंडपॉइंट। |

### वापसी मान

भेजे गए बाइट्स की संख्या।

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) मेथड

निर्दिष्ट डेटा को निर्दिष्ट एंडपॉइंट पर भेजता है।

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | भेजे जाने वाला डेटा। |
| offset | **int32_t** | निर्दिष्ट एरे में बाइट्स में ऑफ़सेट। |
| size | **int32_t** | निर्दिष्ट एरे में बाइट्स की संख्या, जो 'offset' पैरामीटर से शुरू होती है। |
| socketFlags | [SocketFlags](../../socketflags/) | भेजने का व्यवहार। |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | रिमोट एंडपॉइंट। |

### वापसी मान

भेजे गए बाइट्स की संख्या।

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) मेथड

निर्दिष्ट डेटा को निर्दिष्ट एंडपॉइंट पर भेजता है।

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | भेजे जाने वाला डेटा। |
| offset | **int32_t** | निर्दिष्ट एरे में बाइट्स में ऑफ़सेट। |
| size | **int32_t** | निर्दिष्ट एरे में बाइट्स की संख्या, जो 'offset' पैरामीटर से शुरू होती है। |
| socketFlags | [SocketFlags](../../socketflags/) | भेजने का व्यवहार। |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | रिमोट एंडपॉइंट। |

### वापसी मान

भेजे गए बाइट्स की संख्या।

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) मेथड

निर्दिष्ट डेटा को निर्दिष्ट एंडपॉइंट पर भेजता है।

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | भेजे जाने वाला डेटा। |
| size | **int32_t** | निर्दिष्ट एरे में बाइट्स की संख्या। |
| socketFlags | [SocketFlags](../../socketflags/) | भेजने का व्यवहार। |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | रिमोट एंडपॉइंट। |

### वापसी मान

भेजे गए बाइट्स की संख्या।

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) मेथड

निर्दिष्ट डेटा को निर्दिष्ट एंडपॉइंट पर भेजता है।

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | भेजे जाने वाला डेटा। |
| size | **int32_t** | निर्दिष्ट एरे में बाइट्स की संख्या। |
| socketFlags | [SocketFlags](../../socketflags/) | भेजने का व्यवहार। |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | रिमोट एंडपॉइंट। |

### वापसी मान

भेजे गए बाइट्स की संख्या।

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) मेथड

निर्दिष्ट डेटा को निर्दिष्ट एंडपॉइंट पर भेजता है।

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | भेजे जाने वाला डेटा। |
| size | **int32_t** | निर्दिष्ट एरे में बाइट्स की संख्या। |
| socketFlags | [SocketFlags](../../socketflags/) | भेजने का व्यवहार। |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | रिमोट एंडपॉइंट। |

### वापसी मान

भेजे गए बाइट्स की संख्या।

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) मेथड

निर्दिष्ट डेटा को निर्दिष्ट एंडपॉइंट पर भेजता है।

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | भेजे जाने वाला डेटा। |
| socketFlags | [SocketFlags](../../socketflags/) | भेजने का व्यवहार। |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | रिमोट एंडपॉइंट। |

### वापसी मान

भेजे गए बाइट्स की संख्या।

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) मेथड

निर्दिष्ट डेटा को निर्दिष्ट एंडपॉइंट पर भेजता है।

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | भेजे जाने वाला डेटा। |
| socketFlags | [SocketFlags](../../socketflags/) | भेजने का व्यवहार। |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | रिमोट एंडपॉइंट। |

### वापसी मान

भेजे गए बाइट्स की संख्या।

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags, System::SharedPtr\<EndPoint\>) मेथड

निर्दिष्ट डेटा को निर्दिष्ट एंडपॉइंट पर भेजता है।

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | भेजे जाने वाला डेटा। |
| socketFlags | [SocketFlags](../../socketflags/) | भेजने का व्यवहार। |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | रिमोट एंडपॉइंट। |

### वापसी मान

भेजे गए बाइट्स की संख्या।

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>) मेथड

निर्दिष्ट डेटा को निर्दिष्ट एंडपॉइंट पर भेजता है।

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | भेजे जाने वाला डेटा। |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | रिमोट एंडपॉइंट। |

### वापसी मान

भेजे गए बाइट्स की संख्या।

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>) मेथड

निर्दिष्ट डेटा को निर्दिष्ट एंडपॉइंट पर भेजता है।

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | भेजे जाने वाला डेटा। |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | रिमोट एंडपॉइंट। |

### वापसी मान

भेजे गए बाइट्स की संख्या।

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>) मेथड

निर्दिष्ट डेटा को निर्दिष्ट एंडपॉइंट पर भेजता है।

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> remoteEP)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | भेजे जाने वाला डेटा। |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | रिमोट एंडपॉइंट। |

### वापसी मान

भेजे गए बाइट्स की संख्या।

## संबंधित देखें

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)