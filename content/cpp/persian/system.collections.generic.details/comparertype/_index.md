---
title: ComparerType
second_title: مرجع API Aspose.Slides برای C++
description: عناصر را با استفاده از معنای 'less' مقایسه می‌کند.
type: docs
weight: 144
url: /fa/system.collections.generic.details/comparertype/
---
## ComparerType ساختار


عناصر را با استفاده از معنای 'less' مقایسه می‌کند.

```cpp
template<typename T>class ComparerType
```


### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | نوع عناصر مقایسه‌شده. |
## متدها

| Method | Description |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | انواع مقدار را که رابط [IComparable](../../system/icomparable/) را پیاده‌سازی می‌کنند مقایسه می‌کند. |
| std::enable_if<\!(std::is_base_of\<[IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value)&&\!std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | انواع مقدار اولیه و اشیائی را که رابط [IComparable](../../system/icomparable/) را پیاده‌سازی نمی‌کنند مقایسه می‌کند. |
| std::enable_if\<std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | انواع نقطه شناور را مقایسه می‌کند. |

## موارد مرتبط

* فضای‌نام [System::Collections::Generic::Details](../)
* کتابخانه [Aspose.Slides](../../)