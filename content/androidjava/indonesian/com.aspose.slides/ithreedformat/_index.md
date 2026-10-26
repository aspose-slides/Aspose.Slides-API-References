---
title: IThreeDFormat
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili properti 3-D.
type: docs
url: /id/com.aspose.slides/ithreedformat/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormat extends IThreeDParamSource
```

Mewakili properti 3D.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | Mengembalikan atau mengatur lebar kontur 3D. |
| [setContourWidth(double value)](#setContourWidth-double-) | Mengembalikan atau mengatur lebar kontur 3D. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Mengembalikan atau mengatur tinggi efek ekstrusi. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | Mengembalikan atau mengatur tinggi efek ekstrusi. |
| [getDepth()](#getDepth--) | Mengembalikan atau mengatur kedalaman bentuk 3D. |
| [setDepth(double value)](#setDepth-double-) | Mengembalikan atau mengatur kedalaman bentuk 3D. |
| [getBevelTop()](#getBevelTop--) | Mengembalikan atau mengatur tipe bevel atas 3D. |
| [getBevelBottom()](#getBevelBottom--) | Mengembalikan atau mengatur tipe bevel bawah 3D. |
| [getContourColor()](#getContourColor--) | Mengembalikan atau mengatur warna kontur. |
| [getExtrusionColor()](#getExtrusionColor--) | Mengembalikan atau mengatur warna ekstrusi. |
| [getCamera()](#getCamera--) | Mengembalikan atau mengatur pengaturan kamera. |
| [getLightRig()](#getLightRig--) | Mengembalikan atau mengatur tipe cahaya. |
| [getMaterial()](#getMaterial--) | Mengembalikan atau mengatur tipe material. |
| [setMaterial(int value)](#setMaterial-int-) | Mengembalikan atau mengatur tipe material. |
| [getEffective()](#getEffective--) | Mendapatkan data pemformatan 3D yang efektif dengan pewarisan yang diterapkan. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

Mengembalikan atau mengatur lebar kontur 3D. Baca/tulis double.

**Mengembalikan:**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public abstract void setContourWidth(double value)
```

Mengembalikan atau mengatur lebar kontur 3D. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

Mengembalikan atau mengatur tinggi efek ekstrusi. Baca/tulis double.

**Mengembalikan:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public abstract void setExtrusionHeight(double value)
```

Mengembalikan atau mengatur tinggi efek ekstrusi. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

Mengembalikan atau mengatur kedalaman bentuk 3D. Baca/tulis double.

**Mengembalikan:**
double
### setDepth(double value) {#setDepth-double-}
```
public abstract void setDepth(double value)
```

Mengembalikan atau mengatur kedalaman bentuk 3D. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevel getBevelTop()
```

Mengembalikan atau mengatur tipe bevel atas 3D. Baca-saja [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Mengembalikan:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevel getBevelBottom()
```

Mengembalikan atau mengatur tipe bevel bawah 3D. Baca-saja [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Mengembalikan:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public abstract IColorFormat getContourColor()
```

Mengembalikan atau mengatur warna kontur. Baca-saja [IColorFormat](../../com.aspose.slides/icolorformat).

**Mengembalikan:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract IColorFormat getExtrusionColor()
```

Mengembalikan atau mengatur warna ekstrusi. Baca-saja [IColorFormat](../../com.aspose.slides/icolorformat).

**Mengembalikan:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public abstract ICamera getCamera()
```

Mengembalikan atau mengatur pengaturan kamera. Baca-saja [ICamera](../../com.aspose.slides/icamera).

**Mengembalikan:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public abstract ILightRig getLightRig()
```

Mengembalikan atau mengatur tipe cahaya. Baca-saja [ILightRig](../../com.aspose.slides/ilightrig).

**Mengembalikan:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

Mengembalikan atau mengatur tipe material. Baca/tulis [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Mengembalikan:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public abstract void setMaterial(int value)
```

Mengembalikan atau mengatur tipe material. Baca/tulis [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public abstract IThreeDFormatEffectiveData getEffective()
```

Mendapatkan data pemformatan 3D yang efektif dengan pewarisan yang diterapkan.

**Mengembalikan:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - Sebuah [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).