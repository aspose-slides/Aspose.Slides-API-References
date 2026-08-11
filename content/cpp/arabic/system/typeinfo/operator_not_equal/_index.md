---
title: operator!=()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد ما إذا كان الكائن الحالي والكائنات المحددة من TypeInfo غير متساوية.
type: docs
weight: 456
url: /ar/system/typeinfo/operator_not_equal/
---
## TypeInfo::operator!=(const TypeInfo\&) const طريقة


Determines if the current and the specified [TypeInfo](../) objects are not equal.

```cpp
bool System::TypeInfo::operator!=(const TypeInfo &info) const
```


### المعطيات

| معامل | نوع | الوصف |
| --- | --- | --- |
| info | const [TypeInfo](../)\& | The [TypeInfo](../) object to compare with |

### قيمة الإرجاع

True إذا لم تكن تجزئات الكائنات متساوية، وإلا - false

## TypeInfo::operator!=(std::nullptr_t) const طريقة


Determines if the current [TypeInfo](../) object is not a null-object, i.e. it represents some type.

```cpp
bool System::TypeInfo::operator!=(std::nullptr_t) const
```


### قيمة الإرجاع

True إذا لم يكن كائن [TypeInfo](../) الحالي كائنًا فارغًا، وإلا - false

## انظر أيضًا

* الفئة [TypeInfo](../)
* النطاق [System](../../)
* المكتبة [Aspose.Slides](../../../)