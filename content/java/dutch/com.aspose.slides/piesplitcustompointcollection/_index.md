---
title: PieSplitCustomPointCollection
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een collectie punten voor voor het splitsen van een punt in een staaf-van-taart- of taart-van-taart-grafiek met een aangepaste splitsing.
type: docs
url: /nl/com.aspose.slides/piesplitcustompointcollection/
---
**Overerving:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
```
public class PieSplitCustomPointCollection implements IPieSplitCustomPointCollection
```

Stelt een collectie punten voor voor het splitsen van een punt in een staaf-van-taart- of taart-van-taart-grafiek met een aangepaste splitsing.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retourneert diagramgegevenspunt voor opgegeven index. |
| [add(int dataPointIndex)](#add-int-) | Voegt gegevenspunt toe op basis van zijn index in de bovenliggende series-punten-collectie. |
| [addItem(IChartDataPoint dataPoint)](#addItem-com.aspose.slides.IChartDataPoint-) | Voegt gegevenspunt toe aan de collectie. |
| [removeItem(IChartDataPoint dataPoint)](#removeItem-com.aspose.slides.IChartDataPoint-) | Verwijdert item uit de collectie. |
| [remove(int dataPointIndex)](#remove-int-) | Verwijdert item uit de collectie op basis van zijn index in de bovenliggende series-punten-collectie. |
| [clear()](#clear--) | Verwijdert alle items uit de [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [containsItem(IChartDataPoint item)](#containsItem-com.aspose.slides.IChartDataPoint-) | Bepaalt of de [IGenericCollection](../../com.aspose.slides/igenericcollection) een specifieke waarde bevat. |
| [copyToTArray(IChartDataPoint[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IChartDataPoint---int-) | Kopieert de elementen van de [IGenericCollection](../../com.aspose.slides/igenericcollection) naar een array, beginnend bij een bepaalde array-index. |
| [size()](#size--) | Retourneert of stelt het aantal diagramgegevenspunten in. |
| [isReadOnly()](#isReadOnly--) | Haalt een waarde op die aangeeft of de [IGenericCollection](../../com.aspose.slides/igenericcollection) alleen-lezen is. |
| [isSynchronized()](#isSynchronized--) | Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd (thread-safe) is. |
| [getSyncRoot()](#getSyncRoot--) | Retourneert een synchronisatiewortel. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie iterereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java-iterator voor de volledige collectie. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

Retourneert diagramgegevenspunt voor opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index. |

**Retour:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Diagramgegevenspunt.
### add(int dataPointIndex) {#add-int-}
```
public final void add(int dataPointIndex)
```

Voegt gegevenspunt toe op basis van zijn index in de bovenliggende series-punten-collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dataPointIndex | int | Index van het gegevenspunt in de bovenliggende series-punten-collectie. |
### addItem(IChartDataPoint dataPoint) {#addItem-com.aspose.slides.IChartDataPoint-}
```
public void addItem(IChartDataPoint dataPoint)
```

Voegt gegevenspunt toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Gegevenspunt om toe te voegen. |
### removeItem(IChartDataPoint dataPoint) {#removeItem-com.aspose.slides.IChartDataPoint-}
```
public boolean removeItem(IChartDataPoint dataPoint)
```

Verwijdert item uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Gegevenspunt om te verwijderen. |

**Retour:**
boolean - true als het item succesvol is verwijderd; anders false. Deze methode geeft ook false terug als het item niet in de System.Collections.Generic.List\{T\} werd gevonden.
### remove(int dataPointIndex) {#remove-int-}
```
public final void remove(int dataPointIndex)
```

Verwijdert item uit de collectie op basis van zijn index in de bovenliggende series-punten-collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dataPointIndex | int | Index van het gegevenspunt in de bovenliggende series-punten-collectie. |
### clear() {#clear--}
```
public final void clear()
```

Verwijdert alle items uit de [IGenericCollection](../../com.aspose.slides/igenericcollection).

### containsItem(IChartDataPoint item) {#containsItem-com.aspose.slides.IChartDataPoint-}
```
public boolean containsItem(IChartDataPoint item)
```

Bepaalt of de [IGenericCollection](../../com.aspose.slides/igenericcollection) een specifieke waarde bevat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Het object om te zoeken in de [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Retour:**
boolean - true als het item wordt gevonden in de [IGenericCollection](../../com.aspose.slides/igenericcollection); anders false.
### copyToTArray(IChartDataPoint[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IChartDataPoint---int-}
```
public void copyToTArray(IChartDataPoint[] array, int arrayIndex)
```

Kopieert de elementen van de [IGenericCollection](../../com.aspose.slides/igenericcollection) naar een array, beginnend bij een bepaalde array-index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | [IChartDataPoint\[\]](../../com.aspose.slides/ichartdatapoint) | De één-dimensionale array die de bestemming is van de gekopieerde elementen van [IGenericCollection](../../com.aspose.slides/igenericcollection). De array moet nul-gebaseerde indexering hebben. |
| arrayIndex | int | De nul-gebaseerde index in de array waarop het kopiëren begint. |
### size() {#size--}
```
public final int size()
```

Retourneert of stelt het aantal diagramgegevenspunten in. Alleen-lezen int.

**Retour:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Haalt een waarde op die aangeeft of de [IGenericCollection](../../com.aspose.slides/igenericcollection) alleen-lezen is. Alleen-lezen boolean.

**Retour:**
boolean - true als de [IGenericCollection](../../com.aspose.slides/igenericcollection) alleen-lezen is; anders false.
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd (thread-safe) is. Alleen-lezen boolean.

**Retour:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Retourneert een synchronisatiewortel. Alleen-lezen Object.

**Retour:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

Retourneert een enumerator die door de collectie iterereert.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

Retourneert een java-iterator voor de volledige collectie.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Een java.util.Iterator voor de volledige collectie.