---
title: ColorOperationCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een verzameling van kleurtransformatieoperaties voor.
type: docs
url: /nl/com.aspose.slides/coloroperationcollection/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
```
public final class ColorOperationCollection implements IColorOperationCollection
```

Stelt een verzameling van kleurtransformatie-operaties voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [size()](#size--) | Retourneert het aantal operaties in een collectie. |
| [get_Item(int index)](#get-Item-int-) | Retourneert of stelt de bewerking in op de opgegeven index. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | Retourneert of stelt de bewerking in op de opgegeven index. |
| [add(int operation, float parameter)](#add-int-float-) | Voegt een nieuwe bewerking toe aan het einde van de collectie. |
| [add(int operation)](#add-int-) | Voegt een nieuwe bewerking toe aan het einde van de collectie. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | Voegt de nieuwe bewerking toe aan een collectie. |
| [insert(int position, int operation)](#insert-int-int-) | Voegt de nieuwe bewerking toe aan een collectie. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert de kleuroperatie uit een collectie. |
| [clear()](#clear--) | Verwijdert alle kleuroperaties. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie itereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een Java-iterator voor de gehele collectie. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopieert alle elementen van de collectie naar de opgegeven array. |
| [isSynchronized()](#isSynchronized--) | Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retourneert een synchronisatie-root. |
| [deepClone()](#deepClone--) | Maakt een kopie van een ColorOperationCollection-collectie. |
| [cloneT()](#cloneT--) | Kloont het huidige object |

### size() {#size--}
```
public final int size()
```

Retourneert het aantal operaties in een collectie. Alleen-lezen int.

**Retour:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IColorOperation get_Item(int index)
```

Retourneert of stelt de bewerking in op de opgegeven index. Lezen/Schrijven [ColorOperation](../../com.aspose.slides/coloroperation).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retour:**
[IColorOperation](../../com.aspose.slides/icoloroperation)
### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public final void set_Item(int index, IColorOperation value)
```

Retourneert of stelt de bewerking in op de opgegeven index. Lezen/Schrijven [ColorOperation](../../com.aspose.slides/coloroperation).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public final IColorOperation add(int operation, float parameter)
```

Voegt een nieuwe bewerking toe aan het einde van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| operation | int | Type bewerking. |
| parameter | float | Parameter van de bewerking. |

**Retour:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Toegevoegde bewerking.
### add(int operation) {#add-int-}
```
public final IColorOperation add(int operation)
```

Voegt een nieuwe bewerking toe aan het einde van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| operation | int | Type bewerking. |

**Retour:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Toegevoegde bewerking.
### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public final IColorOperation insert(int position, int operation, float parameter)
```

Voegt de nieuwe bewerking toe aan een collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| position | int | De index waarop de bewerking wordt ingevoegd. |
| operation | int | Type bewerking. |
| parameter | float | Parameter van de bewerking. |

**Retour:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Ingevoegde bewerking.
### insert(int position, int operation) {#insert-int-int-}
```
public final IColorOperation insert(int position, int operation)
```

Voegt de nieuwe bewerking toe aan een collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| position | int | De index waarop de bewerking wordt ingevoegd. |
| operation | int | Type bewerking. |

**Retour:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Ingevoegde bewerking.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Verwijdert de kleuroperatie uit een collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van een te verwijderen kleuroperatie. |

### clear() {#clear--}
```
public final void clear()
```

Verwijdert alle kleuroperaties.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iterator()
```

Retourneert een enumerator die door de collectie itereert.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iteratorJava()
```

Retourneert een Java-iterator voor de gehele collectie.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - Een java.util.Iterator voor de gehele collectie.
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

Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). Alleen-lezen boolean.

**Retour:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Retourneert een synchronisatie-root. Alleen-lezen Object.

**Retour:**
java.lang.Object
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Maakt een kopie van een ColorOperationCollection-collectie.

**Retour:**
java.lang.Object - Nieuwe [ColorOperationCollection](../../com.aspose.slides/coloroperationcollection) collectie.
### cloneT() {#cloneT--}
```
public final IColorOperationCollection cloneT()
```

Kloont het huidige object

**Retour:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection) - Kloon