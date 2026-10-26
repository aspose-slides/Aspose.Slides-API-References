---
title: IDoubleChartValue
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um valor double que pode ser armazenado em um documento de apresentação pptx de duas maneiras: 1) em célula/células da planilha relacionada ao gráfico; 2) como valor literal.
type: docs
url: /pt/com.aspose.slides/idoublechartvalue/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IDoubleChartValue extends ISingleCellChartValue
```

Representa um valor double que pode ser armazenado em um documento de apresentação pptx de duas formas: 1) em célula/células da planilha relacionada ao gráfico; 2) como valor literal.
## Métodos

| Método | Descrição |
| --- | --- |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Retorna ou define o valor double literal se DataSourceType = Charts.DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Retorna ou define o valor double literal se DataSourceType = Charts.DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | Converte para double. |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```


Retorna ou define o valor double literal se DataSourceType = Charts.DataSourceType.DoubleLiterals. Leitura/gravação double.

**Retorna:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```


Retorna ou define o valor double literal se DataSourceType = Charts.DataSourceType.DoubleLiterals. Leitura/gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```


Converte para double.

**Retorna:**
double - Valor Double.