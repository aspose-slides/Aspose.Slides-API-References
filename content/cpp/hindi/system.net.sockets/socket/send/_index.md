---
title: Send()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट डेटा को सॉकेट पर भेजता है।
type: docs
weight: 638
url: /hi/system.net.sockets/socket/send/
---
## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) मेथड


निर्दिष्ट डेटा को सॉकेट पर भेजता है।

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | भेजने के लिए डेटा। |
| size | **int32_t** | निर्दिष्ट डेटा में से बाइट्स की संख्या जिसे भेजना आवश्यक है। |
| socketFlags | [SocketFlags](../../socketflags/) | भेजने का व्यवहार। |

### रिटर्न वैल्यू

भेजे गए बाइट्स की संख्या।

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) मेथड


निर्दिष्ट डेटा को सॉकेट पर भेजता है।

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | भेजने के लिए डेटा। |
| size | **int32_t** | निर्दिष्ट डेटा में से बाइट्स की संख्या जिसे भेजना आवश्यक है। |
| socketFlags | [SocketFlags](../../socketflags/) | भेजने का व्यवहार। |

### रिटर्न वैल्यू

भेजे गए बाइट्स की संख्या।

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) मेथड


निर्दिष्ट डेटा को सॉकेट पर भेजता है।

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```


### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | भेजने के लिए डेटा। |
| size | **int32_t** | निर्दिष्ट डेटा में से बाइट्स की संख्या जिसे भेजना आवश्यक है। |
| socketFlags | [SocketFlags](../../socketflags/) | भेजने का व्यवहार। |

### रिटर्न वैल्यू

भेजे गए बाइट्स की संख्या।

## Socket::Send(System::ArrayPtr\<uint8_t\>, SocketFlags) मेथड


निर्दिष्ट डेटा को सॉकेट पर भेजता है।

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```


### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | भेजने के लिए डेटा। |
| socketFlags | [SocketFlags](../../socketflags/) | भेजने का व्यवहार। |

### रिटर्न वैल्यू

भेजे गए बाइट्स की संख्या।

## Socket::Send(System::Details::ArrayView\<uint8_t\>, SocketFlags) मेथड


निर्दिष्ट डेटा को सॉकेट पर भेजता है।

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```


### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | भेजने के लिए डेटा। |
| socketFlags | [SocketFlags](../../socketflags/) | भेजने का व्यवहार। |

### रिटर्न वैल्यू

भेजे गए बाइट्स की संख्या।

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) मेथड


निर्दिष्ट डेटा को सॉकेट पर भेजता है।

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```


### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | भेजने के लिए डेटा। |
| socketFlags | [SocketFlags](../../socketflags/) | भेजने का व्यवहार। |

### रिटर्न वैल्यू

भेजे गए बाइट्स की संख्या।

## Socket::Send(System::ArrayPtr\<uint8_t\>) मेथड


निर्दिष्ट डेटा को सॉकेट पर भेजता है।

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer)
```


### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | भेजने के लिए डेटा। |

### रिटर्न वैल्यू

भेजे गए बाइट्स की संख्या।

## Socket::Send(System::Details::ArrayView\<uint8_t\>) मेथड


निर्दिष्ट डेटा को सॉकेट पर भेजता है।

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer)
```


### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | भेजने के लिए डेटा। |

### रिटर्न वैल्यू

भेजे गए बाइट्स की संख्या।

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&) मेथड


निर्दिष्ट डेटा को सॉकेट पर भेजता है।

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer)
```


### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | भेजने के लिए डेटा। |

### रिटर्न वैल्यू

भेजे गए बाइट्स की संख्या।

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) मेथड


निर्दिष्ट डेटा को सॉकेट पर भेजता है।

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```


### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | बाइट ऐरे का संग्रह जिससे डेटा भेजा जाना है। |

### रिटर्न वैल्यू

भेजे गए बाइट्स की संख्या।

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) मेथड


निर्दिष्ट डेटा को सॉकेट पर भेजता है।

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```


### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | बाइट ऐरे का संग्रह जिससे डेटा भेजा जाना है। |
| socketFlags | [SocketFlags](../../socketflags/) | भेजने का व्यवहार। |

### रिटर्न वैल्यू

भेजे गए बाइट्स की संख्या।

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) मेथड


निर्दिष्ट डेटा को सॉकेट पर भेजता है।

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```


### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | बाइट ऐरे का संग्रह जिससे डेटा भेजा जाना है। |
| socketFlags | [SocketFlags](../../socketflags/) | भेजने का व्यवहार। |
| errorCode | [SocketError](../../socketerror/)\& | आउटपुट पैरामीटर जहाँ त्रुटि कोड असाइन किया जाएगा जब भेजने का कार्य विफल हो। |

### रिटर्न वैल्यू

भेजे गए बाइट्स की संख्या।

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) मेथड


निर्दिष्ट डेटा को सॉकेट पर भेजता है।

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | भेजने के लिए डेटा। |
| offset | **int32_t** | निर्दिष्ट ऐरे में बाइट्स में ऑफ़सेट। |
| size | **int32_t** | 'offset' पैरामीटर से शुरू होने वाले निर्दिष्ट ऐरे में बाइट्स की संख्या। |
| socketFlags | [SocketFlags](../../socketflags/) | भेजने का व्यवहार। |

### रिटर्न वैल्यू

भेजे गए बाइट्स की संख्या।

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) मेथड


निर्दिष्ट डेटा को सॉकेट पर भेजता है।

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | भेजने के लिए डेटा। |
| offset | **int32_t** | निर्दिष्ट ऐरे में बाइट्स में ऑफ़सेट। |
| size | **int32_t** | 'offset' पैरामीटर से शुरू होने वाले निर्दिष्ट ऐरे में बाइट्स की संख्या। |
| socketFlags | [SocketFlags](../../socketflags/) | भेजने का व्यवहार। |

### रिटर्न वैल्यू

भेजे गए बाइट्स की संख्या।

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) मेथड


निर्दिष्ट डेटा को सॉकेट पर भेजता है।

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | भेजने के लिए डेटा। |
| offset | **int32_t** | निर्दिष्ट ऐरे में बाइट्स में ऑफ़सेट। |
| size | **int32_t** | 'offset' पैरामीटर से शुरू होने वाले निर्दिष्ट ऐरे में बाइट्स की संख्या। |
| socketFlags | [SocketFlags](../../socketflags/) | भेजने का व्यवहार। |

### रिटर्न वैल्यू

भेजे गए बाइट्स की संख्या।

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) मेथड


निर्दिष्ट डेटा को सॉकेट पर भेजता है।

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | भेजने के लिए डेटा। |
| offset | **int32_t** | निर्दिष्ट ऐरे में बाइट्स में ऑफ़सेट। |
| size | **int32_t** | 'offset' पैरामीटर से शुरू होने वाले निर्दिष्ट ऐरे में बाइट्स की संख्या। |
| socketFlags | [SocketFlags](../../socketflags/) | भेजने का व्यवहार। |
| errorCode | [SocketError](../../socketerror/)\& | आउटपुट पैरामीटर जहाँ त्रुटि कोड असाइन किया जाएगा जब भेजने का कार्य विफल हो। |

### रिटर्न वैल्यू

भेजे गए बाइट्स की संख्या।

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) मेथड


निर्दिष्ट डेटा को सॉकेट पर भेजता है।

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | भेजने के लिए डेटा। |
| offset | **int32_t** | निर्दिष्ट ऐरे में बाइट्स में ऑफ़सेट। |
| size | **int32_t** | 'offset' पैरामीटर से शुरू होने वाले निर्दिष्ट ऐरे में बाइट्स की संख्या। |
| socketFlags | [SocketFlags](../../socketflags/) | भेजने का व्यवहार। |
| errorCode | [SocketError](../../socketerror/)\& | आउटपुट पैरामीटर जहाँ त्रुटि कोड असाइन किया जाएगा जब भेजने का कार्य विफल हो। |

### रिटर्न वैल्यू

भेजे गए बाइट्स की संख्या।

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) मेथड


निर्दिष्ट डेटा को सॉकेट पर भेजता है।

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | भेजने के लिए डेटा। |
| offset | **int32_t** | निर्दिष्ट ऐरे में बाइट्स में ऑफ़सेट। |
| size | **int32_t** | 'offset' पैरामीटर से शुरू होने वाले निर्दिष्ट ऐरे में बाइट्स की संख्या। |
| socketFlags | [SocketFlags](../../socketflags/) | भेजने का व्यवहार। |
| errorCode | [SocketError](../../socketerror/)\& | आउटपुट पैरामीटर जहाँ त्रुटि कोड असाइन किया जाएगा जब भेजने का कार्य विफल हो। |

### रिटर्न वैल्यू

भेजे गए बाइट्स की संख्या।

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