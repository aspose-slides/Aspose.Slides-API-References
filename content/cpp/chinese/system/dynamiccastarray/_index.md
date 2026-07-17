---
title: DynamicCastArray()
second_title: Aspose.Slides for C++ API 参考
description: 对指定数组的元素执行转换为不同类型的操作。
type: docs
weight: 2952
url: /zh/system/dynamiccastarray/
---
## System::DynamicCastArray(const SharedPtr\<Array\<From\>\>\&) 函数


对指定数组的元素执行转换为不同类型的操作。

```cpp
template<class To,class From> SharedPtr<Array<To>> System::DynamicCastArray(const SharedPtr<Array<From>> &from)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| To | 将指定数组的元素转换为的目标类型 |
| From | 要进行转换的数组元素的源类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| from | const [SharedPtr](../sharedptr/)\<[Array](../array/)\<From\>\>\& | 包含要转换的元素的数组的共享指针 |

### 返回值

指向新数组的指针，数组包含与 **from** 中的元素等价的 **To** 类型元素

已弃用
:   为了向后兼容而添加。请改用 ExplicitCast。

## 另请参阅

* 类型定义 [SharedPtr](../sharedptr/)
* 类 [Array](../array/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)