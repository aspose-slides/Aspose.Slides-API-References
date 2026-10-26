---
title: ChartCellCollection
second_title: Aspose.Slides pro Android prostřednictvím reference Java API
description: Representuje kolekci buněk s daty.
type: docs
url: /cs/com.aspose.slides/chartcellcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IChartCellCollection](../../com.aspose.slides/ichartcellcollection), com.aspose.slides.IDOMObject
```
public class ChartCellCollection implements IChartCellCollection, IDOMObject
```

Representuje kolekci buněk s daty.
## Metody

| Metoda | Popis |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | Vrací adresu sady buněk v sešitu. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | Řetězec vzniklý spojením všech řetězcových hodnot buněk. |
| [get_Item(int index)](#get-Item-int-) | Vrací buňku (IChartDataCell) podle indexu. |
| [add(IChartDataCell cell)](#add-com.aspose.slides.IChartDataCell-) | Přidejte novou buňku do kolekce. |
| [add(Object value)](#add-java.lang.Object-) | Vytvoří [ChartDataCell](../../com.aspose.slides/chartdatacell) ze specifikované hodnoty a přidá ji do kolekce. |
| [removeAt(int index)](#removeAt-int-) | Odstraní buňku z kolekce podle indexu. |
| [getCount()](#getCount--) | Získá počet buněk v kolekci. |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází kolekcí. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterátor pro celou kolekci. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getCellsAddress() {#getCellsAddress--}
```
public final String getCellsAddress()
```


Vrací adresu sady buněk v sešitu.

**Vrací:**
java.lang.String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public final String getConcatenatedValuesFromCells()
```


Řetězec vzniklý spojením všech řetězcových hodnot buněk.

**Vrací:**
java.lang.String
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataCell get_Item(int index)
```


Vrací buňku (IChartDataCell) podle indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index buňky. |

**Vrací:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell s daty.
### add(IChartDataCell cell) {#add-com.aspose.slides.IChartDataCell-}
```
public final void add(IChartDataCell cell)
```


Přidejte novou buňku do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Nová buňka k přidání. |

### add(Object value) {#add-java.lang.Object-}
```
public final void add(Object value)
```


Vytvoří [ChartDataCell](../../com.aspose.slides/chartdatacell) ze specifikované hodnoty a přidá ji do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.Object | Hodnota.

--------------------

Tato metoda přidá list s názvem AUTO_DATA a vloží do něj všechny hodnoty. Pokud používáte [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) k přidávání nebo úpravě hodnot Cell, ujistěte se, že tento list nepoužíváte. Maximální počet hodnot přidaných pomocí této metody nesmí překročit 16711680 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Odstraní buňku z kolekce podle indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index buňky k odstranění. |

### getCount() {#getCount--}
```
public final int getCount()
```


Získá počet buněk v kolekci. Pouze pro čtení int.

**Vrací:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iterator()
```


Vrací enumerátor, který prochází kolekcí.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - IGenericEnumerator, který lze použít k iteraci přes kolekci.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iteratorJava()
```


Vrací java iterátor pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - java.util.Iterator pro celou kolekci.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Vrací objekt Parent_Immediate. Pouze pro čtení IDOMObject.

**Vrací:**
com.aspose.slides.IDOMObject