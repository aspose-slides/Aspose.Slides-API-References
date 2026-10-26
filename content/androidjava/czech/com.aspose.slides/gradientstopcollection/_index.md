---
title: GradientStopCollection
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Reprezentuje kolekci gradientových zastávek.
type: docs
url: /cs/com.aspose.slides/gradientstopcollection/
---
**Dědičnost:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Všechny implementované rozhraní:**  
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
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | Vytvoří novou gradientovou zastávku a přidá ji na konec kolekce. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Vytvoří novou gradientovou zastávku a přidá ji na konec kolekce. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Vytvoří novou gradientovou zastávku a přidá ji na konec kolekce. |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | Vytvoří novou gradientovou zastávku a vloží ji na zadaný index do kolekce. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Vytvoří novou gradientovou zastávku a vloží ji na zadaný index do kolekce. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Vytvoří novou gradientovou zastávku a vloží ji na zadaný index do kolekce. |
| [removeAt(int index)](#removeAt-int-) | Odstraní gradientovou zastávku na zadaném indexu. |
| [clear()](#clear--) | Odstraní všechny gradientové zastávky z kolekce. |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází kolekci. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterátor pro celou kolekci. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopíruje všechny prvky z kolekce do zadaného pole. |
| [isSynchronized()](#isSynchronized--) | Vrací hodnotu označující, zda je přístup ke kolekci synchronizován (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Vrací synchronizační kořen. |

### getVersion() {#getVersion--}
```
public long getVersion()
```


Verze. Pouze pro čtení, long.

**Vrací:**
long

### size() {#size--}
```
public final int size()
```


Vrací počet gradientových zastávek v kolekci. Pouze pro čtení  int .

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

### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public final IGradientStop add(float position, Integer color)
```


Vytvoří novou gradientovou zastávku a přidá ji na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| position | float | Pozice nové gradientové zastávky. |
| color | java.lang.Integer | Barva nové gradientové zastávky. |

**Vrací:**
[IGradientStop](../../com.aspose.slides/igradientstop) – Index nové gradientové zastávky v kolekci.

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
[IGradientStop](../../com.aspose.slides/igradientstop) – Index nové gradientové zastávky v kolekci.

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
[IGradientStop](../../com.aspose.slides/igradientstop) – Index nové gradientové zastávky v kolekci.

### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public final void insert(int index, float position, Integer color)
```


Vytvoří novou gradientovou zastávku a vloží ji na zadaný index do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index v kolekci, kde bude nová gradientová zastávka vložena. |
| position | float | Pozice nové gradientové zastávky. |
| color | java.lang.Integer | Barva nové gradientové zastávky. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public final void insertPresetColor(int index, float position, int presetColor)
```


Vytvoří novou gradientovou zastávku a vloží ji na zadaný index do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index v kolekci, kde bude nová gradientová zastávka vložena. |
| position | float | Pozice nové gradientové zastávky. |
| presetColor | int | Barva nové gradientové zastávky. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public final void insertSchemeColor(int index, float position, int schemeColor)
```


Vytvoří novou gradientovou zastávku a vloží ji na zadaný index do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index v kolekci, kde bude nová gradientová zastávka vložena. |
| position | float | Pozice nové gradientové zastávky. |
| schemeColor | int | Barva nové gradientové zastávky. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Odstraní gradientovou zastávku na zadaném indexu.

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


Vrací enumerátor, který prochází kolekcí.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - IGenericEnumerator, který lze použít k iteraci přes kolekci.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iteratorJava()
```


Vrací java iterátor pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - java.util.Iterator pro celou kolekci.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopíruje všechny prvky z kolekce do zadaného pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cílové pole. |
| index | int | Počáteční index v cílovém poli. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Vrací hodnotu označující, zda je přístup ke kolekci synchronizován (thread-safe). Pouze pro čtení  boolean .

**Vrací:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Vrací synchronizační kořen. Pouze pro čtení Object.

**Vrací:**
java.lang.Object