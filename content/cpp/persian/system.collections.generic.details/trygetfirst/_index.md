---
title: TryGetFirst()
second_title: مرجع API Aspose.Slides برای C++
description: سعی می‌کند اولین عنصر مجموعه را دریافت کند.
type: docs
weight: 248
url: /fa/system.collections.generic.details/trygetfirst/
---
## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, bool\&) تابع

سعی می‌کند عنصر اول مجموعه را دریافت کند.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, bool &found)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر مجموعه. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | مجموعه‌ای که از آن عنصر دریافت شود. |
| found | **bool**\& | پارامتر خروجی. وقتی مجموعه حاوی هر عنصری باشد true برمی‌گرداند. در غیر این صورت false برمی‌گردد. |

### مقدار بازگشت

اولین عنصر مجموعه را برمی‌گرداند. مقدار پیش‌فرض نوع زمانی که مجموعه خالی باشد برگردانده می‌شود.

## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, const Func\<T, bool\>\&, bool\&) تابع

سعی می‌کند اولین عنصر مجموعه را که تابع پیش‌شرط را برآورده می‌کند، دریافت کند.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, const Func<T, bool> &predicate, bool &found)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر مجموعه. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | مجموعه‌ای که از آن عنصر دریافت شود. |
| predicate | const [Func](../../system/func/)\<T, **bool**\>\& | تابع پیش‌شرط. |
| found | **bool**\& | پارامتر خروجی. وقتی مجموعه حاوی هر عنصری باشد true برمی‌گرداند. در غیر این صورت false برمی‌گردد. |

### مقدار بازگشت

اولین عنصر مجموعه را برمی‌گرداند. مقدار پیش‌فرض نوع زمانی که عنصری که تابع پیش‌شرط مشخص شده را برآورده کند یافت نشود، برگردانده می‌شود.

## موارد مرتبط

* کلاس [IEnumerable](../../system.collections.generic/ienumerable/)
* کلاس [Func](../../system/func/)
* فضای‌نام [System::Collections::Generic::Details](../)
* کتابخانه [Aspose.Slides](../../)