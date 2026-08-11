---
title: AsTask()
second_title: مرجع API Aspose.Slides برای C++
description: این ResultValueTask را به یک shared pointer به ResultTask<T> تبدیل می‌کند.
type: docs
weight: 79
url: /fa/system.threading.tasks/resultvaluetask/astask/
---
## ResultValueTask::AsTask() const متد

این [ResultValueTask](../) را به یک shared pointer به ResultTask<T> تبدیل می‌کند.

```cpp
RTaskPtr<T> System::Threading::Tasks::ResultValueTask<T>::AsTask() const
```

### مقدار بازگشت

RTaskPtr<T> یک shared pointer به ResultTask<T> که این عملیات را نمایش می‌دهد.

## توضیحات

اگر [ResultValueTask](../) دارای یک نتیجه مستقیم باشد، یک task تکمیل‌شده با آن نتیجه ایجاد می‌کند. اگر شامل یک task باشد، یک shared pointer به آن task را برمی‌گرداند.

## موارد مرتبط

* typedef [RTaskPtr](../../../system/rtaskptr/)
* کلاس [ResultValueTask](../)
* فضای‌نام [System::Threading::Tasks](../../)
* کتابخانه [Aspose.Slides](../../../)