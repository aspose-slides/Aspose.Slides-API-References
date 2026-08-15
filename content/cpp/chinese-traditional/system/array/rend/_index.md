---
title: rend()
second_title: Aspose.Slides for C++ API 參考文件
description: 傳回一個反向迭代器，指向倒置容器中最後一個元素之後的元素。它對應於非倒置容器中第一個元素之前的元素。此元素充當佔位符，嘗試存取它會導致未定義的行為。
type: docs
weight: 495
url: /zh-hant/system/array/rend/
---
## Array::rend() 方法


返回一個反向迭代器，指向倒置容器中最後一個元素之後的元素。它對應於非倒置容器中第一個元素之前的元素。此元素充當佔位符，嘗試存取它會導致未定義的行為。

```cpp
reverse_iterator System::Array<T>::rend() noexcept
```


### 返回值

指向容器中第一個元素之前的理論元素的迭代器。

## Array::rend() const 方法


返回一個反向迭代器，指向倒置容器中最後一個元素之後的元素。它對應於非倒置容器中第一個元素之前的元素。此元素充當佔位符，嘗試存取它會導致未定義的行為。

```cpp
const_reverse_iterator System::Array<T>::rend() const noexcept
```


### 返回值

指向 const 限定容器中第一個元素之前的理論元素的迭代器。

## See Also

* Typedef [reverse_iterator](../reverse_iterator/)
* Typedef [const_reverse_iterator](../const_reverse_iterator/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)