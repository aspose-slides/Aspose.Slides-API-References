---
title: PieSplitCustomPointCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een verzameling punten voor die worden gebruikt om een punt te splitsen in een staaf-van-taart- of taart-van-taart-diagram met een aangepaste splitsing.
type: docs
url: /nl/com.aspose.slides/piesplitcustompointcollection/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
```
public class PieSplitCustomPointCollection implements IPieSplitCustomPointCollection
```

Stelt een verzameling punten voor die worden gebruikt om een punt te splitsen in een staaf-van-taart- of taart-van-taart-diagram met een aangepaste splitsing.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retourneert grafiekgegevenspunt voor de opgegeven index. |
| [add(int dataPointIndex)](#add-int-) | Voegt een gegevenspunt toe op basis van zijn index in de puntenverzameling van de bovenliggende serie. |
| [addItem(IChartDataPoint dataPoint)](#addItem-com.aspose.slides.IChartDataPoint-) | Voegt een gegevenspunt toe aan de verzameling. |
| [removeItem(IChartDataPoint dataPoint)](#removeItem-com.aspose.slides.IChartDataPoint-) | Verwijdert een item uit de verzameling. |
| [remove(int dataPointIndex)](#remove-int-) | Verwijdert een item uit de verzameling op basis van zijn index in de puntenverzameling van de bovenliggende serie. |
| [clear()](#clear--) | Verwijdert alle items uit de [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [containsItem(IChartDataPoint item)](#containsItem-com.aspose.slides.IChartDataPoint-) | Bepaalt of de [IGenericCollection](../../com.aspose.slides/igenericcollection) een specifieke waarde bevat. |
| [copyToTArray(IChartDataPoint[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IChartDataPoint---int-) | Kopieert de elementen van de [IGenericCollection](../../com.aspose.slides/igenericcollection) naar een array, beginnend bij een bepaalde array-index. |
| [size()](#size--) | Retourneert of stelt het aantal grafiekgegevenspunten in. |
| [isReadOnly()](#isReadOnly--) | Geeft een waarde terug die aangeeft of de [IGenericCollection](../../com.aspose.slides/igenericcollection) alleen-lezen is. |
| [isSynchronized()](#isSynchronized--) | Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd (thread-safe) is. |
| [getSyncRoot()](#getSyncRoot--) | Retourneert een synchronisatiewortel. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de verzameling iterereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java-iterator voor de volledige verzameling. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```


Retourneert grafiekgegevenspunt voor de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index. |

**Retour:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Grafiekgegevenspunt.
### add(int dataPointIndex) {#add-int-}
```
public final void add(int dataPointIndex)
```


Voegt een gegevenspunt toe op basis van zijn index in de puntenverzameling van de bovenliggende serie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dataPointIndex | int | Index van het gegevenspunt in de puntenverzameling van de bovenliggende serie. |
### addItem(IChartDataPoint dataPoint) {#addItem-com.aspose.slides.IChartDataPoint-}
```
public void addItem(IChartDataPoint dataPoint)
```


Voegt een gegevenspunt toe aan de verzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Gegevenspunt om toe te voegen. |
### removeItem(IChartDataPoint dataPoint) {#removeItem-com.aspose.slides.IChartDataPoint-}
```
public boolean removeItem(IChartDataPoint dataPoint)
```


Verwijdert een item uit de verzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Gegevenspunt om te verwijderen. |

**Retour:**
boolean - true als het item succesvol is verwijderd; anders false. Deze methode retourneert ook false als het item niet werd gevonden in de System.Collections.Generic.List\{T\}.
### remove(int dataPointIndex) {#remove-int-}
```
public final void remove(int dataPointIndex)
```


Verwijdert een item uit de verzameling op basis van zijn index in de puntenverzameling van de bovenliggende serie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dataPointIndex | int | Index van het gegevenspunt in de puntenverzameling van de bovenliggende serie. |
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
| item | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Het object dat moet worden gevonden in de [IGenericCollection](../../com.aspose.slides/igenericcollection). |

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
| array | [IChartDataPoint\[\]](../../com.aspose.slides/ichartdatapoint) | De een-dimensionale array die het doel is van de elementen gekopieerd van [IGenericCollection](../../com.aspose.slides/igenericcollection). De array moet nulgebaseerde indexering hebben. |
| arrayIndex | int | De nulgebaseerde index in de array waarop het kopiëren begint. |
### size() {#size--}
```
public final int size()
```


Retourneert of stelt het aantal grafiekgegevenspunten in. Alleen-lezen int.

**Retour:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Geeft een waarde terug die aangeeft of de [IGenericCollection](../../com.aspose.slides/igenericcollection) alleen-lezen is. Alleen-lezen boolean.

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


Retourneert een enumerator die door de verzameling iterereert.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Een IGenericEnumerator die kan worden gebruikt om door de verzameling te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```


Retourneert een java-iterator voor de volledige collectie.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Een java.util.Iterator voor de volledige collectie.