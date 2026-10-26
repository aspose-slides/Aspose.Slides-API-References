---
title: Yield()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ مهمة قابلة للانتظار تُعيد التحكم بشكل غير متزامن إلى السياق الحالي عند الانتظار.
type: docs
weight: 222
url: /ar/system.threading.tasks/yield/
---
## System::Threading::Tasks::Yield() دالة


ينشئ مهمة قابلة للانتظار تُعيد التحكم بشكل غير متزامن إلى السياق الحالي عند الانتظار.

```cpp
Runtime::CompilerServices::YieldAwaitable System::Threading::Tasks::Yield()
```


### قيمة الإرجاع

كائن YieldAwaitable يمكن الانتظار عليه لإعادة التحكم.
## ملاحظات



هذه الطريقة مفيدة لإجبار طريقة غير متزامنة على إعادة التحكم، مما يسمح بمعالجة الأعمال المعلقة الأخرى قبل المتابعة. 
## أنظر أيضًا

* الفئة [YieldAwaitable](../../system.runtime.compilerservices/yieldawaitable/)
* النطاق [System::Threading::Tasks](../)
* المكتبة [Aspose.Slides](../../)