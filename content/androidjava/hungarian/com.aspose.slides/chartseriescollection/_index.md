---
title: ChartSeriesCollection
second_title: Aspose.Slides Android Java API hivatkozás
description: Gyűjteményt képvisel
type: docs
url: /hu/com.aspose.slides/chartseriescollection/
---
**Öröklés:**  
java.lang.Object, com.aspose.slides.DomObject

**Minden megvalósított interfész:**  
[com.aspose.slides.IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)  
```
public class ChartSeriesCollection extends DomObject<ChartData> implements IChartSeriesCollection
```

A [ChartSeries](../../com.aspose.slides/chartseries) gyűjteményét képviseli
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | A megadott indexű elemet adja vissza. |
| [size()](#size--) | A gyűjteményben lévő objektumok számát adja vissza. |
| [add(int type)](#add-int-) | Új diagram sorozatot hoz létre és hozzáadja a gyűjteményhez. |
| [insert(int index, int type)](#insert-int-int-) | Új diagram sorozatot hoz létre és beszúrja a gyűjteménybe. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | Új diagram sorozatot hoz létre a(z) [ChartDataCell](../../com.aspose.slides/chartdatacell) alapján és hozzáadja a gyűjteményhez. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | Új diagram sorozatot hoz létre a(z) [ChartCellCollection](../../com.aspose.slides/chartcellcollection) alapján és hozzáadja a gyűjteményhez. |
| [add(String name, int type)](#add-java.lang.String-int-) | Új diagram sorozatot hoz létre az értékből és hozzáadja a gyűjteményhez. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | A megadott [ChartSeries](../../com.aspose.slides/chartseries) keresése és a teljes gyűjteményben található első előfordulás nulla alapú indexének visszaadása |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | A megadott érték eltávolítása. |
| [removeAt(int index)](#removeAt-int-) | Az adott pozícióban tárolt ActiveX vezérlő eltávolítása a gyűjteményből. |
| [clear()](#clear--) | Az összes vezérlő eltávolítása a gyűjteményből. |
| [iterator()](#iterator--) | Egy enumerátor visszaadása, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Egy Java iterátor visszaadása az egész gyűjteményhez. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | A teljes gyűjtemény másolása a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Egy érték visszaadása, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos)-e. |
| [getSyncRoot()](#getSyncRoot--) | Szinkronizációs gyökér visszaadása. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

A megadott indexű elemet adja vissza.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[IChartSeries](../../com.aspose.slides/ichartseries) - A megadott indexű elem.

### size() {#size--}
```
public final int size()
```

A gyűjteményben lévő objektumok számát adja vissza. Csak olvasható int.

**Visszatérési érték:**
int

### add(int type) {#add-int-}
```
public final IChartSeries add(int type)
```

Új diagram sorozatot hoz létre és hozzáadja a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | int | A sorozat típusa |

**Visszatérési érték:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Új diagram sorozat.

### insert(int index, int type) {#insert-int-int-}
```
public final IChartSeries insert(int index, int type)
```

Új diagram sorozatot hoz létre és beszúrja a gyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |
| type | int | A sorozat típusa |

**Visszatérési érték:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public final IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

Új diagram sorozatot hoz létre a(z) [ChartDataCell](../../com.aspose.slides/chartdatacell) alapján és hozzáadja a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Az a cella, amely a sorozat nevét tartalmazza. |
| type | int | A sorozat típusának beállítása |

--------------------
Ha a diagram sorozat már létező cellából származik a gyűjteményben, akkor a metódus semmit sem ad hozzá és az indexét adja vissza.

**Visszatérési érték:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Hozzáadott diagram sorozat vagy a már a gyűjteményben lévő sorozat.

### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public final IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

Új diagram sorozatot hoz létre a(z) [ChartCellCollection](../../com.aspose.slides/chartcellcollection) alapján és hozzáadja a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | A cellák, amelyek a sorozat nevét tartalmazzák. |
| type | int | A sorozat típusának beállítása |

--------------------
Ha a diagram sorozat már létező cellából származik a gyűjteményben, akkor a metódus semmit sem ad hozzá és az indexét adja vissza.

**Visszatérési érték:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Hozzáadott diagram sorozat vagy a már a gyűjteményben lévő sorozat.

### add(String name, int type) {#add-java.lang.String-int-}
```
public final IChartSeries add(String name, int type)
```

Új diagram sorozatot hoz létre az értékből és hozzáadja a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A sorozat neve. |
| type | int | A sorozat típusának beállítása |

**Visszatérési érték:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Hozzáadott diagram sorozat.

### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public final int indexOf(IChartSeries value)
```

A megadott [ChartSeries](../../com.aspose.slides/chartseries) keresése és a teljes gyűjteményben található első előfordulás nulla alapú indexének visszaadása

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Diagram sorozat értéke. |

**Visszatérési érték:**
int - A megadott érték első előfordulásának nulla alapú indexe a teljes CollectionBase-ban, ha megtalálható; egyébként -1.

### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public final void remove(IChartSeries value)
```

A megadott érték eltávolítása.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Az érték. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Az adott pozícióban tárolt ActiveX vezérlő eltávolítása a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az eltávolítandó vezérlő indexe. |

### clear() {#clear--}
```
public final void clear()
```

Az összes vezérlő eltávolítása a gyűjteményből.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iterator()
```

Egy enumerátor visszaadása, amely végigiterál a gyűjteményen.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - A IGenericEnumerator, amely a gyűjteményen való iteráláshoz használható.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iteratorJava()
```

Egy Java iterátor visszaadása az egész gyűjteményhez.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - Egy java.util.Iterator az egész gyűjteményhez.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

A teljes gyűjtemény másolása a megadott tömbbe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cél tömb |
| index | int | Az index a cél tömbben. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Egy érték visszaadása, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos)-e. Csak olvasható boolean.

**Visszatérési érték:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Szinkronizációs gyökér visszaadása. Csak olvasható Object.

**Visszatérési érték:**
java.lang.Object