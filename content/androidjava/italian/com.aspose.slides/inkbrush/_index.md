---
title: InkBrush
second_title: Aspose.Slides per Android tramite riferimento API Java
description: Rappresenta un oggetto inkBrush.
type: docs
url: /it/com.aspose.slides/inkbrush/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IInkBrush](../../com.aspose.slides/iinkbrush)
```
public class InkBrush implements IInkBrush
```

Rappresenta un oggetto inkBrush.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getColor()](#getColor--) | Ottiene o imposta il colore del pennello per una linea. |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Ottiene o imposta il colore del pennello per una linea. |
| [getSize()](#getSize--) | Ottiene o imposta la dimensione del pennello per una linea in punti. |
| [setSize(SizeF value)](#setSize-com.aspose.slides.android.SizeF-) | Ottiene o imposta la dimensione del pennello per una linea in punti. |
| [getInkEffect()](#getInkEffect--) | Ottiene il tipo di effetto dell'inchiostro (ad esempio, Galaxy, Gold, Silver) che definisce lo stile visivo della traccia di inchiostro. |

### getColor() {#getColor--}
```
public final Integer getColor()
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
public final void setColor(Integer value)
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
public final SizeF getSize()
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
public final void setSize(SizeF value)
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
public final int getInkEffect()
```

Ottiene il tipo di effetto dell'inchiostro (ad esempio, Galaxy, Gold, Silver) che definisce lo stile visivo della traccia di inchiostro. Il valore è analizzato dalla proprietà del pennello "inkEffects". Se non è specificato alcun effetto riconosciuto, [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) viene restituito.

**Restituisce:**
int