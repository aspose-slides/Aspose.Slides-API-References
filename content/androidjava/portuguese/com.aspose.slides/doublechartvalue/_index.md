---
title: DoubleChartValue
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa valor double que pode ser armazenado em um documento de apresentação pptx de duas maneiras: 1) em célula(s) da planilha relacionada ao gráfico; 2) como valor literal.
type: docs
url: /pt/com.aspose.slides/doublechartvalue/
---
**Herança:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
```
public class DoubleChartValue extends BaseChartValue implements IDoubleChartValue
```

Representa um valor double que pode ser armazenado em um documento de apresentação pptx de duas maneiras: 1) em célula(s) da planilha relacionada ao gráfico; 2) como valor literal.
## Métodos

| Método | Descrição |
| --- | --- |
| [getAsCell()](#getAsCell--) | Retorna ou define a célula de dados do gráfico. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Retorna ou define a célula de dados do gráfico. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Retorna ou define o valor como double literal. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Retorna ou define o valor como double literal. |
| [getData()](#getData--) | Retorna ou define o objeto Data. |
| [setData(Object value)](#setData-java.lang.Object-) | Retorna ou define o objeto Data. |
| [toDouble()](#toDouble--) | Converte para double. |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```


Retorna ou define a célula de dados do gráfico. Leitura/gravação [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Retorna:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```


Retorna ou define a célula de dados do gráfico. Leitura/gravação [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```


Retorna ou define o valor como double literal. Leitura/gravação double.

**Retorna:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```


Retorna ou define o valor como double literal. Leitura/gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |

### getData() {#getData--}
```
public Object getData()
```


Retorna ou define o objeto Data. Leitura/gravação Object.

**Retorna:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```


Retorna ou define o objeto Data. Leitura/gravação Object.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.Object |  |

### toDouble() {#toDouble--}
```
public final double toDouble()
```


Converte para double.

**Retorna:**
double - Retorna LiteralDouble se DataSourceType for igual a DoubleLiterals. Se DataSourceType for igual a Worksheet, retorna o valor da célula convertido com sucesso para double, caso contrário retorna NaN.