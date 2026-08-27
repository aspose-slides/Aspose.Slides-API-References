---
title: SlideImageFormat
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/slideimageformat/
---
## SlideImageFormat 类

 确定在将演示文稿导出为 HTML 时，幻灯片图像将保存的格式。
 
### SlideImageFormat {#SlideImageFormat}

| 名称 | 描述 |
| --- | --- |
| SlideImageFormat() |  |

 **返回:**
SlideImageFormat


---


### bitmap {#bitmap}

| 名称 | 描述 |
| --- | --- |
| bitmap (float, int) | 幻灯片应转换为光栅图像。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| scale | float | 用于缩放输出图像的因子。 |
| imageFormat | int | 生成图像的格式（例如 PNG、JPEG）。 |

 **返回:**
SlideImageFormat


---


### svg {#svg}

| 名称 | 描述 |
| --- | --- |
| svg ([SVGOptions](../svgoptions)) | 幻灯片应转换为 SVG 格式。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| options | [SVGOptions](../svgoptions) | SVG 导出的选项。 |

 **返回:**
SlideImageFormat


---