---
title: SendTo()
second_title: مرجع API لـ Aspose.Slides لـ C++
description: يرسل البيانات المحددة إلى نقطة النهاية المحددة.
type: docs
weight: 651
url: /ar/system.net.sockets/socket/sendto/
---
## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) طريقة

يرسل البيانات المحددة إلى نقطة النهاية المحددة.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | البيانات المراد إرسالها. |
| offset | **int32_t** | الإزاحة بالبايت في المصفوفة المحددة. |
| size | **int32_t** | عدد البايتات في المصفوفة المحددة بدءًا من المعامل 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الإرسال. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | نقطة النهاية البعيدة. |

### قيمة الإرجاع

عدد البايتات المرسلة.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) طريقة


يرسل البيانات المحددة إلى نقطة النهاية المحددة.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | البيانات المراد إرسالها. |
| offset | **int32_t** | الإزاحة بالبايت في المصفوفة المحددة. |
| size | **int32_t** | عدد البايتات في المصفوفة المحددة بدءًا من المعامل 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الإرسال. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | نقطة النهاية البعيدة. |

### قيمة الإرجاع

عدد البايتات المرسلة.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) طريقة


يرسل البيانات المحددة إلى نقطة النهاية المحددة.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | البيانات المراد إرسالها. |
| offset | **int32_t** | الإزاحة بالبايت في المصفوفة المحددة. |
| size | **int32_t** | عدد البايتات في المصفوفة المحددة بدءًا من المعامل 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الإرسال. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | نقطة النهاية البعيدة. |

### قيمة الإرجاع

عدد البايتات المرسلة.

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) طريقة


يرسل البيانات المحددة إلى نقطة النهاية المحددة.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | البيانات المراد إرسالها. |
| size | **int32_t** | عدد البايتات في المصفوفة المحددة. |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الإرسال. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | نقطة النهاية البعيدة. |

### قيمة الإرجاع

عدد البايتات المرسلة.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) طريقة


يرسل البيانات المحددة إلى نقطة النهاية المحددة.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | البيانات المراد إرسالها. |
| size | **int32_t** | عدد البايتات في المصفوفة المحددة. |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الإرسال. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | نقطة النهاية البعيدة. |

### قيمة الإرجاع

عدد البايتات المرسلة.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) طريقة


يرسل البيانات المحددة إلى نقطة النهاية المحددة.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | البيانات المراد إرسالها. |
| size | **int32_t** | عدد البايتات في المصفوفة المحددة. |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الإرسال. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | نقطة النهاية البعيدة. |

### قيمة الإرجاع

عدد البايتات المرسلة.

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) طريقة


يرسل البيانات المحددة إلى نقطة النهاية المحددة.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | البيانات المراد إرسالها. |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الإرسال. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | نقطة النهاية البعيدة. |

### قيمة الإرجاع

عدد البايتات المرسلة.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) طريقة


يرسل البيانات المحددة إلى نقطة النهاية المحددة.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | البيانات المراد إرسالها. |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الإرسال. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | نقطة النهاية البعيدة. |

### قيمة الإرجاع

عدد البايتات المرسلة.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags, System::SharedPtr\<EndPoint\>) طريقة


يرسل البيانات المحددة إلى نقطة النهاية المحددة.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | البيانات المراد إرسالها. |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الإرسال. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | نقطة النهاية البعيدة. |

### قيمة الإرجاع

عدد البايتات المرسلة.

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>) طريقة


يرسل البيانات المحددة إلى نقطة النهاية المحددة.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | البيانات المراد إرسالها. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | نقطة النهاية البعيدة. |

### قيمة الإرجاع

عدد البايتات المرسلة.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>) طريقة


يرسل البيانات المحددة إلى نقطة النهاية المحددة.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | البيانات المراد إرسالها. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | نقطة النهاية البعيدة. |

### قيمة الإرجاع

عدد البايتات المرسلة.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>) طريقة


يرسل البيانات المحددة إلى نقطة النهاية المحددة.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> remoteEP)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | البيانات المراد إرسالها. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | نقطة النهاية البعيدة. |

### قيمة الإرجاع

عدد البايتات المرسلة.

## انظر أيضًا

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)