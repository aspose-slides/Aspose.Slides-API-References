---
title: operator[]()
second_title: Aspose.Slides for C++ API 参考
description: 用于键类型转换的访问运算符。
type: docs
weight: 14
url: /zh/system.collections.generic/dictionaryptr/operator[]/
---
## DictionaryPtr::operator[](const X\&) const 方法


访问运算符，用于键类型转换。

```cpp
template<class X> V & System::Collections::Generic::DictionaryPtr<T, V>::operator[](const X &key) const
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| X | 源键类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| key | const X\& | [Dictionary](../../dictionary/) 键。 |

### 返回值

对传入键对应的值的引用，若不存在则创建新的。

## DictionaryPtr::operator[](const T\&) const 方法


访问运算符。

```cpp
V & System::Collections::Generic::DictionaryPtr<T, V>::operator[](const T &key) const
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| key | const T\& | [Dictionary](../../dictionary/) 键。 |

### 返回值

对传入键对应的值的引用，若不存在则创建新的。

## 另见

* 类 [DictionaryPtr](../)
* 命名空间 [System::Collections::Generic](../../)
* 库 [Aspose.Slides](../../../)