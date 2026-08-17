---
title: IErrorBarsFormat
second_title: Aspose.Slides için Java API Referansı
description: Grafik serisinin hata çubuklarını temsil eder.
type: docs
url: /tr/com.aspose.slides/ierrorbarsformat/
---
**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IErrorBarsFormat extends IChartComponent
```

Grafik serisinin hata çubuklarını temsil eder. ErrorBars özel değerleri IChartDataPointCollection içinde bulunur ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) özelliğinde).

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getType()](#getType--) | Hata çubuklarının tipini alır veya ayarlar. |
| [setType(int value)](#setType-int-) | Hata çubuklarının tipini alır veya ayarlar. |
| [getValueType()](#getValueType--) | Hata çubuklarının uzunluğunu belirleme yollarını temsil eder. |
| [setValueType(int value)](#setValueType-int-) | Hata çubuklarının uzunluğunu belirleme yollarını temsil eder. |
| [hasEndCap()](#hasEndCap--) | Hata çubukları üzerinde uç kapağı çizilmediğini belirtir. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Hata çubukları üzerinde uç kapağı çizilmediğini belirtir. |
| [getValue()](#getValue--) | Hata çubuklarının uzunluğunu belirlemek için Fixed, Percentage ve StandardDeviation değer tipleriyle kullanılan değeri alır veya ayarlar. |
| [setValue(float value)](#setValue-float-) | Hata çubuklarının uzunluğunu belirlemek için Fixed, Percentage ve StandardDeviation değer tipleriyle kullanılan değeri alır veya ayarlar. |
| [getFormat()](#getFormat--) | Hata çubuklarının biçimini temsil eder. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Hata çubuklarının biçimini temsil eder. |
| [isVisible()](#isVisible--) | Hata Çubukları görünürlüğünü alır veya ayarlar. |
| [setVisible(boolean value)](#setVisible-boolean-) | Hata Çubukları görünürlüğünü alır veya ayarlar. |

### getType() {#getType--}
```
public abstract int getType()
```

Hata çubuklarının tipini alır veya ayarlar. Okuma/yazma [ErrorBarType](../../com.aspose.slides/errorbartype).

**Döndürür:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Hata çubuklarının tipini alır veya ayarlar. Okuma/yazma [ErrorBarType](../../com.aspose.slides/errorbartype).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

Hata çubuklarının uzunluğunu belirleme yollarını temsil eder. Özelleştirilmiş değer tipinde, serinin DataPoints koleksiyonundaki belirli veri noktasının [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) özelliğini kullanın. Okuma/yazma [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Döndürür:**
int

### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

Hata çubuklarının uzunluğunu belirleme yollarını temsil eder. Özelleştirilmiş değer tipinde, serinin DataPoints koleksiyonundaki belirli veri noktasının [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) özelliğini kullanın. Okuma/yazma [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public abstract boolean hasEndCap()
```

Hata çubukları üzerinde uç kapağı çizilmediğini belirtir. Okuma/yazma boolean.

**Döndürür:**
boolean

### setEndCap(boolean value) {#setEndCap-boolean-}
```
public abstract void setEndCap(boolean value)
```

Hata çubukları üzerinde uç kapağı çizilmediğini belirtir. Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public abstract float getValue()
```

Hata çubuklarının uzunluğunu belirlemek için Fixed, Percentage ve StandardDeviation değer tipleriyle kullanılan değeri alır veya ayarlar. Okuma/yazma float.

**Döndürür:**
float

### setValue(float value) {#setValue-float-}
```
public abstract void setValue(float value)
```

Hata çubuklarının uzunluğunu belirlemek için Fixed, Percentage ve StandardDeviation değer tipleriyle kullanılan değeri alır veya ayarlar. Okuma/yazma float.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Hata çubuklarının biçimini temsil eder. Okuma/yazma [IFormat](../../com.aspose.slides/iformat).

**Döndürür:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Hata çubuklarının biçimini temsil eder. Okuma/yazma [IFormat](../../com.aspose.slides/iformat).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Hata Çubukları görünürlüğünü alır veya ayarlar. Okuma/yazma boolean.

**Döndürür:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Hata Çubukları görünürlüğünü alır veya ayarlar. Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |