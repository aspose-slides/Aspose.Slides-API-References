---
title: Axis
second_title: Référence API Java d'Aspose.Slides pour Android
description: Encapsule l'objet qui représente l'axe d'un graphique.
type: docs
url: /fr/com.aspose.slides/axis/
---
**Héritage :**
java.lang.Object, com.aspose.slides.DomObject

**Toutes les interfaces implémentées :**
[com.aspose.slides.IAxis](../../com.aspose.slides/iaxis)
```
public class Axis extends DomObject<AxesManager> implements IAxis
```

Encapsule l'objet qui représente l'axe d'un graphique.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getChart()](#getChart--) | Retourne le graphique parent. |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Indique si l'axe des valeurs croise l'axe des catégories entre les catégories. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Indique si l'axe des valeurs croise l'axe des catégories entre les catégories. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Spécifie le type de l'axe des catégories. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Spécifie le type de l'axe des catégories. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Définit la propriété IAxis.CategoryAxisType avec une valeur déterminée automatiquement à partir des données de l'axe. |
| [getCrossAt()](#getCrossAt--) | Indique le point de l'axe où l'axe perpendiculaire le traverse. |
| [setCrossAt(float value)](#setCrossAt-float-) | Indique le point de l'axe où l'axe perpendiculaire le traverse. |
| [getDisplayUnit()](#getDisplayUnit--) | Spécifie la valeur d'échelle des unités d'affichage pour l'axe des valeurs. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Spécifie la valeur d'échelle des unités d'affichage pour l'axe des valeurs. |
| [getActualMaxValue()](#getActualMaxValue--) | Spécifie la valeur maximale réelle sur l'axe. |
| [getActualMinValue()](#getActualMinValue--) | Spécifie la valeur minimale réelle sur l'axe. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Spécifie l'unité majeure réelle de l'axe. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Spécifie l'unité mineure réelle de l'axe. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Spécifie l'échelle d'unité majeure réelle de l'axe. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Spécifie l'échelle d'unité mineure réelle de l'axe. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Indique si la valeur maximale est attribuée automatiquement. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Indique si la valeur maximale est attribuée automatiquement. |
| [getMaxValue()](#getMaxValue--) | Représente la valeur maximale sur l'axe des valeurs. |
| [setMaxValue(double value)](#setMaxValue-double-) | Représente la valeur maximale sur l'axe des valeurs. |
| [getMinorUnit()](#getMinorUnit--) | Représente les unités mineures pour l'axe de date ou de valeur. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Représente les unités mineures pour l'axe de date ou de valeur. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Indique si l'unité mineure de l'axe est attribuée automatiquement. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Indique si l'unité mineure de l'axe est attribuée automatiquement. |
| [getMajorUnit()](#getMajorUnit--) | Représente les unités majeures pour l'axe de date ou de valeur. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Représente les unités majeures pour l'axe de date ou de valeur. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Indique si l'unité majeure de l'axe est attribuée automatiquement. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Indique si l'unité majeure de l'axe est attribuée automatiquement. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Indique si la valeur minimale est attribuée automatiquement. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Indique si la valeur minimale est attribuée automatiquement. |
| [getMinValue()](#getMinValue--) | Représente la valeur minimale sur l'axe des valeurs. |
| [setMinValue(double value)](#setMinValue-double-) | Représente la valeur minimale sur l'axe des valeurs. |
| [isLogarithmic()](#isLogarithmic--) | Indique si le type d'échelle de l'axe des valeurs est logarithmique ou non. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Indique si le type d'échelle de l'axe des valeurs est logarithmique ou non. |
| [getLogBase()](#getLogBase--) | Représente la base logarithmique. |
| [setLogBase(double value)](#setLogBase-double-) | Représente la base logarithmique. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Indique si MS PowerPoint trace les points de données de la fin vers le début. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Indique si MS PowerPoint trace les points de données de la fin vers le début. |
| [isVisible()](#isVisible--) | Indique si l'axe est visible. |
| [setVisible(boolean value)](#setVisible-boolean-) | Indique si l'axe est visible. |
| [getMajorTickMark()](#getMajorTickMark--) | Représente le type de marqueur de graduation majeure pour l'axe spécifié. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Représente le type de marqueur de graduation majeure pour l'axe spécifié. |
| [getMinorTickMark()](#getMinorTickMark--) | Représente le type de marqueur de graduation mineure pour l'axe spécifié. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Représente le type de marqueur de graduation mineure pour l'axe spécifié. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Représente la position des libellés de graduation sur l'axe spécifié. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Représente la position des libellés de graduation sur l'axe spécifié. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Représente l'échelle d'unité majeure pour l'axe de date. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Représente l'échelle d'unité majeure pour l'axe de date. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Représente l'échelle d'unité majeure pour l'axe de date. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Représente l'échelle d'unité majeure pour l'axe de date. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Spécifie la plus petite unité de temps représentée sur l'axe de date. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Spécifie la plus petite unité de temps représentée sur l'axe de date. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Représente le format des quadrillages mineurs sur un axe de graphique. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Représente le format des quadrillages majeurs sur un axe de graphique. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Pour masquer le quadrillage mineur, définissez MinorGridLinesFormat.Line.FillFormat.FillType sur FillType.NoFill. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Pour masquer le quadrillage majeur, définissez MajorGridLinesFormat.Line.FillFormat.FillType sur FillType.NoFill. |
| [getFormat()](#getFormat--) | Représente le format de l'axe. |
| [getTextFormat()](#getTextFormat--) | Représente le format du texte. |
| [getTitle()](#getTitle--) | Obtient le titre de l'axe. |
| [getCrossType()](#getCrossType--) | Représente le CrossType sur l'axe spécifié où l'autre axe le croise. |
| [setCrossType(int value)](#setCrossType-int-) | Représente le CrossType sur l'axe spécifié où l'autre axe le croise. |
| [getPosition()](#getPosition--) | Représente la position de l'axe. |
| [setPosition(int value)](#setPosition-int-) | Représente la position de l'axe. |
| [hasTitle()](#hasTitle--) | Détermine si un axe possède un titre visible. |
| [setTitle(boolean value)](#setTitle-boolean-) | Détermine si un axe possède un titre visible. |
| [getNumberFormat()](#getNumberFormat--) | Représente la chaîne de format pour les libellés d'axe. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Représente la chaîne de format pour les libellés d'axe. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Indique si le format est lié aux données sources. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Indique si le format est lié aux données sources. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Représente l'angle de rotation des libellés de graduation. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Représente l'angle de rotation des libellés de graduation. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Spécifie le nombre de libellés de graduation à sauter entre ceux qui sont dessinés. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Spécifie le nombre de libellés de graduation à sauter entre ceux qui sont dessinés. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Spécifie la valeur d'espacement automatique des libellés de graduation. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Spécifie la valeur d'espacement automatique des libellés de graduation. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Spécifie le nombre de marques de graduation à sauter avant d'en dessiner une autre. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Spécifie le nombre de marques de graduation à sauter avant d'en dessiner une autre. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Spécifie la valeur d'espacement automatique des marques de graduation. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Spécifie la valeur d'espacement automatique des marques de graduation. |
| [getLabelOffset()](#getLabelOffset--) | Spécifie la distance des libellés par rapport à l'axe. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Spécifie la distance des libellés par rapport à l'axe. |
| [getAggregationType()](#getAggregationType--) | Représente le type d'agrégation de l'axe des catégories (groupement). |
| [setAggregationType(int value)](#setAggregationType-int-) | Représente le type d'agrégation de l'axe des catégories (groupement). |
| [getBinWidth()](#getBinWidth--) | Spécifie la largeur du bin lorsque la propriété AggregationType est définie sur AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | Spécifie la largeur du bin lorsque la propriété AggregationType est définie sur AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | Spécifie le nombre de bins lorsque la propriété AggregationType est définie sur AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Spécifie le nombre de bins lorsque la propriété AggregationType est définie sur AxisAggregationType.ByNumberOfBins. |
| [isOverflowBin()](#isOverflowBin--) | Indique si un bin de dépassement est appliqué. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Indique si un bin de dépassement est appliqué. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Spécifie la valeur automatique du bin de dépassement. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Spécifie la valeur automatique du bin de dépassement. |
| [getOverflowBin()](#getOverflowBin--) | Spécifie la valeur personnalisée du bin de dépassement. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Spécifie la valeur personnalisée du bin de dépassement. |
| [isUnderflowBin()](#isUnderflowBin--) | Indique si un bin de sous-dépassement est appliqué. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Indique si un bin de sous-dépassement est appliqué. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Spécifie la valeur automatique du bin de sous-dépassement. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Spécifie la valeur automatique du bin de sous-dépassement. |
| [getUnderflowBin()](#getUnderflowBin--) | Spécifie la valeur personnalisée du bin de sous-dépassement. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Spécifie la valeur personnalisée du bin de sous-dépassement. |
| [getSlide()](#getSlide--) | Retourne la diapositive parent d'un FillFormat. |
| [getPresentation()](#getPresentation--) | Retourne la présentation parent d'un FillFormat. |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Retourne le graphique parent. Lecture seule [IChart](../../com.aspose.slides/ichart).

**Retour :**
[IChart](../../com.aspose.slides/ichart)

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public final boolean getAxisBetweenCategories()
```

Indique si l'axe des valeurs croise l'axe des catégories entre les catégories. Cette propriété s'applique uniquement aux axes des catégories et ne s'applique pas aux graphiques 3-D. Lecture/écriture booléen.

**Retour :**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public final void setAxisBetweenCategories(boolean value)
```

Indique si l'axe des valeurs croise l'axe des catégories entre les catégories. Cette propriété s'applique uniquement aux axes des catégories et ne s'applique pas aux graphiques 3-D. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public final int getCategoryAxisType()
```

Spécifie le type de l'axe des catégories. Lecture/écriture [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Retour :**
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public final void setCategoryAxisType(int value)
```

Spécifie le type de l'axe des catégories. Lecture/écriture [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public final void setCategoryAxisTypeAutomatically()
```

Définit la propriété IAxis.CategoryAxisType avec une valeur déterminée automatiquement à partir des données de l'axe.

### getCrossAt() {#getCrossAt--}
```
public final float getCrossAt()
```

Indique le point sur l'axe où l'axe perpendiculaire le traverse. Lecture/écriture float.

**Retour :**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public final void setCrossAt(float value)
```

Indique le point sur l'axe où l'axe perpendiculaire le traverse. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public final int getDisplayUnit()
```

Spécifie la valeur d'échelle des unités d'affichage pour l'axe des valeurs. Lecture/écriture [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Retour :**
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public final void setDisplayUnit(int value)
```

Spécifie la valeur d'échelle des unités d'affichage pour l'axe des valeurs. Lecture/écriture [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public final double getActualMaxValue()
```

Spécifie la valeur maximale réelle sur l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur réelle.

**Retour :**
double

### getActualMinValue() {#getActualMinValue--}
```
public final double getActualMinValue()
```

Spécifie la valeur minimale réelle sur l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur réelle.

**Retour :**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public final double getActualMajorUnit()
```

Spécifie l'unité majeure réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur réelle.

**Retour :**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public final double getActualMinorUnit()
```

Spécifie l'unité mineure réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur réelle.

**Retour :**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public final int getActualMajorUnitScale()
```

Spécifie l'échelle d'unité majeure réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur réelle.

**Retour :**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public final int getActualMinorUnitScale()
```

Spécifie l'échelle d'unité mineure réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur réelle.

**Retour :**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public final boolean isAutomaticMaxValue()
```

Indique si la valeur maximale est attribuée automatiquement. Lecture/écriture booléen.

**Retour :**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public final void setAutomaticMaxValue(boolean value)
```

Indique si la valeur maximale est attribuée automatiquement. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public final double getMaxValue()
```

Représente la valeur maximale sur l'axe des valeurs. Lecture/écriture double.

**Retour :**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public final void setMaxValue(double value)
```

Représente la valeur maximale sur l'axe des valeurs. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public final double getMinorUnit()
```

Représente les unités mineures pour l'axe de date ou de valeur. Lecture/écriture double.

**Retour :**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public final void setMinorUnit(double value)
```

Représente les unités mineures pour l'axe de date ou de valeur. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public final boolean isAutomaticMinorUnit()
```

Indique si l'unité mineure de l'axe est attribuée automatiquement. Lecture/écriture booléen.

**Retour :**
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public final void setAutomaticMinorUnit(boolean value)
```

Indique si l'unité mineure de l'axe est attribuée automatiquement. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public final double getMajorUnit()
```

Représente les unités majeures pour l'axe de date ou de valeur. Lecture/écriture double.

**Retour :**
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public final void setMajorUnit(double value)
```

Représente les unités majeures pour l'axe de date ou de valeur. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public final boolean isAutomaticMajorUnit()
```

Indique si l'unité majeure de l'axe est attribuée automatiquement. Lecture/écriture booléen.

**Retour :**
boolean

### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public final void setAutomaticMajorUnit(boolean value)
```

Indique si l'unité majeure de l'axe est attribuée automatiquement. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public final boolean isAutomaticMinValue()
```

Indique si la valeur minimale est attribuée automatiquement. Lecture/écriture booléen.

**Retour :**
boolean

### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public final void setAutomaticMinValue(boolean value)
```

Indique si la valeur minimale est attribuée automatiquement. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public final double getMinValue()
```

Représente la valeur minimale sur l'axe des valeurs. Lecture/écriture double.

**Retour :**
double

### setMinValue(double value) {#setMinValue-double-}
```
public final void setMinValue(double value)
```

Représente la valeur minimale sur l'axe des valeurs. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public final boolean isLogarithmic()
```

Indique si le type d'échelle de l'axe des valeurs est logarithmique ou non. Lecture/écriture booléen.

**Retour :**
boolean

### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public final void setLogarithmic(boolean value)
```

Indique si le type d'échelle de l'axe des valeurs est logarithmique ou non. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public final double getLogBase()
```

Représente la base logarithmique. La valeur par défaut est 10. Lecture/écriture double.

**Retour :**
double

### setLogBase(double value) {#setLogBase-double-}
```
public final void setLogBase(double value)
```

Représente la base logarithmique. La valeur par défaut est 10. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public final boolean isPlotOrderReversed()
```

Indique si MS PowerPoint trace les points de données de la fin vers le début. Lecture/écriture booléen.

**Retour :**
boolean

### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public final void setPlotOrderReversed(boolean value)
```

Indique si MS PowerPoint trace les points de données de la fin vers le début. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

Indique si l'axe est visible. Lecture/écriture booléen.

**Retour :**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

Indique si l'axe est visible. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public final int getMajorTickMark()
```

Représente le type de marqueur de graduation majeure pour l'axe spécifié. Lecture/écriture [TickMarkType](../../com.aspose.slides/tickmarktype).

**Retour :**
int

### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public final void setMajorTickMark(int value)
```

Représente le type de marqueur de graduation majeure pour l'axe spécifié. Lecture/écriture [TickMarkType](../../com.aspose.slides/tickmarktype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public final int getMinorTickMark()
```

Représente le type de marqueur de graduation mineure pour l'axe spécifié. Lecture/écriture [TickMarkType](../../com.aspose.slides/tickmarktype).

**Retour :**
int

### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public final void setMinorTickMark(int value)
```

Représente le type de marqueur de graduation mineure pour l'axe spécifié. Lecture/écriture [TickMarkType](../../com.aspose.slides/tickmarktype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public final int getTickLabelPosition()
```

Représente la position des libellés de graduation sur l'axe spécifié. Lecture/écriture [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Retour :**
int

### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public final void setTickLabelPosition(int value)
```

Représente la position des libellés de graduation sur l'axe spécifié. Lecture/écriture [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public final int getMajorUnitScale()
```

Représente l'échelle d'unité majeure pour l'axe de date. Lecture/écriture [TimeUnitType](../../com.aspose.slides/timeunittype).

**Retour :**
int

### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public final void setMajorUnitScale(int value)
```

Représente l'échelle d'unité majeure pour l'axe de date. Lecture/écriture [TimeUnitType](../../com.aspose.slides/timeunittype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public final int getMinorUnitScale()
```

Représente l'échelle d'unité majeure pour l'axe de date. Lecture/écriture [TimeUnitType](../../com.aspose.slides/timeunittype).

**Retour :**
int

### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public final void setMinorUnitScale(int value)
```

Représente l'échelle d'unité majeure pour l'axe de date. Lecture/écriture [TimeUnitType](../../com.aspose.slides/timeunittype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public final int getBaseUnitScale()
```

Spécifie la plus petite unité de temps représentée sur l'axe de date. Lecture/écriture [TimeUnitType](../../com.aspose.slides/timeunittype).

**Retour :**
int

### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public final void setBaseUnitScale(int value)
```

Spécifie la plus petite unité de temps représentée sur l'axe de date. Lecture/écriture [TimeUnitType](../../com.aspose.slides/timeunittype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public final IChartLinesFormat getMinorGridLinesFormat()
```

Représente le format des quadrillages mineurs sur un axe de graphique. Lecture seule [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Retour :**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public final IChartLinesFormat getMajorGridLinesFormat()
```

Représente le format des quadrillages majeurs sur un axe de graphique. Lecture seule [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Retour :**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public final boolean getShowMinorGridLines()
```

Pour masquer le quadrillage mineur, définissez MinorGridLinesFormat.Line.FillFormat.FillType sur FillType.NoFill. Lecture seule booléen.

**Retour :**
boolean

### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public final boolean getShowMajorGridLines()
```

Pour masquer le quadrillage majeur, définissez MajorGridLinesFormat.Line.FillFormat.FillType sur FillType.NoFill. Lecture seule booléen.

**Retour :**
boolean

### getFormat() {#getFormat--}
```
public final IAxisFormat getFormat()
```

Représente le format de l'axe. Lecture seule [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Retour :**
[IAxisFormat](../../com.aspose.slides/iaxisformat)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Représente le format du texte. Lecture seule [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Retour :**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getTitle() {#getTitle--}
```
public final IChartTitle getTitle()
```

Obtient le titre de l'axe. Lecture seule [IChartTitle](../../com.aspose.slides/icharttitle).

**Retour :**
[IChartTitle](../../com.aspose.slides/icharttitle)

### getCrossType() {#getCrossType--}
```
public final int getCrossType()
```

Représente le CrossType sur l'axe spécifié où l'autre axe le croise. Lecture/écriture [CrossesType](../../com.aspose.slides/crossestype).

**Retour :**
int

### setCrossType(int value) {#setCrossType-int-}
```
public final void setCrossType(int value)
```

Représente le CrossType sur l'axe spécifié où l'autre axe le croise. Lecture/écriture [CrossesType](../../com.aspose.slides/crossestype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```

Représente la position de l'axe. Lecture/écriture [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Retour :**
int

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Représente la position de l'axe. Lecture/écriture [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

Détermine si un axe possède un titre visible. Lecture/écriture booléen.

**Retour :**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

Détermine si un axe possède un titre visible. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

Représente la chaîne de format pour les libellés d'axe. Lecture/écriture java.lang.String.

**Retour :**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

Représente la chaîne de format pour les libellés d'axe. Lecture/écriture java.lang.String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

Indique si le format est lié aux données sources. Lecture/écriture booléen.

**Retour :**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

Indique si le format est lié aux données sources. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public final float getTickLabelRotationAngle()
```

Représente l'angle de rotation des libellés de graduation. Lecture/écriture float.

**Retour :**
float

### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public final void setTickLabelRotationAngle(float value)
```

Représente l'angle de rotation des libellés de graduation. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public final long getTickLabelSpacing()
```

Spécifie le nombre de libellés de graduation à sauter entre ceux qui sont dessinés. Appliqué aux axes de catégorie ou de série. Lecture/écriture long.

**Retour :**
long

### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public final void setTickLabelSpacing(long value)
```

Spécifie le nombre de libellés de graduation à sauter entre ceux qui sont dessinés. Appliqué aux axes de catégorie ou de série. Lecture/écriture long.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public final boolean isAutomaticTickLabelSpacing()
```

Spécifie la valeur d'espacement automatique des libellés de graduation. Si false : utilisez la propriété TickLabelSpacing. Lecture/écriture booléen.

**Retour :**
boolean

### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public final void setAutomaticTickLabelSpacing(boolean value)
```

Spécifie la valeur d'espacement automatique des libellés de graduation. Si false : utilisez la propriété TickLabelSpacing. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public final long getTickMarksSpacing()
```

Spécifie le nombre de marques de graduation à sauter avant d'en dessiner une autre. Appliqué aux axes de catégorie ou de série. Lecture/écriture int.

**Retour :**
long

### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public final void setTickMarksSpacing(long value)
```

Spécifie le nombre de marques de graduation à sauter avant d'en dessiner une autre. Appliqué aux axes de catégorie ou de série. Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public final boolean isAutomaticTickMarksSpacing()
```

Spécifie la valeur d'espacement automatique des marques de graduation. Si false : utilisez la propriété TickMarksSpacing. Lecture/écriture booléen.

**Retour :**
boolean

### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public final void setAutomaticTickMarksSpacing(boolean value)
```

Spécifie la valeur d'espacement automatique des marques de graduation. Si false : utilisez la propriété TickMarksSpacing. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public final int getLabelOffset()
```

Spécifie la distance des libellés par rapport à l'axe. Appliqué aux axes de catégorie ou de date. La valeur doit être comprise entre 0 % et 1000 %. Lecture/écriture int.

**Retour :**
int

### setLabelOffset(int value) {#setLabelOffset-int-}
```
public final void setLabelOffset(int value)
```

Spécifie la distance des libellés par rapport à l'axe. Appliqué aux axes de catégorie ou de date. La valeur doit être comprise entre 0 % et 1000 %. Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAggregationType() {#getAggregationType--}
```
public final int getAggregationType()
```

Représente le type d'agrégation de l'axe des catégories (groupement). Appliqué aux catégories. Utilisé uniquement avec les séries Histogram ou HistogramPareto.

**Retour :**
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public final void setAggregationType(int value)
```

Représente le type d'agrégation de l'axe des catégories (groupement). Appliqué aux catégories. Utilisé uniquement avec les séries Histogram ou HistogramPareto.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public final double getBinWidth()
```

Spécifie la largeur du bin lorsque la propriété AggregationType est définie sur AxisAggregationType.ByBinWidth. Appliqué aux axes de catégorie. Utilisé uniquement avec les séries Histogram ou HistogramPareto.

**Retour :**
double

### setBinWidth(double value) {#setBinWidth-double-}
```
public....



```

Spécifie la largeur du bin lorsque la propriété AggregationType est définie sur AxisAggregationType.ByBinWidth. Appliqué aux axes de catégorie. Utilisé uniquement avec les séries Histogram ou HistogramPareto.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public final long getNumberOfBins()
```

Spécifie le nombre de bins lorsque la propriété AggregationType est définie sur AxisAggregationType.ByNumberOfBins. Appliqué aux axes de catégorie. Utilisé uniquement avec les séries Histogram ou HistogramPareto.

**Retour :**
long

### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public final void setNumberOfBins(long value)
```

Spécifie le nombre de bins lorsque la propriété AggregationType est définie sur AxisAggregationType.ByNumberOfBins. Appliqué aux axes de catégorie. Utilisé uniquement avec les séries Histogram ou HistogramPareto.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public final boolean isOverflowBin()
```

Indique si un bin de dépassement est appliqué. Utilisez IsAutomaticOverflowBin et OverflowBin pour ajuster la valeur du bin de dépassement.

**Retour :**
boolean

### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public final void setOverflowBin(boolean value)
```

Indique si un bin de dépassement est appliqué. Utilisez IsAutomaticOverflowBin et OverflowBin pour ajuster la valeur du bin de dépassement.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public final boolean isAutomaticOverflowBin()
```

Spécifie la valeur automatique du bin de dépassement. Si false : utilisez la propriété OverflowBin.

**Retour :**
boolean

### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public final void setAutomaticOverflowBin(boolean value)
```

Spécifie la valeur automatique du bin de dépassement. Si false : utilisez la propriété OverflowBin.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public final double getOverflowBin()
```

Spécifie la valeur personnalisée du bin de dépassement. Appliquée lorsque IsAutomaticOverflowBin est false et IsOverflowBin est true.

**Retour :**
double

### setOverflowBin(double value) {#setOverflowBin-double-}
```
public final void setOverflowBin(double value)
```

Spécifie la valeur personnalisée du bin de dépassement. Appliquée lorsque IsAutomaticOverflowBin est false et IsOverflowBin est true.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public final boolean isUnderflowBin()
```

Indique si un bin de sous-dépassement est appliqué. Utilisez IsAutomaticUnderflowBin et UnderflowBin pour ajuster la valeur du bin de sous-dépassement.

**Retour :**
boolean

### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public final void setUnderflowBin(boolean value)
```

Indique si un bin de sous-dépassement est appliqué. Utilisez IsAutomaticUnderflowBin et UnderflowBin pour ajuster la valeur du bin de sous-dépassement.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public final boolean isAutomaticUnderflowBin()
```

Spécifie la valeur automatique du bin de sous-dépassement. Si false : utilisez la propriété UnderflowBin.

**Retour :**
boolean

### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public final void setAutomaticUnderflowBin(boolean value)
```

Spécifie la valeur automatique du bin de sous-dépassement. Si false : utilisez la propriété UnderflowBin.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public final double getUnderflowBin()
```

Spécifie la valeur personnalisée du bin de sous-dépassement. Appliquée lorsque IsAutomaticUnderflowBin est false et IsUnderflowBin est true.

**Retour :**
double

### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public final void setUnderflowBin(double value)
```

Spécifie la valeur personnalisée du bin de sous-dépassement. Appliquée lorsque IsAutomaticUnderflowBin est false et IsUnderflowBin est true.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Retourne la diapositive parent d'un FillFormat. Lecture seule [BaseSlide](../../com.aspose.slides/baseslide).

**Retour :**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Retourne la présentation parent d'un FillFormat. Lecture seule [IPresentation](../../com.aspose.slides/ipresentation).

**Retour :**
[IPresentation](../../com.aspose.slides/ipresentation)