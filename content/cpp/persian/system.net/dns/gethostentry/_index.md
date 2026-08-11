---
title: GetHostEntry()
second_title: Aspose.Slides برای C++ مرجع API
description: یک نمونه جدید از IPHostEntry-class را با استفاده از یک رشته که شامل نام میزبان یا آدرس IP است، ایجاد می‌کند.
type: docs
weight: 79
url: /fa/system.net/dns/gethostentry/
---
## Dns::GetHostEntry(String) method

یک نمونه جدید از IPHostEntry-class را با استفاده از رشتهٔ مشخص‌شده‌ای که شامل نام میزبان یا آدرس IP است، ایجاد می‌کند.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(String hostNameOrAddress)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | رشته‌ای که شامل نام میزبان یا آدرس IP است. |

### Return Value

یک نمونه جدید از IPHostEntry-class.

## Dns::GetHostEntry(System::SharedPtr\<IPAddress\>) method

یک نمونه جدید از IPHostEntry-class را با استفاده از آدرس IP مشخص‌شده ایجاد می‌کند.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(System::SharedPtr<IPAddress> address)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | آدرس IP. |

### Return Value

یک نمونه جدید از IPHostEntry-class.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPHostEntry](../../iphostentry/)
* Class [String](../../../system/string/)
* Class [Dns](../)
* Class [IPAddress](../../ipaddress/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)