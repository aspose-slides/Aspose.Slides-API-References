---
title: ColorAdjustType
second_title: Aspose.Slides for C++ API 参考文档
description: 指定哪些对象使用颜色调整信息。
type: docs
weight: 183
url: /zh/system.drawing.imaging/coloradjusttype/
---
## ColorAdjustType enum

指定哪些对象使用颜色调整信息。

```cpp
enum class ColorAdjustType
```

### Values

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Default | 0 | 定义所有未拥有自身颜色调整信息的对象使用的颜色调整信息。 |
| Bitmap | 1 | 为 [Bitmap](../../system.drawing/bitmap/) 对象定义颜色调整信息。 |
| Brush | 2 | 为 [Brush](../../system.drawing/brush/) 对象定义颜色调整信息。 |
| Pen | 3 | 为 [Pen](../../system.drawing/pen/) 对象定义颜色调整信息。 |
| Text | 4 | 为文本定义颜色调整信息。 |
| Count | 5 | 指定已指定类型的数量。 |
| Any | 6 | 指定已指定类型的数量。 |

## 参见

* 命名空间 [System::Drawing::Imaging](../)
* 库 [Aspose.Slides](../../)