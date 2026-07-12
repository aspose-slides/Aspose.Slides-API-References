---
title: Collect
second_title: Aspose.Slides Androidhoz Java API-referencia
description: Olyan metóduscsoportot képvisel, amely különböző típusú modellobjektumok gyűjtésére szolgál a .
type: docs
url: /hu/com.aspose.slides/collect/
---
**Öröklés:**
java.lang.Object
```
public class Collect
```

Olyan metóduscsoportot képvisel, amely a(z) [Presentation](../../com.aspose.slides/presentation)-ból különböző típusú modellobjektumok gyűjtésére szolgál.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // ... módosítsa a forma formázását vagy egyéb tulajdonságokat
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
| [shapes(Presentation pres)](#shapes-com.aspose.slides.Presentation-) | Az összes [Shape](../../com.aspose.slides/shape) példányt a(z) [Presentation](../../com.aspose.slides/presentation)-ban gyűjti össze. |
### Collect() {#Collect--}
```
public Collect()
```

### shapes(Presentation pres) {#shapes-com.aspose.slides.Presentation-}
```
public static System.Collections.Generic.IGenericEnumerable<Shape> shapes(Presentation pres)
```

Az összes [Shape](../../com.aspose.slides/shape) példányt a(z) [Presentation](../../com.aspose.slides/presentation)-ban gyűjti össze.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // ha az alakzat AutoShape, akkor egy fekete szilárd keretet ad hozzá
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
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation a alakzatok gyűjtéséhez |

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.Shape> - Az összes alakzat gyűjteménye, amely a prezentációban található