---
title: ITableFormat
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili format tabel.
type: docs
url: /id/com.aspose.slides/itableformat/
---```
public interface ITableFormat
```

Mewakili format tabel.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Mengembalikan objek properti isi tabel. |
| [getTransparency()](#getTransparency--) | Mendapatkan atau mengatur transparansi warna isi. |
| [setTransparency(float value)](#setTransparency-float-) | Mendapatkan atau mengatur transparansi warna isi. |
| [getEffective()](#getEffective--) | Mendapatkan properti pemformatan tabel yang efektif dengan pewarisan dan gaya tabel yang diterapkan. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Mengembalikan objek properti isi tabel. Baca-saja [IFillFormat](../../com.aspose.slides/ifillformat).

**Mengembalikan:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```


Mendapatkan atau mengatur transparansi warna isi. Baca/tulis float.

**Mengembalikan:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```


Mendapatkan atau mengatur transparansi warna isi. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public abstract ITableFormatEffectiveData getEffective()
```


Mendapatkan properti pemformatan tabel yang efektif dengan pewarisan dan gaya tabel yang diterapkan.

**Mengembalikan:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - Sebuah [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).