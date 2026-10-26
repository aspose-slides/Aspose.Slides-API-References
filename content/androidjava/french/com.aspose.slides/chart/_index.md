---
title: Chart
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente un graphique sur une diapositive.
type: docs
url: /fr/com.aspose.slides/chart/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IChart](../../com.aspose.slides/ichart)
```
public class Chart extends GraphicalObject implements IChart
```

Représente un graphique sur une diapositive.
## Méthodes

| Méthode | Description |
| --- | --- |
| [validateChartLayout()](#validateChartLayout--) | Calcule les valeurs réelles des éléments du graphique. |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | Détermine si seules les cellules visibles sont tracées. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | Détermine si seules les cellules visibles sont tracées. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | Renvoie ou définit la façon de tracer les cellules vides sur un graphique. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | Renvoie ou définit la façon de tracer les cellules vides sur un graphique. |
| [getChartData()](#getChartData--) | Renvoie des informations sur les données liées ou incorporées associées à un graphique. |
| [hasTitle()](#hasTitle--) | Détermine si un graphique possède un titre visible. |
| [setTitle(boolean value)](#setTitle-boolean-) | Détermine si un graphique possède un titre visible. |
| [getChartTitle()](#getChartTitle--) | Renvoie ou définit le titre du graphique. |
| [hasDataTable()](#hasDataTable--) | Détermine si un graphique possède un tableau de données. |
| [setDataTable(boolean value)](#setDataTable-boolean-) | Détermine si un graphique possède un tableau de données. |
| [hasLegend()](#hasLegend--) | Détermine si un graphique possède une légende. |
| [setLegend(boolean value)](#setLegend-boolean-) | Détermine si un graphique possède une légende. |
| [getLegend()](#getLegend--) | Renvoie ou définit une légende pour un graphique. |
| [getChartDataTable()](#getChartDataTable--) | Renvoie un tableau de données d'un graphique. |
| [getStyle()](#getStyle--) | Renvoie ou définit le style du graphique. |
| [setStyle(int value)](#setStyle-int-) | Renvoie ou définit le style du graphique. |
| [getType()](#getType--) | Renvoie ou définit le type du graphique. |
| [setType(int value)](#setType-int-) | Renvoie ou définit le type du graphique. |
| [getPlotArea()](#getPlotArea--) | Représente la zone de tracé d'un graphique. |
| [getRotation3D()](#getRotation3D--) | Renvoie une rotation 3D d'un graphique. |
| [getBackWall()](#getBackWall--) | Renvoie un objet qui permet de changer le format du mur arrière d'un graphique 3D. |
| [getSideWall()](#getSideWall--) | Renvoie un objet qui permet de changer le format du mur latéral d'un graphique 3D. |
| [getFloor()](#getFloor--) | Renvoie un objet qui permet de changer le format du sol d'un graphique 3D. |
| [getTextFormat()](#getTextFormat--) | Renvoie le format du texte du graphique. |
| [createThemeEffective()](#createThemeEffective--) | Renvoie un thème effectif pour ce graphique. |
| [getThemeManager()](#getThemeManager--) | Renvoie le gestionnaire de thèmes. |
| [getUserShapes()](#getUserShapes--) | Spécifie les formes dessinées au-dessus du graphique. |
| [getAxes()](#getAxes--) | Fournit l'accès aux axes du graphique. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | Spécifie que les étiquettes de données au-dessus du maximum du graphique doivent être affichées. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | Spécifie que les étiquettes de données au-dessus du maximum du graphique doivent être affichées. |
| [hasRoundedCorners()](#hasRoundedCorners--) | Spécifie que la zone du graphique doit avoir des coins arrondis. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | Spécifie que la zone du graphique doit avoir des coins arrondis. |
| [getChart()](#getChart--) |  |
### validateChartLayout() {#validateChartLayout--}
```
public final void validateChartLayout()
```

Calcule les valeurs réelles des éléments du graphique. Les valeurs réelles incluent la position des éléments qui implémentent l'interface IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) et les valeurs réelles des axes (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public final boolean getPlotVisibleCellsOnly()
```

Détermine si seules les cellules visibles sont tracées. False pour tracer à la fois les cellules visibles et cachées. Lecture/écriture booléen.

**Renvoie :**
boolean
### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public final void setPlotVisibleCellsOnly(boolean value)
```

Détermine si seules les cellules visibles sont tracées. False pour tracer à la fois les cellules visibles et cachées. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public final int getDisplayBlanksAs()
```

Renvoie ou définit la façon de tracer les cellules vides sur un graphique. Lecture/écriture [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Renvoie :**
int
### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public final void setDisplayBlanksAs(int value)
```

Renvoie ou définit la façon de tracer les cellules vides sur un graphique. Lecture/écriture [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public final IChartData getChartData()
```

Renvoie des informations sur les données liées ou incorporées associées à un graphique. Lecture seule [IChartData](../../com.aspose.slides/ichartdata).

**Renvoie :**
[IChartData](../../com.aspose.slides/ichartdata)
### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

Détermine si un graphique possède un titre visible. Lecture/écriture booléen.

**Renvoie :**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

Détermine si un graphique possède un titre visible. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public final IChartTitle getChartTitle()
```

Renvoie ou définit le titre d'un graphique. Lecture seule [IChartTitle](../../com.aspose.slides/icharttitle).

**Renvoie :**
[IChartTitle](../../com.aspose.slides/icharttitle)
### hasDataTable() {#hasDataTable--}
```
public final boolean hasDataTable()
```

Détermine si un graphique possède un tableau de données. Lecture/écriture booléen.

**Renvoie :**
boolean
### setDataTable(boolean value) {#setDataTable-boolean-}
```
public final void setDataTable(boolean value)
```

Détermine si un graphique possède un tableau de données. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public final boolean hasLegend()
```

Détermine si un graphique possède une légende. Lecture/écriture booléen.

**Renvoie :**
boolean
### setLegend(boolean value) {#setLegend-boolean-}
```
public final void setLegend(boolean value)
```

Détermine si un graphique possède une légende. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public final ILegend getLegend()
```

Renvoie ou définit une légende pour un graphique. Lecture seule [ILegend](../../com.aspose.slides/ilegend).

**Renvoie :**
[ILegend](../../com.aspose.slides/ilegend)
### getChartDataTable() {#getChartDataTable--}
```
public final IDataTable getChartDataTable()
```

Renvoie un tableau de données d'un graphique. Lecture seule [IDataTable](../../com.aspose.slides/idatatable).

**Renvoie :**
[IDataTable](../../com.aspose.slides/idatatable)
### getStyle() {#getStyle--}
```
public final int getStyle()
```

Renvoie ou définit le style du graphique. Lecture/écriture [StyleType](../../com.aspose.slides/styletype).

**Renvoie :**
int
### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```

Renvoie ou définit le style du graphique. Lecture/écriture [StyleType](../../com.aspose.slides/styletype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```

Renvoie ou définit le type du graphique. Lecture/écriture [ChartType](../../com.aspose.slides/charttype).

**Renvoie :**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Renvoie ou définit le type du graphique. Lecture/écriture [ChartType](../../com.aspose.slides/charttype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public final IChartPlotArea getPlotArea()
```

Représente la zone de tracé d'un graphique. Lecture seule [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**Renvoie :**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)
### getRotation3D() {#getRotation3D--}
```
public final IRotation3D getRotation3D()
```

Renvoie une rotation 3D d'un graphique. Lecture seule [IRotation3D](../../com.aspose.slides/irotation3d).

**Renvoie :**
[IRotation3D](../../com.aspose.slides/irotation3d)
### getBackWall() {#getBackWall--}
```
public final IChartWall getBackWall()
```

Renvoie un objet qui permet de changer le format du mur arrière d'un graphique 3D. Lecture seule [IChartWall](../../com.aspose.slides/ichartwall).

**Renvoie :**
[IChartWall](../../com.aspose.slides/ichartwall)
### getSideWall() {#getSideWall--}
```
public final IChartWall getSideWall()
```

Renvoie un objet qui permet de changer le format du mur latéral d'un graphique 3D. Lecture seule [IChartWall](../../com.aspose.slides/ichartwall).

**Renvoie :**
[IChartWall](../../com.aspose.slides/ichartwall)
### getFloor() {#getFloor--}
```
public final IChartWall getFloor()
```

Renvoie un objet qui permet de changer le format du sol d'un graphique 3D. Lecture seule [IChartWall](../../com.aspose.slides/ichartwall).

**Renvoie :**
[IChartWall](../../com.aspose.slides/ichartwall)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Renvoie le format du texte du graphique. La propriété n'est pas applicable aux types suivants : [ChartType.Treemap](../../com.aspose.slides/charttype\#Treemap), [ChartType.Sunburst](../../com.aspose.slides/charttype\#Sunburst), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel),[ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker). Lecture seule [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Renvoie :**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Renvoie un thème effectif pour ce graphique.

**Renvoie :**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Renvoie le gestionnaire de thèmes. Lecture seule [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Renvoie :**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getUserShapes() {#getUserShapes--}
```
public final IGroupShape getUserShapes()
```

Spécifie les formes dessinées au-dessus du graphique. Lecture seule [IGroupShape](../../com.aspose.slides/igroupshape).

**Renvoie :**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getAxes() {#getAxes--}
```
public final IAxesManager getAxes()
```

Fournit l'accès aux axes du graphique. Lecture seule [IAxesManager](../../com.aspose.slides/iaxesmanager).

**Renvoie :**
[IAxesManager](../../com.aspose.slides/iaxesmanager)
### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public final boolean getShowDataLabelsOverMaximum()
```

Spécifie que les étiquettes de données au-dessus du maximum du graphique doivent être affichées. Lecture/écriture booléen.

**Renvoie :**
boolean
### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public final void setShowDataLabelsOverMaximum(boolean value)
```

Spécifie que les étiquettes de données au-dessus du maximum du graphique doivent être affichées. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public final boolean hasRoundedCorners()
```

Spécifie que la zone du graphique doit avoir des coins arrondis. Lecture/écriture booléen.

**Renvoie :**
boolean
### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public final void setRoundedCorners(boolean value)
```

Spécifie que la zone du graphique doit avoir des coins arrondis. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Renvoie le graphique. Lecture seule [IChart](../../com.aspose.slides/ichart).

**Renvoie :**
[IChart](../../com.aspose.slides/ichart)