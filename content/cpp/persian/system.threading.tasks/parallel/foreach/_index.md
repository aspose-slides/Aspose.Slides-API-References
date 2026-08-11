---
title: ForEach()
second_title: مرجع API Aspose.Slides برای C++
description: یک عملیات foreach را بر روی IEnumerable اجرا می‌کند که در آن تکرارها می‌توانند به صورت همزمان اجرا شوند.
type: docs
weight: 1
url: /fa/system.threading.tasks/parallel/foreach/
---
## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const SharedPtr\<ParallelOptions\>\&, const Action\<TSource\>\&) متد

یک عملیات foreach را بر روی IEnumerable اجرا می‌کند که در آن تکرارها می‌توانند به صورت همزمان اجرا شوند.

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const SharedPtr<ParallelOptions> &parallelOptions, const Action<TSource> &body)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| TSource | نوع داده‌ها در منبع. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | یک منبع داده‌ی قابل شمارش. |
| parallelOptions | const [SharedPtr](../../../system/sharedptr/)\<[ParallelOptions](../../paralleloptions/)\>\& | شیئی که رفتار این عملیات را پیکربندی می‌کند. |
| body | const [Action](../../../system/action/)\<TSource\>\& | نماینده‌ای که در هر تکرار یک‌بار فراخوانی می‌شود. |

### مقدار بازگشت

یک ساختار [ParallelLoopResult](../../parallelloopresult/) که اطلاعاتی دربارهٔ بخش تکمیل‌شدهٔ حلقه را شامل می‌شود.

## یادداشت‌ها

این متد منبع قابل شمارش را تقسیم می‌کند و نماینده body را به صورت همزمان بر روی چندین رشته اجرا می‌نماید.

## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const Action\<TSource\>\&) متد

یک عملیات foreach را بر روی IEnumerable اجرا می‌کند که در آن تکرارها می‌توانند به صورت همزمان اجرا شوند.

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const Action<TSource> &body)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| TSource | نوع داده‌ها در منبع. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | یک منبع داده‌ی قابل شمارش. |
| body | const [Action](../../../system/action/)\<TSource\>\& | نماینده‌ای که در هر تکرار یک‌بار فراخوانی می‌شود. |

### مقدار بازگشت

یک ساختار [ParallelLoopResult](../../parallelloopresult/) که اطلاعاتی دربارهٔ بخش تکمیل‌شدهٔ حلقه را شامل می‌شود.

## یادداشت‌ها

از [ParallelOptions](../../paralleloptions/) پیش‌فرض با موازی‌سازی نامحدود و بدون لغو استفاده می‌کند.

## مراجع

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Action](../../../system/action/)
* کلاس [ParallelLoopResult](../../parallelloopresult/)
* کلاس [IEnumerable](../../../system.collections.generic/ienumerable/)
* کلاس [ParallelOptions](../../paralleloptions/)
* کلاس [Parallel](../)
* فضای‌نام [System::Threading::Tasks](../../)
* کتابخانه [Aspose.Slides](../../../)