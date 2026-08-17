---
title: IGlow
second_title: Aspose.Slides için Java API Referansı
description: Renkli bulanık bir anahat nesnenin kenarlarının dışına eklendiği bir Glow etkisini temsil eder.
type: docs
url: /tr/com.aspose.slides/iglow/
---
**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IGlow extends IImageTransformOperation, IAccessiblePVIObject<IGlowEffectiveData>
```

Glow etkisini temsil eder; bu etki, nesnenin kenarlarının dışına eklenen renkli bulanık bir anahat içerir.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getRadius()](#getRadius--) | Yarıçap. |
| [setRadius(double value)](#setRadius-double-) | Yarıçap. |
| [getColor()](#getColor--) | Renk biçimi. |

### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

Yarıçap. Okunur/Yazılır double.

**Döndürür:**
double

### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```

Yarıçap. Okunur/Yazılır double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

Renk biçimi. Sadece okuma [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)