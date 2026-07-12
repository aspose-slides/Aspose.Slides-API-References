---
title: IInkBrush
second_title: Aspose.Slides for Android için Java API Referansı
description: İz fırçasını temsil eder.
type: docs
url: /tr/com.aspose.slides/iinkbrush/
---```
public interface IInkBrush
```

İz fırçasını temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getColor()](#getColor--) | Bir satır için fırça rengini alır veya ayarlar. |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Bir satır için fırça rengini alır veya ayarlar. |
| [getSize()](#getSize--) | Bir satır için fırça boyutunu puantaj cinsinden alır veya ayarlar. |
| [setSize(SizeF value)](#setSize-com.aspose.slides.android.SizeF-) | Bir satır için fırça boyutunu puantaj cinsinden alır veya ayarlar. |
| [getInkEffect()](#getInkEffect--) | İnket etkisi tipini (örn. Galaxy, Gold, Silver) alır; bu, ink stroke'un görsel stilini tanımlar. |

### getColor() {#getColor--}
```
public abstract Integer getColor()
```

Bir satır için fırça rengini alır veya ayarlar.

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
public abstract void setColor(Integer value)
```

Bir satır için fırça rengini alır veya ayarlar.

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
public abstract SizeF getSize()
```

Bir satır için fırça boyutunu puantaj cinsinden alır veya ayarlar.

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
public abstract void setSize(SizeF value)
```

Bir satır için fırça boyutunu puantaj cinsinden alır veya ayarlar.

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
public abstract int getInkEffect()
```

İnket etkisi tipini (örn. Galaxy, Gold, Silver) alır; bu, ink stroke'un görsel stilini tanımlar. Değer, fırça özelliği \"inkEffects\"'den ayrıştırılır. Tanınan bir etki belirtilmemişse, [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) döndürülür.

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

**Döndürür:**
int