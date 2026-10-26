---
title: IInkBrush
second_title: Aspose.Slides Androidhoz Java API-referencia
description: A nyomvonal ecsetet ábrázolja.
type: docs
url: /hu/com.aspose.slides/iinkbrush/
---```
public interface IInkBrush
```

Ábrázolja a nyomvonal ecsetet.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getColor()](#getColor--) | Lekérdezi vagy beállítja a vonal ecsetszínét. |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Lekérdezi vagy beállítja a vonal ecsetszínét. |
| [getSize()](#getSize--) | Lekérdezi vagy beállítja a vonal ecsetméretét pontokban. |
| [setSize(SizeF value)](#setSize-com.aspose.slides.android.SizeF-) | Lekérdezi vagy beállítja a vonal ecsetméretét pontokban. |
| [getInkEffect()](#getInkEffect--) | Lekérdezi a tintaeffektus típusát (pl. Galaxy, Gold, Silver), amely meghatározza a tintavonal vizuális stílusát. |
### getColor() {#getColor--}
```
public abstract Integer getColor()
```


Lekérdezi vagy beállítja a vonal ecsetszínét.

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

**Visszatér:**  
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
```


Lekérdezi vagy beállítja a vonal ecsetszínét.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.Integer |  |
### getSize() {#getSize--}
```
public abstract SizeF getSize()
```


Lekérdezi vagy beállítja a vonal ecsetméretét pontokban.

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

**Visszatér:**  
[SizeF](../../com.aspose.slides.android/sizef)
### setSize(SizeF value) {#setSize-com.aspose.slides.android.SizeF-}
```
public abstract void setSize(SizeF value)
```


Lekérdezi vagy beállítja a vonal ecsetméretét pontokban.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.slides.android/sizef) |  |
### getInkEffect() {#getInkEffect--}
```
public abstract int getInkEffect()
```


Lekérdezi a tintaeffektus típusát (pl. Galaxy, Gold, Silver), amely meghatározza a tintavonal vizuális stílusát. Ha nincs felismert effektus megadva, akkor [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) kerül visszaadásra.

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

**Visszatér:**  
int