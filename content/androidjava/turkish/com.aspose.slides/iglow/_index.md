---
title: IGlow
second_title: Aspose.Slides for Android üzerinden Java API Referansı
description: Bir nesnenin kenarlarının dışına renkli bulanık bir dış hat eklenen Glow etkisini temsil eder.
type: docs
url: /tr/com.aspose.slides/iglow/
---
**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IGlow extends IImageTransformOperation, IAccessiblePVIObject<IGlowEffectiveData>
```

Bir nesnenin kenarlarının dışına renkli bulanık bir dış hat eklenen Glow etkisini temsil eder.
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


Yarıçap. Okuma/yazma double.

**Döndürür:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```


Yarıçap. Okuma/yazma double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```


Renk biçimi. Yalnızca okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)