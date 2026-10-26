---
title: IErrorBarsCustomValues
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Menentukan nilai bar kesalahan.
type: docs
url: /id/com.aspose.slides/ierrorbarscustomvalues/
---```
public interface IErrorBarsCustomValues
```

Menentukan nilai bar kesalahan. Hanya akan digunakan ketika tipe nilai Error bars adalah Custom.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getXMinus()](#getXMinus--) | Menentukan nilai error bar dalam arah negatif. |
| [getYMinus()](#getYMinus--) | Menentukan nilai error bar dalam arah negatif. |
| [getXPlus()](#getXPlus--) | Menentukan nilai error bar dalam arah positif. |
| [getYPlus()](#getYPlus--) | Menentukan nilai error bar dalam arah positif. |
### getXMinus() {#getXMinus--}
```
public abstract IDoubleChartValue getXMinus()
```

Menentukan nilai error bar dalam arah negatif. Tersedia jika tipe nilai error bars adalah Custom dan ErrorBarsXFormat diizinkan. Dalam kasus lain properti ini mengembalikan null. Hanya-baca [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Mengembalikan:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYMinus() {#getYMinus--}
```
public abstract IDoubleChartValue getYMinus()
```

Menentukan nilai error bar dalam arah negatif. Tersedia jika tipe nilai error bars adalah Custom dan ErrorBarsYFormat diizinkan. Dalam kasus lain properti ini mengembalikan null. Hanya-baca [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Mengembalikan:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getXPlus() {#getXPlus--}
```
public abstract IDoubleChartValue getXPlus()
```

Menentukan nilai error bar dalam arah positif. Tersedia jika tipe nilai error bars adalah Custom dan ErrorBarsXFormat diizinkan. Dalam kasus lain properti ini mengembalikan null. Hanya-baca [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Mengembalikan:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYPlus() {#getYPlus--}
```
public abstract IDoubleChartValue getYPlus()
```

Menentukan nilai error bar dalam arah positif. Tersedia jika tipe nilai error bars adalah Custom dan ErrorBarsYFormat diizinkan. Dalam kasus lain properti ini mengembalikan null. Hanya-baca [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Mengembalikan:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)