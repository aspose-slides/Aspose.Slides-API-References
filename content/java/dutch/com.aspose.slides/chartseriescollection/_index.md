---
title: ChartSeriesCollection
second_title: Aspose.Slides voor Java API Referentie
description: Stelt een collectie van
type: docs
url: /nl/com.aspose.slides/chartseriescollection/
---
**Erfenis:**
java.lang.Object, com.aspose.slides.DomObject

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
```
public class ChartSeriesCollection extends DomObject<ChartData> implements IChartSeriesCollection
```

Stelt een collectie van [ChartSeries](../../com.aspose.slides/chartseries) voor
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op op de opgegeven index. |
| [size()](#size--) | Retourneert een aantal objecten in de collectie. |
| [add(int type)](#add-int-) | Maakt een nieuwe diagramreeks aan en voegt deze toe aan de collectie. |
| [insert(int index, int type)](#insert-int-int-) | Maakt een nieuwe diagramreeks aan en voegt deze in de collectie in. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | Maakt een nieuwe diagramreeks aan vanuit [ChartDataCell](../../com.aspose.slides/chartdatacell) en voegt deze toe aan de collectie. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | Maakt een nieuwe diagramreeks aan vanuit [ChartCellCollection](../../com.aspose.slides/chartcellcollection) en voegt deze toe aan de collectie. |
| [add(String name, int type)](#add-java.lang.String-int-) | Maakt een nieuwe diagramreeks aan vanuit een waarde en voegt deze toe aan de collectie. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | Zoekt naar de opgegeven [ChartSeries](../../com.aspose.slides/chartseries) en retourneert de nulgebaseerde index van de eerste voorkoming binnen de volledige collectie |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | Verwijdert de opgegeven waarde. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert een ActiveX-besturingselement opgeslagen op een opgegeven positie uit de collectie. |
| [clear()](#clear--) | Verwijdert alle besturingselementen uit de collectie. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie itereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java-iterator voor de volledige collectie. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopieert de volledige collectie naar de opgegeven array. |
| [isSynchronized()](#isSynchronized--) | Retourneert een waarde die aangeeft of toegang tot de collectie gesynchroniseerd (thread-safe) is. |
| [getSyncRoot()](#getSyncRoot--) | Retourneert een synchronisatieroot. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

Haalt het element op op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Het element op de opgegeven index.
### size() {#size--}
```
public final int size()
```

Retourneert een aantal objecten in de collectie. Alleen-lezen int.

**Returns:**
int
### add(int type) {#add-int-}
```
public final IChartSeries add(int type)
```

Maakt een nieuwe diagramreeks aan en voegt deze toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | int | Type van reeks |

**Returns:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Nieuwe diagramreeks.
### insert(int index, int type) {#insert-int-int-}
```
public final IChartSeries insert(int index, int type)
```

Maakt een nieuwe diagramreeks aan en voegt deze in de collectie in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |
| type | int |  |

**Returns:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public final IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

Maakt een nieuwe diagramreeks aan vanuit [ChartDataCell](../../com.aspose.slides/chartdatacell) en voegt deze toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cel die de reeksnamen bevat. |
| type | int | Type van reeks

--------------------

Als een diagramreeks al bestaat vanuit dezelfde cel in de collectie, voegt de methode niets toe en retourneert de index. |

**Returns:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Toegevoegde diagramreeks of reeds aanwezige reeks in de collectie.
### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public final IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

Maakt een nieuwe diagramreeks aan vanuit [ChartCellCollection](../../com.aspose.slides/chartcellcollection) en voegt deze toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | Cellsen die de reeksnamen bevatten. |
| type | int | Type van reeks

--------------------

Als een diagramreeks al bestaat vanuit dezelfde cel in de collectie, voegt de methode niets toe en retourneert de index. |

**Returns:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Toegevoegde diagramreeks of reeds aanwezige reeks in de collectie.
### add(String name, int type) {#add-java.lang.String-int-}
```
public final IChartSeries add(String name, int type)
```

Maakt een nieuwe diagramreeks aan vanuit een waarde en voegt deze toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Reeksnaam. |
| type | int | Type van reeks |

**Returns:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Toegevoegde diagramreeks.
### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public final int indexOf(IChartSeries value)
```

Zoekt naar de opgegeven [ChartSeries](../../com.aspose.slides/chartseries) en retourneert de nulgebaseerde index van de eerste voorkoming binnen de volledige collectie

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Diagramreekswaarde. |

**Returns:**
int - De nulgebaseerde index van de eerste voorkoming van waarde binnen de volledige CollectionBase, indien gevonden; anders -1.
### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public final void remove(IChartSeries value)
```

Verwijdert de opgegeven waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | De waarde. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Verwijdert een ActiveX-besturingselement opgeslagen op een opgegeven positie uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van het te verwijderen besturingselement. |

### clear() {#clear--}
```
public final void clear()
```

Verwijdert alle besturingselementen uit de collectie.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iterator()
```

Retourneert een enumerator die door de collectie itereert.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iteratorJava()
```

Retourneert een java-iterator voor de volledige collectie.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - Een java.util.Iterator voor de volledige collectie.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopieert de volledige collectie naar de opgegeven array.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Doelarrray |
| index | int | Index in de doelarray. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Retourneert een waarde die aangeeft of toegang tot de collectie gesynchroniseerd (thread-safe) is. Alleen-lezen boolean.

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Retourneert een synchronisatieroot. Alleen-lezen Object.

**Returns:**
java.lang.Object