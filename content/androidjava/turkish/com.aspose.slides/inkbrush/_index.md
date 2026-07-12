---
title: InkBrush
second_title: Aspose.Slides Android için Java API Referansı
description: Bir inkBrush nesnesini temsil eder.
type: docs
url: /tr/com.aspose.slides/inkbrush/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IInkBrush](../../com.aspose.slides/iinkbrush)  
```
public class InkBrush implements IInkBrush
```

Bir inkBrush nesnesini temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getColor()](#getColor--) | Bir çizgi için fırça rengini alır veya ayarlar. |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Bir çizgi için fırça rengini alır veya ayarlar. |
| [getSize()](#getSize--) | Bir çizgi için fırça boyutunu puan cinsinden alır veya ayarlar. |
| [setSize(SizeF value)](#setSize-com.aspose.slides.android.SizeF-) | Bir çizgi için fırça boyutunu puan cinsinden alır veya ayarlar. |
| [getInkEffect()](#getInkEffect--) | Kalem darbesinin görsel stilini tanımlayan mürekkep efekt türünü alır (ör. Galaxy, Gold, Silver). |

### getColor() {#getColor--}
```
public final Integer getColor()
```

Bir çizgi için fırça rengini alır veya ayarlar.

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

**Döndürür:**  
java.lang.Integer

### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public final void setColor(Integer value)
```

Bir çizgi için fırça rengini alır veya ayarlar.

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

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getSize() {#getSize--}
```
public final SizeF getSize()
```

Bir çizgi için fırça boyutunu puan cinsinden alır veya ayarlar.

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

**Döndürür:**  
[SizeF](../../com.aspose.slides.android/sizef)

### setSize(SizeF value) {#setSize-com.aspose.slides.android.SizeF-}
```
public final void setSize(SizeF value)
```

Bir çizgi için fırça boyutunu puan cinsinden alır veya ayarlar.

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


**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.slides.android/sizef) |  |

### getInkEffect() {#getInkEffect--}
```
public final int getInkEffect()
```

Kalem darbesinin görsel stilini tanımlayan mürekkep efekt türünü alır (ör. Galaxy, Gold, Silver). Değer, fırça özelliği "inkEffects"den ayrıştırılır. Tanınan bir efekt belirtilmezse, [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) döndürülür.

**Döndürür:**  
int