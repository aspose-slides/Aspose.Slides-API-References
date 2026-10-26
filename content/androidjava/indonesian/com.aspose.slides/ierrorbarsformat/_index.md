---
title: IErrorBarsFormat
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili error bars pada seri chart.
type: docs
url: /id/com.aspose.slides/ierrorbarsformat/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IErrorBarsFormat extends IChartComponent
```

Mewakili error bars dari seri chart. Nilai kustom ErrorBars berada di IChartDataPointCollection (pada properti [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)).

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getType()](#getType--) | Mendapatkan atau mengatur tipe error bars. |
| [setType(int value)](#setType-int-) | Mendapatkan atau mengatur tipe error bars. |
| [getValueType()](#getValueType--) | Mewakili cara-cara yang memungkinkan untuk menentukan panjang error bars. |
| [setValueType(int value)](#setValueType-int-) | Mewakili cara-cara yang memungkinkan untuk menentukan panjang error bars. |
| [hasEndCap()](#hasEndCap--) | Menentukan bahwa ujung penutup tidak digambar pada error bars. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Menentukan bahwa ujung penutup tidak digambar pada error bars. |
| [getValue()](#getValue--) | Mendapatkan atau mengatur nilai yang digunakan dengan tipe nilai Fixed, Percentage, dan StandardDeviation untuk menentukan panjang error bars. |
| [setValue(float value)](#setValue-float-) | Mendapatkan atau mengatur nilai yang digunakan dengan tipe nilai Fixed, Percentage, dan StandardDeviation untuk menentukan panjang error bars. |
| [getFormat()](#getFormat--) | Mewakili format error bars. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Mewakili format error bars. |
| [isVisible()](#isVisible--) | Mendapatkan atau mengatur visibilitas Error Bars. |
| [setVisible(boolean value)](#setVisible-boolean-) | Mendapatkan atau mengatur visibilitas Error Bars. |

### getType() {#getType--}
```
public abstract int getType()
```

Mendapatkan atau mengatur tipe error bars. Baca/tulis [ErrorBarType](../../com.aspose.slides/errorbartype).

**Mengembalikan:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Mendapatkan atau mengatur tipe error bars. Baca/tulis [ErrorBarType](../../com.aspose.slides/errorbartype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

Mewakili cara-cara yang memungkinkan untuk menentukan panjang error bars. Dalam kasus tipe nilai khusus, gunakan properti [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) pada data point tertentu di koleksi DataPoints seri. Baca/tulis [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Mengembalikan:**
int

### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

Mewakili cara-cara yang memungkinkan untuk menentukan panjang error bars. Dalam kasus tipe nilai khusus, gunakan properti [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) pada data point tertentu di koleksi DataPoints seri. Baca/tulis [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public abstract boolean hasEndCap()
```

Menentukan bahwa ujung penutup tidak digambar pada error bars. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setEndCap(boolean value) {#setEndCap-boolean-}
```
public abstract void setEndCap(boolean value)
```

Menentukan bahwa ujung penutup tidak digambar pada error bars. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public abstract float getValue()
```

Mendapatkan atau mengatur nilai yang digunakan dengan tipe nilai Fixed, Percentage, dan StandardDeviation untuk menentukan panjang error bars. Baca/tulis float.

**Mengembalikan:**
float

### setValue(float value) {#setValue-float-}
```
public abstract void setValue(float value)
```

Mendapatkan atau mengatur nilai yang digunakan dengan tipe nilai Fixed, Percentage, dan StandardDeviation untuk menentukan panjang error bars. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Mewakili format error bars. Baca/tulis [IFormat](../../com.aspose.slides/iformat).

**Mengembalikan:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Mewakili format error bars. Baca/tulis [IFormat](../../com.aspose.slides/iformat).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Mendapatkan atau mengatur visibilitas Error Bars. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Mendapatkan atau mengatur visibilitas Error Bars. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |