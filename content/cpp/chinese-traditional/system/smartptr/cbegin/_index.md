---
title: cbegin()
second_title: Aspose.Slides for C++ API 參考文件
description: 存取器，用於底層集合的 cbegin() 方法。僅在 SmartPtr_ 為具備 cbegin() 方法的特化類型時才能編譯。
type: docs
weight: 404
url: /zh-hant/system/smartptr/cbegin/
---
## SmartPtr::cbegin() const 方法


存取器，用於 [cbegin()](./) 方法的底層集合。僅在 SmartPtr_ 為具備 [cbegin()](./) 方法的特化類型時才能編譯。

```cpp
template<typename Q> auto System::SmartPtr<T>::cbegin() const -> decltype(std::declval<const Q>().cbegin())
```


### 返回值

指向集合起始位置的迭代器

## 另請參閱

* 類別 [SmartPtr](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)