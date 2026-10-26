---
title: Background
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili latar belakang slide.
type: docs
url: /id/com.aspose.slides/background/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IBackground](../../com.aspose.slides/ibackground), com.aspose.slides.IDOMObject
```
public final class Background extends PVIObject implements IBackground, IDOMObject
```

Mewakili latar belakang slide.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getType()](#getType--) | Mengembalikan jenis isi latar belakang. |
| [setType(byte value)](#setType-byte-) | Mengembalikan jenis isi latar belakang. |
| [getFillFormat()](#getFillFormat--) | Mengembalikan FillFormat untuk isi BackgroundType.OwnBackground. |
| [getEffectFormat()](#getEffectFormat--) | Mengembalikan EffectFormat untuk isi BackgroundType.OwnBackground. |
| [getStyleColor()](#getStyleColor--) | Mengembalikan ColorFormat untuk isi BackgroundType.Themed. |
| [getStyleIndex()](#getStyleIndex--) | Mengembalikan indeks dari isi BackgroundType.Themed dalam koleksi tema latar belakang. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | Mengembalikan indeks dari isi BackgroundType.Themed dalam koleksi tema latar belakang. |
| [getEffective()](#getEffective--) | Mendapatkan data latar belakang yang efektif dengan pewarisan yang diterapkan. |
| [getVersion()](#getVersion--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Mengembalikan slide induk dari sebuah bentuk. |
| [getPresentation()](#getPresentation--) | Mengembalikan presentasi induk dari sebuah slide. |
### getType() {#getType--}
```
public final byte getType()
```

Mengembalikan jenis isi latar belakang. Baca/tulis [BackgroundType](../../com.aspose.slides/backgroundtype).

**Mengembalikan:**
byte
### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```

Mengembalikan jenis isi latar belakang. Baca/tulis [BackgroundType](../../com.aspose.slides/backgroundtype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Mengembalikan FillFormat untuk isi BackgroundType.OwnBackground. Hanya-baca [IFillFormat](../../com.aspose.slides/ifillformat).

**Mengembalikan:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

Mengembalikan EffectFormat untuk isi BackgroundType.OwnBackground. Hanya-baca [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Mengembalikan:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public final IColorFormat getStyleColor()
```

Mengembalikan ColorFormat untuk isi BackgroundType.Themed. Hanya-baca [IColorFormat](../../com.aspose.slides/icolorformat).

**Mengembalikan:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public final int getStyleIndex()
```

Mengembalikan indeks dari isi BackgroundType.Themed dalam koleksi tema latar belakang. 0 berarti tidak ada isian. 1..999 - indeks. Baca/tulis int.

**Mengembalikan:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public final void setStyleIndex(int value)
```

Mengembalikan indeks dari isi BackgroundType.Themed dalam koleksi tema latar belakang. 0 berarti tidak ada isian. 1..999 - indeks. Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public final IBackgroundEffectiveData getEffective()
```

Mendapatkan data latar belakang yang efektif dengan pewarisan yang diterapkan.

--------------------

> ```
> This example demonstrates getting effective background properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IBackgroundEffectiveData effectiveBackground = pres.getSlides().get_Item(0).getBackground().getEffective();
>  	System.out.println("Background fill type: " + effectiveBackground.getFillFormat().getFillType());
>  	System.out.println("Any effects applied: " + !effectiveBackground.getEffectFormat().isNoEffects());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```

**Mengembalikan:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - sebuah [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versi. Hanya-baca long.

**Mengembalikan:**
long
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Mengembalikan objek Parent_Immediate. Hanya-baca IDOMObject.

**Mengembalikan:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final BaseSlide getSlide()
```

Mengembalikan slide induk dari sebuah bentuk. Hanya-baca [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Mengembalikan:**
[BaseSlide](../../com.aspose.slides/baseslide)
### getPresentation() {#getPresentation--}
```
public final Presentation getPresentation()
```

Mengembalikan presentasi induk dari sebuah slide. Hanya-baca [IPresentation](../../com.aspose.slides/ipresentation).

**Mengembalikan:**
[Presentation](../../com.aspose.slides/presentation)