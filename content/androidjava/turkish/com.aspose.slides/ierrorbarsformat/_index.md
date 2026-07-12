---
title: IErrorBarsFormat
second_title: Aspose.Slides for Android aracılığıyla Java API Referansı
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
| [getValueType()](#getValueType--) | Hata çubuklarının uzunluğunu belirlemenin olası yollarını temsil eder. |
| [setValueType(int value)](#setValueType-int-) | Hata çubuklarının uzunluğunu belirlemenin olası yollarını temsil eder. |
| [hasEndCap()](#hasEndCap--) | Hata çubuklarının ucunda bir son kapak çizilmediğini belirtir. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Hata çubuklarının ucunda bir son kapak çizilmediğini belirtir. |
| [getValue()](#getValue--) | Sabit, Percentage ve StandardDeviation değer tipleriyle kullanılan, hata çubuklarının uzunluğunu belirlemek için kullanılan değeri alır veya ayarlar. |
| [setValue(float value)](#setValue-float-) | Sabit, Percentage ve StandardDeviation değer tipleriyle kullanılan, hata çubuklarının uzunluğunu belirlemek için kullanılan değeri alır veya ayarlar. |
| [getFormat()](#getFormat--) | Hata çubuklarının biçimini temsil eder. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Hata çubuklarının biçimini temsil eder. |
| [isVisible()](#isVisible--) | Error Bars görünürlüğünü alır veya ayarlar. |
| [setVisible(boolean value)](#setVisible-boolean-) | Error Bars görünürlüğünü alır veya ayarlar. |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

Hata çubuklarının uzunluğunu belirlemenin olası yollarını temsil eder. Özel değer tipinde, değeri belirtmek için serinin DataPoints koleksiyonundaki belirli veri noktasının [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) özelliğini kullanın. Okuma/yazma [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Döndürür:**
int
### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

Hata çubuklarının uzunluğunu belirlemenin olası yollarını temsil eder. Özel değer tipinde, değeri belirtmek için serinin DataPoints koleksiyonundaki belirli veri noktasının [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) özelliğini kullanın. Okuma/yazma [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### hasEndCap() {#hasEndCap--}
```
public abstract boolean hasEndCap()
```

Hata çubuklarının ucunda bir son kapak çizilmediğini belirtir. Okuma/yazma boolean.

**Döndürür:**
boolean
### setEndCap(boolean value) {#setEndCap-boolean-}
```
public abstract void setEndCap(boolean value)
```

Hata çubuklarının ucunda bir son kapak çizilmediğini belirtir. Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Error Bars görünürlüğünü alır veya ayarlar. Okuma/yazma boolean.

**Döndürür:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Error Bars görünürlüğünü alır veya ayarlar. Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
