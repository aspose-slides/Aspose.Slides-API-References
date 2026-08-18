---
title: EffectStyleCollection
second_title: Aspose.Slides Java API hivatkozás
description: Egy effektusstílusok gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/effectstylecollection/
---
**Öröklés:**
java.lang.Object, com.aspose.slides.DomObject

**Összes megvalósított interfész:**
[com.aspose.slides.IEffectStyleCollection](../../com.aspose.slides/ieffectstylecollection)
```
public final class EffectStyleCollection extends DomObject<FormatScheme> implements IEffectStyleCollection
```

Egy effektusstílusok gyűjteményét képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszatér egy elemmel a megadott pozíción. |
| [iterator()](#iterator--) | Visszatér egy enumerátorral, amely végig iterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszatér egy java iterátorral az egész gyűjteményhez. |
| [size()](#size--) | Visszatér a gyűjtemény elemeinek számával. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Átmásolja a gyűjtemény összes elemét a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Visszatér egy értékkel, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos). |
| [getSyncRoot()](#getSyncRoot--) | Visszatér egy szinkronizációs gyökérrel. |
### get_Item(int index) {#get-Item-int-}
```
public final IEffectStyle get_Item(int index)
```

Visszatér egy elemmel a megadott pozíción. Csak olvasható [EffectStyle](../../com.aspose.slides/effectstyle).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Elem pozíciója. |

**Visszatér:**
[IEffectStyle](../../com.aspose.slides/ieffectstyle) - Elem a megadott pozíción.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectStyle> iterator()
```

Visszatér egy enumerátorral, amely végig iterál a gyűjteményen.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectStyle> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectStyle> iteratorJava()
```

Visszatér egy java iterátorral az egész gyűjteményhez.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectStyle> - An java.util.Iterator for the entire collection.
### size() {#size--}
```
public final int size()
```

Visszatér a gyűjtemény elemeinek számával. Csak olvasható int, csak olvasható int.

**Visszatér:**
int
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

Visszatér egy értékkel, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos). Csak olvasható boolean.

**Visszatér:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Visszatér egy szinkronizációs gyökérrel. Csak olvasható Object.

**Visszatér:**
java.lang.Object