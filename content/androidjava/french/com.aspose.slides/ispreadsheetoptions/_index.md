---
title: ISpreadsheetOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Représente les options pouvant être utilisées pour spécifier un comportement supplémentaire des feuilles de calcul.
type: docs
url: /fr/com.aspose.slides/ispreadsheetoptions/
---
```
public interface ISpreadsheetOptions
```

Représente les options pouvant être utilisées pour spécifier un comportement supplémentaire des feuilles de calcul.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | Obtient ou définit les informations culturelles préférées pour le calcul de certaines fonctions destinées à être utilisées avec des langues qui utilisent le jeu de caractères à deux octets (DBCS). |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | Obtient ou définit les informations culturelles préférées pour le calcul de certaines fonctions destinées à être utilisées avec des langues qui utilisent le jeu de caractères à deux octets (DBCS). |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | Si la source de données du diagramme provient d’un classeur externe et qu’il n’est pas disponible, il sera récupéré à partir du cache du diagramme. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | Si la source de données du diagramme provient d’un classeur externe et qu’il n’est pas disponible, il sera récupéré à partir du cache du diagramme. |

### getPreferredCulture() {#getPreferredCulture--}
```
public abstract Locale getPreferredCulture()
```

Obtient ou définit les informations culturelles préférées pour le calcul de certaines fonctions destinées à être utilisées avec des langues qui utilisent le jeu de caractères à deux octets (DBCS).

**Renvoie :**
java.util.Locale

### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public abstract void setPreferredCulture(Locale value)
```

Obtient ou définit les informations culturelles préférées pour le calcul de certaines fonctions destinées à être utilisées avec des langues qui utilisent le jeu de caractères à deux octets (DBCS).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public abstract boolean getRecoverWorkbookFromChartCache()
```

Si la source de données du diagramme provient d’un classeur externe et qu’il n’est pas disponible, il sera récupéré à partir du cache du diagramme.

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

**Returns:**
boolean
### setRecoverWorkbookFromChartCache(boolean value) {#setRecoverWorkbookFromChartCache-boolean-}
```
public abstract void setRecoverWorkbookFromChartCache(boolean value)
If data source for the chart is an external workbook and it's not available, it will be recovered from the chart cache.

> ```
> Exemple :
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

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |