---
title: CommentAuthorCollection
second_title: Aspose.Slides voor Java API Referentie
description: Stelt een verzameling van commentaurauteurs voor.
type: docs
url: /nl/com.aspose.slides/commentauthorcollection/
---
**Erfelijkheid:**  
java.lang.Object, com.aspose.slides.DomObject

**Alle geïmplementeerde interfaces:**  
[com.aspose.slides.ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
```
public final class CommentAuthorCollection extends DomObject<Presentation> implements ICommentAuthorCollection
```

Stelt een verzameling van commentaurauteurs voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [size()](#size--) | Haalt het aantal elementen op dat daadwerkelijk in de collectie zit. |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op op de opgegeven index. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | Voeg nieuwe auteur toe aan het einde van een collectie. |
| [toArray()](#toArray--) | Maakt en retourneert een array met alle auteurs. |
| [findByName(String name)](#findByName-java.lang.String-) | Zoek auteur in een collectie op naam. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | Zoek auteur in een collectie op naam en initiaal. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert de auteur op de opgegeven index van de collectie. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | Verwijdert de eerste instantie van de opgegeven auteur in een collectie. |
| [clear()](#clear--) | Verwijdert alle auteurs uit een collectie. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie itereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java iterator voor de gehele collectie. |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retour:**  
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public final ICommentAuthor addAuthor(String name, String initials)
```

Voeg een nieuwe auteur toe aan het einde van een collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van een nieuwe auteur. |
| initials | java.lang.String | Initialen van een nieuwe auteur. |

**Retour:**  
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - Nieuw [ICommentAuthor](../../com.aspose.slides/icommentauthor) object.
### toArray() {#toArray--}
```
public final ICommentAuthor[] toArray()
```

Maakt en retourneert een array met alle auteurs.

**Retour:**  
com.aspose.slides.ICommentAuthor[] - Array van [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public final ICommentAuthor[] findByName(String name)
```

Zoek auteur in een collectie op naam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van een auteur om te zoeken. |

**Retour:**  
com.aspose.slides.ICommentAuthor[] - Auteur of null.
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public final ICommentAuthor[] findByNameAndInitials(String name, String initials)
```

Zoek auteur in een collectie op naam en initiaal.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van een auteur om te zoeken. |
| initials | java.lang.String | Initialen van een auteur om te zoeken. |

**Retour:**  
com.aspose.slides.ICommentAuthor[] - Auteur of null.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Verwijdert de auteur op de opgegeven index van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nul-gebaseerde index van het te verwijderen element. |

### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public final void remove(ICommentAuthor author)
```

Verwijdert de eerste instantie van de opgegeven auteur in een collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | De auteur die uit de collectie moet worden verwijderd. |

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

Retourneert een java iterator voor de gehele collectie.

**Retour:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - Een java.util.Iterator voor de gehele collectie.
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

Retourneert een synchronisatiewortel. Alleen-lezen Object.

**Retour:**  
java.lang.Object