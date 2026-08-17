---
title: ErrorBarsFormat
second_title: Aspose.Slides için Java API Referansı
description: Grafik serisinin hata çubuklarını temsil eder.
type: docs
url: /tr/com.aspose.slides/errorbarsformat/
---
**Kalıtım:**  
java.lang.Object, com.aspose.slides.DomObject

**Uygulanan Tüm Arabirimler:**  
[com.aspose.slides.IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)  
```
public class ErrorBarsFormat extends DomObject<ChartSeries> implements IErrorBarsFormat
```

Grafik serisinin hata çubuklarını temsil eder. ErrorBars özelleştirilmiş değerler IChartDataPointCollection içinde bulunur ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) özelliğinde.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getType()](#getType--) | Hata çubuklarının tipini alır veya ayarlar. |
| [setType(int value)](#setType-int-) | Hata çubuklarının tipini alır veya ayarlar. |
| [getValueType()](#getValueType--) | Hata çubuklarının uzunluğunu belirlemenin olası yollarını temsil eder. |
| [setValueType(int value)](#setValueType-int-) | Hata çubuklarının uzunluğunu belirlemenin olası yollarını temsil eder. |
| [hasEndCap()](#hasEndCap--) | Hata çubukları üzerinde bir uç kapağı çizilmediğini belirtir. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Hata çubukları üzerinde bir uç kapağı çizilmediğini belirtir. |
| [getValue()](#getValue--) | Hata çubuklarının uzunluğunu belirlemek için Sabit, Yüzde ve StandartSapma değer türleriyle kullanılan değeri alır veya ayarlar. |
| [setValue(float value)](#setValue-float-) | Hata çubuklarının uzunluğunu belirlemek için Sabit, Yüzde ve StandartSapma değer türleriyle kullanılan değeri alır veya ayarlar. |
| [getFormat()](#getFormat--) | Hata çubuklarının biçimini temsil eder. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Hata çubuklarının biçimini temsil eder. |
| [getChart()](#getChart--) | Üst chart'ı döndürür. |
| [isVisible()](#isVisible--) | Hata Çubukları görünürlüğünü alır veya ayarlar. |
| [setVisible(boolean value)](#setVisible-boolean-) | Hata Çubukları görünürlüğünü alır veya ayarlar. |
| [getSlide()](#getSlide--) | FillFormat'ın üst slaytını döndürür. |
| [getPresentation()](#getPresentation--) | FillFormat'ın üst sunumunu döndürür. |

### getType() {#getType--}
```
public final int getType()
```

Hata çubuklarının tipini alır veya ayarlar. Okunur/Yazılır [ErrorBarType](../../com.aspose.slides/errorbartype).

**Döndürür:**  
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Hata çubuklarının tipini alır veya ayarlar. Okunur/Yazılır [ErrorBarType](../../com.aspose.slides/errorbartype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public final int getValueType()
```

Hata çubuklarının uzunluğunu belirlemenin olası yollarını temsil eder. Özel değer türü durumunda değeri belirtmek için serinin DataPoints koleksiyonundaki belirli veri noktasının ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) özelliğini kullanın. Sabit, Yüzde veya StandartSapma değer türü durumunda değeri belirtmek için Value özelliğini kullanın. Okunur/Yazılır [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Döndürür:**  
int

### setValueType(int value) {#setValueType-int-}
```
public final void setValueType(int value)
```

Hata çubuklarının uzunluğunu belirlemenin olası yollarını temsil eder. Özel değer türü durumunda değeri belirtmek için serinin DataPoints koleksiyonundaki belirli veri noktasının ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) özelliğini kullanın. Sabit, Yüzde veya StandartSapma değer türü durumunda değeri belirtmek için Value özelliğini kullanın. Okunur/Yazılır [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public final boolean hasEndCap()
```

Hata çubukları üzerinde bir uç kapağının çizilmediğini belirtir. Okunur/Yazılır boolean.

**Döndürür:**  
boolean

### setEndCap(boolean value) {#setEndCap-boolean-}
```
public final void setEndCap(boolean value)
```

Hata çubukları üzerinde bir uç kapağının çizilmediğini belirtir. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public final float getValue()
```

Sabıt, Yüzde ve StandartSapma değer türleriyle kullanılan değeri alır veya ayarlar; diğer tüm durumlarda NaN döndürür. Okunur/Yazılır float.

**Döndürür:**  
float

### setValue(float value) {#setValue-float-}
```
public final void setValue(float value)
```

Sabıt, Yüzde ve StandartSapma değer türleriyle kullanılan değeri alır veya ayarlar; diğer tüm durumlarda NaN döndürür. Okunur/Yazılır float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Hata çubuklarının biçimini temsil eder. Okunur/Yazılır [IFormat](../../com.aspose.slides/iformat).

**Döndürür:**  
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Hata çubuklarının biçimini temsil eder. Okunur/Yazılır [IFormat](../../com.aspose.slides/iformat).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Üst chart'ı döndürür. Sadece okunur [IChart](../../com.aspose.slides/ichart).

**Döndürür:**  
[IChart](../../com.aspose.slides/ichart)

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

Hata Çubukları görünürlüğünü alır veya ayarlar. Okunur/Yazılır boolean.

**Döndürür:**  
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

Hata Çubukları görünürlüğünü alır veya ayarlar. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

FillFormat'ın üst slaytını döndürür. Sadece okunur [BaseSlide](../../com.aspose.slides/baseslide).

**Döndürür:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

FillFormat'ın üst sunumunu döndürür. Sadece okunur [IPresentation](../../com.aspose.slides/ipresentation).

**Döndürür:**  
[IPresentation](../../com.aspose.slides/ipresentation)