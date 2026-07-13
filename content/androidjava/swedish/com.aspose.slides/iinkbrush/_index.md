---
title: IInkBrush
second_title: Aspose.Slides för Android via Java API-referens
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
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Hämtar eller anger penselfärgen för en linje. |
| [getSize()](#getSize--) | Hämtar eller anger penselstorleken för en linje i punkter. |
| [setSize(SizeF value)](#setSize-com.aspose.slides.android.SizeF-) | Hämtar eller anger penselstorleken för en linje i punkter. |
| [getInkEffect()](#getInkEffect--) | Hämtar bläckeffekttypen (t.ex. Galaxy, Gold, Silver) som definierar den visuella stilen för bläckstrecket. |

### getColor() {#getColor--}
```
public abstract Integer getColor()
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

**Returns:**
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
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
| value | java.lang.Integer |  |

### getSize() {#getSize--}
```
public abstract SizeF getSize()
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
>      SizeF brushSize = brush.getSize();
>      brush.setSize(new com.aspose.slides.android.Size(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[SizeF](../../com.aspose.slides.android/sizef)
### setSize(SizeF value) {#setSize-com.aspose.slides.android.SizeF-}
```
public abstract void setSize(SizeF value)
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
public abstract int getInkEffect()
```


Hämtar bläckeffekttypen (t.ex. Galaxy, Gold, Silver) som definierar den visuella stilen för bläckstrecket. Värdet hämtas från penselns egenskap "inkEffects". Om ingen erkänd effekt anges, returneras [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined).

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

**Returns:**
int