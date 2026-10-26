---
title: IErrorBarsCustomValues
second_title: Aspose.Slides para Java API Reference
description: Especifica os valores das barras de erro.
type: docs
url: /pt/com.aspose.slides/ierrorbarscustomvalues/
---```
public interface IErrorBarsCustomValues
```

Especifica os valores das barras de erro. Deve ser usado apenas quando o tipo de valor das barras de erro for Custom.
## Métodos

| Método | Descrição |
| --- | --- |
| [getXMinus()](#getXMinus--) | Especifica o valor da barra de erro na direção negativa. |
| [getYMinus()](#getYMinus--) | Especifica o valor da barra de erro na direção negativa. |
| [getXPlus()](#getXPlus--) | Especifica o valor da barra de erro na direção positiva. |
| [getYPlus()](#getYPlus--) | Especifica o valor da barra de erro na direção positiva. |
### getXMinus() {#getXMinus--}
```
public abstract IDoubleChartValue getXMinus()
```

Especifica o valor da barra de erro na direção negativa. Disponível se o tipo de valor das barras de erro for Custom e ErrorBarsXFormat for permitido. Em qualquer outro caso, esta propriedade retorna null. Somente leitura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retorna:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYMinus() {#getYMinus--}
```
public abstract IDoubleChartValue getYMinus()
```

Especifica o valor da barra de erro na direção negativa. Disponível se o tipo de valor das barras de erro for Custom e ErrorBarsYFormat for permitido. Em qualquer outro caso, esta propriedade retorna null. Somente leitura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retorna:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getXPlus() {#getXPlus--}
```
public abstract IDoubleChartValue getXPlus()
```

Especifica o valor da barra de erro na direção positiva. Disponível se o tipo de valor das barras de erro for Custom e ErrorBarsXFormat for permitido. Em qualquer outro caso, esta propriedade retorna null. Somente leitura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retorna:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYPlus() {#getYPlus--}
```
public abstract IDoubleChartValue getYPlus()
```

Especifica o valor da barra de erro na direção positiva. Disponível se o tipo de valor das barras de erro for Custom e ErrorBarsYFormat for permitido. Em qualquer outro caso, esta propriedade retorna null. Somente leitura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retorna:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)