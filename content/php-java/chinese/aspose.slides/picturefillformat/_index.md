---
title: PictureFillFormat
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/picturefillformat/
---
## PictureFillFormat 类

 表示一种图片填充样式。
 
### compressImage {#compressImage}

| 名称 | 描述 |
| --- | --- |
| compressImage (boolean, int) | 通过基于形状大小和指定分辨率来减小图像尺寸，从而压缩图像。可选地，它还会删除裁剪区域。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| deleteCroppedAreasOfImage | boolean | 如果为 true，方法将删除图像的裁剪区域，可能进一步减小其大小。 |
| resolution | int | 压缩的目标分辨率，以 PicturesCompression 枚举的值指定。此方法会更改图像的大小和分辨率，类似于 PowerPoint 的 “Picture Format -> Compress Pictures” 功能。 |

 **返回值：**
boolean

 **异常**

| 错误 | 条件 |
| --- | --- |
 | ArgumentException | 当分辨率不是有效值时抛出。 |


---


### compressImage {#compressImage}

| 名称 | 描述 |
| --- | --- |
| compressImage (boolean, float) | 通过基于形状大小和指定分辨率来减小图像尺寸，从而压缩图像。可选地，它还会删除裁剪区域。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| deleteCroppedAreasOfImage | boolean | 如果为 true，方法将删除图像的裁剪区域，可能进一步减小其大小。 |
| resolution | float | 以 DPI 为单位的目标分辨率。该值必须为正数，并定义图像的缩放方式。此方法会更改图像的大小和分辨率，类似于 PowerPoint 的 “Picture Format -> Compress Pictures” 功能。 |

 **返回值：**
boolean

 **异常**

| 错误 | 条件 |
| --- | --- |
 | ArgumentException | 当分辨率不是正值时抛出。 |


---


### deletePictureCroppedAreas {#deletePictureCroppedAreas}

| 名称 | 描述 |
| --- | --- |
| deletePictureCroppedAreas () | 删除填充图片的裁剪区域。 |

 **返回值：**
[PPImage](../ppimage)


---


### getCropBottom {#getCropBottom}

| 名称 | 描述 |
| --- | --- |
| getCropBottom () | 返回或设置图片底部被裁剪的实际图像高度的百分比。读写 float。 |

 **返回值：**
float


---


### getCropLeft {#getCropLeft}

| 名称 | 描述 |
| --- | --- |
| getCropLeft () | 返回或设置图片左侧被裁剪的实际图像宽度的百分比。读写 float。 |

 **返回值：**
float


---


### getCropRight {#getCropRight}

| 名称 | 描述 |
| --- | --- |
| getCropRight () | 返回或设置图片右侧被裁剪的实际图像宽度的百分比。读写 float。 |

 **返回值：**
float


---


### getCropTop {#getCropTop}

| 名称 | 描述 |
| --- | --- |
| getCropTop () | 返回或设置图片顶部被裁剪的实际图像高度的百分比。读写 float。 |

 **返回值：**
float


---


### getDpi {#getDpi}

| 名称 | 描述 |
| --- | --- |
| getDpi () | 返回或设置用于填充图片的 dpi。读写 int。 |

 **返回值：**
int


---


### getPicture {#getPicture}

| 名称 | 描述 |
| --- | --- |
| getPicture () | 返回图片。只读 ISlidesPicture。 |

 **返回值：**
[Picture](../picture)


---


### getPictureFillMode {#getPictureFillMode}

| 名称 | 描述 |
| --- | --- |
| getPictureFillMode () | 返回或设置图片填充模式。读写 PictureFillMode。 |

 **返回值：**
int


---


### getStretchOffsetBottom {#getStretchOffsetBottom}

| 名称 | 描述 |
| --- | --- |
| getStretchOffsetBottom () | 返回或设置填充矩形的底部边缘，该边缘由相对于形状边界框底部边缘的百分比偏移定义。正百分比表示内缩，负百分比表示外扩。读写 float。 |

 **返回值：**
float


---


### getStretchOffsetLeft {#getStretchOffsetLeft}

| 名称 | 描述 |
| --- | --- |
| getStretchOffsetLeft () | 返回或设置填充矩形的左侧边缘，该边缘由相对于形状边界框左侧边缘的百分比偏移定义。正百分比表示内缩，负百分比表示外扩。读写 float。 |

 **返回值：**
float


---


### getStretchOffsetRight {#getStretchOffsetRight}

| 名称 | 描述 |
| --- | --- |
| getStretchOffsetRight () | 返回或设置填充矩形的右侧边缘，该边缘由相对于形状边界框右侧边缘的百分比偏移定义。正百分比表示内缩，负百分比表示外扩。读写 float。 |

 **返回值：**
float


---


### getStretchOffsetTop {#getStretchOffsetTop}

| 名称 | 描述 |
| --- | --- |
| getStretchOffsetTop () | 返回或设置填充矩形的顶部边缘，该边缘由相对于形状边界框顶部边缘的百分比偏移定义。正百分比表示内缩，负百分比表示外扩。读写 float。 |

 **返回值：**
float


---


### getTileAlignment {#getTileAlignment}

| 名称 | 描述 |
| --- | --- |
| getTileAlignment () | 返回或设置纹理在形状内的对齐方式。此设置控制纹理图案的起始点以及在形状上的重复方式。读写 RectangleAlignment。默认是 RectangleAlignment#TopLeft。 |

 **返回值：**
byte


---


### getTileFlip {#getTileFlip}

| 名称 | 描述 |
| --- | --- |
| getTileFlip () | 在水平、垂直或两者轴上翻转纹理平铺。读写 TileFlip。默认是 TileFlip#NoFlip。 |

 **返回值：**
int


---


### getTileOffsetX {#getTileOffsetX}

| 名称 | 描述 |
| --- | --- |
| getTileOffsetX () | 返回或设置纹理相对于形状原点的水平偏移（以点为单位）。正值将纹理向右移动，负值向左移动。读写 float。 |

 **返回值：**
float


---


### getTileOffsetY {#getTileOffsetY}

| 名称 | 描述 |
| --- | --- |
| getTileOffsetY () | 返回或设置纹理相对于形状原点的垂直偏移（以点为单位）。正值将纹理向下移动，负值向上移动。读写 float。 |

 **返回值：**
float


---


### getTileScaleX {#getTileScaleX}

| 名称 | 描述 |
| --- | --- |
| getTileScaleX () | 返回或设置纹理填充的水平比例（百分比）。读写 float。 |

 **返回值：**
float


---


### getTileScaleY {#getTileScaleY}

| 名称 | 描述 |
| --- | --- |
| getTileScaleY () | 返回或设置纹理填充的垂直比例（百分比）。读写 float。 |

 **返回值：**
float


---


### getVersion {#getVersion}

| 名称 | 描述 |
| --- | --- |
| getVersion () |  |

 **返回值：**
long


---


### setCropBottom {#setCropBottom}

| 名称 | 描述 |
| --- | --- |
| setCropBottom (float) | 返回或设置图片底部被裁剪的实际图像高度的百分比。读写 float。 |

 **返回值：**
void


---


### setCropLeft {#setCropLeft}

| 名称 | 描述 |
| --- | --- |
| setCropLeft (float) | 返回或设置图片左侧被裁剪的实际图像宽度的百分比。读写 float。 |

 **返回值：**
void


---


### setCropRight {#setCropRight}

| 名称 | 描述 |
| --- | --- |
| setCropRight (float) | 返回或设置图片右侧被裁剪的实际图像宽度的百分比。读写 float。 |

 **返回值：**
void


---


### setCropTop {#setCropTop}

| 名称 | 描述 |
| --- | --- |
| setCropTop (float) | 返回或设置图片顶部被裁剪的实际图像高度的百分比。读写 float。 |

 **返回值：**
void


---


### setDpi {#setDpi}

| 名称 | 描述 |
| --- | --- |
| setDpi (int) | 返回或设置用于填充图片的 dpi。读写 int。 |

 **返回值：**
void


---


### setPictureFillMode {#setPictureFillMode}

| 名称 | 描述 |
| --- | --- |
| setPictureFillMode (int) | 返回或设置图片填充模式。读写 PictureFillMode。 |

 **返回值：**
void


---


### setStretchOffsetBottom {#setStretchOffsetBottom}

| 名称 | 描述 |
| --- | --- |
| setStretchOffsetBottom (float) | 返回或设置填充矩形的底部边缘，该边缘由相对于形状边界框底部边缘的百分比偏移定义。正百分比表示内缩，负百分比表示外扩。读写 float。 |

 **返回值：**
void


---


### setStretchOffsetLeft {#setStretchOffsetLeft}

| 名称 | 描述 |
| --- | --- |
| setStretchOffsetLeft (float) | 返回或设置填充矩形的左侧边缘，该边缘由相对于形状边界框左侧边缘的百分比偏移定义。正百分比表示内缩，负百分比表示外扩。读写 float。 |

 **返回值：**
void


---


### setStretchOffsetRight {#setStretchOffsetRight}

| 名称 | 描述 |
| --- | --- |
| setStretchOffsetRight (float) | 返回或设置填充矩形的右侧边缘，该边缘由相对于形状边界框右侧边缘的百分比偏移定义。正百分比表示内缩，负百分比表示外扩。读写 float。 |

 **返回值：**
void


---


### setStretchOffsetTop {#setStretchOffsetTop}

| 名称 | 描述 |
| --- | --- |
| setStretchOffsetTop (float) | 返回或设置填充矩形的顶部边缘，该边缘由相对于形状边界框顶部边缘的百分比偏移定义。正百分比表示内缩，负百分比表示外扩。读写 float。 |

 **返回值：**
void


---


### setTileAlignment {#setTileAlignment}

| 名称 | 描述 |
| --- | --- |
| setTileAlignment (byte) | 返回或设置纹理在形状内的对齐方式。此设置控制纹理图案的起始点以及在形状上的重复方式。读写 RectangleAlignment。默认是 RectangleAlignment#TopLeft。 |

 **返回值：**
void


---


### setTileFlip {#setTileFlip}

| 名称 | 描述 |
| --- | --- |
| setTileFlip (int) | 在水平、垂直或两者轴上翻转纹理平铺。读写 TileFlip。默认是 TileFlip#NoFlip。 |

 **返回值：**
void


---


### setTileOffsetX {#setTileOffsetX}

| 名称 | 描述 |
| --- | --- |
| setTileOffsetX (float) | 返回或设置纹理相对于形状原点的水平偏移（以点为单位）。正值将纹理向右移动，负值向左移动。读写 float。 |

 **返回值：**
void


---


### setTileOffsetY {#setTileOffsetY}

| 名称 | 描述 |
| --- | --- |
| setTileOffsetY (float) | 返回或设置纹理相对于形状原点的垂直偏移（以点为单位）。正值将纹理向下移动，负值向上移动。读写 float。 |

 **返回值：**
void


---


### setTileScaleX {#setTileScaleX}

| 名称 | 描述 |
| --- | --- |
| setTileScaleX (float) | 返回或设置纹理填充的水平比例（百分比）。读写 float。 |

 **返回值：**
void


---


### setTileScaleY {#setTileScaleY}

| 名称 | 描述 |
| --- | --- |
| setTileScaleY (float) | 返回或设置纹理填充的垂直比例（百分比）。读写 float。 |

 **返回值：**
void


---