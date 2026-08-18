---
title: RowCollection
second_title: Aspose.Slides Java API referencia
description: A táblázat sorgyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/rowcollection/
---
**Öröklés:**
java.lang.Object, com.aspose.slides.DomObject

**Minden megvalósított interfész:**
[com.aspose.slides.IRowCollection](../../com.aspose.slides/irowcollection)
```
public final class RowCollection extends DomObject<Table> implements IRowCollection
```

A táblázatsor-gyűjteményt képviseli.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [size()](#size--) | Lekéri a gyűjteményben ténylegesen lévő sorok számát. |
| [get_Item(int index)](#get-Item-int-) | Visszatér a megadott indexű sorral. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | Létrehozza a megadott sablon sor másolatát, és a táblázat aljára illeszti. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | Létrehozza a megadott sablon sor másolatát, és a megadott pozícióba illeszti a táblázatban. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Eltávolít egy sort a megadott pozícióból a táblázatból. |
| [iterator()](#iterator--) | Visszatér egy felsorolóval, amely bejárja a gyűjteményt. |
| [iteratorJava()](#iteratorJava--) | Visszatér egy java iterátorral a teljes gyűjteményhez. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Átmásolja a gyűjtemény összes elemét a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Visszatér egy értékkel, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált-e (szálbiztos). |
| [getSyncRoot()](#getSyncRoot--) | Visszatér egy szinkronizációs gyökkel. |
### size() {#size--}
```
public final int size()
```


Lekéri a gyűjteményben ténylegesen lévő sorok számát. **Csak olvasható** int.

**Visszatér:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IRow get_Item(int index)
```


Visszatér a megadott indexű sorral. **Csak olvasható** [Row](../../com.aspose.slides/row).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatér:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public final IRow[] addClone(IRow templ, boolean withAttachedRows)
```


Létrehozza a megadott sablon sor másolatát, és a táblázat aljára illeszti.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | Sor, amely sablonként szolgál. |
| withAttachedRows | boolean | Igaz, ha a sablon sorhoz csatolt összes sort is másolni szeretné. |

**Visszatér:**
com.aspose.slides.IRow[] - Hozzáadott sorok.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public final IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```


Létrehozza a megadott sablon sor másolatát, és a megadott pozícióba illeszti a táblázatban.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az új sor indexe. |
| templ | [IRow](../../com.aspose.slides/irow) | Sor, amely sablonként szolgál. |
| withAttachedRows | boolean | Igaz, ha a sablon sorhoz csatolt összes sort is másolni szeretné. |

**Visszatér:**
com.aspose.slides.IRow[] - Beszúrt sorok.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstRowIndex, boolean withAttachedRows)
```


Eltávolít egy sort a megadott pozícióból a táblázatból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| firstRowIndex | int | A törlendő sor indexe. |
| withAttachedRows | boolean | Igaz, ha a csatolt sorokat is törölni szeretné. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iterator()
```


Visszatér egy felsorolóval, amely bejárja a gyűjteményt.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRrow> - Egy IGenericEnumerator, amely használható a gyűjtemény bejárásához.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iteratorJava()
```


Visszatér egy java iterátorral a teljes gyűjteményhez.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRrow> - Egy java.util.Iterator a teljes gyűjteményhez.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Átmásolja a gyűjtemény összes elemét a megadott tömbbe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cél tömb. |
| index | int | Kezdő index a cél tömbben. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Visszatér egy értékkel, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált-e (szálbiztos). **Csak olvasható** boolean.

**Visszatér:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Visszatér egy szinkronizációs gyökkel. **Csak olvasható** Object.

**Visszatér:**
java.lang.Object