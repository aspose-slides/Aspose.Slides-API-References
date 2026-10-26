---
title: LayoutSlideCollection
second_title: Aspose.Slides for Java API Referenciája
description: Az elrendezési diák gyűjteményéhez tartozó alap osztályt képviseli.
type: docs
url: /hu/com.aspose.slides/layoutslidecollection/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection), com.aspose.slides.IDOMObject
```
public class LayoutSlideCollection implements ILayoutSlideCollection, IDOMObject
```

Az elrendezési diák gyűjteményéhez tartozó alap osztályt képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [size()](#size--) | Visszaadja a gyűjteményben lévő elrendezési diák számát. |
| [get_Item(int index)](#get-Item-int-) | Visszaadja az index szerinti elrendezési diát. |
| [getByType(byte type)](#getByType-byte-) | Visszaadja a megadott típusú első elrendezési diát. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Eltávolít egy elrendezést a gyűjteményből. |
| [removeUnused()](#removeUnused--) | Eltávolítja a használaton kívüli elrendezési diákot (azok a diák, amelyeknél a HasDependingSlides hamis). |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigjárja a gyűjteményt. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy Java iterátort a teljes gyűjteményhez. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Átmásolja a gyűjtemény összes elemét a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos)-e. |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy szinkronizációs gyökeret. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### size() {#size--}
```
public final int size()
```


Visszaadja a gyűjteményben lévő elrendezési diák számát. Csak olvasható int.

**Visszatér:**  
int
### get_Item(int index) {#get-Item-int-}
```
public final ILayoutSlide get_Item(int index)
```


Visszaadja az index szerinti elrendezési diát. Csak olvasható [LayoutSlide](../../com.aspose.slides/layoutslide).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatér:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public final ILayoutSlide getByType(byte type)
```


Visszaadja a megadott típusú első elrendezési diát.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | byte | Az elrendezési dia típusa, amelyet keres. |

**Visszatér:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) – [LayoutSlide](../../com.aspose.slides/layoutslide) a megadott típussal vagy null, ha nem található elrendezés.
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public final void remove(ILayoutSlide value)
```


Eltávolít egy elrendezést a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Az elrendezési dia, amelyet el kell távolítani a gyűjteményből.

--------------------

1) A PptxEditException dobásának elkerülése érdekében ellenőrizze a layout HasDependingSlides tulajdonságát előtte. 2) Használhatja a(z) [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) metódust is a kód egyszerűsítéséhez. |
### removeUnused() {#removeUnused--}
```
public final void removeUnused()
```


Eltávolítja a használaton kívüli elrendezési diákot (azok a diák, amelyeknél a HasHavingDependingSlides hamis).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iterator()
```


Visszaad egy enumerátort, amely végigjárja a gyűjteményt.

**Visszatér:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - A IGenericEnumerator, amely használható a gyűjtemény bejárásához.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iteratorJava()
```


Visszaad egy Java iterátort a teljes gyűjteményhez.

**Visszatér:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - Egy java.util.Iterator a teljes gyűjteményhez.
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


Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos)-e. Csak olvasható boolean.

**Visszatér:**  
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Visszaad egy szinkronizációs gyökeret. Csak olvasható Object.

**Visszatér:**  
java.lang.Object
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Visszaadja a Parent_Immediate objektumot. Csak olvasható IDOMObject.