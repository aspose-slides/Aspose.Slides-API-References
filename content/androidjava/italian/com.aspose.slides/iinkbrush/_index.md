---
title: IInkBrush
second_title: Aspose.Slides for Android via Java API Reference
description: Rappresenta il pennello di tracciatura.
type: docs
url: /it/com.aspose.slides/iinkbrush/
---```
public interface IInkBrush
```

Rappresenta il pennello di tracciatura.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getColor()](#getColor--) | Ottiene o imposta il colore del pennello per una linea. |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Ottiene o imposta il colore del pennello per una linea. |
| [getSize()](#getSize--) | Ottiene o imposta la dimensione del pennello per una linea in punti. |
| [setSize(SizeF value)](#setSize-com.aspose.slides.android.SizeF-) | Ottiene o imposta la dimensione del pennello per una linea in punti. |
| [getInkEffect()](#getInkEffect--) | Ottiene il tipo di effetto inchiostro (ad es., Galaxy, Gold, Silver) che definisce lo stile visuale della traccia di inchiostro. |
### getColor() {#getColor--}
```
public abstract Integer getColor()
```

Ottiene o imposta il colore del pennello per una linea.

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

**Restituisce:**
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
```

Ottiene o imposta il colore del pennello per una linea.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.Integer |  |
### getSize() {#getSize--}
```
public abstract SizeF getSize()
```

Ottiene o imposta la dimensione del pennello per una linea in punti.

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

**Restituisce:**
[SizeF](../../com.aspose.slides.android/sizef)
### setSize(SizeF value) {#setSize-com.aspose.slides.android.SizeF-}
```
public abstract void setSize(SizeF value)
```

Ottiene o imposta la dimensione del pennello per una linea in punti.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.slides.android/sizef) |  |
### getInkEffect() {#getInkEffect--}
```
public abstract int getInkEffect()
```

Ottiene il tipo di effetto inchiostro (ad es., Galaxy, Gold, Silver) che definisce lo stile visuale della traccia di inchiostro. Il valore è analizzato dalla proprietà del pennello "inkEffects". Se non è specificato alcun effetto riconosciuto, [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) è restituito.

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

**Restituisce:**
int