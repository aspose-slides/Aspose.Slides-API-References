---
title: IChartTitle
second_title: Aspose.Slides untuk Java Referensi API
description: Mewakili properti judul diagram.
type: docs
url: /id/com.aspose.slides/icharttitle/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartTitle extends ILayoutable, IOverridableText, IActualLayout
```

Mewakili properti judul diagram.
## Metode

| Method | Description |
| --- | --- |
| [getOverlay()](#getOverlay--) | Menentukan apakah elemen diagram lainnya diizinkan untuk menumpuk judul. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Menentukan apakah elemen diagram lainnya diizinkan untuk menumpuk judul. |
| [getFormat()](#getFormat--) | Mengembalikan gaya isian, garis, efek dari judul. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```


Menentukan apakah elemen diagram lainnya diizinkan untuk menumpuk judul. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```


Menentukan apakah elemen diagram lainnya diizinkan untuk menumpuk judul. Baca/tulis boolean.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Mengembalikan gaya isian, garis, efek dari judul. Hanya-baca [IFormat](../../com.aspose.slides/iformat).

**Mengembalikan:**
[IFormat](../../com.aspose.slides/iformat)