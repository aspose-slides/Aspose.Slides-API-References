---
title: ShapeElement
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs
url: /zh/aspose.slides/shapeelement/
---
## ShapeElement 类

 表示具有相同轮廓和填充属性的形状部分。

### getFillSource {#getFillSource}

| 名称 | 描述 |
| --- | --- |
| getFillSource () | 返回有关如何填充元素的信息。只读 ShapeElementFillSource。 |

 **返回：**
byte

---


### getParentShape {#getParentShape}

| 名称 | 描述 |
| --- | --- |
| getParentShape () | 返回创建该元素的 Shape_PPT。只读 Shape。 |

 **返回：**
Shape

---


### getPathPoints {#getPathPoints}

| 名称 | 描述 |
| --- | --- |
| getPathPoints () | 获取定义元素路径几何形状的点数组。 |

 **返回：**
Point2D.Float

---


### getPathTypes {#getPathTypes}

| 名称 | 描述 |
| --- | --- |
| getPathTypes () | 获取指定元素路径中每个点类型的字节值数组。0 表示该点是图形的起始点。1 表示该点是线段的两个端点之一。3 表示该点是三次贝塞尔样条的端点或控制点。7 将所有位掩码为除最低三位之外的位，这三位指示点类型。16 指定相应段为虚线。32 指定该点为标记。128 指定该点是闭合子路径（图形）中的最后一点。129 表示既是线段端点又是闭合子路径最后一点的数据点。 |

 **返回：**
byte

---


### getStrokeSource {#getStrokeSource}

| 名称 | 描述 |
| --- | --- |
| getStrokeSource () | 返回有关如何描边元素的信息。只读 ShapeElementStrokeSource。 |

 **返回：**
byte

---