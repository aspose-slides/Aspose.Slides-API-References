---
title: ChartCellCollection
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje kolekci buněk s daty.
type: docs
url: /cs/com.aspose.slides/chartcellcollection/
---
**Dědičnost:**
java.lang.Object

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IChartCellCollection](../../com.aspose.slides/ichartcellcollection), com.aspose.slides.IDOMObject
```
public class ChartCellCollection implements IChartCellCollection, IDOMObject
```

Reprezentuje kolekci buněk s daty.
## Metody

| Metoda | Popis |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | Vrací adresu sady buněk v sešitu. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | Řetězec získaný spojením řetězcových hodnot všech buněk. |
| [get_Item(int index)](#get-Item-int-) | Vrací buňku (IChartDataCell) podle indexu. |
| [add(IChartDataCell cell)](#add-com.aspose.slides.IChartDataCell-) | Přidá novou buňku do kolekce. |
| [add(Object value)](#add-java.lang.Object-) | Vytvoří [ChartDataCell](../../com.aspose.slides/chartdatacell) ze zadané hodnoty a přidá jej do kolekce. |
| [removeAt(int index)](#removeAt-int-) | Odebere buňku z kolekce podle indexu. |
| [getCount()](#getCount--) | Získá počet buněk v kolekci. |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází kolekcí. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterator pro celou kolekci. |
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

Řetězec získaný spojením řetězcových hodnot všech buněk.

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
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Buňka s daty.
### add(IChartDataCell cell) {#add-com.aspose.slides.IChartDataCell-}
```
public final void add(IChartDataCell cell)
```

Přidá novou buňku do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Nová buňka k přidání. |

### add(Object value) {#add-java.lang.Object-}
```
public final void add(Object value)
```

Vytvoří [ChartDataCell](../../com.aspose.slides/chartdatacell) ze zadané hodnoty a přidá jej do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.Object | Hodnota. |

--------------------

Tato metoda přidá list s názvem AUTO_DATA a přidá do něj všechny hodnoty. Pokud používáte [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) k přidání nebo úpravě hodnot buněk, ujistěte se, že tento list nepoužíváte. Maximální počet hodnot přidaných pomocí této metody nesmí překročit 16711680 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Odebere buňku z kolekce podle indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index buňky k odebrání. |

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

Vrací java iterator pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - java.util.Iterator pro celou kolekci.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Vrací objekt Parent_Immediate. Pouze pro čtení IDOMObject.

**Vrací:**
com.aspose.slides.IDOMObject