---
title: ChartSeriesCollection
second_title: Aspose.Slides voor Android via Java API Referentie
description: Vertegenwoordigt een verzameling van
type: docs
url: /nl/com.aspose.slides/chartseriescollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
```
public class ChartSeriesCollection extends DomObject<ChartData> implements IChartSeriesCollection
```

Vertegenwoordigt een verzameling van [ChartSeries](../../com.aspose.slides/chartseries)
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op op de opgegeven index. |
| [size()](#size--) | Retourneert een aantal objecten in de collectie. |
| [add(int type)](#add-int-) | Maakt een nieuwe diagramreeks en voegt deze toe aan de collectie. |
| [insert(int index, int type)](#insert-int-int-) | Maakt een nieuwe diagramreeks en voegt deze in de collectie in. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | Maakt een nieuwe diagramreeks van [ChartDataCell](../../com.aspose.slides/chartdatacell) en voegt deze toe aan de collectie. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | Maakt een nieuwe diagramreeks van [ChartCellCollection](../../com.aspose.slides/chartcellcollection) en voegt deze toe aan de collectie. |
| [add(String name, int type)](#add-java.lang.String-int-) | Maakt een nieuwe diagramreeks van waarde en voegt deze toe aan de collectie. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | Zoekt naar de opgegeven [ChartSeries](../../com.aspose.slides/chartseries) en retourneert de nulgebaseerde index van de eerste voorkomen binnen de gehele collectie |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | Verwijdert de opgegeven waarde. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert een ActiveX-besturingselement dat op de opgegeven positie in de collectie is opgeslagen. |
| [clear()](#clear--) | Verwijdert alle besturingselementen uit de collectie. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie iterereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een Java-iterator voor de volledige collectie. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopieert de volledige collectie naar de opgegeven array. |
| [isSynchronized()](#isSynchronized--) | Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-veilig). |
| [getSyncRoot()](#getSyncRoot--) | Retourneert een synchronisatie-wortel. |
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

Maakt een nieuwe diagramreeks en voegt deze toe aan de collectie.

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

Maakt een nieuwe diagramreeks en voegt deze in de collectie in.

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

Maakt een nieuwe diagramreeks van [ChartDataCell](../../com.aspose.slides/chartdatacell) en voegt deze toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cel die de serienaam bevat. |
| type | int | Type van reeks

--------------------

Als een diagramreeks die al uit dezelfde cel bestaat in de collectie is, voegt de methode niets toe en retourneert de index. |

**Returns:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Toegevoegde diagramreeks of reeks die al in de collectie aanwezig is.
### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public final IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

Maakt een nieuwe diagramreeks van [ChartCellCollection](../../com.aspose.slides/chartcellcollection) en voegt deze toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | Cellen die de serienaam bevatten. |
| type | int | Type van reeks

--------------------

Als een diagramreeks die al uit dezelfde cel bestaat in de collectie is, voegt de methode niets toe en retourneert de index. |

**Returns:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Toegevoegde diagramreeks of reeks die al in de collectie aanwezig is.
### add(String name, int type) {#add-java.lang.String-int-}
```
public final IChartSeries add(String name, int type)
```

Maakt een nieuwe diagramreeks van waarde en voegt deze toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Serienaam. |
| type | int | Type van reeks |

**Returns:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Toegevoegde diagramreeks.
### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public final int indexOf(IChartSeries value)
```

Zoekt naar de opgegeven [ChartSeries](../../com.aspose.slides/chartseries) en retourneert de nulgebaseerde index van de eerste voorkomen binnen de gehele collectie

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Diagramreekswaarde. |

**Returns:**
int - De nulgebaseerde index van het eerste voorkomen van value binnen de gehele CollectionBase, indien gevonden; anders -1.
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

Verwijdert een ActiveX-besturingselement dat op de opgegeven positie in de collectie is opgeslagen.

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

Retourneert een enumerator die door de collectie iterereert.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iteratorJava()
```

Retourneert een Java-iterator voor de volledige collectie.

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
| array | com.aspose.ms.System.Array | Doelarray |
| index | int | Index in de doelarray. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-veilig). Alleen-lezen boolean.

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Retourneert een synchronisatie-wortel. Alleen-lezen Object.

**Returns:**
java.lang.Object