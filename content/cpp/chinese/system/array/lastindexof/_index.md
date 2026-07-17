---
title: LastIndexOf()
second_title: Aspose.Slides for C++ API 参考
description: 确定在由起始索引和范围内元素数量指定的数组项范围内，指定项最后一次出现的索引。
type: docs
weight: 703
url: /zh/system/array/lastindexof/
---
## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) 方法

确定在由起始索引和范围内元素数量指定的数组项范围内，指定项最后一次出现的索引。

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| ArrayType | 目标数组中元素的类型 |
| ValueType | 要在数组中搜索的项的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) 用于搜索指定项 |
| value | const [ValueType](../valuetype/)\& | 要确定索引的项 |
| startIndex | int | 开始搜索的索引 |
| count | int | 要搜索的范围内元素的数量 |

### 返回值

如果找到指定项，则返回该项最后一次出现的索引；否则返回 -1

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) 方法

确定从指定索引开始的数组中，指定项最后一次出现的索引。

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value, int startIndex)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| ArrayType | 目标数组中元素的类型 |
| ValueType | 要在数组中搜索的项的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) 用于搜索指定项 |
| value | const [ValueType](../valuetype/)\& | 要确定索引的项 |
| startIndex | int | 开始搜索的索引 |

### 返回值

如果找到指定项，则返回该项最后一次出现的索引；否则返回 -1

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) 方法

确定数组中指定项最后一次出现的索引。

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| ArrayType | 目标数组中元素的类型 |
| ValueType | 要在数组中搜索的项的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) 用于搜索指定项 |
| value | const [ValueType](../valuetype/)\& | 要确定索引的项 |

### 返回值

如果找到指定项，则返回该项最后一次出现的索引；否则返回 -1

## 另请参见

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)