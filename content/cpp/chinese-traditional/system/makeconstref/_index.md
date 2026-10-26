---
title: MakeConstRef
second_title: Aspose.Slides for C++ API 參考
description: 特徵用於在類型為 String 或 SmartPtr<> 時將通用類型製作為 \"const reference\"。
type: docs
weight: 1769
url: /zh-hant/system/makeconstref/
---
## MakeConstRef 結構

特徵用於在 [String](../string/) 或 SmartPtr<> 類型時，將通用類型製作為 \"常量引用\"。

```cpp
template<typename T>class MakeConstRef : public std::conditional<System::detail::is_a<T, System::SmartPtr>::value||std::is_same<System::String, T>::value, const T &, T>
```

## 參見

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)