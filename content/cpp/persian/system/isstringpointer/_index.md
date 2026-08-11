---
title: IsStringPointer
second_title: مرجع API برای Aspose.Slides برای C++
description: جادوی قالب برای بررسی اینکه آیا یک نوع اشاره‌گر به رشته کاراکتری است.
type: docs
weight: 1743
url: /fa/system/isstringpointer/
---
## ساختار IsStringPointer

جادوی قالب برای بررسی اینکه آیا یک نوع اشاره‌گر به رشته کاراکتری است.

```cpp
template<typename T,typename CharT>class IsStringPointer : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_pointer<T>::value>
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع بررسی‌شده. |
| CharT | نوع کاراکتر برای مقایسه. |

## موارد مرتبط

* فضای نام [System](../)
* کتابخانه [Aspose.Slides](../../)