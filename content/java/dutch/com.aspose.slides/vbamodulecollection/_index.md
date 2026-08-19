---
title: VbaModuleCollection
second_title: Aspose.Slides voor Java API-referentie
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

| Methode | Omschrijving |
| --- | --- |
| [size()](#size--) | Haalt het aantal elementen op dat daadwerkelijk in de collectie zit. |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | Verwijdert de eerste voorkoming van een specifiek object uit de collectie. |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | Voegt een nieuw leeg module toe aan het VBA-project. |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op op de opgegeven index. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie iterereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java-iterator voor de volledige collectie. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopieert alle elementen van de collectie naar de opgegeven array. |
| [isSynchronized()](#isSynchronized--) | Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd (thread-safe) is. |
| [getSyncRoot()](#getSyncRoot--) | Retourneert een synchronisatiewortel. |
### size() {#size--}
```
public final int size()
```


Haalt het aantal elementen op dat daadwerkelijk in de collectie zit. Alleen-lezen int.

**Retour:**
int
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public final void remove(IVbaModule value)
```


Verwijdert de eerste voorkoming van een specifiek object uit de collectie.

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | De module die uit de collectie moet worden verwijderd. |

### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public final IVbaModule addEmptyModule(String name)
```


Voegt een nieuw leeg module toe aan het VBA-project.

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de module |

**Retour:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - Toegevoegde module.
### get_Item(int index) {#get-Item-int-}
```
public final IVbaModule get_Item(int index)
```


Haalt het element op op de opgegeven index.

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| index | int |  |

**Retour:**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iterator()
```


Retourneert een enumerator die door de collectie iterereert.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iteratorJava()
```


Retourneert een java-iterator voor de volledige collectie.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - Een java.util.Iterator voor de volledige collectie.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopieert alle elementen van de collectie naar de opgegeven array.

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Doel-array. |
| index | int | Begindex in de doel-array. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd (thread-safe) is. Alleen-lezen boolean.

**Retour:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Retourneert een synchronisatiewortel. Alleen-lezen Object.

**Retour:**
java.lang.Object