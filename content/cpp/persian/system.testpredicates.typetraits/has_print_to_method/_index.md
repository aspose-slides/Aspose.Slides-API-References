---
title: has_print_to_method
second_title: Aspose.Slides برای مرجع API C++
description: "بررسی می‌کند که آیا overloadی از تابع PrintTo وجود دارد که نوع داده‌شده را به‌عنوان اولین آرگومان می‌پذیرد. اگر overloadی وجود داشته باشد، از std::true_type ارث می‌برد، در غیر این صورت از std::false_type ارث می‌برد."
type: docs
weight: 27
url: /fa/system.testpredicates.typetraits/has_print_to_method/
---
## has_print_to_method struct

وجود overloadی برای تابع PrintTo که نوع داده‌شده را به‌عنوان اولین آرگومان می‌پذیرد، بررسی می‌کند. اگر overload وجود داشته باشد، از std::true_type ارث می‌برد، در غیر این صورت از std::false_type ارث می‌برد.

```cpp
template<typename T,typename Enable>class has_print_to_method : public std::false_type
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع برای بررسی. |
| Enable | آرگومان رسمی برای کارکرد SFINCE. |

## مراجع

* فضای نام [System::TestPredicates::TypeTraits](../)
* کتابخانه [Aspose.Slides](../../)