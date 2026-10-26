---
title: setter_wrap()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: تراكب لدوال الضبط الثابتة مع تحويل النوع.
type: docs
weight: 2822
url: /ar/system/setter_wrap/
---
## System::setter_wrap(void(*)(T2), T) دالة

تراكب لدوال الضبط الثابتة مع تحويل النوع.

```cpp
template<typename T,typename T2> T System::setter_wrap(void(*pSetter)(T2), T value)
```

### معلمات القالب

| المعلمة | الوصف |
| --- | --- |
| T | نوع القيمة. |
| T2 | النوع المتوقع من دالة الضبط. |

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| pSetter | void(*)(T2) | مرجع دالة الضبط الثابتة. |
| value | T | القيمة التي سيتم ضبطها. |

### قيمة الإرجاع

تعيين القيمة.

## System::setter_wrap(Host *const, void(HostSet::*)(T2), T) دالة

تراكب لدوال الضبط الخاصة بالنسخة مع تحويل النوع.

```cpp
template<typename T,typename T2,typename Host,typename HostSet> std::enable_if<std::is_base_of<HostSet, Host>::value, T>::type System::setter_wrap(Host *const host, void(HostSet::*pSetter)(T2), T value)
```

### معلمات القالب

| المعلمة | الوصف |
| --- | --- |
| T | نوع القيمة. |
| T2 | النوع المتوقع من دالة الضبط. |
| Host | نوع النسخة. |
| HostSet | - المضيف نفسه، أو نوعه الأساسي، حيث تم تعريف مُضبط الخاصية. |

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| host | Host *const | [Object](../object/) لاستدعاء دالة الضبط لـ. |
| pSetter | void(HostSet::*)(T2) | مرجع دالة الضبط. |
| value | T | القيمة التي سيتم ضبطها. |

### قيمة الإرجاع

تعيين القيمة.

## انظر أيضًا

* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)