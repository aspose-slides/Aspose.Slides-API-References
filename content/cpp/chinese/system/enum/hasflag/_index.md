---
title: HasFlag()
second_title: Aspose.Slides C++ API 参考
description: 确定在指定枚举值的位数组表示中是否设置了指定的位。
type: docs
weight: 14
url: /zh/system/enum/hasflag/
---
## Enum::HasFlag(E, E) 方法

确定在指定枚举值的位数组表示中是否设置了指定的位。

```cpp
static bool System::Enum<E, Guard>::HasFlag(E value, E mask)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | E | 要测试的枚举值 |
| mask | E | 检查值位的掩码 |

### 返回值

如果在 **mask** 中设置的位也在 **value** 中设置，则为 True，否则为 false

## 另见

* 结构 [Enum](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)