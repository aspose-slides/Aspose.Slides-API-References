---
title: IAxis
second_title: Référence de l'API Aspose.Slides pour Java
description: Encapsule l'objet qui représente un axe de graphique.
type: docs
url: /fr/com.aspose.slides/iaxis/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IAxis extends IFormattedTextContainer
```

Encapsule l'objet qui représente l'axe d'un graphique.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Représente si l'axe de valeurs croise l'axe des catégories entre les catégories. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Représente si l'axe de valeurs croise l'axe des catégories entre les catégories. |
| [getCrossAt()](#getCrossAt--) | Représente le point sur l'axe où l'axe perpendiculaire le croise. |
| [setCrossAt(float value)](#setCrossAt-float-) | Représente le point sur l'axe où l'axe perpendiculaire le croise. |
| [getDisplayUnit()](#getDisplayUnit--) | Spécifie la valeur d'échelle des unités d'affichage pour l'axe de valeurs. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Spécifie la valeur d'échelle des unités d'affichage pour l'axe de valeurs. |
| [getActualMaxValue()](#getActualMaxValue--) | Spécifie la valeur maximale réelle sur l'axe. |
| [getActualMinValue()](#getActualMinValue--) | Spécifie la valeur minimale réelle sur l'axe. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Spécifie l'unité principale réelle de l'axe. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Spécifie l'unité secondaire réelle de l'axe. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Spécifie l'échelle de l'unité principale réelle de l'axe. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Spécifie l'échelle de l'unité secondaire réelle de l'axe. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Indique si la valeur maximale est attribuée automatiquement. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Indique si la valeur maximale est attribuée automatiquement. |
| [getMaxValue()](#getMaxValue--) | Représente la valeur maximale sur l'axe de valeurs. |
| [setMaxValue(double value)](#setMaxValue-double-) | Représente la valeur maximale sur l'axe de valeurs. |
| [getMinorUnit()](#getMinorUnit--) | Représente les unités secondaires pour l'axe de date ou de valeurs. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Représente les unités secondaires pour l'axe de date ou de valeurs. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Indique si l'unité secondaire de l'axe est attribuée automatiquement. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Indique si l'unité secondaire de l'axe est attribuée automatiquement. |
| [getMajorUnit()](#getMajorUnit--) | Représente les unités principales pour l'axe de date ou de valeurs. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Représente les unités principales pour l'axe de date ou de valeurs. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Indique si l'unité principale de l'axe est attribuée automatiquement. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Indique si l'unité principale de l'axe est attribuée automatiquement. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Indique si la valeur minimale est attribuée automatiquement. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Indique si la valeur minimale est attribuée automatiquement. |
| [getMinValue()](#getMinValue--) | Représente la valeur minimale sur l'axe de valeurs. |
| [setMinValue(double value)](#setMinValue-double-) | Représente la valeur minimale sur l'axe de valeurs. |
| [isLogarithmic()](#isLogarithmic--) | Indique si le type d'échelle de l'axe de valeurs est logarithmique ou non. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Indique si le type d'échelle de l'axe de valeurs est logarithmique ou non. |
| [getLogBase()](#getLogBase--) | Représente la base logarithmique. |
| [setLogBase(double value)](#setLogBase-double-) | Représente la base logarithmique. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Indique si MS PowerPoint trace les points de données de la dernière à la première. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Indique si MS PowerPoint trace les points de données de la dernière à la première. |
| [isVisible()](#isVisible--) | Indique si l'axe est visible. |
| [setVisible(boolean value)](#setVisible-boolean-) | Indique si l'axe est visible. |
| [getMajorTickMark()](#getMajorTickMark--) | Représente le type de graduation principale pour l'axe spécifié. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Représente le type de graduation principale pour l'axe spécifié. |
| [getMinorTickMark()](#getMinorTickMark--) | Représente le type de graduation secondaire pour l'axe spécifié. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Représente le type de graduation secondaire pour l'axe spécifié. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Représente la position des étiquettes de graduation sur l'axe spécifié. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Représente la position des étiquettes de graduation sur l'axe spécifié. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Représente l'échelle de l'unité principale pour l'axe de date. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Représente l'échelle de l'unité principale pour l'axe de date. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Représente l'échelle de l'unité principale pour l'axe de date. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Représente l'échelle de l'unité principale pour l'axe de date. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Spécifie la plus petite unité de temps représentée sur l'axe de date. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Spécifie la plus petite unité de temps représentée sur l'axe de date. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Représente le format des quadrillages secondaires sur un axe de graphique. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Représente le format des quadrillages principaux sur un axe de graphique. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Indique si les quadrillages secondaires sont affichés. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Indique si les quadrillages principaux sont affichés. |
| [getFormat()](#getFormat--) | Représente le format de l'axe. |
| [getTitle()](#getTitle--) | Obtient le titre de l'axe. |
| [getCrossType()](#getCrossType--) | Représente le CrossType sur l'axe spécifié où l'autre axe le croise. |
| [setCrossType(int value)](#setCrossType-int-) | Représente le CrossType sur l'axe spécifié où l'autre axe le croise. |
| [getPosition()](#getPosition--) | Représente la position de l'axe. |
| [setPosition(int value)](#setPosition-int-) | Représente la position de l'axe. |
| [hasTitle()](#hasTitle--) | Détermine si un axe possède un titre visible. |
| [setTitle(boolean value)](#setTitle-boolean-) | Détermine si un axe possède un titre visible. |
| [getNumberFormat()](#getNumberFormat--) | Représente la chaîne de format pour les étiquettes d'axe. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Représente la chaîne de format pour les étiquettes d'axe. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Indique si le format provient de données source liées. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Indique si le format provient de données source liées. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Représente l'angle de rotation des étiquettes de graduation Lecture/écriture float. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Représente l'angle de rotation des étiquettes de graduation Lecture/écriture float. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Spécifie le nombre d'étiquettes de graduation à sauter entre celles qui sont dessinées. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Spécifie le nombre d'étiquettes de graduation à sauter entre celles qui sont dessinées. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Spécifie la valeur d'espacement automatique des étiquettes de graduation. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Spécifie la valeur d'espacement automatique des étiquettes de graduation. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Spécifie le nombre de marques de graduation à sauter avant que la suivante ne soit dessinée. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Spécifie le nombre de marques de graduation à sauter avant que la suivante ne soit dessinée. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Spécifie la valeur d'espacement automatique des marques de graduation. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Spécifie la valeur d'espacement automatique des marques de graduation. |
| [getLabelOffset()](#getLabelOffset--) | Spécifie la distance des étiquettes par rapport à l'axe. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Spécifie la distance des étiquettes par rapport à l'axe. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Spécifie le type de l'axe de catégorie. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Spécifie le type de l'axe de catégorie. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Définit la propriété IAxis.CategoryAxisType avec une valeur déterminée automatiquement en fonction des données de l'axe. |
| [getAggregationType()](#getAggregationType--) | Représente le type d'agrégation de l'axe de catégorie (regroupement). |
| [setAggregationType(int value)](#setAggregationType-int-) | Représente le type d'agrégation de l'axe de catégorie (regroupement). |
| [getBinWidth()](#getBinWidth--) | Spécifie la largeur du bin lorsque la valeur de la propriété AggregationType est définie sur AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | Spécifie la largeur du bin lorsque la valeur de la propriété AggregationType est définie sur AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | Spécifie le nombre de bins lorsque la valeur de la propriété AggregationType est définie sur AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Spécifie le nombre de bins lorsque la valeur de la propriété AggregationType est définie sur AxisAggregationType.ByNumberOfBins. |
| [isOverflowBin()](#isOverflowBin--) | Indique si le bin de dépassement est appliqué. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Indique si le bin de dépassement est appliqué. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Spécifie la valeur automatique du bin de dépassement. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Spécifie la valeur automatique du bin de dépassement. |
| [getOverflowBin()](#getOverflowBin--) | Spécifie la valeur personnalisée du bin de dépassement. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Spécifie la valeur personnalisée du bin de dépassement. |
| [isUnderflowBin()](#isUnderflowBin--) | Indique si le bin de sous-flux est appliqué. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Indique si le bin de sous-flux est appliqué. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Spécifie la valeur automatique du bin de sous-flux. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Spécifie la valeur automatique du bin de sous-flux. |
| [getUnderflowBin()](#getUnderflowBin--) | Spécifie la valeur personnalisée du bin de sous-flux. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Spécifie la valeur personnalisée du bin de sous-flux. |

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public abstract boolean getAxisBetweenCategories()
```

Représente si l'axe de valeurs croise l'axe des catégories entre les catégories. Cette propriété ne s'applique qu'aux axes de catégorie et ne s'applique pas aux graphiques 3D. Lecture/écriture boolean.

**Retourne :**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public abstract void setAxisBetweenCategories(boolean value)
```

Représente si l'axe de valeurs croise l'axe des catégories entre les catégories. Cette propriété ne s'applique qu'aux axes de catégorie et ne s'applique pas aux graphiques 3D. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getCrossAt() {#getCrossAt--}
```
public abstract float getCrossAt()
```

Représente le point sur l'axe où l'axe perpendiculaire le croise. Lecture/écriture float.

**Retourne :**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public abstract void setCrossAt(float value)
```

Représente le point sur l'axe où l'axe perpendiculaire le croise. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public abstract int getDisplayUnit()
```

Spécifie la valeur d'échelle des unités d'affichage pour l'axe de valeurs. Lecture/écriture [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Retourne :**
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public abstract void setDisplayUnit(int value)
```

Spécifie la valeur d'échelle des unités d'affichage pour l'axe de valeurs. Lecture/écriture [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public abstract double getActualMaxValue()
```

Spécifie la valeur maximale réelle sur l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur réelle.

**Retourne :**
double

### getActualMinValue() {#getActualMinValue--}
```
public abstract double getActualMinValue()
```

Spécifie la valeur minimale réelle sur l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur réelle.

**Retourne :**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public abstract double getActualMajorUnit()
```

Spécifie l'unité principale réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur réelle.

**Retourne :**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public abstract double getActualMinorUnit()
```

Spécifie l'unité secondaire réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur réelle.

**Retourne :**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public abstract int getActualMajorUnitScale()
```

Spécifie l'échelle de l'unité principale réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur réelle.

**Retourne :**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public abstract int getActualMinorUnitScale()
```

Spécifie l'échelle de l'unité secondaire réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur réelle.

**Retourne :**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public abstract boolean isAutomaticMaxValue()
```

Indique si la valeur maximale est attribuée automatiquement. Lecture/écriture boolean.

**Retourne :**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public abstract void setAutomaticMaxValue(boolean value)
```

Indique si la valeur maximale est attribuée automatiquement. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public abstract double getMaxValue()
```

Représente la valeur maximale sur l'axe de valeurs. Lecture/écriture double.

**Retourne :**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public abstract void setMaxValue(double value)
```

Représente la valeur maximale sur l'axe de valeurs. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public abstract double getMinorUnit()
```

Représente les unités secondaires pour l'axe de date ou de valeurs. Lecture/écriture double.

**Retourne :**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public abstract void setMinorUnit(double value)
```

Représente les unités secondaires pour l'axe de date ou de valeurs. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public abstract boolean isAutomaticMinorUnit()
```

Indique si l'unité secondaire de l'axe est attribuée automatiquement. Lecture/écriture boolean.

**Retourne :**
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public abstract void setAutomaticMinorUnit(boolean value)
```

Indique si l'unité secondaire de l'axe est attribuée automatiquement. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public abstract double getMajorUnit()
```

Représente les unités principales pour l'axe de date ou de valeurs. Lecture/écriture double.

**Retourne :**
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public abstract void setMajorUnit(double value)
```

Représente les unités principales pour l'axe de date ou de valeurs. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public abstract boolean isAutomaticMajorUnit()
```

Indique si l'unité principale de l'axe est attribuée automatiquement. Lecture/écriture boolean.

**Retourne :**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public abstract void setAutomaticMajorUnit(boolean value)
```

Indique si l'unité principale de l'axe est attribuée automatiquement. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public abstract boolean isAutomaticMinValue()
```

Indique si la valeur minimale est attribuée automatiquement. Lecture/écriture booléen.

**Retour :**
boolean

### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public abstract void setAutomaticMinValue(boolean value)
```

Indique si la valeur minimale est attribuée automatiquement. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public abstract double getMinValue()
```

Représente la valeur minimale sur l'axe des valeurs. Lecture/écriture double.

**Retour :**
double

### setMinValue(double value) {#setMinValue-double-}
```
public abstract void setMinValue(double value)
```

Représente la valeur minimale sur l'axe des valeurs. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public abstract boolean isLogarithmic()
```

Représente si le type d'échelle de l'axe des valeurs est logarithmique ou non. Lecture/écriture booléen.

**Retour :**
boolean

### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public abstract void setLogarithmic(boolean value)
```

Représente si le type d'échelle de l'axe des valeurs est logarithmique ou non. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public abstract double getLogBase()
```

Représente la base logarithmique. La valeur par défaut est 10. Lecture/écriture double.

**Retour :**
double

### setLogBase(double value) {#setLogBase-double-}
```
public abstract void setLogBase(double value)
```

Représente la base logarithmique. La valeur par défaut est 10. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public abstract boolean isPlotOrderReversed()
```

Représente si MS PowerPoint trace les points de données du dernier au premier. Lecture/écriture booléen.

**Retour :**
boolean

### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public abstract void setPlotOrderReversed(boolean value)
```

Représente si MS PowerPoint trace les points de données du dernier au premier. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Représente si l'axe est visible. Lecture/écriture booléen.

**Retour :**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Représente si l'axe est visible. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public abstract int getMajorTickMark()
```

Représente le type de repère majeur pour l'axe spécifié. Lecture/écriture [TickMarkType](../../com.aspose.slides/tickmarktype).

**Retour :**
int

### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public abstract void setMajorTickMark(int value)
```

Représente le type de repère majeur pour l'axe spécifié. Lecture/écriture [TickMarkType](../../com.aspose.slides/tickmarktype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public abstract int getMinorTickMark()
```

Représente le type de repère mineur pour l'axe spécifié. Lecture/écriture [TickMarkType](../../com.aspose.slides/tickmarktype).

**Retour :**
int

### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public abstract void setMinorTickMark(int value)
```

Représente le type de repère mineur pour l'axe spécifié. Lecture/écriture [TickMarkType](../../com.aspose.slides/tickmarktype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public abstract int getTickLabelPosition()
```

Représente la position des étiquettes de repère sur l'axe spécifié. Lecture/écriture [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Retour :**
int

### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public abstract void setTickLabelPosition(int value)
```

Représente la position des étiquettes de repère sur l'axe spécifié. Lecture/écriture [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public abstract int getMajorUnitScale()
```

Représente l'échelle de l'unité principale pour l'axe de date. Lecture/écriture [TimeUnitType](../../com.aspose.slides/timeunittype).

**Retour :**
int

### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public abstract void setMajorUnitScale(int value)
```

Représente l'échelle de l'unité principale pour l'axe de date. Lecture/écriture [TimeUnitType](../../com.aspose.slides/timeunittype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public abstract int getMinorUnitScale()
```

Représente l'échelle de l'unité principale pour l'axe de date. Lecture/écriture [TimeUnitType](../../com.aspose.slides/timeunittype).

**Retour :**
int

### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public abstract void setMinorUnitScale(int value)
```

Représente l'échelle de l'unité principale pour l'axe de date. Lecture/écriture [TimeUnitType](../../com.aspose.slides/timeunittype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public abstract int getBaseUnitScale()
```

Spécifie la plus petite unité de temps représentée sur l'axe de date. Lecture/écriture [TimeUnitType](../../com.aspose.slides/timeunittype).

**Retour :**
int

### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public abstract void setBaseUnitScale(int value)
```

Spécifie la plus petite unité de temps représentée sur l'axe de date. Lecture/écriture [TimeUnitType](../../com.aspose.slides/timeunittype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

Représente le format des quadrillages mineurs sur un axe de diagramme. Lecture seule [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Retour :**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public abstract IChartLinesFormat getMajorGridLinesFormat()
```

Représente le format des quadrillages majeurs sur un axe de diagramme. Lecture seule [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Retour :**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public abstract boolean getShowMinorGridLines()
```

Indique si les quadrillages mineurs sont affichés. Lecture seule booléen.

**Retour :**
boolean

### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public abstract boolean getShowMajorGridLines()
```

Indique si les quadrillages majeurs sont affichés. Lecture seule booléen.

**Retour :**
boolean

### getFormat() {#getFormat--}
```
public abstract IAxisFormat getFormat()
```

Représente le format de l'axe. Lecture seule [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Retour :**
[IAxisFormat](../../com.aspose.slides/iaxisformat)

### getTitle() {#getTitle--}
```
public abstract IChartTitle getTitle()
```

Obtient le titre de l'axe. Lecture seule [IChartTitle](../../com.aspose.slides/icharttitle).

**Retour :**
[IChartTitle](../../com.aspose.slides/icharttitle)

### getCrossType() {#getCrossType--}
```
public abstract int getCrossType()
```

Représente le CrossType sur l'axe spécifié où l'autre axe croise. Lecture/écriture [CrossesType](../../com.aspose.slides/crossestype).

**Retour :**
int

### setCrossType(int value) {#setCrossType-int-}
```
public abstract void setCrossType(int value)
```

Représente le CrossType sur l'axe spécifié où l'autre axe croise. Lecture/écriture [CrossesType](../../com.aspose.slides/crossestype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Représente la position de l'axe. Lecture/écriture [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Retour :**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Représente la position de l'axe. Lecture/écriture [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

Détermine si un axe possède un titre visible. Lecture/écriture booléen.

**Retour :**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

Détermine si un axe possède un titre visible. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

Représente la chaîne de format pour les étiquettes d'axe. Lecture/écriture String.

**Retour :**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

Représente la chaîne de format pour les étiquettes d'axe. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Indique si le format est lié aux données source. Lecture/écriture booléen.

**Retour :**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Indique si le format est lié aux données source. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public abstract float getTickLabelRotationAngle()
```

Représente l'angle de rotation des étiquettes de repère. Lecture/écriture float.

**Retour :**
float

### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public abstract void setTickLabelRotationAngle(float value)
```

Représente l'angle de rotation des étiquettes de repère. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public abstract long getTickLabelSpacing()
```

Spécifie combien d'étiquettes de repère sauter entre les étiquettes affichées. Lecture/écriture long.

**Retour :**
long

### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public abstract void setTickLabelSpacing(long value)
```

Spécifie combien d'étiquettes de repère sauter entre les étiquettes affichées. Lecture/écriture long.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public abstract boolean isAutomaticTickLabelSpacing()
```

Spécifie la valeur d'espacement automatique des étiquettes de repère. Si false : utilisez la propriété TickLabelSpacing. Lecture/écriture booléen.

**Retour :**
boolean

### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public abstract void setAutomaticTickLabelSpacing(boolean value)
```

Spécifie la valeur d'espacement automatique des étiquettes de repère. Si false : utilisez la propriété TickLabelSpacing. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public abstract long getTickMarksSpacing()
```

Spécifie combien de repères doivent être sautés avant que le suivant ne soit dessiné. Appliqué à l'axe de catégorie ou de série. Lecture/écriture int.

**Retour :**
long

### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public abstract void setTickMarksSpacing(long value)
```

Spécifie combien de repères doivent être sautés avant que le suivant ne soit dessiné. Appliqué à l'axe de catégorie ou de série. Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public abstract boolean isAutomaticTickMarksSpacing()
```

Spécifie la valeur d'espacement automatique des repères. Si false : utilisez la propriété TickMarksSpacing. Lecture/écriture booléen.

**Retour :**
boolean

### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public abstract void setAutomaticTickMarksSpacing(boolean value)
```

Spécifie la valeur d'espacement automatique des repères. Si false : utilisez la propriété TickMarksSpacing. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public abstract int getLabelOffset()
```

Spécifie la distance des étiquettes par rapport à l'axe. Appliqué à l'axe de catégorie ou de date. La valeur doit être comprise entre 0% et 1000%. Lecture/écriture int.

**Retour :**
int

### setLabelOffset(int value) {#setLabelOffset-int-}
```
public abstract void setLabelOffset(int value)
```

Spécifie la distance des étiquettes par rapport à l'axe. Appliqué à l'axe de catégorie ou de date. La valeur doit être comprise entre 0% et 1000%. Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public abstract int getCategoryAxisType()
```

Spécifie le type de l'axe de catégorie. Lecture/écriture [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Retour :**
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public abstract void setCategoryAxisType(int value)
```

Spécifie le type de l'axe de catégorie. Lecture/écriture [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Paramètres :**
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

Représente le type d'agrégation de l'axe de catégorie (regroupement). Appliqué à la catégorie. Utilisé uniquement avec les séries Histogram ou HistogramPareto.

**Retour :**
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public abstract void setAggregationType(int value)
```

Représente le type d'agrégation de l'axe de catégorie (regroupement). Appliqué à la catégorie. Utilisé uniquement avec les séries Histogram ou HistogramPareto.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getBinWidth() {#getBinWidth--}
```
public abstract double getBinWidth()
```

Spécifie la largeur du bin lorsque la valeur de la propriété AggregationType est définie sur AxisAggregationType.ByBinWidth. Appliqué aux axes de catégorie. Utilisé uniquement avec les séries Histogram ou HistogramPareto.

**Renvoie :**
double
### setBinWidth(double value) {#setBinWidth-double-}
```
public abstract void setBinWidth(double value)
```

Spécifie la largeur du bin lorsque la valeur de la propriété AggregationType est définie sur AxisAggregationType.ByBinWidth. Appliqué aux axes de catégorie. Utilisé uniquement avec les séries Histogram ou HistogramPareto.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public abstract long getNumberOfBins()
```

Spécifie le nombre de bins lorsque la valeur de la propriété AggregationType est définie sur AxisAggregationType.ByNumberOfBins. Appliqué aux axes de catégorie. Utilisé uniquement avec les séries Histogram ou HistogramPareto.

**Renvoie :**
long
### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public abstract void setNumberOfBins(long value)
```

Spécifie le nombre de bins lorsque la valeur de la propriété AggregationType est définie sur AxisAggregationType.ByNumberOfBins. Appliqué aux axes de catégorie. Utilisé uniquement avec les séries Histogram ou HistogramPareto.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public abstract boolean isOverflowBin()
```

Spécifie si le bin de débordement est appliqué. Utilisez IsAutomaticOverflowBin et OverflowBin pour ajuster la valeur du bin de débordement.

**Renvoie :**
boolean
### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public abstract void setOverflowBin(boolean value)
```

Spécifie si le bin de débordement est appliqué. Utilisez IsAutomaticOverflowBin et OverflowBin pour ajuster la valeur du bin de débordement.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public abstract boolean isAutomaticOverflowBin()
```

Spécifie la valeur automatique du bin de débordement. Si false : utilisez la propriété OverflowBin.

**Renvoie :**
boolean
### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public abstract void setAutomaticOverflowBin(boolean value)
```

Spécifie la valeur automatique du bin de débordement. Si false : utilisez la propriété OverflowBin.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public abstract double getOverflowBin()
```

Spécifie la valeur personnalisée du bin de débordement. Appliquée lorsque la propriété IsAutomaticOverflowBin est définie sur false et que la propriété IsOverflowBin vaut true.

**Renvoie :**
double
### setOverflowBin(double value) {#setOverflowBin-double-}
```
public abstract void setOverflowBin(double value)
```

Spécifie la valeur personnalisée du bin de débordement. Appliquée lorsque la propriété IsAutomaticOverflowBin est définie sur false et que la propriété IsOverflowBin vaut true.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public abstract boolean isUnderflowBin()
```

Spécifie si le bin de sous-débordement est appliqué. Utilisez IsAutomaticUnderflowBin et UnderflowBin pour ajuster la valeur du bin de sous-débordement.

**Renvoie :**
boolean
### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public abstract void setUnderflowBin(boolean value)
```

Spécifie si le bin de sous-débordement est appliqué. Utilisez IsAutomaticUnderflowBin et UnderflowBin pour ajuster la valeur du bin de sous-débordement.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public abstract boolean isAutomaticUnderflowBin()
```

Spécifie la valeur automatique du bin de sous-débordement. Si false : utilisez la propriété UnderflowBin.

**Renvoie :**
boolean
### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public abstract void setAutomaticUnderflowBin(boolean value)
```

Spécifie la valeur automatique du bin de sous-débordement. Si false : utilisez la propriété UnderflowBin.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public abstract double getUnderflowBin()
```

Spécifie la valeur personnalisée du bin de sous-débordement. Appliquée lorsque la propriété IsAutomaticUnderflowBin est définie sur false et que la propriété IsUnderflowBin vaut true.

**Renvoie :**
double
### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public abstract void setUnderflowBin(double value)
```

Spécifie la valeur personnalisée du bin de sous-débordement. Appliquée lorsque la propriété IsAutomaticUnderflowBin est définie sur false et que la propriété IsUnderflowBin vaut true.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |