---
title: AbstractEqual()
second_title: Aspose.Slides برای C++ مرجع API
description: دو مجموعه از نوع نامشخص را مقایسه می‌کند.
type: docs
weight: 14
url: /fa/system/testcompare/abstractequal/
---
## TestCompare::AbstractEqual(SCG::ICollection\<T\> *const, SCG::ICollection\<T\> *const) متد

دو مجموعه از نوع نامشخص را مقایسه می‌کند.

```cpp
template<typename T> static bool System::TestCompare::AbstractEqual(SCG::ICollection<T> *const collA, SCG::ICollection<T> *const collB)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عنصر مجموعه. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| collA | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | مجموعه سمت چپ. |
| collB | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | مجموعه سمت راست. |

### مقدار بازگشت

در صورتی که مجموعه‌ها مطابقت داشته باشند (مثلاً هر دو تهی باشند) یا اندازه‌ها و عناصر مطابقت داشته باشند، مقدار true برگردانده می‌شود؛ در غیر این صورت مقدار false.

## موارد مرتبط

* کلاس [ICollection](../../../system.collections.generic/icollection/)
* ساختار [TestCompare](../)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)