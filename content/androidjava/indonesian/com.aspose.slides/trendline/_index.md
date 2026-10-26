---
title: Trendline
second_title: Referensi API Java Aspose.Slides untuk Android
description: Kelas mewakili garis tren dari seri diagram
type: docs
url: /id/com.aspose.slides/trendline/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.ITrendline](../../com.aspose.slides/itrendline)
```
public class Trendline extends DomObject<TrendlineCollection> implements ITrendline
```

Kelas mewakili garis tren dari seri diagram
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | Mendapatkan atau mengatur nama garis tren. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | Mendapatkan atau mengatur nama garis tren. |
| [getTrendlineType()](#getTrendlineType--) | Mendapatkan atau mengatur tipe garis tren. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | Mendapatkan atau mengatur tipe garis tren. |
| [getFormat()](#getFormat--) | Mewakili format garis tren. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Mewakili format garis tren. |
| [getBackward()](#getBackward--) | Menentukan jumlah kategori (atau unit pada diagram pencar) yang garis tren memperluas sebelum data untuk seri yang sedang dianalisis. |
| [setBackward(double value)](#setBackward-double-) | Menentukan jumlah kategori (atau unit pada diagram pencar) yang garis tren memperluas sebelum data untuk seri yang sedang dianalisis. |
| [getForward()](#getForward--) | Menentukan jumlah kategori (atau unit pada diagram pencar) yang garis tren memperluas setelah data untuk seri yang sedang dianalisis. |
| [setForward(double value)](#setForward-double-) | Menentukan jumlah kategori (atau unit pada diagram pencar) yang garis tren memperluas setelah data untuk seri yang sedang dianalisis. |
| [getIntercept()](#getIntercept--) | Menentukan nilai di mana garis tren akan memotong sumbu y. |
| [setIntercept(double value)](#setIntercept-double-) | Menentukan nilai di mana garis tren akan memotong sumbu y. |
| [getDisplayEquation()](#getDisplayEquation--) | Menentukan bahwa persamaan untuk garis tren ditampilkan pada diagram (pada label yang sama dengan nilai Rsquared). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | Menentukan bahwa persamaan untuk garis tren ditampilkan pada diagram (pada label yang sama dengan nilai Rsquared). |
| [getOrder()](#getOrder--) | Menentukan urutan garis tren polinomial. |
| [setOrder(byte value)](#setOrder-byte-) | Menentukan urutan garis tren polinomial. |
| [getPeriod()](#getPeriod--) | Menentukan periode garis tren untuk garis rata-rata bergerak. |
| [setPeriod(byte value)](#setPeriod-byte-) | Menentukan periode garis tren untuk garis rata-rata bergerak. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | Menentukan bahwa nilai R-squared dari garis tren ditampilkan pada diagram (pada label yang sama dengan persamaan). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | Menentukan bahwa nilai R-squared dari garis tren ditampilkan pada diagram (pada label yang sama dengan persamaan). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Mewakili entri legenda yang terkait dengan garis tren ini Baca-saja [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Inisialisasi TextFrameForOverriding dengan teks dalam parameter "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Dapat berisi teks berformat kaya. |
| [getTextFormat()](#getTextFormat--) | Mengembalikan format teks. |
| [getChart()](#getChart--) | Mengembalikan diagram induk. |
| [getSlide()](#getSlide--) | Mengembalikan slide induk dari FillFormat. |
| [getPresentation()](#getPresentation--) | Mengembalikan presentasi induk dari FillFormat. |
### getTrendlineName() {#getTrendlineName--}
```
public final String getTrendlineName()
```

Mendapatkan atau mengatur nama garis tren. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public final void setTrendlineName(String value)
```

Mendapatkan atau mengatur nama garis tren. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |
### getTrendlineType() {#getTrendlineType--}
```
public final int getTrendlineType()
```

Mendapatkan atau mengatur tipe garis tren. Baca/tulis [TrendlineType](../../com.aspose.slides/trendlinetype).

**Mengembalikan:**
int
### setTrendlineType(int value) {#setTrendlineType-int-}
```
public final void setTrendlineType(int value)
```

Mendapatkan atau mengatur tipe garis tren. Baca/tulis [TrendlineType](../../com.aspose.slides/trendlinetype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Mewakili format garis tren. Baca/tulis [IFormat](../../com.aspose.slides/iformat).

**Mengembalikan:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Mewakili format garis tren. Baca/tulis [IFormat](../../com.aspose.slides/iformat).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getBackward() {#getBackward--}
```
public final double getBackward()
```

Menentukan jumlah kategori (atau unit pada diagram pencar) yang garis tren memperluas sebelum data untuk seri yang sedang dianalisis. Pada diagram pencar dan bukan pencar, nilai dapat berupa nilai nonnegatif apa pun. Baca/tulis double.

**Mengembalikan:**
double
### setBackward(double value) {#setBackward-double-}
```
public final void setBackward(double value)
```

Menentukan jumlah kategori (atau unit pada diagram pencar) yang garis tren memperluas sebelum data untuk seri yang sedang dianalisis. Pada diagram pencar dan bukan pencar, nilai dapat berupa nilai nonnegatif apa pun. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |
### getForward() {#getForward--}
```
public final double getForward()
```

Menentukan jumlah kategori (atau unit pada diagram pencar) yang garis tren memperluas setelah data untuk seri yang sedang dianalisis. Pada diagram pencar dan bukan pencar, nilai dapat berupa nilai non-negatif apa pun. Baca/tulis double.

**Mengembalikan:**
double
### setForward(double value) {#setForward-double-}
```
public final void setForward(double value)
```

Menentukan jumlah kategori (atau unit pada diagram pencar) yang garis tren memperluas setelah data untuk seri yang sedang dianalisis. Pada diagram pencar dan bukan pencar, nilai dapat berupa nilai non-negatif apa pun. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |
### getIntercept() {#getIntercept--}
```
public final double getIntercept()
```

Menentukan nilai di mana garis tren akan memotong sumbu y. Properti ini hanya didukung ketika tipe garis tren adalah exp, linear, atau poly. Baca/tulis double.

**Mengembalikan:**
double
### setIntercept(double value) {#setIntercept-double-}
```
public final void setIntercept(double value)
```

Menentukan nilai di mana garis tren akan memotong sumbu y. Properti ini hanya didukung ketika tipe garis tren adalah exp, linear, atau poly. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |
### getDisplayEquation() {#getDisplayEquation--}
```
public final boolean getDisplayEquation()
```

Menentukan bahwa persamaan untuk garis tren ditampilkan pada diagram (pada label yang sama dengan nilai Rsquared). Baca/tulis boolean.

**Mengembalikan:**
boolean
### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public final void setDisplayEquation(boolean value)
```

Menentukan bahwa persamaan untuk garis tren ditampilkan pada diagram (pada label yang sama dengan nilai Rsquared). Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getOrder() {#getOrder--}
```
public final byte getOrder()
```

Menentukan urutan garis tren polinomial. Diabaikan untuk tipe garis tren lainnya. Nilai harus antara 2 dan 6. Baca/tulis byte.

**Mengembalikan:**
byte
### setOrder(byte value) {#setOrder-byte-}
```
public final void setOrder(byte value)
```

Menentukan urutan garis tren polinomial. Diabaikan untuk tipe garis tren lainnya. Nilai harus antara 2 dan 6. Baca/tulis byte.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getPeriod() {#getPeriod--}
```
public final byte getPeriod()
```

Menentukan periode garis tren untuk garis rata-rata bergerak. Diabaikan untuk varian garis tren lainnya. Nilai harus antara 2 dan 255. Baca/tulis byte.

**Mengembalikan:**
byte
### setPeriod(byte value) {#setPeriod-byte-}
```
public final void setPeriod(byte value)
```

Menentukan periode garis tren untuk garis rata-rata bergerak. Diabaikan untuk varian garis tren lainnya. Nilai harus antara 2 dan 255. Baca/tulis byte.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public final boolean getDisplayRSquaredValue()
```

Menentukan bahwa nilai R-squared dari garis tren ditampilkan pada diagram (pada label yang sama dengan persamaan). Baca/tulis boolean.

**Mengembalikan:**
boolean
### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public final void setDisplayRSquaredValue(boolean value)
```

Menentukan bahwa nilai R-squared dari garis tren ditampilkan pada diagram (pada label yang sama dengan persamaan). Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Mewakili entri legenda yang terkait dengan garis tren ini Baca-saja [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Mengembalikan:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

Inisialisasi TextFrameForOverriding dengan teks dalam parameter "text". Jika TextFrameForOverriding sudah diinisialisasi maka cukup mengubah teksnya.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | java.lang.String | Teks untuk TextFrameForOverriding baru. |

**Mengembalikan:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

Dapat berisi teks berformat kaya. Jika properti ini tidak null maka nilai teks berformat ini menggantikan teks yang dihasilkan otomatis dari label data. Teks yang dihasilkan otomatis dari label data berarti teks yang dikelola oleh properti ShowSeriesName, ShowValue, ... dan diformat dengan properti TextFormatManager.TextFormat. Baca-saja [ITextFrame](../../com.aspose.slides/itextframe).

**Mengembalikan:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Mengembalikan format teks. Baca-saja [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Mengembalikan:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```

Mengembalikan diagram induk. Baca-saja [IChart](../../com.aspose.slides/ichart).

**Mengembalikan:**
[IChart](../../com.aspose.slides/ichart)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Mengembalikan slide induk dari FillFormat. Baca-saja [BaseSlide](../../com.aspose.slides/baseslide).

**Mengembalikan:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Mengembalikan presentasi induk dari FillFormat. Baca-saja [IPresentation](../../com.aspose.slides/ipresentation).

**Mengembalikan:**
[IPresentation](../../com.aspose.slides/ipresentation)