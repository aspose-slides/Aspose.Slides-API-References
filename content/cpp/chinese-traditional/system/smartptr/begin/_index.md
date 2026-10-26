---
title: begin()
second_title: Aspose.Slides for C++ API 參考文件
description: 底層集合的 begin() 方法的存取器。僅在 SmartPtr_ 為具備 begin() 方法的專門化類型時編譯。
type: docs
weight: 378
url: /zh-hant/system/smartptr/begin/
---
## SmartPtr::begin() 方法


存取底層集合的 [begin()](./) 方法。僅在 SmartPtr_ 為具備 [begin()](./) 方法的專門化類型時編譯。

```cpp
template<typename Q> auto System::SmartPtr<T>::begin() -> decltype(std::declval<Q>().begin())
```


### 返回值

指向集合起始位置的 iterator

## SmartPtr::begin() const 方法


存取底層集合的 [begin()](./) 方法。僅在 SmartPtr_ 為具備 [begin()](./) 方法的專門化類型時編譯。

```cpp
template<typename Q> auto System::SmartPtr<T>::begin() const -> decltype(std::declval<const Q>().begin())
```


### 返回值

指向集合起始位置的 iterator

## 另請參閱

* 類別 [SmartPtr](../)
* 命名空間 [System](../../)
* 程式庫 [Aspose.Slides](../../../)