---
title: NullableBoolHelper()
second_title: مرجع API Aspose.Slides برای C++
description: تابع کمکی برای بررسی اینکه this و other هر دو مقدار null نیستند و در صورت درست بودن یک لامبدا را فراخوانی می‌کند. در implementation.s استفاده می‌شود.
type: docs
weight: 105
url: /fa/system/nullable/nullableboolhelper/
---
## Nullable::NullableBoolHelper(const T1\&, const std::function\<bool()>\&, bool) const متد

تابع کمکی برای بررسی اینکه این و **other** هر دو مقدار null نیستند و در این صورت یک لامبدا را فراخوانی می‌کند. در implementation.s استفاده می‌شود.

```cpp
template<typename T1> bool System::Nullable<T>::NullableBoolHelper(const T1 &other, const std::function<bool()> &f, bool default_if_both_are_null=false) const
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع nullable دیگر. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| other | const T1\& | مقدار nullable دیگر برای مقایسه. |
| f | const std::function\<**bool**()>\& | لامبدایی که در صورت عدم null بودن هر دو **this** و **other** فراخوانی می‌شود. |
| default_if_both_are_null | **bool** | مقدار بازگشت اگر هر دو مقدار null باشند. |

### مقدار بازگشت

false اگر هر یک از **this** یا **other** null باشد؛ **default_if_both_are_null** اگر هر دو null باشند؛ نتیجه فراخوانی **f** اگر هر دو null نباشند.

## موارد مرتبط

* کلاس [Nullable](../)
* فضای نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)