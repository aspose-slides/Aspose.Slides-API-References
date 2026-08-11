---
title: Receive()
second_title: مرجع API Aspose.Slides برای C++
description: داده‌ها را از سوکت دریافت می‌کند و در آرایه بایتی مشخص‌شده می‌نویسد.
type: docs
weight: 664
url: /fa/system.net.sockets/socket/receive/
---
## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) متد

داده‌ها را از سوکت دریافت می‌کند و در آرایه بایتی مشخص‌شده می‌نویسد.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | آرایه بایتی که داده‌های دریافت‌شده در آن اختصاص می‌یابد. |
| size | **int32_t** | تعداد بایت‌هایی که باید دریافت شوند. |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار دریافت. |

### مقدار بازگشت

تعداد بایت‌های دریافت‌شده.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) متد

داده‌ها را از سوکت دریافت می‌کند و در آرایه بایتی مشخص‌شده می‌نویسد.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | آرایه بایتی که داده‌های دریافت‌شده در آن اختصاص می‌یابد. |
| size | **int32_t** | تعداد بایت‌هایی که باید دریافت شوند. |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار دریافت. |

### مقدار بازگشت

تعداد بایت‌های دریافت‌شده.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) متد

داده‌ها را از سوکت دریافت می‌کند و در آرایه بایتی مشخص‌شده می‌نویسد.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | آرایه بایتی که داده‌های دریافت‌شده در آن اختصاص می‌یابد. |
| size | **int32_t** | تعداد بایت‌هایی که باید دریافت شوند. |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار دریافت. |

### مقدار بازگشت

تعداد بایت‌های دریافت‌شده.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, SocketFlags) متد

داده‌ها را از سوکت دریافت می‌کند و در آرایه بایتی مشخص‌شده می‌نویسد.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | آرایه بایتی که داده‌های دریافت‌شده در آن اختصاص می‌یابد. |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار دریافت. |

### مقدار بازگشت

تعداد بایت‌های دریافت‌شده.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, SocketFlags) متد

داده‌ها را از سوکت دریافت می‌کند و در آرایه بایتی مشخص‌شده می‌نویسد.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | آرایه بایتی که داده‌های دریافت‌شده در آن اختصاص می‌یابد. |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار دریافت. |

### مقدار بازگشت

تعداد بایت‌های دریافت‌شده.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) متد

داده‌ها را از سوکت دریافت می‌کند و در آرایه بایتی مشخص‌شده می‌نویسد.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | آرایه بایتی که داده‌های دریافت‌شده در آن اختصاص می‌یابد. |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار دریافت. |

### مقدار بازگشت

تعداد بایت‌های دریافت‌شده.

## Socket::Receive(System::ArrayPtr\<uint8_t\>) متد

داده‌ها را از سوکت دریافت می‌کند و در آرایه بایتی مشخص‌شده می‌نویسد.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | آرایه بایتی که داده‌های دریافت‌شده در آن اختصاص می‌یابد. |

### مقدار بازگشت

تعداد بایت‌های دریافت‌شده.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>) متد

داده‌ها را از سوکت دریافت می‌کند و در آرایه بایتی مشخص‌شده می‌نویسد.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | آرایه بایتی که داده‌های دریافت‌شده در آن اختصاص می‌یابد. |

### مقدار بازگشت

تعداد بایت‌های دریافت‌شده.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&) متد

داده‌ها را از سوکت دریافت می‌کند و در آرایه بایتی مشخص‌شده می‌نویسد.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | آرایه بایتی که داده‌های دریافت‌شده در آن اختصاص می‌یابد. |

### مقدار بازگشت

تعداد بایت‌های دریافت‌شده.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) متد

داده‌ها را از سوکت دریافت می‌کند و در آرایه بایتی مشخص‌شده می‌نویسد.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | آرایه بایتی که داده‌های دریافت‌شده در آن اختصاص می‌یابد. |
| offset | **int32_t** | جابجایی به بایت در آرایه مشخص‌شده. |
| size | **int32_t** | تعداد بایت‌هایی که باید دریافت شوند و از اندیس 'offset' به آرایه بایتی مشخص‌شده اختصاص می‌یابند. |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار دریافت. |

### مقدار بازگشت

تعداد بایت‌های دریافت‌شده.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) متد

داده‌ها را از سوکت دریافت می‌کند و در آرایه بایتی مشخص‌شده می‌نویسد.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | آرایه بایتی که داده‌های دریافت‌شده در آن اختصاص می‌یابد. |
| offset | **int32_t** | جابجایی به بایت در آرایه مشخص‌شده. |
| size | **int32_t** | تعداد بایت‌هایی که باید دریافت شوند و از اندیس 'offset' به آرایه بایتی مشخص‌شده اختصاص می‌یابند. |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار دریافت. |

### مقدار بازگشت

تعداد بایت‌های دریافت‌شده.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) متد

داده‌ها را از سوکت دریافت می‌کند و در آرایه بایتی مشخص‌شده می‌نویسد.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | آرایه بایتی که داده‌های دریافت‌شده در آن اختصاص می‌یابد. |
| offset | **int32_t** | جابجایی به بایت در آرایه مشخص‌شده. |
| size | **int32_t** | تعداد بایت‌هایی که باید دریافت شوند و از اندیس 'offset' به آرایه بایتی مشخص‌شده اختصاص می‌یابند. |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار دریافت. |

### مقدار بازگشت

تعداد بایت‌های دریافت‌شده.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) متد

داده‌ها را از سوکت دریافت می‌کند و در آرایه بایتی مشخص‌شده می‌نویسد.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | آرایه بایتی که داده‌های دریافت‌شده در آن اختصاص می‌یابد. |
| offset | **int32_t** | جابجایی به بایت در آرایه مشخص‌شده. |
| size | **int32_t** | تعداد بایت‌هایی که باید دریافت شوند و از اندیس 'offset' به آرایه بایتی مشخص‌شده اختصاص می‌یابند. |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار دریافت. |
| errorCode | [SocketError](../../socketerror/)\& | پارامتر خروجی که در صورت شکست عملیات دریافت، کد خطا در آن اختصاص می‌یابد. |

### مقدار بازگشت

تعداد بایت‌های دریافت‌شده.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) متد

داده‌ها را از سوکت دریافت می‌کند و در آرایه بایتی مشخص‌شده می‌نویسد.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | آرایه بایتی که داده‌های دریافت‌شده در آن اختصاص می‌یابد. |
| offset | **int32_t** | جابجایی به بایت در آرایه مشخص‌شده. |
| size | **int32_t** | تعداد بایت‌هایی که باید دریافت شوند و از اندیس 'offset' به آرایه بایتی مشخص‌شده اختصاص می‌یابند. |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار دریافت. |
| errorCode | [SocketError](../../socketerror/)\& | پارامتر خروجی که در صورت شکست عملیات دریافت، کد خطا در آن اختصاص می‌یابد. |

### مقدار بازگشت

تعداد بایت‌های دریافت‌شده.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) متد

داده‌ها را از سوکت دریافت می‌کند و در آرایه بایتی مشخص‌شده می‌نویسد.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | آرایه بایتی که داده‌های دریافت‌شده در آن اختصاص می‌یابد. |
| offset | **int32_t** | جابجایی به بایت در آرایه مشخص‌شده. |
| size | **int32_t** | تعداد بایت‌هایی که باید دریافت شوند و از اندیس 'offset' به آرایه بایتی مشخص‌شده اختصاص می‌یابند. |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار دریافت. |
| errorCode | [SocketError](../../socketerror/)\& | پارامتر خروجی که در صورت شکست عملیات دریافت، کد خطا در آن اختصاص می‌یابد. |

### مقدار بازگشت

تعداد بایت‌های دریافت‌شده.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) متد

داده‌ها را از سوکت دریافت می‌کند و در آرایه‌های بایتی مشخص‌شده می‌نویسد.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | آرایه‌های بایتی که داده‌های دریافت‌شده در آن‌ها اختصاص می‌یابد. |

### مقدار بازگشت

تعداد بایت‌های دریافت‌شده.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) متد

داده‌ها را از سوکت دریافت می‌کند و در آرایه‌های بایتی مشخص‌شده می‌نویسد.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | آرایه‌های بایتی که داده‌های دریافت‌شده در آن‌ها اختصاص می‌یابد. |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار دریافت. |

### مقدار بازگشت

تعداد بایت‌های دریافت‌شده.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) متد

داده‌ها را از سوکت دریافت می‌کند و در آرایه‌های بایتی مشخص‌شده می‌نویسد.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | آرایه‌های بایتی که داده‌های دریافت‌شده در آن‌ها اختصاص می‌یابد. |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار دریافت. |
| errorCode | [SocketError](../../socketerror/)\& | پارامتر خروجی که در صورت شکست عملیات دریافت، کد خطا در آن اختصاص می‌یابد. |

### مقدار بازگشت

تعداد بایت‌های دریافت‌شده.

## موارد مرتبط

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Socket](../)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)