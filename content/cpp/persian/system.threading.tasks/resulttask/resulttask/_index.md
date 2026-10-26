---
title: ResultTask()
second_title: مرجع API Aspose.Slides برای C++
description: ResultTask را با تابعی که مقدار را برمی‌گرداند می‌سازد.
type: docs
weight: 1
url: /fa/system.threading.tasks/resulttask/resulttask/
---
## ResultTask::ResultTask(const Func\<T\>\&) سازنده

یک [ResultTask](../) را با تابعی که مقدار باز می‌گرداند می‌سازد.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const Func<T> &function)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| function | const [Func](../../../system/func/)\<T\>\& | تابعی که به‌صورت ناهمزمان اجرا می‌شود و نتیجه‌ای بر می‌گرداند |

## ResultTask::ResultTask() سازنده

پیاده‌سازی داخلی. نه برای کد کاربر.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask()
```

## ملاحظات

سازنده داخلی برای ایجاد تسک‌های نتیجه‌ای که مقداردهی اولیه نشده‌اند

## ResultTask::ResultTask(const T\&) سازنده

سازنده داخلی برای ایجاد تسک‌های نتیجه‌ای با نتیجهٔ مشخص شده.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const T &result)
```

## مراجع

* کلاس [Func](../../../system/func/)
* کلاس [ResultTask](../)
* فضای‌نام [System::Threading::Tasks](../../)
* کتابخانه [Aspose.Slides](../../../)