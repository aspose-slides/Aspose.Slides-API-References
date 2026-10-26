---
title: CommentAuthorCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een verzameling van commentaarauteurs voor.
type: docs
url: /nl/com.aspose.slides/commentauthorcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
```
public final class CommentAuthorCollection extends DomObject<Presentation> implements ICommentAuthorCollection
```

Stelt een verzameling van commentaarauteurs voor.

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [size()](#size--) | Haalt het aantal elementen op dat daadwerkelijk in de collectie zit. |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op op de opgegeven index. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | Voegt een nieuwe auteur toe aan het einde van een collectie. |
| [toArray()](#toArray--) | Maakt een array met alle auteurs en retourneert deze. |
| [findByName(String name)](#findByName-java.lang.String-) | Zoekt een auteur in een collectie op naam. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | Zoekt een auteur in een collectie op naam en initialen. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert de auteur op de opgegeven index van de collectie. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | Verwijdert het eerste voorkomen van de opgegeven auteur in een collectie. |
| [clear()](#clear--) | Verwijdert alle auteurs uit een collectie. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie itereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java iterator voor de volledige collectie. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopieert alle elementen van de collectie naar de opgegeven array. |
| [isSynchronized()](#isSynchronized--) | Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retourneert een synchronisatiewortel. |

### size() {#size--}
```
public final int size()
```

Haalt het aantal elementen op dat daadwerkelijk in de collectie zit. Alleen-lezen int.

**Retour:**
int

### get_Item(int index) {#get-Item-int-}
```
public final ICommentAuthor get_Item(int index)
```

Haalt het element op op de opgegeven index. Alleen-lezen [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Retour:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)

### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public final ICommentAuthor addAuthor(String name, String initials)
```

Voegt een nieuwe auteur toe aan het einde van een collectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of a new author. |
| initials | java.lang.String | Initials of a new author. |

**Retour:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - Nieuw [ICommentAuthor](../../com.aspose.slides/icommentauthor) object.

### toArray() {#toArray--}
```
public final ICommentAuthor[] toArray()
```

Maakt een array met alle auteurs en retourneert deze.

**Retour:**
com.aspose.slides.ICommentAuthor[] - Array of [ICommentAuthor](../../com.aspose.slides/icommentauthor)

### findByName(String name) {#findByName-java.lang.String-}
```
public final ICommentAuthor[] findByName(String name)
```

Zoekt een auteur in een collectie op naam.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of an author to find. |

**Retour:**
com.aspose.slides.ICommentAuthor[] - Auteur of null.

### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public final ICommentAuthor[] findByNameAndInitials(String name, String initials)
```

Zoekt een auteur in een collectie op naam en initialen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of an author to find. |
| initials | java.lang.String | Initials of an author to find. |

**Retour:**
com.aspose.slides.ICommentAuthor[] - Auteur of null.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Verwijdert de auteur op de opgegeven index van de collectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nul-gebaseerde index van het te verwijderen element. |

### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public final void remove(ICommentAuthor author)
```

Verwijdert het eerste voorkomen van de opgegeven auteur in een collectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | De auteur die uit een collectie moet worden verwijderd. |

### clear() {#clear--}
```
public final void clear()
```

Verwijdert alle auteurs uit een collectie.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iterator()
```

Retourneert een enumerator die door de collectie itereert.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iteratorJava()
```

Retourneert een java iterator voor de volledige collectie.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - Een java.util.Iterator voor de volledige collectie.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopieert alle elementen van de collectie naar de opgegeven array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Doelarray. |
| index | int | Startindex in de doelarray. |

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