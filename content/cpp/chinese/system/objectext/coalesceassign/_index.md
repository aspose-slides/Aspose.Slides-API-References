---
title: CoalesceAssign()
second_title: Aspose.Slides for C++ API 参考
description: 实现 '??=' 运算符的翻译.
type: docs
weight: 183
url: /zh/system/objectext/coalesceassign/
---
## ObjectExt::CoalesceAssign(T0\&, T1) method

实现 `??=` 运算符的翻译。

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::CoalesceAssign(T0 &value, T1 func) -> T0 &
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T0 | 左侧值的类型。 |
| T1 | 封装 RHS 表达式的 lambda 类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | T0\& | 左侧值。 |
| func | T1 | RHS 表达式。 |

### 返回值

如果左侧值不为 null，则返回左侧值；否则计算 RHS 表达式并返回结果。

## 另请参见

* 类 [ObjectExt](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)