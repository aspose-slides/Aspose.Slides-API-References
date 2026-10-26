---
title: operator!=()
second_title: مرجع API Aspose.Slides برای C++
description: عملگر مقایسه نامساوی.
type: docs
weight: 313
url: /fa/system/string/operator_not_equal/
---
## String::operator!=(const String\&) const متد

عملگر مقایسه نامساوی.

```cpp
bool System::String::operator!=(const String &str) const
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) برای مقایسهٔ مورد فعلی با. |

### مقدار بازگشت

false اگر هر دو رشته null باشند یا هر دو null نباشند و برابر باشند، در غیر این صورت true.

## String::operator!=(std::nullptr_t) const متد

بررسی می‌کند که رشته null نیست. منطق مشابهی را همانند فراخوانی [IsNull()](../isnull/) اعمال می‌کند.

```cpp
bool System::String::operator!=(std::nullptr_t) const
```

### مقدار بازگشت

false اگر رشته null باشد، در غیر این صورت true.

## موارد مرتبط

* کلاس [String](../)
* فضای نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)