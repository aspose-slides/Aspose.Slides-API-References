---
title: InkBrush
second_title: Aspose.Slides dla Androida poprzez odwołanie API Java
description: Reprezentuje obiekt inkBrush.
type: docs
url: /pl/com.aspose.slides/inkbrush/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IInkBrush](../../com.aspose.slides/iinkbrush)
```
public class InkBrush implements IInkBrush
```

Reprezentuje obiekt inkBrush.

## Metody

| Metoda | Opis |
| --- | --- |
| [getColor()](#getColor--) | Pobiera lub ustawia kolor pędzla dla linii. |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Pobiera lub ustawia kolor pędzla dla linii. |
| [getSize()](#getSize--) | Pobiera lub ustawia rozmiar pędzla dla linii w punktach. |
| [setSize(SizeF value)](#setSize-com.aspose.slides.android.SizeF-) | Pobiera lub ustawia rozmiar pędzla dla linii w punktach. |
| [getInkEffect()](#getInkEffect--) | Pobiera typ efektu atramentu (np. Galaxy, Gold, Silver), który definiuje styl wizualny pociągnięcia atramentu. |

### getColor() {#getColor--}
```
public final Integer getColor()
```

Pobiera lub ustawia kolor pędzla dla linii.

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


**Zwraca:**
java.lang.Integer

### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public final void setColor(Integer value)
```

Pobiera lub ustawia kolor pędzla dla linii.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getSize() {#getSize--}
```
public final SizeF getSize()
```

Pobiera lub ustawia rozmiar pędzla dla linii w punktach.

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


**Zwraca:**
[SizeF](../../com.aspose.slides.android/sizef)

### setSize(SizeF value) {#setSize-com.aspose.slides.android.SizeF-}
```
public final void setSize(SizeF value)
```

Pobiera lub ustawia rozmiar pędzla dla linii w punktach.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.slides.android/sizef) |  |

### getInkEffect() {#getInkEffect--}
```
public final int getInkEffect()
```

Pobiera typ efektu atramentu (np. Galaxy, Gold, Silver), który definiuje styl wizualny pociągnięcia atramentu. Wartość jest parsowana z właściwości pędzla "inkEffects". Jeśli nie określono rozpoznanego efektu, zwracany jest [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined).

**Zwraca:**
int