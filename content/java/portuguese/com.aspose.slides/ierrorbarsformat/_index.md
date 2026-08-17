---
title: IErrorBarsFormat
second_title: Aspose.Slides para Referência da API Java
description: Representa barras de erro de séries de gráfico.
type: docs
url: /pt/com.aspose.slides/ierrorbarsformat/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IErrorBarsFormat extends IChartComponent
```

Representa barras de erro de séries de gráfico. Valores personalizados de ErrorBars estão em IChartDataPointCollection (na propriedade [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)).

## Métodos

| Método | Descrição |
| --- | --- |
| [getType()](#getType--) | Obtém ou define o tipo de barras de erro. |
| [setType(int value)](#setType-int-) | Obtém ou define o tipo de barras de erro. |
| [getValueType()](#getValueType--) | Representa possíveis maneiras de determinar o comprimento das barras de erro. |
| [setValueType(int value)](#setValueType-int-) | Representa possíveis maneiras de determinar o comprimento das barras de erro. |
| [hasEndCap()](#hasEndCap--) | Especifica que uma ponta não é desenhada nas barras de erro. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Especifica que uma ponta não é desenhada nas barras de erro. |
| [getValue()](#getValue--) | Obtém ou define o valor que é usado com os tipos de valor Fixed, Percentage e StandardDeviation para determinar o comprimento das barras de erro. |
| [setValue(float value)](#setValue-float-) | Obtém ou define o valor que é usado com os tipos de valor Fixed, Percentage e StandardDeviation para determinar o comprimento das barras de erro. |
| [getFormat()](#getFormat--) | Representa o formato das barras de erro. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Representa o formato das barras de erro. |
| [isVisible()](#isVisible--) | Obtém ou define a visibilidade das barras de erro. |
| [setVisible(boolean value)](#setVisible-boolean-) | Obtém ou define a visibilidade das barras de erro. |

### getType() {#getType--}
```
public abstract int getType()
```

Obtém ou define o tipo de barras de erro. Leitura/gravação [ErrorBarType](../../com.aspose.slides/errorbartype).

**Retorna:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Obtém ou define o tipo de barras de erro. Leitura/gravação [ErrorBarType](../../com.aspose.slides/errorbartype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

Representa possíveis maneiras de determinar o comprimento das barras de erro. No caso de tipo de valor personalizado para especificar o valor, use a propriedade [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) do ponto de dados específico na coleção DataPoints da série. Leitura/gravação [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Retorna:**
int

### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

Representa possíveis maneiras de determinar o comprimento das barras de erro. No caso de tipo de valor personalizado para especificar o valor, use a propriedade [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) do ponto de dados específico na coleção DataPoints da série. Leitura/gravação [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public abstract boolean hasEndCap()
```

Especifica que uma ponta não é desenhada nas barras de erro. Leitura/gravação boolean.

**Retorna:**
boolean

### setEndCap(boolean value) {#setEndCap-boolean-}
```
public abstract void setEndCap(boolean value)
```

Especifica que uma ponta não é desenhada nas barras de erro. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public abstract float getValue()
```

Obtém ou define o valor que é usado com os tipos de valor Fixed, Percentage e StandardDeviation para determinar o comprimento das barras de erro. Leitura/gravação float.

**Retorna:**
float

### setValue(float value) {#setValue-float-}
```
public abstract void setValue(float value)
```

Obtém ou define o valor que é usado com os tipos de valor Fixed, Percentage e StandardDeviation para determinar o comprimento das barras de erro. Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Representa o formato das barras de erro. Leitura/gravação [IFormat](../../com.aspose.slides/iformat).

**Retorna:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Representa o formato das barras de erro. Leitura/gravação [IFormat](../../com.aspose.slides/iformat).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Obtém ou define a visibilidade das barras de erro. Leitura/gravação boolean.

**Retorna:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Obtém ou define a visibilidade das barras de erro. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |