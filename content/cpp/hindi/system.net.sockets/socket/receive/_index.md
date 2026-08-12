---
title: Receive()
second_title: Aspose.Slides for C++ API संदर्भ
description: सॉकेट से डेटा प्राप्त करता है और इसे निर्दिष्ट बाइट एरे में लिखता है।
type: docs
weight: 664
url: /hi/system.net.sockets/socket/receive/
---
## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) मेथड


सॉकेट से डेटा प्राप्त करता है और इसे निर्दिष्ट बाइट एरे में लिखता है।

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | वह बाइट एरे जहाँ प्राप्त डेटा असाइन किया जाएगा। |
| size | **int32_t** | प्राप्त करने के लिए बाइट्स की संख्या। |
| socketFlags | [SocketFlags](../../socketflags/) | प्राप्ति व्यवहार। |

### वापसी मान

प्राप्त बाइट्स की संख्या।

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) मेथड


सॉकेट से डेटा प्राप्त करता है और इसे निर्दिष्ट बाइट एरे में लिखता है।

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | वह बाइट एरे जहाँ प्राप्त डेटा असाइन किया जाएगा। |
| size | **int32_t** | प्राप्त करने के लिए बाइट्स की संख्या। |
| socketFlags | [SocketFlags](../../socketflags/) | प्राप्ति व्यवहार। |

### वापसी मान

प्राप्त बाइट्स की संख्या।

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) मेथड


सॉकेट से डेटा प्राप्त करता है और इसे निर्दिष्ट बाइट एरे में लिखता है।

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | वह बाइट एरे जहाँ प्राप्त डेटा असाइन किया जाएगा। |
| size | **int32_t** | प्राप्त करने के लिए बाइट्स की संख्या। |
| socketFlags | [SocketFlags](../../socketflags/) | प्राप्ति व्यवहार। |

### वापसी मान

प्राप्त बाइट्स की संख्या।

## Socket::Receive(System::ArrayPtr\<uint8_t\>, SocketFlags) मेथड


सॉकेट से डेटा प्राप्त करता है और इसे निर्दिष्ट बाइट एरे में लिखता है।

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | वह बाइट एरे जहाँ प्राप्त डेटा असाइन किया जाएगा। |
| socketFlags | [SocketFlags](../../socketflags/) | प्राप्ति व्यवहार। |

### वापसी मान

प्राप्त बाइट्स की संख्या।

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, SocketFlags) मेथड


सॉकेट से डेटा प्राप्त करता है और इसे निर्दिष्ट बाइट एरे में लिखता है।

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | वह बाइट एरे जहाँ प्राप्त डेटा असाइन किया जाएगा। |
| socketFlags | [SocketFlags](../../socketflags/) | प्राप्ति व्यवहार। |

### वापसी मान

प्राप्त बाइट्स की संख्या।

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) मेथड


सॉकेट से डेटा प्राप्त करता है और इसे निर्दिष्ट बाइट एरे में लिखता है।

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | वह बाइट एरे जहाँ प्राप्त डेटा असाइन किया जाएगा। |
| socketFlags | [SocketFlags](../../socketflags/) | प्राप्ति व्यवहार। |

### वापसी मान

प्राप्त बाइट्स की संख्या।

## Socket::Receive(System::ArrayPtr\<uint8_t\>) मेथड


सॉकेट से डेटा प्राप्त करता है और इसे निर्दिष्ट बाइट एरे में लिखता है।

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | वह बाइट एरे जहाँ प्राप्त डेटा असाइन किया जाएगा। |

### वापसी मान

प्राप्त बाइट्स की संख्या।

## Socket::Receive(System::Details::ArrayView\<uint8_t\>) मेथड


सॉकेट से डेटा प्राप्त करता है और इसे निर्दिष्ट बाइट एरे में लिखता है।

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | वह बाइट एरे जहाँ प्राप्त डेटा असाइन किया जाएगा। |

### वापसी मान

प्राप्त बाइट्स की संख्या।

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&) मेथड


सॉकेट से डेटा प्राप्त करता है और इसे निर्दिष्ट बाइट एरे में लिखता है।

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | वह बाइट एरे जहाँ प्राप्त डेटा असाइन किया जाएगा। |

### वापसी मान

प्राप्त बाइट्स की संख्या।

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) मेथड


सॉकेट से डेटा प्राप्त करता है और इसे निर्दिष्ट बाइट एरे में लिखता है।

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | वह बाइट एरे जहाँ प्राप्त डेटा असाइन किया जाएगा। |
| offset | **int32_t** | निर्दिष्ट एरे में बाइट में ऑफ़सेट। |
| size | **int32_t** | ‘offset’ इंडेक्स से निर्दिष्ट बाइट एरे में असाइन किए जाने वाले बाइट्स की संख्या। |
| socketFlags | [SocketFlags](../../socketflags/) | प्राप्ति व्यवहार। |

### वापसी मान

प्राप्त बाइट्स की संख्या।

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) मेथड


सॉकेट से डेटा प्राप्त करता है और इसे निर्दिष्ट बाइट एरे में लिखता है।

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | वह बाइट एरे जहाँ प्राप्त डेटा असाइन किया जाएगा। |
| offset | **int32_t** | निर्दिष्ट एरे में बाइट में ऑफ़सेट। |
| size | **int32_t** | ‘offset’ इंडेक्स से निर्दिष्ट बाइट एरे में असाइन किए जाने वाले बाइट्स की संख्या। |
| socketFlags | [SocketFlags](../../socketflags/) | प्राप्ति व्यवहार। |

### वापसी मान

प्राप्त बाइट्स की संख्या।

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) मेथड


सॉकेट से डेटा प्राप्त करता है और इसे निर्दिष्ट बाइट एरे में लिखता है।

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | वह बाइट एरे जहाँ प्राप्त डेटा असाइन किया जाएगा। |
| offset | **int32_t** | निर्दिष्ट एरे में बाइट में ऑफ़सेट। |
| size | **int32_t** | ‘offset’ इंडेक्स से निर्दिष्ट बाइट एरे में असाइन किए जाने वाले बाइट्स की संख्या। |
| socketFlags | [SocketFlags](../../socketflags/) | प्राप्ति व्यवहार। |

### वापसी मान

प्राप्त बाइट्स की संख्या।

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) मेथड


सॉकेट से डेटा प्राप्त करता है और इसे निर्दिष्ट बाइट एरे में लिखता है।

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | वह बाइट एरे जहाँ प्राप्त डेटा असाइन किया जाएगा। |
| offset | **int32_t** | निर्दिष्ट एरे में बाइट में ऑफ़सेट। |
| size | **int32_t** | ‘offset’ इंडेक्स से निर्दिष्ट बाइट एरे में असाइन किए जाने वाले बाइट्स की संख्या। |
| socketFlags | [SocketFlags](../../socketflags/) | प्राप्ति व्यवहार। |
| errorCode | [SocketError](../../socketerror/)\& | प्राप्ति ऑपरेशन विफल होने पर त्रुटि कोड असाइन किया जाएगा वह आउटपुट पैरामीटर। |

### वापसी मान

प्राप्त बाइट्स की संख्या।

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) मेथड


सॉकेट से डेटा प्राप्त करता है और इसे निर्दिष्ट बाइट एरे में लिखता है।

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | वह बाइट एरे जहाँ प्राप्त डेटा असाइन किया जाएगा। |
| offset | **int32_t** | निर्दिष्ट एरे में बाइट में ऑफ़सेट। |
| size | **int32_t** | ‘offset’ इंडेक्स से निर्दिष्ट बाइट एरे में असाइन किए जाने वाले बाइट्स की संख्या। |
| socketFlags | [SocketFlags](../../socketflags/) | प्राप्ति व्यवहार। |
| errorCode | [SocketError](../../socketerror/)\& | प्राप्ति ऑपरेशन विफल होने पर त्रुटि कोड असाइन किया जाएगा वह आउटपुट पैरामीटर। |

### वापसी मान

प्राप्त बाइट्स की संख्या।

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) मेथड


सॉकेट से डेटा प्राप्त करता है और इसे निर्दिष्ट बाइट एरे में लिखता है।

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | वह बाइट एरे जहाँ प्राप्त डेटा असाइन किया जाएगा। |
| offset | **int32_t** | निर्दिष्ट एरे में बाइट में ऑफ़सेट। |
| size | **int32_t** | ‘offset’ इंडेक्स से निर्दिष्ट बाइट एरे में असाइन किए जाने वाले बाइट्स की संख्या। |
| socketFlags | [SocketFlags](../../socketflags/) | प्राप्ति व्यवहार। |
| errorCode | [SocketError](../../socketerror/)\& | प्राप्ति ऑपरेशन विफल होने पर त्रुटि कोड असाइन किया जाएगा वह आउटपुट पैरामीटर। |

### वापसी मान

प्राप्त बाइट्स की संख्या।

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) मेथड


सॉकेट से डेटा प्राप्त करता है और इसे निर्दिष्ट बाइट एरेज़ में लिखता है।

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | वह बाइट एरेज़ जहाँ प्राप्त डेटा असाइन किया जाएगा। |

### वापसी मान

प्राप्त बाइट्स की संख्या।

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) मेथड


सॉकेट से डेटा प्राप्त करता है और इसे निर्दिष्ट बाइट एरेज़ में लिखता है।

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | वह बाइट एरेज़ जहाँ प्राप्त डेटा असाइन किया जाएगा। |
| socketFlags | [SocketFlags](../../socketflags/) | प्राप्ति व्यवहार। |

### वापसी मान

प्राप्त बाइट्स की संख्या।

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) मेथड


सॉकेट से डेटा प्राप्त करता है और इसे निर्दिष्ट बाइट एरेज़ में लिखता है।

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | वह बाइट एरेज़ जहाँ प्राप्त डेटा असाइन किया जाएगा। |
| socketFlags | [SocketFlags](../../socketflags/) | प्राप्ति व्यवहार। |
| errorCode | [SocketError](../../socketerror/)\& | प्राप्ति ऑपरेशन विफल होने पर त्रुटि कोड असाइन किया जाएगा वह आउटपुट पैरामीटर। |

### वापसी मान

प्राप्त बाइट्स की संख्या।

## संबंधित देखें

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Socket](../)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)