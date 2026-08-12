---
title: ReceiveFrom()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट अंतबिंदु से डेटा प्राप्त करता है और उसे निर्दिष्ट बाइट एरे में लिखता है।
type: docs
weight: 690
url: /hi/system.net.sockets/socket/receivefrom/
---
## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) मेथड


निर्दिष्ट एंडपॉइंट से डेटा प्राप्त करता है और उसे निर्दिष्ट बाइट ऐरे में लिखता है।

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | प्राप्त डेटा को सौंपे जाने वाला बाइट ऐरे। |
| offset | **int32_t** | निर्दिष्ट ऐरे में बाइट्स में ऑफसेट। |
| size | **int32_t** | ऑफ़सेट इंडेक्स से निर्दिष्ट बाइट ऐरे को सौंपे जाने वाले प्राप्त करने के बाइट्स की संख्या। |
| socketFlags | [SocketFlags](../../socketflags/) | प्राप्ति व्यवहार। |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | रिमोट एंडपॉइंट। |

### रिटर्न वैल्यू

प्राप्त बाइट्स की संख्या।

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) मेथड


निर्दिष्ट एंडपॉइंट से डेटा प्राप्त करता है और उसे निर्दिष्ट बाइट ऐरे में लिखता है।

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | प्राप्त डेटा को सौंपे जाने वाला बाइट ऐरे। |
| offset | **int32_t** | निर्दिष्ट ऐरे में बाइट्स में ऑफसेट। |
| size | **int32_t** | ऑफ़सेट इंडेक्स से निर्दिष्ट बाइट ऐरे को सौंपे जाने वाले प्राप्त करने के बाइट्स की संख्या। |
| socketFlags | [SocketFlags](../../socketflags/) | प्राप्ति व्यवहार। |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | रिमोट एंडपॉइंट। |

### रिटर्न वैल्यू

प्राप्त बाइट्स की संख्या।

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) मेथड


निर्दिष्ट एंडपॉइंट से डेटा प्राप्त करता है और उसे निर्दिष्ट बाइट ऐरे में लिखता है।

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | प्राप्त डेटा को सौंपे जाने वाला बाइट ऐरे। |
| offset | **int32_t** | निर्दिष्ट ऐरे में बाइट्स में ऑफसेट। |
| size | **int32_t** | ऑफ़सेट इंडेक्स से निर्दिष्ट बाइट ऐरे को सौंपे जाने वाले प्राप्त करने के बाइट्स की संख्या। |
| socketFlags | [SocketFlags](../../socketflags/) | प्राप्ति व्यवहार। |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | रिमोट एंडपॉइंट। |

### रिटर्न वैल्यू

प्राप्त बाइट्स की संख्या।

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) मेथड


निर्दिष्ट एंडपॉइंट से डेटा प्राप्त करता है और उसे निर्दिष्ट बाइट ऐरे में लिखता है।

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | प्राप्त डेटा को सौंपे जाने वाला बाइट ऐरे। |
| size | **int32_t** | ऑफ़सेट इंडेक्स से निर्दिष्ट बाइट ऐरे को सौंपे जाने वाले प्राप्त करने के बाइट्स की संख्या। |
| socketFlags | [SocketFlags](../../socketflags/) | प्राप्ति व्यवहार। |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | रिमोट एंडपॉइंट। |

### रिटर्न वैल्यू

प्राप्त बाइट्स की संख्या।

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) मेथड


निर्दिष्ट एंडपॉइंट से डेटा प्राप्त करता है और उसे निर्दिष्ट बाइट ऐरे में लिखता है।

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | प्राप्त डेटा को सौंपे जाने वाला बाइट ऐरे। |
| size | **int32_t** | ऑफ़सेट इंडेक्स से निर्दिष्ट बाइट ऐरे को सौंपे जाने वाले प्राप्त करने के बाइट्स की संख्या। |
| socketFlags | [SocketFlags](../../socketflags/) | प्राप्ति व्यवहार। |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | रिमोट एंडपॉइंट। |

### रिटर्न वैल्यू

प्राप्त बाइट्स की संख्या।

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) मेथड


निर्दिष्ट एंडपॉइंट से डेटा प्राप्त करता है और उसे निर्दिष्ट बाइट ऐरे में लिखता है।

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | प्राप्त डेटा को सौंपे जाने वाला बाइट ऐरे। |
| size | **int32_t** | ऑफ़सेट इंडेक्स से निर्दिष्ट बाइट ऐरे को सौंपे जाने वाले प्राप्त करने के बाइट्स की संख्या। |
| socketFlags | [SocketFlags](../../socketflags/) | प्राप्ति व्यवहार। |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | रिमोट एंडपॉइंट। |

### रिटर्न वैल्यू

प्राप्त बाइट्स की संख्या।

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) मेथड


निर्दिष्ट एंडपॉइंट से डेटा प्राप्त करता है और उसे निर्दिष्ट बाइट ऐरे में लिखता है।

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | प्राप्त डेटा को सौंपे जाने वाला बाइट ऐरे। |
| socketFlags | [SocketFlags](../../socketflags/) | प्राप्ति व्यवहार। |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | रिमोट एंडपॉइंट। |

### रिटर्न वैल्यू

प्राप्त बाइट्स की संख्या।

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) मेथड


निर्दिष्ट एंडपॉइंट से डेटा प्राप्त करता है और उसे निर्दिष्ट बाइट ऐरे में लिखता है।

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | प्राप्त डेटा को सौंपे जाने वाला बाइट ऐरे। |
| socketFlags | [SocketFlags](../../socketflags/) | प्राप्ति व्यवहार। |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | रिमोट एंडपॉइंट। |

### रिटर्न वैल्यू

प्राप्त बाइट्स की संख्या।

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) मेथड


निर्दिष्ट एंडपॉइंट से डेटा प्राप्त करता है और उसे निर्दिष्ट बाइट ऐरे में लिखता है।

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | प्राप्त डेटा को सौंपे जाने वाला बाइट ऐरे। |
| socketFlags | [SocketFlags](../../socketflags/) | प्राप्ति व्यवहार। |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | रिमोट एंडपॉइंट। |

### रिटर्न वैल्यू

प्राप्त बाइट्स की संख्या।

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) मेथड


निर्दिष्ट एंडपॉइंट से डेटा प्राप्त करता है और उसे निर्दिष्ट बाइट ऐरे में लिखता है।

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```


### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | प्राप्त डेटा को सौंपे जाने वाला बाइट ऐरे। |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | रिमोट एंडपॉइंट। |

### रिटर्न वैल्यू

प्राप्त बाइट्स की संख्या।

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) मेथड


निर्दिष्ट एंडपॉइंट से डेटा प्राप्त करता है और उसे निर्दिष्ट बाइट ऐरे में लिखता है।

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```


### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | प्राप्त डेटा को सौंपे जाने वाला बाइट ऐरे। |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | रिमोट एंडपॉइंट। |

### रिटर्न वैल्यू

प्राप्त बाइट्स की संख्या।

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>\&) मेथड


निर्दिष्ट एंडपॉइंट से डेटा प्राप्त करता है और उसे निर्दिष्ट बाइट ऐरे में लिखता है।

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> &remoteEP)
```


### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | प्राप्त डेटा को सौंपे जाने वाला बाइट ऐरे। |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | रिमोट एंडपॉइंट। |

### रिटर्न वैल्यू

प्राप्त बाइट्स की संख्या।

## देखें

* एन्यूम [SocketFlags](../../socketflags/)
* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [EndPoint](../../../system.net/endpoint/)
* क्लास [Socket](../)
* नामस्थान [System::Net::Sockets](../../)
* लाइब्रेरी [Aspose.Slides](../../../)