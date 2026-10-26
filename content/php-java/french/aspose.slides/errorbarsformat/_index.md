---
title: ErrorBarsFormat
second_title: Aspose.Slides pour PHP via Référence API Java
description: 
type: docs

url: /fr/aspose.slides/errorbarsformat/
---
## ErrorBarsFormat classe

 Représente les barres d'erreur d'une série de graphique. Les valeurs personnalisées d'ErrorBars sont dans IChartDataPointCollection (dans la propriété ( IChartDataPoint#getErrorBarsCustomValues)).

### getChart {#getChart}

| Nom | Description |
| --- | --- |
| getChart () | Renvoie le graphique parent. Lecture seule IChart. |

 **Retourne:**
[Chart](../chart)


---


### getFormat {#getFormat}

| Nom | Description |
| --- | --- |
| getFormat () | Représente le format des barres d'erreur. Lecture/écriture IFormat. |

 **Retourne:**
[Format](../format)


---


### getPresentation {#getPresentation}

| Nom | Description |
| --- | --- |
| getPresentation () | Renvoie la présentation parent d'un FillFormat. Lecture seule IPresentation. |

 **Retourne:**
[Presentation](../presentation)


---


### getSlide {#getSlide}

| Nom | Description |
| --- | --- |
| getSlide () | Renvoie la diapositive parent d'un FillFormat. Lecture seule BaseSlide. |

 **Retourne:**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)


---


### getType {#getType}

| Nom | Description |
| --- | --- |
| getType () | Obtient ou définit le type des barres d'erreur. Lecture/écriture ErrorBarType. |

 **Retourne:**
int


---


### getValue {#getValue}

| Nom | Description |
| --- | --- |
| getValue () | Obtient ou définit la valeur utilisée avec les types de valeur Fixed, Percentage et StandardDeviation pour déterminer la longueur des barres d'erreur. Dans tout autre cas, renvoie NaN. Lecture/écriture float. |

 **Retourne:**
float


---


### getValueType {#getValueType}

| Nom | Description |
| --- | --- |
| getValueType () | Représente les façons possibles de déterminer la longueur des barres d'erreur. En cas de type de valeur personnalisé, utilisez la propriété ( IChartDataPoint#getErrorBarsCustomValues) du point de données spécifique dans la collection DataPoints de la série pour spécifier la valeur. En cas de type de valeur Fixed, Percentage ou StandardDeviation, utilisez la propriété Value pour spécifier la valeur. Lecture/écriture ErrorBarValueType. |

 **Retourne:**
int


---


### hasEndCap {#hasEndCap}

| Nom | Description |
| --- | --- |
| hasEndCap () | Spécifie qu'une extrémité n'est pas dessinée sur les barres d'erreur. Lecture/écriture boolean. |

 **Retourne:**
boolean


---


### isVisible {#isVisible}

| Nom | Description |
| --- | --- |
| isVisible () | Obtient ou définit la visibilité des barres d'erreur. Lecture/écriture boolean. |

 **Retourne:**
boolean


---


### setEndCap {#setEndCap}

| Nom | Description |
| --- | --- |
| setEndCap (boolean) | Spécifie qu'une extrémité n'est pas dessinée sur les barres d'erreur. Lecture/écriture boolean. |

 **Retourne:**
void


---


### setFormat {#setFormat}

| Nom | Description |
| --- | --- |
| setFormat ([Format](../format)) | Représente le format des barres d'erreur. Lecture/écriture IFormat. |

 **Retourne:**
void


---


### setType {#setType}

| Nom | Description |
| --- | --- |
| setType (int) | Obtient ou définit le type des barres d'erreur. Lecture/écriture ErrorBarType. |

 **Retourne:**
void


---


### setValue {#setValue}

| Nom | Description |
| --- | --- |
| setValue (float) | Obtient ou définit la valeur utilisée avec les types de valeur Fixed, Percentage et StandardDeviation pour déterminer la longueur des barres d'erreur. Dans tout autre cas, renvoie NaN. Lecture/écriture float. |

 **Retourne:**
void


---


### setValueType {#setValueType}

| Nom | Description |
| --- | --- |
| setValueType (int) | Représente les façons possibles de déterminer la longueur des barres d'erreur. En cas de type de valeur personnalisé, utilisez la propriété ( IChartDataPoint#getErrorBarsCustomValues) du point de données spécifique dans la collection DataPoints de la série pour spécifier la valeur. En cas de type de valeur Fixed, Percentage ou StandardDeviation, utilisez la propriété Value pour spécifier la valeur. Lecture/écriture ErrorBarValueType. |

 **Retourne:**
void


---


### setVisible {#setVisible}

| Nom | Description |
| --- | --- |
| setVisible (boolean) | Obtient ou définit la visibilité des barres d'erreur. Lecture/écriture boolean. |

 **Retourne:**
void


---