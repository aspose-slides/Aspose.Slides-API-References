---
title: PptxOptions
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/pptxoptions/
---
## PptxOptions 类

 表示用于保存 OpenXml 演示文稿（PPTX、PPSX、POTX、PPTM、PPSM、POTM）的选项。
 
### PptxOptions {#PptxOptions}

| 名称 | 描述 |
| --- | --- |
| PptxOptions() | 创建 PptxOptions 的新实例 |

 **返回：**
PptxOptions


---


### getCompressionLevel {#getCompressionLevel}

| 名称 | 描述 |
| --- | --- |
| getCompressionLevel () | 指定在保存演示文稿时使用的压缩级别。默认值为 CompressionLevel#Level6。更高的压缩级别会生成更小的文件，但需要更多的处理时间。实际压缩比取决于演示文稿的内容。 |

 **返回：**
int


---


### getConformance {#getConformance}

| 名称 | 描述 |
| --- | --- |
| getConformance () | 指定演示文稿符合的合规性类别。默认值为 Conformance#Ecma376_2006 |

 **返回：**
int


---


### getRefreshThumbnail {#getRefreshThumbnail}

| 名称 | 描述 |
| --- | --- |
| getRefreshThumbnail () | 指定是否刷新演示文稿的缩略图。读/写 boolean。默认值为 true。当选项值为 true 时，将生成新的缩略图。当选项值为 false 时，当前缩略图将原样保存。 |

 **返回：**
boolean


---


### getZip64Mode {#getZip64Mode}

| 名称 | 描述 |
| --- | --- |
| getZip64Mode () | 指定是否对演示文稿使用 ZIP64 格式。默认值为 Zip64Mode#IfNecessary |

 **返回：**
int


---


### setCompressionLevel {#setCompressionLevel}

| 名称 | 描述 |
| --- | --- |
| setCompressionLevel (int) | 指定在保存演示文稿时使用的压缩级别。默认值为 CompressionLevel#Level6。更高的压缩级别会生成更小的文件，但需要更多的处理时间。实际压缩比取决于演示文稿的内容。 |

 **返回：**
void


---


### setConformance {#setConformance}

| 名称 | 描述 |
| --- | --- |
| setConformance (int) | 指定演示文稿符合的合规性类别。默认值为 Conformance#Ecma376_2006 |

 **返回：**
void


---


### setRefreshThumbnail {#setRefreshThumbnail}

| 名称 | 描述 |
| --- | --- |
| setRefreshThumbnail (boolean) | 指定是否刷新演示文稿的缩略图。读/写 boolean。默认值为 true。当选项值为 true 时，将生成新的缩略图。当选项值为 false 时，当前缩略图将原样保存。 |

 **返回：**
void


---


### setZip64Mode {#setZip64Mode}

| 名称 | 描述 |
| --- | --- |
| setZip64Mode (int) | 指定是否对演示文稿使用 ZIP64 格式。默认值为 Zip64Mode#IfNecessary |

 **返回：**
void


---