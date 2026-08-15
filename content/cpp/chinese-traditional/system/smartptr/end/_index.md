---
title: end()
second_title: Aspose.Slides for C++ API 參考文件
description: 對底層集合的 end() 方法的存取子。僅在 SmartPtr_ 為具備 end() 方法的特化類型時才會編譯。
type: docs
weight: 391
url: /zh-hant/system/smartptr/end/
---
## SmartPtr::end() 方法

Accessor for [end()](./) method of an underling collection. Only compiles if SmartPtr_ is specialization type with [end()](./) method.

```cpp
template<typename Q> auto System::SmartPtr<T>::end() -> decltype(std::declval<Q>().end())
```

### 返回值

iterator to the end of collection

## SmartPtr::end() const 方法

Accessor for [end()](./) method of an underling collection. Only compiles if SmartPtr_ is specialization type with [end()](./) method.

```cpp
template<typename Q> auto System::SmartPtr<T>::end() const -> decltype(std::declval<const Q>().end())
```

### 返回值

iterator to the end of collection

## 另請參閱

* 類別 [SmartPtr](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)