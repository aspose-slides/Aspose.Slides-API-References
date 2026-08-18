---
title: PieSplitCustomPointCollection
second_title: Aspose.Slides Java API Referenciája
description: Egy gyűjteményt képvisel a pontokról, amelyek egy bar-of-pie vagy pie-of-pie diagram szétválasztási pontjának egyéni szétválasztásához használhatók.
type: docs
url: /hu/com.aspose.slides/piesplitcustompointcollection/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
```
public class PieSplitCustomPointCollection implements IPieSplitCustomPointCollection
```

Egy gyűjteményt képvisel a pontokról, amelyek egy bar-of-pie vagy pie-of-pie diagram szétválasztási pontjának testreszabott szétválasztásához használhatók.

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaadja a diagram adatpontot a megadott indexhez. |
| [add(int dataPointIndex)](#add-int-) | Hozzáad egy adatpontot a szülő sorozat pontgyűjteményében lévő indexe alapján. |
| [addItem(IChartDataPoint dataPoint)](#addItem-com.aspose.slides.IChartDataPoint-) | Hozzáad egy adatpontot a gyűjteményhez. |
| [removeItem(IChartDataPoint dataPoint)](#removeItem-com.aspose.slides.IChartDataPoint-) | Eltávolít egy elemet a gyűjteményből. |
| [remove(int dataPointIndex)](#remove-int-) | Eltávolít egy elemet a gyűjteményből a szülő sorozat pontgyűjteményében lévő indexe alapján. |
| [clear()](#clear--) | Eltávolítja az összes elemet a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ből. |
| [containsItem(IChartDataPoint item)](#containsItem-com.aspose.slides.IChartDataPoint-) | Megállapítja, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) tartalmaz-e egy adott értéket. |
| [copyToTArray(IChartDataPoint[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IChartDataPoint---int-) | A [IGenericCollection](../../com.aspose.slides/igenericcollection) elemeit egy tömbbe másolja, egy adott tömbindexnél kezdve. |
| [size()](#size--) | Visszaadja vagy beállítja a diagram adatpontok számát. |
| [isReadOnly()](#isReadOnly--) | Lekér egy értéket, amely jelzi, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) csak olvasható-e. |
| [isSynchronized()](#isSynchronized--) | Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos)-e. |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy szinkronizációs gyökeret. |
| [iterator()](#iterator--) | Visszaad egy felsorolót, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy Java iterátort a teljes gyűjteményhez. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

Visszaadja a diagram adatpontot a megadott indexhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az index. |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Chart data point.

### add(int dataPointIndex) {#add-int-}
```
public final void add(int dataPointIndex)
```

Hozzáad egy adatpontot a szülő sorozat pontgyűjteményében lévő indexe alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| dataPointIndex | int | Az adatpont indexe a szülő sorozat pontgyűjteményében. |

### addItem(IChartDataPoint dataPoint) {#addItem-com.aspose.slides.IChartDataPoint-}
```
public void addItem(IChartDataPoint dataPoint)
```

Hozzáad egy adatpontot a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Az adatpont, amelyhez hozzáadódik. |

### removeItem(IChartDataPoint dataPoint) {#removeItem-com.aspose.slides.IChartDataPoint-}
```
public boolean removeItem(IChartDataPoint dataPoint)
```

Eltávolít egy elemet a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Az adatpont, amelyet el kell távolítani. |

**Visszatérési érték:**
boolean - igaz, ha az elem sikeresen eltávolításra került; egyébként hamis. Ez a metódus hamis értéket is visszaad, ha az elem nem található a System.Collections.Generic.List\{T\}-ben.

### remove(int dataPointIndex) {#remove-int-}
```
public final void remove(int dataPointIndex)
```

Eltávolít egy elemet a gyűjteményből a szülő sorozat pontgyűjteményében lévő indexe alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| dataPointIndex | int | Az adatpont indexe a szülő sorozat pontgyűjteményében. |

### clear() {#clear--}
```
public final void clear()
```

Eltávolítja az összes elemet a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ból.

### containsItem(IChartDataPoint item) {#containsItem-com.aspose.slides.IChartDataPoint-}
```
public boolean containsItem(IChartDataPoint item)
```

Megállapítja, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) tartalmaz-e egy adott értéket.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Az objektum, amelyet a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ben keresünk. |

**Visszatérési érték:**
boolean - igaz, ha az elem megtalálható a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ben; egyébként hamis.

### copyToTArray(IChartDataPoint[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IChartDataPoint---int-}
```
public void copyToTArray(IChartDataPoint[] array, int arrayIndex)
```

A [IGenericCollection](../../com.aspose.slides/igenericcollection) elemeit egy tömbbe másolja, egy adott tömbindexnél kezdve.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | [IChartDataPoint\[\]](../../com.aspose.slides/ichartdatapoint) | Az egydimenziós tömb, amely a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ből másolt elemek célcélpontja. A tömbnek nullával kezdődő indexelése van. |
| arrayIndex | int | A nullával kezdődő index a tömbben, ahol a másolás kezdődik. |

### size() {#size--}
```
public final int size()
```

Visszaadja vagy beállítja a diagram adatpontok számát. Csak olvasható int.

**Visszatérési érték:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Lekér egy értéket, amely jelzi, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) csak olvasható-e. Csak olvasható boolean.

**Visszatérési érték:**
boolean - igaz, ha a [IGenericCollection](../../com.aspose.slides/igenericcollection) csak olvasható; egyébként hamis.

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos)-e. Csak olvasható boolean.

**Visszatérési érték:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Visszaad egy szinkronizációs gyökeret. Csak olvasható Object.

**Visszatérési érték:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

Visszaad egy felsorolót, amely végigiterál a gyűjteményen.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - egy IGenericEnumerator, amely a gyűjteményen való iteráláshoz használható.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

Visszaad egy Java iterátort a teljes gyűjteményhez.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - egy java.util.Iterator a teljes gyűjteményhez.