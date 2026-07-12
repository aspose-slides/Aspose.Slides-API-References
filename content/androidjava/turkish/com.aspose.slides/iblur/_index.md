---
title: IBlur
second_title: Aspose.Slides Android için Java API Referansı aracılığıyla
description: Doldurması da dahil olmak üzere tüm şekle uygulanan bir Bulanıklaştırma etkisini temsil eder.
type: docs
url: /tr/com.aspose.slides/iblur/
---
**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IBlur extends IImageTransformOperation, IAccessiblePVIObject<IBlurEffectiveData>
```

Tüm şekle, doldurması dahil, uygulanan bir Bulanıklaştırma etkisini temsil eder. Alfa dahil tüm renk kanalları etkilenir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getRadius()](#getRadius--) | Bulanıklık yarıçapını döndürür veya ayarlar. |
| [setRadius(double value)](#setRadius-double-) | Bulanıklık yarıçapını döndürür veya ayarlar. |
| [getGrow()](#getGrow--) | Bulanıklaştırma sonucunda nesnenin sınırlarının büyütülüp büyütülmeyeceğini belirler. |
| [setGrow(boolean value)](#setGrow-boolean-) | Bulanıklaştırma sonucunda nesnenin sınırlarının büyütülüp büyütülmeyeceğini belirler. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


Bulanıklık yarıçapını döndürür veya ayarlar. Okunur/yazılır double.

**Dönüş:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```


Bulanıklık yarıçapını döndürür veya ayarlar. Okunur/yazılır double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```


Bulanıklaştırma sonucunda nesnenin sınırlarının büyütülüp büyütülmeyeceğini belirler. True, sınırların büyütüldüğünü gösterirken false, büyütülmediğini gösterir. Okunur/yazılır boolean.

**Dönüş:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public abstract void setGrow(boolean value)
```


Bulanıklaştırma sonucunda nesnenin sınırlarının büyütülüp büyütülmeyeceğini belirler. True, sınırların büyütüldüğünü gösterirken false, büyütülmediğini gösterir. Okunur/yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |