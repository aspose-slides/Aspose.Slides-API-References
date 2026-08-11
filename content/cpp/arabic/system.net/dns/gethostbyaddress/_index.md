---
title: GetHostByAddress()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ مثيلًا جديدًا من الفئة IPHostEntry-class باستخدام تمثيل النص المحدد لعنوان IP.
type: docs
weight: 14
url: /ar/system.net/dns/gethostbyaddress/
---
## Dns::GetHostByAddress(String) طريقة

Creates a new IPHostEntry-class instance using the specified string representation of an IP address.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(String address)
```

### المعطيات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| address | [String](../../../system/string/) | تمثيل النص لعنوان IP. |

### قيمة الإرجاع

A newly created IPHostEntry-class instance.

## Dns::GetHostByAddress(System::SharedPtr\<IPAddress\>) طريقة

Creates a new IPHostEntry-class instance using the specified IP address.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(System::SharedPtr<IPAddress> address)
```

### المعطيات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | عنوان IP. |

### قيمة الإرجاع

A newly created IPHostEntry-class instance.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IPHostEntry](../../iphostentry/)
* فئة [String](../../../system/string/)
* فئة [Dns](../)
* فئة [IPAddress](../../ipaddress/)
* مساحة الاسم [System::Net](../../)
* مكتبة [Aspose.Slides](../../../)