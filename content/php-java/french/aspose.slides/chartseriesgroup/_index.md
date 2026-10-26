---
title: ChartSeriesGroup
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/chartseriesgroup/
---
## ChartSeriesGroup class

 Représente un groupe de séries.
 
 1) Voir le résumé et les remarques pour la classe ChartSeriesGroupCollection et l'énumération CombinableSeriesTypesGroup.
 2) Le groupe de séries contient certaines propriétés de séries qui sont communes à chaque série du groupe (« series group properties »). Les « series group properties » dans la classe ChartSeriesGroup sont en lecture/écriture. Chacune des « series group properties » peut avoir une projection en lecture seule dans la classe ChartSeries.

### getBubbleSizeRepresentation {#getBubbleSizeRepresentation}

| Nom | Description |
| --- | --- |
| getBubbleSizeRepresentation () | Spécifie comment les valeurs de taille des bulles sont représentées sur le graphique à bulles. Lecture/écriture BubbleSizeRepresentationType. |

 **Renvoie :**
int


---


### getBubbleSizeScale {#getBubbleSizeScale}

| Nom | Description |
| --- | --- |
| getBubbleSizeScale () | Spécifie le facteur d’échelle pour le graphique à bulles (peut être compris entre 0 et 300 % de la taille par défaut). Lecture/écriture int. |

 **Renvoie :**
int


---


### getChart {#getChart}

| Nom | Description |
| --- | --- |
| getChart () | Renvoie le graphique parent. Lecture seule IChart. |

 **Renvoie :**
[Chart](../chart)


---


### getDoughnutHoleSize {#getDoughnutHoleSize}

| Nom | Description |
| --- | --- |
| getDoughnutHoleSize () | Spécifie la taille du trou dans un graphique en anneau (peut être comprise entre 0 et 90 % de la taille de la zone de tracé). Lecture/écriture byte. |

 **Renvoie :**
byte


---


### getFirstSliceAngle {#getFirstSliceAngle}

| Nom | Description |
| --- | --- |
| getFirstSliceAngle () | Obtient ou définit l’angle de la première tranche de graphique en secteur ou en anneau, en degrés (dans le sens des aiguilles d’une montre à partir du haut, de 0 à 360 degrés). Lecture/écriture int. |

 **Renvoie :**
int


---


### getGapDepth {#getGapDepth}

| Nom | Description |
| --- | --- |
| getGapDepth () | Renvoie ou définit la distance, exprimée en pourcentage de la largeur du marqueur, entre les séries de données dans un graphique 3D. Lecture/écriture int. |

 **Renvoie :**
int


---


### getGapWidth {#getGapWidth}

| Nom | Description |
| --- | --- |
| getGapWidth () | Spécifie l’espace entre les groupes de barres ou de colonnes, en pourcentage de la largeur de la barre ou de la colonne. Lecture/écriture int. |

 **Renvoie :**
int


---


### getHiLowLinesFormat {#getHiLowLinesFormat}

| Nom | Description |
| --- | --- |
| getHiLowLinesFormat () | Spécifie le format HiLowLines. HiLowLines s’applique aux types de graphiques HiLowClose, OpenHiLowClose, VolumeHiLowClose et VolumeOpenHiLowClose. |

 **Renvoie :**
[ChartLinesFormat](../chartlinesformat)


---


### getOverlap {#getOverlap}

| Nom | Description |
| --- | --- |
| getOverlap () | Spécifie le degré de chevauchement des barres et des colonnes sur les graphiques 2 D, en pourcentage (de -100 % à 100 %). -100 % : espacement maximal (barres complètement séparées). 0 % : barres placées côte à côte sans chevauchement ni espacement. 100 % : chevauchement maximal (barres totalement superposées). Cette propriété est en lecture/écriture byte. |

 **Renvoie :**
byte

 **Exception**

| Erreur | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | Lancée lorsque la valeur est définie en dehors de l’intervalle valide de -100 à 100. |


---


### getPieSplitBy {#getPieSplitBy}

| Nom | Description |
| --- | --- |
| getPieSplitBy () | Spécifie comment déterminer quels points de données se trouvent dans le deuxième secteur ou la deuxième barre d’un graphique pie-of-pie ou bar-of-pie. Lecture/écriture PieSplitType. |

 **Renvoie :**
int


---


### getPieSplitCustomPoints {#getPieSplitCustomPoints}

| Nom | Description |
| --- | --- |
| getPieSplitCustomPoints () | Les informations de division personnalisée pour un graphique pie-of-pie ou bar-of-pie avec une division personnalisée. Contient les points de données qui doivent être dessinés dans le deuxième secteur ou la deuxième barre. Lecture seule PieSplitCustomPointCollection. |

 **Renvoie :**
[PieSplitCustomPointCollection](../piesplitcustompointcollection)


---


### getPieSplitPosition {#getPieSplitPosition}

| Nom | Description |
| --- | --- |
| getPieSplitPosition () | Spécifie une valeur qui doit être utilisée pour déterminer quels points de données se trouvent dans le deuxième secteur ou la deuxième barre d’un graphique pie-of-pie ou bar-of-pie. Utilisée conjointement avec la propriété PieSplitBy. Lecture/écriture double. |

 **Renvoie :**
double


---


### getPlotOnSecondAxis {#getPlotOnSecondAxis}

| Nom | Description |
| --- | --- |
| getPlotOnSecondAxis () | Indique si les séries de ce groupe sont tracées sur l’axe secondaire. Lecture seule boolean. |

 **Renvoie :**
boolean


---


### getPresentation {#getPresentation}

| Nom | Description |
| --- | --- |
| getPresentation () | Renvoie la présentation parente d’un FillFormat. Lecture seule IPresentation. |

 **Renvoie :**
[Presentation](../presentation)


---


### getSecondPieSize {#getSecondPieSize}

| Nom | Description |
| --- | --- |
| getSecondPieSize () | Spécifie la taille du deuxième secteur ou de la deuxième barre d’un graphique pie-of-pie ou bar-of-pie, en pourcentage de la taille du premier secteur (peut être comprise entre 5 et 200 %). Lecture/écriture int. |

 **Renvoie :**
int


---


### getSeries {#getSeries}

| Nom | Description |
| --- | --- |
| getSeries () | Renvoie une collection de séries. Lecture seule IChartSeriesReadonlyCollection. |

 **Renvoie :**
ChartSeriesReadonlyCollection


---


### getSlide {#getSlide}

| Nom | Description |
| --- | --- |
| getSlide () | Renvoie la diapositive parente d’un FillFormat. Lecture seule BaseSlide. |

 **Renvoie :**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)


---


### getType {#getType}

| Nom | Description |
| --- | --- |
| getType () | Renvoie le type de ce groupe de séries. Lecture seule CombinableSeriesTypesGroup. |

 **Renvoie :**
int


---


### getUpDownBars {#getUpDownBars}

| Nom | Description |
| --- | --- |
| getUpDownBars () | Fournit l’accès aux barres haut/bas des graphiques en ligne ou en bourse. Lecture seule IUpDownBarsManager. |

 **Renvoie :**
[UpDownBarsManager](../updownbarsmanager)


---


### get_Item {#get_Item}

| Nom | Description |
| --- | --- |
| get_Item (int) | Obtient l’élément à l’index spécifié. |

 **Renvoie :**
[ChartSeries](../chartseries)


---


### hasSeriesLines {#hasSeriesLines}

| Nom | Description |
| --- | --- |
| hasSeriesLines () | Vrai si le graphique possède des lignes de séries. Appliqué aux graphiques à barres empilées et OfPie. Lecture/écriture boolean. |

 **Renvoie :**
boolean


---


### isColorVaried {#isColorVaried}

| Nom | Description |
| --- | --- |
| isColorVaried () | Spécifie que chaque repère de données dans la série a une couleur différente. Lecture/écriture boolean. |

 **Renvoie :**
boolean


---


### setBubbleSizeRepresentation {#setBubbleSizeRepresentation}

| Nom | Description |
| --- | --- |
| setBubbleSizeRepresentation (int) | Spécifie comment les valeurs de taille des bulles sont représentées sur le graphique à bulles. Lecture/écriture BubbleSizeRepresentationType. |

 **Renvoie :**
void


---


### setBubbleSizeScale {#setBubbleSizeScale}

| Nom | Description |
| --- | --- |
| setBubbleSizeScale (int) | Spécifie le facteur d’échelle pour le graphique à bulles (peut être compris entre 0 et 300 % de la taille par défaut). Lecture/écriture int. |

 **Renvoie :**
void


---


### setColorVaried {#setColorVaried}

| Nom | Description |
| --- | --- |
| setColorVaried (boolean) | Spécifie que chaque repère de données dans la série a une couleur différente. Lecture/écriture boolean. |

 **Renvoie :**
void


---


### setDoughnutHoleSize {#setDoughnutHoleSize}

| Nom | Description |
| --- | --- |
| setDoughnutHoleSize (byte) | Spécifie la taille du trou dans un graphique en anneau (peut être comprise entre 0 et 90 % de la taille de la zone de tracé). Lecture/écriture byte. |

 **Renvoie :**
void


---


### setFirstSliceAngle {#setFirstSliceAngle}

| Nom | Description |
| --- | --- |
| setFirstSliceAngle (int) | Obtient ou définit l’angle de la première tranche de graphique en secteur ou en anneau, en degrés (dans le sens des aiguilles d’une montre à partir du haut, de 0 à 360 degrés). Lecture/écriture int. |

 **Renvoie :**
void


---


### setGapDepth {#setGapDepth}

| Nom | Description |
| --- | --- |
| setGapDepth (int) | Renvoie ou définit la distance, exprimée en pourcentage de la largeur du marqueur, entre les séries de données dans un graphique 3D. Lecture/écriture int. |

 **Renvoie :**
void


---


### setGapWidth {#setGapWidth}

| Nom | Description |
| --- | --- |
| setGapWidth (int) | Spécifie l’espace entre les groupes de barres ou de colonnes, en pourcentage de la largeur de la barre ou de la colonne. Lecture/écriture int. |

 **Renvoie :**
void


---


### setOverlap {#setOverlap}

| Nom | Description |
| --- | --- |
| setOverlap (byte) | Spécifie le degré de chevauchement des barres et des colonnes sur les graphiques 2 D, en pourcentage (de -100 % à 100 %). -100 % : espacement maximal (barres complètement séparées). 0 % : barres placées côte à côte sans chevauchement ni espacement. 100 % : chevauchement maximal (barres totalement superposées). Cette propriété est en lecture/écriture byte. |

 **Renvoie :**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | Lancée lorsque la valeur est définie en dehors de l’intervalle valide de -100 à 100. |


---


### setPieSplitBy {#setPieSplitBy}

| Nom | Description |
| --- | --- |
| setPieSplitBy (int) | Spécifie comment déterminer quels points de données se trouvent dans le deuxième secteur ou la deuxième barre d’un graphique pie-of-pie ou bar-of-pie. Lecture/écriture PieSplitType. |

 **Renvoie :**
void


---


### setPieSplitPosition {#setPieSplitPosition}

| Nom | Description |
| --- | --- |
| setPieSplitPosition (double) | Spécifie une valeur qui doit être utilisée pour déterminer quels points de données se trouvent dans le deuxième secteur ou la deuxième barre d’un graphique pie-of-pie ou bar-of-pie. Utilisée conjointement avec la propriété PieSplitBy. Lecture/écriture double. |

 **Renvoie :**
void


---


### setSecondPieSize {#setSecondPieSize}

| Nom | Description |
| --- | --- |
| setSecondPieSize (int) | Spécifie la taille du deuxième secteur ou de la deuxième barre d’un graphique pie-of-pie ou bar-of-pie, en pourcentage de la taille du premier secteur (peut être comprise entre 5 et 200 %). Lecture/écriture int. |

 **Renvoie :**
void


---


### setSeriesLines {#setSeriesLines}

| Nom | Description |
| --- | --- |
| setSeriesLines (boolean) | Vrai si le graphique possède des lignes de séries. Appliqué aux graphiques à barres empilées et OfPie. Lecture/écriture boolean. |

 **Renvoie :**
void


---  