---
title: ISpreadsheetOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Representa opções que podem ser usadas para especificar comportamento adicional das planilhas.
type: docs
url: /pt/com.aspose.slides/ispreadsheetoptions/
---```
public interface ISpreadsheetOptions
```

Representa opções que podem ser usadas para especificar comportamento adicional das planilhas.
## Métodos

| Método | Descrição |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | Obtém ou define as informações de cultura preferidas para calcular algumas funções destinadas ao uso com idiomas que utilizam o conjunto de caracteres de dois bytes (DBCS). |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | Obtém ou define as informações de cultura preferidas para calcular algumas funções destinadas ao uso com idiomas que utilizam o conjunto de caracteres de dois bytes (DBCS). |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | Se a origem de dados do gráfico for uma pasta de trabalho externa e não estiver disponível, ela será recuperada do cache do gráfico. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | Se a origem de dados do gráfico for uma pasta de trabalho externa e não estiver disponível, ela será recuperada do cache do gráfico. |
### getPreferredCulture() {#getPreferredCulture--}
```
public abstract Locale getPreferredCulture()
```

Obtém ou define as informações de cultura preferidas para calcular algumas funções destinadas ao uso com idiomas que utilizam o conjunto de caracteres de dois bytes (DBCS).

**Retorna:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public abstract void setPreferredCulture(Locale value)
```

Obtém ou define as informações de cultura preferidas para calcular algumas funções destinadas ao uso com idiomas que utilizam o conjunto de caracteres de dois bytes (DBCS).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public abstract boolean getRecoverWorkbookFromChartCache()
```

Se a origem de dados do gráfico for uma pasta de trabalho externa e não estiver disponível, ela será recuperada do cache do gráfico.

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

Se a origem de dados do gráfico for uma pasta de trabalho externa e não estiver disponível, ela será recuperada do cache do gráfico.

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