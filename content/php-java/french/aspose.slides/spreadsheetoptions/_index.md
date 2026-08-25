---
title: SpreadsheetOptions
second_title: Référence de l'API Java via Aspose.Sildes pour PHP
description: 
type: docs

url: /fr/aspose.slides/spreadsheetoptions/
---
## SpreadsheetOptions classe

 Représente des options pouvant être utilisées pour spécifier un comportement supplémentaire des feuilles de calcul.
 
### SpreadsheetOptions {#SpreadsheetOptions}

| Nom | Description |
| --- | --- |
| SpreadsheetOptions() | Initialise une nouvelle instance de la classe SpreadsheetOptions. |

 **Renvoie:**  
SpreadsheetOptions


---


### getPreferredCulture {#getPreferredCulture}

| Nom | Description |
| --- | --- |
| getPreferredCulture () | Obtient ou définit les informations de culture préférées pour le calcul de certaines fonctions destinées à être utilisées avec les langues qui utilisent le jeu de caractères double octet (DBCS). |

 **Renvoie:**  
Locale


---


### getRecoverWorkbookFromChartCache {#getRecoverWorkbookFromChartCache}

| Nom | Description |
| --- | --- |
| getRecoverWorkbookFromChartCache () | Si la source de données pour le chart est un classeur externe et qu'il n'est pas disponible, il sera récupéré depuis le cache du chart. |

 **Renvoie:**  
boolean

 **Exception**

| Erreur | Condition |
| --- | --- |
| InvalidOperationException | Lancée lorsque le classeur externe n'est pas disponible et que la valeur de la propriété RecoverWorkbookFromChartCache est false. |


---


### setPreferredCulture {#setPreferredCulture}

| Nom | Description |
| --- | --- |
| setPreferredCulture (Locale) | Obtient ou définit les informations de culture préférées pour le calcul de certaines fonctions destinées à être utilisées avec les langues qui utilisent le jeu de caractères double octet (DBCS). |

 **Renvoie:**  
void


---


### setRecoverWorkbookFromChartCache {#setRecoverWorkbookFromChartCache}

| Nom | Description |
| --- | --- |
| setRecoverWorkbookFromChartCache (boolean) | Si la source de données pour le chart est un classeur externe et qu'il n'est pas disponible, il sera récupéré depuis le cache du chart. |

 **Renvoie:**  
void

 **Exception**

| Erreur | Condition |
| --- | --- |
| InvalidOperationException | Lancée lorsque le classeur externe n'est pas disponible et que la valeur de la propriété RecoverWorkbookFromChartCache est false. |


---