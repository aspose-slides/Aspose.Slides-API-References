---
title: GetHostByAddress()
second_title: مرجع API Aspose.Slides برای C++
description: یک نمونه جدید از کلاس IPHostEntry را با استفاده از نمایش متنی مشخص‌شده از یک آدرس IP ایجاد می‌کند.
type: docs
weight: 14
url: /fa/system.net/dns/gethostbyaddress/
---
## Dns::GetHostByAddress(String) method

یک نمونه جدید از کلاس IPHostEntry را با استفاده از نمایش متنی مشخص‌شده از یک آدرس IP ایجاد می‌کند.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(String address)
```

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| address | [String](../../../system/string/) | نمایش متنی یک آدرس IP. |

### مقدار بازگشت

یک نمونه جدید از کلاس IPHostEntry ایجاد شده.

## Dns::GetHostByAddress(System::SharedPtr\<IPAddress\>) method

یک نمونه جدید از کلاس IPHostEntry را با استفاده از آدرس IP مشخص‌شده ایجاد می‌کند.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(System::SharedPtr<IPAddress> address)
```

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | آدرس IP. |

### مقدار بازگشت

یک نمونه جدید از کلاس IPHostEntry ایجاد شده.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPHostEntry](../../iphostentry/)
* Class [String](../../../system/string/)
* Class [Dns](../)
* Class [IPAddress](../../ipaddress/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)