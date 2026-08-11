---
title: IsStringLiteral
second_title: مرجع API Aspose.Slides برای C++
description: جادوی قالب برای بررسی اینکه آیا یک نوع یک مقدار ثابت رشته‌ای است.
type: docs
weight: 1730
url: /fa/system/isstringliteral/
---
## ساختار IsStringLiteral

جادوی قالب برای بررسی اینکه آیا یک نوع یک مقدار ثابت رشته‌ای است.

```cpp
template<typename T,typename CharT>class IsStringLiteral : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_array<T>::value>
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع بررسی شده. |
| CharT | نوع کاراکتر برای مقایسه. |

## موارد مرتبط

* فضای نام [System](../)
* کتابخانه [Aspose.Slides](../../)