---
title: IInkBrush
second_title: Aspose.Slides for Java API Reference
description: Represents trace brush.
type: docs
url: /pl/com.aspose.slides/iinkbrush/
---```
public interface IInkBrush
```

Reprezentuje pędzel śladowy.
## Metody

| Metoda | Opis |
| --- | --- |
| [getColor()](#getColor--) | Pobiera lub ustawia kolor pędzla dla linii. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Pobiera lub ustawia kolor pędzla dla linii. |
| [getSize()](#getSize--) | Pobiera lub ustawia rozmiar pędzla dla linii w punktach. |
| [setSize(Dimension2D value)](#setSize-java.awt.geom.Dimension2D-) | Pobiera lub ustawia rozmiar pędzla dla linii w punktach. |
| [getInkEffect()](#getInkEffect--) | Pobiera typ efektu tuszu (np. Galaxy, Gold, Silver), który określa styl wizualny kreski tuszu. |

### getColor() {#getColor--}
```
public abstract Color getColor()
```

Pobiera lub ustawia kolor pędzla dla linii.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Color brushColor = brush.getColor();
>      brush.setColor(Color.RED);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Zwraca:**
java.awt.Color

### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```

Pobiera lub ustawia kolor pędzla dla linii.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Color brushColor = brush.getColor();
>      brush.setColor(Color.RED);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.awt.Color |  |

### getSize() {#getSize--}
```
public abstract Dimension2D getSize()
```

Pobiera lub ustawia rozmiar pędzla dla linii w punktach.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Dimension2D brushSize = brush.getSize();
>      brush.setSize(new Dimension(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Zwraca:**
java.awt.geom.Dimension2D

### setSize(Dimension2D value) {#setSize-java.awt.geom.Dimension2D-}
```
public abstract void setSize(Dimension2D value)
```

Pobiera lub ustawia rozmiar pędzla dla linii w punktach.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Dimension2D brushSize = brush.getSize();
>      brush.setSize(new Dimension(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.awt.geom.Dimension2D |  |

### getInkEffect() {#getInkEffect--}
```
public abstract int getInkEffect()
```

Pobiera typ efektu tuszu (np. Galaxy, Gold, Silver), który określa styl wizualny kreski tuszu. Wartość jest parsowana z właściwości pędzla „inkEffects”. Jeśli nie określono rozpoznawalnego efektu, zwracane jest [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      Ink ink = (Ink) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkBrush brush = ink.getTraces()[0].getBrush();
>      System.out.println("InkEffects = " + brush.getInkEffect());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Zwraca:**
int