---
title: SendTo()
second_title: مرجع API Aspose.Slides برای C++
description: دادهٔ مشخص‌شده را به نقطهٔ انتهایی مشخص‌شده می‌فرستد.
type: docs
weight: 651
url: /fa/system.net.sockets/socket/sendto/
---
## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) متد

دادهٔ مشخص‌شده را به نقطهٔ انتهایی مشخص‌شده می‌فرستد.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | داده‌ای که باید ارسال شود. |
| offset | **int32_t** | جای‌گذاری در بایت‌ها در آرایهٔ مشخص‌شده. |
| size | **int32_t** | تعداد بایت‌ها در آرایهٔ مشخص‌شده که از پارامتر 'offset' آغاز می‌شود. |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار ارسال. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | نقطهٔ انتهایی ریموت. |

### مقدار بازگشتی

تعداد بایت‌های ارسال‌شده.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) متد

دادهٔ مشخص‌شده را به نقطهٔ انتهایی مشخص‌شده می‌فرستد.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | داده‌ای که باید ارسال شود. |
| offset | **int32_t** | جای‌گذاری در بایت‌ها در آرایهٔ مشخص‌شده. |
| size | **int32_t** | تعداد بایت‌ها در آرایهٔ مشخص‌شده که از پارامتر 'offset' آغاز می‌شود. |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار ارسال. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | نقطهٔ انتهایی ریموت. |

### مقدار بازگشتی

تعداد بایت‌های ارسال‌شده.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) متد

دادهٔ مشخص‌شده را به نقطهٔ انتهایی مشخص‌شده می‌فرستد.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | داده‌ای که باید ارسال شود. |
| offset | **int32_t** | جای‌گذاری در بایت‌ها در آرایهٔ مشخص‌شده. |
| size | **int32_t** | تعداد بایت‌ها در آرایهٔ مشخص‌شده که از پارامتر 'offset' آغاز می‌شود. |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار ارسال. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | نقطهٔ انتهایی ریموت. |

### مقدار بازگشتی

تعداد بایت‌های ارسال‌شده.

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) متد

دادهٔ مشخص‌شده را به نقطهٔ انتهایی مشخص‌شده می‌فرستد.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | داده‌ای که باید ارسال شود. |
| size | **int32_t** | تعداد بایت‌ها در آرایهٔ مشخص‌شده. |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار ارسال. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | نقطهٔ انتهایی ریموت. |

### مقدار بازگشتی

تعداد بایت‌های ارسال‌شده.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) متد

دادهٔ مشخص‌شده را به نقطهٔ انتهایی مشخص‌شده می‌فرستد.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | داده‌ای که باید ارسال شود. |
| size | **int32_t** | تعداد بایت‌ها در آرایهٔ مشخص‌شده. |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار ارسال. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | نقطهٔ انتهایی ریموت. |

### مقدار بازگشتی

تعداد بایت‌های ارسال‌شده.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) متد

دادهٔ مشخص‌شده را به نقطهٔ انتهایی مشخص‌شده می‌فرستد.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | داده‌ای که باید ارسال شود. |
| size | **int32_t** | تعداد بایت‌ها در آرایهٔ مشخص‌شده. |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار ارسال. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | نقطهٔ انتهایی ریموت. |

### مقدار بازگشتی

تعداد بایت‌های ارسال‌شده.

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) متد

دادهٔ مشخص‌شده را به نقطهٔ انتهایی مشخص‌شده می‌فرستد.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | داده‌ای که باید ارسال شود. |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار ارسال. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | نقطهٔ انتهایی ریموت. |

### مقدار بازگشتی

تعداد بایت‌های ارسال‌شده.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) متد

دادهٔ مشخص‌شده را به نقطهٔ انتهایی مشخص‌شده می‌فرستد.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | داده‌ای که باید ارسال شود. |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار ارسال. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | نقطهٔ انتهایی ریموت. |

### مقدار بازگشتی

تعداد بایت‌های ارسال‌شده.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags, System::SharedPtr\<EndPoint\>) متد

دادهٔ مشخص‌شده را به نقطهٔ انتهایی مشخص‌شده می‌فرستد.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | داده‌ای که باید ارسال شود. |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار ارسال. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | نقطهٔ انتهایی ریموت. |

### مقدار بازگشتی

تعداد بایت‌های ارسال‌شده.

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>) متد

دادهٔ مشخص‌شده را به نقطهٔ انتهایی مشخص‌شده می‌فرستد.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | داده‌ای که باید ارسال شود. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | نقطهٔ انتهایی ریموت. |

### مقدار بازگشتی

تعداد بایت‌های ارسال‌شده.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>) متد

دادهٔ مشخص‌شده را به نقطهٔ انتهایی مشخص‌شده می‌فرستد.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | داده‌ای که باید ارسال شود. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | نقطهٔ انتهایی ریموت. |

### مقدار بازگشتی

تعداد بایت‌های ارسال‌شده.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>) متد

دادهٔ مشخص‌شده را به نقطهٔ انتهایی مشخص‌شده می‌فرستد.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> remoteEP)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | داده‌ای که باید ارسال شود. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | نقطهٔ انتهایی ریموت. |

### مقدار بازگشتی

تعداد بایت‌های ارسال‌شده.

## موارد مرتبط

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)