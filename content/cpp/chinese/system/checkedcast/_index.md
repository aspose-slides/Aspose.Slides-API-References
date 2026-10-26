---
title: CheckedCast()
second_title: Aspose.Slides for C++ API 参考
description: 确定指定的值是否在类型 TTo 的值范围内，如果是，则将其转换为类型 TTo。
type: docs
weight: 2757
url: /zh/system/checkedcast/
---
## System::CheckedCast(TFrom) 函数

确定指定的值是否在类型 **TTo** 的值范围内，如果是，则将其转换为类型 **TTo**。

```cpp
template<typename TTo,typename TFrom> TTo System::CheckedCast(TFrom value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| TTo | 要将指定值转换为的类型 |
| TFrom | 指定值的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | TFrom | 要转换的值 |

### 返回值

等价于 **value** 的 **TTo** 类型的值

## 另请参见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)