---
title: IFillOverlay
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili efek Fill Overlay.
type: docs
url: /id/com.aspose.slides/ifilloverlay/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IFillOverlay extends IImageTransformOperation, IAccessiblePVIObject<IFillOverlayEffectiveData>
```

Mewakili efek Fill Overlay. Fill overlay dapat digunakan untuk menentukan isian tambahan untuk sebuah objek dan mencampur kedua isian tersebut.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getFillFormat()](#getFillFormat--) | Format isian. |
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


Format isian. Baca-saja [IFillFormat](../../com.aspose.slides/ifillformat).

**Mengembalikan:**
[IFillFormat](../../com.aspose.slides/ifillformat)