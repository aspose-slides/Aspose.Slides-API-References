---
title: ConfigureAwait()
second_title: Aspose.Slides برای مرجع API C++
description: پیکربندی می‌کند که awaitها بر روی این ResultTask چگونه نسبت به capture زمینه رفتار کنند.
type: docs
weight: 27
url: /fa/system.threading.tasks/resulttask/configureawait/
---
## ResultTask::ConfigureAwait(bool) const متد


پیکربندی می‌کند که awaitها بر روی این ResultTask چگونه نسبت به capture زمینه رفتار کنند.

```cpp
Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> System::Threading::Tasks::ResultTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | این که آیا باید در زمینه capture شده ادامه یابد |

### مقدار بازگشت

Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> A configured awaitable for the result
## توضیحات



این امکان کنترل دقیق جریان زمینه برای الگوهای async/await را فراهم می‌کند. 

## موارد مرتبط

* کلاس [ConfiguredResultTaskAwaitable](../../../system.runtime.compilerservices/configuredresulttaskawaitable/)
* کلاس [ResultTask](../)
* فضای نام [System::Threading::Tasks](../../)
* کتابخانه [Aspose.Slides](../../../)