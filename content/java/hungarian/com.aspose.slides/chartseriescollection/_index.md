---
title: ChartSeriesCollection
second_title: Aspose.Slides for Java API referenciája
description: Gyűjteményt képvisel
type: docs
url: /hu/com.aspose.slides/chartseriescollection/
---
**Öröklés:**
java.lang.Object, com.aspose.slides.DomObject

**Az összes megvalósított interfész:**
[com.aspose.slides.IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
```
public class ChartSeriesCollection extends DomObject<ChartData> implements IChartSeriesCollection
```

A(z) [ChartSeries](../../com.aspose.slides/chartseries) gyűjteménye.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lekéri a megadott indexű elemet. |
| [size()](#size--) | Visszatér a gyűjteményben lévő objektumok számával. |
| [add(int type)](#add-int-) | Új diagram sorozatot hoz létre és hozzáadja a gyűjteményhez. |
| [insert(int index, int type)](#insert-int-int-) | Új diagram sorozatot hoz létre és beszúrja a gyűjteménybe. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | Új diagram sorozatot hoz létre a(z) [ChartDataCell](../../com.aspose.slides/chartdatacell) alapján és hozzáadja a gyűjteményhez. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | Új diagram sorozatot hoz létre a(z) [ChartCellCollection](../../com.aspose.slides/chartcellcollection) alapján és hozzáadja a gyűjteményhez. |
| [add(String name, int type)](#add-java.lang.String-int-) | Új diagram sorozatot hoz létre az érték alapján és hozzáadja a gyűjteményhez. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | Keres a megadott [ChartSeries](../../com.aspose.slides/chartseries) után, és visszaadja a nullától kezdődő indexet az első előforduláshoz az egész Gyűjteményben. |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | Eltávolítja a megadott értéket. |
| [removeAt(int index)](#removeAt-int-) | Eltávolít egy megadott pozícióban tárolt ActiveX vezérlőt a gyűjteményből. |
| [clear()](#clear--) | Eltávolítja az összes vezérlőt a gyűjteményből. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort az egész gyűjteményhez. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Átmásolja a teljes gyűjteményt a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Visszaad egy értéket, amely jelzi, hogy a gyűjtemény elérése szinkronizált (szálbiztos)-e. |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy szinkronizációs gyökér objektumot. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```


Lekéri a megadott indexű elemet.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatér:**
[IChartSeries](../../com.aspose.slides/ichartseries) – A megadott indexű elem.
### size() {#size--}
```
public final int size()
```


Visszatér a gyűjteményben lévő objektumok számával. Csak olvasható int.

**Visszatér:**
int
### add(int type) {#add-int-}
```
public final IChartSeries add(int type)
```


Új diagram sorozatot hoz létre és hozzáadja a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | int | Sorozat típusa |

**Visszatér:**
[IChartSeries](../../com.aspose.slides/ichartseries) – Új diagram sorozat.
### insert(int index, int type) {#insert-int-int-}
```
public final IChartSeries insert(int index, int type)
```


Új diagram sorozatot hoz létre és beszúrja a gyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |
| type | int |  |

**Visszatér:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public final IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```


Új diagram sorozatot hoz létre a(z) [ChartDataCell](../../com.aspose.slides/chartdatacell) alapján és hozzáadja a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | A sorozat nevet tartalmazó cella. |
| type | int | Sorozat típusát beállító típus

--------------------

Ha a diagram sorozat már létezik a gyűjteményben ugyanabból a cellából, a metódus nem ad hozzá semmit, és visszaadja annak indexét. |

**Visszatér:**
[IChartSeries](../../com.aspose.slides/ichartseries) – Hozzáadott diagram sorozat vagy a már létező sorozat.
### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public final IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```


Új diagram sorozatot hoz létre a(z) [ChartCellCollection](../../com.aspose.slides/chartcellcollection) alapján és hozzáadja a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | A sorozat nevet tartalmazó cellák. |
| type | int | Sorozat típusát beállító típus

--------------------

Ha a diagram sorozat már létezik a gyűjteményben ugyanabból a cellából, a metódus nem ad hozzá semmit, és visszaadja annak indexét. |

**Visszatér:**
[IChartSeries](../../com.aspose.slides/ichartseries) – Hozzáadott diagram sorozat vagy a már létező sorozat.
### add(String name, int type) {#add-java.lang.String-int-}
```
public final IChartSeries add(String name, int type)
```


Új diagram sorozatot hoz létre az érték alapján és hozzáadja a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | Sorozat neve. |
| type | int | Sorozat típusát beállító típus |

**Visszatér:**
[IChartSeries](../../com.aspose.slides/ichartseries) – Hozzáadott diagram sorozat.
### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public final int indexOf(IChartSeries value)
```


Keres a megadott [ChartSeries](../../com.aspose.slides/chartseries) után, és visszaadja a nullától kezdődő indexet az első előforduláshoz az egész Gyűjteményben.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Diagram sorozat értéke. |

**Visszatér:**
int – A nullától kezdődő index az első előforduláshoz, ha megtalálható; egyébként -1.
### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public final void remove(IChartSeries value)
```


Eltávolítja a megadott értéket.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Az érték. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Eltávolít egy megadott pozícióban tárolt ActiveX vezérlőt a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A eltávolítandó vezérlő indexe. |

### clear() {#clear--}
```
public final void clear()
```


Eltávolítja az összes vezérlőt a gyűjteményből.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iterator()
```


Visszaad egy enumerátort, amely végigiterál a gyűjteményen.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> – Egy IGenericEnumerator, amelyet a gyűjtemény bejárására használhat.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iteratorJava()
```


Visszaad egy java iterátort az egész gyűjteményhez.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> – Egy java.util.Iterator az egész gyűjteményhez.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Átmásolja a teljes gyűjteményt a megadott tömbbe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cél tömb |
| index | int | Index a cél tömbben. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Visszaad egy értéket, amely jelzi, hogy a gyűjtemény elérése szinkronizált (szálbiztos)-e. Csak olvasható boolean.

**Visszatér:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Visszaad egy szinkronizációs gyökér objektumot. Csak olvasható Object.

**Visszatér:**
java.lang.Object