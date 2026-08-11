---
title: CastEnumerableTo()
second_title: Aspose.Slides برای C++ مرجع API
description: تبدیل صریح عناصر شیء enumerable مشخص به نوع متفاوت را انجام می‌دهد.
type: docs
weight: 2965
url: /fa/system/castenumerableto/
---
## System::CastEnumerableTo(const From&) تابع

انجام تبدیل صریح عناصر شیء enumerable مشخص به نوع متفاوت.

```cpp
template<class To,class From> std::enable_if<!System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| To | نوعی که عناصر شیء enumerable به صورت ثابت به آن تبدیل می‌شوند |
| From | نوع شیء enumerable |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| enumerable | const From& | شیء enumerable شامل عناصری که باید تبدیل شوند |

### مقدار بازگشت

یک اشاره‌گر به مجموعه جدیدی که عناصر از نوع **To** معادل عناصر **enumerable** دارد

## System::CastEnumerableTo(const From&) تابع

انجام تبدیل صریح عناصر شیء enumerable مشخص به نوع متفاوت.

```cpp
template<class To,class From> std::enable_if<System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| To | نوعی که عناصر شیء enumerable به صورت ثابت به آن تبدیل می‌شوند |
| From | نوع شیء enumerable |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| enumerable | const From& | یک ارث‌باز از شیء Enumerable با متد get_Count تعریف‌شده که شامل عناصری برای تبدیل است |

### مقدار بازگشت

یک اشاره‌گر به مجموعه جدیدی که عناصر از نوع **To** معادل عناصر **enumerable** دارد

## موارد مرتبط

* کلاس [ListPtr](../../system.collections.generic/listptr/)
* فضای نام [System](../)
* کتابخانه [Aspose.Slides](../../)