---
title: IAlphaBiLevel
second_title: Aspose.Slides for Java API Referansı
description: Alpha Bi-Level etkisini temsil eder.
type: docs
url: /tr/com.aspose.slides/ialphabilevel/
---
**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IAlphaBiLevel extends IImageTransformOperation, IAccessiblePVIObject<IAlphaBiLevelEffectiveData>
```

Alpha Bi-Level etkisini temsil eder. Eşik değerinden küçük Alpha (Opacity) değerleri 0 (tamamen şeffaf) olarak, eşik değerine eşit veya büyük alpha değerleri ise %100 (tamamen opak) olarak değiştirilir.

--------------------

ImageTransformOperationFactory kullanarak COM içinde örnekler oluşturun.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getThreshold()](#getThreshold--) | Eşik değerini döndürür. |
| [setThreshold(float value)](#setThreshold-float-) | Eşik değerini döndürür. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```


Eşik değerini döndürür. Okuma/yazma float.

**Döndürür:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public abstract void setThreshold(float value)
```


Eşik değerini döndürür. Okuma/yazma float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |