---
title: ErrorBarsCustomValues
second_title: Referensi API Java untuk Aspose.Slides pada Android
description: Menentukan nilai error bar.
type: docs
url: /id/com.aspose.slides/errorbarscustomvalues/
---
**Pewarisan:**
java.lang.Object, com.aspose.slides.DomObject

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
```
public class ErrorBarsCustomValues extends DomObject<ChartDataPoint> implements IErrorBarsCustomValues
```

Menentukan nilai error bar. Hanya akan digunakan ketika tipe nilai Error bars adalah Custom.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getXMinus()](#getXMinus--) | Menentukan nilai error bar ke arah negatif. |
| [getYMinus()](#getYMinus--) | Menentukan nilai error bar ke arah negatif. |
| [getXPlus()](#getXPlus--) | Menentukan nilai error bar ke arah positif. |
| [getYPlus()](#getYPlus--) | Menentukan nilai error bar ke arah positif. |
### getXMinus() {#getXMinus--}
```
public final IDoubleChartValue getXMinus()
```

Menentukan nilai error bar ke arah negatif. Tersedia jika tipe nilai error bars adalah Custom dan ErrorBarsXFormat diizinkan. Dalam kasus lain properti ini mengembalikan null. Baca-saja [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Mengembalikan:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYMinus() {#getYMinus--}
```
public final IDoubleChartValue getYMinus()
```

Menentukan nilai error bar ke arah negatif. Tersedia jika tipe nilai error bars adalah Custom dan ErrorBarsYFormat diizinkan. Dalam kasus lain properti ini mengembalikan null. Baca-saja [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Mengembalikan:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getXPlus() {#getXPlus--}
```
public final IDoubleChartValue getXPlus()
```

Menentukan nilai error bar ke arah positif. Tersedia jika tipe nilai error bars adalah Custom dan ErrorBarsXFormat diizinkan. Dalam kasus lain properti ini mengembalikan null. Baca-saja [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Mengembalikan:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYPlus() {#getYPlus--}
```
public final IDoubleChartValue getYPlus()
```

Menentukan nilai error bar ke arah positif. Tersedia jika tipe nilai error bars adalah Custom dan ErrorBarsYFormat diizinkan. Dalam kasus lain properti ini mengembalikan null. Baca-saja [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Mengembalikan:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)