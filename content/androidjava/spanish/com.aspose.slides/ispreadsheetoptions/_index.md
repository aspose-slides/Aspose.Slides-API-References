---
title: ISpreadsheetOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Representa opciones que pueden usarse para especificar un comportamiento adicional de las hojas de cálculo.
type: docs
url: /es/com.aspose.slides/ispreadsheetoptions/
---```
public interface ISpreadsheetOptions
```

Representa opciones que pueden usarse para especificar un comportamiento adicional de las hojas de cálculo.
## Métodos

| Método | Descripción |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | Obtiene o establece la información de cultura preferida para calcular algunas funciones destinadas a usarse con idiomas que utilizan el conjunto de caracteres de doble byte (DBCS). |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | Obtiene o establece la información de cultura preferida para calcular algunas funciones destinadas a usarse con idiomas que utilizan el conjunto de caracteres de doble byte (DBCS). |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | Si la fuente de datos para el gráfico es un libro de trabajo externo y no está disponible, se recuperará del caché del gráfico. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | Si la fuente de datos para el gráfico es un libro de trabajo externo y no está disponible, se recuperará del caché del gráfico. |
### getPreferredCulture() {#getPreferredCulture--}
```
public abstract Locale getPreferredCulture()
```


Obtiene o establece la información de cultura preferida para calcular algunas funciones destinadas a usarse con idiomas que utilizan el conjunto de caracteres de doble byte (DBCS).

**Devuelve:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public abstract void setPreferredCulture(Locale value)
```


Obtiene o establece la información de cultura preferida para calcular algunas funciones destinadas a usarse con idiomas que utilizan el conjunto de caracteres de doble byte (DBCS).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public abstract boolean getRecoverWorkbookFromChartCache()
```


Si la fuente de datos para el gráfico es un libro de trabajo externo y no está disponible, se recuperará del caché del gráfico.

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
public abstract void setRecoverWorkbookFromChartCache(boolean value)
```


Si la fuente de datos para el gráfico es un libro de trabajo externo y no está disponible, se recuperará del caché del gráfico.

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