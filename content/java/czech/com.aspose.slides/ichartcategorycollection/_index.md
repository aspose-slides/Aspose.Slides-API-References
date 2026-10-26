---
title: IChartCategoryCollection
second_title: Aspose.Slides pro Java – reference API
description: Reprezentuje kolekci
type: docs
url: /cs/com.aspose.slides/ichartcategorycollection/
---
**Všechna implementovaná rozhraní:**
com.aspose.slides.IGenericCollection
```
public interface IChartCategoryCollection extends IGenericCollection<IChartCategory>
```

Reprezentuje kolekci [IChartCategory](../../com.aspose.slides/ichartcategory)
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Vrací prvek na zadaném indexu. |
| [getUseCells()](#getUseCells--) | Pokud je true, pak se list používá k ukládání kategorií (tento případ podporuje víceúrovňové kategorie). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | Pokud je true, pak se list používá k ukládání kategorií (tento případ podporuje víceúrovňové kategorie). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | Vrací počet úrovní seskupování kategorií, které jsou použity. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Pokud kategorie existuje v kolekci, vrátí ji. |
| [add(Object value)](#add-java.lang.Object-) | Vytvoří nový [IChartCategory](../../com.aspose.slides/ichartcategory) z hodnoty a přidá jej do kolekce. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | Vyhledá zadaný [IChartCategory](../../com.aspose.slides/ichartcategory) a vrátí nulový index první výskytu v celé kolekci |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | Odstraní zadanou hodnotu. |
| [removeAt(int index)](#removeAt-int-) | Odstraní prvek na zadaném indexu. |
| [clear()](#clear--) | Odstraní všechny prvky z kolekce. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartCategory get_Item(int index)
```

Vrací prvek na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Návratová hodnota:**
[IChartCategory](../../com.aspose.slides/ichartcategory) – Prvek na zadaném indexu.
### getUseCells() {#getUseCells--}
```
public abstract boolean getUseCells()
```

Pokud je true, pak se list používá k ukládání kategorií (tento případ podporuje víceúrovňové kategorie). Pokud je false, pak se list NEpoužívá k ukládání hodnot (a tento případ nepodporuje víceúrovňové kategorie). Čtení/zápis boolean.

**Návratová hodnota:**
boolean
### setUseCells(boolean value) {#setUseCells-boolean-}
```
public abstract void setUseCells(boolean value)
```

Pokud je true, pak se list používá k ukládání kategorií (tento případ podporuje víceúrovňové kategorie). Pokud je false, pak se list NEpoužívá k ukládání hodnot (a tento případ nepodporuje víceúrovňové kategorie). Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public abstract int getGroupingLevelCount()
```

Vrací počet úrovní seskupování kategorií, které jsou použity. Je vyšší než jedna pro víceúrovňové kategorie. Pouze pro čtení int.

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
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Buňka použita k vytvoření kategorie grafu. |

**Návratová hodnota:**
[IChartCategory](../../com.aspose.slides/ichartcategory) – Přidaná nebo existující kategorie.
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

Tato metoda přidá sešit s názvem AUTO_DATA a přidá do něj všechny hodnoty. Pokud používáte [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) k přidávání nebo úpravě hodnot buněk, ujistěte se, že tento sešit nepoužijete. Maximální počet hodnot přidaných pomocí této metody nesmí překročit 16711680

**Návratová hodnota:**
[IChartCategory](../../com.aspose.slides/ichartcategory) – Přidáno [IChartCategory](../../com.aspose.slides/ichartcategory).
### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public abstract int indexOf(IChartCategory value)
```

Vyhledá zadaný [IChartCategory](../../com.aspose.slides/ichartcategory) a vrátí nulový index první výskytu v celé kolekci

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Kategorie grafu. |

**Návratová hodnota:**
int – Nulový index první výskytu hodnoty v celé CollectionBase, pokud je nalezen; jinak -1.
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