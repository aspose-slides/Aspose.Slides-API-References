---
title: ISpreadsheetOptions
second_title: Aspose.Slides for Java API Reference
description: Representa opções que podem ser usadas para especificar comportamento adicional de planilhas.
type: docs
url: /pt/com.aspose.slides/ispreadsheetoptions/
---```
public interface ISpreadsheetOptions
```

Representa opções que podem ser usadas para especificar comportamento adicional de planilhas.
## Métodos

| Método | Descrição |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | Obtém ou define informações de cultura preferida para calcular algumas funções destinadas a uso com idiomas que utilizam o conjunto de caracteres de dois bytes (DBCS). |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | Obtém ou define informações de cultura preferida para calcular algumas funções destinadas a uso com idiomas que utilizam o conjunto de caracteres de dois bytes (DBCS). |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | Se a fonte de dados para o gráfico for uma pasta de trabalho externa e não estiver disponível, será recuperada do cache do gráfico. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | Se a fonte de dados para o gráfico for uma pasta de trabalho externa e não estiver disponível, será recuperada do cache do gráfico. |
### getPreferredCulture() {#getPreferredCulture--}
```
public abstract Locale getPreferredCulture()
```

Obtém ou define informações de cultura preferida para calcular algumas funções destinadas a uso com idiomas que utilizam o conjunto de caracteres de dois bytes (DBCS).

**Retorna:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public abstract void setPreferredCulture(Locale value)
```

Obtém ou define informações de cultura preferida para calcular algumas funções destinadas a uso com idiomas que utilizam o conjunto de caracteres de dois bytes (DBCS).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public abstract boolean getRecoverWorkbookFromChartCache()
```

Se a fonte de dados para o gráfico for uma pasta de trabalho externa e não estiver disponível, será recuperada do cache do gráfico.

--------------------

> ```
> Example:
>   
>   SpreadsheetOptions spreadOptions = new SpreadsheetOptions();
>   spreadOptions.setRecoverWorkbookFromChartCache(true);
> 
>   LoadOptions loadOptions = new LoadOptions();
>   loadOptions.setSpreadsheetOptions(spreadOptions);
> 
>   Presentation pres = new Presentation("Presentation.pptx", loadOptions);
>   try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartDataWorkbook recoveredWorkbook = chart.getChartData().getChartDataWorkbook();
>   } finally {
>      if (pres != null) pres.dispose();
>   }
> ```

**Retorna:**
boolean
### setRecoverWorkbookFromChartCache(boolean value) {#setRecoverWorkbookFromChartCache-boolean-}
```
public abstract void setRecoverWorkbookFromChartCache(boolean value)
```

Se a fonte de dados para o gráfico for uma pasta de trabalho externa e não estiver disponível, será recuperada do cache do gráfico.

--------------------

> ```
> Example:
>   
>   SpreadsheetOptions spreadOptions = new SpreadsheetOptions();
>   spreadOptions.setRecoverWorkbookFromChartCache(true);
> 
>   LoadOptions loadOptions = new LoadOptions();
>   loadOptions.setSpreadsheetOptions(spreadOptions);
> 
>   Presentation pres = new Presentation("Presentation.pptx", loadOptions);
>   try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartDataWorkbook recoveredWorkbook = chart.getChartData().getChartDataWorkbook();
>   } finally {
>      if (pres != null) pres.dispose();
>   }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |