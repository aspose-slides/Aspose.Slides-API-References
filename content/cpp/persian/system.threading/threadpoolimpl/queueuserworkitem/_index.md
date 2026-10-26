---
title: QueueUserWorkItem()
second_title: مرجع API Aspose.Slides برای C++
description: آیتم کاری را به صف اضافه می‌کند.
type: docs
weight: 1
url: /fa/system.threading/threadpoolimpl/queueuserworkitem/
---
## ThreadPoolImpl::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) متد


آیتم کاری را به صف اضافه می‌کند.

```cpp
bool System::Threading::ThreadPoolImpl::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | تابع Callback برای اجرا. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | آرگومان تابع Callback. |

### مقدار بازگشت

همیشه true را برمی‌گرداند.

## موارد مرتبط

* تعریف نوع [WaitCallback](../../waitcallback/)
* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [Object](../../../system/object/)
* کلاس [ThreadPoolImpl](../)
* فضای نام [System::Threading](../../)
* کتابخانه [Aspose.Slides](../../../)