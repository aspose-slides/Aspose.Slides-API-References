---
title: IStringChartValue
second_title: Referência da API Java do Aspose.Slides para Android
description: Representa o valor de string que pode ser armazenado em um documento de apresentação pptx de duas maneiras: 1) em célula(s) da pasta de trabalho relacionada ao gráfico 2) como valor literal.
type: docs
url: /pt/com.aspose.slides/istringchartvalue/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IMultipleCellChartValue](../../com.aspose.slides/imultiplecellchartvalue)
```
public interface IStringChartValue extends IMultipleCellChartValue
```

Representa o valor de string que pode ser armazenado em um documento de apresentação pptx de duas maneiras: 1) em célula(s) da pasta de trabalho relacionada ao gráfico; 2) como valor literal.
## Métodos

| Método | Descrição |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Retorna ou define a string literal se a propriedade DataSourceType for DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Retorna ou define a string literal se a propriedade DataSourceType for DataSourceType.StringLiterals. |
| [toString()](#toString--) | Retorna a representação da string. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Define o valor a partir da célula especificada. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | Se a propriedade DataSourceType for DataSourceType.Worksheet, este método retorna o endereço das células na pasta de trabalho que representam os dados de string. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

Retorna ou define a string literal se a propriedade DataSourceType for DataSourceType.StringLiterals. Leitura/gravação String.

**Retorna:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

Retorna ou define a string literal se a propriedade DataSourceType for DataSourceType.StringLiterals. Leitura/gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public abstract String toString()
```

Retorna a representação da string.

**Retorna:**
java.lang.String - Representação de string de um valor String
### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setFromOneCell(IChartDataCell cell)
```

Define o valor a partir da célula especificada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Célula. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public abstract String getCellsAddressInWorkbook()
```

Se a propriedade DataSourceType for DataSourceType.Worksheet, este método retorna o endereço das células na pasta de trabalho que representam os dados de string. Caso contrário, retorna uma string vazia.

**Retorna:**
java.lang.String - Valor de string String