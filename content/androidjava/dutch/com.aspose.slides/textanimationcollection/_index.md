---
title: TextAnimationCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een collectie van tekstanimaties voor.
type: docs
url: /nl/com.aspose.slides/textanimationcollection/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)
```
public class TextAnimationCollection implements ITextAnimationCollection
```

Stelt een collectie van tekstanimaties voor.
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [TextAnimationCollection()](#TextAnimationCollection--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [size()](#size--) | Retourneert het aantal elementen in de collectie. |
| [add()](#add--) | Voegt een nieuwe tekstanimatie toe aan de collectie. |
| [get_Item(int index)](#get-Item-int-) | Retourneert een element op index. |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | Retourneert alle elementen |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie heen iterereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een Java-iterator voor de gehele collectie. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopieert alle elementen uit de collectie naar de opgegeven array. |
| [isSynchronized()](#isSynchronized--) | Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retourneert een synchronisatiewortel. |
### TextAnimationCollection() {#TextAnimationCollection--}
```
public TextAnimationCollection()
```

### size() {#size--}
```
public final int size()
```

Retourneert het aantal elementen in de collectie. Alleen-lezen int.

**Retour:**
int
### add() {#add--}
```
public final TextAnimation add()
```

Voegt een nieuwe tekstanimatie toe aan de collectie.

**Retour:**
[TextAnimation](../../com.aspose.slides/textanimation) - Added [TextAnimation](../../com.aspose.slides/textanimation)
### get_Item(int index) {#get-Item-int-}
```
public final ITextAnimation get_Item(int index)
```

Retourneert een element op index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retour:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### get_Item(IShape shape) {#get-Item-com.aspose.slides.IShape-}
```
public final ITextAnimation[] get_Item(IShape shape)
```

Retourneert alle elementen

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) te verwijderen. |

**Retour:**
com.aspose.slides.ITextAnimation[] - Array van [ITextAnimation](../../com.aspose.slides/itextanimation)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITextAnimation> iterator()
```

Retourneert een enumerator die door de collectie heen iterereert.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITextAnimation> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITextAnimation> iteratorJava()
```

Retourneert een Java-iterator voor de gehele collectie.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITextAnimation> - Een java.util.Iterator voor de gehele collectie.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopieert alle elementen uit de collectie naar de opgegeven array.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array om te vullen. |
| index | int | Startpositie in doelarray. |

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

Retourneert een synchronisatiewortel. Alleen-lezen Object.

**Retour:**
java.lang.Object