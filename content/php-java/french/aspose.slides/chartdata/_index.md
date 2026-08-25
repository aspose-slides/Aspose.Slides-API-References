---
title: ChartData
second_title: Aspose.Sildes pour PHP via la référence d'API Java
description: 
type: docs

url: /fr/aspose.slides/chartdata/
---
## ChartData classe

 Représente les données utilisées pour le tracé d'un graphique.
 
### getCategories {#getCategories}

| Nom | Description |
| --- | --- |
| getCategories () | Obtient les catégories principales (ou à la fois les catégories principales et secondaires si la propriété #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) est false). Lecture seule IChartCategoryCollection. Si la propriété #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) est false alors la propriété ( #getSecondaryCategories) renvoie null et les données de la propriété #getCategories sont utilisées à la fois pour les séries principales et secondaires. Si la propriété #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) est true alors les données de la propriété ( #getSecondaryCategories) sont utilisées pour les séries secondaires et les données de la propriété #getCategories sont utilisées pour les séries principales. |

 **Retour :**
[ChartCategoryCollection](../chartcategorycollection)


---


### getChartDataWorkbook {#getChartDataWorkbook}

| Nom | Description |
| --- | --- |
| getChartDataWorkbook () | Obtient la fabrique de cellules pour créer les cellules utilisées pour les séries ou les catégories du graphique. Lecture seule IChartDataWorkbook. |

 **Retour :**
[ChartDataWorkbook](../chartdataworkbook)

 **Exception**

| Erreur | Condition |
| --- | --- |
 | InvalidOperationException | Lancés lorsque le format du classeur n'est pas pris en charge. |


---


### getDataSourceType {#getDataSourceType}

| Nom | Description |
| --- | --- |
| getDataSourceType () | Représente le chemin du classeur externe si source de données externe, sinon null |

 **Retour :**
int


---


### getEmbeddedWorkbookType {#getEmbeddedWorkbookType}

| Nom | Description |
| --- | --- |
| getEmbeddedWorkbookType () | Obtient le type du classeur embarqué. Retourne WorkbookType#NotDefined si DataSourceType( #getDataSourceType) est ChartDataSourceType#ExternalWorkbook. Lecture seule WorkbookType. |

 **Retour :**
int


---


### getExternalWorkbookPath {#getExternalWorkbookPath}

| Nom | Description |
| --- | --- |
| getExternalWorkbookPath () | Représente la source de données du graphique |

 **Retour :**
String


---


### getRange {#getRange}

| Nom | Description |
| --- | --- |
| getRange () | Obtient la plage de données du graphique. |

 **Retour :**
String

 **Exception**

| Erreur | Condition |
| --- | --- |
 | InvalidOperationException | Le graphique n'utilise pas de classeur comme source de données |


---


### getSecondaryCategories {#getSecondaryCategories}

| Nom | Description |
| --- | --- |
| getSecondaryCategories () | Obtient les catégories secondaires si la propriété #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) est true. Lecture seule IChartCategoryCollection. Si la propriété #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) est false alors la propriété ( #getSecondaryCategories) renvoie null et les données de la propriété #getCategories sont utilisées à la fois pour les séries principales et secondaires. Si la propriété #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) est true alors les données de la propriété #getSecondaryCategories sont utilisées pour les séries secondaires et les données de la propriété #getCategories sont utilisées pour les séries principales. |

 **Retour :**
[ChartCategoryCollection](../chartcategorycollection)


---


### getSeries {#getSeries}

| Nom | Description |
| --- | --- |
| getSeries () | Obtient les séries. Lecture seule IChartSeriesCollection. |

 **Retour :**
[ChartSeriesCollection](../chartseriescollection)


---


### getSeriesGroups {#getSeriesGroups}

| Nom | Description |
| --- | --- |
| getSeriesGroups () | Obtient les groupes de séries. Lecture seule IChartSeriesGroupCollection. 1) Chaque groupe de séries contient des séries avec des types combinables. Les groupes de types de séries combinables sont définis et décrits avec l'énumération CombinableSeriesTypesGroup. De plus, chaque groupe de séries contient des séries qui sont tracées soit sur les axes primaires, soit sur les axes secondaires (pas les deux cas dans le même groupe). Ainsi, le principe de regroupement des séries est un regroupement par les groupes de types mentionnés ci-dessus et par le type de tracé primaire/secondaire. 2) Un groupe de séries contient certaines propriétés de séries communes à chaque série du groupe (« propriétés du groupe de séries »). Les « propriétés du groupe de séries » dans la classe ChartSeriesGroup sont lecture/écriture. Chacune des « propriétés du groupe de séries » peut avoir une projection lecture seule dans la classe ChartSeries. |

 **Retour :**
ChartSeriesGroupCollection


---


### getUseSecondaryCategories {#getUseSecondaryCategories}

| Nom | Description |
| --- | --- |
| getUseSecondaryCategories () | Si false alors la propriété #getSecondaryCategories renvoie null et les données de la propriété #getCategories sont utilisées à la fois pour les séries principales et secondaires. Si true alors les données de la propriété #getSecondaryCategories sont utilisées pour les séries secondaires et les données de la propriété #getCategories sont utilisées pour les séries principales. Lecture/écriture booléen. |

 **Retour :**
boolean


---


### readWorkbookStream {#readWorkbookStream}

| Nom | Description |
| --- | --- |
| readWorkbookStream () | Écrit le classeur Excel contenu en interne dans un flux en mémoire. |

 **Retour :**
byte


---


### setExternalWorkbook {#setExternalWorkbook}

| Nom | Description |
| --- | --- |
| setExternalWorkbook (String) | Définit le classeur externe comme source de données pour le graphique. Les données du graphique seront mises à jour à partir du classeur cible. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| workbookPath | String | Chemin vers le classeur cible |

 **Retour :**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
 | InvalidOperationException | Le classeur externe n'est pas disponible ou ne peut pas être chargé. |


---


### setExternalWorkbook {#setExternalWorkbook}

| Nom | Description |
| --- | --- |
| setExternalWorkbook (String, boolean) | Définit le classeur externe comme source de données pour le graphique. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| workbookPath | String | Chemin vers le classeur cible |
| updateChartData | boolean | Si la valeur est false, seul le chemin du classeur sera mis à jour. Les données du graphique ne seront pas chargées et mises à jour à partir du classeur cible. Peut être utilisé lorsque le classeur cible n'existe pas ou n'est pas disponible. Si la valeur est true, les données du graphique seront mises à jour à partir du classeur cible. |

 **Retour :**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
 | InvalidOperationException | Le classeur externe n'est pas disponible ou ne peut pas être chargé. |


---


### setRange {#setRange}

| Nom | Description |
| --- | --- |
| setRange (String) | Définit la plage de données du graphique. Les séries et les catégories seront mises à jour en fonction de la nouvelle plage de données. Si le nombre de séries dans la plage de données est supérieur au nombre de séries dans les données du graphique, des séries supplémentaires avec le même type que la dernière série de la collection actuelle seront ajoutées à la fin de la collection. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| formula | String | La formule de la plage de données des cellules. Par ex. : "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

 **Retour :**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
 | ArgumentException | la formule a un format incorrect. |


---


### setUseSecondaryCategories {#setUseSecondaryCategories}

| Nom | Description |
| --- | --- |
| setUseSecondaryCategories (boolean) | Si false alors la propriété #getSecondaryCategories renvoie null et les données de la propriété #getCategories sont utilisées à la fois pour les séries principales et secondaires. Si true alors les données de la propriété #getSecondaryCategories sont utilisées pour les séries secondaires et les données de la propriété #getCategories sont utilisées pour les séries principales. Lecture/écriture booléen. |

 **Retour :**
void


---


### switchRowColumn {#switchRowColumn}

| Nom | Description |
| --- | --- |
| switchRowColumn () | Échange les données entre les axes. Les données tracées sur l'axe X seront déplacées vers l'axe Y et inversement. |

 **Retour :**
void


---


### writeWorkbookStream {#writeWorkbookStream}

| Nom | Description |
| --- | --- |
| writeWorkbookStream (byte[]) | Initialise le classeur Excel contenu en interne avec la valeur spécifiée par l'utilisateur. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| ms | byte[] | Le flux fourni par l'utilisateur contenant l'intégralité du classeur Excel. |

 **Retour :**
void


---