---
title: ISpreadsheetOptions
second_title: Aspose.Slides for Java API Reference
description: Représente les options pouvant être utilisées pour spécifier un comportement supplémentaire des feuilles de calcul.
type: docs
url: /fr/com.aspose.slides/ispreadsheetoptions/
---```
public interface ISpreadsheetOptions
```

Représente les options pouvant être utilisées pour spécifier un comportement supplémentaire des feuilles de calcul.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | Obtient ou définit les informations de culture préférées pour le calcul de certaines fonctions destinées à être utilisées avec des langues qui utilisent le jeu de caractères double octet (DBCS). |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | Obtient ou définit les informations de culture préférées pour le calcul de certaines fonctions destinées à être utilisées avec des langues qui utilisent le jeu de caractères double octet (DBCS). |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | Si la source de données du graphique provient d'un classeur externe et qu'elle n'est pas disponible, elle sera récupérée à partir du cache du graphique. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | Si la source de données du graphique provient d'un classeur externe et qu'elle n'est pas disponible, elle sera récupérée à partir du cache du graphique. |
### getPreferredCulture() {#getPreferredCulture--}
```
public abstract Locale getPreferredCulture()
```


Obtient ou définit les informations de culture préférées pour le calcul de certaines fonctions destinées à être utilisées avec des langues qui utilisent le jeu de caractères double octet (DBCS).

**Retourne:**  
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public abstract void setPreferredCulture(Locale value)
```


Obtient ou définit les informations de culture préférées pour le calcul de certaines fonctions destinées à être utilisées avec des langues qui utilisent le jeu de caractères double octet (DBCS).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public abstract boolean getRecoverWorkbookFromChartCache()
```


Si la source de données du graphique provient d'un classeur externe et qu'elle n'est pas disponible, elle sera récupérée à partir du cache du graphique.

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

**Retourne:**  
boolean
### setRecoverWorkbookFromChartCache(boolean value) {#setRecoverWorkbookFromChartCache-boolean-}
```
public abstract void setRecoverWorkbookFromChartCache(boolean value)
```


Si la source de données du graphique provient d'un classeur externe et qu'elle n'est pas disponible, elle sera récupérée à partir du cache du graphique.

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

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |