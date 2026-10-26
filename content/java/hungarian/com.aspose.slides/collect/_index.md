---
title: Collect
second_title: Aspose.Slides Java API referencia
description: Egy olyan metóduscsoportot reprezentál, amely különböző típusú modellobjektumok gyűjtésére szolgál a .
type: docs
url: /hu/com.aspose.slides/collect/
---
**Öröklés:**
java.lang.Object
```
public class Collect
```

A [Presentation](../../com.aspose.slides/presentation)-ból különböző típusú modellobjektumok gyűjtésére szánt metóduscsoportot képviseli.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // ... módosítsa a forma formázását vagy egyéb tulajdonságait
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [Collect()](#Collect--) |  |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [shapes(Presentation pres)](#shapes-com.aspose.slides.Presentation-) | Az összes [Shape](../../com.aspose.slides/shape) példányt a(z) [Presentation](../../com.aspose.slides/presentation)-ban gyűjti. |
### Collect() {#Collect--}
```
public Collect()
```

### shapes(Presentation pres) {#shapes-com.aspose.slides.Presentation-}
```
public static System.Collections.Generic.IGenericEnumerable<Shape> shapes(Presentation pres)
```

Az összes [Shape](../../com.aspose.slides/shape) példányt a(z) [Presentation](../../com.aspose.slides/presentation)-ban gyűjti.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // ha a shape AutoShape, fekete szilárd keretet ad hozzá
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


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Az alakzatok gyűjtéséhez használt prezentáció |

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.Shape> - A prezentációban található összes alakzat gyűjteménye