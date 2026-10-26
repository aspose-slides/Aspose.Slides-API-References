---
title: ChartCategoryCollection
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje kolekci
type: docs
url: /cs/com.aspose.slides/chartcategorycollection/
---
**Dědičnost:**
java.lang.Object, com.aspose.slides.DomObject

**Všechny implementované rozhraní:**
[com.aspose.slides.IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
```
public class ChartCategoryCollection extends DomObject<ChartData> implements IChartCategoryCollection
```

Reprezentuje kolekci [ChartCategory](../../com.aspose.slides/chartcategory)
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Vrací prvek na daném indexu. |
| [getUseCells()](#getUseCells--) | Pokud je true, pak se list používá k ukládání kategorií (tento případ podporuje víceúrovňové kategorie). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | Pokud je true, pak se list používá k ukládání kategorií (tento případ podporuje víceúrovňové kategorie). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | Vrací počet úrovní seskupování kategorií, které jsou použity. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Pokud kategorie v kolekci existuje, vrátí ji. |
| [add(Object value)](#add-java.lang.Object-) | Vytvoří novou [ChartCategory](../../com.aspose.slides/chartcategory) z hodnoty a přidá ji do kolekce. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | Vyhledá zadaný [ChartCategory](../../com.aspose.slides/chartcategory) a vrátí nulový index prvního výskytu v celé Collection. |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | Odstraní zadanou hodnotu. |
| [removeAt(int index)](#removeAt-int-) | Odstraní prvek na zadaném indexu. |
| [clear()](#clear--) | Odstraní všechny prvky z kolekce. |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází kolekcí. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterator pro celou kolekci. |
| [size()](#size--) | Vrací počet prvků v kolekci. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Zkopíruje všechny prvky kolekce do zadaného pole. |
| [isSynchronized()](#isSynchronized--) | Vrací hodnotu, která určuje, zda je přístup k Listu synchronizován (vláknově bezpečný). |
| [getSyncRoot()](#getSyncRoot--) | Vrací objekt, který lze použít k synchronizaci přístupu ke kolekci. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartCategory get_Item(int index)
```

Vrací prvek na daném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Návratová hodnota:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Prvek na daném indexu.
### getUseCells() {#getUseCells--}
```
public final boolean getUseCells()
```

Pokud je true, pak se list používá k ukládání kategorií (tento případ podporuje víceúrovňové kategorie). Pokud je false, pak se list NEpoužívá k ukládání hodnot (a tento případ nepodporuje víceúrovňové kategorie). Čtení/zápis boolean.

**Návratová hodnota:**
boolean
### setUseCells(boolean value) {#setUseCells-boolean-}
```
public final void setUseCells(boolean value)
```

Pokud je true, pak se list používá k ukládání kategorií (tento případ podporuje víceúrovňové kategorie). Pokud je false, pak se list NEpoužívá k ukládání hodnot (a tento případ nepodporuje víceúrovňové kategorie). Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public final int getGroupingLevelCount()
```

Vrací počet úrovní seskupování kategorií, které jsou použity. Je více než jedna pro víceúrovňové kategorie. Pouze pro čtení int.

**Návratová hodnota:**
int
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public final IChartCategory add(IChartDataCell chartDataCell)
```

Pokud kategorie v kolekci existuje, vrátí ji. Jinak vytvoří novou kategorii grafu z [IChartDataCell](../../com.aspose.slides/ichartdatacell) a přidá ji do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Buňka použitá k vytvoření kategorie grafu. |

**Návratová hodnota:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Přidaná nebo existující kategorie.
### add(Object value) {#add-java.lang.Object-}
```
public final IChartCategory add(Object value)
```

Vytvoří novou [ChartCategory](../../com.aspose.slides/chartcategory) z hodnoty a přidá ji do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.Object | Hodnota.

--------------------

Tato metoda přidá list s názvem AUTO_DATA a přidá do něj všechny hodnoty. Pokud používáte [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) k přidání nebo úpravě hodnot buněk, ujistěte se, že tento list nepoužíváte. Maximální počet hodnot přidaných touto metodou nesmí překročit 16711680

**Návratová hodnota:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Přidáno [IChartCategory](../../com.aspose.slides/ichartcategory).
### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public final int indexOf(IChartCategory value)
```

Vyhledá zadaný [ChartCategory](../../com.aspose.slides/chartcategory) a vrátí nulový index prvního výskytu v celé Collection.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Kategorie grafu. |

**Návratová hodnota:**
int - Nulový index prvního výskytu hodnoty v celé CollectionBase, pokud je nalezena; jinak -1.
### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public final void remove(IChartCategory value)
```

Odstraní zadanou hodnotu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Hodnota. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Odstraní prvek na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index kategorie, která se má odstranit. |
### clear() {#clear--}
```
public final void clear()
```

Odstraní všechny prvky z kolekce.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iterator()
```

Vrací enumerátor, který prochází kolekcí.

**Návratová hodnota:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - IGenericEnumerator, který lze použít k iteraci přes kolekci.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iteratorJava()
```

Vrací java iterator pro celou kolekci.

**Návratová hodnota:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - java.util.Iterator pro celou kolekci.
### size() {#size--}
```
public final int size()
```

Vrací počet prvků v kolekci. Pouze pro čtení int.

**Návratová hodnota:**
int
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Zkopíruje všechny prvky kolekce do zadaného pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cílové pole. |
| index | int | Počáteční index v poli. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Vrací hodnotu, která určuje, zda je přístup k Listu synchronizován (vláknově bezpečný). Pouze pro čtení boolean.

**Návratová hodnota:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Vrací objekt, který lze použít k synchronizaci přístupu ke kolekci. Pouze pro čtení Object.

Vrací synchronizační kořen. Pouze pro čtení Object.

**Návratová hodnota:**
java.lang.Object