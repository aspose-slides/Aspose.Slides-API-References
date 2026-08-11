---
title: IsBoxable
second_title: مرجع API Aspose.Slides برای C++
description: پیش‌شرط قالبی که بررسی می‌کند آیا جعبه‌سازی از نوع مشخص شده پشتیبانی می‌شود.
type: docs
weight: 1665
url: /fa/system/isboxable/
---
## IsBoxable struct

پیش‌شرط قالبی که بررسی می‌کند آیا جعبه‌سازی از نوع مشخص شده پشتیبانی می‌شود.

```cpp
template<typename T>class IsBoxable : public std::integral_constant<bool, std::is_base_of<Details::BoxableObjectBase, T>::value||std::is_arithmetic<T>::value||std::is_enum<T>::value>
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوعی که باید بررسی شود |

## همچنین ببینید

* Namespace [System](../)
* Library [Aspose.Slides](../../)