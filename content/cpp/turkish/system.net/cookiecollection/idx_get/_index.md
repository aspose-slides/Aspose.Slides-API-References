---
title: idx_get()
second_title: C++ API Referansı için Aspose.Slides
description: Belirtilen dizindeki çerez koleksiyonundan bir çerez döndürür.
type: docs
weight: 40
url: /tr/system.net/cookiecollection/idx_get/
---
## CookieCollection::idx_get(int32_t) method

Belirtilen dizindeki çerez koleksiyonundan bir çerez döndürür.

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(int32_t index)
```

### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Döndürülmesi gereken çerez'in dizini. |

### Return Value

Belirtilen dizindeki bir çerez.

## CookieCollection::idx_get(String) method

Belirtilen ada göre çerez koleksiyonundan bir çerez döndürür.

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(String name)
```

### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Döndürülmesi gereken çerez'in adı. |

### Return Value

Belirtilen adla çerez koleksiyonundan bir çerez, bulunduğunda; aksi takdirde nullptr.

## See Also

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [Cookie](../../cookie/)
* Sınıf [CookieCollection](../)
* Sınıf [String](../../../system/string/)
* Ad Alanı [System::Net](../../)
* Kütüphane [Aspose.Slides](../../../)