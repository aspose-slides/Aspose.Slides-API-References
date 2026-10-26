---
title: idx_get()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يرجع cookie من مجموعة ملفات تعريف الارتباط عند الفهرس المحدد.
type: docs
weight: 40
url: /ar/system.net/cookiecollection/idx_get/
---
## طريقة CookieCollection::idx_get(int32_t) method

Returns a cookie from the cookie collection at the specified index.

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(int32_t index)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | فهرس الكوكي الذي يجب إرجاعه. |

### قيمة الإرجاع

كوكي في الفهرس المحدد.

## طريقة CookieCollection::idx_get(String) method

Returns a cookie from the cookie collection by specified name.

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(String name)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | اسم الكوكي الذي يجب إرجاعه. |

### قيمة الإرجاع

كوكي من مجموعة الكوكيات بالاسم المحدد عندما يتم العثور عليه، وإلا nullptr.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [Cookie](../../cookie/)
* فئة [CookieCollection](../)
* فئة [String](../../../system/string/)
* نطاق [System::Net](../../)
* مكتبة [Aspose.Slides](../../../)