---
title: GetAwaiter()
second_title: Aspose.Slides برای C++ مرجع API
description: یک awaiter برای این result task دریافت می‌کند تا با Await استفاده شود.
type: docs
weight: 53
url: /fa/system.threading.tasks/resulttask/getawaiter/
---
## ResultTask::GetAwaiter() const متد

یک awaiter برای این ResultTask دریافت می‌کند تا با Await استفاده شود.

```cpp
Runtime::CompilerServices::ResultTaskAwaiter<T> System::Threading::Tasks::ResultTask<T>::GetAwaiter() const
```

### مقدار بازگشت

Runtime::CompilerServices::ResultTaskAwaiter<T> یک نمونه awaiter که نتیجه را برمی‌گرداند

## توضیحات

هنگامی که awaited شود، coroutine با مقدار نتیجه در دسترس از سر گرفته می‌شود 

## موارد مرتبط

* کلاس [ResultTaskAwaiter](../../../system.runtime.compilerservices/resulttaskawaiter/)
* کلاس [ResultTask](../)
* فضای‌نام [System::Threading::Tasks](../../)
* کتابخانه [Aspose.Slides](../../../)