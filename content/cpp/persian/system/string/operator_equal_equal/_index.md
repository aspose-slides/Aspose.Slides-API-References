---
title: operator==()
second_title: Aspose.Slides برای C++ مرجع API
description: عملگر مقایسهٔ مساوی.
type: docs
weight: 300
url: /fa/system/string/operator_equal_equal/
---
## String::operator==(const String\&) const متد

عملگر مقایسه مساوی.

```cpp
bool System::String::operator==(const String &str) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) برای مقایسهٔ مورد فعلی. |

### مقدار بازگشت

در صورتی که هر دو رشته null باشند یا هر دو null نباشند و برابر باشند، true؛ در غیر این صورت false.

## String::operator==(std::nullptr_t) const متد

بررسی می‌کند که آیا رشته null است یا خیر. همان منطق [IsNull()](../isnull/) فراخوانی اعمال می‌شود.

```cpp
bool System::String::operator==(std::nullptr_t) const
```

### مقدار بازگشت

در صورتی که رشته null باشد، true؛ در غیر این صورت false.

## موارد مرتبط

* کلاس [String](../)
* فضای نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)