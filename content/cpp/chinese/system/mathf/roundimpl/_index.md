---
title: RoundImpl()
second_title: Aspose.Slides for C++ API 参考
description: 将指定的值四舍五入到具有指定小数位数的最近值。如果指定的值与两个最近的数字等距，则参数指定函数的行为。
type: docs
weight: 287
url: /zh/system/mathf/roundimpl/
---
## MathF::RoundImpl(float, int, MidpointRounding) 方法

将指定的 **value** 四舍五入到具有指定小数位数的最近值。 如果指定的 **value** 与两个最近的数字等距，则由参数指定函数的行为。

```cpp
static float System::MathF::RoundImpl(float value, int digits, MidpointRounding mode)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **float** | 要四舍五入的 **value** |
| digits | int | 四舍五入后 **value** 的小数位数 |
| mode | [MidpointRounding](../../midpointrounding/) | 指定在 **value** 与两个最近的数字等距时如何执行四舍五入。 |

### 返回值

最接近 **value** 且具有指定数字位数的数值

## 另请参阅

* Enum [MidpointRounding](../../midpointrounding/)
* Struct [MathF](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)