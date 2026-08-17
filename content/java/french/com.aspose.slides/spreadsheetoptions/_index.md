---
title: SpreadsheetOptions
second_title: Référence API Aspose.Slides pour Java
description: Représente les options qui peuvent être utilisées pour spécifier un comportement supplémentaire des feuilles de calcul.
type: docs
url: /fr/com.aspose.slides/spreadsheetoptions/
---
**Héritage :**  
java.lang.Object

**Toutes les interfaces implémentées :**  
[com.aspose.slides.ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)  
```
public class SpreadsheetOptions implements ISpreadsheetOptions
```

Représente les options qui peuvent être utilisées pour spécifier un comportement supplémentaire des feuilles de calcul.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SpreadsheetOptions()](#SpreadsheetOptions--) | Initialise une nouvelle instance de la classe [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions). |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | Obtient ou définit les informations de culture préférées pour calculer certaines fonctions destinées à être utilisées avec des langues qui utilisent le jeu de caractères à double octet (DBCS). |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | Obtient ou définit les informations de culture préférées pour calculer certaines fonctions destinées à être utilisées avec des langues qui utilisent le jeu de caractères à double octet (DBCS). |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | Si la source de données du graphique provient d'un classeur externe et qu'elle n'est pas disponible, elle sera récupérée depuis le cache du graphique. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | Si la source de données du graphique provient d'un classeur externe et qu'elle n'est pas disponible, elle sera récupérée depuis le cache du graphique. |

### SpreadsheetOptions() {#SpreadsheetOptions--}
```
public SpreadsheetOptions()
```

Initialise une nouvelle instance de la classe [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions).

### getPreferredCulture() {#getPreferredCulture--}
```
public final Locale getPreferredCulture()
```

Obtient ou définit les informations de culture préférées pour calculer certaines fonctions destinées à être utilisées avec des langues qui utilisent le jeu de caractères à double octet (DBCS).

**Retourne :**  
java.util.Locale

### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public final void setPreferredCulture(Locale value)
```

Obtient ou définit les informations de culture préférées pour calculer certaines fonctions destinées à être utilisées avec des langues qui utilisent le jeu de caractères à double octet (DBCS).

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public final boolean getRecoverWorkbookFromChartCache()
```

Si la source de données du graphique provient d'un classeur externe et qu'elle n'est pas disponible, elle sera récupérée depuis le cache du graphique.

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

**Retourne :**  
boolean

### setRecoverWorkbookFromChartCache(boolean value) {#setRecoverWorkbookFromChartCache-boolean-}
```
public final void setRecoverWorkbookFromChartCache(boolean value)
```

Si la source de données du graphique provient d'un classeur externe et qu'elle n'est pas disponible, elle sera récupérée depuis le cache du graphique.

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

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |