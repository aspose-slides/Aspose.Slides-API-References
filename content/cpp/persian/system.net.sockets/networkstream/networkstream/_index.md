---
title: NetworkStream()
second_title: Aspose.Slides برای مرجع API C++
description: یک نمونه جدید می‌سازد.
type: docs
weight: 170
url: /fa/system.net.sockets/networkstream/networkstream/
---
## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>) سازنده

یک نمونه جدید می‌سازد.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | سوکتی که برای ارسال و دریافت داده‌ها استفاده می‌شود. |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, System::IO::FileAccess, bool) سازنده

یک نمونه جدید می‌سازد.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, System::IO::FileAccess access, bool ownsSocket)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | سوکتی که برای ارسال و دریافت داده‌ها استفاده می‌شود. |
| access | [System::IO::FileAccess](../../../system.io/fileaccess/) | نوع دسترسی داده‌شده به نمونه بر روی سوکت مشخص‌شده را تعیین می‌کند. |
| ownsSocket | **bool** | مقداری که نشان می‌دهد آیا نمونه جاری مالک سوکت مشخص‌شده می‌شود زمانی که مقدار true باشد. |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, bool) سازنده

یک نمونه جدید می‌سازد.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, bool ownsSocket)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | سوکتی که برای ارسال و دریافت داده‌ها استفاده می‌شود. |
| ownsSocket | **bool** | مقداری که نشان می‌دهد آیا نمونه جاری مالک سوکت مشخص‌شده می‌شود زمانی که مقدار true باشد. |

## موارد مرتبط

* Enum [FileAccess](../../../system.io/fileaccess/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Socket](../../socket/)
* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)