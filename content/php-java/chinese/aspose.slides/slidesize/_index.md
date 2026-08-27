---
title: SlideSize
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/slidesize/
---
## SlideSize 类

 表示幻灯片的尺寸和方向。
 
### getOrientation {#getOrientation}

| 名称 | 描述 |
| --- | --- |
| getOrientation () | 获取或设置幻灯片方向。更改此值会交换幻灯片的宽度和高度。 |

 **返回：**
int


---


### getSize {#getSize}

| 名称 | 描述 |
| --- | --- |
| getSize () | 获取幻灯片的尺寸（以点为单位）。分配新值会将 #getType 属性重置为 SlideSizeType#Custom 并设置 #getOrientation/ #setOrientation(int)。 |

 **返回：**
Dimension2D


---


### getType {#getType}

| 名称 | 描述 |
| --- | --- |
| getType () | 获取幻灯片尺寸类型。将任意非 SlideSizeType#Custom 的值分配给它会根据预定义尺寸调整 #getSize，同时保留当前的 #getOrientation/ #setOrientation(int)。 |

 **返回：**
int


---


### setOrientation {#setOrientation}

| 名称 | 描述 |
| --- | --- |
| setOrientation (int) | 获取或设置幻灯片方向。更改此值会交换幻灯片的宽度和高度。 |

 **返回：**
void


---


### setSize {#setSize}

| 名称 | 描述 |
| --- | --- |
| setSize (int, int) | 通过类型设置幻灯片尺寸并缩放现有内容。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| type | int | 要应用的预定义幻灯片尺寸。 |
| scaleType | int | 要使用的内容缩放模式。将任意非 SlideSizeType#Custom 的值分配给它会根据所选类型调整 #getSize，同时保留 #getOrientation/ #setOrientation(int)。 |

 **返回：**
void


---


### setSize {#setSize}

| 名称 | 描述 |
| --- | --- |
| setSize (float, float, int) | 显式设置幻灯片尺寸并缩放现有内容。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| width | float | 新的幻灯片宽度，单位为点。 |
| height | float | 新的幻灯片高度，单位为点。 |
| scaleType | int | 要使用的内容缩放模式。这会将 #getType 属性重置为 SlideSizeType#Custom 并设置 #getOrientation/ #setOrientation(int)。 |

 **返回：**
void


---