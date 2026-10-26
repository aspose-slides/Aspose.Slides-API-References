---
title: rbegin()
second_title: Aspose.Slides for C++ API 參考
description: 傳回一個指向已反轉容器中第一個元素的反向迭代器。它對應於未反轉容器的最後一個元素。如果容器為空，傳回的迭代器等於 rend().
type: docs
weight: 469
url: /zh-hant/system/array/rbegin/
---
## Array::rbegin() 方法


傳回一個指向反向容器中第一個元素的反向迭代器。它對應於未反轉容器的最後一個元素。如果容器為空，傳回的迭代器等於 [rend()](../rend/).

```cpp
reverse_iterator System::Array<T>::rbegin() noexcept
```


### 返回值

指向容器最後一個元素的迭代器。

## Array::rbegin() const 方法


傳回一個指向反向容器中第一個元素的反向迭代器。它對應於未反轉容器的最後一個元素。如果容器為空，傳回的迭代器等於 [rend()](../rend/).

```cpp
const_reverse_iterator System::Array<T>::rbegin() const noexcept
```


### 返回值

指向 const 限定容器最後一個元素的迭代器。

## 參見

* Typedef [reverse_iterator](../reverse_iterator/)
* Typedef [const_reverse_iterator](../const_reverse_iterator/)
* 類別 [Array](../)
* 命名空間 [System](../../)
* Library [Aspose.Slides](../../../)