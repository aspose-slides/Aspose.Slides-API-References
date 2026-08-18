---
title: InkBrush
second_title: Aspose.Slides für Java API-Referenz
description: Stellt ein inkBrush-Objekt dar.
type: docs
url: /de/com.aspose.slides/inkbrush/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IInkBrush](../../com.aspose.slides/iinkbrush)
```
public class InkBrush implements IInkBrush
```

Stellt ein inkBrush-Objekt dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getColor()](#getColor--) | Liest oder setzt die Pinselfarbe für eine Linie. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Liest oder setzt die Pinselfarbe für eine Linie. |
| [getSize()](#getSize--) | Liest oder setzt die Pinselgröße für eine Linie in Punkten. |
| [setSize(Dimension2D value)](#setSize-java.awt.geom.Dimension2D-) | Liest oder setzt die Pinselgröße für eine Linie in Punkten. |
| [getInkEffect()](#getInkEffect--) | Liest den Tinteneffekttyp (z. B. Galaxy, Gold, Silver), der den visuellen Stil des Tintenschlags definiert. |
### getColor() {#getColor--}
```
public final Color getColor()
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

**Rückgabewert:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
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
public final Dimension2D getSize()
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

**Rückgabewert:**
java.awt.geom.Dimension2D
### setSize(Dimension2D value) {#setSize-java.awt.geom.Dimension2D-}
```
public final void setSize(Dimension2D value)
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
public final int getInkEffect()
```


Liest den Tinteneffekttyp (z. B. Galaxy, Gold, Silver), der den visuellen Stil des Tintenschlags definiert. Der Wert wird aus der Pinsel-Eigenschaft „inkEffects“ geparst. Wenn kein erkannter Effekt angegeben ist, wird [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) zurückgegeben.

**Rückgabewert:**
int