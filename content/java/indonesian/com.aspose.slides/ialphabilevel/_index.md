---
title: IAlphaBiLevel
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili efek Alpha Bi-Level.
type: docs
url: /id/com.aspose.slides/ialphabilevel/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IAlphaBiLevel extends IImageTransformOperation, IAccessiblePVIObject<IAlphaBiLevelEffectiveData>
```

Mewakili efek Alpha Bi-Level. Nilai Alpha (Opacity) yang kurang dari ambang batas diubah menjadi 0 (sepenuhnya transparan) dan nilai Alpha yang lebih besar atau sama dengan ambang batas diubah menjadi 100% (sepenuhnya tidak tembus pandang).

--------------------

Gunakan ImageTransformOperationFactory untuk membuat instance dalam COM.
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