---
title: WhenAll()
second_title: مرجع API Aspose.Slides برای C++
description: کاری را ایجاد می‌کند که پس از تکمیل تمام کارهای ارائه‌شده به پایان می‌رسد.
type: docs
weight: 196
url: /fa/system.threading.tasks/whenall/
---
## System::Threading::Tasks::WhenAll(const ArrayPtr\<TaskPtr\>\&) function

یک کار را ایجاد می‌کند که پس از تکمیل تمام کارهای ارائه‌شده به اتمام می‌رسد.

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const ArrayPtr<TaskPtr> &tasks)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | کارهایی که باید برای تکمیل منتظر آنها بود. |

### مقدار برگشتی

کاری که نمایانگر تکمیل تمام کارهای ارائه‌شده است.

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) function

یک کار را ایجاد می‌کند که پس از تکمیل تمام کارهای ارائه‌شده به اتمام می‌رسد.

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | کارهایی که باید برای تکمیل منتظر آنها بود. |

### مقدار برگشتی

کاری که نمایانگر تکمیل تمام کارهای ارائه‌شده است.

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) function

یک کار را ایجاد می‌کند که پس از تکمیل تمام کارهای ارائه‌شده به اتمام می‌رسد.

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TResult | نوع نتایج کارهای تکمیل‌شده. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | کارهایی که باید برای تکمیل منتظر آنها بود. |

### مقدار برگشتی

کاری که آرایه‌ای از همه نتایج را وقتی تمام کارها کامل شوند برمی‌گرداند.

## System::Threading::Tasks::WhenAll(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) function

یک کار را ایجاد می‌کند که پس از تکمیل تمام کارهای ارائه‌شده به اتمام می‌رسد.

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TResult | نوع نتایج کارهای تکمیل‌شده. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | کارهایی که باید برای تکمیل منتظر آنها بود. |

### مقدار برگشتی

کاری که آرایه‌ای از همه نتایج را وقتی تمام کارها کامل شوند برمی‌گرداند.

## مراجع

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)