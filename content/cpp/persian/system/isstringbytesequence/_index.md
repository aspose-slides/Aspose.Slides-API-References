---
title: IsStringByteSequence
second_title: Aspose.Slides برای C++ مرجع API
description: جادوی قالب برای بررسی اینکه آیا یک نوع توالی‌ای از کاراکترهای رشته است.
type: docs
weight: 1717
url: /fa/system/isstringbytesequence/
---
## ساختار IsStringByteSequence

جادوی قالب برای بررسی اینکه آیا یک نوع توالی‌ای از کاراکترهای رشته است.

```cpp
template<typename T,typename CharT>class IsStringByteSequence : public std::integral_constant<bool, std::is_same<std::remove_const<std::remove_pointer<std::decay<T>::type>::type>::type, CharT>::value>
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع بررسی‌شده. |
| CharT | نوع کاراکتری که باید بررسی شود. |

## مراجع

* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)