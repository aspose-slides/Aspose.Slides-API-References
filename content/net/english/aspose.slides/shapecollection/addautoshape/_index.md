---
title: AddAutoShape
second_title: Aspose.Sildes for .NET API Reference
description: Creates a new AutoShape tunes it from default template and adds it to the end of the collection.
type: docs
weight: 90
url: /aspose.slides/shapecollection/addautoshape/
---

## AddAutoShape(ShapeType, float, float, float, float) {#addautoshape}

Creates a new AutoShape, tunes it from default template and adds it to the end of the collection.

```csharp
public IAutoShape AddAutoShape(ShapeType shapeType, float x, float y, float width, float height)
```

| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | ShapeType | The [`ShapeType`](../../shapetype) of shape. |
| x | Single | The X-coordinate for a left side of shape's frame. |
| y | Single | The Y-coordinate for a top side of shape's frame. |
| width | Single | The width of shape's frame. |
| height | Single | The height of shape's frame. |

### Return Value

Created AutoShape object.

### See Also

* interface [IAutoShape](../../iautoshape)
* enum [ShapeType](../../shapetype)
* class [ShapeCollection](../../shapecollection)
* namespace [Aspose.Slides](../../shapecollection)
* assembly [Aspose.Slides](../../../)

---

## AddAutoShape(ShapeType, float, float, float, float, bool) {#addautoshape_1}

Creates a new AutoShape and adds it to the end of the collection.

```csharp
public IAutoShape AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, 
    bool createFromTemplate)
```

| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | ShapeType | The [`ShapeType`](../../shapetype) of shape. |
| x | Single | The X-coordinate for a left side of shape's frame. |
| y | Single | The Y-coordinate for a top side of shape's frame. |
| width | Single | The width of shape's frame. |
| height | Single | The height of shape's frame. |
| createFromTemplate | Boolean | If true then new shape will be tuned from default template. Not empty name, simple style, text centered will be assined to the new shape. If false then all values of the properties of the new shape will have default values. |

### Return Value

Created AutoShape object.

### See Also

* interface [IAutoShape](../../iautoshape)
* enum [ShapeType](../../shapetype)
* class [ShapeCollection](../../shapecollection)
* namespace [Aspose.Slides](../../shapecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
