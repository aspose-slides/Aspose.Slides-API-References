---
title: BehaviorCollection
second_title: Aspose.Slides Androidra a Java API hivatkozás
description: Viselkedés hatásokat tartalmazó gyűjteményt képvisel.
type: docs
url: /hu/com.aspose.slides/behaviorcollection/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
```
public class BehaviorCollection implements IBehaviorCollection
```

Viselkedés hatásokat tartalmazó gyűjteményt képvisel.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getCount()](#getCount--) | Visszaadja a viselkedések számát egy gyűjteményben. |
| [isReadOnly()](#isReadOnly--) | Lekér egy értéket, amely azt jelzi, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) csak olvasható-e. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | Új viselkedést ad a gyűjteményhez. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | Meghatározza egy adott elem indexét a Listában. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | Új viselkedést szúr be a gyűjteménybe a megadott indexnél. |
| [copyTo(IBehavior[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehavior---int-) | Átmásolja a [IGenericCollection](../../com.aspose.slides/igenericcollection) elemeit egy tömbbe, egy adott tömbindexnél kezdve. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | Eltávolítja a megadott viselkedést egy gyűjteményből. |
| [removeAt(int index)](#removeAt-int-) | Eltávolít egy viselkedést a gyűjteményből a megadott indexnél. |
| [clear()](#clear--) | Eltávolítja az összes viselkedést egy gyűjteményből. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | Megállapítja, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) tartalmaz-e egy adott értéket. |
| [get_Item(int index)](#get-Item-int-) | Visszaad egy viselkedést a megadott indexnél. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | Beállít egy viselkedést a megadott indexnél. |
| [iterator()](#iterator--) | Visszaad egy felsorolót, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy Java iterátort az egész gyűjteményhez. |
### getCount() {#getCount--}
```
public final int getCount()
```


Visszaadja a viselkedések számát egy gyűjteményben. Csak olvasható int.

**Visszatérési érték:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Lekér egy értéket, amely azt jelzi, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) csak olvasható-e. Csak olvasható boolean.

**Visszatérési érték:**
boolean - true, ha a [IGenericCollection](../../com.aspose.slides/igenericcollection) csak olvasható; egyébként false.
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public final void add(IBehavior item)
```


Új viselkedést ad a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Hozzáadandó viselkedés. |

### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public final int indexOf(IBehavior item)
```


Meghatározza egy adott elem indexét a Listában.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | A Listában keresendő objektum. |

**Visszatérési érték:**
int - Az elem indexe, ha megtalálható a listában; egyébként -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public final void insert(int index, IBehavior item)
```


Új viselkedést szúr be a gyűjteménybe a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az index, ahol az új viselkedést be kell szúrni. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | A beszúrandó viselkedés. |

### copyTo(IBehavior[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehavior---int-}
```
public final void copyTo(IBehavior[] array, int arrayIndex)
```


Átmásolja a [IGenericCollection](../../com.aspose.slides/igenericcollection) elemeit egy tömbbe, egy adott tömbindexnél kezdve.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | [IBehavior\[\]](../../com.aspose.slides/ibehavior) | Az egy dimenziós tömb, amely a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ból átmásolt elemek célja. A tömbnek nullával kezdődő indexelése van. |
| arrayIndex | int | A tömb nulláralapú indexe, ahol a másolás kezdődik. |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public final boolean remove(IBehavior item)
```


Eltávolítja a megadott viselkedést egy gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Eltávolítandó viselkedés. |

**Visszatérési érték:**
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Eltávolít egy viselkedést a gyűjteményből a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A eltávolítandó viselkedés indexe. |

### clear() {#clear--}
```
public final void clear()
```


Eltávolítja az összes viselkedést egy gyűjteményből.

### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public final boolean contains(IBehavior item)
```


Megállapítja, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) tartalmaz-e egy adott értéket.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | A [IGenericCollection](../../com.aspose.slides/igenericcollection)-ban keresendő objektum. |

**Visszatérési érték:**
boolean - true, ha az elem megtalálható a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ban; egyébként false.
### get_Item(int index) {#get-Item-int-}
```
public final IBehavior get_Item(int index)
```


Visszaad egy viselkedést a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A visszaadandó viselkedés indexe. |

**Visszatérési érték:**
[IBehavior](../../com.aspose.slides/ibehavior) - Animációs viselkedés.
### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public final void set_Item(int index, IBehavior value)
```


Beállít egy viselkedést a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A visszaadandó viselkedés indexe. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iterator()
```


Visszaad egy felsorolót, amely végigiterál a gyűjteményen.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - A IGenericEnumerator, amelyet a gyűjtemény bejárásához lehet használni.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iteratorJava()
```


Visszaad egy Java iterátort az egész gyűjteményhez.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - Egy java.util.Iterator az egész gyűjteményhez.