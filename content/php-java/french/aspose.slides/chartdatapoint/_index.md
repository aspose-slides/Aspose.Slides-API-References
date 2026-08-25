---
title: ChartDataPoint
second_title: Aspose.Sildes pour PHP via la référence de l'API Java
description: 
type: docs

url: /fr/aspose.slides/chartdatapoint/
---
## ChartDataPoint classe

 Représente le point de données de la série.
 
### getActualHeight {#getActualHeight}

| Nom | Description |
| --- | --- |
| getActualHeight () | Spécifie la hauteur réelle de l'élément du graphique. Appelez la méthode IChart.ValidateChartLayout() avant pour obtenir les valeurs réelles. Lecture float. |

 **Retour:**
float


---


### getActualWidth {#getActualWidth}

| Nom | Description |
| --- | --- |
| getActualWidth () | Spécifie la largeur réelle de l'élément du graphique. Appelez la méthode IChart.ValidateChartLayout() avant pour obtenir les valeurs réelles. Lecture float. |

 **Retour:**
float


---


### getActualX {#getActualX}

| Nom | Description |
| --- | --- |
| getActualX () | Spécifie la position x réelle (gauche) de l'élément du graphique par rapport au coin supérieur gauche du graphique. Appelez la méthode IChart.ValidateChartLayout() avant pour obtenir les valeurs réelles. Lecture float. |

 **Retour:**
float


---


### getActualY {#getActualY}

| Nom | Description |
| --- | --- |
| getActualY () | Spécifie le haut réel de l'élément du graphique par rapport au coin supérieur gauche du graphique. Appelez la méthode IChart.ValidateChartLayout() avant pour obtenir les valeurs réelles. Lecture float. |

 **Retour:**
float


---


### getAutomaticDataPointColor {#getAutomaticDataPointColor}

| Nom | Description |
| --- | --- |
| getAutomaticDataPointColor () | Renvoie une couleur automatique du point de données basée sur l'index de la série, l'index du point de données, la propriété ParentSeriesGroup.IsColorVaried et le style du graphique. Cette couleur est utilisée par défaut si FillType est égal à NotDefined. |

 **Retour:**
Color


---


### getBubbleSize {#getBubbleSize}

| Nom | Description |
| --- | --- |
| getBubbleSize () | BubbleSize. Lecture seule IDoubleChartValue. |

 **Retour:**
[DoubleChartValue](../doublechartvalue)


---


### getColorValue {#getColorValue}

| Nom | Description |
| --- | --- |
| getColorValue () | Renvoie la valeur de couleur du point de données du graphique. Utilisé avec les graphiques Map. Lecture seule IDoubleChartValue. |

 **Retour:**
[DoubleChartValue](../doublechartvalue)


---


### getDataPointLevels {#getDataPointLevels}

| Nom | Description |
| --- | --- |
| getDataPointLevels () | Renvoie le conteneur des niveaux de points de données. Appliqué aux séries Treeamp et Sunburst. L'indexation des niveaux de points de données commence à zéro. |

 **Retour:**
[ChartDataPointLevelsManager](../chartdatapointlevelsmanager)


---


### getErrorBarsCustomValues {#getErrorBarsCustomValues}

| Nom | Description |
| --- | --- |
| getErrorBarsCustomValues () | Représente les valeurs des barres d'erreur de la série dans le cas du type de valeur Custom. Lecture seule IErrorBarsCustomValues. |

 **Retour:**
[ErrorBarsCustomValues](../errorbarscustomvalues)


---


### getExplosion {#getExplosion}

| Nom | Description |
| --- | --- |
| getExplosion () | Spécifie la distance que le point de données doit être déplacé du centre du secteur. Lecture/écriture int. |

 **Retour:**
int


---


### getFormat {#getFormat}

| Nom | Description |
| --- | --- |
| getFormat () | Représente les propriétés de mise en forme. Lecture/écriture IFormat. |

 **Retour:**
[Format](../format)


---


### getIndex {#getIndex}

| Nom | Description |
| --- | --- |
| getIndex () |  |

 **Retour:**
long


---


### getInvertIfNegative {#getInvertIfNegative}

| Nom | Description |
| --- | --- |
| getInvertIfNegative () | Spécifie que le point de données doit inverser ses couleurs si la valeur est négative. Lecture/écriture boolean. |

 **Retour:**
boolean


---


### getLabel {#getLabel}

| Nom | Description |
| --- | --- |
| getLabel () | Label. Lecture seule IDataLabel. |

 **Retour:**
[DataLabel](../datalabel)


---


### getMarker {#getMarker}

| Nom | Description |
| --- | --- |
| getMarker () | Spécifie un marqueur de données. Lecture seule IMarker. |

 **Retour:**
[Marker](../marker)


---


### getRelatedLegendEntry {#getRelatedLegendEntry}

| Nom | Description |
| --- | --- |
| getRelatedLegendEntry () | Propriétés de l'entrée de légende correspondante dans le cas d'un type de graphique parmi cette liste : ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Lecture seule ILegendEntryProperties. |

 **Retour:**
[LegendEntryProperties](../legendentryproperties)


---


### getSetAsTotal {#getSetAsTotal}

| Nom | Description |
| --- | --- |
| getSetAsTotal () | Définit le point de données comme total. Appliqué uniquement au type de série Waterfall. |

 **Retour:**
boolean


---


### getSizeValue {#getSizeValue}

| Nom | Description |
| --- | --- |
| getSizeValue () | Renvoie la valeur de taille du point de données du graphique. Utilisé avec les graphiques Treemap et Sunburst. Lecture seule IDoubleChartValue. |

 **Retour:**
[DoubleChartValue](../doublechartvalue)


---


### getValue {#getValue}

| Nom | Description |
| --- | --- |
| getValue () | Value. Lecture seule IDoubleChartValue. |

 **Retour:**
[DoubleChartValue](../doublechartvalue)


---


### getXValue {#getXValue}

| Nom | Description |
| --- | --- |
| getXValue () | XValue. Lecture seule IStringOrDoubleChartValue. |

 **Retour:**
[StringOrDoubleChartValue](../stringordoublechartvalue)


---


### getYValue {#getYValue}

| Nom | Description |
| --- | --- |
| getYValue () | YValue. Lecture seule IDoubleChartValue. |

 **Retour:**
[DoubleChartValue](../doublechartvalue)


---


### isBubble3D {#isBubble3D}

| Nom | Description |
| --- | --- |
| isBubble3D () | Spécifie que les bulles ont un effet 3-D appliqué. Lecture/écriture boolean. |

 **Retour:**
boolean


---


### remove {#remove}

| Nom | Description |
| --- | --- |
| remove () | Supprime le DataPoint de la série du graphique. |

 **Retour:**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
| PptxEditException | Lancée si le point de données a déjà été supprimé de la série du graphique. |


---


### setBubble3D {#setBubble3D}

| Nom | Description |
| --- | --- |
| setBubble3D (boolean) | Spécifie que les bulles ont un effet 3-D appliqué. Lecture/écriture boolean. |

 **Retour:**
void


---


### setExplosion {#setExplosion}

| Nom | Description |
| --- | --- |
| setExplosion (int) | Spécifie la distance que le point de données doit être déplacé du centre du secteur. Lecture/écriture int. |

 **Retour:**
void


---


### setFormat {#setFormat}

| Nom | Description |
| --- | --- |
| setFormat ([Format](../format)) | Représente les propriétés de mise en forme. Lecture/écriture IFormat. |

 **Retour:**
void


---


### setInvertIfNegative {#setInvertIfNegative}

| Nom | Description |
| --- | --- |
| setInvertIfNegative (boolean) | Spécifie que le point de données doit inverser ses couleurs si la valeur est négative. Lecture/écriture boolean. |

 **Retour:**
void


---


### setSetAsTotal {#setSetAsTotal}

| Nom | Description |
| --- | --- |
| setSetAsTotal (boolean) | Définit le point de données comme total. Appliqué uniquement au type de série Waterfall. |

 **Retour:**
void


---