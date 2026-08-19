---
title: InkBrush
second_title: Aspose.Slides för Java API-referens
description: Representerar ett inkBrush-objekt.
type: docs
url: /sv/com.aspose.slides/inkbrush/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IInkBrush](../../com.aspose.slides/iinkbrush)
```
public class InkBrush implements IInkBrush
```

Representerar ett inkBrush-objekt.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getColor()](#getColor--) | Hämtar eller anger penselfärgen för en linje. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Hämtar eller anger penselfärgen för en linje. |
| [getSize()](#getSize--) | Hämtar eller anger penselstorleken för en linje i punkter. |
| [setSize(Dimension2D value)](#setSize-java.awt.geom.Dimension2D-) | Hämtar eller anger penselstorleken för en linje i punkter. |
| [getInkEffect()](#getInkEffect--) | Hämtar ink-effekttypen (t.ex. Galaxy, Gold, Silver) som definierar den visuella stilen för bläckstrecket. |

### getColor() {#getColor--}
```
public final Color getColor()
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
public final void setColor(Color value)
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
public final Dimension2D getSize()
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
public final void setSize(Dimension2D value)
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
public final int getInkEffect()
```


Hämtar ink-effekttypen (t.ex. Galaxy, Gold, Silver) som definierar den visuella stilen för bläckstrecket. Värdet tolkas från pensel-egenskapen "inkEffects". Om ingen erkänd effekt anges, [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) returneras.

**Returnerar:**
int