---
title: IUpDownBarsManager
second_title: Aspose.Slides for Android via Java API Reference
description: Provide access to up/down bars of Line- or Stock-chart.
type: docs
url: /id/com.aspose.slides/iupdownbarsmanager/
---```
public interface IUpDownBarsManager
```

Menyediakan akses ke bar atas/bawah dari grafik Garis atau Saham.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getUpBarsFormat()](#getUpBarsFormat--) | Mengembalikan format bar atas. |
| [getDownBarsFormat()](#getDownBarsFormat--) | Mengembalikan format bar bawah. |
| [hasUpDownBars()](#hasUpDownBars--) | Menentukan apakah grafik memiliki bar atas/bawah. |
| [setUpDownBars(boolean value)](#setUpDownBars-boolean-) | Menentukan apakah grafik memiliki bar atas/bawah. |
| [getGapWidth()](#getGapWidth--) | Mengembalikan atau mengatur lebar celah. |
| [setGapWidth(int value)](#setGapWidth-int-) | Mengembalikan atau mengatur lebar celah. |
### getUpBarsFormat() {#getUpBarsFormat--}
```
public abstract IFormat getUpBarsFormat()
```

Mengembalikan format bar atas. Baca-saja [IFormat](../../com.aspose.slides/iformat).

**Mengembalikan:**
[IFormat](../../com.aspose.slides/iformat)
### getDownBarsFormat() {#getDownBarsFormat--}
```
public abstract IFormat getDownBarsFormat()
```

Mengembalikan format bar bawah. Baca-saja [IFormat](../../com.aspose.slides/iformat).

**Mengembalikan:**
[IFormat](../../com.aspose.slides/iformat)
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

Menentukan apakah grafik memiliki bar atas/bawah. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setUpDownBars(boolean value) {#setUpDownBars-boolean-}
```
public abstract void setUpDownBars(boolean value)
```

Menentukan apakah grafik memiliki bar atas/bawah. Baca/tulis boolean.

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