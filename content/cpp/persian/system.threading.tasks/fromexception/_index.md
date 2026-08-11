---
title: FromException()
second_title: مرجع API Aspose.Slides برای C++
description: یک Task ایجاد می‌کند که با یک استثنای مشخص تکمیل شده است.
type: docs
weight: 131
url: /fa/system.threading.tasks/fromexception/
---
## System::Threading::Tasks::FromException(const Exception\&) تابع

یک Task ایجاد می‌کند که با استثنای مشخص شده تکمیل شده است.

```cpp
TaskPtr System::Threading::Tasks::FromException(const Exception &exception)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | استثنایی که برای تکمیل Task استفاده می‌شود. |

### مقدار بازگشت

یک Task خراب.

## System::Threading::Tasks::FromException(const Exception\&) تابع

یک Task ایجاد می‌کند که با استثنای مشخص شده و نوع نتیجه تکمیل شده است.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::FromException(const Exception &exception)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TResult | نوع نتیجه Task. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | استثنایی که برای تکمیل Task استفاده می‌شود. |

### مقدار بازگشت

یک Task خراب با نوع نتیجه مشخص شده.

## موارد مرتبط

* تعریف‌نوع [TaskPtr](../../system/taskptr/)
* تعریف‌نوع [Exception](../../system/exception/)
* تعریف‌نوع [RTaskPtr](../../system/rtaskptr/)
* فضای‌نام [System::Threading::Tasks](../)
* کتابخانه [Aspose.Slides](../../)