---
title: IInkBrush
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt einen Zeichenpinsel dar.
type: docs
url: /de/com.aspose.slides/iinkbrush/
---```
public interface IInkBrush
```

Stellt einen Zeichenpinsel dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getColor()](#getColor--) | Lädt oder setzt die Pinselfarbe für eine Linie. |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Lädt oder setzt die Pinselfarbe für eine Linie. |
| [getSize()](#getSize--) | Lädt oder setzt die Pinselgröße für eine Linie in Punkten. |
| [setSize(SizeF value)](#setSize-com.aspose.slides.android.SizeF-) | Lädt oder setzt die Pinselgröße für eine Linie in Punkten. |
| [getInkEffect()](#getInkEffect--) | Ruft den Tinteneffekttyp ab (z. B. Galaxy, Gold, Silver), der den visuellen Stil des Tintenstrichs definiert. |

### getColor() {#getColor--}
```
public abstract Integer getColor()
```

Lädt oder setzt die Pinselfarbe für eine Linie.

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
public abstract void setColor(Integer value)
```

Lädt oder setzt die Pinselfarbe für eine Linie.

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
public abstract SizeF getSize()
```

Lädt oder setzt die Pinselgröße für eine Linie in Punkten.

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
public abstract void setSize(SizeF value)
```

Lädt oder setzt die Pinselgröße für eine Linie in Punkten.

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
public abstract int getInkEffect()
```

Ruft den Tinteneffekttyp ab (z. B. Galaxy, Gold, Silver), der den visuellen Stil des Tintenstrichs definiert. Der Wert wird aus der Pinsel-Eigenschaft "inkEffects" geparst. Wenn kein erkannter Effekt angegeben ist, wird [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) zurückgegeben.

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

**Rückgabewert:**
int