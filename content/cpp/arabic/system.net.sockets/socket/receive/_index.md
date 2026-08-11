---
title: Receive()
second_title: Aspose.Slides لـ C++ مرجع API
description: يتلقى البيانات من المقبس ويكتبها إلى مصفوفة البايت المحددة.
type: docs
weight: 664
url: /ar/system.net.sockets/socket/receive/
---
## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) طريقة

يتلقى البيانات من المقبس ويكتبها إلى مصفوفة البايت المحددة.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مصفوفة البايت التي سيتم تعيين البيانات المستلمة فيها. |
| size | **int32_t** | عدد البايتات التي سيتم استلامها. |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الاستلام. |

### قيمة الإرجاع

عدد البايتات المستلمة.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) طريقة

يتلقى البيانات من المقبس ويكتبها إلى مصفوفة البايت المحددة.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | مصفوفة البايت التي سيتم تعيين البيانات المستلمة فيها. |
| size | **int32_t** | عدد البايتات التي سيتم استلامها. |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الاستلام. |

### قيمة الإرجاع

عدد البايتات المستلمة.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) طريقة

يتلقى البيانات من المقبس ويكتبها إلى مصفوفة البايت المحددة.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | مصفوفة البايت التي سيتم تعيين البيانات المستلمة فيها. |
| size | **int32_t** | عدد البايتات التي سيتم استلامها. |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الاستلام. |

### قيمة الإرجاع

عدد البايتات المستلمة.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, SocketFlags) طريقة

يتلقى البيانات من المقبس ويكتبها إلى مصفوفة البايت المحددة.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مصفوفة البايت التي سيتم تعيين البيانات المستلمة فيها. |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الاستلام. |

### قيمة الإرجاع

عدد البايتات المستلمة.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, SocketFlags) طريقة

يتلقى البيانات من المقبس ويكتبها إلى مصفوفة البايت المحددة.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | مصفوفة البايت التي سيتم تعيين البيانات المستلمة فيها. |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الاستلام. |

### قيمة الإرجاع

عدد البايتات المستلمة.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) طريقة

يتلقى البيانات من المقبس ويكتبها إلى مصفوفة البايت المحددة.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | مصفوفة البايت التي سيتم تعيين البيانات المستلمة فيها. |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الاستلام. |

### قيمة الإرجاع

عدد البايتات المستلمة.

## Socket::Receive(System::ArrayPtr\<uint8_t\>) طريقة

يتلقى البيانات من المقبس ويكتبها إلى مصفوفة البايت المحددة.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مصفوفة البايت التي سيتم تعيين البيانات المستلمة فيها. |

### قيمة الإرجاع

عدد البايتات المستلمة.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>) طريقة

يتلقى البيانات من المقبس ويكتبها إلى مصفوفة البايت المحددة.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | مصفوفة البايت التي سيتم تعيين البيانات المستلمة فيها. |

### قيمة الإرجاع

عدد البايتات المستلمة.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&) طريقة

يتلقى البيانات من المقبس ويكتبها إلى مصفوفة البايت المحددة.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | مصفوفة البايت التي سيتم تعيين البيانات المستلمة فيها. |

### قيمة الإرجاع

عدد البايتات المستلمة.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) طريقة

يتلقى البيانات من المقبس ويكتبها إلى مصفوفة البايت المحددة.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مصفوفة البايت التي سيتم تعيين البيانات المستلمة فيها. |
| offset | **int32_t** | الإزاحة بالبايتات في المصفوفة المحددة. |
| size | **int32_t** | عدد البايتات التي سيتم استلامها وتعيينها في مصفوفة البايت المحددة بدءًا من الفهرس 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الاستلام. |

### قيمة الإرجاع

عدد البايتات المستلمة.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) طريقة

يتلقى البيانات من المقبس ويكتبها إلى مصفوفة البايت المحددة.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | مصفوفة البايت التي سيتم تعيين البيانات المستلمة فيها. |
| offset | **int32_t** | الإزاحة بالبايتات في المصفوفة المحددة. |
| size | **int32_t** | عدد البايتات التي سيتم استلامها وتعيينها في مصفوفة البايت المحددة بدءًا من الفهرس 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الاستلام. |

### قيمة الإرجاع

عدد البايتات المستلمة.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) طريقة

يتلقى البيانات من المقبس ويكتبها إلى مصفوفة البايت المحددة.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | مصفوفة البايت التي سيتم تعيين البيانات المستلمة فيها. |
| offset | **int32_t** | الإزاحة بالبايتات في المصفوفة المحددة. |
| size | **int32_t** | عدد البايتات التي سيتم استلامها وتعيينها في مصفوفة البايت المحددة بدءًا من الفهرس 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الاستلام. |

### قيمة الإرجاع

عدد البايتات المستلمة.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) طريقة

يتلقى البيانات من المقبس ويكتبها إلى مصفوفة البايت المحددة.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مصفوفة البايت التي سيتم تعيين البيانات المستلمة فيها. |
| offset | **int32_t** | الإزاحة بالبايتات في المصفوفة المحددة. |
| size | **int32_t** | عدد البايتات التي سيتم استلامها وتعيينها في مصفوفة البايت المحددة بدءًا من الفهرس 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الاستلام. |
| errorCode | [SocketError](../../socketerror/)\& | المعامل الإخراجي الذي سيُعيّن فيه رمز الخطأ عندما يفشل عملية الاستلام. |

### قيمة الإرجاع

عدد البايتات المستلمة.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) طريقة

يتلقى البيانات من المقبس ويكتبها إلى مصفوفة البايت المحددة.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | مصفوفة البايت التي سيتم تعيين البيانات المستلمة فيها. |
| offset | **int32_t** | الإزاحة بالبايتات في المصفوفة المحددة. |
| size | **int32_t** | عدد البايتات التي سيتم استلامها وتعيينها في مصفوفة البايت المحددة بدءًا من الفهرس 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الاستلام. |
| errorCode | [SocketError](../../socketerror/)\& | المعامل الإخراجي الذي سيُعيّن فيه رمز الخطأ عندما يفشل عملية الاستلام. |

### قيمة الإرجاع

عدد البايتات المستلمة.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) طريقة

يتلقى البيانات من المقبس ويكتبها إلى مصفوفة البايت المحددة.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | مصفوفة البايت التي سيتم تعيين البيانات المستلمة فيها. |
| offset | **int32_t** | الإزاحة بالبايتات في المصفوفة المحددة. |
| size | **int32_t** | عدد البايتات التي سيتم استلامها وتعيينها في مصفوفة البايت المحددة بدءًا من الفهرس 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الاستلام. |
| errorCode | [SocketError](../../socketerror/)\& | المعامل الإخراجي الذي سيُعيّن فيه رمز الخطأ عندما يفشل عملية الاستلام. |

### قيمة الإرجاع

عدد البايتات المستلمة.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) طريقة

يتلقى البيانات من المقبس ويكتبها إلى مصفوفات البايت المحددة.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | مصفوفات البايت التي سيتم تعيين البيانات المستلمة فيها. |

### قيمة الإرجاع

عدد البايتات المستلمة.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) طريقة

يتلقى البيانات من المقبس ويكتبها إلى مصفوفات البايت المحددة.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | مصفوفات البايت التي سيتم تعيين البيانات المستلمة فيها. |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الاستلام. |

### قيمة الإرجاع

عدد البايتات المستلمة.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) طريقة

يتلقى البيانات من المقبس ويكتبها إلى مصفوفات البايت المحددة.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | مصفوفات البايت التي سيتم تعيين البيانات المستلمة فيها. |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الاستلام. |
| errorCode | [SocketError](../../socketerror/)\& | المعامل الإخراجي الذي سيُعيّن فيه رمز الخطأ عندما يفشل عملية الاستلام. |

### قيمة الإرجاع

عدد البايتات المستلمة.

## انظر أيضًا

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [Socket](../)
* فئة [IList](../../../system.collections.generic/ilist/)
* فئة [ArraySegment](../../../system/arraysegment/)
* نطاق [System::Net::Sockets](../../)
* مكتبة [Aspose.Slides](../../../)