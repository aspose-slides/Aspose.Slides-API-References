---
title: Get()
second_title: Aspose.Slides for C++ API 参考
description: 获取给定元组的第 N 个元素的函数。针对基对象的重载。
type: docs
weight: 2367
url: /zh/system/get/
---
## System::Get(const SharedPtr\<Object\>\&) 函数

获取给定元组的第 N 个元素的函数。针对基对象的重载。

```cpp
template<std::size_t> auto System::Get(const SharedPtr<Object> &object)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| N | 元素索引。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | 要检查的 object。 |

### 返回值

返回值为第 N 个元组元素，已转换为 object。

## System::Get(const T\&) 函数

获取给定元组的第 N 个元素的函数。针对具有 Deconstruct 方法的对象的重载。

```cpp
template<std::size_t,typename T> auto System::Get(const T &object)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| N | 元素索引。 |
| T | 被检查对象的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| object | const T\& | 要检查的 object。 |

### 返回值

返回第 N 个元组元素的值。

## System::Get(const SharedPtr\<T\>\&) 函数

获取给定元组的第 N 个元素的函数。针对共享指针的重载。

```cpp
template<std::size_t,typename T> auto System::Get(const SharedPtr<T> &pointer)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| N | 元素索引。 |
| T | 被检查对象的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<T\>\& | 要检查的 object。 |

### 返回值

返回第 N 个元组元素的值。

## System::Get(const ValueTuple\<Args...\>\&) 函数

获取值元组的第 N 个元素。

```cpp
template<std::size_t,typename...> auto System::Get(const ValueTuple<Args...> &tuple)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| N | 元素索引。 |
| Args | 元组元素。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tuple | const [ValueTuple](../valuetuple/)\<Args...\>\& | 要获取元素的 tuple。 |

### 返回值

返回第 N 个元组元素的值。

## 另见

* 类型别名 [SharedPtr](../sharedptr/)
* 类 [Object](../object/)
* 类 [ValueTuple](../valuetuple/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)