---
title: Trendline
second_title: Aspose.Slides pour PHP via la référence d'API Java
description: 
type: docs
url: /fr/aspose.slides/trendline/
---
## Trendline classe

 La classe représente la ligne de tendance d’une série de graphique

### addTextFrameForOverriding {#addTextFrameForOverriding}

| Nom | Description |
| --- | --- |
| addTextFrameForOverriding (String) | Initialise TextFrameForOverriding avec le texte du paramètre « text ». Si TextFrameForOverriding est déjà initialisé, il modifie simplement son texte. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| text | String | Texte pour un nouveau TextFrameForOverriding. |

**Retour :**
[TextFrame](../textframe)


---


### getBackward {#getBackward}

| Nom | Description |
| --- | --- |
| getBackward () | Spécifie le nombre de catégories (ou d'unités sur un graphique de dispersion) que la ligne de tendance étend avant les données de la série étudiée. Sur les graphiques de dispersion et non-dispersion, la valeur doit être une valeur non négative. Lecture/écriture double. |

**Retour :**
double


---


### getChart {#getChart}

| Nom | Description |
| --- | --- |
| getChart () | Renvoie le graphique parent. Lecture seule IChart. |

**Retour :**
[Chart](../chart)


---


### getDisplayEquation {#getDisplayEquation}

| Nom | Description |
| --- | --- |
| getDisplayEquation () | Spécifie que l’équation de la ligne de tendance est affichée sur le graphique (dans la même étiquette que la Rsquaredvalue). Lecture/écriture boolean. |

**Retour :**
boolean


---


### getDisplayRSquaredValue {#getDisplayRSquaredValue}

| Nom | Description |
| --- | --- |
| getDisplayRSquaredValue () | Spécifie que la valeur R-squared de la ligne de tendance est affichée sur le graphique (dans la même étiquette que l’équation). Lecture/écriture boolean. |

**Retour :**
boolean


---


### getFormat {#getFormat}

| Nom | Description |
| --- | --- |
| getFormat () | Représente le format de la ligne de tendance. Lecture/écriture IFormat. |

**Retour :**
[Format](../format)


---


### getForward {#getForward}

| Nom | Description |
| --- | --- |
| getForward () | Spécifie le nombre de catégories (ou d'unités sur un graphique de dispersion) que la ligne de tendance étend après les données de la série étudiée. Sur les graphiques de dispersion et non-dispersion, la valeur doit être une valeur non négative. Lecture/écriture double. |

**Retour :**
double


---


### getIntercept {#getIntercept}

| Nom | Description |
| --- | --- |
| getIntercept () | Spécifie la valeur où la ligne de tendance doit traverser l’axe y. Cette propriété n’est prise en charge que lorsque le type de ligne de tendance est exp, linear ou poly. Lecture/écriture double. |

**Retour :**
double


---


### getOrder {#getOrder}

| Nom | Description |
| --- | --- |
| getOrder () | Spécifie l’ordre de la ligne de tendance polynomial. Elle est ignorée pour les autres types de ligne de tendance. La valeur doit être comprise entre 2 et 6. Lecture/écriture byte. |

**Retour :**
byte


---


### getPeriod {#getPeriod}

| Nom | Description |
| --- | --- |
| getPeriod () | Spécifie la période de la ligne de tendance pour une ligne de moyenne mobile. Elle est ignorée pour les autres variantes de ligne de tendance. La valeur doit être comprise entre 2 et 255. Lecture/écriture byte. |

**Retour :**
byte


---


### getPresentation {#getPresentation}

| Nom | Description |
| --- | --- |
| getPresentation () | Renvoie la présentation parente d’un FillFormat. Lecture seule IPresentation. |

**Retour :**
[Presentation](../presentation)


---


### getRelatedLegendEntry {#getRelatedLegendEntry}

| Nom | Description |
| --- | --- |
| getRelatedLegendEntry () | Représente l’entrée de légende associée à cette ligne de tendance. Lecture seule ILegendEntryProperties. |

**Retour :**
[LegendEntryProperties](../legendentryproperties)


---


### getSlide {#getSlide}

| Nom | Description |
| --- | --- |
| getSlide () | Renvoie la diapositive parente d’un FillFormat. Lecture seule BaseSlide. |

**Retour :**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)


---


### getTextFormat {#getTextFormat}

| Nom | Description |
| --- | --- |
| getTextFormat () | Renvoie le format du texte. Lecture seule IChartTextFormat. |

**Retour :**
[ChartTextFormat](../charttextformat)


---


### getTextFrameForOverriding {#getTextFrameForOverriding}

| Nom | Description |
| --- | --- |
| getTextFrameForOverriding () | Peut contenir un texte formaté riche. Si cette propriété n’est pas nulle, alors cette valeur de texte formaté remplace le texte auto-généré de l’étiquette de données. Le texte auto-généré de l’étiquette de données désigne le texte géré par les propriétés ShowSeriesName, ShowValue, … et formaté avec la propriété TextFormatManager.TextFormat. Lecture seule ITextFrame. |

**Retour :**
[TextFrame](../textframe)


---


### getTrendlineName {#getTrendlineName}

| Nom | Description |
| --- | --- |
| getTrendlineName () | Obtient ou définit le nom de la ligne de tendance. Lecture/écriture String. |

**Retour :**
String


---


### getTrendlineType {#getTrendlineType}

| Nom | Description |
| --- | --- |
| getTrendlineType () | Obtient ou définit le type de ligne de tendance. Lecture/écriture TrendlineType. |

**Retour :**
int


---


### setBackward {#setBackward}

| Nom | Description |
| --- | --- |
| setBackward (double) | Spécifie le nombre de catégories (ou d'unités sur un graphique de dispersion) que la ligne de tendance étend avant les données de la série étudiée. Sur les graphiques de dispersion et non-dispersion, la valeur doit être une valeur non négative. Lecture/écriture double. |

**Retour :**
void


---


### setDisplayEquation {#setDisplayEquation}

| Nom | Description |
| --- | --- |
| setDisplayEquation (boolean) | Spécifie que l’équation de la ligne de tendance est affichée sur le graphique (dans la même étiquette que la Rsquaredvalue). Lecture/écriture boolean. |

**Retour :**
void


---


### setDisplayRSquaredValue {#setDisplayRSquaredValue}

| Nom | Description |
| --- | --- |
| setDisplayRSquaredValue (boolean) | Spécifie que la valeur R-squared de la ligne de tendance est affichée sur le graphique (dans la même étiquette que l’équation). Lecture/écriture boolean. |

**Retour :**
void


---


### setFormat {#setFormat}

| Nom | Description |
| --- | --- |
| setFormat ([Format](../format)) | Représente le format de la ligne de tendance. Lecture/écriture IFormat. |

**Retour :**
void


---


### setForward {#setForward}

| Nom | Description |
| --- | --- |
| setForward (double) | Spécifie le nombre de catégories (ou d'unités sur un graphique de dispersion) que la ligne de tendance étend après les données de la série étudiée. Sur les graphiques de dispersion et non-dispersion, la valeur doit être une valeur non négative. Lecture/écriture double. |

**Retour :**
void


---


### setIntercept {#setIntercept}

| Nom | Description |
| --- | --- |
| setIntercept (double) | Spécifie la valeur où la ligne de tendance doit traverser l’axe y. Cette propriété n’est prise en charge que lorsque le type de ligne de tendance est exp, linear ou poly. Lecture/écriture double. |

**Retour :**
void


---


### setOrder {#setOrder}

| Nom | Description |
| --- | --- |
| setOrder (byte) | Spécifie l’ordre de la ligne de tendance polynomial. Elle est ignorée pour les autres types de ligne de tendance. La valeur doit être comprise entre 2 et 6. Lecture/écriture byte. |

**Retour :**
void


---


### setPeriod {#setPeriod}

| Nom | Description |
| --- | --- |
| setPeriod (byte) | Spécifie la période de la ligne de tendance pour une ligne de moyenne mobile. Elle est ignorée pour les autres variantes de ligne de tendance. La valeur doit être comprise entre 2 et 255. Lecture/écriture byte. |

**Retour :**
void


---


### setTrendlineName {#setTrendlineName}

| Nom | Description |
| --- | --- |
| setTrendlineName (String) | Obtient ou définit le nom de la ligne de tendance. Lecture/écriture String. |

**Retour :**
void


---


### setTrendlineType {#setTrendlineType}

| Nom | Description |
| --- | --- |
| setTrendlineType (int) | Obtient ou définit le type de ligne de tendance. Lecture/écriture TrendlineType. |

**Retour :**
void


---