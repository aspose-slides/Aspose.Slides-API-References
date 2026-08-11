---
title: setter_post_increment_wrap()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يترجم المترجم تعبيرات الزيادة اللاحقة في C# التي تستهدف خاصية الفئة التي لديها setter و getter معرفة، إلى استدعاء هذه الدالة.
type: docs
weight: 2848
url: /ar/system/setter_post_increment_wrap/
---
## System::setter_post_increment_wrap(T(*)(), void(*)(T)) function

يترجم المترجم تعبيرات الزيادة اللاحقة في C# التي تستهدف خاصية الفئة التي لديها setter و getter مُعرّف، إلى استدعاء هذه الدالة.

```cpp
template<typename T> T System::setter_post_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### معلمات القالب

| معمل | الوصف |
| --- | --- |
| T | نوع الخاصية |

### المعاملات

| معمل | النوع | الوصف |
| --- | --- | --- |
| pGetter | T(*)() | مؤشر دالة يُشير إلى دالة مجانية لمستقبل الخاصية |
| pSetter | void(*)(T) | مؤشر دالة يُشير إلى دالة مجانية لمُعَدِّل الخاصية |

### قيمة الإرجاع

قيمة الخاصية قبل الزيادة

## System::setter_post_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) function

يترجم المترجم تعبيرات الزيادة اللاحقة في C# التي تستهدف خاصية الكائن التي لديها setter و getter مُعرّف، إلى استدعاء هذه الدالة (إصدار overload للgetter غير الثابت).

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### معلمات القالب

| معمل | الوصف |
| --- | --- |
| T | نوع الخاصية. |
| Host | - الفئة الخاصة بالكائن الذي سيتم تعديله |
| HostGet | - الفئة Host نفسها، أو نوعها الأساسي، حيث يُعرّف getter الخاصية |
| HostSet | - الفئة Host نفسها، أو نوعها الأساسي، حيث يُعرّف setter الخاصية |

### المعاملات

| معمل | النوع | الوصف |
| --- | --- | --- |
| host | Host *const | الكائن الذي يتم استدعاء getter و setter له. |
| pGetter | T(HostGet::*)() | مؤشر دالة يُشير إلى دالة getter للخاصية |
| pSetter | void(HostSet::*)(T) | مؤشر دالة يُشير إلى دالة setter للخاصية |

### قيمة الإرجاع

قيمة الخاصية قبل الزيادة

## System::setter_post_increment_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) function

يترجم المترجم تعبيرات الزيادة اللاحقة في C# التي تستهدف خاصية الكائن التي لديها setter و getter مُعرّف، إلى استدعاء هذه الدالة (إصدار overload للgetter الثابت).

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_increment_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```

### معلمات القالب

| معمل | الوصف |
| --- | --- |
| T | نوع الخاصية. |
| Host | - الفئة الخاصة بالكائن الذي سيتم تعديله |
| HostConstGet | - الفئة Host نفسها، أو نوعها الأساسي، حيث يُعرّف getter الخاصية |
| HostSet | - الفئة Host نفسها، أو نوعها الأساسي، حيث يُعرّف setter الخاصية |

### المعاملات

| معمل | النوع | الوصف |
| --- | --- | --- |
| host | Host *const | الكائن الذي يتم استدعاء getter و setter له. |
| pGetter | T(HostConstGet::*)() const | مؤشر دالة يُشير إلى دالة getter للخاصية |
| pSetter | void(HostSet::*)(T) | مؤشر دالة يُشير إلى دالة setter للخاصية |

### قيمة الإرجاع

قيمة الخاصية قبل الزيادة

## انظر أيضًا

* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)