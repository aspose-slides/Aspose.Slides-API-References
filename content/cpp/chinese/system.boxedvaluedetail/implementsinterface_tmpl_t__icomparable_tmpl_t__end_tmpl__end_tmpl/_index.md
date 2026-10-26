---
title: ImplementsInterface< T, IComparable< T > >
second_title: Aspose.Slides for C++ API 参考
description: 模板谓词，用于检查装箱对象是否应自行实现 IComparable 接口。
type: docs
weight: 53
url: /zh/system.boxedvaluedetail/implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/
---
## ImplementsInterface< T, IComparable< T > > struct


模板谓词用于检查装箱对象是否应该自行实现 [IComparable](../../system/icomparable/) 接口。

```cpp
template<typename T>class ImplementsInterface< T, IComparable< T > > : public std::integral_constant<bool, std::is_arithmetic<T>::value||std::is_enum<T>::value>
```

## 另请参见

* 命名空间 [System::BoxedValueDetail](../)
* 库 [Aspose.Slides](../../)