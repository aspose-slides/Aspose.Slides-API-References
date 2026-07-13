---
title: IThreeDFormatEffectiveData
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Objek tak dapat diubah yang mewakili properti pemformatan 3-D yang efektif.
type: docs
url: /id/com.aspose.slides/ithreedformateffectivedata/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormatEffectiveData extends IThreeDParamSource
```

Objek tak dapat diubah yang mewakili properti pemformatan 3-D yang efektif.

--------------------

Antarmuka ini digunakan bersama dengan antarmuka [IThreeDFormat](../../com.aspose.slides/ithreedformat) untuk mengembalikan nilai pemformatan yang efektif dengan penerapan warisan.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | Mengembalikan lebar kontur 3D. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Mengembalikan tinggi efek ekstrusi. |
| [getDepth()](#getDepth--) | Mengembalikan kedalaman bentuk 3D. |
| [getBevelTop()](#getBevelTop--) | Mengembalikan jenis bevel 3D atas. |
| [getBevelBottom()](#getBevelBottom--) | Mengembalikan jenis bevel 3D bawah. |
| [getContourColor()](#getContourColor--) | Mengembalikan warna kontur. |
| [getExtrusionColor()](#getExtrusionColor--) | Mengembalikan warna ekstrusi. |
| [getCamera()](#getCamera--) | Mengembalikan pengaturan kamera. |
| [getLightRig()](#getLightRig--) | Mengembalikan jenis cahaya. |
| [getMaterial()](#getMaterial--) | Mengembalikan jenis material. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```


Mengembalikan lebar kontur 3D. Double hanya-baca.

**Mengembalikan:**
double
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```


Mengembalikan tinggi efek ekstrusi. Double hanya-baca.

**Mengembalikan:**
double
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```


Mengembalikan kedalaman bentuk 3D. Double hanya-baca.

**Mengembalikan:**
double
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevelEffectiveData getBevelTop()
```


Mengembalikan jenis bevel 3D atas. Hanya-baca [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Mengembalikan:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevelEffectiveData getBevelBottom()
```


Mengembalikan jenis bevel 3D bawah. Hanya-baca [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Mengembalikan:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getContourColor() {#getContourColor--}
```
public abstract Integer getContourColor()
```


Mengembalikan warna kontur. java.lang.Integer hanya-baca.

**Mengembalikan:**
java.lang.Integer
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract Integer getExtrusionColor()
```


Mengembalikan warna ekstrusi. java.lang.Integer hanya-baca.

**Mengembalikan:**
java.lang.Integer
### getCamera() {#getCamera--}
```
public abstract ICameraEffectiveData getCamera()
```


Mengembalikan pengaturan kamera. Hanya-baca [ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata).

**Mengembalikan:**
[ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata)
### getLightRig() {#getLightRig--}
```
public abstract ILightRigEffectiveData getLightRig()
```


Mengembalikan jenis cahaya. Hanya-baca [ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata).

**Mengembalikan:**
[ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```


Mengembalikan jenis material. Hanya-baca [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Mengembalikan:**
int