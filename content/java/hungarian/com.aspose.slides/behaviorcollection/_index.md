---
title: BehaviorCollection
second_title: Aspose.Slides Java API Referenciája
description: A viselkedési hatások gyűjteményét képviseli.
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

A viselkedési hatások gyűjteményét képviseli.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getCount()](#getCount--) | Visszaadja a viselkedések számát a gyűjteményben. |
| [isReadOnly()](#isReadOnly--) | Lekér egy értéket, amely jelzi, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) csak olvasható-e. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | Új viselkedést ad hozzá a gyűjteményhez. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | Megállapítja egy adott elem indexét a Listában. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | Új viselkedést szúr be a gyűjteménybe a megadott indexen. |
| [copyTo(IBehavior[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehavior---int-) | A [IGenericCollection](../../com.aspose.slides/igenericcollection) elemeit egy tömbbe másolja, egy adott tömbindexnél kezdve. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | Eltávolítja a megadott viselkedést a gyűjteményből. |
| [removeAt(int index)](#removeAt-int-) | Eltávolít egy viselkedést a gyűjteményből a megadott indexen. |
| [clear()](#clear--) | Eltávolítja az összes viselkedést a gyűjteményből. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | Megállapítja, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) tartalmaz-e egy adott értéket. |
| [get_Item(int index)](#get-Item-int-) | Visszaad egy viselkedést a megadott indexen. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | Beállít egy viselkedést a megadott indexen. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort a teljes gyűjteményhez. |
### getCount() {#getCount--}
```
public final int getCount()
```

Visszaadja a viselkedések számát a gyűjteményben. Csak olvasható int.

**Visszatér:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Lekér egy értéket, amely jelzi, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) csak olvasható-e. Csak olvasható boolean.

**Visszatér:**
boolean - igaz, ha a [IGenericCollection](../../com.aspose.slides/igenericcollection) csak olvasható; egyébként hamis.
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public final void add(IBehavior item)
```

Új viselkedést ad hozzá a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Hozzáadandó viselkedés. |
### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public final int indexOf(IBehavior item)
```

Megállapítja egy adott elem indexét a Listában.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Az objektum, amelyet a Listában keres. |

**Visszatér:**
int - Az elem indexe, ha megtalálható a listában; egyébként -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public final void insert(int index, IBehavior item)
```

Új viselkedést szúr be a gyűjteménybe a megadott indexen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az index, ahol az új viselkedést be kell illeszteni. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | A beszúrandó viselkedés. |
### copyTo(IBehavior[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehavior---int-}
```
public final void copyTo(IBehavior[] array, int arrayIndex)
```

A [IGenericCollection](../../com.aspose.slides/igenericcollection) elemeit egy tömbbe másolja, egy adott tömbindexnél kezdve.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | [IBehavior\[\]](../../com.aspose.slides/ibehavior) | Az egydimenziós tömb, amely a [IGenericCollection](../../com.aspose.slides/igenericcollection) elemeinek másolásának célja. A tömbnek nullára indexeltnek kell lennie. |
| arrayIndex | int | A nullára indexelt kezdőindex a tömbben, ahol a másolás kezdődik. |
### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public final boolean remove(IBehavior item)
```

Eltávolítja a megadott viselkedést a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Az eltávolítandó viselkedés. |

**Visszatér:**
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Eltávolít egy viselkedést a gyűjteményből a megadott indexen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az eltávolítandó viselkedés indexe. |
### clear() {#clear--}
```
public final void clear()
```

Eltávolítja az összes viselkedést a gyűjteményből.
### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public final boolean contains(IBehavior item)
```

Megállapítja, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) tartalmaz-e egy adott értéket.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Az objektum, amelyet a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ben keres. |

**Visszatér:**
boolean - igaz, ha az elem megtalálható a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ben; egyébként hamis.
### get_Item(int index) {#get-Item-int-}
```
public final IBehavior get_Item(int index)
```

Visszaad egy viselkedést a megadott indexen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A visszaadandó viselkedés indexe. |

**Visszatér:**
[IBehavior](../../com.aspose.slides/ibehavior) - Animációs viselkedés.
### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public final void set_Item(int index, IBehavior value)
```

Beállít egy viselkedést a megadott indexen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A visszaadandó viselkedés indexe. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iterator()
```

Visszaad egy enumerátort, amely végigiterál a gyűjteményen.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - egy IGenericEnumerator, amely a gyűjteményen való iteráláshoz használható.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iteratorJava()
```

Visszaad egy java iterátort a teljes gyűjteményhez.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - egy java.util.Iterator a teljes gyűjteményhez.