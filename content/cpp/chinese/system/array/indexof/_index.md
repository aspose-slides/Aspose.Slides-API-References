---
title: IndexOf()
second_title: Aspose.Slides C++ API 参考
description: 确定数组中指定项第一次出现的索引。
type: docs
weight: 131
url: /zh/system/array/indexof/
---
## Array::IndexOf(const T\&) const 方法

确定数组中指定项第一次出现的索引。

```cpp
virtual int System::Array<T>::IndexOf(const T &item) const override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | const T\& | 要确定其索引的项 |

### 返回值

如果找到指定的项，则返回第一次出现的索引；否则返回 -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) 方法

确定数组中指定项第一次出现的索引。

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| ArrayType | 目标数组中元素的类型 |
| ValueType | 要在数组中搜索的项的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) 用于搜索指定的项 |
| value | const [ValueType](../valuetype/)\& | 要确定其索引的项 |

### 返回值

如果找到指定的项，则返回第一次出现的索引；否则返回 -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) 方法

确定从指定索引开始在数组中查找指定项时，其第一次出现的索引。

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| ArrayType | 目标数组中元素的类型 |
| ValueType | 要在数组中搜索的项的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) 用于搜索指定的项 |
| value | const [ValueType](../valuetype/)\& | 要确定其索引的项 |
| startIndex | int | 开始搜索的索引 |

### 返回值

如果找到指定的项，则返回第一次出现的索引；否则返回 -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) 方法

确定在由起始索引和范围元素数量指定的数组子范围内，指定项第一次出现的索引。

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| ArrayType | 目标数组中元素的类型 |
| ValueType | 要在数组中搜索的项的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) 用于搜索指定的项 |
| value | const [ValueType](../valuetype/)\& | 要确定其索引的项 |
| startIndex | int | 开始搜索的索引 |
| count | int | 要搜索的范围内元素的数量 |

### 返回值

如果找到指定的项，则返回第一次出现的索引；否则返回 -1

## 参见

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* 类 [Array](../)
* 命名空间 [System](../../)
* Library [Aspose.Slides](../../../)