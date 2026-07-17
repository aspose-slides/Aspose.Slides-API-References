---
title: CopyTo()
second_title: Aspose.Slides for C++ API 参考
description: 将列表元素复制到已有的数组元素中。
type: docs
weight: 209
url: /zh/system.collections.generic/list/copyto/
---
## List::CopyTo(System::ArrayPtr\<T\>, int) 方法


将列表元素复制到已有的数组元素中。

```cpp
void System::Collections::Generic::List<T>::CopyTo(System::ArrayPtr<T> array, int arrayIndex) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<T\> | 目标数组。 |
| arrayIndex | int | 目标数组的起始索引。 |

## List::CopyTo(const System::ArrayPtr\<T\>\&) 方法


将所有元素复制到已有的数组元素中。

```cpp
void System::Collections::Generic::List<T>::CopyTo(const System::ArrayPtr<T> &array)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/) 用于复制元素的目标。 |

## List::CopyTo(int, const System::ArrayPtr\<T\>\&, int, int) 方法


从指定索引开始复制元素到已有的数组元素中。

```cpp
void System::Collections::Generic::List<T>::CopyTo(int index, const System::ArrayPtr<T> &array, int arrayIndex, int count)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 从当前对象表示的列表中开始复制的元素的0基索引。 |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/) 用于复制元素的目标。 |
| arrayIndex | int | 目标数组的起始位置。 |
| count | int | 要复制的元素数量。 |

## 另见

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)