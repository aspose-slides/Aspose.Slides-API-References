---
title: ExceptionWrapper()
second_title: مرجع API Aspose.Slides للغة C++
description: ينشئ نسخة فارغة من فئة ExceptionWrapper لا تمثل أي استثناء.
type: docs
weight: 14
url: /ar/system/exceptionwrapper/exceptionwrapper/
---
## ExceptionWrapper::ExceptionWrapper(std::nullptr_t) منشئ

ينشئ نسخة فارغة من الفئة [ExceptionWrapper](../) التي لا تمثل أي استثناء.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(std::nullptr_t)
```

## ExceptionWrapper::ExceptionWrapper(const ExceptionPtr\&) منشئ

ينشئ نسخة من الفئة [ExceptionWrapper](../) التي تحتوي على المؤشر الممرر.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionPtr &ptr)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| ptr | const [ExceptionPtr](../../exceptionptr/)\& | مؤشر ذكي إلى نسخة من الفئة Exception. |

## ExceptionWrapper::ExceptionWrapper(const ExceptionWrapper\&) منشئ

منشئ النسخ.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionWrapper &other)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| other | const [ExceptionWrapper](../)\& | نسخة أخرى من فئة الغلاف التي يجب نسخها. |

## ExceptionWrapper::ExceptionWrapper(ExceptionWrapper\&&) منشئ

منشئ النقل.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(ExceptionWrapper &&other) noexcept
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| other | [ExceptionWrapper](../)\&& | نسخة أخرى من فئة الغلاف التي يجب نقلها. |

## ExceptionWrapper::ExceptionWrapper(Args\&&...) منشئ

منشئ يمرر المعاملات إلى منشئي الفئة Exception وينشئ مؤشرًا ذكيًا يحتفظ بنسخة جديدة من فئة Exception.

```cpp
template<typename ...,typename> System::ExceptionWrapper<T>::ExceptionWrapper(Args &&...args)
```

## انظر أيضًا

* Typedef [ExceptionPtr](../../exceptionptr/)
* Class [ExceptionWrapper](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)