---
title: IStringOrDoubleChartValue
second_title: Referência da API Aspose.Slides para Java
description: "Representa um valor string ou double que pode ser armazenado em um documento de apresentação pptx de duas maneiras: 1) em célula(s) da pasta de trabalho relacionada ao gráfico; 2) como valor literal."
type: docs
url: /pt/com.aspose.slides/istringordoublechartvalue/
---
**Todas as interfaces implementadas:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IStringOrDoubleChartValue extends ISingleCellChartValue
```

Representa um valor string ou double que pode ser armazenado em um documento de apresentação pptx de duas maneiras: 1) em célula/células da pasta de trabalho relacionada ao gráfico; 2) como valor literal.
## Métodos

| Método | Descrição |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Retorna ou define a string literal se a propriedade DataSourceType for DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Retorna ou define a string literal se a propriedade DataSourceType for DataSourceType.StringLiterals. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Retorna ou define o double literal se a propriedade DataSourceType for DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Retorna ou define o double literal se a propriedade DataSourceType for DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | Converte o valor para double. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

Retorna ou define a string literal se a propriedade DataSourceType for DataSourceType.StringLiterals. Leitura/Escrita String.

**Retorna:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

Retorna ou define a string literal se a propriedade DataSourceType for DataSourceType.StringLiterals. Leitura/Escrita String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

Retorna ou define o double literal se a propriedade DataSourceType for DataSourceType.DoubleLiterals. Leitura/Escrita double.

**Retorna:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

Retorna ou define o double literal se a propriedade DataSourceType for DataSourceType.DoubleLiterals. Leitura/Escrita double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |
### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

Converte o valor para double.

**Retorna:**
double - Valor double