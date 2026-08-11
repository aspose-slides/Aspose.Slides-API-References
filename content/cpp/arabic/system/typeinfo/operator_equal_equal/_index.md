---
title: operator==()
second_title: مرجع API Aspose.Slides للـ C++
description: يحدد ما إذا كان الكائن الحالي وكائنات TypeInfo المحددة متساوية.
type: docs
weight: 443
url: /ar/system/typeinfo/operator_equal_equal/
---
## TypeInfo::operator==(const TypeInfo\&) const method


يحدد ما إذا كان الكائن الحالي والكائنات المحددة [TypeInfo](../) متساوية.

```cpp
bool System::TypeInfo::operator==(const TypeInfo &info) const
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| info | const [TypeInfo](../)\& | الكائن [TypeInfo](../) للمقارنة معه |

### قيمة الإرجاع

صحيح إذا كانت تجزئات الكائنات متساوية، وإلا - خطأ

## TypeInfo::operator==(std::nullptr_t) const method


يحدد ما إذا كان الكائن الحالي [TypeInfo](../) كائنًا فارغًا، أي أنه لا يمثل أي نوع.

```cpp
bool System::TypeInfo::operator==(std::nullptr_t) const
```


### قيمة الإرجاع

صحيح إذا كان الكائن الحالي [TypeInfo](../) كائنًا فارغًا، وإلا - خطأ

## انظر أيضًا

* الفئة [TypeInfo](../)
* مساحة الاسم [System](../../)
* المكتبة [Aspose.Slides](../../../)