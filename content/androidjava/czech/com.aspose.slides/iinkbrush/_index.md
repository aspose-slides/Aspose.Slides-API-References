---
title: IInkBrush
second_title: Aspose.Slides for Android pomocí referenčního Java API
description: Zastupuje tahový štětec.
type: docs
url: /cs/com.aspose.slides/iinkbrush/
---```
public interface IInkBrush
```

Zastupuje tahový štětec.
## Metody

| Metoda | Popis |
| --- | --- |
| [getColor()](#getColor--) | Získá nebo nastaví barvu štětce pro čáru. |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Získá nebo nastaví barvu štětce pro čáru. |
| [getSize()](#getSize--) | Získá nebo nastaví velikost štětce pro čáru v bodech. |
| [setSize(SizeF value)](#setSize-com.aspose.slides.android.SizeF-) | Získá nebo nastaví velikost štětce pro čáru v bodech. |
| [getInkEffect()](#getInkEffect--) | Získá typ efektu inkoustu (např. Galaxy, Gold, Silver), který definuje vizuální styl tahu štětce. |

### getColor() {#getColor--}
```
public abstract Integer getColor()
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
public abstract void setColor(Integer value)
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
public abstract SizeF getSize()
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
public abstract void setSize(SizeF value)
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
public abstract int getInkEffect()
```


Získá typ efektu inkoustu (např. Galaxy, Gold, Silver), který definuje vizuální styl tahu štětce. Hodnota je načtena z vlastnosti štětce "inkEffects". Pokud není zadán žádný rozpoznaný efekt, [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) je vrácen.

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

**Vrací:**
int