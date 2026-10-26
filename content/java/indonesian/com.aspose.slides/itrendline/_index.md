---
title: ITrendline
second_title: Referensi API Aspose.Slides untuk Java
description: Kelas mewakili garis tren dari seri diagram
type: docs
url: /id/com.aspose.slides/itrendline/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext)
```
public interface ITrendline extends IOverridableText
```

Kelas mewakili garis tren dari seri diagram
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | Mendapatkan atau menetapkan nama garis tren. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | Mendapatkan atau menetapkan nama garis tren. |
| [getTrendlineType()](#getTrendlineType--) | Mendapatkan atau menetapkan tipe garis tren. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | Mendapatkan atau menetapkan tipe garis tren. |
| [getFormat()](#getFormat--) | Mewakili format garis tren. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Mewakili format garis tren. |
| [getBackward()](#getBackward--) | Menentukan jumlah kategori (atau unit pada diagram sebar) yang garis tren memperluas sebelum data untuk seri yang sedang ditrending. |
| [setBackward(double value)](#setBackward-double-) | Menentukan jumlah kategori (atau unit pada diagram sebar) yang garis tren memperluas sebelum data untuk seri yang sedang ditrending. |
| [getForward()](#getForward--) | Menentukan jumlah kategori (atau unit pada diagram sebar) yang garis tren memperluas setelah data untuk seri yang sedang ditrending. |
| [setForward(double value)](#setForward-double-) | Menentukan jumlah kategori (atau unit pada diagram sebar) yang garis tren memperluas setelah data untuk seri yang sedang ditrending. |
| [getIntercept()](#getIntercept--) | Menentukan nilai di mana garis tren akan memotong sumbu y. |
| [setIntercept(double value)](#setIntercept-double-) | Menentukan nilai di mana garis tren akan memotong sumbu y. |
| [getDisplayEquation()](#getDisplayEquation--) | Menentukan bahwa persamaan untuk garis tren ditampilkan pada diagram (dalam label yang sama dengan Rsquaredvalue). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | Menentukan bahwa persamaan untuk garis tren ditampilkan pada diagram (dalam label yang sama dengan Rsquaredvalue). |
| [getOrder()](#getOrder--) | Menentukan urutan garis tren polinomial. |
| [setOrder(byte value)](#setOrder-byte-) | Menentukan urutan garis tren polinomial. |
| [getPeriod()](#getPeriod--) | Menentukan periode garis tren untuk garis tren rata-rata bergerak. |
| [setPeriod(byte value)](#setPeriod-byte-) | Menentukan periode garis tren untuk garis tren rata-rata bergerak. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | Menentukan bahwa nilai R-squared dari garis tren ditampilkan pada diagram (dalam label yang sama dengan persamaan). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | Menentukan bahwa nilai R-squared dari garis tren ditampilkan pada diagram (dalam label yang sama dengan persamaan). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Mewakili entri legenda yang terkait dengan garis tren ini Hanya-baca [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
### getTrendlineName() {#getTrendlineName--}
```
public abstract String getTrendlineName()
```


Mendapatkan atau menetapkan nama garis tren. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public abstract void setTrendlineName(String value)
```


Mendapatkan atau menetapkan nama garis tren. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |
### getTrendlineType() {#getTrendlineType--}
```
public abstract int getTrendlineType()
```


Mendapatkan atau menetapkan tipe garis tren. Baca/tulis [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Mengembalikan:**
int
### setTrendlineType(int value) {#setTrendlineType-int-}
```
public abstract void setTrendlineType(int value)
```


Mendapatkan atau menetapkan tipe garis tren. Baca/tulis [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Mewakili format garis tren. Baca/tulis [IFormat](../../com.aspose.slides/iformat).

**Mengembalikan:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```


Mewakili format garis tren. Baca/tulis [IFormat](../../com.aspose.slides/iformat).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getBackward() {#getBackward--}
```
public abstract double getBackward()
```


Menentukan jumlah kategori (atau unit pada diagram sebar) yang garis tren memperluas sebelum data untuk seri yang sedang ditrending. Pada diagram sebar dan non-sebar, nilai harus berupa nilai nonnegatif apa pun. Baca/tulis double.

**Mengembalikan:**
double
### setBackward(double value) {#setBackward-double-}
```
public abstract void setBackward(double value)
```


Menentukan jumlah kategori (atau unit pada diagram sebar) yang garis tren memperluas sebelum data untuk seri yang sedang ditrending. Pada diagram sebar dan non-sebar, nilai harus berupa nilai nonnegatif apa pun. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |
### getForward() {#getForward--}
```
public abstract double getForward()
```


Menentukan jumlah kategori (atau unit pada diagram sebar) yang garis tren memperluas setelah data untuk seri yang sedang ditrending. Pada diagram sebar dan non-sebar, nilai harus berupa nilai non-negatif apa pun. Baca/tulis double.

**Mengembalikan:**
double
### setForward(double value) {#setForward-double-}
```
public abstract void setForward(double value)
```


Menentukan jumlah kategori (atau unit pada diagram sebar) yang garis tren memperluas setelah data untuk seri yang sedang ditrending. Pada diagram sebar dan non-sebar, nilai harus berupa nilai non-negatif apa pun. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |
### getIntercept() {#getIntercept--}
```
public abstract double getIntercept()
```


Menentukan nilai di mana garis tren akan memotong sumbu y. Properti ini hanya didukung ketika tipe garis tren adalah exp, linear, atau poly. Baca/tulis double.

**Mengembalikan:**
double
### setIntercept(double value) {#setIntercept-double-}
```
public abstract void setIntercept(double value)
```


Menentukan nilai di mana garis tren akan memotong sumbu y. Properti ini hanya didukung ketika tipe garis tren adalah exp, linear, atau poly. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |
### getDisplayEquation() {#getDisplayEquation--}
```
public abstract boolean getDisplayEquation()
```


Menentukan bahwa persamaan untuk garis tren ditampilkan pada diagram (dalam label yang sama dengan Rsquaredvalue). Baca/tulis boolean.

**Mengembalikan:**
boolean
### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public abstract void setDisplayEquation(boolean value)
```


Menentukan bahwa persamaan untuk garis tren ditampilkan pada diagram (dalam label yang sama dengan Rsquaredvalue). Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getOrder() {#getOrder--}
```
public abstract byte getOrder()
```


Menentukan urutan garis tren polinomial. Diabaikan untuk tipe garis tren lain. Nilai harus antara 2 dan 6. Baca/tulis byte.

**Mengembalikan:**
byte
### setOrder(byte value) {#setOrder-byte-}
```
public abstract void setOrder(byte value)
```


Menentukan urutan garis tren polinomial. Diabaikan untuk tipe garis tren lain. Nilai harus antara 2 dan 6. Baca/tulis byte.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getPeriod() {#getPeriod--}
```
public abstract byte getPeriod()
```


Menentukan periode garis tren untuk garis tren rata-rata bergerak. Diabaikan untuk varian garis tren lain. Nilai harus antara 2 dan 255. Baca/tulis byte.

**Mengembalikan:**
byte
### setPeriod(byte value) {#setPeriod-byte-}
```
public abstract void setPeriod(byte value)
```


Menentukan periode garis tren untuk garis tren rata-rata bergerak. Diabaikan untuk varian garis tren lain. Nilai harus antara 2 dan 255. Baca/tulis byte.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public abstract boolean getDisplayRSquaredValue()
```


Menentukan bahwa nilai R-squared dari garis tren ditampilkan pada diagram (dalam label yang sama dengan persamaan). Baca/tulis boolean.

**Mengembalikan:**
boolean
### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public abstract void setDisplayRSquaredValue(boolean value)
```


Menentukan bahwa nilai R-squared dari garis tren ditampilkan pada diagram (dalam label yang sama dengan persamaan). Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```


Mewakili entri legenda yang terkait dengan garis tren ini Hanya-baca [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Mengembalikan:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)