---
title: CancellationTokenRegistration
second_title: Aspose.Slides لـ C++ مرجع API
description: يمثل تسجيلًا لاستدعاء رمز إلغاء.
type: docs
weight: 27
url: /ar/system.threading/cancellationtokenregistration/
---
## CancellationTokenRegistration الفئة

يمثل تسجيلًا لاستدعاء رمز الإلغاء.

```cpp
class CancellationTokenRegistration
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| void [Dispose](./dispose/)() | تُفرغ التسجيل وتزيل الاستدعاء من [CancellationTokenSource](../cancellationtokensource/) المرتبط. بعد استدعاء هذه الطريقة، لن يتم استدعاء الاستدعاء المسجل بعد الآن عندما يتم إلغاء [CancellationTokenSource](../cancellationtokensource/) المرتبط. |
## ملاحظات

تسمح هذه الفئة بإلغاء تسجيل الاستدعاء من رمز إلغاء. عند التفريغ، تزيل الاستدعاء من [CancellationTokenSource](../cancellationtokensource/) المرتبط.  
هذه الفئة لا ينبغي إنشاؤها مباشرةً - يتم إرجاعها بواسطة طرق تسجيل [CancellationToken](../cancellationtoken/).

## انظر أيضًا

* النطاق [System::Threading](../)
* المكتبة [Aspose.Slides](../../)