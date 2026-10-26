---
title: has_method_compareto_shared_ptr
second_title: مستندات API Aspose.Slides برای C++
description: "بررسی می‌کند که آیا متد CompareTo(SharedPtr<T>) در نوع مشخص وجود دارد یا خیر. در صورت وجود، از std::true_type ارث می‌برد، در غیر این صورت از std::false_type ارث می‌برد. می‌تواند در std::enable_if استفاده شود."
type: docs
weight: 183
url: /fa/system.collections.generic.details/has_method_compareto_shared_ptr/
---
## has_method_compareto_shared_ptr ساختار

بررسی می‌کند آیا متد CompareTo(SharedPtr<T>) در نوع مشخص وجود دارد یا خیر. در این صورت از std::true_type ارث می‌برد، در غیر این صورت از std::false_type ارث می‌برد. می‌تواند در std::enable_if استفاده شود.

```cpp
template<typename T,typename Sfinae>class has_method_compareto_shared_ptr : public std::false_type
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوعی برای بررسی وجود متد Equals. |
| Sfinae | آرگومان قالب رسمی برای کار کردن SFINAE. |

## موارد مرتبط

* فضای‌نام [System::Collections::Generic::Details](../)
* کتابخانه [Aspose.Slides](../../)