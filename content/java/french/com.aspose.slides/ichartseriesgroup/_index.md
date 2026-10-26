---
title: IChartSeriesGroup
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente un groupe de séries.
type: docs
url: /fr/com.aspose.slides/ichartseriesgroup/
---
**Toutes les interfaces implémentées :**  
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeriesGroup extends IChartComponent
```

Représente un groupe de séries.

--------------------

1) Voir le résumé et les remarques pour la classe ChartSeriesGroupCollection et l'énumération CombinableSeriesTypesGroup. 2) Le groupe de séries contient certaines propriétés communes à chaque série du groupe (« propriétés du groupe de séries »). Les « propriétés du groupe de séries » dans la classe ChartSeriesGroup sont lecture/écriture. Chaque propriété du groupe de séries peut avoir une projection en lecture seule dans la classe ChartSeries.  

## Méthodes

| Méthode | Description |
| --- | --- |
| [getType()](#getType--) | Retourne un type de ce groupe de séries. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Indique si les séries de ce groupe sont tracées sur un axe secondaire. |
| [getSeries()](#getSeries--) | Retourne une collection en lecture seule de séries de graphique. |
| [get_Item(int index)](#get-Item-int-) | Obtient l’élément à l’indice spécifié. |
| [getUpDownBars()](#getUpDownBars--) | Fournit l’accès aux barres up/down d’un graphique en ligne ou en cours. |
| [getGapWidth()](#getGapWidth--) | Spécifie l’espace entre les groupes de barres ou de colonnes, en pourcentage de la largeur de la barre ou de la colonne. |
| [setGapWidth(int value)](#setGapWidth-int-) | Spécifie l’espace entre les groupes de barres ou de colonnes, en pourcentage de la largeur de la barre ou de la colonne. |
| [getGapDepth()](#getGapDepth--) | Retourne ou définit la distance, en pourcentage de la largeur du marqueur, entre les séries de données dans un graphique 3D. |
| [setGapDepth(int value)](#setGapDepth-int-) | Retourne ou définit la distance, en pourcentage de la largeur du marqueur, entre les séries de données dans un graphique 3D. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Obtient ou définit l’angle de la première tranche de diagramme circulaire ou en anneau, en degrés (dans le sens horaire depuis le haut, de 0 à 360 degrés). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Obtient ou définit l’angle de la première tranche de diagramme circulaire ou en anneau, en degrés (dans le sens horaire depuis le haut, de 0 à 360 degrés). |
| [isColorVaried()](#isColorVaried--) | Indique que chaque indicateur de données de la série a une couleur différente. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Indique que chaque indicateur de données de la série a une couleur différente. |
| [hasSeriesLines()](#hasSeriesLines--) | Vrai si le graphique possède des lignes de série. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Vrai si le graphique possède des lignes de série. |
| [getOverlap()](#getOverlap--) | Spécifie le chevauchement des barres et colonnes sur les graphiques 2 D, en pourcentage (de -100 % à 100 %). |
| [setOverlap(byte value)](#setOverlap-byte-) | Spécifie le chevauchement des barres et colonnes sur les graphiques 2 D, en pourcentage (de -100 % à 100 %). |
| [getSecondPieSize()](#getSecondPieSize--) | Spécifie la taille du deuxième secteur ou barre d’un graphique « pie-of-pie » ou « bar-of-pie », en pourcentage de la taille du premier secteur (entre 5 % et 200 %). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Spécifie la taille du deuxième secteur ou barre d’un graphique « pie-of-pie » ou « bar-of-pie », en pourcentage de la taille du premier secteur (entre 5 % et 200 %). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Spécifie une valeur utilisée pour déterminer quels points de données appartiennent au deuxième secteur ou barre d’un graphique « pie-of-pie » ou « bar-of-pie ». |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Spécifie une valeur utilisée pour déterminer quels points de données appartiennent au deuxième secteur ou barre d’un graphique « pie-of-pie » ou « bar-of-pie ». |
| [getPieSplitBy()](#getPieSplitBy--) | Spécifie comment déterminer quels points de données appartiennent au deuxième secteur ou barre d’un graphique « pie-of-pie » ou « bar-of-pie ». |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Spécifie comment déterminer quels points de données appartiennent au deuxième secteur ou barre d’un graphique « pie-of-pie » ou « bar-of-pie ». |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Informations de séparation personnalisée pour un graphique « pie-of-pie » ou « bar-of-pie » avec séparation personnalisée. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Spécifie la taille du trou dans un graphique en anneau (entre 10 % et 90 % de la zone de traçage). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Spécifie la taille du trou dans un graphique en anneau (entre 10 % et 90 % de la zone de traçage). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Spécifie le facteur d’échelle pour le graphique à bulles (entre 0 % et 300 % de la taille par défaut). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Spécifie le facteur d’échelle pour le graphique à bulles (entre 0 % et 300 % de la taille par défaut). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Spécifie le format HiLowLines. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Spécifie comment les valeurs de taille des bulles sont représentées sur le graphique à bulles. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Spécifie comment les valeurs de taille des bulles sont représentées sur le graphique à bulles. |

### getType() {#getType--}
```
public abstract int getType()
```

Retourne un type de ce groupe de séries. Lecture seule [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Retourne :**  
int  

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Indique si les séries de ce groupe sont tracées sur un axe secondaire. Lecture seule booléen.

**Retourne :**  
boolean  

### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

Retourne une collection en lecture seule de séries de graphique. Lecture seule [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Retourne :**  
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)  

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

Obtient l’élément à l’indice spécifié.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Retourne :**  
[IChartSeries](../../com.aspose.slides/ichartseries)  

### getUpDownBars() {#getUpDownBars--}
```
public abstract IUpDownBarsManager getUpDownBars()
```

Fournit l’accès aux barres up/down d’un graphique en ligne ou en cours. Lecture seule [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Retourne :**  
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)  

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Spécifie l’espace entre les groupes de barres ou de colonnes, en pourcentage de la largeur de la barre ou de la colonne. Lecture/écriture int.

**Retourne :**  
int  

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

Spécifie l’espace entre les groupes de barres ou de colonnes, en pourcentage de la largeur de la barre ou de la colonne. Lecture/écriture int.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Retourne ou définit la distance, en pourcentage de la largeur du marqueur, entre les séries de données dans un graphique 3D. Lecture/écriture int.

**Retourne :**  
int  

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

Retourne ou définit la distance, en pourcentage de la largeur du marqueur, entre les séries de données dans un graphique 3D. Lecture/écriture int.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Obtient ou définit l’angle de la première tranche de diagramme circulaire ou en anneau, en degrés (dans le sens horaire depuis le haut, de 0 à 360 degrés). Lecture/écriture int.

**Retourne :**  
int  

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

Obtient ou définit l’angle de la première tranche de diagramme circulaire ou en anneau, en degrés (dans le sens horaire depuis le haut, de 0 à 360 degrés). Lecture/écriture int.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Indique que chaque indicateur de données de la série a une couleur différente. Lecture/écriture booléen.

**Retourne :**  
boolean  

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

Indique que chaque indicateur de données de la série a une couleur différente. Lecture/écriture booléen.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Vrai si le graphique possède des lignes de série. Appliqué aux graphiques à barres empilées et OfPie. Lecture/écriture booléen.

**Retourne :**  
boolean  

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

Vrai si le graphique possède des lignes de série. Appliqué aux graphiques à barres empilées et OfPie. Lecture/écriture booléen.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Spécifie le chevauchement des barres et colonnes sur les graphiques 2 D, en pourcentage (de -100 % à 100 %). -100 % : espacement maximal (les barres sont totalement séparées). -0 % : les barres sont côte à côte sans chevauchement ni espacement. 100 % : chevauchement maximal (les barres se superposent entièrement). Cette propriété est lecture/écriture byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Définir le chevauchement à 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retourne :**  
byte  

### setOverlap(byte value) {#setOverlap-byte-}
```
public abstract void setOverlap(byte value)
```

Spécifie le chevauchement des barres et colonnes sur les graphiques 2 D, en pourcentage (de -100 % à 100 %). -100 % : espacement maximal (les barres sont totalement séparées). -0 % : les barres sont côte à côte sans chevauchement ni espacement. 100 % : chevauchement maximal (les barres se superposent entièrement). Cette propriété est lecture/écriture byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Définir le chevauchement à 55%
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
public abstract int getSecondPieSize()
```

Spécifie la taille du deuxième secteur ou barre d’un graphique « pie-of-pie » ou « bar-of-pie », en pourcentage de la taille du premier secteur (entre 5 % et 200 %). Lecture/écriture int.

**Retourne :**  
int  

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

Spécifie la taille du deuxième secteur ou barre d’un graphique « pie-of-pie » ou « bar-of-pie », en pourcentage de la taille du premier secteur (entre 5 % et 200 %). Lecture/écriture int.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Spécifie une valeur utilisée pour déterminer quels points de données appartiennent au deuxième secteur ou barre d’un graphique « pie-of-pie » ou « bar-of-pie ». Utilisée conjointement avec la propriété PieSplitBy. Lecture/écriture double.

**Retourne :**  
double  

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

Spécifie une valeur utilisée pour déterminer quels points de données appartiennent au deuxième secteur ou barre d’un graphique « pie-of-pie » ou « bar-of-pie ». Utilisée conjointement avec la propriété PieSplitBy. Lecture/écriture double.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Spécifie comment déterminer quels points de données appartiennent au deuxième secteur ou barre d’un graphique « pie-of-pie » ou « bar-of-pie ». Lecture/écriture [PieSplitType](../../com.aspose.slides/piesplittype).

**Retourne :**  
int  

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

Spécifie comment déterminer quels points de données appartiennent au deuxième secteur ou barre d’un graphique « pie-of-pie » ou « bar-of-pie ». Lecture/écriture [PieSplitType](../../com.aspose.slides/piesplittype).

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Les informations de séparation personnalisée pour un graphique « pie-of-pie » ou « bar-of-pie » avec séparation personnalisée. Contient les points de données à dessiner dans le deuxième secteur ou barre. Lecture seule [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

**Retourne :**  
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)  

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Spécifie la taille du trou dans un graphique en anneau (entre 10 % et 90 % de la taille de la zone de traçage). Lecture/écriture byte.

**Retourne :**  
byte  

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

Spécifie la taille du trou dans un graphique en anneau (entre 10 % et 90 % de la taille de la zone de traçage). Lecture/écriture byte.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Spécifie le facteur d’échelle pour le graphique à bulles (entre 0 % et 300 % de la taille par défaut). Lecture/écriture int.

**Retourne :**  
int  

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

Spécifie le facteur d’échelle pour le graphique à bulles (entre 0 % et 300 % de la taille par défaut). Lecture/écriture int.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

Spécifie le format HiLowLines. HiLowLines appliqué aux types de graphiques HiLowClose, OpenHiLowClose, VolumeHiLowClose et VolumeOpenHiLowClose.

**Retourne :**  
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)  

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Spécifie comment les valeurs de taille des bulles sont représentées sur le graphique à bulles. Lecture/écriture [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Retourne :**  
int  

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

Spécifie comment les valeurs de taille des bulles sont représentées sur le graphique à bulles. Lecture/écriture [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |