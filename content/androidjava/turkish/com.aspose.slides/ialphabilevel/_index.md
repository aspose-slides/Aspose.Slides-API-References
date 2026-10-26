---
title: IAlphaBiLevel
second_title: Aspose.Slides for Android, Java API Referansı aracılığıyla
description: Alpha Bi-Level efektini temsil eder.
type: docs
url: /tr/com.aspose.slides/ialphabilevel/
---
**Tüm Gerçekleştirilen Arabirimler:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IAlphaBiLevel extends IImageTransformOperation, IAccessiblePVIObject<IAlphaBiLevelEffectiveData>
```

Alpha Bi-Level efektini temsil eder. Eşik değerinden düşük Alpha (Opacity) değerleri 0 (tamamen şeffaf) olarak değiştirilir ve eşik değerine eşit veya daha büyük alpha değerleri %100 (tamamen opak) olarak değiştirilir.

--------------------

COM içinde örnekler oluşturmak için ImageTransformOperationFactory'yi kullanın.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getThreshold()](#getThreshold--) | Etki eşik değerini döndürür. |
| [setThreshold(float value)](#setThreshold-float-) | Etki eşik değerini döndürür. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```


Etki eşik değerini döndürür. Okunur/yazılır float.

**Döndürür:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public abstract void setThreshold(float value)
```


Etki eşik değerini döndürür. Okunur/yazılır float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |