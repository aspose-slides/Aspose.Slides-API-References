---
title: IInkBrush
second_title: Aspose.Slides dla Androida za pośrednictwem referencji API Java
description: Reprezentuje pędzel śladu.
type: docs
url: /pl/com.aspose.slides/iinkbrush/
---```
public interface IInkBrush
```

Reprezentuje pędzel śladu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getColor()](#getColor--) | Pobiera lub ustawia kolor pędzla dla linii. |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Pobiera lub ustawia kolor pędzla dla linii. |
| [getSize()](#getSize--) | Pobiera lub ustawia rozmiar pędzla dla linii w punktach. |
| [setSize(SizeF value)](#setSize-com.aspose.slides.android.SizeF-) | Pobiera lub ustawia rozmiar pędzla dla linii w punktach. |
| [getInkEffect()](#getInkEffect--) | Pobiera typ efektu atramentu (np. Galaxy, Gold, Silver), który definiuje wizualny styl pociągnięcia atramentu. |
### getColor() {#getColor--}
```
public abstract Integer getColor()
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
public abstract void setColor(Integer value)
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
public abstract SizeF getSize()
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
public abstract void setSize(SizeF value)
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
public abstract int getInkEffect()
```


Pobiera typ efektu atramentu (np. Galaxy, Gold, Silver), który definiuje wizualny styl pociągnięcia atramentu. Wartość jest parsowana z właściwości pędzla "inkEffects". Jeśli nie określono rozpoznanego efektu, [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) jest zwracane.

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

**Zwraca:**
int