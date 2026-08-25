---
title: Axis
second_title: Aspose.Sildes pour PHP via la référence d'API Java
description: 
type: docs
url: /fr/aspose.slides/axis/
---
## Classe Axis

 Encapsule l'objet qui représente l'axe d'un graphique.
 
### getActualMajorUnit {#getActualMajorUnit}

| Nom | Description |
| --- | --- |
| getActualMajorUnit () | Spécifie l'unité principale réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() auparavant pour obtenir la valeur réelle. |

 **Renvoie :** 
double


---


### getActualMajorUnitScale {#getActualMajorUnitScale}

| Nom | Description |
| --- | --- |
| getActualMajorUnitScale () | Spécifie l'échelle de l'unité principale réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() auparavant pour obtenir la valeur réelle. |

 **Renvoie :** 
int


---


### getActualMaxValue {#getActualMaxValue}

| Nom | Description |
| --- | --- |
| getActualMaxValue () | Spécifie la valeur maximale réelle sur l'axe. Appelez la méthode IChart.ValidateChartLayout() auparavant pour obtenir la valeur réelle. |

 **Renvoie :** 
double


---


### getActualMinValue {#getActualMinValue}

| Nom | Description |
| --- | --- |
| getActualMinValue () | Spécifie la valeur minimale réelle sur l'axe. Appelez la méthode IChart.ValidateChartLayout() auparavant pour obtenir la valeur réelle. |

 **Renvoie :** 
double


---


### getActualMinorUnit {#getActualMinorUnit}

| Nom | Description |
| --- | --- |
| getActualMinorUnit () | Spécifie l'unité secondaire réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() auparavant pour obtenir la valeur réelle. |

 **Renvoie :** 
double


---


### getActualMinorUnitScale {#getActualMinorUnitScale}

| Nom | Description |
| --- | --- |
| getActualMinorUnitScale () | Spécifie l'échelle de l'unité secondaire réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() auparavant pour obtenir la valeur réelle. |

 **Renvoie :** 
int


---


### getAggregationType {#getAggregationType}

| Nom | Description |
| --- | --- |
| getAggregationType () | Représente le type d'agrégation de l'axe des catégories (groupement). Appliqué aux catégories. Utilisé uniquement avec les séries Histogram ou HistogramPareto. |

 **Renvoie :** 
int


---


### getAxisBetweenCategories {#getAxisBetweenCategories}

| Nom | Description |
| --- | --- |
| getAxisBetweenCategories () | Indique si l'axe des valeurs croise l'axe des catégories entre les catégories. Cette propriété s'applique uniquement aux axes de catégorie et ne s'applique pas aux graphiques 3-D. Lecture/écriture booléen. |

 **Renvoie :** 
boolean


---


### getBaseUnitScale {#getBaseUnitScale}

| Nom | Description |
| --- | --- |
| getBaseUnitScale () | Spécifie la plus petite unité de temps représentée sur l'axe de date. Lecture/écriture TimeUnitType. |

 **Renvoie :** 
int


---


### getBinWidth {#getBinWidth}

| Nom | Description |
| --- | --- |
| getBinWidth () | Spécifie la largeur du bin lorsque la valeur de la propriété AggregationType est définie sur AxisAggregationType.ByBinWidth. Appliqué aux axes de catégorie. Utilisé uniquement avec les séries Histogram ou HistogramPareto. |

 **Renvoie :** 
double


---


### getCategoryAxisType {#getCategoryAxisType}

| Nom | Description |
| --- | --- |
| getCategoryAxisType () | Spécifie le type de l'axe de catégorie. Lecture/écriture CategoryAxisType. |

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


### getCrossAt {#getCrossAt}

| Nom | Description |
| --- | --- |
| getCrossAt () | Représente le point sur l'axe où l'axe perpendiculaire le croise. Lecture/écriture float. |

 **Renvoie :** 
float


---


### getCrossType {#getCrossType}

| Nom | Description |
| --- | --- |
| getCrossType () | Représente le CrossType sur l'axe spécifié où l'autre axe le croise. Lecture/écriture CrossesType. |

 **Renvoie :** 
int


---


### getDisplayUnit {#getDisplayUnit}

| Nom | Description |
| --- | --- |
| getDisplayUnit () | Spécifie la valeur de mise à l'échelle des unités d'affichage pour l'axe des valeurs. Lecture/écriture DisplayUnitType. |

 **Renvoie :** 
int


---


### getFormat {#getFormat}

| Nom | Description |
| --- | --- |
| getFormat () | Représente le format de l'axe. Lecture seule IAxisFormat. |

 **Renvoie :** 
[AxisFormat](../axisformat)


---


### getLabelOffset {#getLabelOffset}

| Nom | Description |
| --- | --- |
| getLabelOffset () | Spécifie la distance des étiquettes par rapport à l'axe. Appliqué à l'axe de catégorie ou de date. La valeur doit être comprise entre 0 % et 1000 %. Lecture/écriture int. |

 **Renvoie :** 
int


---


### getLogBase {#getLogBase}

| Nom | Description |
| --- | --- |
| getLogBase () | Représente la base logarithmique. La valeur par défaut est 10. Lecture/écriture double. |

 **Renvoie :** 
double


---


### getMajorGridLinesFormat {#getMajorGridLinesFormat}

| Nom | Description |
| --- | --- |
| getMajorGridLinesFormat () | Représente le format des lignes de grille majeures sur un axe de graphique. Lecture seule IChartLinesFormat. |

 **Renvoie :** 
[ChartLinesFormat](../chartlinesformat)


---


### getMajorTickMark {#getMajorTickMark}

| Nom | Description |
| --- | --- |
| getMajorTickMark () | Représente le type de marque de graduation majeure pour l'axe spécifié. Lecture/écriture TickMarkType. |

 **Renvoie :** 
int


---


### getMajorUnit {#getMajorUnit}

| Nom | Description |
| --- | --- |
| getMajorUnit () | Représente les unités majeures pour l'axe de date ou de valeur. Lecture/écriture double. |

 **Renvoie :** 
double


---


### getMajorUnitScale {#getMajorUnitScale}

| Nom | Description |
| --- | --- |
| getMajorUnitScale () | Représente l'échelle de l'unité majeure pour l'axe de date. Lecture/écriture TimeUnitType. |

 **Renvoie :** 
int


---


### getMaxValue {#getMaxValue}

| Nom | Description |
| --- | --- |
| getMaxValue () | Représente la valeur maximale sur l'axe des valeurs. Lecture/écriture double. |

 **Renvoie :** 
double


---


### getMinValue {#getMinValue}

| Nom | Description |
| --- | --- |
| getMinValue () | Représente la valeur minimale sur l'axe des valeurs. Lecture/écriture double. |

 **Renvoie :** 
double


---


### getMinorGridLinesFormat {#getMinorGridLinesFormat}

| Nom | Description |
| --- | --- |
| getMinorGridLinesFormat () | Représente le format des lignes de grille mineures sur un axe de graphique. Lecture seule IChartLinesFormat. |

 **Renvoie :** 
[ChartLinesFormat](../chartlinesformat)


---


### getMinorTickMark {#getMinorTickMark}

| Nom | Description |
| --- | --- |
| getMinorTickMark () | Représente le type de marque de graduation mineure pour l'axe spécifié. Lecture/écriture TickMarkType. |

 **Renvoie :** 
int


---


### getMinorUnit {#getMinorUnit}

| Nom | Description |
| --- | --- |
| getMinorUnit () | Représente les unités mineures pour l'axe de date ou de valeur. Lecture/écriture double. |

 **Renvoie :** 
double


---


### getMinorUnitScale {#getMinorUnitScale}

| Nom | Description |
| --- | --- |
| getMinorUnitScale () | Représente l'échelle de l'unité majeure pour l'axe de date. Lecture/écriture TimeUnitType. |

 **Renvoie :** 
int


---


### getNumberFormat {#getNumberFormat}

| Nom | Description |
| --- | --- |
| getNumberFormat () | Représente la chaîne de format pour les libellés d'axe. Lecture/écriture String. |

 **Renvoie :** 
String


---


### getNumberOfBins {#getNumberOfBins}

| Nom | Description |
| --- | --- |
| getNumberOfBins () | Spécifie le nombre de bins lorsque la valeur de la propriété AggregationType est définie sur AxisAggregationType.ByNumberOfBins. Appliqué aux axes de catégorie. Utilisé uniquement avec les séries Histogram ou HistogramPareto. |

 **Renvoie :** 
long


---


### getOverflowBin {#getOverflowBin}

| Nom | Description |
| --- | --- |
| getOverflowBin () | Spécifie la valeur personnalisée du bin de dépassement. Appliqué lorsque la propriété IsAutomaticOverflowBin est définie sur false et que la propriété IsOverflowBin vaut true. |

 **Renvoie :** 
double


---


### getPosition {#getPosition}

| Nom | Description |
| --- | --- |
| getPosition () | Représente la position de l'axe. Lecture/écriture AxisPositionType. |

 **Renvoie :** 
int


---


### getPresentation {#getPresentation}

| Nom | Description |
| --- | --- |
| getPresentation () | Renvoie la présentation parente d'un FillFormat. Lecture seule IPresentation. |

 **Renvoie :** 
[Presentation](../presentation)


---


### getShowMajorGridLines {#getShowMajorGridLines}

| Nom | Description |
| --- | --- |
| getShowMajorGridLines () | Pour masquer la ligne de grille majeure, définissez MajorGridLinesFormat.Line.FillFormat.FillType sur FillType.NoFill. Lecture seule booléen. |

 **Renvoie :** 
boolean


---


### getShowMinorGridLines {#getShowMinorGridLines}

| Nom | Description |
| --- | --- |
| getShowMinorGridLines () | Pour masquer la ligne de grille mineure, définissez MinorGridLinesFormat.Line.FillFormat.FillType sur FillType.NoFill. Lecture seule booléen. |

 **Renvoie :** 
boolean


---


### getSlide {#getSlide}

| Nom | Description |
| --- | --- |
| getSlide () | Renvoie la diapositive parente d'un FillFormat. Lecture seule BaseSlide. |

 **Renvoie :** 
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)


---


### getTextFormat {#getTextFormat}

| Nom | Description |
| --- | --- |
| getTextFormat () | Représente le format du texte. Lecture seule IChartTextFormat. |

 **Renvoie :** 
[ChartTextFormat](../charttextformat)


---


### getTickLabelPosition {#getTickLabelPosition}

| Nom | Description |
| --- | --- |
| getTickLabelPosition () | Représente la position des étiquettes de graduation sur l'axe spécifié. Lecture/écriture TickLabelPositionType. |

 **Renvoie :** 
int


---


### getTickLabelRotationAngle {#getTickLabelRotationAngle}

| Nom | Description |
| --- | --- |
| getTickLabelRotationAngle () | Représente l'angle de rotation des étiquettes de graduation. Lecture/écriture float. |

 **Renvoie :** 
float


---


### getTickLabelSpacing {#getTickLabelSpacing}

| Nom | Description |
| --- | --- |
| getTickLabelSpacing () | Spécifie le nombre d'étiquettes de graduation à sauter entre les étiquettes dessinées. Appliqué aux axes de catégorie ou de série. Lecture/écriture long. |

 **Renvoie :** 
long


---


### getTickMarksSpacing {#getTickMarksSpacing}

| Nom | Description |
| --- | --- |
| getTickMarksSpacing () | Spécifie le nombre de marques de graduation à sauter avant que la suivante ne soit dessinée. Appliqué aux axes de catégorie ou de série. Lecture/écriture int. |

 **Renvoie :** 
long


---


### getTitle {#getTitle}

| Nom | Description |
| --- | --- |
| getTitle () | Obtient le titre de l'axe. Lecture seule IChartTitle. |

 **Renvoie :** 
[ChartTitle](../charttitle)


---


### getUnderflowBin {#getUnderflowBin}

| Nom | Description |
| --- | --- |
| getUnderflowBin () | Spécifie la valeur personnalisée du bin de sous-dépassement. Appliqué lorsque la propriété IsAutomaticUnderflowBin est définie sur false et que la propriété IsUnderflowBin vaut true. |

 **Renvoie :** 
double


---


### hasTitle {#hasTitle}

| Nom | Description |
| --- | --- |
| hasTitle () | Détermine si un axe possède un titre visible. Lecture/écriture booléen. |

 **Renvoie :** 
boolean


---


### isAutomaticMajorUnit {#isAutomaticMajorUnit}

| Nom | Description |
| --- | --- |
| isAutomaticMajorUnit () | Indique si l'unité majeure de l'axe est assignée automatiquement. Lecture/écriture booléen. |

 **Renvoie :** 
boolean


---


### isAutomaticMaxValue {#isAutomaticMaxValue}

| Nom | Description |
| --- | --- |
| isAutomaticMaxValue () | Indique si la valeur maximale est assignée automatiquement. Lecture/écriture booléen. |

 **Renvoie :** 
boolean


---


### isAutomaticMinValue {#isAutomaticMinValue}

| Nom | Description |
| --- | --- |
| isAutomaticMinValue () | Indique si la valeur minimale est assignée automatiquement. Lecture/écriture booléen. |

 **Renvoie :** 
boolean


---


### isAutomaticMinorUnit {#isAutomaticMinorUnit}

| Nom | Description |
| --- | --- |
| isAutomaticMinorUnit () | Indique si l'unité secondaire de l'axe est assignée automatiquement. Lecture/écriture booléen. |

 **Renvoie :** 
boolean


---


### isAutomaticOverflowBin {#isAutomaticOverflowBin}

| Nom | Description |
| --- | --- |
| isAutomaticOverflowBin () | Spécifie la valeur du bin de dépassement automatique. Si false : utilisez la propriété OverflowBin. |

 **Renvoie :** 
boolean


---


### isAutomaticTickLabelSpacing {#isAutomaticTickLabelSpacing}

| Nom | Description |
| --- | --- |
| isAutomaticTickLabelSpacing () | Spécifie la valeur d'espacement automatique des étiquettes de graduation. Si false : utilisez la propriété TickLabelSpacing. Lecture/écriture booléen. |

 **Renvoie :** 
boolean


---


### isAutomaticTickMarksSpacing {#isAutomaticTickMarksSpacing}

| Nom | Description |
| --- | --- |
| isAutomaticTickMarksSpacing () | Spécifie la valeur d'espacement automatique des marques de graduation. Si false : utilisez la propriété TickMarksSpacing. Lecture/écriture booléen. |

 **Renvoie :** 
boolean


---
### isAutomaticUnderflowBin {#isAutomaticUnderflowBin}

| Name | Description |
| --- | --- |
| isAutomaticUnderflowBin () | Spécifie la valeur du bac de sous-débordement automatique. Si false : utilisez la propriété UnderflowBin. |

 **Retour:**  
boolean


---


### isLogarithmic {#isLogarithmic}

| Name | Description |
| --- | --- |
| isLogarithmic () | Représente si le type d’échelle de l’axe de valeurs est logarithmique ou non. Booléen lecture/écriture. |

 **Retour:**  
boolean


---


### isNumberFormatLinkedToSource {#isNumberFormatLinkedToSource}

| Name | Description |
| --- | --- |
| isNumberFormatLinkedToSource () | Indique si le format est lié aux données source. Booléen lecture/écriture. |

 **Retour:**  
boolean


---


### isOverflowBin {#isOverflowBin}

| Name | Description |
| --- | --- |
| isOverflowBin () | Spécifie si le bac de dépassement est appliqué. Utilisez IsAutomaticOverflowBin et OverflowBin pour ajuster la valeur du bac de dépassement. |

 **Retour:**  
boolean


---


### isPlotOrderReversed {#isPlotOrderReversed}

| Name | Description |
| --- | --- |
| isPlotOrderReversed () | Représente si MS PowerPoint trace les points de données du dernier au premier. Booléen lecture/écriture. |

 **Retour:**  
boolean


---


### isUnderflowBin {#isUnderflowBin}

| Name | Description |
| --- | --- |
| isUnderflowBin () | Spécifie si le bac de sous-débordement est appliqué. Utilisez IsAutomaticUnderflowBin et UnderflowBin pour ajuster la valeur du bac de sous-débordement. |

 **Retour:**  
boolean


---


### isVisible {#isVisible}

| Name | Description |
| --- | --- |
| isVisible () | Représente si l’axe est visible. Booléen lecture/écriture. |

 **Retour:**  
boolean


---


### setAggregationType {#setAggregationType}

| Name | Description |
| --- | --- |
| setAggregationType (int) | Représente le type d’agrégation de l’axe de catégorie (groupement). Appliqué à la catégorie. Utilisé uniquement avec les séries Histogram ou HistogramPareto. |

 **Retour:**  
void


---


### setAutomaticMajorUnit {#setAutomaticMajorUnit}

| Name | Description |
| --- | --- |
| setAutomaticMajorUnit (boolean) | Indique si l’unité principale de l’axe est attribuée automatiquement. Booléen lecture/écriture. |

 **Retour:**  
void


---


### setAutomaticMaxValue {#setAutomaticMaxValue}

| Name | Description |
| --- | --- |
| setAutomaticMaxValue (boolean) | Indique si la valeur maximale est attribuée automatiquement. Booléen lecture/écriture. |

 **Retour:**  
void


---


### setAutomaticMinValue {#setAutomaticMinValue}

| Name | Description |
| --- | --- |
| setAutomaticMinValue (boolean) | Indique si la valeur minimale est attribuée automatiquement. Booléen lecture/écriture. |

 **Retour:**  
void


---


### setAutomaticMinorUnit {#setAutomaticMinorUnit}

| Name | Description |
| --- | --- |
| setAutomaticMinorUnit (boolean) | Indique si l’unité mineure de l’axe est attribuée automatiquement. Booléen lecture/écriture. |

 **Retour:**  
void


---


### setAutomaticOverflowBin {#setAutomaticOverflowBin}

| Name | Description |
| --- | --- |
| setAutomaticOverflowBin (boolean) | Spécifie la valeur du bac de dépassement automatique. Si false : utilisez la propriété OverflowBin. |

 **Retour:**  
void


---


### setAutomaticTickLabelSpacing {#setAutomaticTickLabelSpacing}

| Name | Description |
| --- | --- |
| setAutomaticTickLabelSpacing (boolean) | Spécifie la valeur d’espacement automatique des libellés de graduation. Si false : utilisez la propriété TickLabelSpacing. Booléen lecture/écriture. |

 **Retour:**  
void


---


### setAutomaticTickMarksSpacing {#setAutomaticTickMarksSpacing}

| Name | Description |
| --- | --- |
| setAutomaticTickMarksSpacing (boolean) | Spécifie la valeur d’espacement automatique des marques de graduation. Si false : utilisez la propriété TickMarksSpacing. Booléen lecture/écriture. |

 **Retour:**  
void


---


### setAutomaticUnderflowBin {#setAutomaticUnderflowBin}

| Name | Description |
| --- | --- |
| setAutomaticUnderflowBin (boolean) | Spécifie la valeur du bac de sous-débordement automatique. Si false : utilisez la propriété UnderflowBin. |

 **Retour:**  
void


---


### setAxisBetweenCategories {#setAxisBetweenCategories}

| Name | Description |
| --- | --- |
| setAxisBetweenCategories (boolean) | Représente si l’axe des valeurs traverse l’axe des catégories entre les catégories. Cette propriété s’applique uniquement aux axes de catégorie et ne s’applique pas aux graphiques 3-D. Booléen lecture/écriture. |

 **Retour:**  
void


---


### setBaseUnitScale {#setBaseUnitScale}

| Name | Description |
| --- | --- |
| setBaseUnitScale (int) | Spécifie la plus petite unité de temps représentée sur l’axe de date. TimeUnitType lecture/écriture. |

 **Retour:**  
void


---


### setBinWidth {#setBinWidth}

| Name | Description |
| --- | --- |
| setBinWidth (double) | Spécifie la largeur du bac lorsque la propriété AggregationType est définie sur AxisAggregationType.ByBinWidth. Appliqué aux axes de catégorie. Utilisé uniquement avec les séries Histogram ou HistogramPareto. |

 **Retour:**  
void


---


### setCategoryAxisType {#setCategoryAxisType}

| Name | Description |
| --- | --- |
| setCategoryAxisType (int) | Spécifie le type de l’axe de catégorie. CategoryAxisType lecture/écriture. |

 **Retour:**  
void


---


### setCategoryAxisTypeAutomatically {#setCategoryAxisTypeAutomatically}

| Name | Description |
| --- | --- |
| setCategoryAxisTypeAutomatically () | Définit la propriété IAxis.CategoryAxisType avec une valeur déterminée automatiquement en fonction des données de l’axe. |

 **Retour:**  
void


---


### setCrossAt {#setCrossAt}

| Name | Description |
| --- | --- |
| setCrossAt (float) | Représente le point sur l’axe où l’axe perpendiculaire le traverse. Float lecture/écriture. |

 **Retour:**  
void


---


### setCrossType {#setCrossType}

| Name | Description |
| --- | --- |
| setCrossType (int) | Représente le CrossType sur l’axe spécifié où l’autre axe le traverse. CrossesType lecture/écriture. |

 **Retour:**  
void


---


### setDisplayUnit {#setDisplayUnit}

| Name | Description |
| --- | --- |
| setDisplayUnit (int) | Spécifie la valeur d’échelle des unités d’affichage pour l’axe de valeurs. DisplayUnitType lecture/écriture. |

 **Retour:**  
void


---


### setLabelOffset {#setLabelOffset}

| Name | Description |
| --- | --- |
| setLabelOffset (int) | Spécifie la distance des libellés par rapport à l’axe. Appliqué à l’axe de catégorie ou de date. La valeur doit être comprise entre 0 % et 1000 %. Int lecture/écriture. |

 **Retour:**  
void


---


### setLogBase {#setLogBase}

| Name | Description |
| --- | --- |
| setLogBase (double) | Représente la base logarithmique. La valeur par défaut est 10. Double lecture/écriture. |

 **Retour:**  
void


---


### setLogarithmic {#setLogarithmic}

| Name | Description |
| --- | --- |
| setLogarithmic (boolean) | Représente si le type d’échelle de l’axe de valeurs est logarithmique ou non. Booléen lecture/écriture. |

 **Retour:**  
void


---


### setMajorTickMark {#setMajorTickMark}

| Name | Description |
| --- | --- |
| setMajorTickMark (int) | Représente le type de marque principale pour l’axe spécifié. TickMarkType lecture/écriture. |

 **Retour:**  
void


---


### setMajorUnit {#setMajorUnit}

| Name | Description |
| --- | --- |
| setMajorUnit (double) | Représente les unités principales pour l’axe de date ou de valeurs. Double lecture/écriture. |

 **Retour:**  
void


---


### setMajorUnitScale {#setMajorUnitScale}

| Name | Description |
| --- | --- |
| setMajorUnitScale (int) | Représente l’échelle de l’unité principale pour l’axe de date. TimeUnitType lecture/écriture. |

 **Retour:**  
void


---


### setMaxValue {#setMaxValue}

| Name | Description |
| --- | --- |
| setMaxValue (double) | Représente la valeur maximale sur l’axe de valeurs. Double lecture/écriture. |

 **Retour:**  
void


---


### setMinValue {#setMinValue}

| Name | Description |
| --- | --- |
| setMinValue (double) | Représente la valeur minimale sur l’axe de valeurs. Double lecture/écriture. |

 **Retour:**  
void


---


### setMinorTickMark {#setMinorTickMark}

| Name | Description |
| --- | --- |
| setMinorTickMark (int) | Représente le type de petite marque pour l’axe spécifié. TickMarkType lecture/écriture. |

 **Retour:**  
void


---


### setMinorUnit {#setMinorUnit}

| Name | Description |
| --- | --- |
| setMinorUnit (double) | Représente les petites unités pour l’axe de date ou de valeurs. Double lecture/écriture. |

 **Retour:**  
void


---


### setMinorUnitScale {#setMinorUnitScale}

| Name | Description |
| --- | --- |
| setMinorUnitScale (int) | Représente l’échelle de l’unité principale pour l’axe de date. TimeUnitType lecture/écriture. |

 **Retour:**  
void


---


### setNumberFormat {#setNumberFormat}

| Name | Description |
| --- | --- |
| setNumberFormat (String) | Représente la chaîne de format pour les libellés d’axe. String lecture/écriture. |

 **Retour:**  
void


---


### setNumberFormatLinkedToSource {#setNumberFormatLinkedToSource}

| Name | Description |
| --- | --- |
| setNumberFormatLinkedToSource (boolean) | Indique si le format est lié aux données source. Booléen lecture/écriture. |

 **Retour:**  
void


---


### setNumberOfBins {#setNumberOfBins}

| Name | Description |
| --- | --- |
| setNumberOfBins (long) | Spécifie le nombre de bacs lorsque la propriété AggregationType est définie sur AxisAggregationType.ByNumberOfBins. Appliqué aux axes de catégorie. Utilisé uniquement avec les séries Histogram ou HistogramPareto. |

 **Retour:**  
void


---


### setOverflowBin {#setOverflowBin}

| Name | Description |
| --- | --- |
| setOverflowBin (boolean) | Spécifie si le bac de dépassement est appliqué. Utilisez IsAutomaticOverflowBin et OverflowBin pour ajuster la valeur du bac de dépassement. |

 **Retour:**  
void


---


### setOverflowBin {#setOverflowBin}

| Name | Description |
| --- | --- |
| setOverflowBin (double) | Spécifie une valeur personnalisée du bac de dépassement. Appliqué lorsque la propriété IsAutomaticOverflowBin est définie sur false et que la propriété IsOverflowBin vaut true. |

 **Retour:**  
void


---


### setPlotOrderReversed {#setPlotOrderReversed}

| Name | Description |
| --- | --- |
| setPlotOrderReversed (boolean) | Représente si MS PowerPoint trace les points de données du dernier au premier. Booléen lecture/écriture. |

 **Retour:**  
void


---


### setPosition {#setPosition}

| Name | Description |
| --- | --- |
| setPosition (int) | Représente la position de l’axe. AxisPositionType lecture/écriture. |

 **Retour:**  
void


---


### setTickLabelPosition {#setTickLabelPosition}

| Name | Description |
| --- | --- |
| setTickLabelPosition (int) | Représente la position des libellés de graduation sur l’axe spécifié. TickLabelPositionType lecture/écriture. |

 **Retour:**  
void


---


### setTickLabelRotationAngle {#setTickLabelRotationAngle}

| Name | Description |
| --- | --- |
| setTickLabelRotationAngle (float) | Représente l’angle de rotation des libellés de graduation. Float lecture/écriture. |

 **Retour:**  
void


---


### setTickLabelSpacing {#setTickLabelSpacing}

| Name | Description |
| --- | --- |
| setTickLabelSpacing (long) | Spécifie le nombre de libellés de graduation à sauter entre chaque libellé affiché. Appliqué aux axes de catégorie ou de série. Long lecture/écriture. |

 **Retour:**  
void


---


### setTickMarksSpacing {#setTickMarksSpacing}

| Name | Description |
| --- | --- |
| setTickMarksSpacing (long) | Spécifie le nombre de marques de graduation à sauter avant que la suivante ne soit dessinée. Appliqué aux axes de catégorie ou de série. Int lecture/écriture. |

 **Retour:**  
void


---


### setTitle {#setTitle}

| Name | Description |
| --- | --- |
| setTitle (boolean) | Détermine si un axe possède un titre visible. Booléen lecture/écriture. |

 **Retour:**  
void


---


### setUnderflowBin {#setUnderflowBin}

| Name | Description |
| --- | --- |
| setUnderflowBin (boolean) | Spécifie si le bac de sous-débordement est appliqué. Utilisez IsAutomaticUnderflowBin et UnderflowBin pour ajuster la valeur du bac de sous-débordement. |

 **Retour:**  
void


---


### setUnderflowBin {#setUnderflowBin}

| Name | Description |
| --- | --- |
| setUnderflowBin (double) | Spécifie une valeur personnalisée du bac de sous-débordement. Appliqué lorsque la propriété IsAutomaticUnderflowBin est définie sur false et que la propriété IsUnderflowBin vaut true. |

 **Retour:**  
void


---


### setVisible {#setVisible}

| Name | Description |
| --- | --- |
| setVisible (boolean) | Représente si l’axe est visible. Booléen lecture/écriture. |

 **Retour:**  
void


---