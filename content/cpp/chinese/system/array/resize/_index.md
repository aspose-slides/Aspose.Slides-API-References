---
title: Resize()
second_title: Aspose.Slides for C++ API 参考
description: 将指定数组的大小更改为指定的值，或在指定大小时创建新数组。
type: docs
weight: 768
url: /zh/system/array/resize/
---
## Array::Resize(ArrayPtr\<Type\>\&, int) 方法

更改指定数组的大小为指定的值，或在指定大小时创建新数组。

```cpp
template<typename Type> static void System::Array<T>::Resize(ArrayPtr<Type> &arr, int new_size)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | [Array](../) 进行调整大小。如果 **arr** 为空指针，将创建新数组 |
| new_size | int | 数组的新大小，或者当 **arr** 为 null 时的新数组大小 |

## 另见

* 类型定义 [ArrayPtr](../../arrayptr/)
* 方法 [Type](../../object/type/)
* 类 [Array](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)