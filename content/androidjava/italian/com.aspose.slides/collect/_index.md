---
title: Collect
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta un gruppo di metodi destinati a raccogliere oggetti modello di diversi tipi da .
type: docs
url: /it/com.aspose.slides/collect/
---
**Eredità:**
java.lang.Object
```
public class Collect
```

Rappresenta un gruppo di metodi destinati a raccogliere oggetti modello di diversi tipi da [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // ... modificare la formattazione della forma o altre proprietà
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Collect()](#Collect--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [shapes(Presentation pres)](#shapes-com.aspose.slides.Presentation-) | Raccoglie tutte le istanze di [Shape](../../com.aspose.slides/shape) nel [Presentation](../../com.aspose.slides/presentation). |
### Collect() {#Collect--}
```
public Collect()
```


### shapes(Presentation pres) {#shapes-com.aspose.slides.Presentation-}
```
public static System.Collections.Generic.IGenericEnumerable<Shape> shapes(Presentation pres)
```


Raccoglie tutte le istanze di [Shape](../../com.aspose.slides/shape) nel [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // se la forma è AutoShape, aggiungi un bordo solido nero
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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentazione per raccogliere le forme |

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.Shape> - Collezione di tutte le forme contenute nella presentazione