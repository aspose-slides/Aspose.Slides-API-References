---
title: IErrorBarsCustomValues
second_title: Aspose.Slides for Java API Reference
description: Menentukan nilai batang kesalahan.
type: docs
url: /id/com.aspose.slides/ierrorbarscustomvalues/
---```
public interface IErrorBarsCustomValues
```

Menentukan nilai batang kesalahan. Hanya akan digunakan ketika tipe nilai batang kesalahan adalah Custom.
## Methods

| Method | Description |
| --- | --- |
| [getXMinus()](#getXMinus--) | Menentukan nilai batang kesalahan dalam arah negatif. |
| [getYMinus()](#getYMinus--) | Menentukan nilai batang kesalahan dalam arah negatif. |
| [getXPlus()](#getXPlus--) | Menentukan nilai batang kesalahan dalam arah positif. |
| [getYPlus()](#getYPlus--) | Menentukan nilai batang kesalahan dalam arah positif. |
### getXMinus() {#getXMinus--}
```
public abstract IDoubleChartValue getXMinus()
```


Menentukan nilai batang kesalahan dalam arah negatif. Tersedia jika tipe nilai batang kesalahan adalah Custom dan ErrorBarsXFormat diizinkan. Dalam kasus lain properti ini mengembalikan null. Hanya-baca [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Mengembalikan:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYMinus() {#getYMinus--}
```
public abstract IDoubleChartValue getYMinus()
```


Menentukan nilai batang kesalahan dalam arah negatif. Tersedia jika tipe nilai batang kesalahan adalah Custom dan ErrorBarsYFormat diizinkan. Dalam kasus lain properti ini mengembalikan null. Hanya-baca [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Mengembalikan:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getXPlus() {#getXPlus--}
```
public abstract IDoubleChartValue getXPlus()
```


Menentukan nilai batang kesalahan dalam arah positif. Tersedia jika tipe nilai batang kesalahan adalah Custom dan ErrorBarsXFormat diizinkan. Dalam kasus lain properti ini mengembalikan null. Hanya-baca [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Mengembalikan:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYPlus() {#getYPlus--}
```
public abstract IDoubleChartValue getYPlus()
```


Menentukan nilai batang kesalahan dalam arah positif. Tersedia jika tipe nilai batang kesalahan adalah Custom dan ErrorBarsYFormat diizinkan. Dalam kasus lain properti ini mengembalikan null. Hanya-baca [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Mengembalikan:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)