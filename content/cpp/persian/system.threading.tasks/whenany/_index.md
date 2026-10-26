---
title: WhenAny()
second_title: مستندات API Aspose.Slides برای C++
description: یک تسک ایجاد می‌کند که وقتی هر یک از تسک‌های ارائه‌شده تکمیل شوند، تکمیل می‌شود.
type: docs
weight: 209
url: /fa/system.threading.tasks/whenany/
---
## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) تابع

یک تسک ایجاد می‌کند که وقتی هر یک از تسک‌های ارائه‌شده تکمیل شوند، تکمیل می‌شود.

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | تسک‌های منتظر برای تکمیل. |

### مقدار بازگشت

یک تسک که نمایانگر تکمیل یکی از تسک‌های ارائه‌شده است.

## System::Threading::Tasks::WhenAny(const ArrayPtr\<TaskPtr\>\&) تابع

یک تسک ایجاد می‌کند که وقتی هر یک از تسک‌های ارائه‌شده تکمیل شوند، تکمیل می‌شود.

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const ArrayPtr<TaskPtr> &tasks)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | تسک‌های منتظر برای تکمیل. |

### مقدار بازگشت

یک تسک که نمایانگر تکمیل یکی از تسک‌های ارائه‌شده است.

## System::Threading::Tasks::WhenAny(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) تابع

یک تسک ایجاد می‌کند که وقتی هر یک از تسک‌های ارائه‌شده تکمیل شوند، تکمیل می‌شود.

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TResult | نوع نتیجه تسک تکمیل‌شده. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | تسک‌های منتظر برای تکمیل. |

### مقدار بازگشت

یک تسک که اولین تسک تکمیل‌شده را وقتی هر تسکی تکمیل می‌شود برمی‌گرداند.

## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) تابع

یک تسک ایجاد می‌کند که وقتی هر یک از تسک‌های ارائه‌شده تکمیل شوند، تکمیل می‌شود.

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TResult | نوع نتیجه تسک تکمیل‌شده. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | تسک‌های منتظر برای تکمیل. |

### مقدار بازگشت

یک تسک که اولین تسک تکمیل‌شده را وقتی هر تسکی تکمیل می‌شود برمی‌گرداند.

## موارد مرتبط

* تعریف‌نوع [RTaskPtr](../../system/rtaskptr/)
* تعریف‌نوع [TaskPtr](../../system/taskptr/)
* تعریف‌نوع [SharedPtr](../../system/sharedptr/)
* تعریف‌نوع [ArrayPtr](../../system/arrayptr/)
* کلاس [IEnumerable](../../system.collections.generic/ienumerable/)
* فضای‌نام [System::Threading::Tasks](../)
* کتابخانه [Aspose.Slides](../../)