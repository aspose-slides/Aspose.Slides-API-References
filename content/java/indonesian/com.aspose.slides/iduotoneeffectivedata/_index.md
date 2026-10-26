---
title: IDuotoneEffectiveData
second_title: Referensi API Aspose.Slides untuk Java
description: Objek tidak dapat diubah yang mewakili efek Duotone.
type: docs
url: /id/com.aspose.slides/iduotoneeffectivedata/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IDuotoneEffectiveData extends IEffectEffectiveData
```

Objek tidak dapat diubah yang mewakili efek Duotone. Untuk setiap piksel, menggabungkan clr1 dan clr2 melalui interpolasi linier untuk menentukan warna baru bagi piksel tersebut.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getColor1()](#getColor1--) | Mengembalikan format warna target untuk piksel gelap. |
| [getColor2()](#getColor2--) | Mengembalikan format warna target untuk piksel terang. |
### getColor1() {#getColor1--}
```
public abstract Color getColor1()
```


Mengembalikan format warna target untuk piksel gelap. Hanya-baca java.awt.Color.

**Mengembalikan:**
java.awt.Color
### getColor2() {#getColor2--}
```
public abstract Color getColor2()
```


Mengembalikan format warna target untuk piksel terang. Hanya-baca java.awt.Color.

**Mengembalikan:**
java.awt.Color