---
title: GradientStopCollectionEffectiveData
second_title: Aspose.Slides Android számára - Java API referencia
description: A GradientStopData objektumok gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/gradientstopcollectioneffectivedata/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
com.aspose.slides.IEffectiveData, [com.aspose.slides.IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)
```
public class GradientStopCollectionEffectiveData implements IEffectiveData, IGradientStopCollectionEffectiveData
```

A GradientStopData objektumok gyűjteményét képviseli.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [size()](#size--) | Visszatér a gyűjteményben lévő színátmenet-állomások számával. |
| [get_Item(int index)](#get-Item-int-) | Visszatér a megadott indexű színátmenet-állomással. |
| [iterator()](#iterator--) | Visszatér egy enumerátorral, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszatér egy java iterátorral a teljes gyűjteményhez. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Átmásolja a gyűjtemény összes elemét a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Visszatér egy értékkel, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos)-e. |
| [getSyncRoot()](#getSyncRoot--) | Visszatér egy szinkronizációs gyökkel. |
### size() {#size--}
```
public final int size()
```


Visszatér a gyűjteményben lévő színátmenet-állomások számával. Csak olvasható int.

**Visszatér:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IGradientStopEffectiveData get_Item(int index)
```


Visszatér a megadott indexű színátmenet-állomással.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatér:**
[IGradientStopEffectiveData](../../com.aspose.slides/igradientstopeffectivedata)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStopEffectiveData> iterator()
```


Visszatér egy enumerátorral, amely végigiterál a gyűjteményen.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStopEffectiveData> - Egy IGenericEnumerator, amely a gyűjteményen történő iteráláshoz használható.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStopEffectiveData> iteratorJava()
```


Visszatér egy java iterátorral a teljes gyűjteményhez.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStopEffectiveData> - Egy java.util.Iterator a teljes gyűjteményhez.
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


Visszatér egy értékkel, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos)-e. Csak olvasható boolean.

**Visszatér:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Visszatér egy szinkronizációs gyökkel. Csak olvasható Object.

**Visszatér:**
java.lang.Object