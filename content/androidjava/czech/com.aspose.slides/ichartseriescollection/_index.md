---
title: IChartSeriesCollection
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje kolekci
type: docs
url: /cs/com.aspose.slides/ichartseriescollection/
---
**Všechny implementované rozhraní:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesCollection extends IGenericCollection<IChartSeries>
```

Reprezentuje kolekci [IChartSeries](../../com.aspose.slides/ichartseries)
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Získá prvek na určeném indexu. |
| [add(int type)](#add-int-) | Vytvoří novou sérii grafu a přidá ji do kolekce. |
| [insert(int index, int type)](#insert-int-int-) | Vytvoří novou sérii grafu a vloží ji do kolekce. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | Vytvoří novou sérii grafu z [IChartDataCell](../../com.aspose.slides/ichartdatacell) a přidá ji do kolekce. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | Vytvoří novou sérii grafu z [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) a přidá ji do kolekce. |
| [add(String name, int type)](#add-java.lang.String-int-) | Vytvoří novou sérii grafu z hodnoty a přidá ji do kolekce. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | Vyhledá zadaný [IChartSeries](../../com.aspose.slides/ichartseries) a vrátí nulový index první výskytu v celé kolekci. |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | Odstraní zadanou hodnotu. |
| [removeAt(int index)](#removeAt-int-) | Odstraní prvek na určeném indexu |
| [clear()](#clear--) | Odstraní všechny prvky (včetně stylu grafu) z kolekce. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

Získá prvek na určeném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Návratová hodnota:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Prvek na určeném indexu.

### add(int type) {#add-int-}
```
public abstract IChartSeries add(int type)
```

Vytvoří novou sérii grafu a přidá ji do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| type | int | Typ řady |

**Návratová hodnota:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Nová série grafu.

### insert(int index, int type) {#insert-int-int-}
```
public abstract IChartSeries insert(int index, int type)
```

Vytvoří novou sérii grafu a vloží ji do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index pro vložení |
| type | int | Typ grafu [ChartType](../../com.aspose.slides/charttype) |

**Návratová hodnota:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Nová série grafu [IChartSeries](../../com.aspose.slides/ichartseries)

### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public abstract IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

Vytvoří novou sérii grafu z [IChartDataCell](../../com.aspose.slides/ichartdatacell) a přidá ji do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Buňka, která obsahuje název řady. |
| type | int | Typ nastavený pro řadu |

--------------------

Pokud je série grafu vytvořena ze stejné buňky, která již v kolekci existuje, metoda nic nepřidá a vrátí její index. |

**Návratová hodnota:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Přidaná série grafu nebo série, která již v kolekci je.

### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public abstract IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

Vytvoří novou sérii grafu z [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) a přidá ji do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | Buňky, které obsahují název řady. |
| type | int | Typ nastavený pro řadu |

--------------------

Pokud je série grafu vytvořena ze stejné buňky, která již v kolekci existuje, metoda nic nepřidá a vrátí její index. |

**Návratová hodnota:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Přidaná série grafu nebo série, která již v kolekci je.

### add(String name, int type) {#add-java.lang.String-int-}
```
public abstract IChartSeries add(String name, int type)
```

Vytvoří novou sérii grafu z hodnoty a přidá ji do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název série. |
| type | int | Typ nastavený pro řadu |

**Návratová hodnota:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Přidaná série grafu.

### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public abstract int indexOf(IChartSeries value)
```

Vyhledá zadaný [IChartSeries](../../com.aspose.slides/ichartseries) a vrátí nulový index první výskytu v celé Collection

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Hodnota série grafu. |

**Návratová hodnota:**
int - Nulový index první výskytu hodnoty v celé CollectionBase, pokud je nalezena; jinak -1.

### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public abstract void remove(IChartSeries value)
```

Odstraní zadanou hodnotu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Hodnota. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Odstraní prvek na určeném indexu

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index int |

### clear() {#clear--}
```
public abstract void clear()
```

Odstraní všechny prvky (včetně stylu grafu) z kolekce.