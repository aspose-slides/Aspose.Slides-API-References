---
title: setter_increment_wrap()
second_title: Aspose.Slides لـ C++ مرجع API
description: يقوم المترجم بترجمة تعبيرات الزيادة في C# التي تستهدف خاصية الفئة التي لديها محدد ومسترجع معرفين، إلى استدعاء هذه الدالة.
type: docs
weight: 2835
url: /ar/system/setter_increment_wrap/
---
## System::setter_increment_wrap(T(*)(), void(*)(T)) الدالة

المترجم يترجم تعبيرات الزيادة في C# التي تستهدف خاصية الفئة التي لديها محدد ومسترجع معرفين، إلى استدعاء هذه الدالة.

```cpp
template<typename T> T System::setter_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع الخاصية |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pGetter | T(*)() | مؤشر دالة يشير إلى دالة مجانية للمسترجع الخاص بالخاصية |
| pSetter | void(*)(T) | مؤشر دالة يشير إلى دالة مجانية للمحدد الخاص بالخاصية |

### قيمة الإرجاع

القيمة المُزادَة للخاصية

## System::setter_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) الدالة

المترجم يترجم تعبيرات الزيادة في C# التي تستهدف خاصية الفئة التي لديها محدد ومسترجع معرفين، إلى استدعاء هذه الدالة.

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع الخاصية |
| Host | - الفئة التي يحتويها الكائن المراد تعديلها |
| HostGet | - Host نفسه، أو نوعه الأساسي حيث تم تعريف المسترجع الخاص بالخاصية |
| HostSet | - Host نفسه، أو نوعه الأساسي حيث تم تعريف المحدد الخاص بالخاصية |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| host | Host *const | مؤشر إلى كائن تُزاد خاصيته |
| pGetter | T(HostGet::*)() | مؤشر دالة يشير إلى طريقة المسترجع للخاصية |
| pSetter | void(HostSet::*)(T) | مؤشر دالة يشير إلى طريقة المحدد للخاصية |

### قيمة الإرجاع

القيمة المُزادَة للخاصية

## انظر أيضًا

* المساحة الاسمية [System](../)
* المكتبة [Aspose.Slides](../../)