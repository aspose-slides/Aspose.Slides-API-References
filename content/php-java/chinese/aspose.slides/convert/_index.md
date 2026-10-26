---
title: Convert
second_title: Aspose.Sildes for PHP 通过 Java API 参考
description: 
type: docs

url: /zh/aspose.slides/convert/
---
## Convert 类

表示用于转换 Presentation 的方法组。

### Convert {#Convert}

| 名称 | 描述 |
| --- | --- |
| Convert() |  |

 **返回：**
Convert


---


### autoByExtension {#autoByExtension}

| 名称 | 描述 |
| --- | --- |
| autoByExtension (String, String) | 使用传入的输出路径扩展名来确定所需的导出格式，从而转换 Presentation。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| presPath | String | 输入演示文稿的路径 |
| outPath | String | 输出路径 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
 | ArgumentOutOfRangeException | 如果是未知或不受支持的格式 |


---


### toJpeg {#toJpeg}

| 名称 | 描述 |
| --- | --- |
| toJpeg ([Presentation](../presentation), String) | 将输入演示文稿转换为一组 JPEG 格式的图像。如果输出文件名为 "myPath/myFilename.jpeg"，则结果将保存为一组 "myPath/myFilename_N.jpeg" 文件，N 为幻灯片编号。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../presentation) | 输入的演示文稿。 |
| outputFileName | String | 输出文件名。 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
 | null | ArgumentException |


---


### toJpeg {#toJpeg}

| 名称 | 描述 |
| --- | --- |
| toJpeg ([Presentation](../presentation), String, Dimension) | 将输入演示文稿转换为一组 JPEG 格式的图像。如果输出文件名为 "myPath/myFilename.jpeg"，则结果将保存为一组 "myPath/myFilename_N.jpeg" 文件，N 为幻灯片编号。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../presentation) | 输入演示文稿 |
| outputFileName | String | 输出文件名。 |
| imageSize | Dimension | 每个生成图像的尺寸。 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
 | null | ArgumentException |


---


### toJpeg {#toJpeg}

| 名称 | 描述 |
| --- | --- |
| toJpeg ([Presentation](../presentation), String, float, [RenderingOptions](../renderingoptions)) | 将输入演示文稿转换为一组 JPEG 格式的图像。如果输出文件名为 "myPath/myFilename.jpeg"，则结果将保存为一组 "myPath/myFilename_N.jpeg" 文件，N 为幻灯片编号。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../presentation) | 输入演示文稿。 |
| outputFileName | String | 输出文件名。 |
| scale | float | 相对于原始幻灯片尺寸的缩放因子。 |
| options | [RenderingOptions](../renderingoptions) | 渲染选项。 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
 | null | ArgumentException |


---


### toPdf {#toPdf}

| 名称 | 描述 |
| --- | --- |
| toPdf (String, String) | 将 Presentation 转换为 PDF。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| presPath | String | 输入演示文稿的路径 |
| outPath | String | 输出路径 |

 **返回：**
void


---


### toPdf {#toPdf}

| 名称 | 描述 |
| --- | --- |
| toPdf (String, String, [PdfOptions](../pdfoptions)) | 将 Presentation 转换为 PDF。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| presPath | String | 输入演示文稿的路径 |
| outPath | String | 输出路径 |
| options | [PdfOptions](../pdfoptions) | 输出 PDF 选项 |

 **返回：**
void


---


### toPdf {#toPdf}

| 名称 | 描述 |
| --- | --- |
| toPdf ([Presentation](../presentation), String) | 将 Presentation 转换为 PDF。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../presentation) | 输入演示文稿 |
| outPath | String | 输出路径 |

 **返回：**
void


---


### toPdf {#toPdf}

| 名称 | 描述 |
| --- | --- |
| toPdf ([Presentation](../presentation), String, [PdfOptions](../pdfoptions)) | 将 Presentation 转换为 PDF。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../presentation) | 输入演示文稿 |
| outPath | String | 输出路径 |
| options | [PdfOptions](../pdfoptions) | 输出 PDF 选项 |

 **返回：**
void


---


### toPng {#toPng}

| 名称 | 描述 |
| --- | --- |
| toPng ([Presentation](../presentation), String) | 将输入演示文稿转换为一组 PNG 格式的图像。如果输出文件名为 "myPath/myFilename.png"，则结果将保存为一组 "myPath/myFilename_N.png" 文件，N 为幻灯片编号。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../presentation) | 输入演示文稿。 |
| outputFileName | String | 输出文件名。 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
 | null | ArgumentException |


---


### toPng {#toPng}

| 名称 | 描述 |
| --- | --- |
| toPng ([Presentation](../presentation), String, Dimension) | 将输入演示文稿转换为一组 PNG 格式的图像。如果输出文件名为 "myPath/myFilename.png"，则结果将保存为一组 "myPath/myFilename_N.png" 文件，N 为幻灯片编号。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../presentation) | 输入演示文稿 |
| outputFileName | String | 输出文件名。 |
| imageSize | Dimension | 每个生成图像的尺寸。 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
 | null | ArgumentException |


---


### toPng {#toPng}

| 名称 | 描述 |
| --- | --- |
| toPng ([Presentation](../presentation), String, float, [RenderingOptions](../renderingoptions)) | 将输入演示文稿转换为一组 PNG 格式的图像。如果输出文件名为 "myPath/myFilename.png"，则结果将保存为一组 "myPath/myFilename_N.png" 文件，N 为幻灯片编号。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../presentation) | 输入演示文稿。 |
| outputFileName | String | 输出文件名。 |
| scale | float | 相对于原始幻灯片尺寸的缩放因子。 |
| options | [RenderingOptions](../renderingoptions) | 渲染选项。 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
 | null | ArgumentException |


---


### toSvg {#toSvg}

| 名称 | 描述 |
| --- | --- |
| toSvg (String) | 将 Presentation 转换为 SVG。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| presPath | String | 输入演示文稿的路径 |

 **返回：**
void


---


### toSvg {#toSvg}

| 名称 | 描述 |
| --- | --- |
| toSvg (String, [Convert.GetOutPathCallback](../convert.getoutpathcallback)) | 将 Presentation 转换为 SVG。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| presPath | String | 输入演示文稿的路径 |
| getOutPath | [Convert.GetOutPathCallback](../convert.getoutpathcallback) | 为演示文稿中每个幻灯片返回 SVG 输出路径的回调函数 |

 **返回：**
void


---


### toSvg {#toSvg}

| 名称 | 描述 |
| --- | --- |
| toSvg ([Presentation](../presentation), [Convert.GetOutPathCallback](../convert.getoutpathcallback)) | 将 Presentation 转换为 SVG。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../presentation) | 输入演示文稿 |
| getOutPath | [Convert.GetOutPathCallback](../convert.getoutpathcallback) | 为演示文稿中每个幻灯片返回 SVG 输出路径的回调函数 |

 **返回：**
void


---


### toSvg {#toSvg}

| 名称 | 描述 |
| --- | --- |
| toSvg ([Presentation](../presentation), [SVGOptions](../svgoptions)) | 将 Presentation 转换为 SVG。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../presentation) | 输入演示文稿 |
| options | [SVGOptions](../svgoptions) | SVG 导出选项 |

 **返回：**
void


---


### toSvg {#toSvg}

| 名称 | 描述 |
| --- | --- |
| toSvg ([Presentation](../presentation), [Convert.GetOutPathCallback](../convert.getoutpathcallback), [SVGOptions](../svgoptions)) | 将 Presentation 转换为 SVG。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../presentation) | 输入演示文稿 |
| getOutPath | [Convert.GetOutPathCallback](../convert.getoutpathcallback) | 为演示文稿中每个幻灯片返回 SVG 输出路径的回调函数 |
| options | [SVGOptions](../svgoptions) | SVG 导出选项 |

 **返回：**
void


---


### toTiff {#toTiff}

| 名称 | 描述 |
| --- | --- |
| toTiff ([Presentation](../presentation), String) | 将输入演示文稿转换为一组 TIFF 格式的图像。如果输出文件名为 "myPath/myFilename.tiff"，则结果将保存为一组 "myPath/myFilename_N.tiff" 文件，N 为幻灯片编号。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../presentation) | 输入演示文稿。 |
| outputFileName | String | 输出文件名。 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
 | null | ArgumentException |


---


### toTiff {#toTiff}

| 名称 | 描述 |
| --- | --- |
| toTiff ([Presentation](../presentation), String, [TiffOptions](../tiffoptions), boolean) | 使用自定义选项将输入演示文稿转换为 TIFF 格式。如果输出文件名为 "myPath/myFilename.tiff" 且 multipage 为 false，则结果将保存为一组 "myPath/myFilename_N.tiff" 文件，N 为幻灯片编号。否则，如果 multipage 为 true，结果将是一个多页的 "myPath/myFilename.tiff" 文档。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../presentation) | 输入演示文稿。 |
| outputFileName | String | 输出文件名。 |
| options | [TiffOptions](../tiffoptions) | TIFF 保存选项。 |
| multipage | boolean | 指定生成的 TIFF 文档是否为多页。 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
 | null | ArgumentException |
