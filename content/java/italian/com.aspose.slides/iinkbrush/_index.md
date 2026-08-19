---
title: IInkBrush
second_title: Aspose.Slides for Java API Reference
description: Represents trace brush.
type: docs
url: /it/com.aspose.slides/iinkbrush/
---```
public interface IInkBrush
```

Rappresenta il pennello di traccia.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getColor()](#getColor--) | Ottiene o imposta il colore del pennello per una linea. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Ottiene o imposta il colore del pennello per una linea. |
| [getSize()](#getSize--) | Ottiene o imposta la dimensione del pennello per una linea in punti. |
| [setSize(Dimension2D value)](#setSize-java.awt.geom.Dimension2D-) | Ottiene o imposta la dimensione del pennello per una linea in punti. |
| [getInkEffect()](#getInkEffect--) | Ottiene il tipo di effetto inchiostro (ad es., Galaxy, Gold, Silver) che definisce lo stile visivo del tratto d'inchiostro. |

### getColor() {#getColor--}
```
public abstract Color getColor()
```

Ottiene o imposta il colore del pennello per una linea.

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

**Restituisce:**
java.awt.Color

### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```

Ottiene o imposta il colore del pennello per una linea.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.awt.Color |  |

### getSize() {#getSize--}
```
public abstract Dimension2D getSize()
```

Ottiene o imposta la dimensione del pennello per una linea in punti.

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

**Restituisce:**
java.awt.geom.Dimension2D

### setSize(Dimension2D value) {#setSize-java.awt.geom.Dimension2D-}
```
public abstract void setSize(Dimension2D value)
```

Ottiene o imposta la dimensione del pennello per una linea in punti.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.awt.geom.Dimension2D |  |

### getInkEffect() {#getInkEffect--}
```
public abstract int getInkEffect()
```

Ottiene il tipo di effetto inchiostro (ad es., Galaxy, Gold, Silver) che definisce lo stile visivo del tratto d'inchiostro. Il valore è analizzato dalla proprietà del pennello "inkEffects". Se non è specificato alcun effetto riconosciuto, [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) viene restituito.

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

**Restituisce:**
int