---
title: ILegend
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili properti legenda diagram.
type: docs
url: /id/com.aspose.slides/ilegend/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface ILegend extends ILayoutable, IFormattedTextContainer, IActualLayout
```

Mewakili properti legenda diagram.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getOverlay()](#getOverlay--) | Menentukan apakah elemen diagram lain diizinkan menimpa legenda. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Menentukan apakah elemen diagram lain diizinkan menimpa legenda. |
| [getPosition()](#getPosition--) | Menentukan posisi legenda pada diagram. |
| [setPosition(int value)](#setPosition-int-) | Menentukan posisi legenda pada diagram. |
| [getFormat()](#getFormat--) | Mengembalikan format legenda. |
| [getEntries()](#getEntries--) | Mendapatkan entri legenda. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```

Menentukan apakah elemen diagram lain diizinkan menimpa legenda. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```

Menentukan apakah elemen diagram lain diizinkan menimpa legenda. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Menentukan posisi legenda pada diagram. Nilai non-NaN dari properti X, Y, Width, Heigt menimpa efek properti ini. Baca/tulis [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Mengembalikan:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Menentukan posisi legenda pada diagram. Nilai non-NaN dari properti X, Y, Width, Heigt menimpa efek properti ini. Baca/tulis [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Mengembalikan format legenda. Hanya-baca [IFormat](../../com.aspose.slides/iformat).

**Mengembalikan:**
[IFormat](../../com.aspose.slides/iformat)
### getEntries() {#getEntries--}
```
public abstract ILegendEntryCollection getEntries()
```

Mendapatkan entri legenda. Hanya-baca [ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection).

**Mengembalikan:**
[ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)