---
title: VbaModuleCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een verzameling van VBA-projectmodules voor.
type: docs
url: /nl/com.aspose.slides/vbamodulecollection/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
```
public final class VbaModuleCollection implements IVbaModuleCollection
```

Stelt een verzameling van VBA-projectmodules voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [size()](#size--) | Haalt het aantal elementen op dat daadwerkelijk in de collectie aanwezig is. |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | Verwijdert de eerste instantie van een specifiek object uit de collectie. |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | Voegt een nieuw leeg module toe aan het VBA-project. |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op op de opgegeven index. |
| [iterator()](#iterator--) | Geeft een enumerator terug die door de collectie iterereert. |
| [iteratorJava()](#iteratorJava--) | Geeft een Java-iterator terug voor de volledige collectie. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopieert alle elementen vanuit de collectie naar de opgegeven array. |
| [isSynchronized()](#isSynchronized--) | Geeft een waarde terug die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Geeft een synchronisatiewortel terug. |
### size() {#size--}
```
public final int size()
```

Haalt het aantal elementen op dat daadwerkelijk in de collectie aanwezig is. Alleen-lezen int.

**Returns:**
int
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public final void remove(IVbaModule value)
```

Verwijdert de eerste instantie van een specifiek object uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | De module die uit de collectie moet worden verwijderd. |

### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public final IVbaModule addEmptyModule(String name)
```

Voegt een nieuw leeg module toe aan het VBA-project.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de module |

**Returns:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - Toegevoegde module.
### get_Item(int index) {#get-Item-int-}
```
public final IVbaModule get_Item(int index)
```

Haalt het element op op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iterator()
```

Geeft een enumerator terug die door de collectie iterereert.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iteratorJava()
```

Geeft een Java-iterator terug voor de volledige collectie.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - Een java.util.Iterator voor de volledige collectie.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopieert alle elementen vanuit de collectie naar de opgegeven array.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Doelarray. |
| index | int | Startindex in de doelarray. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Geeft een waarde terug die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). Alleen-lezen boolean.

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Geeft een synchronisatiewortel terug. Alleen-lezen Object.

**Returns:**
java.lang.Object