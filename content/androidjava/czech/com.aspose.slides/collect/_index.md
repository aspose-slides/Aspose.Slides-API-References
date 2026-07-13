---
title: Collect
second_title: Aspose.Slides pro Android přes Java API referenci
description: Představuje skupinu metod určených ke sběru modelových objektů různých typů z .
type: docs
url: /cs/com.aspose.slides/collect/
---
**Dědičnost:**
java.lang.Object
```
public class Collect
```

Představuje skupinu metod určených k sběru modelových objektů různých typů z [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // ... změňte formátování tvaru nebo jiné vlastnosti
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [Collect()](#Collect--) |  |
## Metody

| Metoda | Popis |
| --- | --- |
| [shapes(Presentation pres)](#shapes-com.aspose.slides.Presentation-) | Shromažďuje všechny instance [Shape](../../com.aspose.slides/shape) v [Presentation](../../com.aspose.slides/presentation). |
### Collect() {#Collect--}
```
public Collect()
```

### shapes(Presentation pres) {#shapes-com.aspose.slides.Presentation-}
```
public static System.Collections.Generic.IGenericEnumerable<Shape> shapes(Presentation pres)
```

Shromažďuje všechny instance [Shape](../../com.aspose.slides/shape) v [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // pokud je tvar AutoShape, přidejte černý plný okraj
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


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation pro sběr tvarů |

**Návratová hodnota:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.Shape> - Kolekce všech tvarů, které jsou v prezentaci