---
title: UriComponents
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل مكوّنات URI.
type: docs
weight: 3251
url: /ar/system/uricomponents/
---
## عدد UriComponents

يمثل مكوّنات URI.

```cpp
enum class UriComponents
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Scheme | 1 | بيانات Scheme. |
| UserInfo | 2 | بيانات UserInfo. |
| Host | 4 | بيانات Host. |
| Port | 8 | بيانات Port. |
| SchemeAndServer | n/a | بيانات Scheme, Host و Port. |
| Path | 16 | بيانات LocalPath. |
| Query | 32 | بيانات Query. |
| PathAndQuery | n/a | بيانات LocalPath و Query. |
| HttpRequestUrl | n/a | بيانات Scheme, Host, Port, Query و LocalPath. |
| Fragment | 64 | بيانات Fragment. |
| AbsoluteUri | n/a | بيانات Scheme, Host, Port, Quer, LocalPath و Fragment. |
| StrongPort | 128 | بيانات Port؛ إذا لم تكن بيانات المنفذ موجودة في [Uri](../uri/) وتم تعيين منفذ افتراضي إلى Scheme، يتم إرجاع المنفذ الافتراضي؛ إذا لم يكن هناك منفذ افتراضي، يتم إرجاع -1. |
| HostAndPort | n/a | بيانات Host و Port؛ إذا لم تكن بيانات المنفذ موجودة في [Uri](../uri/) وتم تعيين منفذ افتراضي إلى Scheme، يتم إرجاع المنفذ الافتراضي. إذا لم يكن هناك منفذ افتراضي، يتم إرجاع -1. |
| StrongAuthority | n/a | بيانات UserInfo, Host و Port. إذا لم تكن بيانات المنفذ موجودة في [Uri](../uri/) وتم تعيين منفذ افتراضي إلى Scheme، يتم إرجاع المنفذ الافتراضي. إذا لم يكن هناك منفذ افتراضي، يتم إرجاع -1. |
| NormalizedHost | 256 |  |
| KeepDelimiter | 1073741824 | يحدد أنه يجب تضمين الفاصل. |
| SerializationInfoString | n/a | السياق الكامل [Uri](../uri/) المطلوب لـ [Uri](../uri/) Serializers. يشمل السياق نطاق IPv6. |

## انظر أيضاً

* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)