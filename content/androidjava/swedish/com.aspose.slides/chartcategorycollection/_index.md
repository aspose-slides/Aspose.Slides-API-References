---
title: ChartCategoryCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av
type: docs
url: /sv/com.aspose.slides/chartcategorycollection/
---
**Arv:**
java.lang.Object, com.aspose.slides.DomObject

**Alla implementerade gränssnitt:**
[com.aspose.slides.IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
```
public class ChartCategoryCollection extends DomObject<ChartData> implements IChartCategoryCollection
```

Representerar samling av [ChartCategory](../../com.aspose.slides/chartcategory)
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Hämtar elementet på det angivna indexet. |
| [getUseCells()](#getUseCells--) | Om true används kalkylbladet för att lagra kategorier (detta fall stöder flernivåkategorier). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | Om true används kalkylbladet för att lagra kategorier (detta fall stöder flernivåkategorier). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | Returnerar antalet nivåer för kategorigruppering som används. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Om kategori finns i samlingen, returnera den. |
| [add(Object value)](#add-java.lang.Object-) | Skapar ny [ChartCategory](../../com.aspose.slides/chartcategory) från värde och lägger till den i samlingen. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | Söker efter den angivna [ChartCategory](../../com.aspose.slides/chartcategory) och returnerar det nollbaserade indexet för den första förekomsten i hela samlingen. |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | Tar bort det angivna värdet. |
| [removeAt(int index)](#removeAt-int-) | Tar bort elementet på det angivna indexet. |
| [clear()](#clear--) | Tar bort alla element från samlingen. |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [iteratorJava()](#iteratorJava--) | Returnerar en java-iterator för hela samlingen. |
| [size()](#size--) | Returnerar antalet element i samlingen. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopierar alla element i samlingen till den angivna arrayen. |
| [isSynchronized()](#isSynchronized--) | Returnerar ett värde som indikerar om åtkomst till listan är synkroniserad (trådsäker). |
| [getSyncRoot()](#getSyncRoot--) | Returnerar ett objekt som kan användas för att synkronisera åtkomst till samlingen. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartCategory get_Item(int index)
```

Hämtar elementet på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Elementet på det angivna indexet.

### getUseCells() {#getUseCells--}
```
public final boolean getUseCells()
```

Om true används kalkylbladet för att lagra kategorier (detta fall stöder flernivåkategorier). Om false används kalkylbladet INTE för att lagra värden (och detta fall stöder inte flernivåkategorier). Läs/skriv boolesk.

**Returnerar:**
boolean

### setUseCells(boolean value) {#setUseCells-boolean-}
```
public final void setUseCells(boolean value)
```

Om true används kalkylbladet för att lagra kategorier (detta fall stöder flernivåkategorier). Om false används kalkylbladet INTE för att lagra värden (och detta fall stöder inte flernivåkategorier). Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public final int getGroupingLevelCount()
```

Returnerar antalet nivåer för kategorigruppering som används. Är fler än ett för flernivåkategorier. Skrivskyddad int.

**Returnerar:**
int

### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public final IChartCategory add(IChartDataCell chartDataCell)
```

Om kategori finns i samlingen, returnera den. Annars skapas en ny diagramkategori från [IChartDataCell](../../com.aspose.slides/ichartdatacell) och läggs till i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell som används för att skapa diagramkategori. |

**Returnerar:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Tillagd eller befintlig kategori.

### add(Object value) {#add-java.lang.Object-}
```
public final IChartCategory add(Object value)
```

Skapar ny [ChartCategory](../../com.aspose.slides/chartcategory) från värde och lägger till den i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.Object | Värdet.

--------------------

Denna metod lägger till ett kalkylblad med namnet AUTO_DATA och lägger till alla värden där. Om du använder [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) för att lägga till eller redigera cellvärden, se till att du inte använder detta kalkylblad. Maximalt antal värden som läggs till med denna metod får inte överstiga 16711680 |

**Returnerar:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Tillagd [IChartCategory](../../com.aspose.slides/ichartcategory).

### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public final int indexOf(IChartCategory value)
```

Söker efter den angivna [ChartCategory](../../com.aspose.slides/chartcategory) och returnerar det nollbaserade indexet för den första förekomsten i hela samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Diagramkategori. |

**Returnerar:**
int - Det nollbaserade indexet för den första förekomsten av värdet i hela CollectionBase, om det hittas; annars -1.

### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public final void remove(IChartCategory value)
```

Tar bort det angivna värdet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Värdet. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Tar bort elementet på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för den kategori som ska tas bort. |

### clear() {#clear--}
```
public final void clear()
```

Tar bort alla element från samlingen.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iterator()
```

Returnerar en enumerator som itererar genom samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - En IGenericEnumerator som kan användas för att iterera genom samlingen.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iteratorJava()
```

Returnerar en java-iterator för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - En java.util.Iterator för hela samlingen.

### size() {#size--}
```
public final int size()
```

Returnerar antalet element i samlingen. Skrivskyddad int.

**Returnerar:**
int

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopierar alla element i samlingen till den angivna arrayen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Målarray. |
| index | int | Startindex i arrayen. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Returnerar ett värde som indikerar om åtkomst till listan är synkroniserad (trådsäker). Skrivskyddad boolesk.

**Returnerar:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Returnerar ett objekt som kan användas för att synkronisera åtkomst till samlingen. Skrivskyddad Object.
Returnerar ett synkroniseringsrot. Skrivskyddad Object.

**Returnerar:**
java.lang.Object