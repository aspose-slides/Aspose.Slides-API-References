---
title: SpreadsheetOptions
second_title: Referencia de API de Aspose.Slides para Java
description: Representa opciones que pueden usarse para especificar un comportamiento adicional de las hojas de cálculo.
type: docs
url: /es/com.aspose.slides/spreadsheetoptions/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
```
public class SpreadsheetOptions implements ISpreadsheetOptions
```

Representa opciones que pueden usarse para especificar un comportamiento adicional de las hojas de cálculo.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [SpreadsheetOptions()](#SpreadsheetOptions--) | Inicializa una nueva instancia de la clase [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | Obtiene o establece la información de cultura preferida para calcular algunas funciones destinadas a usarse con idiomas que utilizan el conjunto de caracteres de doble byte (DBCS). |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | Obtiene o establece la información de cultura preferida para calcular algunas funciones destinadas a usarse con idiomas que utilizan el conjunto de caracteres de doble byte (DBCS). |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | Si la fuente de datos del gráfico es un libro de trabajo externo y no está disponible, se recuperará del caché del gráfico. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | Si la fuente de datos del gráfico es un libro de trabajo externo y no está disponible, se recuperará del caché del gráfico. |
### SpreadsheetOptions() {#SpreadsheetOptions--}
```
public SpreadsheetOptions()
```

Inicializa una nueva instancia de la clase [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions).

### getPreferredCulture() {#getPreferredCulture--}
```
public final Locale getPreferredCulture()
```

Obtiene o establece la información de cultura preferida para calcular algunas funciones destinadas a usarse con idiomas que utilizan el conjunto de caracteres de doble byte (DBCS).

**Devuelve:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public final void setPreferredCulture(Locale value)
```

Obtiene o establece la información de cultura preferida para calcular algunas funciones destinadas a usarse con idiomas que utilizan el conjunto de caracteres de doble byte (DBCS).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public final boolean getRecoverWorkbookFromChartCache()
```

Si la fuente de datos del gráfico es un libro de trabajo externo y no está disponible, se recuperará del caché del gráfico.

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

**Devuelve:**
boolean
### setRecoverWorkbookFromChartCache(boolean value) {#setRecoverWorkbookFromChartCache-boolean-}
```
public final void setRecoverWorkbookFromChartCache(boolean value)
```

Si la fuente de datos del gráfico es un libro de trabajo externo y no está disponible, se recuperará del caché del gráfico.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |