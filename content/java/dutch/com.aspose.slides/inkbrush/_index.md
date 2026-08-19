---
title: InkBrush
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een inkBrush-object voor.
type: docs
url: /nl/com.aspose.slides/inkbrush/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IInkBrush](../../com.aspose.slides/iinkbrush)
```
public class InkBrush implements IInkBrush
```

Stelt een inkBrush-object voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getColor()](#getColor--) | Haalt de penseelkleur op of stelt deze in voor een lijn. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Haalt de penseelkleur op of stelt deze in voor een lijn. |
| [getSize()](#getSize--) | Haalt de penseelgrootte op of stelt deze in voor een lijn in punten. |
| [setSize(Dimension2D value)](#setSize-java.awt.geom.Dimension2D-) | Haalt de penseelgrootte op of stelt deze in voor een lijn in punten. |
| [getInkEffect()](#getInkEffect--) | Haalt het inkt-effecttype op (bijv. Galaxy, Gold, Silver) dat de visuele stijl van de inktstreep bepaalt. |

### getColor() {#getColor--}
```
public final Color getColor()
```

Haalt de penseelkleur op of stelt deze in voor een lijn.

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

**Retour:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```

Haalt de penseelkleur op of stelt deze in voor een lijn.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.awt.Color |  |

### getSize() {#getSize--}
```
public final Dimension2D getSize()
```

Haalt de penseelgrootte op of stelt deze in voor een lijn in punten.

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

**Retour:**
java.awt.geom.Dimension2D
### setSize(Dimension2D value) {#setSize-java.awt.geom.Dimension2D-}
```
public final void setSize(Dimension2D value)
```

Haalt de penseelgrootte op of stelt deze in voor een lijn in punten.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.awt.geom.Dimension2D |  |

### getInkEffect() {#getInkEffect--}
```
public final int getInkEffect()
```

Haalt het inkt-effecttype op (bijv. Galaxy, Gold, Silver) dat de visuele stijl van de inktstreep bepaalt. De waarde wordt geparseerd uit de brush-eigenschap "inkEffects". Als er geen herkend effect is gespecificeerd, wordt [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) geretourneerd.

**Retour:**
int