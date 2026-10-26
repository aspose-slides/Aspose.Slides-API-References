---
title: CopyPixelOperation
second_title: Aspose.Slides for C++ API 参考
description: 指定在像素复制操作中，源颜色如何与目标颜色组合以产生最终颜色。
type: docs
weight: 391
url: /zh/system.drawing/copypixeloperation/
---
## CopyPixelOperation 枚举

指定在像素复制操作中，源颜色如何与目标颜色组合以产生最终颜色。

```cpp
enum class CopyPixelOperation
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| NoMirrorBitmap | n/a | 位图未被镜像。 |
| Blackness | 66 | 目标区域使用物理调色板中索引 0 的颜色填充。 |
| NotSourceErase | 1114278 | 对源颜色和目标颜色进行或运算，然后对结果颜色取反。 |
| NotSourceCopy | 3342344 | 对源区域取反后复制到目标区域。 |
| SourceErase | 4457256 | 将目标区域的取反颜色与源区域的颜色进行与运算。 |
| DestinationInvert | 5570569 | 对目标区域取反。 |
| PatInvert | 5898313 | 目标设备上下文中当前选定的画笔颜色与目标颜色进行异或运算。 |
| SourceInvert | 6684742 | 对源区域和目标区域的颜色进行异或运算。 |
| SourceAnd | 8913094 | 对源区域和目标区域的颜色进行与运算。 |
| MergePaint | 12255782 | 将取反的源区域颜色与目标区域颜色进行或运算。 |
| MergeCopy | 12583114 | 将源区域颜色与目标设备上下文中选定画笔的颜色进行与运算。 |
| SourceCopy | 13369376 | 将源区域直接复制到目标区域。 |
| SourcePaint | 15597702 | 对源区域和目标区域的颜色进行或运算。 |
| PatCopy | 15728673 | 将目标设备上下文中当前选定的画笔复制到目标位图。 |
| PatPaint | 16452105 | 将目标设备上下文中当前选定的画笔颜色与取反的源区域颜色进行或运算。该操作的结果再与目标区域颜色进行或运算。 |
| Whiteness | 16711778 | 目标区域使用物理调色板中索引 1 的颜色填充。 |
| CaptureBlt | 1073741824 | [Windows](../../system.windows/) 层叠在应用程序窗口之上的内容包含在生成的图像中。 |

## 参见

* 命名空间 [System::Drawing](../)
* 库 [Aspose.Slides](../../)