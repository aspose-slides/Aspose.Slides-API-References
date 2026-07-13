---
title: InkBrush
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een inkBrush-object voor.
type: docs
url: /nl/com.aspose.slides/inkbrush/
---
**Overerving:**
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
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Haalt de penseelkleur op of stelt deze in voor een lijn. |
| [getSize()](#getSize--) | Haalt de penseelgrootte op of stelt deze in voor een lijn in punten. |
| [setSize(SizeF value)](#setSize-com.aspose.slides.android.SizeF-) | Haalt de penseelgrootte op of stelt deze in voor een lijn in punten. |
| [getInkEffect()](#getInkEffect--) | Haalt het type inkteffect op (bijv., Galaxy, Gold, Silver) dat de visuele stijl van de inktstreep definieert. |
### getColor() {#getColor--}
```
public final Integer getColor()
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
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public final void setColor(Integer value)
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
public final SizeF getSize()
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

**Retour:**
[SizeF](../../com.aspose.slides.android/sizef)
### setSize(SizeF value) {#setSize-com.aspose.slides.android.SizeF-}
```
public final void setSize(SizeF value)
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
public final int getInkEffect()
```


Haalt het type inkteffect op (bijv., Galaxy, Gold, Silver) dat de visuele stijl van de inktstreep definieert. De waarde wordt geparseerd uit de penseel-eigenschap "inkEffects". Als geen herkend effect is opgegeven, wordt [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) geretourneerd.

**Retour:**
int