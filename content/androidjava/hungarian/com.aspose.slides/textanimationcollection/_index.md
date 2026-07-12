---
title: TextAnimationCollection
second_title: Aspose.Slides Android számára Java API hivatkozáson keresztül
description: A szöveganimációk gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/textanimationcollection/
---
**Öröklés:**
java.lang.Object

**Az összes megvalósított interfész:**
[com.aspose.slides.ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)
```
public class TextAnimationCollection implements ITextAnimationCollection
```

A szöveganimációk gyűjteményét képviseli.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [TextAnimationCollection()](#TextAnimationCollection--) |  |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [size()](#size--) | Visszaadja a gyűjtemény elemeinek számát. |
| [add()](#add--) | Új szöveganimációt ad a gyűjteményhez. |
| [get_Item(int index)](#get-Item-int-) | Visszaad egy elemet index alapján. |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | Visszaadja az összes elemet |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort a teljes gyűjteményhez. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Átmásolja a gyűjtemény összes elemét a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált-e (szálbiztos). |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy szinkronizációs gyökeret. |
### TextAnimationCollection() {#TextAnimationCollection--}
```
public TextAnimationCollection()
```


### size() {#size--}
```
public final int size()
```


Visszaadja a gyűjtemény elemeinek számát. Csak olvasható int.

**Visszatér:**
int
### add() {#add--}
```
public final TextAnimation add()
```


Új szöveganimációt ad a gyűjteményhez.

**Visszatér:**
[TextAnimation](../../com.aspose.slides/textanimation) - Hozzáadott [TextAnimation](../../com.aspose.slides/textanimation)
### get_Item(int index) {#get-Item-int-}
```
public final ITextAnimation get_Item(int index)
```


Visszaad egy elemet index alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatér:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### get_Item(IShape shape) {#get-Item-com.aspose.slides.IShape-}
```
public final ITextAnimation[] get_Item(IShape shape)
```


Visszaadja az összes elemet

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) eltávolítandó. |

**Visszatér:**
com.aspose.slides.ITextAnimation[] - Tömb a [ITextAnimation](../../com.aspose.slides/itextanimation)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITextAnimation> iterator()
```


Visszaad egy enumerátort, amely végigiterál a gyűjteményen.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITextAnimation> - Egy IGenericEnumerator, amely a gyűjteményen való iterálásra használható.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITextAnimation> iteratorJava()
```


Visszaad egy java iterátort a teljes gyűjteményhez.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITextAnimation> - Egy java.util.Iterator a teljes gyűjteményhez.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Átmásolja a gyűjtemény összes elemét a megadott tömbbe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Kitöltendő tömb. |
| index | int | Kezdeti pozíció a cél tömbben. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált-e (szálbiztos). Csak olvasható boolean.

**Visszatér:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Visszaad egy szinkronizációs gyökeret. Csak olvasható Object.

**Visszatér:**
java.lang.Object