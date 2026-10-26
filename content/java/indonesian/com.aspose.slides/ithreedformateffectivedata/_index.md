---
title: IThreeDFormatEffectiveData
second_title: Aspose.Slides untuk Referensi API Java
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

Antarmuka ini digunakan bersama dengan antarmuka [IThreeDFormat](../../com.aspose.slides/ithreedformat) untuk mengembalikan nilai pemformatan yang efektif dengan pewarisan diterapkan.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | Mengembalikan lebar kontur 3D. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Mengembalikan tinggi efek ekstrusi. |
| [getDepth()](#getDepth--) | Mengembalikan kedalaman bentuk 3D. |
| [getBevelTop()](#getBevelTop--) | Mengembalikan tipe bevel 3D atas. |
| [getBevelBottom()](#getBevelBottom--) | Mengembalikan tipe bevel 3D bawah. |
| [getContourColor()](#getContourColor--) | Mengembalikan warna kontur. |
| [getExtrusionColor()](#getExtrusionColor--) | Mengembalikan warna ekstrusi. |
| [getCamera()](#getCamera--) | Mengembalikan pengaturan kamera. |
| [getLightRig()](#getLightRig--) | Mengembalikan tipe cahaya. |
| [getMaterial()](#getMaterial--) | Mengembalikan tipe material. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

Mengembalikan lebar kontur 3D. Baca-saja double.

**Mengembalikan:**
double
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

Mengembalikan tinggi efek ekstrusi. Baca-saja double.

**Mengembalikan:**
double
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

Mengembalikan kedalaman bentuk 3D. Baca-saja double.

**Mengembalikan:**
double
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevelEffectiveData getBevelTop()
```

Mengembalikan tipe bevel 3D atas. Baca-saja [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Mengembalikan:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevelEffectiveData getBevelBottom()
```

Mengembalikan tipe bevel 3D bawah. Baca-saja [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Mengembalikan:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getContourColor() {#getContourColor--}
```
public abstract Color getContourColor()
```

Mengembalikan warna kontur. Baca-saja java.awt.Color.

**Mengembalikan:**
java.awt.Color
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract Color getExtrusionColor()
```

Mengembalikan warna ekstrusi. Baca-saja java.awt.Color.

**Mengembalikan:**
java.awt.Color
### getCamera() {#getCamera--}
```
public abstract ICameraEffectiveData getCamera()
```

Mengembalikan pengaturan kamera. Baca-saja [ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata).

**Mengembalikan:**
[ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata)
### getLightRig() {#getLightRig--}
```
public abstract ILightRigEffectiveData getLightRig()
```

Mengembalikan tipe cahaya. Baca-saja [ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata).

**Mengembalikan:**
[ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

Mengembalikan tipe material. Baca-saja [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Mengembalikan:**
int