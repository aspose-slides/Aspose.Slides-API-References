---
title: IsProperSupersetOf()
second_title: مرجع API Aspose.Slides للغة C++
description: يتحقق مما إذا كانت المجموعة الحالية مجموعة فوقية صارمة بالنسبة لحاوية أخرى.
type: docs
weight: 53
url: /ar/system.collections.generic/iset/ispropersupersetof/
---
## ISet::IsProperSupersetOf(IEnumerablePtr) طريقة

يتحقق مما إذا كانت المجموعة الحالية مجموعة فوقية صارمة بالنسبة لحاوية أخرى.

```cpp
virtual bool System::Collections::Generic::ISet<T>::IsProperSupersetOf(IEnumerablePtr other)=0
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| other | [IEnumerablePtr](../ienumerableptr/) | المجموعة الفرعية للتحقق منها. |

### قيمة الإرجاع

صحيح إذا كانت جميع العناصر في **other** موجودة في المجموعة وكان للمجموعة عناصر أكثر من **other**، وإلا خطأ.

## انظر أيضًا

* تعريف نوع [IEnumerablePtr](../ienumerableptr/)
* فئة [ISet](../)
* مساحة الأسماء [System::Collections::Generic](../../)
* مكتبة [Aspose.Slides](../../../)