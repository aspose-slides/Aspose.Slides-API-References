---
title: IFillOverlay
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili efek Fill Overlay.
type: docs
url: /id/com.aspose.slides/ifilloverlay/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IFillOverlay extends IImageTransformOperation, IAccessiblePVIObject<IFillOverlayEffectiveData>
```

Mewakili efek Fill Overlay. Fill overlay dapat digunakan untuk menentukan isi tambahan bagi sebuah objek dan memadukan kedua isi tersebut.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getFillFormat()](#getFillFormat--) | Fill format. |
### getBlend() {#getBlend--}
```
public abstract int getBlend()
```


FillBlendMode. Baca/tulis [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Mengembalikan:**
int
### setBlend(int value) {#setBlend-int-}
```
public abstract void setBlend(int value)
```


FillBlendMode. Baca/tulis [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Fill format. Baca-saja [IFillFormat](../../com.aspose.slides/ifillformat).

**Mengembalikan:**
[IFillFormat](../../com.aspose.slides/ifillformat)