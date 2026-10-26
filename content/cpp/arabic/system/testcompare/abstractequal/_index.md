---
title: AbstractEqual()
second_title: Aspose.Slides للـ C++ مرجع API
description: يقارن مجموعتين من نوع غير معروف.
type: docs
weight: 14
url: /ar/system/testcompare/abstractequal/
---
## TestCompare::AbstractEqual(SCG::ICollection\<T\> *const, SCG::ICollection\<T\> *const) طريقة

يقارن مجموعتين من نوع غير معروف.

```cpp
template<typename T> static bool System::TestCompare::AbstractEqual(SCG::ICollection<T> *const collA, SCG::ICollection<T> *const collB)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع عنصر المجموعة. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| collA | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | مجموعة الجانب الأيسر. |
| collB | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | مجموعة الجانب الأيمن. |

### قيمة الإرجاع

صحيح إذا كانت المجموعات متطابقة (مثلاً كلاهما فارغ)، أو إذا كان الأحجام متطابقة والعناصر متطابقة، وإلا خطأ.

## انظر أيضًا

* فئة [ICollection](../../../system.collections.generic/icollection/)
* بنية [TestCompare](../)
* مساحة الاسم [System](../../)
* مكتبة [Aspose.Slides](../../../)