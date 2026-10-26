---
title: TrendlineCollection
second_title: Aspose.Slides Android számára Java API hivatkozás
description: Trendline gyűjteményt ábrázol
type: docs
url: /hu/com.aspose.slides/trendlinecollection/
---
**Öröklődés:**
java.lang.Object, com.aspose.slides.DomObject

**Minden megvalósított interfész:**
[com.aspose.slides.ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
```
public class TrendlineCollection extends DomObject<ChartSeries> implements ITrendlineCollection
```

A Trendline gyűjteményt ábrázolja
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lekéri az elemet a megadott indexen. |
| [add(int trendlineType)](#add-int-) | Új Trendline hozzáadása a gyűjtemény végéhez és visszaadja. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | Eltávolítja a megadott értéket. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort a teljes gyűjteményhez. |
| [getCount()](#getCount--) | Lekéri a gyűjteményben ténylegesen található elemek számát. |
### get_Item(int index) {#get-Item-int-}
```
public final ITrendline get_Item(int index)
```

Lekéri az elemet a megadott indexen. Csak olvasható [Trendline](../../com.aspose.slides/trendline).

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

Új Trendline hozzáadása a gyűjtemény végéhez és visszaadja.

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
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - Egy IGenericEnumerator, amely a gyűjteményen való iteráláshoz használható.
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

Lekéri a gyűjteményben ténylegesen található elemek számát. Csak olvasható int.

**Visszatérési érték:**
int