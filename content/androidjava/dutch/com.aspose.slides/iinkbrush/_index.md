---
title: IInkBrush
second_title: Aspose.Slides voor Android via Java API-referentie
description: Vertegenwoordigt een traceerpenseel.
type: docs
url: /nl/com.aspose.slides/iinkbrush/
---```
public interface IInkBrush
```

Vertegenwoordigt een traceerpenseel.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getColor()](#getColor--) | Haalt de penseelkleur op of stelt deze in voor een lijn. |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Haalt de penseelkleur op of stelt deze in voor een lijn. |
| [getSize()](#getSize--) | Haalt de penseelgrootte op of stelt deze in voor een lijn in punten. |
| [setSize(SizeF value)](#setSize-com.aspose.slides.android.SizeF-) | Haalt de penseelgrootte op of stelt deze in voor een lijn in punten. |
| [getInkEffect()](#getInkEffect--) | Haalt het ink-effecttype op (bijv. Galaxy, Gold, Silver) dat de visuele stijl van de inkstreep definieert. |
### getColor() {#getColor--}
```
public abstract Integer getColor()
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

**Retourneert:**
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
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
| value | java.lang.Integer |  |
### getSize() {#getSize--}
```
public abstract SizeF getSize()
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
>      SizeF brushSize = brush.getSize();
>      brush.setSize(new com.aspose.slides.android.Size(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourneert:**
[SizeF](../../com.aspose.slides.android/sizef)
### setSize(SizeF value) {#setSize-com.aspose.slides.android.SizeF-}
```
public abstract void setSize(SizeF value)
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
>      SizeF brushSize = brush.getSize();
>      brush.setSize(new com.aspose.slides.android.Size(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.slides.android/sizef) |  |
### getInkEffect() {#getInkEffect--}
```
public abstract int getInkEffect()
```


Haalt het ink-effecttype op (bijv. Galaxy, Gold, Silver) dat de visuele stijl van de inkstreep definieert. De waarde wordt geparseerd uit de penseel-eigenschap "inkEffects". Als er geen herkend effect is gespecificeerd, wordt [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) geretourneerd.

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

**Retourneert:**
int