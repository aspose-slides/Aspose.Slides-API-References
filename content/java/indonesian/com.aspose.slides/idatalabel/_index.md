---
title: IDataLabel
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili label seri.
type: docs
url: /id/com.aspose.slides/idatalabel/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

Mewakili label seri.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [isVisible()](#isVisible--) | False berarti label data tidak terlihat (dan sehingga semua Show*-flags (ShowValue, ...) bernilai false). |
| [hide()](#hide--) | Sembunyikan label data dengan mengatur semua Show*-flags (ShowValue, ...) ke status false. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Mengembalikan format label data. |
| [getValueFromCell()](#getValueFromCell--) | Mendapatkan atau mengatur sel data workbook. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Mendapatkan atau mengatur sel data workbook. |
| [getActualLabelText()](#getActualLabelText--) | Mengembalikan teks label aktual berdasarkan pengaturan DataLabelFormat atau nilai TextFrameForOverriding.Text. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False berarti label data tidak terlihat (dan sehingga semua Show*-flags (ShowValue, ...) bernilai false). Boolean hanya-baca.

--------------------

Jika label data terlihat, Anda dapat menyembunyikannya dengan metode Hide(). Namun jika label data tidak terlihat (IsVisible bernilai false), Anda dapat membuat label data terlihat dengan mengatur Show*-flags (ShowValue, ...) ke status true.

**Mengembalikan:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Sembunyikan label data dengan mengatur semua Show*-flags (ShowValue, ...) ke status false. IsVisible akan menjadi false setelah ini.

--------------------

Jika label data tidak terlihat (IsVisible bernilai false), Anda dapat membuat label data terlihat dengan mengatur Show*-flags (ShowValue, ...) ke status true.

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

Mengembalikan format label data. Hanya-baca [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Mengembalikan:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

Mendapatkan atau mengatur sel data workbook. Diterapkan jika properti IDataLabelFormat.ShowLabelValueFromCell bernilai true.

**Mengembalikan:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

Mendapatkan atau mengatur sel data workbook. Diterapkan jika properti IDataLabelFormat.ShowLabelValueFromCell bernilai true.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

Mengembalikan teks label aktual berdasarkan pengaturan DataLabelFormat atau nilai TextFrameForOverriding.Text.

**Mengembalikan:**
java.lang.String - String teks label aktual