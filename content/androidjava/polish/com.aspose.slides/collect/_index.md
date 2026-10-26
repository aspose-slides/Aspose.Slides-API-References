---
title: Collect
second_title: Aspose.Slides dla Androida poprzez dokumentację Java API
description: Reprezentuje grupę metod przeznaczonych do zbierania obiektów modelu różnych typów z .
type: docs
url: /pl/com.aspose.slides/collect/
---
**Dziedziczenie:**
java.lang.Object
```
public class Collect
```

Reprezentuje grupę metod przeznaczonych do zbierania obiektów modelu różnych typów z [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // ... zmień formatowanie kształtu lub inne właściwości
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [Collect()](#Collect--) |  |
## Metody

| Metoda | Opis |
| --- | --- |
| [shapes(Presentation pres)](#shapes-com.aspose.slides.Presentation-) | Zbiera wszystkie instancje [Shape](../../com.aspose.slides/shape) w [Presentation](../../com.aspose.slides/presentation). |
### Collect() {#Collect--}
```
public Collect()
```


### shapes(Presentation pres) {#shapes-com.aspose.slides.Presentation-}
```
public static System.Collections.Generic.IGenericEnumerable<Shape> shapes(Presentation pres)
```


Zbiera wszystkie instancje [Shape](../../com.aspose.slides/shape) w [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // jeśli kształt jest AutoShape, dodaj czarną jednolitą obwódkę
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
| Parametr | Typ | Opis |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Prezentacja do zbierania kształtów |

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.Shape> - Kolekcja wszystkich kształtów zawartych w prezentacji