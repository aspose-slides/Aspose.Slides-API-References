---
title: ExceptionWrapper
second_title: Aspose.Slides لـ C++ مرجع API
description: قالب يمثل غلاف الاستثناءات المشتقة من فئة Exception.
type: docs
weight: 833
url: /ar/system/exceptionwrapper/
---
## ExceptionWrapper فئة

قالب يمثل غلاف الاستثناءات المستمدة من فئة Exception.

```cpp
template<typename T>class ExceptionWrapper
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
|  [ExceptionWrapper](./exceptionwrapper/)(std::nullptr_t) | يُنشئ نسخة فارغة من فئة [ExceptionWrapper](./) التي لا تمثل أي استثناء. |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionPtr](../exceptionptr/)\&) | يُنشئ نسخة من فئة [ExceptionWrapper](./) التي تحتوي على المؤشر الممرَّ. |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionWrapper](./)\&) | منشئ النسخة. |
|  [ExceptionWrapper](./exceptionwrapper/)([ExceptionWrapper](./)\&&) | منشئ النقل. |
| explicit  [ExceptionWrapper](./exceptionwrapper/)(Args\&&...) | منشئ يمرّر المعلمات إلى منشئي فئة Exception ويُنشئ مؤشرًا ذكيًا يحمل نسخة جديدة من فئة Exception. |
| static void * [operator new](./operator_new/)(std::size_t) |  |
| static void * [operator new[]](./operator_new[]/)(std::size_t) |  |
|  [operator SharedPtr< Object >](./operator_sharedptr_less_object__greater/)() | عامل تحويل ضمني إلى SharedPtr<Object> |
| T * [operator->](./operator_minus_greater/)() const | يسمح بالوصول إلى أعضاء كائن Exception. |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)(const [ExceptionWrapper](./)\&) | عامل الإسناد. |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)([ExceptionWrapper](./)\&&) | عامل إسناد النقل. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() | اختصار للحصول على كائن [System::TypeInfo](../typeinfo/) لنوع Exception. |
## الأنواع التعريفية

| التعريف | الوصف |
| --- | --- |
| [ExceptionType](./exceptiontype/) | يُستخدم لتوابع التحويل. |
## انظر أيضًا

* مساحة الأسماء [System](../)
* مكتبة [Aspose.Slides](../../)