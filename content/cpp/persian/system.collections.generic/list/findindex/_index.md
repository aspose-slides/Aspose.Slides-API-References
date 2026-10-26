---
title: FindIndex()
second_title: مرجع API Aspose.Slides برای C++
description: عنصری را جستجو می‌کند که به شرط خاصی پایبند باشد.
type: docs
weight: 404
url: /fa/system.collections.generic/list/findindex/
---
## List::FindIndex(System::Predicate\<T\>) متد

به دنبال عنصری می‌گردد که به شرط خاصی پایبند باشد.

```cpp
int System::Collections::Generic::List<T>::FindIndex(System::Predicate<T> match)
```

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| match | [System::Predicate](../../../system/predicate/)\<T\> | پیش‌شرط برای بررسی عناصر. |

### مقدار بازگشت

[Index](../../../system/index/) از عنصر منطبق یا -1 اگر یافت نشد.

## List::FindIndex(int, System::Predicate\<T\>) متد

به دنبال عنصری می‌گردد که به شرط خاصی پایبند باشد.

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, System::Predicate<T> match)
```

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| startIndex | int | [Index](../../../system/index/) برای شروع جستجو از. |
| match | [System::Predicate](../../../system/predicate/)\<T\> | پیش‌شرط برای بررسی عناصر. |

### مقدار بازگشت

[Index](../../../system/index/) از عنصر منطبق یا -1 اگر یافت نشد.

## List::FindIndex(int, int, System::Predicate\<T\>) متد

به دنبال عنصری می‌گردد که به شرط خاصی پایبند باشد.

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, int count, System::Predicate<T> match)
```

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| startIndex | int | [Index](../../../system/index/) برای شروع جستجو از. |
| count | int | تعداد عناصری که باید بررسی شوند. |
| match | [System::Predicate](../../../system/predicate/)\<T\> | پیش‌شرط برای بررسی عناصر. |

### مقدار بازگشت

[Index](../../../system/index/) از عنصر منطبق یا -1 اگر یافت نشد.

## موارد مرتبط

* Typedef [Predicate](../../../system/predicate/)
* کلاس [List](../)
* فضای‌نام [System::Collections::Generic](../../)
* کتابخانه [Aspose.Slides](../../../)