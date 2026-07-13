---
title: Collect
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en grupp av metoder avsedda att samla modellobjekt av olika typer från .
type: docs
url: /sv/com.aspose.slides/collect/
---
**Arv:**
java.lang.Object
```
public class Collect
```

Representerar en grupp av metoder avsedda att samla modellobjekt av olika typer från [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // ... ändra formatering av formen eller andra egenskaper
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [Collect()](#Collect--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [shapes(Presentation pres)](#shapes-com.aspose.slides.Presentation-) | Samlar alla instanser av [Shape](../../com.aspose.slides/shape) i [Presentation](../../com.aspose.slides/presentation). |
### Collect() {#Collect--}
```
public Collect()
```


### shapes(Presentation pres) {#shapes-com.aspose.slides.Presentation-}
```
public static System.Collections.Generic.IGenericEnumerable<Shape> shapes(Presentation pres)
```


Samlar alla instanser av [Shape](../../com.aspose.slides/shape) i [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // om formen är AutoShape, lägg till en svart solid kant
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


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation för att samla former |

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.Shape> - Samling av alla former som finns i presentationen