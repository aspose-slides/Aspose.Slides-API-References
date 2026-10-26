---
title: cend()
second_title: Aspose.Slides for C++ API 參考
description: 底層集合之 cend() 方法的存取器。僅在 SmartPtr_ 為具備 cend() 方法的專門化類型時才能編譯。
type: docs
weight: 417
url: /zh-hant/system/smartptr/cend/
---
## SmartPtr::cend() const 方法

Accessor for [cend()](./) method of an underling collection. Only compiles if SmartPtr_ is specialization type with [cend()](./) method.

```cpp
template<typename Q> auto System::SmartPtr<T>::cend() const -> decltype(std::declval<const Q>().cend())
```

### 返回值

指向集合末端的迭代器

## 另請參閱

* 類別 [SmartPtr](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)