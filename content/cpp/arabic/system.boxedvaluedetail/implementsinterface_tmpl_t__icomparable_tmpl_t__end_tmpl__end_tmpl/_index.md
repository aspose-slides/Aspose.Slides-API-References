---
title: ImplementsInterface< T, IComparable< T > >
second_title: مرجع API لـ Aspose.Slides للـ C++
description: بادئة القالب التي تتحقق مما إذا كان الكائن المعبأ يجب أن يطبق واجهة IComparable بنفسه.
type: docs
weight: 53
url: /ar/system.boxedvaluedetail/implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/
---
## ImplementsInterface< T, IComparable< T > > struct


بادئة القالب التي تتحقق مما إذا كان كائن المعبأ يجب أن يطبق واجهة [IComparable](../../system/icomparable/) بنفسه.

```cpp
template<typename T>class ImplementsInterface< T, IComparable< T > > : public std::integral_constant<bool, std::is_arithmetic<T>::value||std::is_enum<T>::value>
```

## انظر أيضًا

* نطاق [System::BoxedValueDetail](../)
* مكتبة [Aspose.Slides](../../)