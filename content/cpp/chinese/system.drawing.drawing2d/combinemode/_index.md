---
title: CombineMode
second_title: Aspose.Slides C++ API 参考
description: 指定剪裁区域的组合方式。
type: docs
weight: 170
url: /zh/system.drawing.drawing2d/combinemode/
---
## CombineMode 枚举

指定如何组合剪裁区域。

```cpp
enum class CombineMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Replace | 0 | 一个剪裁区域被另一个剪裁区域替换。 |
| Intersect | 1 | 通过取它们的交集来合并这两个剪裁区域。 |
| Union | 2 | 通过取两者的并集来合并这两个剪裁区域。 |
| Xor | 3 | 仅取任一区域所围成的面积（但不包括两者重叠的部分），来合并这两个剪裁区域。 |
| Exclude | 4 | 通过取第一个剪裁区域中不与第二个相交的面积来合并这两个剪裁区域。 |
| Complement | 5 | 通过取第二个剪裁区域中不与第一个相交的面积来合并这两个剪裁区域。 |

## 另请参见

* 命名空间 [System::Drawing::Drawing2D](../)
* 库 [Aspose.Slides](../../)