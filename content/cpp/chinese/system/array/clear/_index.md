---
title: Clear()
second_title: Aspose.Slides for C++ API 参考
description: 不支持此操作，因为当前对象表示的数组是只读的。
type: docs
weight: 53
url: /zh/system/array/clear/
---
## Array::Clear() 方法

不支持此操作，因为当前对象表示的数组是只读的。

```cpp
virtual void System::Array<T>::Clear() override
```

## Array::Clear(const ArrayPtr\<Type\>\&, int, int) 方法

将指定数组中从 **startIndex** 索引开始的 **count** 个值替换为默认值。

```cpp
template<typename Type> static void System::Array<T>::Clear(const ArrayPtr<Type> &arr, int startIndex, int count)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Type | 目标数组中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | 目标数组 |
| startIndex | int | 开始替换项目的索引 |
| count | int | 要替换的项目数量 |

## 另见

* Typedef [ArrayPtr](../../arrayptr/)
* Method [Type](../../object/type/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)