---
title: IChart
second_title: Référence de l'API Java pour Aspose.Slides for Android
description: Représente un graphique sur une diapositive.
type: docs
url: /fr/com.aspose.slides/ichart/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface IChart extends IGraphicalObject, IFormattedTextContainer, IOverrideThemeable
```

Représente un graphique sur une diapositive.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | Détermine si seules les cellules visibles sont tracées. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | Détermine si seules les cellules visibles sont tracées. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | Renvoie ou définit la façon de tracer les cellules vides sur un graphique. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | Renvoie ou définit la façon de tracer les cellules vides sur un graphique. |
| [getChartData()](#getChartData--) | Renvoie les informations sur les données liées ou intégrées associées à un graphique. |
| [hasTitle()](#hasTitle--) | Détermine si un graphique possède un titre visible. |
| [setTitle(boolean value)](#setTitle-boolean-) | Détermine si un graphique possède un titre visible. |
| [getChartTitle()](#getChartTitle--) | Renvoie ou définit le titre du graphique Lecture seule [IChartTitle](../../com.aspose.slides/icharttitle). |
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
| [getBackWall()](#getBackWall--) | Renvoie un objet qui permet de modifier le format du mur arrière d'un graphique 3D. |
| [getSideWall()](#getSideWall--) | Renvoie un objet qui permet de modifier le format du mur latéral d'un graphique 3D. |
| [getFloor()](#getFloor--) | Renvoie un objet qui permet de modifier le format du plancher d'un graphique 3D. |
| [getUserShapes()](#getUserShapes--) | Spécifie les formes dessinées au-dessus du graphique. |
| [getAxes()](#getAxes--) | Fournit l'accès aux axes du graphique. |
| [validateChartLayout()](#validateChartLayout--) | Calcule les valeurs réelles des éléments du graphique. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | Spécifie que les étiquettes de données au-dessus du maximum du graphique doivent être affichées. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | Spécifie que les étiquettes de données au-dessus du maximum du graphique doivent être affichées. |
| [hasRoundedCorners()](#hasRoundedCorners--) | Spécifie que la zone du graphique doit avoir des coins arrondis. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | Spécifie que la zone du graphique doit avoir des coins arrondis. |

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public abstract boolean getPlotVisibleCellsOnly()
```

Détermine si seules les cellules visibles sont tracées. False pour tracer à la fois les cellules visibles et cachées. Lecture/écriture booléen.

**Renvoie:**  
boolean

### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public abstract void setPlotVisibleCellsOnly(boolean value)
```

Détermine si seules les cellules visibles sont tracées. False pour tracer à la fois les cellules visibles et cachées. Lecture/écriture booléen.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public abstract int getDisplayBlanksAs()
```

Renvoie ou définit la façon de tracer les cellules vides sur un graphique. Lecture/écriture [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Renvoie:**  
int

### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public abstract void setDisplayBlanksAs(int value)
```

Renvoie ou définit la façon de tracer les cellules vides sur un graphique. Lecture/écriture [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public abstract IChartData getChartData()
```

Renvoie les informations sur les données liées ou intégrées associées à un graphique. Lecture seule [IChartData](../../com.aspose.slides/ichartdata).

**Renvoie:**  
[IChartData](../../com.aspose.slides/ichartdata)

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

Détermine si un graphique possède un titre visible. Lecture/écriture booléen.

**Renvoie:**  
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

Détermine si un graphique possède un titre visible. Lecture/écriture booléen.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public abstract IChartTitle getChartTitle()
```

Renvoie ou définit le titre du graphique Lecture seule [IChartTitle](../../com.aspose.slides/icharttitle).

**Renvoie:**  
[IChartTitle](../../com.aspose.slides/icharttitle)

### hasDataTable() {#hasDataTable--}
```
public abstract boolean hasDataTable()
```

Détermine si un graphique possède un tableau de données. Lecture/écriture booléen.

**Renvoie:**  
boolean

### setDataTable(boolean value) {#setDataTable-boolean-}
```
public abstract void setDataTable(boolean value)
```

Détermine si un graphique possède un tableau de données. Lecture/écriture booléen.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public abstract boolean hasLegend()
```

Détermine si un graphique possède une légende. Lecture/écriture booléen.

**Renvoie:**  
boolean

### setLegend(boolean value) {#setLegend-boolean-}
```
public abstract void setLegend(boolean value)
```

Détermine si un graphique possède une légende. Lecture/écriture booléen.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public abstract ILegend getLegend()
```

Renvoie ou définit une légende pour un graphique. Lecture seule [ILegend](../../com.aspose.slides/ilegend).

**Renvoie:**  
[ILegend](../../com.aspose.slides/ilegend)

### getChartDataTable() {#getChartDataTable--}
```
public abstract IDataTable getChartDataTable()
```

Renvoie un tableau de données d'un graphique. Lecture seule [IDataTable](../../com.aspose.slides/idatatable).

**Renvoie:**  
[IDataTable](../../com.aspose.slides/idatatable)

### getStyle() {#getStyle--}
```
public abstract int getStyle()
```

Renvoie ou définit le style du graphique. Lecture/écriture [StyleType](../../com.aspose.slides/styletype).

**Renvoie:**  
int

### setStyle(int value) {#setStyle-int-}
```
public abstract void setStyle(int value)
```

Renvoie ou définit le style du graphique. Lecture/écriture [StyleType](../../com.aspose.slides/styletype).

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public abstract int getType()
```

Renvoie ou définit le type du graphique. Lecture/écriture [ChartType](../../com.aspose.slides/charttype).

**Renvoie:**  
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Renvoie ou définit le type du graphique. Lecture/écriture [ChartType](../../com.aspose.slides/charttype).

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public abstract IChartPlotArea getPlotArea()
```

Représente la zone de tracé d'un graphique. Lecture seule [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**Renvoie:**  
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)

### getRotation3D() {#getRotation3D--}
```
public abstract IRotation3D getRotation3D()
```

Renvoie une rotation 3D d'un graphique. Lecture seule [IRotation3D](../../com.aspose.slides/irotation3d).

**Renvoie:**  
[IRotation3D](../../com.aspose.slides/irotation3d)

### getBackWall() {#getBackWall--}
```
public abstract IChartWall getBackWall()
```

Renvoie un objet qui permet de modifier le format du mur arrière d'un graphique 3D. Lecture seule [IChartWall](../../com.aspose.slides/ichartwall).

**Renvoie:**  
[IChartWall](../../com.aspose.slides/ichartwall)

### getSideWall() {#getSideWall--}
```
public abstract IChartWall getSideWall()
```

Renvoie un objet qui permet de modifier le format du mur latéral d'un graphique 3D. Lecture seule [IChartWall](../../com.aspose.slides/ichartwall).

**Renvoie:**  
[IChartWall](../../com.aspose.slides/ichartwall)

### getFloor() {#getFloor--}
```
public abstract IChartWall getFloor()
```

Renvoie un objet qui permet de modifier le format du plancher d'un graphique 3D. Lecture seule [IChartWall](../../com.aspose.slides/ichartwall).

**Renvoie:**  
[IChartWall](../../com.aspose.slides/ichartwall)

### getUserShapes() {#getUserShapes--}
```
public abstract IGroupShape getUserShapes()
```

Spécifie les formes dessinées au-dessus du graphique. Lecture seule [IGroupShape](../../com.aspose.slides/igroupshape).

**Renvoie:**  
[IGroupShape](../../com.aspose.slides/igroupshape)

### getAxes() {#getAxes--}
```
public abstract IAxesManager getAxes()
```

Fournit l'accès aux axes du graphique. Lecture seule [IAxesManager](../../com.aspose.slides/iaxesmanager).

**Renvoie:**  
[IAxesManager](../../com.aspose.slides/iaxesmanager)

### validateChartLayout() {#validateChartLayout--}
```
public abstract void validateChartLayout()
```

Calcule les valeurs réelles des éléments du graphique. Les valeurs réelles incluent la position des éléments qui implémentent l’interface IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) et les valeurs réelles des axes (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)

### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public abstract boolean getShowDataLabelsOverMaximum()
```

Spécifie que les étiquettes de données au-dessus du maximum du graphique doivent être affichées. Lecture/écriture booléen.

**Renvoie:**  
boolean

### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public abstract void setShowDataLabelsOverMaximum(boolean value)
```

Spécifie que les étiquettes de données au-dessus du maximum du graphique doivent être affichées. Lecture/écriture booléen.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public abstract boolean hasRoundedCorners()
```

Spécifie que la zone du graphique doit avoir des coins arrondis. Lecture/écriture booléen.

**Renvoie:**  
boolean

### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public abstract void setRoundedCorners(boolean value)
```

Spécifie que la zone du graphique doit avoir des coins arrondis. Lecture/écriture booléen.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |