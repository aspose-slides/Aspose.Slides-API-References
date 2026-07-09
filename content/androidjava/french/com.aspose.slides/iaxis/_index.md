---
title: IAxis
second_title: Aspose.Slides pour Android via la référence d'API Java
description: Encapsule l'objet qui représente l'axe d'un graphique.
type: docs
url: /fr/com.aspose.slides/iaxis/
---
**Toutes les interfaces implémentées:**  
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IAxis extends IFormattedTextContainer
```

Encapsule l'objet qui représente l'axe d'un graphique.  

## Méthodes

| Méthode | Description |
| --- | --- |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Indique si l'axe des valeurs croise l'axe des catégories entre les catégories. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Indique si l'axe des valeurs croise l'axe des catégories entre les catégories. |
| [getCrossAt()](#getCrossAt--) | Représente le point sur l'axe où l'axe perpendiculaire le traverse. |
| [setCrossAt(float value)](#setCrossAt-float-) | Représente le point sur l'axe où l'axe perpendiculaire le traverse. |
| [getDisplayUnit()](#getDisplayUnit--) | Spécifie la valeur d'échelle des unités d'affichage pour l'axe des valeurs. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Spécifie la valeur d'échelle des unités d'affichage pour l'axe des valeurs. |
| [getActualMaxValue()](#getActualMaxValue--) | Spécifie la valeur maximale réelle sur l'axe. |
| [getActualMinValue()](#getActualMinValue--) | Spécifie la valeur minimale réelle sur l'axe. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Spécifie l'unité majeure réelle de l'axe. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Spécifie l'unité mineure réelle de l'axe. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Spécifie l'échelle de l'unité majeure réelle de l'axe. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Spécifie l'échelle de l'unité mineure réelle de l'axe. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Indique si la valeur maximale est assignée automatiquement. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Indique si la valeur maximale est assignée automatiquement. |
| [getMaxValue()](#getMaxValue--) | Représente la valeur maximale sur l'axe des valeurs. |
| [setMaxValue(double value)](#setMaxValue-double-) | Représente la valeur maximale sur l'axe des valeurs. |
| [getMinorUnit()](#getMinorUnit--) | Représente les unités mineures pour l'axe de date ou de valeur. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Représente les unités mineures pour l'axe de date ou de valeur. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Indique si l'unité mineure de l'axe est assignée automatiquement. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Indique si l'unité mineure de l'axe est assignée automatiquement. |
| [getMajorUnit()](#getMajorUnit--) | Représente les unités majeures pour l'axe de date ou de valeur. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Représente les unités majeures pour l'axe de date ou de valeur. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Indique si l'unité majeure de l'axe est assignée automatiquement. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Indique si l'unité majeure de l'axe est assignée automatiquement. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Indique si la valeur minimale est assignée automatiquement. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Indique si la valeur minimale est assignée automatiquement. |
| [getMinValue()](#getMinValue--) | Représente la valeur minimale sur l'axe des valeurs. |
| [setMinValue(double value)](#setMinValue-double-) | Représente la valeur minimale sur l'axe des valeurs. |
| [isLogarithmic()](#isLogarithmic--) | Indique si le type d'échelle de l'axe des valeurs est logarithmique ou non. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Indique si le type d'échelle de l'axe des valeurs est logarithmique ou non. |
| [getLogBase()](#getLogBase--) | Représente la base logarithmique. |
| [setLogBase(double value)](#setLogBase-double-) | Représente la base logarithmique. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Indique si MS PowerPoint trace les points de données du dernier au premier. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Indique si MS PowerPoint trace les points de données du dernier au premier. |
| [isVisible()](#isVisible--) | Indique si l'axe est visible. |
| [setVisible(boolean value)](#setVisible-boolean-) | Indique si l'axe est visible. |
| [getMajorTickMark()](#getMajorTickMark--) | Représente le type de repère majeur pour l'axe spécifié. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Représente le type de repère majeur pour l'axe spécifié. |
| [getMinorTickMark()](#getMinorTickMark--) | Représente le type de repère mineur pour l'axe spécifié. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Représente le type de repère mineur pour l'axe spécifié. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Représente la position des libellés des repères sur l'axe spécifié. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Représente la position des libellés des repères sur l'axe spécifié. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Représente l'échelle de l'unité majeure pour l'axe de date. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Représente l'échelle de l'unité majeure pour l'axe de date. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Représente l'échelle de l'unité majeure pour l'axe de date. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Représente l'échelle de l'unité majeure pour l'axe de date. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Spécifie la plus petite unité de temps représentée sur l'axe de date. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Spécifie la plus petite unité de temps représentée sur l'axe de date. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Représente le format des lignes de grille mineures sur un axe de diagramme. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Représente le format des lignes de grille majeures sur un axe de diagramme. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Indique si les lignes de grille mineures sont affichées. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Indique si les lignes de grille majeures sont affichées. |
| [getFormat()](#getFormat--) | Représente le format de l'axe. |
| [getTitle()](#getTitle--) | Obtient le titre de l'axe. |
| [getCrossType()](#getCrossType--) | Représente le CrossType sur l'axe spécifié où l'autre axe le croise. |
| [setCrossType(int value)](#setCrossType-int-) | Représente le CrossType sur l'axe spécifié où l'autre axe le croise. |
| [getPosition()](#getPosition--) | Représente la position de l'axe. |
| [setPosition(int value)](#setPosition-int-) | Représente la position de l'axe. |
| [hasTitle()](#hasTitle--) | Détermine si un axe possède un titre visible. |
| [setTitle(boolean value)](#setTitle-boolean-) | Détermine si un axe possède un titre visible. |
| [getNumberFormat()](#getNumberFormat--) | Représente la chaîne de format pour les libellés d'axe. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Représente la chaîne de format pour les libellés d'axe. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Indique si le format est lié aux données source. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Indique si le format est lié aux données source. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Représente l'angle de rotation des libellés des repères Lecture/écriture float. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Représente l'angle de rotation des libellés des repères Lecture/écriture float. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Spécifie le nombre de libellés de repère à sauter entre deux libellés affichés. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Spécifie le nombre de libellés de repère à sauter entre deux libellés affichés. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Spécifie la valeur d'espacement automatique des libellés de repère. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Spécifie la valeur d'espacement automatique des libellés de repère. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Spécifie le nombre de repères à sauter avant d'en dessiner un autre. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Spécifie le nombre de repères à sauter avant d'en dessiner un autre. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Spécifie la valeur d'espacement automatique des repères. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Spécifie la valeur d'espacement automatique des repères. |
| [getLabelOffset()](#getLabelOffset--) | Spécifie la distance des libellés par rapport à l'axe. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Spécifie la distance des libellés par rapport à l'axe. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Spécifie le type de l'axe de catégorie. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Spécifie le type de l'axe de catégorie. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Définit la propriété IAxis.CategoryAxisType avec une valeur déterminée automatiquement en fonction des données de l'axe. |
| [getAggregationType()](#getAggregationType--) | Représente le type d'agrégation de l'axe de catégorie (regroupement). |
| [setAggregationType(int value)](#setAggregationType-int-) | Représente le type d'agrégation de l'axe de catégorie (regroupement). |
| [getBinWidth()](#getBinWidth--) | Spécifie la largeur du bin lorsque la propriété AggregationType est définie sur AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | Spécifie la largeur du bin lorsque la propriété AggregationType est définie sur AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | Spécifie le nombre de bins lorsque la propriété AggregationType est définie sur AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Spécifie le nombre de bins lorsque la propriété AggregationType est définie sur AxisAggregationType.ByNumberOfBins. |
| [isOverflowBin()](#isOverflowBin--) | Indique si le bin de débordement est appliqué. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Indique si le bin de débordement est appliqué. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Spécifie la valeur automatique du bin de débordement. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Spécifie la valeur automatique du bin de débordement. |
| [getOverflowBin()](#getOverflowBin--) | Spécifie la valeur personnalisée du bin de débordement. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Spécifie la valeur personnalisée du bin de débordement. |
| [isUnderflowBin()](#isUnderflowBin--) | Indique si le bin de sous-débordement est appliqué. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Indique si le bin de sous-débordement est appliqué. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Spécifie la valeur automatique du bin de sous-débordement. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Spécifie la valeur automatique du bin de sous-débordement. |
| [getUnderflowBin()](#getUnderflowBin--) | Spécifie la valeur personnalisée du bin de sous-débordement. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Spécifie la valeur personnalisée du bin de sous-débordement. |

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public abstract boolean getAxisBetweenCategories()
```

Représente si l'axe des valeurs croise l'axe des catégories entre les catégories. Cette propriété s'applique uniquement aux axes de catégorie et ne s'applique pas aux graphiques 3-D. Lecture/écriture boolean.

**Renvoie:**  
boolean  

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public abstract void setAxisBetweenCategories(boolean value)
```

Représente si l'axe des valeurs croise l'axe des catégories entre les catégories. Cette propriété s'applique uniquement aux axes de catégorie et ne s'applique pas aux graphiques 3-D. Lecture/écriture boolean.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getCrossAt() {#getCrossAt--}
```
public abstract float getCrossAt()
```

Représente le point sur l'axe où l'axe perpendiculaire le traverse. Lecture/écriture float.

**Renvoie:**  
float  

### setCrossAt(float value) {#setCrossAt-float-}
```
public abstract void setCrossAt(float value)
```

Représente le point sur l'axe où l'axe perpendiculaire le traverse. Lecture/écriture float.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public abstract int getDisplayUnit()
```

Spécifie la valeur d'échelle des unités d'affichage pour l'axe des valeurs. Lecture/écriture [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Renvoie:**  
int  

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public abstract void setDisplayUnit(int value)
```

Spécifie la valeur d'échelle des unités d'affichage pour l'axe des valeurs. Lecture/écriture [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public abstract double getActualMaxValue()
```

Spécifie la valeur maximale réelle sur l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur réelle.

**Renvoie:**  
double  

### getActualMinValue() {#getActualMinValue--}
```
public abstract double getActualMinValue()
```

Spécifie la valeur minimale réelle sur l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur réelle.

**Renvoie:**  
double  

### getActualMajorUnit() {#getActualMajorUnit--}
```
public abstract double getActualMajorUnit()
```

Spécifie l'unité majeure réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur réelle.

**Renvoie:**  
double  

### getActualMinorUnit() {#getActualMinorUnit--}
```
public abstract double getActualMinorUnit()
```

Spécifie l'unité mineure réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur réelle.

**Renvoie:**  
double  

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public abstract int getActualMajorUnitScale()
```

Spécifie l'échelle de l'unité majeure réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur réelle.

**Renvoie:**  
int  

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public abstract int getActualMinorUnitScale()
```

Spécifie l'échelle de l'unité mineure réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur réelle.

**Renvoie:**  
int  

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public abstract boolean isAutomaticMaxValue()
```

Indique si la valeur maximale est assignée automatiquement. Lecture/écriture boolean.

**Renvoie:**  
boolean  

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public abstract void setAutomaticMaxValue(boolean value)
```

Indique si la valeur maximale est assignée automatiquement. Lecture/écriture boolean.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public abstract double getMaxValue()
```

Représente la valeur maximale sur l'axe des valeurs. Lecture/écriture double.

**Renvoie:**  
double  

### setMaxValue(double value) {#setMaxValue-double-}
```
public abstract void setMaxValue(double value)
```

Représente la valeur maximale sur l'axe des valeurs. Lecture/écriture double.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public abstract double getMinorUnit()
```

Représente les unités mineures pour l'axe de date ou de valeur. Lecture/écriture double.

**Renvoie:**  
double  

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public abstract void setMinorUnit(double value)
```

Représente les unités mineures pour l'axe de date ou de valeur. Lecture/écriture double.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public abstract boolean isAutomaticMinorUnit()
```

Indique si l'unité mineure de l'axe est assignée automatiquement. Lecture/écriture boolean.

**Renvoie:**  
boolean  

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public abstract void setAutomaticMinorUnit(boolean value)
```

Indique si l'unité mineure de l'axe est assignée automatiquement. Lecture/écriture boolean.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public abstract double getMajorUnit()
```

Représente les unités majeures pour l'axe de date ou de valeur. Lecture/écriture double.

**Renvoie:**  
double  

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public abstract void setMajorUnit(double value)
```

Représente les unités majeures pour l'axe de date ou de valeur. Lecture/écriture double.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public abstract boolean isAutomaticMajorUnit()
```

Indique si l'unité majeure de l'axe est assignée automatiquement. Lecture/écriture boolean.

**Renvoie:**  
boolean  

### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public abstract void setAutomaticMajorUnit(boolean value)
```

Indique si l'unité majeure de l'axe est assignée automatiquement. Lecture/écriture boolean.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public abstract boolean isAutomaticMinValue()
```

Indique si la valeur minimale est assignée automatiquement. Lecture/écriture boolean.

**Renvoie:**  
boolean  

### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public abstract void setAutomaticMinValue(boolean value)
```

Indique si la valeur minimale est assignée automatiquement. Lecture/écriture boolean.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public abstract double getMinValue()
```

Représente la valeur minimale sur l'axe des valeurs. Lecture/écriture double.

**Renvoie:**  
double  

### setMinValue(double value) {#setMinValue-double-}
```
public abstract void setMinValue(double value)
```

Représente la valeur minimale sur l'axe des valeurs. Lecture/écriture double.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public abstract boolean isLogarithmic()
```

Indique si le type d'échelle de l'axe des valeurs est logarithmique ou non. Lecture/écriture boolean.

**Renvoie:**  
boolean  

### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public abstract void setLogarithmic(boolean value)
```

Indique si le type d'échelle de l'axe des valeurs est logarithmique ou non. Lecture/écriture boolean.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public abstract double getLogBase()
```

Représente la base logarithmique. Valeur par défaut : 10. Lecture/écriture double.

**Renvoie:**  
double  

### setLogBase(double value) {#setLogBase-double-}
```
public abstract void setLogBase(double value)
```

Représente la base logarithmique. Valeur par défaut : 10. Lecture/écriture double.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public abstract boolean isPlotOrderReversed()
```

Indique si MS PowerPoint trace les points de données du dernier au premier. Lecture/écriture boolean.

**Renvoie:**  
boolean  

### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public abstract void setPlotOrderReversed(boolean value)
```

Indique si MS PowerPoint trace les points de données du dernier au premier. Lecture/écriture boolean.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Indique si l'axe est visible. Lecture/écriture boolean.

**Renvoie:**  
boolean  

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Indique si l'axe est visible. Lecture/écriture boolean.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public abstract int getMajorTickMark()
```

Représente le type de repère majeur pour l'axe spécifié. Lecture/écriture [TickMarkType](../../com.aspose.slides/tickmarktype).

**Renvoie:**  
int  

### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public abstract void setMajorTickMark(int value)
```

Représente le type de repère majeur pour l'axe spécifié. Lecture/écriture [TickMarkType](../../com.aspose.slides/tickmarktype).

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public abstract int getMinorTickMark()
```

Représente le type de repère mineur pour l'axe spécifié. Lecture/écriture [TickMarkType](../../com.aspose.slides/tickmarktype).

**Renvoie:**  
int  

### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public abstract void setMinorTickMark(int value)
```

Représente le type de repère mineur pour l'axe spécifié. Lecture/écriture [TickMarkType](../../com.aspose.slides/tickmarktype).

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public abstract int getTickLabelPosition()
```

Représente la position des libellés des repères sur l'axe spécifié. Lecture/écriture [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Renvoie:**  
int  

### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public abstract void setTickLabelPosition(int value)
```

Représente la position des libellés des repères sur l'axe spécifié. Lecture/écriture [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public abstract int getMajorUnitScale()
```

Représente l'échelle de l'unité majeure pour l'axe de date. Lecture/écriture [TimeUnitType](../../com.aspose.slides/timeunittype).

**Renvoie:**  
int  

### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public abstract void setMajorUnitScale(int value)
```

Représente l'échelle de l'unité majeure pour l'axe de date. Lecture/écriture [TimeUnitType](../../com.aspose.slides/timeunittype).

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public abstract int getMinorUnitScale()
```

Représente l'échelle de l'unité majeure pour l'axe de date. Lecture/écriture [TimeUnitType](../../com.aspose.slides/timeunittype).

**Renvoie:**  
int  

### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public abstract void setMinorUnitScale(int value)
```

Représente l'échelle de l'unité majeure pour l'axe de date. Lecture/écriture [TimeUnitType](../../com.aspose.slides/timeunittype).

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public abstract int getBaseUnitScale()
```

Spécifie la plus petite unité de temps représentée sur l'axe de date. Lecture/écriture [TimeUnitType](../../com.aspose.slides/timeunittype).

**Renvoie:**  
int  

### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public abstract void setBaseUnitScale(int value)
```

Spécifie la plus petite unité de temps représentée sur l'axe de date. Lecture/écriture [TimeUnitType](../../com.aspose.slides/timeunittype).

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

Représente le format des lignes de grille mineures sur un axe de diagramme. Lecture seule [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Renvoie:**  
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

Représente le format des lignes de grille majeures sur un axe de diagramme. Lecture seule [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Renvoie:**  
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public abstract boolean getShowMinorGridLines()
```

Indique si les lignes de grille mineures sont affichées. Lecture seule boolean.

**Renvoie:**  
boolean  

### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public abstract boolean getShowMinorGridLines()
```

Indique si les lignes de grille majeures sont affichées. Lecture seule boolean.

**Renvoie:**  
boolean  

### getFormat() {#getFormat--}
```
public abstract IAxisFormat getFormat()
```

Représente le format de l'axe. Lecture seule [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Renvoie:**  
[IAxisFormat](../../com.aspose.slides/iaxisformat)

### getTitle() {#getTitle--}
```
public abstract IChartTitle getTitle()
```

Obtient le titre de l'axe. Lecture seule [IChartTitle](../../com.aspose.slides/icharttitle).

**Renvoie:**  
[IChartTitle](../../com.aspose.slides/icharttitle)

### getCrossType() {#getCrossType--}
```
public abstract int getCrossType()
```

Représente le CrossType sur l'axe spécifié où l'autre axe le croise. Lecture/écriture [CrossesType](../../com.aspose.slides/crossestype).

**Renvoie:**  
int  

### setCrossType(int value) {#setCrossType-int-}
```
public abstract void setCrossType(int value)
```

Représente le CrossType sur l'axe spécifié où l'autre axe le croise. Lecture/écriture [CrossesType](../../com.aspose.slides/crossestype).

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Représente la position de l'axe. Lecture/écriture [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Renvoie:**  
int  

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Représente la position de l'axe. Lecture/écriture [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

Détermine si un axe possède un titre visible. Lecture/écriture boolean.

**Renvoie:**  
boolean  

### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

Détermine si un axe possède un titre visible. Lecture/écriture boolean.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

Représente la chaîne de format pour les libellés d'axe. Lecture/écriture String.

**Renvoie:**  
java.lang.String  

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

Représente la chaîne de format pour les libellés d'axe. Lecture/écriture String.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Indique si le format est lié aux données source. Lecture/écriture boolean.

**Renvoie:**  
boolean  

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Indique si le format est lié aux données source. Lecture/écriture boolean.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public abstract float getTickLabelRotationAngle()
```

Représente l'angle de rotation des libellés des repères Lecture/écriture float.

**Renvoie:**  
float  

### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public abstract void setTickLabelRotationAngle(float value)
```

Représente l'angle de rotation des libellés des repères Lecture/écriture float.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public abstract long getTickLabelSpacing()
```

Spécifie le nombre de libellés de repère à sauter entre deux libellés affichés. Lecture/écriture long.

**Renvoie:**  
long  

### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public abstract void setTickLabelSpacing(long value)
```

Spécifie le nombre de libellés de repère à sauter entre deux libellés affichés. Lecture/écriture long.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public abstract boolean 
```

Spécifie la valeur d'espacement automatique des libellés de repère. Si false : utilisez la propriété TickLabelSpacing. Lecture/écriture boolean.

**Renvoie:**  
boolean  

### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public abstract void setAutomaticTickLabelSpacing(boolean value)
```

Spécifie la valeur d'espacement automatique des libellés de repère. Si false : utilisez la propriété TickLabelSpacing. Lecture/écriture boolean.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public abstract long getTickMarksSpacing()
```

Spécifie le nombre de repères à sauter avant d'en dessiner un autre. Appliqué aux axes de catégorie ou de série. Lecture/écriture int.

**Renvoie:**  
long  

### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public abstract void setTickMarksSpacing(long value)
```

Spécifie le nombre de repères à sauter avant d'en dessiner un autre. Appliqué aux axes de catégorie ou de série. Lecture/écriture int.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public abstract boolean isAutomaticTickMarksSpacing()
```

Spécifie la valeur d'espacement automatique des repères. Si false : utilisez la propriété TickMarksSpacing. Lecture/écriture boolean.

**Renvoie:**  
boolean  

### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public abstract void setAutomaticTickMarksSpacing(boolean value)
```

Spécifie la valeur d'espacement automatique des repères. Si false : utilisez la propriété TickMarksSpacing. Lecture/écriture boolean.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public abstract int getLabelOffset()
```

Spécifie la distance des libellés par rapport à l'axe. Appliqué aux axes de catégorie ou de date. La valeur doit être comprise entre 0 % et 1000 %. Lecture/écriture int.

**Renvoie:**  
int  

### setLabelOffset(int value) {#setLabelOffset-int-}
```
public abstract void setLabelOffset(int value)
```

Spécifie la distance des libellés par rapport à l'axe. Appliqué aux axes de catégorie ou de date. La valeur doit être comprise entre 0 % et 1000 %. Lecture/écriture int.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public abstract int getCategoryAxisType()
```

Spécifie le type de l'axe de catégorie. Lecture/écriture [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Renvoie:**  
int  

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public abstract void setCategoryAxisType(int value)
```

Spécifie le type de l'axe de catégorie. Lecture/écriture [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public abstract void setCategoryAxisTypeAutomatically()
```

Définit la propriété IAxis.CategoryAxisType avec une valeur déterminée automatiquement en fonction des données de l'axe.

### getAggregationType() {#getAggregationType--}
```
public abstract int getAggregationType()
```

Représente le type d'agrégation de l'axe de catégorie (regroupement). Appliqué aux catégories. Utilisé uniquement avec les séries Histogram ou HistogramPareto.

**Renvoie:**  
int  

### setAggregationType(int value) {#setAggregationType-int-}
```
public abstract void setAggregationType(int value)
```

Représente le type d'agrégation de l'axe de catégorie (regroupement). Appliqué aux catégories. Utilisé uniquement avec les séries Histogram ou HistogramPareto.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public abstract double getBinWidth()
```

Spécifie la largeur du bin lorsque la propriété AggregationType est définie sur AxisAggregationType.ByBinWidth. Appliqué aux axes de catégorie. Utilisé uniquement avec les séries Histogram ou HistogramPareto.

**Renvoie:**  
double  

### setBinWidth(double value) {#setBinWidth-double-}
```
public abstract void setBinWidth(double value)
```

Spécifie la largeur du bin lorsque la propriété AggregationType est définie sur AxisAggregationType.ByBinWidth. Appliqué aux axes de catégorie. Utilisé uniquement avec les séries Histogram ou HistogramPareto.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public abstract long getNumberOfBins()
```

Spécifie le nombre de bins lorsque la propriété AggregationType est définie sur AxisAggregationType.ByNumberOfBins. Appliqué aux axes de catégorie. Utilisé uniquement avec les séries Histogram ou HistogramPareto.

**Renvoie:**  
long  

### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public abstract void setNumberOfBins(long value)
```

Spécifie le nombre de bins lorsque la propriété AggregationType est définie sur AxisAggregationType.ByNumberOfBins. Appliqué aux axes de catégorie. Utilisé uniquement avec les séries Histogram ou HistogramPareto.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public abstract boolean isOverflowBin()
```

Indique si le bin de débordement est appliqué. Utilisez IsAutomaticOverflowBin et OverflowBin pour ajuster la valeur du bin de débordement.

**Renvoie:**  
boolean  

### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public abstract void setOverflowBin(boolean value)
```

Indique si le bin de débordement est appliqué. Utilisez IsAutomaticOverflowBin et OverflowBin pour ajuster la valeur du bin de débordement.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public abstract boolean isAutomaticOverflowBin()
```

Spécifie la valeur automatique du bin de débordement. Si false : utilisez la propriété OverflowBin.

**Renvoie:**  
boolean  

### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public abstract void setAutomaticOverflowBin(boolean value)
```

Spécifie la valeur automatique du bin de débordement. Si false : utilisez la propriété OverflowBin.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public abstract double getOverflowBin()
```

Spécifie la valeur personnalisée du bin de débordement. Appliqué lorsque la propriété IsAutomaticOverflowBin est définie sur false et que la propriété IsOverflowBin vaut true.

**Renvoie:**  
double  

### setOverflowBin(double value) {#setOverflowBin-double-}
```
public abstract void setOverflowBin(double value)
```

Spécifie la valeur personnalisée du bin de débordement. Appliqué lorsque la propriété IsAutomaticOverflowBin est définie sur false et que la propriété IsOverflowBin vaut true.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public abstract boolean isUnderflowBin()
```

Indique si le bin de sous-débordement est appliqué. Utilisez IsAutomaticUnderflowBin et UnderflowBin pour ajuster la valeur du bin de sous-débordement.

**Renvoie:**  
boolean  

### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public abstract void setUnderflowBin(boolean value)
```

Indique si le bin de sous-débordement est appliqué. Utilisez IsAutomaticUnderflowBin et UnderflowBin pour ajuster la valeur du bin de sous-débordement.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public abstract boolean isAutomaticUnderflowBin()
```

Spécifie la valeur automatique du bin de sous-débordement. Si false : utilisez la propriété UnderflowBin.

**Renvoie:**  
boolean  

### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public abstract void setAutomaticUnderflowBin(boolean value)
```

Spécifie la valeur automatique du bin de sous-débordement. Si false : utilisez la propriété UnderflowBin.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public abstract double getUnderflowBin()
```

Spécifie la valeur personnalisée du bin de sous-débordement. Appliqué lorsque la propriété IsAutomaticUnderflowBin est définie sur false et que la propriété IsUnderflowBin vaut true.

**Renvoie:**  
double  

### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public abstract void setUnderflowBin(double value)
```

Spécifie la valeur personnalisée du bin de sous-débordement. Appliqué lorsque la propriété IsAutomaticUnderflowBin est définie sur false et que la propriété IsUnderflowBin vaut true.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |