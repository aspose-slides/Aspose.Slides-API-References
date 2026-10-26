---
title: Collect
second_title: Aspose.Slides para Android mediante la referencia de la API Java
description: Representa un grupo de métodos destinados a recopilar objetos de modelo de diferentes tipos de .
type: docs
url: /es/com.aspose.slides/collect/
---
**Herencia:**
java.lang.Object
```
public class Collect
```

Representa un grupo de métodos destinados a recopilar objetos de modelo de diferentes tipos de [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // ... cambiar el formato de la forma u otras propiedades
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Collect()](#Collect--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [shapes(Presentation pres)](#shapes-com.aspose.slides.Presentation-) | Recopila todas las instancias de [Shape](../../com.aspose.slides/shape) en el [Presentation](../../com.aspose.slides/presentation). |
### Collect() {#Collect--}
```
public Collect()
```

### shapes(Presentation pres) {#shapes-com.aspose.slides.Presentation-}
```
public static System.Collections.Generic.IGenericEnumerable<Shape> shapes(Presentation pres)
```

Recopila todas las instancias de [Shape](../../com.aspose.slides/shape) en el [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // si la forma es AutoShape, agregar un borde sólido negro
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


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation para recopilar formas |

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.Shape> - Colección de todas las formas que contiene en la presentación