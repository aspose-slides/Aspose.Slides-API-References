---
title: ConfigureAwait()
second_title: مرجع API Aspose.Slides برای C++
description: یک awaiter را برای این تسک پیکربندی می‌کند.
type: docs
weight: 79
url: /fa/system.threading.tasks/valuetask/configureawait/
---
## ValueTask::ConfigureAwait(bool) const متد

یک awaiter را برای این تسک پیکربندی می‌کند.

```cpp
Runtime::CompilerServices::ConfiguredValueTaskAwaitable System::Threading::Tasks::ValueTask::ConfigureAwait(bool continueOnCapturedContext) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | true برای تلاش به انتقال ادامه به زمینهٔ اصلی که ضبط شده است؛ در غیر این صورت false. |

## مقدار بازگشت

ConfiguredValueTaskAwaitable یک شی که نحوهٔ رفتار awaiterها برای این کار را تنظیم می‌کند.

## موارد مرتبط

* کلاس [ConfiguredValueTaskAwaitable](../../../system.runtime.compilerservices/configuredvaluetaskawaitable/)
* کلاس [ValueTask](../)
* فضای‌نام [System::Threading::Tasks](../../)
* کتابخانه [Aspose.Slides](../../../)