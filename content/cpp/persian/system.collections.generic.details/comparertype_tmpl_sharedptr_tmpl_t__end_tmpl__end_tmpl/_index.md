---
title: ComparerType< SharedPtr< T > >
second_title: مرجع API Aspose.Slides برای C++
description: عناصر را با استفاده از معنای 'کمتر' مقایسه می‌کند.
type: docs
weight: 157
url: /fa/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/
---
## ComparerType< SharedPtr< T > > struct

عناصر را با استفاده از معنای 'کمتر' مقایسه می‌کند.

```cpp
template<typename T>class ComparerType< SharedPtr< T > >
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر مقایسه‌شده. |

## متدها

| متد | توضیح |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | انواع اشاره‌گرهایی که رابط [IComparable](../../system/icomparable/) را پیاده‌سازی می‌کنند، مقایسه می‌کند. |
| std::enable_if<\!(std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value), **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | انواع اشاره‌گرهایی که رابط [IComparable](../../system/icomparable/) را پیاده‌سازی نمی‌کنند، مقایسه می‌کند. |

## موارد مرتبط

* فضای‌نام [System::Collections::Generic::Details](../)
* کتابخانه [Aspose.Slides](../../)