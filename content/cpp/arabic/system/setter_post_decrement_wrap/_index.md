---
title: setter_post_decrement_wrap()
second_title: Aspose.Slides للـ C++ – مرجع API
description: المترجم يترجم تعبيرات ما بعد الإنقاص في C# التي تستهدف خاصية الفئة التي لديها مُحدد ومُستخرج معرفة، إلى استدعاء هذه الدالة.
type: docs
weight: 2874
url: /ar/system/setter_post_decrement_wrap/
---
## System::setter_post_decrement_wrap(T(*)(), void(*)(T)) دالة

المترجم يترجم تعبيرات ما بعد الإنقاص الخاصة بـ C# التي تستهدف خاصية الفئة التي لديها مُحدد ومُستخرج معرفة، إلى استدعاء هذه الدالة.

```cpp
template<typename T> T System::setter_post_decrement_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع الخاصية |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pGetter | T(*)() | مؤشر دالة يشير إلى الدالة الحرة لمُستخرج الخاصية |
| pSetter | void(*)(T) | مؤشر دالة يشير إلى الدالة الحرة لمُحدد الخاصية |

### قيمة الإرجاع

قيمة الخاصية قبل الزيادة

## System::setter_post_decrement_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) دالة

المترجم يترجم تعبيرات ما بعد الإنقاص الخاصة بـ C# التي تستهدف خاصية الكائن التي لديها مُحدد ومُستخرج معرفة، إلى استدعاء هذه الدالة (إصدار مختلف للـ getter غير الثابت).

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_decrement_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع الخاصية. |
| Host | - فئة الكائن المراد تعديلها |
| HostGet | - Host نفسه، أو نوعه الأساسي، حيث يُعرف مُستخرج الخاصية |
| HostSet | - Host نفسه، أو نوعه الأساسي، حيث يُعرف مُحدد الخاصية |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| host | Host *const | الكائن لاستدعاء المُستخرج والمُحدد له. |
| pGetter | T(HostGet::*)() | مؤشر دالة يشير إلى دالة مُستخرج الخاصية |
| pSetter | void(HostSet::*)(T) | مؤشر دالة يشير إلى دالة مُحدد الخاصية |

### قيمة الإرجاع

قيمة الخاصية قبل الزيادة

## System::setter_post_decrement_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) دالة

المترجم يترجم تعبيرات ما بعد الإنقاص الخاصة بـ C# التي تستهدف خاصية الكائن التي لديها مُحدد ومُستخرج معرفة، إلى استدعاء هذه الدالة (إصدار مختلف للـ getter الثابت).

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_decrement_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع الخاصية. |
| Host | - فئة الكائن المراد تعديلها |
| HostConstGet | - Host نفسه، أو نوعه الأساسي، حيث يُعرف مُستخرج الخاصية الثابت |
| HostSet | - Host نفسه، أو نوعه الأساسي، حيث يُعرف مُحدد الخاصية |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| host | Host *const | الكائن لاستدعاء المُستخرج والمُحدد له. |
| pGetter | T(HostConstGet::*)() const | مؤشر دالة يشير إلى دالة مُستخرج الخاصية |
| pSetter | void(HostSet::*)(T) | مؤشر دالة يشير إلى دالة مُحدد الخاصية |

### قيمة الإرجاع

قيمة الخاصية قبل الزيادة

## انظر أيضًا

* المجال [System](../)
* المكتبة [Aspose.Slides](../../)