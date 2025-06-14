---
title: AddAutoShape
second_title: Aspose.Sildes for .NET API Reference
description: 创建一个新的自动形状，从默认模板调整它并将其添加到集合的末尾。
type: docs
weight: 90
url: /zh/aspose.slides/shapecollection/addautoshape/
---

## AddAutoShape(ShapeType, float, float, float, float) {#addautoshape}

创建一个新的自动形状，从默认模板调整它并将其添加到集合的末尾。

```csharp
public IAutoShape AddAutoShape(ShapeType shapeType, float x, float y, float width, float height)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapeType | ShapeType | 形状的 [`ShapeType`](../../shapetype)。 |
| x | Single | 形状框左侧的 X 坐标。 |
| y | Single | 形状框顶部的 Y 坐标。 |
| width | Single | 形状框的宽度。 |
| height | Single | 形状框的高度。 |

### 返回值

创建的自动形状对象。

### 另见

* 接口 [IAutoShape](../../iautoshape)
* 枚举 [ShapeType](../../shapetype)
* 类 [ShapeCollection](../../shapecollection)
* 命名空间 [Aspose.Slides](../../shapecollection)
* 程序集 [Aspose.Slides](../../../)

---

## AddAutoShape(ShapeType, float, float, float, float, bool) {#addautoshape_1}

创建一个新的自动形状并将其添加到集合的末尾。

```csharp
public IAutoShape AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, 
    bool createFromTemplate)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapeType | ShapeType | 形状的 [`ShapeType`](../../shapetype)。 |
| x | Single | 形状框左侧的 X 坐标。 |
| y | Single | 形状框顶部的 Y 坐标。 |
| width | Single | 形状框的宽度。 |
| height | Single | 形状框的高度。 |
| createFromTemplate | Boolean | 如果为 true，则新形状将从默认模板调整。新形状将被赋予非空名称、简单样式、居中文本。如果为 false，则新形状的所有属性值将具有默认值。 |

### 返回值

创建的自动形状对象。

### 另见

* 接口 [IAutoShape](../../iautoshape)
* 枚举 [ShapeType](../../shapetype)
* 类 [ShapeCollection](../../shapecollection)
* 命名空间 [Aspose.Slides](../../shapecollection)
* 程序集 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->