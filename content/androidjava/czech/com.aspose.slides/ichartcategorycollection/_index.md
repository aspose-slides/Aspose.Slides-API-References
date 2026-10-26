---
title: IChartCategoryCollection
second_title: Aspose.Slides pro Android přes Java API Reference
description: Reprezentuje kolekci
type: docs
url: /cs/com.aspose.slides/ichartcategorycollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IChartCategoryCollection extends IGenericCollection<IChartCategory>
```

Represents collection of [IChartCategory](../../com.aspose.slides/ichartcategory)
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Získá prvek na zadaném indexu. |
| [getUseCells()](#getUseCells--) | Pokud je true, pak se pracovní list používá pro ukládání kategorií (tento případ podporuje vícestupňové kategorie). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | Pokud je true, pak se pracovní list používá pro ukládání kategorií (tento případ podporuje vícestupňové kategorie). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | Vrací počet úrovní seskupování kategorií. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Pokud kategorie existuje v kolekci, vrátí ji. |
| [add(Object value)](#add-java.lang.Object-) | Vytvoří nový [IChartCategory](../../com.aspose.slides/ichartcategory) z hodnoty a přidá jej do kolekce. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | Vyhledá zadaný [IChartCategory](../../com.aspose.slides/ichartcategory) a vrátí nulovým index první výskyt v celé kolekci. |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | Odstraní zadanou hodnotu. |
| [removeAt(int index)](#removeAt-int-) | Odstraní prvek na zadaném indexu. |
| [clear()](#clear--) | Odstraní všechny prvky z kolekce. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartCategory get_Item(int index)
```


Získá prvek na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Návratová hodnota:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Prvek na zadaném indexu.
### getUseCells() {#getUseCells--}
```
public abstract boolean getUseCells()
```


Pokud je true, pak se pracovní list používá pro ukládání kategorií (tento případ podporuje vícestupňové kategorie). Pokud je false, pak se pracovní list NEpoužívá pro ukládání hodnot (a tento případ nepodporuje vícestupňové kategorie). Čtení/zápis boolean.

**Návratová hodnota:**
boolean
### setUseCells(boolean value) {#setUseCells-boolean-}
```
public abstract void setUseCells(boolean value)
```


Pokud je true, pak se pracovní list používá pro ukládání kategorií (tento případ podporuje vícestupňové kategorie). Pokud je false, pak se pracovní list NEpoužívá pro ukládání hodnot (a tento případ nepodporuje vícestupňové kategorie). Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public abstract int getGroupingLevelCount()
```


Vrací počet úrovní seskupování kategorií. Je více než jedna pro víceúrovňové kategorie. Pouze pro čtení int.

**Návratová hodnota:**
int
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract IChartCategory add(IChartDataCell chartDataCell)
```


Pokud kategorie existuje v kolekci, vrátí ji. Jinak vytvoří novou kategorii grafu z [IChartDataCell](../../com.aspose.slides/ichartdatacell) a přidá ji do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Buňka použitá k vytvoření kategorie grafu. |

**Návratová hodnota:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Přidaná nebo existující kategorie.
### add(Object value) {#add-java.lang.Object-}
```
public abstract IChartCategory add(Object value)
```


Vytvoří nový [IChartCategory](../../com.aspose.slides/ichartcategory) z hodnoty a přidá jej do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.Object | Hodnota.

--------------------

Tato metoda přidá pracovní list s názvem AUTO_DATA a přidá do něj všechny hodnoty. Pokud používáte [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) k přidání nebo úpravě hodnot buněk, ujistěte se, že tento pracovní list nepoužíváte. Maximální počet hodnot přidaných touto metodou nesmí překročit 16711680

**Návratová hodnota:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Přidáno [IChartCategory](../../com.aspose.slides/ichartcategory).
### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public abstract int indexOf(IChartCategory value)
```


Vyhledá zadaný [IChartCategory](../../com.aspose.slides/ichartcategory) a vrátí nulovým index první výskyt v celé kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Kategorie grafu. |

**Návratová hodnota:**
int - Nulový index první výskyt hodnoty v celé CollectionBase, pokud je nalezena; jinak -1.
### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public abstract void remove(IChartCategory value)
```


Odstraní zadanou hodnotu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Hodnota. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Odstraní prvek na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index kategorie k odstranění. |

### clear() {#clear--}
```
public abstract void clear()
```


Odstraní všechny prvky z kolekce.