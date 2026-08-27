---
title: PatternFormat
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs
url: /zh/aspose.slides/patternformat/
---
## PatternFormat 类

 表示用于填充形状的模式。
 
### getBackColor {#getBackColor}

| 名称 | 描述 |
| --- | --- |
| getBackColor () | 返回背景模式颜色。只读 IColorFormat。 |

 **返回：**
[ColorFormat](../colorformat)


---


### getForeColor {#getForeColor}

| 名称 | 描述 |
| --- | --- |
| getForeColor () | 返回前景模式颜色。只读 IColorFormat。 |

 **返回：**
[ColorFormat](../colorformat)


---


### getPatternStyle {#getPatternStyle}

| 名称 | 描述 |
| --- | --- |
| getPatternStyle () | 返回或设置模式样式。读/写 PatternStyle。 |

 **返回：**
byte


---


### getTile {#getTile}

| 名称 | 描述 |
| --- | --- |
| getTile (Color, Color) | 创建具有指定颜色的模式填充平铺图像。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| background | Color | 用于模式的背景 java.awt.Color。 |
| foreground | Color | 用于模式的前景 java.awt.Color。 |

 **返回：**
IImage


---


### getTile {#getTile}

| 名称 | 描述 |
| --- | --- |
| getTile (Color) | 创建用于模式填充的平铺图像。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| styleColor | Color | 默认的 java.awt.Color |

 **返回：**
IImage


---


### getVersion {#getVersion}

| 名称 | 描述 |
| --- | --- |
| getVersion () |  |

 **返回：**
long


---


### setPatternStyle {#setPatternStyle}

| 名称 | 描述 |
| --- | --- |
| setPatternStyle (byte) | 返回或设置模式样式。读/写 PatternStyle。 |

 **返回：**
void


---