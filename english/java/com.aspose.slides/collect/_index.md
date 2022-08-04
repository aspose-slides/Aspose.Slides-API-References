---
title: Collect
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents a group of methods intended to collect model objects of different types from .
type: docs
weight: 105
url: /java/com.aspose.slides/collect/
---
**Inheritance:**
java.lang.Object
```
public class Collect
```

Represents a group of methods intended to collect model objects of different types from [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // ... change shape formatting or other properties
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [Collect()](#Collect--) |  |
## Methods

| Method | Description |
| --- | --- |
| [shapes(Presentation pres)](#shapes-com.aspose.slides.Presentation-) | Collects all instances of [Shape](../../com.aspose.slides/shape) in the [Presentation](../../com.aspose.slides/presentation). |
### Collect() {#Collect--}
```
public Collect()
```


### shapes(Presentation pres) {#shapes-com.aspose.slides.Presentation-}
```
public static System.Collections.Generic.IGenericEnumerable<Shape> shapes(Presentation pres)
```


Collects all instances of [Shape](../../com.aspose.slides/shape) in the [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // if the shape is AutoShape, add a black solid border
>          if (shape instanceof AutoShape)
>          {
>              AutoShape autoShape = (AutoShape)shape;
>              autoShape.getLineFormat().setStyle(LineStyle.Single);
>              autoShape.getLineFormat().setWidth(10f);
>              autoShape.getLineFormat().getFillFormat().setFillType(FillType.Solid);
>              autoShape.getLineFormat().getFillFormat().getSolidFillColor().setColor(Color.black);
>          }
>      }
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation to collect shapes |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.Shape> - Collection of all shapes that contain in the presentation
