---
title: Equals< float, float >()
second_title: Aspose.Slides C++ API 参考
description: "针对单精度浮点值的特化。虽然 IEC 60559:1989 将两个浮点 NaN 定义为始终不相等，但 System.Object.Equals 的约定要求重写必须满足等价运算符的要求。因此，在比较两个 NaN 时，System.Double.Equals 和 System.Single.Equals 返回 True，而相等运算符在此情况下返回 False，符合标准的要求。"
type: docs
weight: 2666
url: /zh/system/equals_less_float,_float__greater/
---
## System::Equals< float, float >(const float\&, const float\&) 函数

针对单精度浮点值的特化。虽然 IEC 60559:1989 将两个浮点 NaN 定义为始终不相等，但 [System.Object.Equals](../object/equals/) 的约定要求重写必须满足等价运算符的要求。因此，System.Double.Equals 和 System.Single.Equals 在比较两个 NaN 时返回 True，而相等运算符在这种情况下返回 False，符合标准的要求。

```cpp
bool System::Equals<float, float>(const float &a, const float &b)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | const **float**\& | 第一个比较数 |
| b | const **float**\& | 第二个比较数 |

### 返回值

如果两个值都是 NaN 或相等则返回 True，否则返回 false

## 另请参阅

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)