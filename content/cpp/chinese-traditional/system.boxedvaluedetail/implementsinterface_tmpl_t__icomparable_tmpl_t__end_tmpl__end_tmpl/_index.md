---
title: ImplementsInterface< T, IComparable< T > >
second_title: Aspose.Slides for C++ API 參考文件
description: 檢查已封裝的物件是否應自行實作 IComparable 介面的模板謂詞。
type: docs
weight: 53
url: /zh-hant/system.boxedvaluedetail/implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/
---
## ImplementsInterface< T, IComparable< T > > struct

模板謂詞，用於檢查已封裝的物件是否應自行實作 [IComparable](../../system/icomparable/) 介面。

```cpp
template<typename T>class ImplementsInterface< T, IComparable< T > > : public std::integral_constant<bool, std::is_arithmetic<T>::value||std::is_enum<T>::value>
```

## 另見

* 命名空間 [System::BoxedValueDetail](../)
* 函式庫 [Aspose.Slides](../../)