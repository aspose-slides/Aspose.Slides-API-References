---
title: InkBrush
second_title: Aspose.Slides pro Android přes referenci Java API
description: Reprezentuje objekt inkBrush.
type: docs
url: /cs/com.aspose.slides/inkbrush/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IInkBrush](../../com.aspose.slides/iinkbrush)
```
public class InkBrush implements IInkBrush
```

Reprezentuje objekt inkBrush.
## Metody

| Metoda | Popis |
| --- | --- |
| [getColor()](#getColor--) | Získá nebo nastaví barvu štětce pro čáru. |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Získá nebo nastaví barvu štětce pro čáru. |
| [getSize()](#getSize--) | Získá nebo nastaví velikost štětce pro čáru v bodech. |
| [setSize(SizeF value)](#setSize-com.aspose.slides.android.SizeF-) | Získá nebo nastaví velikost štětce pro čáru v bodech. |
| [getInkEffect()](#getInkEffect--) | Získá typ ink efektu (např. Galaxy, Gold, Silver), který definuje vizuální styl tahu ink. |

### getColor() {#getColor--}
```
public final Integer getColor()
```

Získá nebo nastaví barvu štětce pro čáru.

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

**Vrací:**
java.lang.Integer

### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public final void setColor(Integer value)
```

Získá nebo nastaví barvu štětce pro čáru.

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getSize() {#getSize--}
```
public final SizeF getSize()
```

Získá nebo nastaví velikost štětce pro čáru v bodech.

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

**Vrací:**
[SizeF](../../com.aspose.slides.android/sizef)

### setSize(SizeF value) {#setSize-com.aspose.slides.android.SizeF-}
```
public final void setSize(SizeF value)
```

Získá nebo nastaví velikost štětce pro čáru v bodech.

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.slides.android/sizef) |  |

### getInkEffect() {#getInkEffect--}
```
public final int getInkEffect()
```

Získá typ ink efektu (např. Galaxy, Gold, Silver), který definuje vizuální styl tahu ink. Hodnota je načtena z vlastnosti štětce "inkEffects". Pokud není zadán žádný rozpoznaný efekt, je vráceno [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined).

**Vrací:**
int