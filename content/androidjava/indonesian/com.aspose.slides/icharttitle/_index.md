---
title: IChartTitle
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili properti judul chart.
type: docs
url: /id/com.aspose.slides/icharttitle/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartTitle extends ILayoutable, IOverridableText, IActualLayout
```

Mewakili properti judul chart.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getOverlay()](#getOverlay--) | Menentukan apakah elemen chart lain diizinkan untuk tumpang tindih dengan judul. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Menentukan apakah elemen chart lain diizinkan untuk tumpang tindih dengan judul. |
| [getFormat()](#getFormat--) | Mengembalikan gaya isi, garis, efek dari sebuah judul. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```


Menentukan apakah elemen chart lain diizinkan untuk tumpang tindih dengan judul. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```


Menentukan apakah elemen chart lain diizinkan untuk tumpang tindih dengan judul. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Mengembalikan gaya isi, garis, efek dari sebuah judul. Hanya-baca [IFormat](../../com.aspose.slides/iformat).

**Mengembalikan:**
[IFormat](../../com.aspose.slides/iformat)