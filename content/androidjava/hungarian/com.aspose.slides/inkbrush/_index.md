---
title: InkBrush
second_title: Aspose.Slides for Android a Java API hivatkozás segítségével
description: Az inkBrush objektumot reprezentálja.
type: docs
url: /hu/com.aspose.slides/inkbrush/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IInkBrush](../../com.aspose.slides/iinkbrush)
```
public class InkBrush implements IInkBrush
```

Az inkBrush objektumot reprezentálja.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getColor()](#getColor--) | Lekéri vagy beállítja a vonal ecsetszínét. |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Lekéri vagy beállítja a vonal ecsetszínét. |
| [getSize()](#getSize--) | Lekéri vagy beállítja a vonal méretét pontban. |
| [setSize(SizeF value)](#setSize-com.aspose.slides.android.SizeF-) | Lekéri vagy beállítja a vonal méretét pontban. |
| [getInkEffect()](#getInkEffect--) | Lekéri a tinta effektus típusát (pl. Galaxy, Gold, Silver), amely meghatározza a tinta vonal vizuális stílusát. |
### getColor() {#getColor--}
```
public final Integer getColor()
```


Lekéri vagy beállítja a vonal ecsetszínét.

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

**Visszatérési érték:**
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public final void setColor(Integer value)
```


Lekéri vagy beállítja a vonal ecsetszínét.

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
public final SizeF getSize()
```


Lekéri vagy beállítja a vonal méretét pontban.

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

**Visszatérési érték:**
[SizeF](../../com.aspose.slides.android/sizef)
### setSize(SizeF value) {#setSize-com.aspose.slides.android.SizeF-}
```
public final void setSize(SizeF value)
```


Lekéri vagy beállítja a vonal méretét pontban.

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
public final int getInkEffect()
```


Lekéri a tinta effektus típusát (pl. Galaxy, Gold, Silver), amely meghatározza a tinta vonal vizuális stílusát. Az érték a brush tulajdonság "inkEffects"-ből kerül kiolvasásra. Ha nincs felismerhető effektus megadva, akkor [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) kerül visszaadásra.

**Visszatérési érték:**
int