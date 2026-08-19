---
title: IChartCellCollection
second_title: Aspose.Slides pro Java - referenční příručka API
description: Representuje kolekci buněk s daty.
type: docs
url: /cs/com.aspose.slides/ichartcellcollection/
---
**Všechna implementovaná rozhraní:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IChartCellCollection extends System.Collections.Generic.IGenericEnumerable<IChartDataCell>
```

Representuje kolekci buněk s daty.
## Metody

| Metoda | Popis |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | Vrací adresu sady buněk v sešitu. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | Spojí řetězec ze všech hodnot buněk. |
| [get_Item(int index)](#get-Item-int-) | Vrací buňku (IChartDataCell) podle indexu. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Přidá novou buňku do kolekce. |
| [add(Object value)](#add-java.lang.Object-) | Vytvoří [IChartDataCell](../../com.aspose.slides/ichartdatacell) ze zadané hodnoty a přidá jej do kolekce. |
| [removeAt(int index)](#removeAt-int-) | Odstraní buňku z kolekce podle indexu. |
| [getCount()](#getCount--) | Získá počet buněk v kolekci. |
### getCellsAddress() {#getCellsAddress--}
```
public abstract String getCellsAddress()
```


Vrací adresu sady buněk v sešitu.

**Vrací:**
java.lang.String - Adresa sady buněk v sešitu

### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public abstract String getConcatenatedValuesFromCells()
```


Spojí řetězec ze všech hodnot buněk.

**Vrací:**
java.lang.String - Výsledný řetězec

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int index)
```


Vrací buňku (IChartDataCell) podle indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index buňky. |

**Vrací:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Buňka s daty.

### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract void add(IChartDataCell chartDataCell)
```


Přidá novou buňku do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Nová buňka k přidání. |

### add(Object value) {#add-java.lang.Object-}
```
public abstract void add(Object value)
```


Vytvoří [IChartDataCell](../../com.aspose.slides/ichartdatacell) ze zadané hodnoty a přidá jej do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.Object | Hodnota.

--------------------

Tato metoda přidá list s názvem AUTO_DATA a přidá všechny hodnoty tam. Pokud používáte [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) k přidání nebo úpravě hodnot buňky, ujistěte se, že tento list nepoužíváte. Maximální počet hodnot přidaných touto metodou nesmí překročit 16711680 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Odstraní buňku z kolekce podle indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index buňky, která má být odstraněna. |

### getCount() {#getCount--}
```
public abstract int getCount()
```


Získá počet buněk v kolekci. Pouze pro čtení int.

**Vrací:**
int