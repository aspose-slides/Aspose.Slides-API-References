---
title: InkBrush
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt ein inkBrush-Objekt dar.
type: docs
url: /de/com.aspose.slides/inkbrush/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IInkBrush](../../com.aspose.slides/iinkbrush)
```
public class InkBrush implements IInkBrush
```

Stellt ein inkBrush-Objekt dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getColor()](#getColor--) | Liest oder setzt die Pinselfarbe für eine Linie. |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Liest oder setzt die Pinselfarbe für eine Linie. |
| [getSize()](#getSize--) | Liest oder setzt die Pinselgröße für eine Linie in Punkten. |
| [setSize(SizeF value)](#setSize-com.aspose.slides.android.SizeF-) | Liest oder setzt die Pinselgröße für eine Linie in Punkten. |
| [getInkEffect()](#getInkEffect--) | Liest den Tinteneffekttyp (z. B. Galaxy, Gold, Silver), der den visuellen Stil des Tintestrichs definiert. |
### getColor() {#getColor--}
```
public final Integer getColor()
```


Liest oder setzt die Pinselfarbe für eine Linie.

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

**Rückgabewert:**
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public final void setColor(Integer value)
```


Liest oder setzt die Pinselfarbe für eine Linie.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.Integer |  |
### getSize() {#getSize--}
```
public final SizeF getSize()
```


Liest oder setzt die Pinselgröße für eine Linie in Punkten.

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

**Rückgabewert:**
[SizeF](../../com.aspose.slides.android/sizef)
### setSize(SizeF value) {#setSize-com.aspose.slides.android.SizeF-}
```
public final void setSize(SizeF value)
```


Liest oder setzt die Pinselgröße für eine Linie in Punkten.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.slides.android/sizef) |  |
### getInkEffect() {#getInkEffect--}
```
public final int getInkEffect()
```


Liest den Tinteneffekttyp (z. B. Galaxy, Gold, Silver), der den visuellen Stil des Tintestrichs definiert. Der Wert wird aus der Pinsel-Eigenschaft „inkEffects“ geparst. Wenn kein erkannter Effekt angegeben ist, wird [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) zurückgegeben.

**Rückgabewert:**
int