---
title: IUpDownBarsManager
second_title: Aspose.Slides for Java API Reference
description: Menyediakan akses ke batang naik/turun dari grafik Garis atau Saham.
type: docs
url: /id/com.aspose.slides/iupdownbarsmanager/
---```
public interface IUpDownBarsManager
```

Menyediakan akses ke batang naik/turun dari grafik Garis atau Saham.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getUpBarsFormat()](#getUpBarsFormat--) | Mengembalikan format batang naik. |
| [getDownBarsFormat()](#getDownBarsFormat--) | Mengembalikan format batang turun. |
| [hasUpDownBars()](#hasUpDownBars--) | Menentukan apakah grafik memiliki batang naik/turun. |
| [setUpDownBars(boolean value)](#setUpDownBars-boolean-) | Menentukan apakah grafik memiliki batang naik/turun. |
| [getGapWidth()](#getGapWidth--) | Mengembalikan atau mengatur lebar celah. |
| [setGapWidth(int value)](#setGapWidth-int-) | Mengembalikan atau mengatur lebar celah. |
### getUpBarsFormat() {#getUpBarsFormat--}
```
public abstract IFormat getUpBarsFormat()
```


Mengembalikan format batang naik. Hanya-baca [IFormat](../../com.aspose.slides/iformat).

**Mengembalikan:**
[IFormat](../../com.aspose.slides/iformat)
### getDownBarsFormat() {#getDownBarsFormat--}
```
public abstract IFormat getDownBarsFormat()
```


Mengembalikan format batang turun. Hanya-baca [IFormat](../../com.aspose.slides/iformat).

**Mengembalikan:**
[IFormat](../../com.aspose.slides/iformat)
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```


Menentukan apakah grafik memiliki batang naik/turun. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setUpDownBars(boolean value) {#setUpDownBars-boolean-}
```
public abstract void setUpDownBars(boolean value)
```


Menentukan apakah grafik memiliki batang naik/turun. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```


Mengembalikan atau mengatur lebar celah. Baca/tulis int.

**Mengembalikan:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```


Mengembalikan atau mengatur lebar celah. Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |