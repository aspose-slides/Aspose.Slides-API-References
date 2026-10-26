---
title: get_Result()
second_title: Aspose.Slides برای C++ مرجع API
description: نتیجهٔ کار تکمیل‌شده را دریافت می‌کند.
type: docs
weight: 66
url: /fa/system.threading.tasks/resultvaluetask/get_result/
---
## ResultValueTask::get_Result() متد

نتیجهٔ کار تکمیل‌شده را دریافت می‌کند.

```cpp
T System::Threading::Tasks::ResultValueTask<T>::get_Result()
```

### مقدار بازگشتی

T مقدار نتیجه.

## ملاحظات

اگر کار توسط ResultTask<T> پشتیبانی شود، این متد صبر می‌کند تا نتیجه آماده شود و آن را در حافظهٔ موقت ذخیره می‌کند. فراخوانی‌های بعدی مقدار ذخیره‌شده را بدون await برمی‌گردانند. 

## همچنین ببینید

* کلاس [ResultValueTask](../)
* فضای نام [System::Threading::Tasks](../../)
* کتابخانه [Aspose.Slides](../../../)