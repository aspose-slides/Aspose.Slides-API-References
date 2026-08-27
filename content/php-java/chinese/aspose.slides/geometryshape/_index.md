---
title: GeometryShape
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs
url: /zh/aspose.slides/geometryshape/
---
## GeometryShape 类

 代表所有几何形状的父类。
 
### createShapeElements {#createShapeElements}

| 名称 | 描述 |
| --- | --- |
| createShapeElements () | 创建并返回形状元素的数组。 |

 **返回：**
[ShapeElement](../shapeelement)


---


### getAdjustments {#getAdjustments}

| 名称 | 描述 |
| --- | --- |
| getAdjustments () | 返回形状的调整值集合。只读 IAdjustValueCollection。 |

 **返回：**
[AdjustValueCollection](../adjustvaluecollection)


---


### getGeometryPaths {#getGeometryPaths}

| 名称 | 描述 |
| --- | --- |
| getGeometryPaths () | 返回几何形状路径的副本。坐标相对于形状的左上角。 |

 **返回：**
[GeometryPath](../geometrypath)


---


### getShapeStyle {#getShapeStyle}

| 名称 | 描述 |
| --- | --- |
| getShapeStyle () | 返回形状的样式对象。只读 IShapeStyle。 |

 **返回：**
[ShapeStyle](../shapestyle)


---


### getShapeType {#getShapeType}

| 名称 | 描述 |
| --- | --- |
| getShapeType () | 返回或设置几何预设类型。注意：值更改时，所有调整值将重置为默认值。读/写 ShapeType。 |

 **返回：**
int


---


### setGeometryPath {#setGeometryPath}

| 名称 | 描述 |
| --- | --- |
| setGeometryPath ([GeometryPath](../geometrypath)) | 从 IGeometryPath 对象更新形状几何。坐标必须相对于形状的左上角。将形状的类型 (ShapeType( #getShapeType/ #setShapeType(int))) 更改为 ShapeType#Custom。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| geometryPath | [GeometryPath](../geometrypath) | 几何路径 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
 | ArgumentException | 找到空路径 |


---


### setGeometryPaths {#setGeometryPaths}

| 名称 | 描述 |
| --- | --- |
| setGeometryPaths (com.aspose.slides.IGeometryPath[]) | 从 IGeometryPath 数组更新形状几何。坐标必须相对于形状的左上角。将形状的类型 (ShapeType( #getShapeType/ #setShapeType(int))) 更改为 ShapeType#Custom。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| geometryPaths | com.aspose.slides.IGeometryPath[] | 数组几何路径 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
 | ArgumentException | 空路径 |


---


### setShapeType {#setShapeType}

| 名称 | 描述 |
| --- | --- |
| setShapeType (int) | 返回或设置几何预设类型。注意：值更改时，所有调整值将重置为默认值。读/写 ShapeType。 |

 **返回：**
void


---