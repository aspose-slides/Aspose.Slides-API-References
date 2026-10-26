---
title: IInkBrush
second_title: Aspose.Slides für Java API-Referenz
description: Stellt einen Trace-Pinsel dar.
type: docs
url: /de/com.aspose.slides/iinkbrush/
---```
public interface IInkBrush
```

Stellt einen Trace-Pinsel dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getColor()](#getColor--) | Liest oder setzt die Pinselfarbe für eine Linie. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Liest oder setzt die Pinselfarbe für eine Linie. |
| [getSize()](#getSize--) | Liest oder setzt die Pinselgröße für eine Linie in Punkten. |
| [setSize(Dimension2D value)](#setSize-java.awt.geom.Dimension2D-) | Liest oder setzt die Pinselgröße für eine Linie in Punkten. |
| [getInkEffect()](#getInkEffect--) | Liest den Tintentyp (z. B. Galaxy, Gold, Silver), der den visuellen Stil des Tintenklecks definiert. |
### getColor() {#getColor--}
```
public abstract Color getColor()
```


Liest oder setzt die Pinselfarbe für eine Linie.

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

**Rückgabe:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```


Liest oder setzt die Pinselfarbe für eine Linie.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.awt.Color |  |

### getSize() {#getSize--}
```
public abstract Dimension2D getSize()
```


Liest oder setzt die Pinselgröße für eine Linie in Punkten.

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

**Rückgabe:**
java.awt.geom.Dimension2D
### setSize(Dimension2D value) {#setSize-java.awt.geom.Dimension2D-}
```
public abstract void setSize(Dimension2D value)
```


Liest oder setzt die Pinselgröße für eine Linie in Punkten.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.awt.geom.Dimension2D |  |

### getInkEffect() {#getInkEffect--}
```
public abstract int getInkEffect()
```


Liest den Tintentyp (z. B. Galaxy, Gold, Silver), der den visuellen Stil des Tintenklecks definiert. Der Wert wird aus der Pinsel-Eigenschaft "inkEffects" geparst. Wenn kein erkannter Effekt angegeben ist, wird [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) zurückgegeben.

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

**Rückgabe:**
int