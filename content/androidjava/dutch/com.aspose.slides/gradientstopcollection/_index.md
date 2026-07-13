---
title: GradientStopCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een collectie van gradient stops voor.
type: docs
url: /nl/com.aspose.slides/gradientstopcollection/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)
```
public final class GradientStopCollection extends PVIObject implements IGradientStopCollection
```

Stelt een collectie van gradient stops voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [size()](#size--) | Retourneert het aantal gradient stops in een collectie. |
| [get_Item(int index)](#get-Item-int-) | Retourneert de gradient stop op index. |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | Maakt de nieuwe gradient stop aan en voegt deze toe aan het einde van de collectie. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Maakt de nieuwe gradient stop aan en voegt deze toe aan het einde van de collectie. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Maakt de nieuwe gradient stop aan en voegt deze toe aan het einde van de collectie. |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | Maakt de nieuwe gradient stop aan en voegt deze in op de opgegeven index in de collectie. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Maakt de nieuwe gradient stop aan en voegt deze in op de opgegeven index in de collectie. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Maakt de nieuwe gradient stop aan en voegt deze in op de opgegeven index in de collectie. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert een gradient stop op de opgegeven index. |
| [clear()](#clear--) | Verwijdert alle gradient stops uit een collectie. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie iterereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java-iterator voor de gehele collectie. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopieert alle elementen van de collectie naar de opgegeven array. |
| [isSynchronized()](#isSynchronized--) | Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retourneert een synchronisatiewortel. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versie. Alleen-lezen long.

**Returns:**
long
### size() {#size--}
```
public final int size()
```

Retourneert het aantal gradient stops in een collectie. Alleen-lezen int .

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IGradientStop get_Item(int index)
```

Retourneert de gradient stop op index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public final IGradientStop add(float position, Integer color)
```

Maakt de nieuwe gradient stop aan en voegt deze toe aan het einde van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| position | float | Positie van de nieuwe gradient stop. |
| color | java.lang.Integer | Kleur van de nieuwe gradient stop. |

**Returns:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Index van de nieuwe gradient stop in de collectie.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public final IGradientStop addPresetColor(float position, int presetColor)
```

Maakt de nieuwe gradient stop aan en voegt deze toe aan het einde van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| position | float | Positie van de nieuwe gradient stop. |
| presetColor | int | Kleur van de nieuwe gradient stop. |

**Returns:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Index van de nieuwe gradient stop in de collectie.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public final IGradientStop addSchemeColor(float position, int schemeColor)
```

Maakt de nieuwe gradient stop aan en voegt deze toe aan het einde van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| position | float | Positie van de nieuwe gradient stop. |
| schemeColor | int | Kleur van de nieuwe gradient stop. |

**Returns:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Index van de nieuwe gradient stop in de collectie.
### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public final void insert(int index, float position, Integer color)
```

Maakt de nieuwe gradient stop aan en voegt deze in op de opgegeven index in de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index in de collectie waar de nieuwe gradient stop wordt ingevoegd. |
| position | float | Positie van de nieuwe gradient stop. |
| color | java.lang.Integer | Kleur van de nieuwe gradient stop. |
### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public final void insertPresetColor(int index, float position, int presetColor)
```

Maakt de nieuwe gradient stop aan en voegt deze in op de opgegeven index in de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index in de collectie waar de nieuwe gradient stop wordt ingevoegd. |
| position | float | Positie van de nieuwe gradient stop. |
| presetColor | int | Kleur van de nieuwe gradient stop. |
### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public final void insertSchemeColor(int index, float position, int schemeColor)
```

Maakt de nieuwe gradient stop aan en voegt deze in op de opgegeven index in de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index in de collectie waar de nieuwe gradient stop wordt ingevoegd. |
| position | float | Positie van de nieuwe gradient stop. |
| schemeColor | int | Kleur van de nieuwe gradient stop. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Verwijdert een gradient stop op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van een gradient stop die verwijderd moet worden. |
### clear() {#clear--}
```
public final void clear()
```

Verwijdert alle gradient stops uit een collectie.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iterator()
```

Retourneert een enumerator die door de collectie iterereert.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iteratorJava()
```

Retourneert een java-iterator voor de gehele collectie.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - Een java.util.Iterator voor de gehele collectie.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopieert alle elementen van de collectie naar de opgegeven array.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Doel-array. |
| index | int | Startindex in de doel-array. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). Alleen-lezen boolean .

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Retourneert een synchronisatiewortel. Alleen-lezen Object.

**Returns:**
java.lang.Object