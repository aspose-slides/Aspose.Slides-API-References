---
title: QueueUserWorkItem()
second_title: Aspose.Slides برای مرجع API C++
description: آیتم کاری را در صفی قرار می‌دهد که با callback بدون پارامتر موجود است.
type: docs
weight: 14
url: /fa/system.threading/threadpool/queueuserworkitem/
---
## ThreadPool::QueueUserWorkItem(WaitCallback) متد

آیتم کاری را در صفی قرار می‌دهد که با callback بدون پارامتر موجود است.

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Callback function to be used as a job. |

### مقدار بازگشت

همیشه true را بر می‌گرداند.

## ThreadPool::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) متد

آیتم کاری را در صفی قرار می‌دهد که با callback بدون پارامتر موجود است.

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Callback function to be used as a job. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Job function parameter. |

### مقدار بازگشت

همیشه true را بر می‌گرداند.

## موارد مرتبط

* تعریف نوع [WaitCallback](../../waitcallback/)
* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ThreadPool](../)
* کلاس [Object](../../../system/object/)
* فضای‌نام [System::Threading](../../)
* کتابخانه [Aspose.Slides](../../../)