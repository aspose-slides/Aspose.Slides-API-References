---
title: ChartSeries
second_title: Aspose.Sildes pour PHP via la référence de l'API Java
description: 
type: docs

url: /fr/aspose.slides/chartseries/
---
## ChartSeries classe

 Représente une série de graphique.
 
### getAutomaticSeriesColor {#getAutomaticSeriesColor}

| Nom | Description |
| --- | --- |
| getAutomaticSeriesColor () | Renvoie une couleur automatique de la série basée sur l'index de la série et le style du graphique. Cette couleur est utilisée par défaut si FillType vaut NotDefined. |

 **Renvoie:**  
Color


---


### getBar3DShape {#getBar3DShape}

| Nom | Description |
| --- | --- |
| getBar3DShape () | Spécifie la forme d'une série d'un histogramme 3-D. Modifier la valeur de cette propriété peut entraîner un changement automatique du Type de la série. Lecture/écriture ChartShapeType. |

 **Renvoie:**  
int


---


### getBubbleSizeRepresentation {#getBubbleSizeRepresentation}

| Nom | Description |
| --- | --- |
| getBubbleSizeRepresentation () | Spécifie comment les valeurs de taille des bulles sont représentées sur le graphique à bulles. Il s'agit de la propriété non seulement de cette série mais de toutes les séries du groupe de séries parent – il s'agit d'une projection de la propriété de groupe appropriée. Ainsi, cette propriété est lecture-seule. Utilisez la propriété ParentSeriesGroup pour accéder au groupe de séries parent. Utilisez la propriété ParentSeriesGroup.BubbleSizeRepresentation lecture/écriture pour modifier la valeur. Il s'agit de la projection de la propriété ParentSeriesGroup.BubbleSizeRepresentation. |

 **Renvoie:**  
int


---


### getBubbleSizeScale {#getBubbleSizeScale}

| Nom | Description |
| --- | --- |
| getBubbleSizeScale () | Spécifie le facteur d'échelle pour le graphique à bulles (peut être compris entre 0 et 300 % de la taille par défaut). Il s'agit de la propriété non seulement de cette série mais de toutes les séries du groupe de séries parent – il s'agit d'une projection de la propriété de groupe appropriée. Ainsi, cette propriété est lecture-seule. Utilisez la propriété ParentSeriesGroup pour accéder au groupe de séries parent. Utilisez la propriété ParentSeriesGroup.BubbleSizeScale lecture/écriture pour modifier la valeur. Il s'agit de la projection de la propriété ParentSeriesGroup.BubbleSizeScale. |

 **Renvoie:**  
int


---


### getChart {#getChart}

| Nom | Description |
| --- | --- |
| getChart () | Renvoie le graphique parent. Lecture-seule IChart. |

 **Renvoie:**  
[Chart](../chart)


---


### getDataPoints {#getDataPoints}

| Nom | Description |
| --- | --- |
| getDataPoints () | Renvoie la collection de points de données de cette série. Lecture-seule IChartDataPointCollection. |

 **Renvoie:**  
[ChartDataPointCollection](../chartdatapointcollection)


---


### getDoughnutHoleSize {#getDoughnutHoleSize}

| Nom | Description |
| --- | --- |
| getDoughnutHoleSize () | Spécifie la taille du trou dans un graphique en beignet (peut être comprise entre 10 et 90 % de la taille de la zone de tracé). Il s'agit de la propriété non seulement de cette série mais de toutes les séries du groupe de séries parent – il s'agit d'une projection de la propriété de groupe appropriée. Ainsi, cette propriété est lecture-seule. Utilisez la propriété ParentSeriesGroup pour accéder au groupe de séries parent. Utilisez la propriété ParentSeriesGroup.DoughnutHoleSize lecture/écriture pour modifier la valeur. Lecture-seule byte. Il s'agit de la projection de la propriété ParentSeriesGroup.DoughnutHoleSize. |

 **Renvoie:**  
byte


---


### getErrorBarsXFormat {#getErrorBarsXFormat}

| Nom | Description |
| --- | --- |
| getErrorBarsXFormat () | Représente les ErrorBars de la série avec direction X. Lecture-seule IErrorBarsFormat. Les ErrorBars avec direction X sont disponibles pour les séries de type area, bar, scatter et bubble. Pour tout autre type de graphique, cette propriété renvoie null (y compris les graphiques 3D). En cas de valeurs personnalisées, utilisez la collection DataPoints pour spécifier la valeur (avec la propriété ( IChartDataPoint#getErrorBarsCustomValues)). |

 **Renvoie:**  
[ErrorBarsFormat](../errorbarsformat)


---


### getErrorBarsYFormat {#getErrorBarsYFormat}

| Nom | Description |
| --- | --- |
| getErrorBarsYFormat () | Représente les ErrorBars de la série avec direction Y. Lecture-seule IErrorBarsFormat. Les ErrorBars avec direction Y sont disponibles pour les séries de type area, bar, line, scatter et bubble. Pour tout autre type de graphique, cette propriété renvoie null (y compris les graphiques 3D). En cas de valeurs personnalisées, utilisez la collection DataPoints pour spécifier la valeur (avec la propriété ( IChartDataPoint#getErrorBarsCustomValues)). |

 **Renvoie:**  
[ErrorBarsFormat](../errorbarsformat)


---


### getExplosion {#getExplosion}

| Nom | Description |
| --- | --- |
| getExplosion () | La distance d'une part de tarte ouverte par rapport au centre du graphique circulaire est exprimée en pourcentage du diamètre de la tarte. Lecture/écriture int. |

 **Renvoie:**  
int


---


### getFirstSliceAngle {#getFirstSliceAngle}

| Nom | Description |
| --- | --- |
| getFirstSliceAngle () | Spécifie l'angle de la première part du graphique circulaire ou du beignet, en degrés (dans le sens des aiguilles d'une montre depuis le haut, de 0 à 360 degrés). Il s'agit de la propriété non seulement de cette série mais de toutes les séries du groupe de séries parent – il s'agit d'une projection de la propriété de groupe appropriée. Ainsi, cette propriété est lecture-seule. Utilisez la propriété ParentSeriesGroup pour accéder au groupe de séries parent. Utilisez la propriété ParentSeriesGroup.FirstSliceAngle lecture/écriture pour modifier la valeur. Lecture-seule int. Il s'agit de la projection de la propriété ParentSeriesGroup.FirstSliceAngle. |

 **Renvoie:**  
int


---


### getFormat {#getFormat}

| Nom | Description |
| --- | --- |
| getFormat () | Renvoie le format d'une série. Lecture-seule IFormat. |

 **Renvoie:**  
[Format](../format)


---


### getGapDepth {#getGapDepth}

| Nom | Description |
| --- | --- |
| getGapDepth () | Renvoie ou définit la distance, exprimée en pourcentage de la largeur du repère, entre les séries de données dans un graphique 3D. Il s'agit de la propriété non seulement de cette série mais de toutes les séries du groupe de séries parent – il s'agit d'une projection de la propriété de groupe appropriée. Ainsi, cette propriété est lecture-seule. Utilisez la propriété ParentSeriesGroup pour accéder au groupe de séries parent. Utilisez la propriété ParentSeriesGroup.GapDepth lecture/écriture pour modifier la valeur. Lecture-seule int. Il s'agit de la projection de la propriété ParentSeriesGroup.GapDepth. |

 **Renvoie:**  
int


---


### getGapWidth {#getGapWidth}

| Nom | Description |
| --- | --- |
| getGapWidth () | Spécifie l'espace entre les groupes de barres ou de colonnes, exprimé en pourcentage de la largeur de la barre ou de la colonne. Il s'agit de la propriété non seulement de cette série mais de toutes les séries du groupe de séries parent – il s'agit d'une projection de la propriété de groupe appropriée. Ainsi, cette propriété est lecture-seule. Utilisez la propriété ParentSeriesGroup pour accéder au groupe de séries parent. Utilisez la propriété ParentSeriesGroup.GapWidth lecture/écriture pour modifier la valeur. Lecture-seule int. Il s'agit de la projection de la propriété ParentSeriesGroup.GapWidth. |

 **Renvoie:**  
int


---


### getInvertIfNegative {#getInvertIfNegative}

| Nom | Description |
| --- | --- |
| getInvertIfNegative () | Spécifie que la série de barres, de colonnes ou de bulles doit inverser ses couleurs si la valeur est négative. Lecture/écriture boolean. |

 **Renvoie:**  
boolean


---


### getInvertedSolidFillColor {#getInvertedSolidFillColor}

| Nom | Description |
| --- | --- |
| getInvertedSolidFillColor () | Spécifie la couleur solide inversée pour la série. Pour appliquer ce réglage, définissez le type de remplissage de la série sur FillType.Solid. Lecture/écriture ColorFormat. |

 **Renvoie:**  
[ColorFormat](../colorformat)


---


### getLabels {#getLabels}

| Nom | Description |
| --- | --- |
| getLabels () | Renvoie les Labels d'une série. Lecture-seule IDataLabelCollection. |

 **Renvoie:**  
[DataLabelCollection](../datalabelcollection)


---


### getMarker {#getMarker}

| Nom | Description |
| --- | --- |
| getMarker () | Marker. Lecture-seule IMarker. |

 **Renvoie:**  
[Marker](../marker)


---


### getName {#getName}

| Nom | Description |
| --- | --- |
| getName () | Renvoie le nom de la série. Lecture-seule IStringChartValue. |

 **Renvoie:**  
[StringChartValue](../stringchartvalue)


---


### getNumberFormatOfBubbleSizes {#getNumberFormatOfBubbleSizes}

| Nom | Description |
| --- | --- |
| getNumberFormatOfBubbleSizes () | NumberFormatOfBubbleSizes. Lecture/écriture String. |

 **Renvoie:**  
String


---


### getNumberFormatOfValues {#getNumberFormatOfValues}

| Nom | Description |
| --- | --- |
| getNumberFormatOfValues () | NumberFormatOfValues. Lecture/écriture String. |

 **Renvoie:**  
String


---


### getNumberFormatOfXValues {#getNumberFormatOfXValues}

| Nom | Description |
| --- | --- |
| getNumberFormatOfXValues () | NumberFormatOfXValues. Lecture/écriture String. |

 **Renvoie:**  
String


---


### getNumberFormatOfYValues {#getNumberFormatOfYValues}

| Nom | Description |
| --- | --- |
| getNumberFormatOfYValues () | NumberFormatOfYValues. Lecture/écriture String. |

 **Renvoie:**  
String


---


### getOrder {#getOrder}

| Nom | Description |
| --- | --- |
| getOrder () | Renvoie l'ordre d'une série. Lecture/écriture int. |

 **Renvoie:**  
int


---


### getOverlap {#getOverlap}

| Nom | Description |
| --- | --- |
| getOverlap () | Spécifie dans quelle mesure les barres et les colonnes se chevauchent sur les graphiques 2-D, en pourcentage (de -100 % à 100 %). Il s'agit de la propriété non seulement de cette série mais de toutes les séries du groupe de séries parent. C'est une projection de la propriété appropriée dans le groupe de séries parent, ainsi cette propriété est lecture-seule. Pour modifier la valeur, utilisez la propriété ParentSeriesGroup.Overlap lecture/écriture. Lecture-seule byte. Overlap indique le degré de chevauchement ou d'espacement entre les barres et les colonnes en pourcentage de leur largeur : - -100 % : espacement maximal (barres complètement séparées). - 0 % : barres placées côte à côte sans chevauchement ni espacement. - 100 % : chevauchement maximal (barres se superposent entièrement). C'est une projection de la propriété ParentSeriesGroup.Overlap. |

 **Renvoie:**  
byte


---


### getParentLabelLayout {#getParentLabelLayout}

| Nom | Description |
| --- | --- |
| getParentLabelLayout () | Représente la disposition des libellés de catégorie parent. S'applique uniquement aux graphiques Treemap. |

 **Renvoie:**  
int


---


### getParentSeriesGroup {#getParentSeriesGroup}

| Nom | Description |
| --- | --- |
| getParentSeriesGroup () | ParentSeriesGroup. Lecture-seule IChartSeriesGroup. |

 **Renvoie:**  
[ChartSeriesGroup](../chartseriesgroup)


---


### getPieSplitBy {#getPieSplitBy}

| Nom | Description |
| --- | --- |
| getPieSplitBy () | Spécifie comment déterminer quels points de données se trouvent dans la deuxième part ou la deuxième barre d'un graphique « pie-of-pie » ou « bar-of-pie ». Il s'agit de la propriété non seulement de cette série mais de toutes les séries du groupe de séries parent – il s'agit d'une projection de la propriété de groupe appropriée. Ainsi, cette propriété est lecture-seule. Utilisez la propriété ParentSeriesGroup pour accéder au groupe de séries parent. Utilisez la propriété ParentSeriesGroup.PieSplitBy lecture/écriture pour modifier la valeur. Lecture-seule PieSplitType. 1) Il s'agit de la projection de la propriété ParentSeriesGroup.PieSplitBy. 2) Si la valeur de la propriété est PieSplitType.Custom, vous pouvez définir des informations de séparation personnalisées avec la propriété ParentSeriesGroup.PieSplitCustomPoints. |

 **Renvoie:**  
int


---


### getPieSplitCustomPoints {#getPieSplitCustomPoints}

| Nom | Description |
| --- | --- |
| getPieSplitCustomPoints () | Les informations de séparation personnalisées pour un graphique « pie-of-pie » ou « bar-of-pie » avec une séparation personnalisée. Contient les points de données qui doivent être dessinés dans la deuxième part ou la deuxième barre. Il s'agit de la propriété non seulement de cette série mais de toutes les séries du groupe de séries parent – il s'agit d'une projection de la propriété de groupe appropriée. Lecture-seule PieSplitCustomPointCollection. Il s'agit de la projection de la propriété ParentSeriesGroup.PieSplitCustomPoints. |

 **Renvoie:**  
[PieSplitCustomPointCollection](../piesplitcustompointcollection)


---


### getPieSplitPosition {#getPieSplitPosition}

| Nom | Description |
| --- | --- |
| getPieSplitPosition () | Spécifie une valeur qui doit être utilisée pour déterminer quels points de données se trouvent dans la deuxième part ou la deuxième barre d'un graphique « pie-of-pie » ou « bar-of-pie ». Utilisée conjointement avec la propriété PieSplitBy. Il s'agit de la propriété non seulement de cette série mais de toutes les séries du groupe de séries parent – il s'agit d'une projection de la propriété de groupe appropriée. Ainsi, cette propriété est lecture-seule. Utilisez la propriété ParentSeriesGroup pour accéder au groupe de séries parent. Utilisez la propriété ParentSeriesGroup.PieSplitPosition lecture/écriture pour modifier la valeur. Lecture-seule double. Il s'agit de la projection de la propriété ParentSeriesGroup.PieSplitPosition. |

 **Renvoie:**  
double


---


### getPlotOnSecondAxis {#getPlotOnSecondAxis}

| Nom | Description |
| --- | --- |
| getPlotOnSecondAxis () | Indique si cette série est tracée sur l'axe secondaire. Lecture/écriture boolean. |

 **Renvoie:**  
boolean


---


### getPresentation {#getPresentation}
| --- | --- |
| getPresentation () | Renvoie la présentation parente d'un FillFormat. Lecture seule IPresentation. |

**Renvoie:**  
[Presentation](../presentation)

---

### getQuartileMethod {#getQuartileMethod}

| Nom | Description |
| --- | --- |
| getQuartileMethod () | Représente la méthode du quartile. S'applique uniquement aux graphiques BoxAndWhisker. |

**Renvoie:**  
int

---

### getRelatedLegendEntry {#getRelatedLegendEntry}

| Nom | Description |
| --- | --- |
| getRelatedLegendEntry () | Représente l'entrée de légende liée à cette série. Lecture seule ILegendEntryProperties. |

**Renvoie:**  
[LegendEntryProperties](../legendentryproperties)

---

### getSecondPieSize {#getSecondPieSize}

| Nom | Description |
| --- | --- |
| getSecondPieSize () | Spécifie la taille du deuxième secteur ou barre d'un graphique camembert-camembert ou d'un graphique barre-camembert, en pourcentage de la taille du premier secteur (peut être entre 5 et 200 pourcent). Il s'agit de la propriété non seulement de cette série mais de toutes les séries du groupe de séries parent – il s'agit de la projection de la propriété de groupe appropriée. Ainsi cette propriété est en lecture seule. Utilisez la propriété ParentSeriesGroup pour accéder au groupe de séries parent. Utilisez la propriété ParentSeriesGroup.SecondPieSize en lecture/écriture pour modifier la valeur. Lecture seule int. Il s'agit de la projection de la propriété ParentSeriesGroup.SecondPieSize. |

**Renvoie:**  
int

---

### getShowConnectorLines {#getShowConnectorLines}

| Nom | Description |
| --- | --- |
| getShowConnectorLines () | Représente les lignes de connexion. S'applique uniquement aux graphiques Waterfall. |

**Renvoie:**  
boolean

---

### getShowInnerPoints {#getShowInnerPoints}

| Nom | Description |
| --- | --- |
| getShowInnerPoints () | Représente les points intérieurs. True si les points intérieurs sont affichés sur le graphique BoxAndWhisker. S'applique uniquement aux graphiques BoxAndWhisker. Lecture/écriture boolean. |

**Renvoie:**  
boolean

---

### getShowMeanLine {#getShowMeanLine}

| Nom | Description |
| --- | --- |
| getShowMeanLine () | Représente la ligne de moyenne. True si la ligne de moyenne est affichée sur le graphique BoxAndWhisker. S'applique uniquement aux graphiques BoxAndWhisker. Lecture/écriture boolean. |

**Renvoie:**  
boolean

---

### getShowMeanMarkers {#getShowMeanMarkers}

| Nom | Description |
| --- | --- |
| getShowMeanMarkers () | Représente les marqueurs de moyenne. True si les marqueurs de moyenne sont affichés sur le graphique BoxAndWhisker. S'applique uniquement aux graphiques BoxAndWhisker. Lecture/écriture boolean. |

**Renvoie:**  
boolean

---

### getShowOutlierPoints {#getShowOutlierPoints}

| Nom | Description |
| --- | --- |
| getShowOutlierPoints () | Représente les points aberrants. True si les points aberrants sont affichés sur le graphique BoxAndWhisker. S'applique uniquement aux graphiques BoxAndWhisker. Lecture/écriture boolean. |

**Renvoie:**  
boolean

---

### getSlide {#getSlide}

| Nom | Description |
| --- | --- |
| getSlide () | Renvoie la diapositive parente d'un FillFormat. Lecture seule BaseSlide. |

**Renvoie:**  
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)

---

### getSmooth {#getSmooth}

| Nom | Description |
| --- | --- |
| getSmooth () | Représente le lissage de courbe. True si le lissage de courbe est activé pour le graphique en ligne ou le graphique nuage de points. S'applique uniquement aux graphiques en ligne et nuage de points connectés par des lignes. Lecture/écriture boolean. |

**Renvoie:**  
boolean

---

### getTrendLines {#getTrendLines}

| Nom | Description |
| --- | --- |
| getTrendLines () | Collection de lignes de tendance de séries. Lecture seule ITrendlineCollection. Les TrendLines sont disponibles (non null) pour les séries de données dans les graphiques 2-D zone, barre, colonne, ligne, actions, xy (nuage de points) et bulles non empilés. Une ligne de tendance n'est pas disponible pour les séries de données dans tout type de graphique empilé ou 3-D. Les Trendlines ne sont également pas disponibles pour les graphiques radar, camembert, surface ou doughnut. |

**Renvoie:**  
[TrendlineCollection](../trendlinecollection)

---

### getType {#getType}

| Nom | Description |
| --- | --- |
| getType () | Renvoie un type de cette série. Lecture/écriture ChartType. |

**Renvoie:**  
int

---

### hasSeriesLines {#hasSeriesLines}

| Nom | Description |
| --- | --- |
| hasSeriesLines () | Détermine s'il existe des lignes de séries pour cette série et les séries apparentées. Il s'agit de la propriété non seulement de cette série mais de toutes les séries du groupe de séries parent – il s'agit de la projection de la propriété de groupe appropriée. Ainsi cette propriété est en lecture seule. Utilisez la propriété ParentSeriesGroup pour accéder au groupe de séries parent. Utilisez la propriété ParentSeriesGroup.HasSeriesLines en lecture/écriture pour modifier la valeur. Utilisez la propriété ParentSeriesGroup.SeriesLinesFormat pour le format des lignes de séries. Lecture seule boolean. Il s'agit de la projection de la propriété ParentSeriesGroup.HasSeriesLines. |

**Renvoie:**  
boolean

---

### hasUpDownBars {#hasUpDownBars}

| Nom | Description |
| --- | --- |
| hasUpDownBars () | Détermine si le graphique Line ou Stock possède des barres haut/bas. Il s'agit de la propriété non seulement de cette série mais de toutes les séries du groupe de séries parent – il s'agit de la projection de la propriété de groupe appropriée. Ainsi cette propriété est en lecture seule. Utilisez la propriété ParentSeriesGroup pour accéder au groupe de séries parent. Utilisez la propriété ParentSeriesGroup.UpDownBars.HasUpDownBars en lecture/écriture pour modifier la valeur. Utilisez la propriété ParentSeriesGroup.UpDownBars pour le format des barres haut/bas. Lecture seule boolean. Il s'agit de la projection de la propriété ParentSeriesGroup.UpDownBars.HasUpDownBars. |

**Renvoie:**  
boolean

---

### isColorVaried {#isColorVaried}

| Nom | Description |
| --- | --- |
| isColorVaried () | Spécifie que chaque marqueur de données de la série a une couleur différente. Il s'agit de la propriété non seulement de cette série mais de toutes les séries du groupe de séries parent – il s'agit de la projection de la propriété de groupe appropriée. Ainsi cette propriété est en lecture seule. Utilisez la propriété ParentSeriesGroup pour accéder au groupe de séries parent. Utilisez la propriété ParentSeriesGroup.IsColorVaried en lecture/écriture pour modifier la valeur. Lecture seule boolean. Il s'agit de la projection de la propriété ParentSeriesGroup.IsColorVaried. |

**Renvoie:**  
boolean

---

### setBar3DShape {#setBar3DShape}

| Nom | Description |
| --- | --- |
| setBar3DShape (int) | Spécifie la forme d'une série d'un graphique à barres 3-D. Modifier la valeur de cette propriété peut entraîner un changement automatique du Type de la série. Lecture/écriture ChartShapeType. |

**Renvoie:**  
void

---

### setExplosion {#setExplosion}

| Nom | Description |
| --- | --- |
| setExplosion (int) | La distance d'une part de camembert ouverte du centre du graphique camembert est exprimée en pourcentage du diamètre du camembert. Lecture/écriture int. |

**Renvoie:**  
void

---

### setInvertIfNegative {#setInvertIfNegative}

| Nom | Description |
| --- | --- |
| setInvertIfNegative (boolean) | Spécifie que la série de barres, de colonnes ou de bulles doit inverser ses couleurs si la valeur est négative. Lecture/écriture boolean. |

**Renvoie:**  
void

---

### setNumberFormatOfBubbleSizes {#setNumberFormatOfBubbleSizes}

| Nom | Description |
| --- | --- |
| setNumberFormatOfBubbleSizes (String) | NumberFormatOfBubbleSizes. Lecture/écriture String. |

**Renvoie:**  
void

---

### setNumberFormatOfValues {#setNumberFormatOfValues}

| Nom | Description |
| --- | --- |
| setNumberFormatOfValues (String) | NumberFormatOfValues. Lecture/écriture String. |

**Renvoie:**  
void

---

### setNumberFormatOfXValues {#setNumberFormatOfXValues}

| Nom | Description |
| --- | --- |
| setNumberFormatOfXValues (String) | NumberFormatOfXValues. Lecture/écriture String. |

**Renvoie:**  
void

---

### setNumberFormatOfYValues {#setNumberFormatOfYValues}

| Nom | Description |
| --- | --- |
| setNumberFormatOfYValues (String) | NumberFormatOfYValues. Lecture/écriture String. |

**Renvoie:**  
void

---

### setOrder {#setOrder}

| Nom | Description |
| --- | --- |
| setOrder (int) | Renvoie l'ordre d'une série. Lecture/écriture int. |

**Renvoie:**  
void

---

### setParentLabelLayout {#setParentLabelLayout}

| Nom | Description |
| --- | --- |
| setParentLabelLayout (int) | Représente la disposition des étiquettes de catégorie parent. S'applique uniquement aux graphiques Treemap. |

**Renvoie:**  
void

---

### setPlotOnSecondAxis {#setPlotOnSecondAxis}

| Nom | Description |
| --- | --- |
| setPlotOnSecondAxis (boolean) | Indique si cette série est tracée sur l'axe secondaire. Lecture/écriture boolean. |

**Renvoie:**  
void

---

### setQuartileMethod {#setQuartileMethod}

| Nom | Description |
| --- | --- |
| setQuartileMethod (int) | Représente la méthode du quartile. S'applique uniquement aux graphiques BoxAndWhisker. |

**Renvoie:**  
void

---

### setShowConnectorLines {#setShowConnectorLines}

| Nom | Description |
| --- | --- |
| setShowConnectorLines (boolean) | Représente les lignes de connexion. S'applique uniquement aux graphiques Waterfall. |

**Renvoie:**  
void

---

### setShowInnerPoints {#setShowInnerPoints}

| Nom | Description |
| --- | --- |
| setShowInnerPoints (boolean) | Représente les points intérieurs. True si les points intérieurs sont affichés sur le graphique BoxAndWhisker. S'applique uniquement aux graphiques BoxAndWhisker. Lecture/écriture boolean. |

**Renvoie:**  
void

---

### setShowMeanLine {#setShowMeanLine}

| Nom | Description |
| --- | --- |
| setShowMeanLine (boolean) | Représente la ligne de moyenne. True si la ligne de moyenne est affichée sur le graphique BoxAndWhisker. S'applique uniquement aux graphiques BoxAndWhisker. Lecture/écriture boolean. |

**Renvoie:**  
void

---

### setShowMeanMarkers {#setShowMeanMarkers}

| Nom | Description |
| --- | --- |
| setShowMeanMarkers (boolean) | Représente les marqueurs de moyenne. True si les marqueurs de moyenne sont affichés sur le graphique BoxAndWhisker. S'applique uniquement aux graphiques BoxAndWhisker. Lecture/écriture boolean. |

**Renvoie:**  
void

---

### setShowOutlierPoints {#setShowOutlierPoints}

| Nom | Description |
| --- | --- |
| setShowOutlierPoints (boolean) | Représente les points aberrants. True si les points aberrants sont affichés sur le graphique BoxAndWhisker. S'applique uniquement aux graphiques BoxAndWhisker. Lecture/écriture boolean. |

**Renvoie:**  
void

---

### setSmooth {#setSmooth}

| Nom | Description |
| --- | --- |
| setSmooth (boolean) | Représente le lissage de courbe. True si le lissage de courbe est activé pour le graphique en ligne ou le graphique nuage de points. S'applique uniquement aux graphiques en ligne et nuage de points connectés par des lignes. Lecture/écriture boolean. |

**Renvoie:**  
void

---

### setType {#setType}

| Nom | Description |
| --- | --- |
| setType (int) | Renvoie un type de cette série. Lecture/écriture ChartType. |

**Renvoie:**  
void

---