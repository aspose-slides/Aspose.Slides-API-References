---
title: ReceiveFrom()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يتلقى البيانات من نقطة النهاية المحددة ويكتبها إلى مصفوفة البايت المحددة.
type: docs
weight: 690
url: /ar/system.net.sockets/socket/receivefrom/
---
## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) طريقة

يتلقى البيانات من نقطة النهاية المحددة ويكتبها إلى مصفوفة البايت المحددة.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مصفوفة البايت التي سيتم تعيين البيانات المستلمة فيها. |
| offset | **int32_t** | الإزاحة بالبايت في المصفوفة المحددة. |
| size | **int32_t** | عدد البايتات التي سيتم استقبالها وتُعيّن إلى مصفوفة البايت المحددة من الفهرس 'offset' . |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الاستقبال. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | نقطة النهاية البعيدة. |

### قيمة الإرجاع

عدد البايتات المستلمة.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) طريقة

يتلقى البيانات من نقطة النهاية المحددة ويكتبها إلى مصفوفة البايت المحددة.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | مصفوفة البايت التي سيتم تعيين البيانات المستلمة فيها. |
| offset | **int32_t** | الإزاحة بالبايت في المصفوفة المحددة. |
| size | **int32_t** | عدد البايتات التي سيتم استقبالها وتُعيّن إلى مصفوفة البايت المحددة من الفهرس 'offset' . |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الاستقبال. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | نقطة النهاية البعيدة. |

### قيمة الإرجاع

عدد البايتات المستلمة.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) طريقة

يتلقى البيانات من نقطة النهاية المحددة ويكتبها إلى مصفوفة البايت المحددة.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | مصفوفة البايت التي سيتم تعيين البيانات المستلمة فيها. |
| offset | **int32_t** | الإزاحة بالبايت في المصفوفة المحددة. |
| size | **int32_t** | عدد البايتات التي سيتم استقبالها وتُعيّن إلى مصفوفة البايت المحددة من الفهرس 'offset' . |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الاستقبال. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | نقطة النهاية البعيدة. |

### قيمة الإرجاع

عدد البايتات المستلمة.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) طريقة

يتلقى البيانات من نقطة النهاية المحددة ويكتبها إلى مصفوفة البايت المحددة.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مصفوفة البايت التي سيتم تعيين البيانات المستلمة فيها. |
| size | **int32_t** | عدد البايتات التي سيتم استقبالها وتُعيّن إلى مصفوفة البايت المحددة من الفهرس 'offset' . |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الاستقبال. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | نقطة النهاية البعيدة. |

### قيمة الإرجاع

عدد البايتات المستلمة.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) طريقة

يتلقى البيانات من نقطة النهاية المحددة ويكتبها إلى مصفوفة البايت المحددة.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | مصفوفة البايت التي سيتم تعيين البيانات المستلمة فيها. |
| size | **int32_t** | عدد البايتات التي سيتم استقبالها وتُعيّن إلى مصفوفة البايت المحددة من الفهرس 'offset' . |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الاستقبال. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | نقطة النهاية البعيدة. |

### قيمة الإرجاع

عدد البايتات المستلمة.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) طريقة

يتلقى البيانات من نقطة النهاية المحددة ويكتبها إلى مصفوفة البايت المحددة.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | مصفوفة البايت التي سيتم تعيين البيانات المستلمة فيها. |
| size | **int32_t** | عدد البايتات التي سيتم استقبالها وتُعيّن إلى مصفوفة البايت المحددة من الفهرس 'offset' . |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الاستقبال. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | نقطة النهاية البعيدة. |

### قيمة الإرجاع

عدد البايتات المستلمة.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) طريقة

يتلقى البيانات من نقطة النهاية المحددة ويكتبها إلى مصفوفة البايت المحددة.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مصفوفة البايت التي سيتم تعيين البيانات المستلمة فيها. |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الاستقبال. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | نقطة النهاية البعيدة. |

### قيمة الإرجاع

عدد البايتات المستلمة.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) طريقة

يتلقى البيانات من نقطة النهاية المحددة ويكتبها إلى مصفوفة البايت المحددة.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | مصفوفة البايت التي سيتم تعيين البيانات المستلمة فيها. |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الاستقبال. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | نقطة النهاية البعيدة. |

### قيمة الإرجاع

عدد البايتات المستلمة.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) طريقة

يتلقى البيانات من نقطة النهاية المحددة ويكتبها إلى مصفوفة البايت المحددة.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مصفوفة البايت التي سيتم تعيين البيانات المستلمة فيها. |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الاستقبال. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | نقطة النهاية البعيدة. |

### قيمة الإرجاع

عدد البايتات المستلمة.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) طريقة

يتلقى البيانات من نقطة النهاية المحددة ويكتبها إلى مصفوفة البايت المحددة.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مصفوفة البايت التي سيتم تعيين البيانات المستلمة فيها. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | نقطة النهاية البعيدة. |

### قيمة الإرجاع

عدد البايتات المستلمة.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) طريقة

يتلقى البيانات من نقطة النهاية المحددة ويكتبها إلى مصفوفة البايت المحددة.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | مصفوفة البايت التي سيتم تعيين البيانات المستلمة فيها. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | نقطة النهاية البعيدة. |

### قيمة الإرجاع

عدد البايتات المستلمة.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>\&) طريقة

يتلقى البيانات من نقطة النهاية المحددة ويكتبها إلى مصفوفة البايت المحددة.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> &remoteEP)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | مصفوفة البايت التي سيتم تعيين البيانات المستلمة فيها. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | نقطة النهاية البعيدة. |

### قيمة الإرجاع

عدد البايتات المستلمة.

## انظر أيضًا

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)