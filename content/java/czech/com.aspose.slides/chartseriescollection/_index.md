---
title: ChartSeriesCollection
second_title: Aspose.Slides pro Java referenční příručka API
description: Reprezentuje kolekci
type: docs
url: /cs/com.aspose.slides/chartseriescollection/
---
**Dědičnost:**
java.lang.Object, com.aspose.slides.DomObject

**Všechny implementované rozhraní:**
[com.aspose.slides.IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
```
public class ChartSeriesCollection extends DomObject<ChartData> implements IChartSeriesCollection
```

Představuje kolekci [ChartSeries](../../com.aspose.slides/chartseries)
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Získává prvek na zadaném indexu. |
| [size()](#size--) | Vrací počet objektů v kolekci. |
| [add(int type)](#add-int-) | Vytvoří novou sérii grafu a přidá ji do kolekce. |
| [insert(int index, int type)](#insert-int-int-) | Vytvoří novou sérii grafu a vloží ji do kolekce. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | Vytvoří novou sérii grafu z [ChartDataCell](../../com.aspose.slides/chartdatacell) a přidá ji do kolekce. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | Vytvoří novou sérii grafu z [ChartCellCollection](../../com.aspose.slides/chartcellcollection) a přidá ji do kolekce. |
| [add(String name, int type)](#add-java.lang.String-int-) | Vytvoří novou sérii grafu z hodnoty a přidá ji do kolekce. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | Vyhledá zadaný [ChartSeries](../../com.aspose.slides/chartseries) a vrátí index počínaje nulou první výskyt v celé kolekci |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | Odstraní zadanou hodnotu. |
| [removeAt(int index)](#removeAt-int-) | Odstraní ActiveX ovládací prvek uložený na zadané pozici z kolekce. |
| [clear()](#clear--) | Odstraní všechny ovládací prvky z kolekce. |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází kolekcí. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterátor pro celou kolekci. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Zkopíruje celou kolekci do zadaného pole. |
| [isSynchronized()](#isSynchronized--) | Vrací hodnotu indikující, zda je přístup ke kolekci synchronizován (vláknově bezpečný). |
| [getSyncRoot()](#getSyncRoot--) | Vrací kořen synchronizace. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

Získává prvek na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Prvek na zadaném indexu.
### size() {#size--}
```
public final int size()
```

Vrací počet objektů v kolekci. Pouze pro čtení int.

**Vrací:**
int
### add(int type) {#add-int-}
```
public final IChartSeries add(int type)
```

Vytvoří novou sérii grafu a přidá ji do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| type | int | Typ série |

**Vrací:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Nová série grafu.
### insert(int index, int type) {#insert-int-int-}
```
public final IChartSeries insert(int index, int type)
```

Vytvoří novou sérii grafu a vloží ji do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |
| type | int |  |

**Vrací:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public final IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

Vytvoří novou sérii grafu z [ChartDataCell](../../com.aspose.slides/chartdatacell) a přidá ji do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Buňka, která obsahuje název série. |
| type | int | Typ nastavený typu série |

--------------------

Pokud je série grafu vytvořena ze stejné buňky, která již v kolekci existuje, metoda nic nepřidá a vrátí její index. |

**Vrací:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Přidaná série grafu nebo série, která již v kolekci je.
### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public final IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

Vytvoří novou sérii grafu z [ChartCellCollection](../../com.aspose.slides/chartcellcollection) a přidá ji do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | Buňky, které obsahují název série. |
| type | int | Typ nastavený typu série |

--------------------

Pokud je série grafu vytvořena ze stejné buňky, která již v kolekci existuje, metoda nic nepřidá a vrátí její index. |

**Vrací:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Přidaná série grafu nebo série, která již v kolekci je.
### add(String name, int type) {#add-java.lang.String-int-}
```
public final IChartSeries add(String name, int type)
```

Vytvoří novou sérii grafu z hodnoty a přidá ji do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název série. |
| type | int | Typ nastavený typu série |

**Vrací:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Přidaná série grafu.
### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public final int indexOf(IChartSeries value)
```

Vyhledá zadaný [ChartSeries](../../com.aspose.slides/chartseries) a vrátí index počínaje nulou první výskyt v celé kolekci

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Hodnota série grafu. |

**Vrací:**
int - Index počínaje nulou první výskyt hodnoty v celé CollectionBase, pokud je nalezena; jinak -1.
### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public final void remove(IChartSeries value)
```

Odstraňuje zadanou hodnotu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Hodnota. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Odstraňuje ActiveX ovládací prvek uložený na zadané pozici z kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index ovládacího prvku, který má být odstraněn. |
### clear() {#clear--}
```
public final void clear()
```

Odstraňuje všechny ovládací prvky z kolekce.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iterator()
```

Vrací enumerátor, který prochází kolekcí.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - IGenericEnumerator, který lze použít k iteraci přes kolekci.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iteratorJava()
```

Vrací java iterátor pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - java.util.Iterator pro celou kolekci.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopíruje celou kolekci do zadaného pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cílové pole |
| index | int | Index v cílovém poli. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Vrací hodnotu indikující, zda je přístup ke kolekci synchronizován (vláknově bezpečný). Pouze pro čtení boolean.

**Vrací:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Vrací kořen synchronizace. Pouze pro čtení Object.

**Vrací:**
java.lang.Object