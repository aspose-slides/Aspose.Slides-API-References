---
title: Send()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يرسل البيانات المحددة إلى المقبس.
type: docs
weight: 638
url: /ar/system.net.sockets/socket/send/
---
## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) طريقة


يرسل البيانات المحددة إلى المقبس.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | البيانات المراد إرسالها. |
| size | **int32_t** | عدد البايتات من البيانات المحددة التي يجب إرسالها. |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الإرسال. |

### قيمة الإرجاع

عدد البايتات المرسلة.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) طريقة


يرسل البيانات المحددة إلى المقبس.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | البيانات المراد إرسالها. |
| size | **int32_t** | عدد البايتات من البيانات المحددة التي يجب إرسالها. |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الإرسال. |

### قيمة الإرجاع

عدد البايتات المرسلة.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) طريقة


يرسل البيانات المحددة إلى المقبس.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | البيانات المراد إرسالها. |
| size | **int32_t** | عدد البايتات من البيانات المحددة التي يجب إرسالها. |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الإرسال. |

### قيمة الإرجاع

عدد البايتات المرسلة.

## Socket::Send(System::ArrayPtr\<uint8_t\>, SocketFlags) طريقة


يرسل البيانات المحددة إلى المقبس.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | البيانات المراد إرسالها. |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الإرسال. |

### قيمة الإرجاع

عدد البايتات المرسلة.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, SocketFlags) طريقة


يرسل البيانات المحددة إلى المقبس.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | البيانات المراد إرسالها. |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الإرسال. |

### قيمة الإرجاع

عدد البايتات المرسلة.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) طريقة


يرسل البيانات المحددة إلى المقبس.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | البيانات المراد إرسالها. |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الإرسال. |

### قيمة الإرجاع

عدد البايتات المرسلة.

## Socket::Send(System::ArrayPtr\<uint8_t\>) طريقة


يرسل البيانات المحددة إلى المقبس.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | البيانات المراد إرسالها. |

### قيمة الإرجاع

عدد البايتات المرسلة.

## Socket::Send(System::Details::ArrayView\<uint8_t\>) طريقة


يرسل البيانات المحددة إلى المقبس.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | البيانات المراد إرسالها. |

### قيمة الإرجاع

عدد البايتات المرسلة.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&) طريقة


يرسل البيانات المحددة إلى المقبس.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | البيانات المراد إرسالها. |

### قيمة الإرجاع

عدد البايتات المرسلة.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) طريقة


يرسل البيانات المحددة إلى المقبس.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | مجموعة من مصفوفات البايت التي يجب إرسال البيانات منها. |

### قيمة الإرجاع

عدد البايتات المرسلة.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) طريقة


يرسل البيانات المحددة إلى المقبس.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | مجموعة من مصفوفات البايت التي يجب إرسال البيانات منها. |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الإرسال. |

### قيمة الإرجاع

عدد البايتات المرسلة.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) طريقة


يرسل البيانات المحددة إلى المقبس.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | مجموعة من مصفوفات البايت التي يجب إرسال البيانات منها. |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الإرسال. |
| errorCode | [SocketError](../../socketerror/)\& | معامل الإخراج الذي سيتم تعيين رمز الخطأ فيه عند فشل عملية الإرسال. |

### قيمة الإرجاع

عدد البايتات المرسلة.

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) طريقة


يرسل البيانات المحددة إلى المقبس.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | البيانات المراد إرسالها. |
| offset | **int32_t** | الإزاحة بالبايت في المصفوفة المحددة. |
| size | **int32_t** | عدد البايتات في المصفوفة المحددة بدءًا من معامل 'الإزاحة'. |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الإرسال. |

### قيمة الإرجاع

عدد البايتات المرسلة.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) طريقة


يرسل البيانات المحددة إلى المقبس.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | البيانات المراد إرسالها. |
| offset | **int32_t** | الإزاحة بالبايت في المصفوفة المحددة. |
| size | **int32_t** | عدد البايتات في المصفوفة المحددة بدءًا من معامل 'الإزاحة'. |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الإرسال. |

### قيمة الإرجاع

عدد البايتات المرسلة.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) طريقة


يرسل البيانات المحددة إلى المقبس.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | البيانات المراد إرسالها. |
| offset | **int32_t** | الإزاحة بالبايت في المصفوفة المحددة. |
| size | **int32_t** | عدد البايتات في المصفوفة المحددة بدءًا من معامل 'الإزاحة'. |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الإرسال. |

### قيمة الإرجاع

عدد البايتات المرسلة.

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) طريقة


يرسل البيانات المحددة إلى المقبس.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | البيانات المراد إرسالها. |
| offset | **int32_t** | الإزاحة بالبايت في المصفوفة المحددة. |
| size | **int32_t** | عدد البايتات في المصفوفة المحددة بدءًا من معامل 'الإزاحة'. |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الإرسال. |
| errorCode | [SocketError](../../socketerror/)\& | معامل الإخراج الذي سيتم تعيين رمز الخطأ فيه عند فشل عملية الإرسال. |

### قيمة الإرجاع

عدد البايتات المرسلة.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) طريقة


يرسل البيانات المحددة إلى المقبس.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | البيانات المراد إرسالها. |
| offset | **int32_t** | الإزاحة بالبايت في المصفوفة المحددة. |
| size | **int32_t** | عدد البايتات في المصفوفة المحددة بدءًا من معامل 'الإزاحة'. |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الإرسال. |
| errorCode | [SocketError](../../socketerror/)\& | معامل الإخراج الذي سيتم تعيين رمز الخطأ فيه عند فشل عملية الإرسال. |

### قيمة الإرجاع

عدد البايتات المرسلة.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) طريقة


يرسل البيانات المحددة إلى المقبس.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | البيانات المراد إرسالها. |
| offset | **int32_t** | الإزاحة بالبايت في المصفوفة المحددة. |
| size | **int32_t** | عدد البايتات في المصفوفة المحددة بدءًا من معامل 'الإزاحة'. |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الإرسال. |
| errorCode | [SocketError](../../socketerror/)\& | معامل الإخراج الذي سيتم تعيين رمز الخطأ فيه عند فشل عملية الإرسال. |

### قيمة الإرجاع

عدد البايتات المرسلة.

## أنظر أيضًا

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [Socket](../)
* فئة [IList](../../../system.collections.generic/ilist/)
* فئة [ArraySegment](../../../system/arraysegment/)
* نطاق [System::Net::Sockets](../../)
* مكتبة [Aspose.Slides](../../../)