---
title: ReceiveMessageFrom()
second_title: مرجع API Aspose.Slides برای C++
description: داده‌ها را از نقطه انتهایی مشخص دریافت می‌کند و در آرایه بایتی مشخص می‌نویسد.
type: docs
weight: 677
url: /fa/system.net.sockets/socket/receivemessagefrom/
---
## Socket::ReceiveMessageFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) متد

داده‌ها را از نقطه انتهایی مشخص دریافت می‌کند و در آرایه بایتی مشخص می‌نویسد.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | آرایه بایتی که داده‌های دریافت‌شده در آن قرار می‌گیرد. |
| offset | **int32_t** | انحراف به بایت در آرایه مشخص شده. |
| size | **int32_t** | تعداد بایت‌هایی که دریافت می‌شوند و از ایندکس 'offset' به آرایه بایتی مشخص شده اختصاص می‌یابند. |
| socketFlags | [SocketFlags](../../socketflags/)\& | رفتار دریافت. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | نقطه انتهایی ریموت. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | پارامتر خروجی که اطلاعات مربوط به بسته در آن قرار می‌گیرد. |

### مقدار بازگشت

تعداد بایت‌های دریافت‌شده.

## Socket::ReceiveMessageFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) متد

داده‌ها را از نقطه انتهایی مشخص دریافت می‌کند و در آرایه بایتی مشخص می‌نویسد.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | آرایه بایتی که داده‌های دریافت‌شده در آن قرار می‌گیرد. |
| offset | **int32_t** | انحراف به بایت در آرایه مشخص شده. |
| size | **int32_t** | تعداد بایت‌هایی که دریافت می‌شوند و از ایندکس 'offset' به آرایه بایتی مشخص شده اختصاص می‌یابند. |
| socketFlags | [SocketFlags](../../socketflags/)\& | رفتار دریافت. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | نقطه انتهایی ریموت. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | پارامتر خروجی که اطلاعات مربوط به بسته در آن قرار می‌گیرد. |

### مقدار بازگشت

تعداد بایت‌های دریافت‌شده.

## Socket::ReceiveMessageFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) متد

داده‌ها را از نقطه انتهایی مشخص دریافت می‌کند و در آرایه بایتی مشخص می‌نویسد.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | آرایه بایتی که داده‌های دریافت‌شده در آن قرار می‌گیرد. |
| offset | **int32_t** | انحراف به بایت در آرایه مشخص شده. |
| size | **int32_t** | تعداد بایت‌هایی که دریافت می‌شوند و از ایندکس 'offset' به آرایه بایتی مشخص شده اختصاص می‌یابند. |
| socketFlags | [SocketFlags](../../socketflags/)\& | رفتار دریافت. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | نقطه انتهایی ریموت. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | پارامتر خروجی که اطلاعات مربوط به بسته در آن قرار می‌گیرد. |

### مقدار بازگشت

تعداد بایت‌های دریافت‌شده.

## مراجع

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [IPPacketInformation](../../ippacketinformation/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)