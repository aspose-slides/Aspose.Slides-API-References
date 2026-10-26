---
title: DataLabelCollection
second_title: Aspose.Sildes pour PHP via la référence d'API Java
description: 
type: docs

url: /fr/aspose.slides/datalabelcollection/
---
## DataLabelCollection classe

 Représente les étiquettes d’une série.
 
### getChart {#getChart}

| Nom | Description |
| --- | --- |
| getChart () | Renvoie le graphique parent. Lecture seule IChart. |

 **Renvoie :**
[Chart](../chart)


---


### getCount {#getCount}

| Nom | Description |
| --- | --- |
| getCount () | Obtient le nombre de toutes les étiquettes de données dans la collection. Lecture seule int. |

 **Renvoie :**
int


---


### getCountOfVisibleDataLabels {#getCountOfVisibleDataLabels}

| Nom | Description |
| --- | --- |
| getCountOfVisibleDataLabels () | Obtient le nombre d’étiquettes de données visibles dans la collection. Lecture seule int. |

 **Renvoie :**
int


---


### getDefaultDataLabelFormat {#getDefaultDataLabelFormat}

| Nom | Description |
| --- | --- |
| getDefaultDataLabelFormat () | Obtient le format d’étiquette de données par défaut. Lecture seule IDataLabelFormat. |

 **Renvoie :**
[DataLabelFormat](../datalabelformat)


---


### getLeaderLinesFormat {#getLeaderLinesFormat}

| Nom | Description |
| --- | --- |
| getLeaderLinesFormat () | Représente le format des lignes de repère des étiquettes de données. Lecture seule IChartLinesFormat. |

 **Renvoie :**
[ChartLinesFormat](../chartlinesformat)


---


### getParentSeries {#getParentSeries}

| Nom | Description |
| --- | --- |
| getParentSeries () | Obtient la série parente. Lecture seule IChartSeries. |

 **Renvoie :**
[ChartSeries](../chartseries)


---


### getPresentation {#getPresentation}

| Nom | Description |
| --- | --- |
| getPresentation () | Renvoie la présentation parente d’un FillFormat. Lecture seule IPresentation. |

 **Renvoie :**
[Presentation](../presentation)


---


### getSlide {#getSlide}

| Nom | Description |
| --- | --- |
| getSlide () | Renvoie la diapositive parente d’un FillFormat. Lecture seule BaseSlide. |

 **Renvoie :**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)


---


### get_Item {#get_Item}

| Nom | Description |
| --- | --- |
| get_Item (int) | Obtient l’étiquette de données pour le point de données ayant l’indice spécifié. Une façon alternative d’accéder à l’étiquette de données est : - series.getDataPoints().get_Item(i).getLabel() - gérer les propriétés de l’étiquette. |

 **Renvoie :**
[DataLabel](../datalabel)


---


### hide {#hide}

| Nom | Description |
| --- | --- |
| hide () | Masque l’étiquette de données par défaut en définissant tous les drapeaux Show*- (ShowValue, …) de la propriété DefaultDataLabelFormat sur false. IsVisible sera false après cela. Si l’étiquette de données n’est pas visible par défaut (IsVisible est false), vous pouvez la rendre « visible par défaut » en définissant les drapeaux Show*- (ShowValue, …) de la propriété DefaultDataLabelFormat sur true. |

 **Renvoie :**
void


---


### indexOf {#indexOf}

| Nom | Description |
| --- | --- |
| indexOf ([DataLabel](../datalabel)) | Renvoie l’indice de l’étiquette de données spécifiée dans la collection. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| value | [DataLabel](../datalabel) | Étiquette de données à rechercher. |

 **Renvoie :**
int


---


### isVisible {#isVisible}

| Nom | Description |
| --- | --- |
| isVisible () | False signifie que l’étiquette de données n’est pas visible par défaut (et donc tous les drapeaux Show*- (ShowValue, …) de la propriété DefaultDataLabelFormat sont false). Lecture seule boolean. Si l’étiquette de données est visible par défaut, vous pouvez la rendre masquée par défaut avec la méthode Hide(). Mais si l’étiquette de données n’est pas visible par défaut (IsVisible est false), vous pouvez la rendre « visible par défaut » en définissant les drapeaux Show*- (ShowValue, …) de la propriété DefaultDataLabelFormat sur true. |

 **Renvoie :**
boolean


---


### iterator {#iterator}

| Nom | Description |
| --- | --- |
| iterator () | Renvoie un itérateur qui parcourt la collection. |

 **Renvoie :**



---


### iteratorJava {#iteratorJava}

| Nom | Description |
| --- | --- |
| iteratorJava () | Renvoie un itérateur java pour l’ensemble de la collection. |

 **Renvoie :**



---