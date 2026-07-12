---
title: ErrorBarsFormat
second_title: Aspose.Slides para Android via Referência de API Java
description: Representa as barras de erro de séries de gráfico.
type: docs
url: /pt/com.aspose.slides/errorbarsformat/
---
**Herança:**
java.lang.Object, com.aspose.slides.DomObject

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
```
public class ErrorBarsFormat extends DomObject<ChartSeries> implements IErrorBarsFormat
```

Representa as barras de erro de séries de gráfico. Os valores personalizados de ErrorBars estão em IChartDataPointCollection (na propriedade ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

## Métodos

| Método | Descrição |
| --- | --- |
| [getType()](#getType--) | Obtém ou define o tipo de barras de erro. |
| [setType(int value)](#setType-int-) | Obtém ou define o tipo de barras de erro. |
| [getValueType()](#getValueType--) | Representa as possíveis maneiras de determinar o comprimento das barras de erro. |
| [setValueType(int value)](#setValueType-int-) | Representa as possíveis maneiras de determinar o comprimento das barras de erro. |
| [hasEndCap()](#hasEndCap--) | Especifica que uma tampa final não é desenhada nas barras de erro. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Especifica que uma tampa final não é desenhada nas barras de erro. |
| [getValue()](#getValue--) | Obtém ou define o valor usado com os tipos de valor Fixed, Percentage e StandardDeviation para determinar o comprimento das barras de erro. |
| [setValue(float value)](#setValue-float-) | Obtém ou define o valor usado com os tipos de valor Fixed, Percentage e StandardDeviation para determinar o comprimento das barras de erro. |
| [getFormat()](#getFormat--) | Representa o formato das barras de erro. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Representa o formato das barras de erro. |
| [getChart()](#getChart--) | Retorna o gráfico pai. |
| [isVisible()](#isVisible--) | Obtém ou define a visibilidade das barras de erro. |
| [setVisible(boolean value)](#setVisible-boolean-) | Obtém ou define a visibilidade das barras de erro. |
| [getSlide()](#getSlide--) | Retorna o slide pai de um FillFormat. |
| [getPresentation()](#getPresentation--) | Retorna a apresentação pai de um FillFormat. |
### getType() {#getType--}
```
public final int getType()
```


Obtém ou define o tipo de barras de erro. Leitura/gravação [ErrorBarType](../../com.aspose.slides/errorbartype).

**Retorna:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Obtém ou define o tipo de barras de erro. Leitura/gravação [ErrorBarType](../../com.aspose.slides/errorbartype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public final int getValueType()
```


Representa as possíveis maneiras de determinar o comprimento das barras de erro. No caso do tipo de valor customizado, use a propriedade ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) do ponto de dados específico na coleção DataPoints da série. No caso dos tipos Fixed, Percentage ou StandardDeviation, use a propriedade Value para especificar o valor. Leitura/gravação [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Retorna:**
int
### setValueType(int value) {#setValueType-int-}
```
public final void setValueType(int value)
```


Representa as possíveis maneiras de determinar o comprimento das barras de erro. No caso do tipo de valor customizado, use a propriedade ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) do ponto de dados específico na coleção DataPoints da série. No caso dos tipos Fixed, Percentage ou StandardDeviation, use a propriedade Value para especificar o valor. Leitura/gravação [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public final boolean hasEndCap()
```


Especifica que uma tampa final não é desenhada nas barras de erro. Leitura/gravação boolean.

**Retorna:**
boolean
### setEndCap(boolean value) {#setEndCap-boolean-}
```
public final void setEndCap(boolean value)
```


Especifica que uma tampa final não é desenhada nas barras de erro. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public final float getValue()
```


Obtém ou define o valor usado com os tipos de valor Fixed, Percentage e StandardDeviation para determinar o comprimento das barras de erro. Em qualquer outro caso retornará NaN. Leitura/gravação float.

**Retorna:**
float
### setValue(float value) {#setValue-float-}
```
public final void setValue(float value)
```


Obtém ou define o valor usado com os tipos de valor Fixed, Percentage e StandardDeviation para determinar o comprimento das barras de erro. Em qualquer outro caso retornará NaN. Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```


Representa o formato das barras de erro. Leitura/gravação [IFormat](../../com.aspose.slides/iformat).

**Retorna:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```


Representa o formato das barras de erro. Leitura/gravação [IFormat](../../com.aspose.slides/iformat).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```


Retorna o gráfico pai. Somente leitura [IChart](../../com.aspose.slides/ichart).

**Retorna:**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


Obtém ou define a visibilidade das barras de erro. Leitura/gravação boolean.

**Retorna:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Obtém ou define a visibilidade das barras de erro. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Retorna o slide pai de um FillFormat. Somente leitura [BaseSlide](../../com.aspose.slides/baseslide).

**Retorna:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Retorna a apresentação pai de um FillFormat. Somente leitura [IPresentation](../../com.aspose.slides/ipresentation).

**Retorna:**
[IPresentation](../../com.aspose.slides/ipresentation)