---
title: LayoutSlideCollection
second_title: Aspose.Slides Androidra a Java API hivatkozás
description: Az elrendezési diák gyűjteményének alaposztályát képviseli.
type: docs
url: /hu/com.aspose.slides/layoutslidecollection/
---
**Öröklés:**
java.lang.Object

**Minden implementált interfész:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection), com.aspose.slides.IDOMObject
```
public class LayoutSlideCollection implements ILayoutSlideCollection, IDOMObject
```

Az elrendezési dia gyűjteményének alaposztályát képviseli.
## Metódusok

| Módszer | Leírás |
| --- | --- |
| [size()](#size--) | Visszaadja az elrendezési diák számát a gyűjteményben. |
| [get_Item(int index)](#get-Item-int-) | Visszaadja az elrendezési diát index alapján. |
| [getByType(byte type)](#getByType-byte-) | Visszaadja az első megadott típusú elrendezési diát. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Eltávolít egy elrendezést a gyűjteményből. |
| [removeUnused()](#removeUnused--) | Eltávolítja a nem használt elrendezési diákat (olyan diákat, amelyeknél a HasDependingSlides hamis). |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely bejárja a gyűjteményt. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort a teljes gyűjteményhez. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Átmásolja a gyűjtemény összes elemét a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált-e (szálbiztos). |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy szinkronizációs gyökérobjektumot. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### size() {#size--}
```
public final int size()
```


Visszaadja az elrendezési diák számát a gyűjteményben. Csak olvasható int.

**Visszatérési érték:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ILayoutSlide get_Item(int index)
```


Visszaadja az elrendezési diát index alapján. Csak olvasható [LayoutSlide](../../com.aspose.slides/layoutslide).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public final ILayoutSlide getByType(byte type)
```


Visszaadja az első megadott típusú elrendezési diát.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | byte | A keresett elrendezési dia típusa. |

**Visszatérési érték:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) – [LayoutSlide](../../com.aspose.slides/layoutslide) a megadott típussal, vagy null, ha nem található elrendezés.
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public final void remove(ILayoutSlide value)
```


Eltávolít egy elrendezést a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Az eltávolítandó elrendezési dia.

--------------------

1) A PptxEditException dobódásának elkerülése érdekében ellenőrizze a layout HasDependingSlides tulajdonságát előtte. 2) Használhatja a [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) metódust is a kód egyszerűsítéséhez. |
### removeUnused() {#removeUnused--}
```
public final void removeUnused()
```


Eltávolítja a nem használt elrendezési diákat (olyan diákat, amelyeknél a HasDependingSlides hamis).

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iterator()
```


Visszaad egy enumerátort, amely bejárja a gyűjteményt.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> – Egy IGenericEnumerator, amely a gyűjtemény bejárására használható.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iteratorJava()
```


Visszaad egy java iterátort a teljes gyűjteményhez.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> – Egy java.util.Iterator a teljes gyűjteményhez.
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


Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált-e (szálbiztos). Csak olvasható boolean.

**Visszatérési érték:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Visszaad egy szinkronizációs gyökérobjektumot. Csak olvasható Object.

**Visszatérési érték:**
java.lang.Object
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Visszaadja a Parent_Immediate objektumot. Csak olvasható IDOMObject.

**Visszatérési érték:**
com.aspose.slides.IDOMObject