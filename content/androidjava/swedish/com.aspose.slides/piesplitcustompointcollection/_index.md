---
title: PieSplitCustomPointCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av punkter för delningspunkt i ett stapel-i-paj eller paj-i-paj diagram med en anpassad delning.
type: docs
url: /sv/com.aspose.slides/piesplitcustompointcollection/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
```
public class PieSplitCustomPointCollection implements IPieSplitCustomPointCollection
```

Representerar en samling av punkter för delningspunkt i ett stapel-i-paj eller paj-i-paj diagram med en anpassad delning.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returnerar diagramdatapunkt för angivet index. |
| [add(int dataPointIndex)](#add-int-) | Lägger till datapunkt genom dess index i föräldraserie-punktsamlingen. |
| [addItem(IChartDataPoint dataPoint)](#addItem-com.aspose.slides.IChartDataPoint-) | Lägger till datapunkt i samlingen. |
| [removeItem(IChartDataPoint dataPoint)](#removeItem-com.aspose.slides.IChartDataPoint-) | Tar bort objekt från samlingen. |
| [remove(int dataPointIndex)](#remove-int-) | Tar bort objekt från samlingen via dess index i föräldraserie-punktsamlingen. |
| [clear()](#clear--) | Tar bort alla objekt från [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [containsItem(IChartDataPoint item)](#containsItem-com.aspose.slides.IChartDataPoint-) | Avgör om [IGenericCollection](../../com.aspose.slides/igenericcollection) innehåller ett specifikt värde. |
| [copyToTArray(IChartDataPoint[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IChartDataPoint---int-) | Kopierar elementen i [IGenericCollection](../../com.aspose.slides/igenericcollection) till en Array, med början vid ett specifikt Array-index. |
| [size()](#size--) | Returnerar eller anger antalet diagramdatapunkter. |
| [isReadOnly()](#isReadOnly--) | Hämtar ett värde som indikerar om [IGenericCollection](../../com.aspose.slides/igenericcollection) är skrivskyddad. |
| [isSynchronized()](#isSynchronized--) | Returnerar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). |
| [getSyncRoot()](#getSyncRoot--) | Returnerar ett synkroniseringsrot. |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [iteratorJava()](#iteratorJava--) | Returnerar en java-iterator för hela samlingen. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

Returnerar diagramdatapunkt för angivet index.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index. |

**Returnerar:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Diagramdatapunkt.

### add(int dataPointIndex) {#add-int-}
```
public final void add(int dataPointIndex)
```

Lägger till datapunkt genom dess index i föräldraserie-punktsamlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dataPointIndex | int | Index för datapunkt i föräldraserie-punktsamlingen. |

### addItem(IChartDataPoint dataPoint) {#addItem-com.aspose.slides.IChartDataPoint-}
```
public void addItem(IChartDataPoint dataPoint)
```

Lägger till datapunkt i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Datapunkt att lägga till i. |

### removeItem(IChartDataPoint dataPoint) {#removeItem-com.aspose.slides.IChartDataPoint-}
```
public boolean removeItem(IChartDataPoint dataPoint)
```

Tar bort objekt från samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Datapunkt att ta bort från. |

**Returnerar:**
boolean – true om objektet framgångsrikt har tagits bort; annars false. Denna metod returnerar också false om objektet inte hittades i System.Collections.Generic.List\{T\}.

### remove(int dataPointIndex) {#remove-int-}
```
public final void remove(int dataPointIndex)
```

Tar bort objekt från samlingen via dess index i föräldraserie-punktsamlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dataPointIndex | int | Index för datapunkt i föräldraserie-punktsamlingen. |

### clear() {#clear--}
```
public final void clear()
```

Tar bort alla objekt från [IGenericCollection](../../com.aspose.slides/igenericcollection).

### containsItem(IChartDataPoint item) {#containsItem-com.aspose.slides.IChartDataPoint-}
```
public boolean containsItem(IChartDataPoint item)
```

Avgör om [IGenericCollection](../../com.aspose.slides/igenericcollection) innehåller ett specifikt värde.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Objektet att söka i [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Returnerar:**
boolean – true om objektet hittas i [IGenericCollection](../../com.aspose.slides/igenericcollection); annars false.

### copyToTArray(IChartDataPoint[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IChartDataPoint---int-}
```
public void copyToTArray(IChartDataPoint[] array, int arrayIndex)
```

Kopierar elementen i [IGenericCollection](../../com.aspose.slides/igenericcollection) till en Array, med början vid ett specifikt Array-index.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | [IChartDataPoint\[\]](../../com.aspose.slides/ichartdatapoint) | Den endimensionella Array som är målet för elementen som kopierats från [IGenericCollection](../../com.aspose.slides/igenericcollection). Arrayen måste ha nollbaserad indexering. |
| arrayIndex | int | Det nollbaserade indexet i arrayen där kopieringen börjar. |

### size() {#size--}
```
public final int size()
```

Returnerar eller anger antalet diagramdatapunkter. Läs-endast int.

**Returnerar:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Hämtar ett värde som indikerar om [IGenericCollection](../../com.aspose.slides/igenericcollection) är skrivskyddad. Läs-endast boolean.

**Returnerar:**
boolean – true om [IGenericCollection](../../com.aspose.slides/igenericcollection) är skrivskyddad; annars false.

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Returnerar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). Läs-endast boolean.

**Returnerar:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Returnerar ett synkroniseringsrot. Läs-endast Object.

**Returnerar:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

Returnerar en enumerator som itererar genom samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - En IGenericEnumerator som kan användas för att iterera genom samlingen.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

Returnerar en java-iterator för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - En java.util.Iterator för hela samlingen.