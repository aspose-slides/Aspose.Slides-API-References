---
title: Round()
second_title: Aspose.Slides C++ API 参考
description: 将指定的值四舍五入到最近的整数。若指定的值与两个最近的数字等距，参数会指定函数的行为。
type: docs
weight: 404
url: /zh/system/decimal/round/
---
## Decimal::Round(const Decimal\&, MidpointRounding) 方法

将指定的值四舍五入到最近的整数。若指定的值与两个最近的数字等距，参数会指定函数的行为。

```cpp
static Decimal System::Decimal::Round(const Decimal &d, MidpointRounding mode=MidpointRounding::ToEven)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| d | const [Decimal](../)\& | 要四舍五入的值 |
| mode | [MidpointRounding](../../midpointrounding/) | 指定当 **值** 与两个最近的数字等距时如何执行四舍五入。 |

### 返回值

**d** 四舍五入到最近的整数值

## Decimal::Round(const Decimal\&, int, MidpointRounding) 方法

将指定的值四舍五入到具有指定小数位数的最近值。若指定的值与两个最近的数字等距，参数会指定函数的行为。

```cpp
static Decimal System::Decimal::Round(const Decimal &d, int digits, MidpointRounding mode=MidpointRounding::ToEven)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| d | const [Decimal](../)\& | 要四舍五入的值 |
| digits | int | 四舍五入后值的小数位数 |
| mode | [MidpointRounding](../../midpointrounding/) | 指定当 **值** 与两个最近的数字等距时如何执行四舍五入。 |

### 返回值

具有指定数字位数且最接近 **值** 的数

## 另请参阅

* 枚举 [MidpointRounding](../../midpointrounding/)
* 类 [Decimal](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)