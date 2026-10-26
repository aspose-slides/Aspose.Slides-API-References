---
title: GetHostEntry()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للـ C++
description: ينشئ كائنًا جديدًا من فئة IPHostEntry-class باستخدام السلسلة المحددة التي تحتوي على اسم مضيف أو عنوان IP.
type: docs
weight: 79
url: /ar/system.net/dns/gethostentry/
---
## Dns::GetHostEntry(String) طريقة

Creates a new IPHostEntry-class instance using the specified string that contains a host name or IP address.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(String hostNameOrAddress)
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | سلسلة تحتوي على اسم مضيف أو عنوان IP. |

### قيمة الإرجاع

مثال جديد من فئة IPHostEntry-class.

## Dns::GetHostEntry(System::SharedPtr\<IPAddress\>) طريقة

Creates a new IPHostEntry-class instance using the specified IP address.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(System::SharedPtr<IPAddress> address)
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | عنوان IP. |

### قيمة الإرجاع

مثال جديد من فئة IPHostEntry-class.

## انظر أيضًا

* تعريف النوع [SharedPtr](../../../system/sharedptr/)
* فئة [IPHostEntry](../../iphostentry/)
* فئة [String](../../../system/string/)
* فئة [Dns](../)
* فئة [IPAddress](../../ipaddress/)
* نطاق الاسم [System::Net](../../)
* مكتبة [Aspose.Slides](../../../)