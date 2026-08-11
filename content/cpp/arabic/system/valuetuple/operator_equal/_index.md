---
title: operator=()
second_title: Aspose.Slides لـ C++ مرجع API
description: 
type: docs
weight: 92
url: /ar/system/valuetuple/operator_equal/
---
## ValueTuple::operator=(const ValueTuple\<OtherArgs...\>\&) طريقة

```cpp
template<typename ...> ValueTuple & System::ValueTuple<Args>::operator=(const ValueTuple<OtherArgs...> &otherTuple)
```

## ValueTuple::operator=(const SharedPtr\<T\>\&) طريقة

يفكّك الكائن إلى هذا الزوج القيمي.

```cpp
template<typename T> ValueTuple & System::ValueTuple<Args>::operator=(const SharedPtr<T> &deconstructiblePtr)
```

### المعطيات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| deconstructiblePtr | const [SharedPtr](../../sharedptr/)\<T\>\& | كائن لتفكيكه |

## انظر أيضًا

* تعريف نوع [SharedPtr](../../sharedptr/)
* فئة [ValueTuple](../)
* مساحة الاسم [System](../../)
* مكتبة [Aspose.Slides](../../../)