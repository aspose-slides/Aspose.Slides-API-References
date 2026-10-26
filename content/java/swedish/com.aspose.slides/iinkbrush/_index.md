---
title: IInkBrush
second_title: Aspose.Slides for Java API Reference
description: Representerar spårpensel.
type: docs
url: /sv/com.aspose.slides/iinkbrush/
---```
public interface IInkBrush
```

Representerar spårpensel.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getColor()](#getColor--) | Hämtar eller anger penselfärgen för en linje. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Hämtar eller anger penselfärgen för en linje. |
| [getSize()](#getSize--) | Hämtar eller anger penselstorleken för en linje i punkter. |
| [setSize(Dimension2D value)](#setSize-java.awt.geom.Dimension2D-) | Hämtar eller anger penselstorleken för en linje i punkter. |
| [getInkEffect()](#getInkEffect--) | Hämtar bläckeffekttypen (t.ex. Galaxy, Gold, Silver) som definierar den visuella stilen på bläckstrecket. |
### getColor() {#getColor--}
```
public abstract Color getColor()
```


Hämtar eller anger penselfärgen för en linje.

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

**Returnerar:**  
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```


Hämtar eller anger penselfärgen för en linje.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.awt.Color |  |

### getSize() {#getSize--}
```
public abstract Dimension2D getSize()
```


Hämtar eller anger penselstorleken för en linje i punkter.

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

**Returnerar:**  
java.awt.geom.Dimension2D
### setSize(Dimension2D value) {#setSize-java.awt.geom.Dimension2D-}
```
public abstract void setSize(Dimension2D value)
```


Hämtar eller anger penselstorleken för en linje i punkter.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.awt.geom.Dimension2D |  |

### getInkEffect() {#getInkEffect--}
```
public abstract int getInkEffect()
```


Hämtar bläckeffekttypen (t.ex. Galaxy, Gold, Silver) som definierar den visuella stilen på bläckstrecket. Värdet hämtas från penseln egenskap "inkEffects". Om ingen igenkänd effekt anges, [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) returneras.

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

**Returnerar:**  
int