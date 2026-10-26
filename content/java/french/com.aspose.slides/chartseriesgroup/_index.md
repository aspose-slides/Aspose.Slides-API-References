---
title: ChartSeriesGroup
second_title: Référence API Aspose.Slides pour Java
description: Représente un groupe de séries.
type: docs
url: /fr/com.aspose.slides/chartseriesgroup/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup), com.aspose.slides.IDOMObject
```
public class ChartSeriesGroup implements IChartSeriesGroup, IDOMObject
```

Représente un groupe de séries.

--------------------

1) Voir le résumé et les remarques pour la classe ChartSeriesGroupCollection et l'énumération CombinableSeriesTypesGroup. 2) Un groupe de séries contient certaines propriétés de séries qui sont communes à chaque série du groupe (« propriétés du groupe de séries »). Les « propriétés du groupe de séries » dans la classe ChartSeriesGroup sont en lecture/écriture. Chacune des « propriétés du groupe de séries » peut avoir une projection en lecture seule dans la classe ChartSeries.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getType()](#getType--) | Renvoie un type de ce groupe de séries. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Indique si les séries de ce groupe sont tracées sur un axe secondaire. |
| [getSeries()](#getSeries--) | Renvoie une collection de séries. |
| [get_Item(int index)](#get-Item-int-) | Obtient l'élément à l'index spécifié. |
| [getUpDownBars()](#getUpDownBars--) | Fournit l'accès aux barres haut/bas d'un graphique en lignes ou en bourse. |
| [getGapWidth()](#getGapWidth--) | Spécifie l'espace entre les groupes de barres ou de colonnes, en pourcentage de la largeur de la barre ou de la colonne. |
| [setGapWidth(int value)](#setGapWidth-int-) | Spécifie l'espace entre les groupes de barres ou de colonnes, en pourcentage de la largeur de la barre ou de la colonne. |
| [getGapDepth()](#getGapDepth--) | Renvoie ou définit la distance, en pourcentage de la largeur du marqueur, entre les séries de données dans un graphique 3D. |
| [setGapDepth(int value)](#setGapDepth-int-) | Renvoie ou définit la distance, en pourcentage de la largeur du marqueur, entre les séries de données dans un graphique 3D. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Obtient ou définit l'angle de la première tranche de diagramme circulaire ou en anneau, en degrés (dans le sens des aiguilles d'une montre depuis le haut, de 0 à 360 degrés). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Obtient ou définit l'angle de la première tranche de diagramme circulaire ou en anneau, en degrés (dans le sens des aiguilles d'une montre depuis le haut, de 0 à 360 degrés). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Spécifie la taille du trou dans un diagramme en anneau (peut être entre 0 et 90 % de la taille de la zone de tracé). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Spécifie la taille du trou dans un diagramme en anneau (peut être entre 0 et 90 % de la taille de la zone de tracé). |
| [getOverlap()](#getOverlap--) | Spécifie le degré de chevauchement des barres et des colonnes sur les graphiques 2D, en pourcentage (de -100 % à 100 %). |
| [setOverlap(byte value)](#setOverlap-byte-) | Spécifie le degré de chevauchement des barres et des colonnes sur les graphiques 2D, en pourcentage (de -100 % à 100 %). |
| [getSecondPieSize()](#getSecondPieSize--) | Spécifie la taille de la deuxième part ou barre d'un diagramme en secteurs imbriqués ou d'un diagramme en barres imbriquées, en pourcentage de la taille de la première part (peut être entre 5 % et 200 %). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Spécifie la taille de la deuxième part ou barre d'un diagramme en secteurs imbriqués ou d'un diagramme en barres imbriquées, en pourcentage de la taille de la première part (peut être entre 5 % et 200 %). |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Spécifie comment les valeurs de taille des bulles sont représentées sur le graphique à bulles. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Spécifie comment les valeurs de taille des bulles sont représentées sur le graphique à bulles. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Spécifie une valeur qui doit être utilisée pour déterminer quels points de données se trouvent dans la deuxième part ou barre d'un diagramme en secteurs imbriqués ou d'un diagramme en barres imbriquées. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Spécifie une valeur qui doit être utilisée pour déterminer quels points de données se trouvent dans la deuxième part ou barre d'un diagramme en secteurs imbriqués ou d'un diagramme en barres imbriquées. |
| [getPieSplitBy()](#getPieSplitBy--) | Spécifie comment déterminer quels points de données se trouvent dans la deuxième part ou barre d'un diagramme en secteurs imbriqués ou d'un diagramme en barres imbriquées. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Spécifie comment déterminer quels points de données se trouvent dans la deuxième part ou barre d'un diagramme en secteurs imbriqués ou d'un diagramme en barres imbriquées. |
| [isColorVaried()](#isColorVaried--) | Spécifie que chaque marqueur de données de la série a une couleur différente. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Spécifie que chaque marqueur de données de la série a une couleur différente. |
| [hasSeriesLines()](#hasSeriesLines--) | Vrai si le graphique possède des lignes de série. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Vrai si le graphique possède des lignes de série. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Spécifie le format HiLowLines. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Spécifie le facteur d'échelle pour le graphique à bulles (peut être entre 0 et 300 % de la taille par défaut). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Spécifie le facteur d'échelle pour le graphique à bulles (peut être entre 0 et 300 % de la taille par défaut). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Les informations de division personnalisée pour un diagramme en secteurs imbriqués ou en barres imbriquées avec une division personnalisée. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Renvoie le graphique parent. |
| [getSlide()](#getSlide--) | Renvoie la diapositive parent d'un FillFormat. |
| [getPresentation()](#getPresentation--) | Renvoie la présentation parent d'un FillFormat. |

### getType() {#getType--}
```
public final int getType()
```

Renvoie un type de ce groupe de séries. Lecture seule [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Renvoie :**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Indique si les séries de ce groupe sont tracées sur un axe secondaire. Lecture seule booléen.

**Renvoie :**
boolean

### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

Renvoie une collection de séries. Lecture seule [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Renvoie :**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

Obtient l'élément à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Renvoie :**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public final IUpDownBarsManager getUpDownBars()
```

Fournit l'accès aux barres haut/bas d'un graphique en lignes ou en bourse. Lecture seule [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Renvoie :**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Spécifie l'espace entre les groupes de barres ou de colonnes, en pourcentage de la largeur de la barre ou de la colonne. Lecture/écriture int.

**Renvoie :**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

Spécifie l'espace entre les groupes de barres ou de colonnes, en pourcentage de la largeur de la barre ou de la colonne. Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Renvoie ou définit la distance, en pourcentage de la largeur du marqueur, entre les séries de données dans un graphique 3D. Lecture/écriture int.

**Renvoie :**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

Renvoie ou définit la distance, en pourcentage de la largeur du marqueur, entre les séries de données dans un graphique 3D. Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Obtient ou définit l'angle de la première tranche de diagramme circulaire ou en anneau, en degrés (dans le sens des aiguilles d'une montre depuis le haut, de 0 à 360 degrés). Lecture/écriture int.

**Renvoie :**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

Obtient ou définit l'angle de la première tranche de diagramme circulaire ou en anneau, en degrés (dans le sens des aiguilles d'une montre depuis le haut, de 0 à 360 degrés). Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Spécifie la taille du trou dans un diagramme en anneau (peut être entre 0 et 90 % de la taille de la zone de tracé). Lecture/écriture byte.

**Renvoie :**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

Spécifie la taille du trou dans un diagramme en anneau (peut être entre 0 et 90 % de la taille de la zone de tracé). Lecture/écriture byte.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Spécifie le degré de chevauchement des barres et des colonnes sur les graphiques 2D, en pourcentage (de -100 % à 100 %). - -100 % : Espacement maximal (les barres sont complètement séparées). - 0 % : Les barres sont côte à côte sans chevauchement ni espacement. - 100 % : Chevauchement maximal (les barres se chevauchent complètement). Cette propriété est en lecture/écriture byte.

--------------------

> ```
> L'exemple suivant montre comment définir le chevauchement d'un groupe de séries de graphique 
>   et rendre le graphique résultant sur un formulaire :
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Définit le chevauchement à 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Renvoie :**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public final void setOverlap(byte value)
```

Spécifie le degré de chevauchement des barres et des colonnes sur les graphiques 2D, en pourcentage (de -100 % à 100 %). - -100 % : Espacement maximal (les barres sont complètement séparées). - 0 % : Les barres sont côte à côte sans chevauchement ni espacement. - 100 % : Chevauchement maximal (les barres se chevauchent complètement). Cette propriété est en lecture/écriture byte.

--------------------

> ```
> L'exemple suivant montre comment définir le chevauchement d'un groupe de séries de graphique 
>   et afficher le graphique résultant sur un formulaire :
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Définit le chevauchement à 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

Spécifie la taille de la deuxième part ou barre d'un diagramme en secteurs imbriqués ou d'un diagramme en barres imbriquées, en pourcentage de la taille de la première part (peut être entre 5 % et 200 %). Lecture/écriture int.

**Renvoie :**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

Spécifie la taille de la deuxième part ou barre d'un diagramme en secteurs imbriqués ou d'un diagramme en barres imbriquées, en pourcentage de la taille de la première part (peut être entre 5 % et 200 %). Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Spécifie comment les valeurs de taille des bulles sont représentées sur le graphique à bulles. Lecture/écriture [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Renvoie :**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

Spécifie comment les valeurs de taille des bulles sont représentées sur le graphique à bulles. Lecture/écriture [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Spécifie une valeur qui doit être utilisée pour déterminer quels points de données se trouvent dans la deuxième part ou barre d'un diagramme en secteurs imbriqués ou d'un diagramme en barres imbriquées. Est utilisé conjointement avec la propriété PieSplitBy. Lecture/écriture double.

**Renvoie :**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

Spécifie une valeur qui doit être utilisée pour déterminer quels points de données se trouvent dans la deuxième part ou barre d'un diagramme en secteurs imbriqués ou d'un diagramme en barres imbriquées. Est utilisé conjointement avec la propriété PieSplitBy. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Spécifie comment déterminer quels points de données se trouvent dans la deuxième part ou barre d'un diagramme en secteurs imbriqués ou d'un diagramme en barres imbriquées. Lecture/écriture [PieSplitType](../../com.aspose.slides/piesplittype).

**Renvoie :**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

Spécifie comment déterminer quels points de données se trouvent dans la deuxième part ou barre d'un diagramme en secteurs imbriqués ou d'un diagramme en barres imbriquées. Lecture/écriture [PieSplitType](../../com.aspose.slides/piesplittype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Spécifie que chaque marqueur de données de la série a une couleur différente. Lecture/écriture booléen.

**Renvoie :**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

Spécifie que chaque marqueur de données de la série a une couleur différente. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Vrai si le graphique possède des lignes de série. Appliqué aux graphiques à barres empilées et aux graphiques en secteurs imbriqués. Lecture/écriture booléen.

**Renvoie :**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

Vrai si le graphique possède des lignes de série. Appliqué aux graphiques à barres empilées et aux graphiques en secteurs imbriqués. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

Spécifie le format HiLowLines. HiLowLines s'applique avec les types de graphiques HiLowClose, OpenHiLowClose, VolumeHiLowClose et VolumeOpenHiLowClose.

**Renvoie :**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Spécifie le facteur d'échelle pour le graphique à bulles (peut être entre 0 et 300 % de la taille par défaut). Lecture/écriture int.

**Renvoie :**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

Spécifie le facteur d'échelle pour le graphique à bulles (peut être entre 0 et 300 % de la taille par défaut). Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Les informations de division personnalisée pour un diagramme en secteurs imbriqués ou en barres imbriquées avec une division personnalisée. Contient les points de données qui doivent être dessinés dans la deuxième part ou barre. Lecture seule [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

**Renvoie :**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Renvoie l'objet Parent_Immediate. Lecture seule IDOMObject.

**Renvoie :**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

Renvoie le graphique parent. Lecture seule [IChart](../../com.aspose.slides/ichart).

**Renvoie :**
[IChart](../../com.aspose.slides/ichart)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Renvoie la diapositive parent d'un FillFormat. Lecture seule [BaseSlide](../../com.aspose.slides/baseslide).

**Renvoie :**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Renvoie la présentation parent d'un FillFormat. Lecture seule [IPresentation](../../com.aspose.slides/ipresentation).

**Renvoie :**
[IPresentation](../../com.aspose.slides/ipresentation)