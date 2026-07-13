---
title: PieSplitCustomPointCollection
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Representuje kolekci bodů pro rozdělovací bod v grafu typu bar-of-pie nebo pie-of-pie s vlastním rozdělením.
type: docs
url: /cs/com.aspose.slides/piesplitcustompointcollection/
---
**Dědičnost:**
java.lang.Object

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
```
public class PieSplitCustomPointCollection implements IPieSplitCustomPointCollection
```

Representuje kolekci bodů pro rozdělovací bod v grafu typu bar-of-pie nebo pie-of-pie s vlastním rozdělením.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Vrací datový bod grafu pro zadaný index. |
| [add(int dataPointIndex)](#add-int-) | Přidá datový bod podle jeho indexu v kolekci bodů nadřazené řady. |
| [addItem(IChartDataPoint dataPoint)](#addItem-com.aspose.slides.IChartDataPoint-) | Přidá datový bod do kolekce. |
| [removeItem(IChartDataPoint dataPoint)](#removeItem-com.aspose.slides.IChartDataPoint-) | Odstraní položku z kolekce. |
| [remove(int dataPointIndex)](#remove-int-) | Odstraní položku z kolekce podle jejího indexu v kolekci bodů nadřazené řady. |
| [clear()](#clear--) | Odstraní všechny položky z [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [containsItem(IChartDataPoint item)](#containsItem-com.aspose.slides.IChartDataPoint-) | Určuje, zda [IGenericCollection](../../com.aspose.slides/igenericcollection) obsahuje konkrétní hodnotu. |
| [copyToTArray(IChartDataPoint[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IChartDataPoint---int-) | Kopíruje prvky [IGenericCollection](../../com.aspose.slides/igenericcollection) do pole, počínaje konkrétním indexem pole. |
| [size()](#size--) | Vrací nebo nastavuje počet datových bodů grafu. |
| [isReadOnly()](#isReadOnly--) | Získá hodnotu, která určuje, zda je [IGenericCollection](../../com.aspose.slides/igenericcollection) jen pro čtení. |
| [isSynchronized()](#isSynchronized--) | Vrací hodnotu, která určuje, zda je přístup ke kolekci synchronizován (vláknově bezpečný). |
| [getSyncRoot()](#getSyncRoot--) | Vrací kořen synchronizace. |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází kolekcí. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterátor pro celou kolekci. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

Vrací datový bod grafu pro zadaný index.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index. |

**Návratová hodnota:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Datový bod grafu.
### add(int dataPointIndex) {#add-int-}
```
public final void add(int dataPointIndex)
```

Přidá datový bod podle jeho indexu v kolekci bodů nadřazené řady.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| dataPointIndex | int | Index datového bodu v kolekci bodů nadřazené řady. |
### addItem(IChartDataPoint dataPoint) {#addItem-com.aspose.slides.IChartDataPoint-}
```
public void addItem(IChartDataPoint dataPoint)
```

Přidá datový bod do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Datový bod, který se má přidat. |
### removeItem(IChartDataPoint dataPoint) {#removeItem-com.aspose.slides.IChartDataPoint-}
```
public boolean removeItem(IChartDataPoint dataPoint)
```

Odstraní položku z kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Datový bod, který se má odstranit. |

**Návratová hodnota:**
boolean - true, pokud je položka úspěšně odstraněna; jinak false. Tato metoda také vrací false, pokud položka nebyla nalezena v System.Collections.Generic.List\{T\}.
### remove(int dataPointIndex) {#remove-int-}
```
public final void remove(int dataPointIndex)
```

Odstraní položku z kolekce podle jejího indexu v kolekci bodů nadřazené řady.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| dataPointIndex | int | Index datového bodu v kolekci bodů nadřazené řady. |
### clear() {#clear--}
```
public final void clear()
```

Odstraní všechny položky z [IGenericCollection](../../com.aspose.slides/igenericcollection).
### containsItem(IChartDataPoint item) {#containsItem-com.aspose.slides.IChartDataPoint-}
```
public boolean containsItem(IChartDataPoint item)
```

Určuje, zda [IGenericCollection](../../com.aspose.slides/igenericcollection) obsahuje konkrétní hodnotu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Objekt, který se má vyhledat v [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Návratová hodnota:**
boolean – true, pokud je položka nalezena v [IGenericCollection](../../com.aspose.slides/igenericcollection); jinak false.
### copyToTArray(IChartDataPoint[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IChartDataPoint---int-}
```
public void copyToTArray(IChartDataPoint[] array, int arrayIndex)
```

Kopíruje prvky [IGenericCollection](../../com.aspose.slides/igenericcollection) do pole, počínaje konkrétním indexem pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | [IChartDataPoint\[\]](../../com.aspose.slides/ichartdatapoint) | Jednorozměrné pole, které je cílem prvků zkopírovaných z [IGenericCollection](../../com.aspose.slides/igenericcollection). Pole musí mít nulové indexování. |
| arrayIndex | int | Nulový index v poli, od kterého začíná kopírování. |
### size() {#size--}
```
public final int size()
```

Vrací nebo nastavuje počet datových bodů grafu. Pouze pro čtení int.

**Návratová hodnota:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Získá hodnotu určující, zda je [IGenericCollection](../../com.aspose.slides/igenericcollection) jen pro čtení. Pouze pro čtení boolean.

**Návratová hodnota:**
boolean – true, pokud je [IGenericCollection](../../com.aspose.slides/igenericcollection) jen pro čtení; jinak false.
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Vrací hodnotu, která určuje, zda je přístup ke kolekci synchronizován (vláknově bezpečný). Pouze pro čtení boolean.

**Návratová hodnota:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Vrací kořen synchronizace. Pouze pro čtení Object.

**Návratová hodnota:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

Vrací enumerátor, který prochází kolekcí.

**Návratová hodnota:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - IGenericEnumerator, který lze použít k iteraci přes kolekci.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

Vrací java iterátor pro celou kolekci.

**Návratová hodnota:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - java.util.Iterator pro celou kolekci.