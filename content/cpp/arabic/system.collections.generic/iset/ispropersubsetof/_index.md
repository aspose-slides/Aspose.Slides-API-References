---
title: IsProperSubsetOf()
second_title: Aspose.Slides لمرجع API للغة C++
description: يتحقق مما إذا كانت المجموعة الحالية مجموعة فرعية صارمة للمجمع الآخر.
type: docs
weight: 40
url: /ar/system.collections.generic/iset/ispropersubsetof/
---
## ISet::IsProperSubsetOf(IEnumerablePtr) طريقة

يتحقق مما إذا كانت المجموعة الحالية مجموعة فرعية صارمة للمجمع **other**.

```cpp
virtual bool System::Collections::Generic::ISet<T>::IsProperSubsetOf(IEnumerablePtr other)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| other | [IEnumerablePtr](../ienumerableptr/) | المجموعة العليا للتحقق ضدها. |

### قيمة الإرجاع

صحيح إذا كانت جميع العناصر في المجموعة الحالية موجودة في **other** وكان **other** يحتوي على عناصر أكثر من المجموعة الحالية، وإلا خاطئ.

## انظر أيضاً

* Typedef [IEnumerablePtr](../ienumerableptr/)
* فئة [ISet](../)
* نطاق [System::Collections::Generic](../../)
* مكتبة [Aspose.Slides](../../../)