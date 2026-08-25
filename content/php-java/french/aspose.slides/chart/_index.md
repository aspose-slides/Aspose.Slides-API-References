---
title: Chart
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/chart/
---
## Chart class

Représente un graphique sur une diapositive.

### createThemeEffective {#createThemeEffective}

| Nom | Description |
| --- | --- |
| createThemeEffective () | Renvoie un thème effectif pour ce graphique. |

**Renvoie :**
ThemeEffectiveData

---

### getAxes {#getAxes}

| Nom | Description |
| --- | --- |
| getAxes () | Fournit l'accès aux axes du graphique. Lecture seule IAxesManager. |

**Renvoie :**
[AxesManager](../axesmanager)

---

### getBackWall {#getBackWall}

| Nom | Description |
| --- | --- |
| getBackWall () | Renvoie un objet qui permet de modifier le format du mur arrière d'un graphique 3D. Lecture seule IChartWall. |

**Renvoie :**
[ChartWall](../chartwall)

---

### getChart {#getChart}

| Nom | Description |
| --- | --- |
| getChart () |  |

**Renvoie :**
[Chart](../chart)

---

### getChartData {#getChartData}

| Nom | Description |
| --- | --- |
| getChartData () | Renvoie des informations sur les données liées ou intégrées associées à un graphique. Lecture seule IChartData. |

**Renvoie :**
[ChartData](../chartdata)

---

### getChartDataTable {#getChartDataTable}

| Nom | Description |
| --- | --- |
| getChartDataTable () | Renvoie une table de données d'un graphique. Lecture seule IDataTable. |

**Renvoie :**
[DataTable](../datatable)

---

### getChartTitle {#getChartTitle}

| Nom | Description |
| --- | --- |
| getChartTitle () | Renvoie ou définit le titre d'un graphique. Lecture seule IChartTitle. |

**Renvoie :**
[ChartTitle](../charttitle)

---

### getDisplayBlanksAs {#getDisplayBlanksAs}

| Nom | Description |
| --- | --- |
| getDisplayBlanksAs () | Renvoie ou définit la façon d'afficher les cellules vides sur un graphique. Lecture/écriture DisplayBlanksAsType. |

**Renvoie :**
int

---

### getFloor {#getFloor}

| Nom | Description |
| --- | --- |
| getFloor () | Renvoie un objet qui permet de modifier le format du plancher d'un graphique 3D. Lecture seule IChartWall. |

**Renvoie :**
[ChartWall](../chartwall)

---

### getLegend {#getLegend}

| Nom | Description |
| --- | --- |
| getLegend () | Renvoie ou définit une légende pour un graphique. Lecture seule ILegend. |

**Renvoie :**
[Legend](../legend)

---

### getPlotArea {#getPlotArea}

| Nom | Description |
| --- | --- |
| getPlotArea () | Représente la zone de traçage d'un graphique. Lecture seule IChartPlotArea. |

**Renvoie :**
[ChartPlotArea](../chartplotarea)

---

### getPlotVisibleCellsOnly {#getPlotVisibleCellsOnly}

| Nom | Description |
| --- | --- |
| getPlotVisibleCellsOnly () | Détermine si seules les cellules visibles sont tracées. False pour tracer les cellules visibles et cachées. Lecture/écriture boolean. |

**Renvoie :**
boolean

---

### getRotation3D {#getRotation3D}

| Nom | Description |
| --- | --- |
| getRotation3D () | Renvoie une rotation 3D d'un graphique. Lecture seule IRotation3D. |

**Renvoie :**
[Rotation3D](../rotation3d)

---

### getShowDataLabelsOverMaximum {#getShowDataLabelsOverMaximum}

| Nom | Description |
| --- | --- |
| getShowDataLabelsOverMaximum () | Spécifie que les étiquettes de données au-delà du maximum du graphique doivent être affichées. Lecture/écriture boolean. |

**Renvoie :**
boolean

---

### getSideWall {#getSideWall}

| Nom | Description |
| --- | --- |
| getSideWall () | Renvoie un objet qui permet de modifier le format du mur latéral d'un graphique 3D. Lecture seule IChartWall. |

**Renvoie :**
[ChartWall](../chartwall)

---

### getStyle {#getStyle}

| Nom | Description |
| --- | --- |
| getStyle () | Renvoie ou définit le style du graphique. Lecture/écriture StyleType. |

**Renvoie :**
int

---

### getTextFormat {#getTextFormat}

| Nom | Description |
| --- | --- |
| getTextFormat () | Renvoie le format du texte du graphique. La propriété n'est pas applicable aux types suivants : ChartType#Treemap, ChartType#Sunburst, ChartType#Waterfall, ChartType#Histogram, ChartType#Funnel, ChartType#BoxAndWhisker. Lecture seule IChartTextFormat. |

**Renvoie :**
[ChartTextFormat](../charttextformat)

---

### getThemeManager {#getThemeManager}

| Nom | Description |
| --- | --- |
| getThemeManager () | Renvoie le gestionnaire de thème. Lecture seule IOverrideThemeManager. |

**Renvoie :**
[SlideThemeManager](../slidethememanager), [LayoutSlideThemeManager](../layoutslidethememanager), [ChartThemeManager](../chartthememanager), [BaseOverrideThemeManager](../baseoverridethememanager), [NotesSlideThemeManager](../notesslidethememanager)

---

### getType {#getType}

| Nom | Description |
| --- | --- |
| getType () | Renvoie ou définit le type du graphique. Lecture/écriture ChartType. |

**Renvoie :**
int

---

### getUserShapes {#getUserShapes}

| Nom | Description |
| --- | --- |
| getUserShapes () | Spécifie les formes dessinées au-dessus du graphique. Lecture seule IGroupShape. |

**Renvoie :**
[GroupShape](../groupshape)

---

### hasDataTable {#hasDataTable}

| Nom | Description |
| --- | --- |
| hasDataTable () | Détermine si un graphique possède une table de données. Lecture/écriture boolean. |

**Renvoie :**
boolean

---

### hasLegend {#hasLegend}

| Nom | Description |
| --- | --- |
| hasLegend () | Détermine si un graphique possède une légende. Lecture/écriture boolean. |

**Renvoie :**
boolean

---

### hasRoundedCorners {#hasRoundedCorners}

| Nom | Description |
| --- | --- |
| hasRoundedCorners () | Spécifie que la zone du graphique doit avoir des coins arrondis. Lecture/écriture boolean. |

**Renvoie :**
boolean

---

### hasTitle {#hasTitle}

| Nom | Description |
| --- | --- |
| hasTitle () | Détermine si un graphique possède un titre visible. Lecture/écriture boolean. |

**Renvoie :**
boolean

---

### setDataTable {#setDataTable}

| Nom | Description |
| --- | --- |
| setDataTable (boolean) | Détermine si un graphique possède une table de données. Lecture/écriture boolean. |

**Renvoie :**
void

---

### setDisplayBlanksAs {#setDisplayBlanksAs}

| Nom | Description |
| --- | --- |
| setDisplayBlanksAs (int) | Renvoie ou définit la façon d'afficher les cellules vides sur un graphique. Lecture/écriture DisplayBlanksAsType. |

**Renvoie :**
void

---

### setLegend {#setLegend}

| Nom | Description |
| --- | --- |
| setLegend (boolean) | Détermine si un graphique possède une légende. Lecture/écriture boolean. |

**Renvoie :**
void

---

### setPlotVisibleCellsOnly {#setPlotVisibleCellsOnly}

| Nom | Description |
| --- | --- |
| setPlotVisibleCellsOnly (boolean) | Détermine si seules les cellules visibles sont tracées. False pour tracer les cellules visibles et cachées. Lecture/écriture boolean. |

**Renvoie :**
void

---

### setRoundedCorners {#setRoundedCorners}

| Nom | Description |
| --- | --- |
| setRoundedCorners (boolean) | Spécifie que la zone du graphique doit avoir des coins arrondis. Lecture/écriture boolean. |

**Renvoie :**
void

---

### setShowDataLabelsOverMaximum {#setShowDataLabelsOverMaximum}

| Nom | Description |
| --- | --- |
| setShowDataLabelsOverMaximum (boolean) | Spécifie que les étiquettes de données au-delà du maximum du graphique doivent être affichées. Lecture/écriture boolean. |

**Renvoie :**
void

---

### setStyle {#setStyle}

| Nom | Description |
| --- | --- |
| setStyle (int) | Renvoie ou définit le style du graphique. Lecture/écriture StyleType. |

**Renvoie :**
void

---

### setTitle {#setTitle}

| Nom | Description |
| --- | --- |
| setTitle (boolean) | Détermine si un graphique possède un titre visible. Lecture/écriture boolean. |

**Renvoie :**
void

---

### setType {#setType}

| Nom | Description |
| --- | --- |
| setType (int) | Renvoie ou définit le type du graphique. Lecture/écriture ChartType. |

**Renvoie :**
void

---

### validateChartLayout {#validateChartLayout}

| Nom | Description |
| --- | --- |
| validateChartLayout () | Calcule les valeurs réelles des éléments du graphique. Les valeurs réelles incluent la position des éléments qui implémentent l'interface IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) et les valeurs réelles des axes (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale). |

**Renvoie :**
void

---