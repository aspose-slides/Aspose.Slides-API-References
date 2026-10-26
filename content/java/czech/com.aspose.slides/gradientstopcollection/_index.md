---
title: GradientStopCollection
second_title: Aspose.Slides pro Java – referenční dokumentace API
description: Reprezentuje kolekci gradientových zastávek.
type: docs
url: /cs/com.aspose.slides/gradientstopcollection/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)
```
public final class GradientStopCollection extends PVIObject implements IGradientStopCollection
```

Reprezentuje kolekci gradientových zastávek.
## Metody

| Metoda | Popis |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [size()](#size--) | Vrací počet gradientových zastávek v kolekci. |
| [get_Item(int index)](#get-Item-int-) | Vrací gradientovou zastávku podle indexu. |
| [add(float position, Color color)](#add-float-java.awt.Color-) | Vytvoří novou gradientovou zastávku a přidá ji na konec kolekce. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Vytvoří novou gradientovou zastávku a přidá ji na konec kolekce. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Vytvoří novou gradientovou zastávku a přidá ji na konec kolekce. |
| [insert(int index, float position, Color color)](#insert-int-float-java.awt.Color-) | Vytvoří novou gradientovou zastávku a vloží ji na určený index v kolekci. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Vytvoří novou gradientovou zastávku a vloží ji na určený index v kolekci. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Vytvoří novou gradientovou zastávku a vloží ji na určený index v kolekci. |
| [removeAt(int index)](#removeAt-int-) | Odstraní gradientovou zastávku na určeném indexu. |
| [clear()](#clear--) | Odstraní všechny gradientové zastávky z kolekce. |
| [iterator()](#iterator--) | Vrací enumerátor, který iteruje přes kolekci. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterátor pro celou kolekci. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Zkopíruje všechny prvky z kolekce do zadaného pole. |
| [isSynchronized()](#isSynchronized--) | Vrací hodnotu indikující, zda je přístup ke kolekci synchronizován (vláknově bezpečný). |
| [getSyncRoot()](#getSyncRoot--) | Vrací kořen synchronizace. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Verze. Pouze pro čtení long.

**Vrací:**
long
### size() {#size--}
```
public final int size()
```

Vrací počet gradientových zastávek v kolekci. Pouze pro čtení int.

**Vrací:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IGradientStop get_Item(int index)
```

Vrací gradientovou zastávku podle indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Color color) {#add-float-java.awt.Color-}
```
public final IGradientStop add(float position, Color color)
```

Vytvoří novou gradientovou zastávku a přidá ji na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| position | float | Pozice nové gradientové zastávky. |
| color | java.awt.Color | Barva nové gradientové zastávky. |

**Vrací:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Index nové gradientové zastávky v kolekci.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public final IGradientStop addPresetColor(float position, int presetColor)
```

Vytvoří novou gradientovou zastávku a přidá ji na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| position | float | Pozice nové gradientové zastávky. |
| presetColor | int | Barva nové gradientové zastávky. |

**Vrací:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Index nové gradientové zastávky v kolekci.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public final IGradientStop addSchemeColor(float position, int schemeColor)
```

Vytvoří novou gradientovou zastávku a přidá ji na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| position | float | Pozice nové gradientové zastávky. |
| schemeColor | int | Barva nové gradientové zastávky. |

**Vrací:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Index nové gradientové zastávky v kolekci.
### insert(int index, float position, Color color) {#insert-int-float-java.awt.Color-}
```
public final void insert(int index, float position, Color color)
```

Vytvoří novou gradientovou zastávku a vloží ji na určený index v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index v kolekci, kam bude nová gradientová zastávka vložena. |
| position | float | Pozice nové gradientové zastávky. |
| color | java.awt.Color | Barva nové gradientové zastávky. |
### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public final void insertPresetColor(int index, float position, int presetColor)
```

Vytvoří novou gradientovou zastávku a vloží ji na určený index v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index v kolekci, kam bude nová gradientová zastávka vložena. |
| position | float | Pozice nové gradientové zastávky. |
| presetColor | int | Barva nové gradientové zastávky. |
### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public final void insertSchemeColor(int index, float position, int schemeColor)
```

Vytvoří novou gradientovou zastávku a vloží ji na určený index v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index v kolekci, kam bude nová gradientová zastávka vložena. |
| position | float | Pozice nové gradientové zastávky. |
| schemeColor | int | Barva nové gradientové zastávky. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Odstraní gradientovou zastávku na určeném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index gradientové zastávky, která má být smazána. |
### clear() {#clear--}
```
public final void clear()
```

Odstraní všechny gradientové zastávky z kolekce.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iterator()
```

Vrací enumerátor, který iteruje přes kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iteratorJava()
```

Vrací java iterátor pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Zkopíruje všechny prvky z kolekce do zadaného pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cílové pole. |
| index | int | Počáteční index v cílovém poli. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Vrací hodnotu indikující, zda je přístup ke kolekci synchronizován (vláknově bezpečný). Pouze pro čtení boolean.

**Vrací:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Vrací kořen synchronizace. Pouze pro čtení Object.

**Vrací:**
java.lang.Object