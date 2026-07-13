---
title: IDataLabel
second_title: Aspose.Slides untuk Android via Referensi API Java
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
| [isVisible()](#isVisible--) | False berarti label data tidak terlihat (dan semua flag Show*- (ShowValue, ...) menjadi false). |
| [hide()](#hide--) | Membuat label data disembunyikan dengan mengatur semua flag Show*- (ShowValue, ...) ke keadaan false. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Mengembalikan format label data. |
| [getValueFromCell()](#getValueFromCell--) | Mendapatkan atau mengatur sel data workbook. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Mendapatkan atau mengatur sel data workbook. |
| [getActualLabelText()](#getActualLabelText--) | Mengembalikan teks label aktual berdasarkan pengaturan DataLabelFormat atau nilai TextFrameForOverriding.Text. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


False berarti label data tidak terlihat (dan semua flag Show*- (ShowValue, ...) menjadi false). Boolean hanya-baca.

--------------------

Jika label data terlihat, Anda dapat menyembunyikannya dengan metode Hide(). Namun jika label data tidak terlihat (IsVisible false) Anda dapat membuat label data terlihat dengan mengatur flag Show*- (ShowValue, ...) ke keadaan true.

**Mengembalikan:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```


Membuat label data disembunyikan dengan mengatur semua flag Show*- (ShowValue, ...) ke keadaan false. IsVisible akan menjadi false setelah ini.

--------------------

Jika label data tidak terlihat (IsVisible false) Anda dapat membuat label data terlihat dengan mengatur flag Show*- (ShowValue, ...) ke keadaan true.

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
java.lang.String - Teks label aktual String