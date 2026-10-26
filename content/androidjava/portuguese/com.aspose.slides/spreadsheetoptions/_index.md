---
title: SpreadsheetOptions
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa opções que podem ser usadas para especificar comportamento adicional nas planilhas.
type: docs
url: /pt/com.aspose.slides/spreadsheetoptions/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
```
public class SpreadsheetOptions implements ISpreadsheetOptions
```

Representa opções que podem ser usadas para especificar comportamento adicional nas planilhas.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [SpreadsheetOptions()](#SpreadsheetOptions--) | Inicializa uma nova instância da classe [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions). |
## Métodos

| Método | Descrição |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | Obtém ou define informações de cultura preferencial para calcular algumas funções destinadas ao uso com idiomas que utilizam o conjunto de caracteres de dois bytes (DBCS). |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | Obtém ou define informações de cultura preferencial para calcular algumas funções destinadas ao uso com idiomas que utilizam o conjunto de caracteres de dois bytes (DBCS). |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | Se a fonte de dados para o gráfico for uma pasta de trabalho externa e não estiver disponível, ela será recuperada do cache do gráfico. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | Se a fonte de dados para o gráfico for uma pasta de trabalho externa e não estiver disponível, ela será recuperada do cache do gráfico. |
### SpreadsheetOptions() {#SpreadsheetOptions--}
```
public SpreadsheetOptions()
```

Inicializa uma nova instância da classe [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions).

### getPreferredCulture() {#getPreferredCulture--}
```
public final Locale getPreferredCulture()
```

Obtém ou define informações de cultura preferencial para calcular algumas funções destinadas ao uso com idiomas que utilizam o conjunto de caracteres de dois bytes (DBCS).

**Retorna:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public final void setPreferredCulture(Locale value)
```

Obtém ou define informações de cultura preferencial para calcular algumas funções destinadas ao uso com idiomas que utilizam o conjunto de caracteres de dois bytes (DBCS).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public final boolean getRecoverWorkbookFromChartCache()
```

Se a fonte de dados para o gráfico for uma pasta de trabalho externa e não estiver disponível, ela será recuperada do cache do gráfico.

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
public final void setRecoverWorkbookFromChartCache(boolean value)
```

Se a fonte de dados para o gráfico for uma pasta de trabalho externa e não estiver disponível, ela será recuperada do cache do gráfico.

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