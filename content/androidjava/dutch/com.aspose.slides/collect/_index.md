---
title: Collect
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een groep methoden voor die bedoeld zijn om modelobjecten van verschillende typen te verzamelen uit .
type: docs
url: /nl/com.aspose.slides/collect/
---
**Erfenis:**
java.lang.Object
```
public class Collect
```

Stelt een groep methoden voor die bedoeld zijn om modelobjecten van verschillende typen te verzamelen uit [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // ... wijzig de vormopmaak of andere eigenschappen
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Collect()](#Collect--) |  |
## Methoden

| Method | Beschrijving |
| --- | --- |
| [shapes(Presentation pres)](#shapes-com.aspose.slides.Presentation-) | Verzamelt alle exemplaren van [Shape](../../com.aspose.slides/shape) in de [Presentation](../../com.aspose.slides/presentation). |
### Collect() {#Collect--}
```
public Collect()
```


### shapes(Presentation pres) {#shapes-com.aspose.slides.Presentation-}
```
public static System.Collections.Generic.IGenericEnumerable<Shape> shapes(Presentation pres)
```


Verzamelt alle exemplaren van [Shape](../../com.aspose.slides/shape) in de [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // als de vorm een AutoShape is, voeg een zwarte vaste rand toe
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentatie om vormen te verzamelen |

**Retourwaarde:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.Shape> - Collectie van alle vormen die zich in de presentatie bevinden