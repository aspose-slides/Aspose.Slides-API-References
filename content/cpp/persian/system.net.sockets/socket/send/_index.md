---
title: Send()
second_title: Aspose.Slides برای مرجع API C++
description: دادهٔ مشخص‌شده را به سوکت ارسال می‌کند.
type: docs
weight: 638
url: /fa/system.net.sockets/socket/send/
---
## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) متد

داده مشخص‌شده را به سوکت ارسال می‌کند.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | داده‌ای که باید ارسال شود. |
| size | **int32_t** | تعداد بایت‌هایی از داده مشخص‌شده که باید ارسال شود. |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار ارسال. |

### مقدار بازگشتی

تعداد بایت‌های ارسال شده.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) متد

داده مشخص‌شده را به سوکت ارسال می‌کند.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | داده‌ای که باید ارسال شود. |
| size | **int32_t** | تعداد بایت‌هایی از داده مشخص‌شده که باید ارسال شود. |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار ارسال. |

### مقدار بازگشتی

تعداد بایت‌های ارسال شده.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) متد

داده مشخص‌شده را به سوکت ارسال می‌کند.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | داده‌ای که باید ارسال شود. |
| size | **int32_t** | تعداد بایت‌هایی از داده مشخص‌شده که باید ارسال شود. |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار ارسال. |

### مقدار بازگشتی

تعداد بایت‌های ارسال شده.

## Socket::Send(System::ArrayPtr\<uint8_t\>, SocketFlags) متد

داده مشخص‌شده را به سوکت ارسال می‌کند.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | داده‌ای که باید ارسال شود. |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار ارسال. |

### مقدار بازگشتی

تعداد بایت‌های ارسال شده.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, SocketFlags) متد

داده مشخص‌شده را به سوکت ارسال می‌کند.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | داده‌ای که باید ارسال شود. |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار ارسال. |

### مقدار بازگشتی

تعداد بایت‌های ارسال شده.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) متد

داده مشخص‌شده را به سوکت ارسال می‌کند.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | داده‌ای که باید ارسال شود. |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار ارسال. |

### مقدار بازگشتی

تعداد بایت‌های ارسال شده.

## Socket::Send(System::ArrayPtr\<uint8_t\>) متد

داده مشخص‌شده را به سوکت ارسال می‌کند.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | داده‌ای که باید ارسال شود. |

### مقدار بازگشتی

تعداد بایت‌های ارسال شده.

## Socket::Send(System::Details::ArrayView\<uint8_t\>) متد

داده مشخص‌شده را به سوکت ارسال می‌کند.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | داده‌ای که باید ارسال شود. |

### مقدار بازگشتی

تعداد بایت‌های ارسال شده.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&) متد

داده مشخص‌شده را به سوکت ارسال می‌کند.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | داده‌ای که باید ارسال شود. |

### مقدار بازگشتی

تعداد بایت‌های ارسال شده.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) متد

داده مشخص‌شده را به سوکت ارسال می‌کند.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | مجموعه‌ای از آرایه‌های بایت که داده باید از آن‌ها ارسال شود. |

### مقدار بازگشتی

تعداد بایت‌های ارسال شده.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) متد

داده مشخص‌شده را به سوکت ارسال می‌کند.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | مجموعه‌ای از آرایه‌های بایت که داده باید از آن‌ها ارسال شود. |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار ارسال. |

### مقدار بازگشتی

تعداد بایت‌های ارسال شده.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) متد

داده مشخص‌شده را به سوکت ارسال می‌کند.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | مجموعه‌ای از آرایه‌های بایت که داده باید از آن‌ها ارسال شود. |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار ارسال. |
| errorCode | [SocketError](../../socketerror/)\& | پارامتر خروجی که در صورت شکست عملیات ارسال، کد خطا در آن اختصاص می‌یابد. |

### مقدار بازگشتی

تعداد بایت‌های ارسال شده.

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) متد

داده مشخص‌شده را به سوکت ارسال می‌کند.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | داده‌ای که باید ارسال شود. |
| offset | **int32_t** | افست بر حسب بایت در آرایه مشخص‌شده. |
| size | **int32_t** | تعداد بایت‌های موجود در آرایه مشخص‌شده از موقعیت «offset». |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار ارسال. |

### مقدار بازگشتی

تعداد بایت‌های ارسال شده.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) متد

داده مشخص‌شده را به سوکت ارسال می‌کند.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | داده‌ای که باید ارسال شود. |
| offset | **int32_t** | افست بر حسب بایت در آرایه مشخص‌شده. |
| size | **int32_t** | تعداد بایت‌های موجود در آرایه مشخص‌شده از موقعیت «offset». |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار ارسال. |

### مقدار بازگشتی

تعداد بایت‌های ارسال شده.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) متد

داده مشخص‌شده را به سوکت ارسال می‌کند.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | داده‌ای که باید ارسال شود. |
| offset | **int32_t** | افست بر حسب بایت در آرایه مشخص‌شده. |
| size | **int32_t** | تعداد بایت‌های موجود در آرایه مشخص‌شده از موقعیت «offset». |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار ارسال. |

### مقدار بازگشتی

تعداد بایت‌های ارسال شده.

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) متد

داده مشخص‌شده را به سوکت ارسال می‌کند.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | داده‌ای که باید ارسال شود. |
| offset | **int32_t** | افست بر حسب بایت در آرایه مشخص‌شده. |
| size | **int32_t** | تعداد بایت‌های موجود در آرایه مشخص‌شده از موقعیت «offset». |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار ارسال. |
| errorCode | [SocketError](../../socketerror/)\& | پارامتر خروجی که در صورت شکست عملیات ارسال، کد خطا در آن اختصاص می‌یابد. |

### مقدار بازگشتی

تعداد بایت‌های ارسال شده.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) متد

داده مشخص‌شده را به سوکت ارسال می‌کند.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | داده‌ای که باید ارسال شود. |
| offset | **int32_t** | افست بر حسب بایت در آرایه مشخص‌شده. |
| size | **int32_t** | تعداد بایت‌های موجود در آرایه مشخص‌شده از موقعیت «offset». |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار ارسال. |
| errorCode | [SocketError](../../socketerror/)\& | پارامتر خروجی که در صورت شکست عملیات ارسال، کد خطا در آن اختصاص می‌یابد. |

### مقدار بازگشتی

تعداد بایت‌های ارسال شده.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) متد

داده مشخص‌شده را به سوکت ارسال می‌کند.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | داده‌ای که باید ارسال شود. |
| offset | **int32_t** | افست بر حسب بایت در آرایه مشخص‌شده. |
| size | **int32_t** | تعداد بایت‌های موجود در آرایه مشخص‌شده از موقعیت «offset». |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار ارسال. |
| errorCode | [SocketError](../../socketerror/)\& | پارامتر خروجی که در صورت شکست عملیات ارسال، کد خطا در آن اختصاص می‌یابد. |

### مقدار بازگشتی

تعداد بایت‌های ارسال شده.

## موارد مرتبط

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [Socket](../)
* کلاس [IList](../../../system.collections.generic/ilist/)
* کلاس [ArraySegment](../../../system/arraysegment/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)