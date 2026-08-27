---
title: IImage
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/iimage/
---
## IImage 类

 表示光栅或矢量图像。
 
 此接口提供了处理光栅和矢量图像的通用抽象。  
 实现可能因底层图像类型而异。
 
### IImage {#IImage}

| 名称 | 描述 |
| --- | --- |
| IImage() |  |

 **返回值:**
IImage


---


### getHeight {#getHeight}

| 名称 | 描述 |
| --- | --- |
| getHeight () | 获取图像的高度（像素）。 |

 **返回值:**
int


---


### getSize {#getSize}

| 名称 | 描述 |
| --- | --- |
| getSize () | 获取图像的大小。 |

 **返回值:**
Dimension


---


### getWidth {#getWidth}

| 名称 | 描述 |
| --- | --- |
| getWidth () | 获取图像的宽度（像素）。 |

 **返回值:**
int


---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (String) | 将图像保存到文件。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| filename | String | 保存图像的文件路径。 |

 **返回值:**
void


---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (String, int) | 将图像保存到指定格式的文件。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| filename | String | 保存图像的文件路径。 |
| format | int | 图像格式。 |

 **返回值:**
void


---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (OutputStream, int) | 将图像以指定格式保存到流。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | OutputStream | 保存图像的流。 |
| format | int | 图像格式。 |

 **返回值:**
void


---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (String, int, int) | 将图像以指定格式和质量保存到文件。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| filename | String | 保存图像的文件路径。 |
| format | int | 图像格式。 |
| quality | int | 已保存图像的质量（0 到 100）。此参数仅影响 ImageFormat#Jpeg 的保存；对所有其他格式均被忽略。 |

 **返回值:**
void


---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (OutputStream, int, int) | 将图像以指定格式和质量保存到流。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | OutputStream | 保存图像的流。 |
| format | int | 图像格式。 |
| quality | int | 已保存图像的质量（0 到 100）。此参数仅影响 ImageFormat#Jpeg 的保存；对所有其他格式均被忽略。 |

 **返回值:**
void


---