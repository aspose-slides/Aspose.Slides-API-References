---
title: IErrorBarsFormat
second_title: Referência da API Java para Aspose.Slides para Android
description: Representa barras de erro de séries de gráfico.
type: docs
url: /pt/com.aspose.slides/ierrorbarsformat/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IErrorBarsFormat extends IChartComponent
```

Representa as barras de erro das séries de gráfico. Os valores personalizados de ErrorBars estão em IChartDataPointCollection (na propriedade [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)).

## Métodos

| Método | Descrição |
| --- | --- |
| [getType()](#getType--) | Obtém ou define o tipo das barras de erro. |
| [setType(int value)](#setType-int-) | Obtém ou define o tipo das barras de erro. |
| [getValueType()](#getValueType--) | Representa as possíveis formas de determinar o comprimento das barras de erro. |
| [setValueType(int value)](#setValueType-int-) | Representa as possíveis formas de determinar o comprimento das barras de erro. |
| [hasEndCap()](#hasEndCap--) | Especifica que uma tampa final não é desenhada nas barras de erro. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Especifica que uma tampa final não é desenhada nas barras de erro. |
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

Obtém ou define o tipo das barras de erro. Leitura/Gravação [ErrorBarType](../../com.aspose.slides/errorbartype).

**Retorna:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Obtém ou define o tipo das barras de erro. Leitura/Gravação [ErrorBarType](../../com.aspose.slides/errorbartype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |
### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

Representa as possíveis formas de determinar o comprimento das barras de erro. No caso de tipo de valor personalizado, para especificar o valor use a propriedade [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) do ponto de dados específico na coleção DataPoints da série. Leitura/Gravação [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Retorna:**
int
### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

Representa as possíveis formas de determinar o comprimento das barras de erro. No caso de tipo de valor personalizado, para especificar o valor use a propriedade [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) do ponto de dados específico na coleção DataPoints da série. Leitura/Gravação [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |
### hasEndCap() {#hasEndCap--}
```
public abstract boolean hasEndCap()
```

Especifica que uma tampa final não é desenhada nas barras de erro. Leitura/Gravação boolean.

**Retorna:**
boolean
### setEndCap(boolean value) {#setEndCap-boolean-}
```
public abstract void setEndCap(boolean value)
```

Especifica que uma tampa final não é desenhada nas barras de erro. Leitura/Gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getValue() {#getValue--}
```
public abstract float getValue()
```

Obtém ou define o valor que é usado com os tipos de valor Fixed, Percentage e StandardDeviation para determinar o comprimento das barras de erro. Leitura/Gravação float.

**Retorna:**
float
### setValue(float value) {#setValue-float-}
```
public abstract void setValue(float value)
```

Obtém ou define o valor que é usado com os tipos de valor Fixed, Percentage e StandardDeviation para determinar o comprimento das barras de erro. Leitura/Gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Representa o formato das barras de erro. Leitura/Gravação [IFormat](../../com.aspose.slides/iformat).

**Retorna:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Representa o formato das barras de erro. Leitura/Gravação [IFormat](../../com.aspose.slides/iformat).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Obtém ou define a visibilidade das barras de erro. Leitura/Gravação boolean.

**Retorna:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Obtém ou define a visibilidade das barras de erro. Leitura/Gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |