---
title: TrendlineCollection
second_title: Aspose.Slides Java API hivatkozás
description: Trendline gyűjteményét képviseli
type: docs
url: /hu/com.aspose.slides/trendlinecollection/
---
**Öröklés:**
java.lang.Object, com.aspose.slides.DomObject

**Minden megvalósított interfész:**
[com.aspose.slides.ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
```
public class TrendlineCollection extends DomObject<ChartSeries> implements ITrendlineCollection
```

Egy Trendline gyűjteményt reprezentál
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | A megadott indexű elemet adja vissza. |
| [add(int trendlineType)](#add-int-) | Új Trendline-t ad a gyűjtemény végéhez és visszaadja. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | Eltávolítja a megadott értéket. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort a teljes gyűjteményhez. |
| [getCount()](#getCount--) | A gyűjteményben ténylegesen tárolt elemek számát adja vissza. |
### get_Item(int index) {#get-Item-int-}
```
public final ITrendline get_Item(int index)
```


A megadott indexű elemet adja vissza. Csak olvasható [Trendline](../../com.aspose.slides/trendline).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[ITrendline](../../com.aspose.slides/itrendline)
### add(int trendlineType) {#add-int-}
```
public final ITrendline add(int trendlineType)
```


Új Trendline-t ad a gyűjtemény végéhez és visszaadja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| trendlineType | int |  |

**Visszatérési érték:**
[ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public final void remove(ITrendline value)
```


Eltávolítja a megadott értéket.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iterator()
```


Visszaad egy enumerátort, amely végigiterál a gyűjteményen.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - Egy IGenericEnumerator, amelyet a gyűjtemény végigiterálásához lehet használni.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iteratorJava()
```


Visszaad egy java iterátort a teljes gyűjteményhez.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - Egy java.util.Iterator a teljes gyűjteményhez.
### getCount() {#getCount--}
```
public final int getCount()
```


A gyűjteményben ténylegesen tárolt elemek számát adja vissza. Csak olvasható int.

**Visszatérési érték:**
int