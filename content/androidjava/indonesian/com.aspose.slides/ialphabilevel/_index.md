---
title: IAlphaBiLevel
second_title: Aspose.Slides untuk Android lewat Referensi API Java
description: Mewakili efek Alpha Bi-Level.
type: docs
url: /id/com.aspose.slides/ialphabilevel/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IAlphaBiLevel extends IImageTransformOperation, IAccessiblePVIObject<IAlphaBiLevelEffectiveData>
```

Mewakili efek Alpha Bi-Level. Nilai Alpha (Opacity) yang kurang dari ambang diubah menjadi 0 (sepenuhnya transparan) dan nilai alpha yang lebih besar atau sama dengan ambang diubah menjadi 100 % (sepenuhnya opak).

--------------------

Gunakan ImageTransformOperationFactory untuk membuat instaces di COM.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getThreshold()](#getThreshold--) | Mengembalikan ambang efek. |
| [setThreshold(float value)](#setThreshold-float-) | Mengembalikan ambang efek. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

Mengembalikan ambang efek. Baca/tulis float.

**Mengembalikan:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public abstract void setThreshold(float value)
```

Mengembalikan ambang efek. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |