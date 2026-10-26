---
title: InkBrush
second_title: Aspose.Slides för Android via Java API-referens
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
| [getColor()](#getColor--) | Hämtar eller sätter penselfärgen för en linje. |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Hämtar eller sätter penselfärgen för en linje. |
| [getSize()](#getSize--) | Hämtar eller sätter penselstorleken för en linje i punkter. |
| [setSize(SizeF value)](#setSize-com.aspose.slides.android.SizeF-) | Hämtar eller sätter penselstorleken för en linje i punkter. |
| [getInkEffect()](#getInkEffect--) | Hämtar bläckeffekttypen (t.ex. Galaxy, Gold, Silver) som definierar den visuella stilen för bläckstrecket. |
### getColor() {#getColor--}
```
public final Integer getColor()
```


Hämtar eller sätter penselfärgen för en linje.

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
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public final void setColor(Integer value)
```


Hämtar eller sätter penselfärgen för en linje.

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
| value | java.lang.Integer |  |

### getSize() {#getSize--}
```
public final SizeF getSize()
```


Hämtar eller sätter penselstorleken för en linje i punkter.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      SizeF brushSize = brush.getSize();
>      brush.setSize(new com.aspose.slides.android.Size(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returnerar:**
[SizeF](../../com.aspose.slides.android/sizef)
### setSize(SizeF value) {#setSize-com.aspose.slides.android.SizeF-}
```
public final void setSize(SizeF value)
```


Hämtar eller sätter penselstorleken för en linje i punkter.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      SizeF brushSize = brush.getSize();
>      brush.setSize(new com.aspose.slides.android.Size(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.slides.android/sizef) |  |

### getInkEffect() {#getInkEffect--}
```
public final int getInkEffect()
```


Hämtar bläckeffekttypen (t.ex. Galaxy, Gold, Silver) som definierar den visuella stilen för bläckstrecket. Värdet hämtas från penselns egenskap "inkEffects". Om ingen igenkänd effekt anges, returneras [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined).

**Returnerar:**
int