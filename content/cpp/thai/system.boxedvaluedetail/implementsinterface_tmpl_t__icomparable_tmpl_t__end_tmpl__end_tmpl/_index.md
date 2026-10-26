---
title: ImplementsInterface< T, IComparable< T > >
second_title: Aspose.Slides สำหรับ C++ API Reference
description: พรีดิเคตแม่แบบที่ตรวจสอบว่าวัตถุที่บรรจุควรทำการใช้งานอินเทอร์เฟซ IComparable ด้วยตนเอง.
type: docs
weight: 53
url: /th/system.boxedvaluedetail/implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/
---
## ImplementsInterface< T, IComparable< T > > struct


Template predicate that checks if boxed object should implement [IComparable](../../system/icomparable/) อินเทอร์เฟซ by itself.

```cpp
template<typename T>class ImplementsInterface< T, IComparable< T > > : public std::integral_constant<bool, std::is_arithmetic<T>::value||std::is_enum<T>::value>
```

## ดูเพิ่มเติม

* เนมสเปซ [System::BoxedValueDetail](../)
* ไลบรารี [Aspose.Slides](../../)