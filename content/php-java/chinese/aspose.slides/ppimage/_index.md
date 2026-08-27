---
title: PPImage
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/ppimage/
---
## PPImage 类

 表示演示文稿中的图像。
 
### dispose {#dispose}

| 名称 | 描述 |
| --- | --- |
| dispose () | 释放对象。 |

 **返回值：**
void


---


### getBinaryData {#getBinaryData}

| 名称 | 描述 |
| --- | --- |
| getBinaryData () | 返回图像数据的副本。只读 byte[]。 |

 **返回值：**
byte


---


### getContentType {#getContentType}

| 名称 | 描述 |
| --- | --- |
| getContentType () | 返回图像的 MIME 类型，编码在 BinaryData(#getBinaryData) 中。只读 String。 |

 **返回值：**
String


---


### getHeight {#getHeight}

| 名称 | 描述 |
| --- | --- |
| getHeight () | 返回图像的高度。只读 int。 |

 **返回值：**
int


---


### getImage {#getImage}

| 名称 | 描述 |
| --- | --- |
| getImage () | 返回图像的副本。只读 IImage。 |

 **返回值：**
IImage


---


### getSvgImage {#getSvgImage}

| 名称 | 描述 |
| --- | --- |
| getSvgImage () | 返回或设置 ISvgImage 对象 ISvgImage。此值指示该图像是由 SVG 创建的。 |

 **返回值：**
[SvgImage](../svgimage)


---


### getWidth {#getWidth}

| 名称 | 描述 |
| --- | --- |
| getWidth () | 返回图像的宽度。只读 int。 |

 **返回值：**
int


---


### getX {#getX}

| 名称 | 描述 |
| --- | --- |
| getX () | 返回图像的 X 偏移量。只读 int。 |

 **返回值：**
int


---


### getY {#getY}

| 名称 | 描述 |
| --- | --- |
| getY () | 返回图像的 Y 偏移量。只读 int。 |

 **返回值：**
int


---


### hashCode {#hashCode}

| 名称 | 描述 |
| --- | --- |
| hashCode () | 返回图像的哈希码。 |

 **返回值：**
int


---


### replaceImage {#replaceImage}

| 名称 | 描述 |
| --- | --- |
| replaceImage (byte[]) | 替换图像数据。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| newImageData | byte[] | 新图像的数据。 |

 **返回值：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
 | ArgumentNullException | 当 newImageData 参数为 null 时。 |


---


### replaceImage {#replaceImage}

| 名称 | 描述 |
| --- | --- |
| replaceImage ([IImage](../iimage)) | 替换图像数据。注意：当 Image 为元文件时——它将被栅格化。请改用 ReplaceImage(byte[])。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| newImage | [IImage](../iimage) | 新的图像。 |

 **返回值：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
 | ArgumentNullException | 当 newImage 参数为 null 时。 |


---


### replaceImage {#replaceImage}

| 名称 | 描述 |
| --- | --- |
| replaceImage ([PPImage](../ppimage)) | 替换图像数据。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| newImage | [PPImage](../ppimage) | 新的 IPPImage。 |

 **返回值：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
 | ArgumentNullException | 当 newImage 参数为 null 时。 |


---


### setSvgImage {#setSvgImage}

| 名称 | 描述 |
| --- | --- |
| setSvgImage ([SvgImage](../svgimage)) | 返回或设置 ISSvgImage 对象 ISSvgImage。此值指示该图像是由 SVG 创建的。 |

 **返回值：**
void


---