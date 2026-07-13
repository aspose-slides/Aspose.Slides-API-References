---
title: IAdjustValue
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a geometry shapes adjustment value.
type: docs
url: /id/com.aspose.slides/iadjustvalue/
---```
public interface IAdjustValue
```

Mewakili nilai penyesuaian bentuk geometris. Nilai-nilai ini memengaruhi bentuk shape.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getRawValue()](#getRawValue--) | Mengembalikan atau mengatur nilai penyesuaian "as is". |
| [setRawValue(long value)](#setRawValue-long-) | Mengembalikan atau mengatur nilai penyesuaian "as is". |
| [getAngleValue()](#getAngleValue--) | Mengembalikan atau mengatur nilai, menginterpretasikannya sebagai sudut dalam derajat. |
| [setAngleValue(float value)](#setAngleValue-float-) | Mengembalikan atau mengatur nilai, menginterpretasikannya sebagai sudut dalam derajat. |
| [getName()](#getName--) | Mengembalikan nama nilai penyesuaian ini. |
| [getType()](#getType--) | Mengembalikan tipe penyesuaian shape. |
### getRawValue() {#getRawValue--}
```
public abstract long getRawValue()
```


Mengembalikan atau mengatur nilai penyesuaian "as is". Baca/tulis long.

**Mengembalikan:**
long
### setRawValue(long value) {#setRawValue-long-}
```
public abstract void setRawValue(long value)
```


Mengembalikan atau mengatur nilai penyesuaian "as is". Baca/tulis long.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | long |  |

### getAngleValue() {#getAngleValue--}
```
public abstract float getAngleValue()
```


Mengembalikan atau mengatur nilai, menginterpretasikannya sebagai sudut dalam derajat. Baca/tulis float.

**Mengembalikan:**
float
### setAngleValue(float value) {#setAngleValue-float-}
```
public abstract void setAngleValue(float value)
```


Mengembalikan atau mengatur nilai, menginterpretasikannya sebagai sudut dalam derajat. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getName() {#getName--}
```
public abstract String getName()
```


Mengembalikan nama nilai penyesuaian ini. Hanya-baca String.

**Mengembalikan:**
java.lang.String
### getType() {#getType--}
```
public abstract int getType()
```


Mengembalikan tipe penyesuaian shape. Hanya-baca [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype).

**Mengembalikan:**
int