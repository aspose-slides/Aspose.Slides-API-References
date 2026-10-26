---
title: Default()
second_title: مرجع Aspose.Slides لـ C++ API
description: يرجع المرجع إلى النسخة الواحدة التي تم إنشاؤها افتراضيًا من نوع الاستثناء.
type: docs
weight: 2224
url: /ar/system/default/
---
## System::Default() الدالة

يرجع المرجع إلى النسخة الواحدة التي تم إنشاؤها افتراضيًا من نوع الاستثناء.

```cpp
template<typename T> std::enable_if<IsExceptionWrapper<T>::value, constT &>::type System::Default()
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | النوع الذي تُرجع مثاله |

## System::Default() الدالة

يرجع المرجع إلى النسخة الواحدة التي تم إنشاؤها افتراضيًا من النوع غير الاستثنائي.

```cpp
template<typename T> std::enable_if<!IsExceptionWrapper<T>::value, constT &>::type System::Default()
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | النوع الذي تُرجع مثاله |

## انظر أيضًا

* بنية [IsExceptionWrapper](../isexceptionwrapper/)
* مساحة الاسم [System](../)
* المكتبة [Aspose.Slides](../../)