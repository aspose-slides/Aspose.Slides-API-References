---
title: setter_decrement_wrap()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم المترجم بترجمة تعبيرات ما قبل الإنقاص في C# التي تستهدف خاصية الفئة التي تم تعريف كل من المُعيّن والمُستخرج لها، إلى استدعاء هذه الدالة.
type: docs
weight: 2861
url: /ar/system/setter_decrement_wrap/
---
## System::setter_decrement_wrap(T(*)(), void(*)(T)) دالة

المترجم يترجم تعبيرات ما قبل الإنقاص في C# التي تستهدف خاصية الفئة التي تم تعريف كل من المُعيّن والمُستخرج لها، إلى استدعاء هذه الدالة.

```cpp
template<typename T> T System::setter_decrement_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### معلمات القالب

| المعلمة | الوصف |
| --- | --- |
| T | نوع الخاصية |

### المعطيات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| pGetter | T(*)() | مؤشر دالة يشير إلى الدالة المستقلة للمُستخرج الخاص بالخاصية |
| pSetter | void(*)(T) | مؤشر دالة يشير إلى الدالة المستقلة للمُعيّن الخاص بالخاصية |

### قيمة الإرجاع

قيمة الخاصية قبل الإنقاص

## System::setter_decrement_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) دالة

المترجم يترجم تعبيرات ما قبل الإنقاص في C# التي تستهدف خاصية المثيل التي تم تعريف كل من المُعيّن والمُستخرج لها، إلى استدعاء هذه الدالة (إصدار للـ getter غير الثابت).

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_decrement_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### معلمات القالب

| المعلمة | الوصف |
| --- | --- |
| T | نوع الخاصية. |
| Host | - فئة المثيل المراد تعديلها |
| HostGet | - الـ Host نفسه، أو النوع الأساسي له، حيث تم تعريف مُستخرج الخاصية |
| HostSet | - الـ Host نفسه، أو النوع الأساسي له، حيث تم تعريف مُعيّن الخاصية |

### المعطيات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| host | Host *const | المثيل الذي يتم استدعاء المُستخرج والمُعيّن له. |
| pGetter | T(HostGet::*)() | مؤشر دالة يشير إلى دالة المُستخرج للخاصية |
| pSetter | void(HostSet::*)(T) | مؤشر دالة يشير إلى دالة المُعيّن للخاصية |

### قيمة الإرجاع

قيمة الخاصية قبل الإنقاص

## System::setter_decrement_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) دالة

المترجم يترجم تعبيرات ما قبل الإنقاص في C# التي تستهدف خاصية المثيل التي تم تعريف كل من المُعيّن والمُستخرج لها، إلى استدعاء هذه الدالة (إصدار للـ getter الثابت).

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_decrement_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```

### معلمات القالب

| المعلمة | الوصف |
| --- | --- |
| T | نوع الخاصية. |
| Host | - فئة المثيل المراد تعديلها |
| HostConstGet | - الـ Host نفسه، أو النوع الأساسي له، حيث تم تعريف مُستخرج الخاصية |
| HostSet | - الـ Host نفسه، أو النوع الأساسي له، حيث تم تعريف مُعيّن الخاصية |

### المعطيات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| host | Host *const | المثيل الذي يتم استدعاء المُستخرج والمُعيّن له. |
| pGetter | T(HostConstGet::*)() const | مؤشر دالة يشير إلى دالة المُستخرج للخاصية |
| pSetter | void(HostSet::*)(T) | مؤشر دالة يشير إلى دالة المُعيّن للخاصية |

### قيمة الإرجاع

قيمة الخاصية قبل الإنقاص

## انظر أيضًا

* Namespace [System](../)
* Library [Aspose.Slides](../../)