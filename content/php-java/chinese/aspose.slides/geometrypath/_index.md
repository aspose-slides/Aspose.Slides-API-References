---
title: GeometryPath
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/geometrypath/
---
## GeometryPath 类

 表示 GeometryShape 的几何路径

### GeometryPath {#GeometryPath}

| 名称 | 描述 |
| --- | --- |
| GeometryPath() | 创建 GeometryPath 的实例 |

 **返回：**
GeometryPath


---


### arcTo {#arcTo}

| 名称 | 描述 |
| --- | --- |
| arcTo (float, float, float, float) | 将指定的弧线添加到路径。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| width | float | 矩形的宽度 |
| heigth | float | 矩形的高度 |
| startAngle | float | 起始角度 |
| sweepAngle | float | 扫掠角度/ |

 **返回：**
void


---


### closeFigure {#closeFigure}

| 名称 | 描述 |
| --- | --- |
| closeFigure () | 关闭此路径的当前图形 |

 **返回：**
void


---


### cubicBezierTo {#cubicBezierTo}

| 名称 | 描述 |
| --- | --- |
| cubicBezierTo (Point2D.Float, Point2D.Float, Point2D.Float) | 在路径末尾添加三次贝塞尔曲线 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| point1 | Point2D.Float | 第一个方向点 |
| point2 | Point2D.Float | 第二个方向点 |
| point3 | Point2D.Float | 结束点 |

 **返回：**
void


---


### cubicBezierTo {#cubicBezierTo}

| 名称 | 描述 |
| --- | --- |
| cubicBezierTo (float, float, float, float, float, float) | 在路径末尾添加三次贝塞尔曲线 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| x1 | float | 第一个方向点的 X 坐标 |
| y1 | float | 第一个方向点的 Y 坐标 |
| x2 | float | 第二个方向点的 X 坐标 |
| y2 | float | 第二个方向点的 Y 坐标 |
| x3 | float | 结束点的 X 坐标 |
| y3 | float | 结束点的 Y 坐标 |

 **返回：**
void


---


### cubicBezierTo {#cubicBezierTo}

| 名称 | 描述 |
| --- | --- |
| cubicBezierTo (Point2D.Float, Point2D.Float, Point2D.Float, long) | 在路径的指定位置添加三次贝塞尔曲线 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| point1 | Point2D.Float | 第一个方向点 |
| point2 | Point2D.Float | 第二个方向点 |
| point3 | Point2D.Float | 结束点 |
| index | long | PathData 中段的索引 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
 | ArgumentOutOfRangeException | 段索引超出 PathData 范围 |


---


### cubicBezierTo {#cubicBezierTo}

| 名称 | 描述 |
| --- | --- |
| cubicBezierTo (float, float, float, float, float, float, long) | 在路径的指定位置添加三次贝塞尔曲线 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| x1 | float | 第一个方向点的 X 坐标 |
| y1 | float | 第一个方向点的 Y 坐标 |
| x2 | float | 第二个方向点的 X 坐标 |
| y2 | float | 第二个方向点的 Y 坐标 |
| x3 | float | 结束点的 X 坐标 |
| y3 | float | 结束点的 Y 坐标 |
| index | long | PathData 中段的索引 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
 | ArgumentOutOfRangeException | 段索引超出 PathData 范围 |


---


### getFillMode {#getFillMode}

| 名称 | 描述 |
| --- | --- |
| getFillMode () | 设置填充模式 |

 **返回：**
byte


---


### getPathData {#getPathData}

| 名称 | 描述 |
| --- | --- |
| getPathData () | 返回 GeometryShape 的几何路径，作为路径段的数组。 |

 **返回：**
[PathSegment](../pathsegment)


---


### getStroke {#getStroke}

| 名称 | 描述 |
| --- | --- |
| getStroke () | 设置描边外观 |

 **返回：**
boolean


---


### lineTo {#lineTo}

| 名称 | 描述 |
| --- | --- |
| lineTo (Point2D.Float) | 在路径末尾添加直线 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| point | Point2D.Float | 直线的结束点 |

 **返回：**
void


---


### lineTo {#lineTo}

| 名称 | 描述 |
| --- | --- |
| lineTo (float, float) | 在路径末尾添加直线 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 直线结束点的 X 坐标 |
| y | float | 直线结束点的 Y 坐标 |

 **返回：**
void


---


### lineTo {#lineTo}

| 名称 | 描述 |
| --- | --- |
| lineTo (Point2D.Float, long) | 在路径的指定位置添加直线 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| point | Point2D.Float | 结束点 |
| index | long | PathData 中段的索引 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
 | ArgumentOutOfRangeException | 段索引超出 PathData 范围 |


---


### lineTo {#lineTo}

| 名称 | 描述 |
| --- | --- |
| lineTo (float, float, long) | 在路径的指定位置添加直线 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 点的 X 坐标 |
| y | float | 点的 Y 坐标 |
| index | long | PathData 中段的索引 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
 | ArgumentOutOfRangeException | 段索引超出 PathData 范围 |


---


### moveTo {#moveTo}

| 名称 | 描述 |
| --- | --- |
| moveTo (Point2D.Float) | 设置下一个点的位置。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| point | Point2D.Float | 点的位置 |

 **返回：**
void


---


### moveTo {#moveTo}

| 名称 | 描述 |
| --- | --- |
| moveTo (float, float) | 设置下一个点的位置。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 点的 X 坐标 |
| y | float | 点的 Y 坐标 |

 **返回：**
void


---


### quadraticBezierTo {#quadraticBezierTo}

| 名称 | 描述 |
| --- | --- |
| quadraticBezierTo (Point2D.Float, Point2D.Float) | 在路径末尾添加二次贝塞尔曲线 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| point1 | Point2D.Float | 方向点 |
| point2 | Point2D.Float | 结束点 |

 **返回：**
void


---


### quadraticBezierTo {#quadraticBezierTo}

| 名称 | 描述 |
| --- | --- |
| quadraticBezierTo (float, float, float, float) | 在路径末尾添加二次贝塞尔曲线 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| x1 | float | 方向点的 X 坐标 |
| y1 | float | 方向点的 Y 坐标 |
| x2 | float | 结束点的 X 坐标 |
| y2 | float | 结束点的 Y 坐标 |

 **返回：**
void


---


### quadraticBezierTo {#quadraticBezierTo}

| 名称 | 描述 |
| --- | --- |
| quadraticBezierTo (Point2D.Float, Point2D.Float, long) | 在路径的指定位置添加二次贝塞尔曲线 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| point1 | Point2D.Float | 方向点 |
| point2 | Point2D.Float | 结束点 |
| index | long | PathData 中段的索引 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
 | ArgumentOutOfRangeException | 段索引超出 PathData 范围 |


---


### quadraticBezierTo {#quadraticBezierTo}

| 名称 | 描述 |
| --- | --- |
| quadraticBezierTo (float, float, float, float, long) | 在路径的指定位置添加二次贝塞尔曲线 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| x1 | float | 方向点的 X 坐标 |
| y1 | float | 方向点的 Y 坐标 |
| x2 | float | 结束点的 X 坐标 |
| y2 | float | 结束点的 Y 坐标 |
| index | long | PathData 中段的索引 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
 | ArgumentOutOfRangeException | 段索引超出 PathData 范围 |


---


### removeAt {#removeAt}

| 名称 | 描述 |
| --- | --- |
| removeAt (int) | 删除几何路径中指定索引处的段。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要删除的几何路径索引。 |

 **返回：**
void


---


### setFillMode {#setFillMode}

| 名称 | 描述 |
| --- | --- |
| setFillMode (byte) | 设置填充模式 |

 **返回：**
void


---


### setStroke {#setStroke}

| 名称 | 描述 |
| --- | --- |
| setStroke (boolean) | 设置描边外观 |

 **返回：**
void


---  