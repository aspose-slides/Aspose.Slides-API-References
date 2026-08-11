---
title: Parallel
second_title: مرجع API Aspose.Slides برای C++
description: پشتیبانی از حلقه‌ها و نواحی موازی را فراهم می‌کند.
type: docs
weight: 1
url: /fa/system.threading.tasks/parallel/
---
## Parallel کلاس

پشتیبانی از حلقه‌ها و نواحی موازی را فراهم می‌کند.

```cpp
class Parallel
```

## متدها

| متد | توضیح |
| --- | --- |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[ParallelOptions](../paralleloptions/)\>\&, const [Action](../../system/action/)\<TSource\>\&) | عملیات foreach را بر روی یک IEnumerable اجرا می‌کند که در آن تکرارها می‌توانند به صورت موازی اجرا شوند. |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [Action](../../system/action/)\<TSource\>\&) | عملیات foreach را بر روی یک IEnumerable اجرا می‌کند که در آن تکرارها می‌توانند به صورت موازی اجرا شوند. |
## توضیحات

این کلاس متدهایی برای اجرای موازی حلقه‌ها و عملیات فراهم می‌کند. 
## موارد مرتبط

* فضای‌نام [System::Threading::Tasks](../)
* کتابخانه [Aspose.Slides](../../)