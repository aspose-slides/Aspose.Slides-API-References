---
title: ReceiveFrom()
second_title: مرجع API Aspose.Slides برای C++
description: داده‌ها را از نقطه انتهایی مشخص دریافت می‌کند و به آرایه بایت مشخص می‌نویسد.
type: docs
weight: 690
url: /fa/system.net.sockets/socket/receivefrom/
---
## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


داده‌ها را از نقطه انتهایی مشخص دریافت می‌کند و به آرایه بایت مشخص می‌نویسد.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | آرایه بایتی که داده‌های دریافت‌شده در آن اختصاص می‌یابد. |
| offset | **int32_t** | مانع (offset) بر حسب بایت در آرایهٔ مشخص. |
| size | **int32_t** | تعداد بایت‌هایی که باید دریافت شوند و به آرایهٔ بایت مشخص از اندیس ‘offset’ اختصاص پیدا می‌کنند. |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار دریافت. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | نقطه انتهایی ریموت. |

### مقدار بازگشت

تعداد بایت‌های دریافت‌شده.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


داده‌ها را از نقطه انتهایی مشخص دریافت می‌کند و به آرایه بایت مشخص می‌نویسد.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | آرایه بایتی که داده‌های دریافت‌شده در آن اختصاص می‌یابد. |
| offset | **int32_t** | مانع (offset) بر حسب بایت در آرایهٔ مشخص. |
| size | **int32_t** | تعداد بایت‌هایی که باید دریافت شوند و به آرایهٔ بایت مشخص از اندیس ‘offset’ اختصاص پیدا می‌کنند. |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار دریافت. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | نقطه انتهایی ریموت. |

### مقدار بازگشت

تعداد بایت‌های دریافت‌شده.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


داده‌ها را از نقطه انتهایی مشخص دریافت می‌کند و به آرایه بایت مشخص می‌نویسد.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | آرایه بایتی که داده‌های دریافت‌شده در آن اختصاص می‌یابد. |
| offset | **int32_t** | مانع (offset) بر حسب بایت در آرایهٔ مشخص. |
| size | **int32_t** | تعداد بایت‌هایی که باید دریافت شوند و به آرایهٔ بایت مشخص از اندیس ‘offset’ اختصاص پیدا می‌کنند. |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار دریافت. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | نقطه انتهایی ریموت. |

### مقدار بازگشت

تعداد بایت‌های دریافت‌شده.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


داده‌ها را از نقطه انتهایی مشخص دریافت می‌کند و به آرایه بایت مشخص می‌نویسد.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | آرایه بایتی که داده‌های دریافت‌شده در آن اختصاص می‌یابد. |
| size | **int32_t** | تعداد بایت‌هایی که باید دریافت شوند و به آرایهٔ بایت مشخص از اندیس ‘offset’ اختصاص پیدا می‌کنند. |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار دریافت. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | نقطه انتهایی ریموت. |

### مقدار بازگشت

تعداد بایت‌های دریافت‌شده.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


داده‌ها را از نقطه انتهایی مشخص دریافت می‌کند و به آرایه بایت مشخص می‌نویسد.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | آرایه بایتی که داده‌های دریافت‌شده در آن اختصاص می‌یابد. |
| size | **int32_t** | تعداد بایت‌هایی که باید دریافت شوند و به آرایهٔ بایت مشخص از اندیس ‘offset’ اختصاص پیدا می‌کنند. |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار دریافت. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | نقطه انتهایی ریموت. |

### مقدار بازگشت

تعداد بایت‌های دریافت‌شده.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


داده‌ها را از نقطه انتهایی مشخص دریافت می‌کند و به آرایه بایت مشخص می‌نویسد.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | آرایه بایتی که داده‌های دریافت‌شده در آن اختصاص می‌یابد. |
| size | **int32_t** | تعداد بایت‌هایی که باید دریافت شوند و به آرایهٔ بایت مشخص از اندیس ‘offset’ اختصاص پیدا می‌کنند. |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار دریافت. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | نقطه انتهایی ریموت. |

### مقدار بازگشت

تعداد بایت‌های دریافت‌شده.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


داده‌ها را از نقطه انتهایی مشخص دریافت می‌کند و به آرایه بایت مشخص می‌نویسد.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | آرایه بایتی که داده‌های دریافت‌شده در آن اختصاص می‌یابد. |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار دریافت. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | نقطه انتهایی ریموت. |

### مقدار بازگشت

تعداد بایت‌های دریافت‌شده.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


داده‌ها را از نقطه انتهایی مشخص دریافت می‌کند و به آرایه بایت مشخص می‌نویسد.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | آرایه بایتی که داده‌های دریافت‌شده در آن اختصاص می‌یابد. |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار دریافت. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | نقطه انتهایی ریموت. |

### مقدار بازگشت

تعداد بایت‌های دریافت‌شده.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


داده‌ها را از نقطه انتهایی مشخص دریافت می‌کند و به آرایه بایت مشخص می‌نویسد.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | آرایه بایتی که داده‌های دریافت‌شده در آن اختصاص می‌یابد. |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار دریافت. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | نقطه انتهایی ریموت. |

### مقدار بازگشت

تعداد بایت‌های دریافت‌شده.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) method


داده‌ها را از نقطه انتهایی مشخص دریافت می‌کند و به آرایه بایت مشخص می‌نویسد.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```


### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | آرایه بایتی که داده‌های دریافت‌شده در آن اختصاص می‌یابد. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | نقطه انتهایی ریموت. |

### مقدار بازگشت

تعداد بایت‌های دریافت‌شده.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) method


داده‌ها را از نقطه انتهایی مشخص دریافت می‌کند و به آرایه بایت مشخص می‌نویسد.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```


### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | آرایه بایتی که داده‌های دریافت‌شده در آن اختصاص می‌یابد. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | نقطه انتهایی ریموت. |

### مقدار بازگشت

تعداد بایت‌های دریافت‌شده.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>\&) method


داده‌ها را از نقطه انتهایی مشخص دریافت می‌کند و به آرایه بایت مشخص می‌نویسد.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> &remoteEP)
```


### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | آرایه بایتی که داده‌های دریافت‌شده در آن اختصاص می‌یابد. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | نقطه انتهایی ریموت. |

### مقدار بازگشت

تعداد بایت‌های دریافت‌شده.

## موارد مرتبط

* enum [SocketFlags](../../socketflags/)
* typedef [ArrayPtr](../../../system/arrayptr/)
* typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [EndPoint](../../../system.net/endpoint/)
* کلاس [Socket](../)
* فضای‌نام [System::Net::Sockets](../../)
* کتابخانه [Aspose.Slides](../../../)