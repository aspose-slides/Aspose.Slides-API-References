---
title: ErrorBarsFormat
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili error bars dari seri chart.
type: docs
url: /id/com.aspose.slides/errorbarsformat/
---
**Pewarisan:**
java.lang.Object, com.aspose.slides.DomObject

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
```
public class ErrorBarsFormat extends DomObject<ChartSeries> implements IErrorBarsFormat
```

Mewakili error bars dari seri chart. ErrorBars custom values are in IChartDataPointCollection (in ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) property).

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getType()](#getType--) | Mendapatkan atau mengatur tipe error bars. |
| [setType(int value)](#setType-int-) | Mendapatkan atau mengatur tipe error bars. |
| [getValueType()](#getValueType--) | Mewakili cara-cara yang mungkin untuk menentukan panjang error bars. |
| [setValueType(int value)](#setValueType-int-) | Mewakili cara-cara yang mungkin untuk menentukan panjang error bars. |
| [hasEndCap()](#hasEndCap--) | Menentukan bahwa end cap tidak digambar pada error bars. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Menentukan bahwa end cap tidak digambar pada error bars. |
| [getValue()](#getValue--) | Mendapatkan atau mengatur nilai yang digunakan dengan Fixed, Percentage dan StandardDeviation value types untuk menentukan panjang error bars. |
| [setValue(float value)](#setValue-float-) | Mendapatkan atau mengatur nilai yang digunakan dengan Fixed, Percentage dan StandardDeviation value types untuk menentukan panjang error bars. |
| [getFormat()](#getFormat--) | Mewakili format error bars. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Mewakili format error bars. |
| [getChart()](#getChart--) | Mengembalikan bagan induk. |
| [isVisible()](#isVisible--) | Mendapatkan atau mengatur visibilitas Error Bars. |
| [setVisible(boolean value)](#setVisible-boolean-) | Mendapatkan atau mengatur visibilitas Error Bars. |
| [getSlide()](#getSlide--) | Mengembalikan slide induk dari FillFormat. |
| [getPresentation()](#getPresentation--) | Mengembalikan presentasi induk dari FillFormat. |

### getType() {#getType--}
```
public final int getType()
```

Mendapatkan atau mengatur tipe error bars. Baca/tulis [ErrorBarType](../../com.aspose.slides/errorbartype).

**Returns:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Mendapatkan atau mengatur tipe error bars. Baca/tulis [ErrorBarType](../../com.aspose.slides/errorbartype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public final int getValueType()
```

Mewakili cara-cara yang mungkin untuk menentukan panjang error bars. Jika tipe nilai kustom, gunakan properti ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) dari data point spesifik dalam koleksi DataPoints pada seri. Jika tipe nilai Fixed, Percentage, atau StandardDeviation, gunakan properti Value untuk menentukan nilai. Baca/tulis [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Returns:**
int

### setValueType(int value) {#setValueType-int-}
```
public final void setValueType(int value)
```

Mewakili cara-cara yang mungkin untuk menentukan panjang error bars. Jika tipe nilai kustom, gunakan properti ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) dari data point spesifik dalam koleksi DataPoints pada seri. Jika tipe nilai Fixed, Percentage, atau StandardDeviation, gunakan properti Value untuk menentukan nilai. Baca/tulis [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public final boolean hasEndCap()
```

Menentukan bahwa end cap tidak digambar pada error bars. Baca/tulis boolean.

**Returns:**
boolean

### setEndCap(boolean value) {#setEndCap-boolean-}
```
public final void setEndCap(boolean value)
```

Menentukan bahwa end cap tidak digambar pada error bars. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public final float getValue()
```

Mendapatkan atau mengatur nilai yang digunakan dengan Fixed, Percentage dan StandardDeviation value types untuk menentukan panjang error bars. Dalam kasus lain akan mengembalikan NaN. Baca/tulis float.

**Returns:**
float

### setValue(float value) {#setValue-float-}
```
public final void setValue(float value)
```

Mendapatkan atau mengatur nilai yang digunakan dengan Fixed, Percentage dan StandardDeviation value types untuk menentukan panjang error bars. Dalam kasus lain akan mengembalikan NaN. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Mewakili format error bars. Baca/tulis [IFormat](../../com.aspose.slides/iformat).

**Returns:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Mewakili format error bars. Baca/tulis [IFormat](../../com.aspose.slides/iformat).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Mengembalikan bagan induk. Baca-saja [IChart](../../com.aspose.slides/ichart).

**Returns:**
[IChart](../../com.aspose.slides/ichart)

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

Mendapatkan atau mengatur visibilitas Error Bars. Baca/tulis boolean.

**Returns:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

Mendapatkan atau mengatur visibilitas Error Bars. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Mengembalikan slide induk dari FillFormat. Baca-saja [BaseSlide](../../com.aspose.slides/baseslide).

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Mengembalikan presentasi induk dari FillFormat. Baca-saja [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)