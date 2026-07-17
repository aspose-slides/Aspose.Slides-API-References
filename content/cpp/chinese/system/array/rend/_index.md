---
title: rend()
second_title: Aspose.Slides for C++ API 参考
description: 返回一个指向反向容器中最后一个元素之后的元素的反向迭代器。它对应于非反向容器中第一个元素之前的元素。该元素充当占位符，尝试访问它会导致未定义行为。
type: docs
weight: 495
url: /zh/system/array/rend/
---
## Array::rend() 方法


返回一个指向反向容器中最后一个元素之后的元素的反向迭代器。它对应于非反向容器中第一个元素之前的元素。该元素充当占位符，尝试访问它会导致未定义行为。

```cpp
reverse_iterator System::Array<T>::rend() noexcept
```


### 返回值

指向容器中第一个元素之前的理论元素的迭代器。

## Array::rend() const 方法


返回一个指向反向容器中最后一个元素之后的元素的反向迭代器。它对应于非反向容器中第一个元素之前的元素。该元素充当占位符，尝试访问它会导致未定义行为。

```cpp
const_reverse_iterator System::Array<T>::rend() const noexcept
```


### 返回值

指向 const 限定容器中第一个元素之前的理论元素的迭代器。

## 另见

* Typedef [reverse_iterator](../reverse_iterator/)
* Typedef [const_reverse_iterator](../const_reverse_iterator/)
* 类 [Array](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)