---
title: ITableFormat
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili format tabel.
type: docs
url: /id/com.aspose.slides/itableformat/
---```
public interface ITableFormat
```

Mewakili format tabel.
## Metode

| Method | Description |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Mengembalikan objek properti isian tabel. |
| [getTransparency()](#getTransparency--) | Mendapatkan atau mengatur transparansi warna isian. |
| [setTransparency(float value)](#setTransparency-float-) | Mendapatkan atau mengatur transparansi warna isian. |
| [getEffective()](#getEffective--) | Mendapatkan properti pemformatan tabel yang efektif dengan pewarisan dan gaya tabel yang diterapkan. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Mengembalikan objek properti isian tabel. Hanya-baca [IFillFormat](../../com.aspose.slides/ifillformat).

**Mengembalikan:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```


Mendapatkan atau mengatur transparansi warna isian. Baca/tulis  float .

**Mengembalikan:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```


Mendapatkan atau mengatur transparansi warna isian. Baca/tulis  float .

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public abstract ITableFormatEffectiveData getEffective()
```


Mendapatkan properti pemformatan tabel yang efektif dengan pewarisan dan gaya tabel yang diterapkan.

**Mengembalikan:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - A [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).