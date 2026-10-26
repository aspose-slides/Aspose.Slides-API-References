---
title: IBlur
second_title: Aspose.Slides for Java API Referansı
description: Tam şekle, dolgu dahil, uygulanan bir Bulanıklaştırma etkisini temsil eder.
type: docs
url: /tr/com.aspose.slides/iblur/
---
**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IBlur extends IImageTransformOperation, IAccessiblePVIObject<IBlurEffectiveData>
```

Tam şekle, dolgu dahil, uygulanan bir Bulanıklaştırma etkisini temsil eder. Alfa dahil tüm renk kanalları etkilenir.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getRadius()](#getRadius--) | Bulanık yarıçapını döndürür veya ayarlar. |
| [setRadius(double value)](#setRadius-double-) | Bulanık yarıçapını döndürür veya ayarlar. |
| [getGrow()](#getGrow--) | Nesnenin sınırlarının bulanıklaştırma sonucu büyütülüp büyütülmeyeceğini belirler. |
| [setGrow(boolean value)](#setGrow-boolean-) | Nesnenin sınırlarının bulanıklaştırma sonucu büyütülüp büyütülmeyeceğini belirler. |

### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

Bulanık yarıçapını döndürür veya ayarlar. Okunabilir/Yazılabilir double.

**Döndürür:**
double

### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```

Bulanık yarıçapını döndürür veya ayarlar. Okunabilir/Yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

Nesnenin sınırlarının bulanıklaştırma sonucu büyütülüp büyütülmeyeceğini belirler. True, sınırların büyütüldüğünü, false ise büyütülmediğini gösterir. Okunabilir/Yazılabilir boolean.

**Döndürür:**
boolean

### setGrow(boolean value) {#setGrow-boolean-}
```
public abstract void setGrow(boolean value)
```

Nesnenin sınırlarının bulanıklaştırma sonucu büyütülüp büyütülmeyeceğini belirler. True, sınırların büyütüldüğünü, false ise büyütülmediğini gösterir. Okunabilir/Yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |