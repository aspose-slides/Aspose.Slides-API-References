---
title: IGlow
second_title: Aspose.Slides untuk Referensi API Java
description: Mewakili efek Glow dimana garis tepi berwarna yang kabur  ditambahkan di luar tepi objek.
type: docs
url: /id/com.aspose.slides/iglow/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IGlow extends IImageTransformOperation, IAccessiblePVIObject<IGlowEffectiveData>
```

Mewakili efek Glow, dimana sebuah garis tepi berwarna yang kabur ditambahkan di luar tepi objek.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getRadius()](#getRadius--) | Radius. |
| [setRadius(double value)](#setRadius-double-) | Radius. |
| [getColor()](#getColor--) | Format warna. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


Radius. Baca/tulis double.

**Mengembalikan:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```


Radius. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```


Format warna. Hanya-baca [IColorFormat](../../com.aspose.slides/icolorformat).

**Mengembalikan:**
[IColorFormat](../../com.aspose.slides/icolorformat)