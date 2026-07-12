---
title: StringChartValue
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um valor de string que pode ser armazenado em um documento de apresentação pptx de duas maneiras: 1) em célula/células da planilha relacionada ao gráfico; 2) como valor literal.
type: docs
url: /pt/com.aspose.slides/stringchartvalue/
---
**Herança:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IStringChartValue](../../com.aspose.slides/istringchartvalue)
```
public class StringChartValue extends BaseChartValue implements IStringChartValue
```

Representa um valor de string que pode ser armazenado em um documento de apresentação pptx de duas formas: 1) em célula/células da planilha relacionada ao gráfico; 2) como valor literal.
## Métodos

| Método | Descrição |
| --- | --- |
| [getAsCells()](#getAsCells--) | Atribuição de valor nulo não é permitida. |
| [setAsCells(IChartCellCollection value)](#setAsCells-com.aspose.slides.IChartCellCollection-) | Atribuição de valor nulo não é permitida. |
| [getAsLiteralString()](#getAsLiteralString--) | Retorna ou define o valor como string literal. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Retorna ou define o valor como string literal. |
| [getData()](#getData--) | Retorna ou define o objeto Data. |
| [setData(Object value)](#setData-java.lang.Object-) | Retorna ou define o objeto Data. |
| [toString()](#toString--) | Retorna os dados de valor da string. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Define o valor a partir da célula especificada. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | Se a propriedade DataSourceType for DataSourceType.Worksheet, este método retorna o endereço das células na planilha que representam os dados da string. |
### getAsCells() {#getAsCells--}
```
public final IChartCellCollection getAsCells()
```

Atribuição de valor nulo não é permitida. O valor retornado nunca é nulo. Leitura/gravação [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Retorno:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### setAsCells(IChartCellCollection value) {#setAsCells-com.aspose.slides.IChartCellCollection-}
```
public final void setAsCells(IChartCellCollection value)
```

Atribuição de valor nulo não é permitida. O valor retornado nunca é nulo. Leitura/gravação [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) |  |
### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

Retorna ou define o valor como string literal. Leitura/gravação String.

**Retorno:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

Retorna ou define o valor como string literal. Leitura/gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getData() {#getData--}
```
public Object getData()
```

Retorna ou define o objeto Data. Leitura/gravação Object.

**Retorno:**
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
### toString() {#toString--}
```
public String toString()
```

Retorna os dados de valor da string. Retorna nulo se DataSourceType for falso e nenhum valor de string foi atribuído.

**Retorno:**
java.lang.String
### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public final void setFromOneCell(IChartDataCell cell)
```

Define o valor a partir da célula especificada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Célula. |
### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public final String getCellsAddressInWorkbook()
```

Se a propriedade DataSourceType for DataSourceType.Worksheet, este método retorna o endereço das células na planilha que representam os dados da string. Caso contrário, retorna uma string vazia.

**Retorno:**
java.lang.String