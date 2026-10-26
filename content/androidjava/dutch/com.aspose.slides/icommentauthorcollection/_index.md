---
title: ICommentAuthorCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een collectie van commentaarauteurs voor.
type: docs
url: /nl/com.aspose.slides/icommentauthorcollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ICommentAuthorCollection extends IGenericCollection<ICommentAuthor>
```

Stelt een collectie van commentaarauteurs voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op op de opgegeven index. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | Voegt een nieuwe auteur toe aan het einde van een collectie. |
| [toArray()](#toArray--) | Maakt een array met alle auteurs aan en retourneert deze. |
| [findByName(String name)](#findByName-java.lang.String-) | Zoekt een auteur in een collectie op naam. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | Zoekt een auteur in een collectie op naam en initialen. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert de auteur op de opgegeven index van de collectie. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | Verwijdert de eerste instantie van de opgegeven auteur in een collectie. |
| [clear()](#clear--) | Verwijdert alle auteurs uit een collectie. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICommentAuthor get_Item(int index)
```

Haalt het element op op de opgegeven index. Alleen-lezen [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retourwaarden:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor addAuthor(String name, String initials)
```

Voegt een nieuwe auteur toe aan het einde van een collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van een nieuwe auteur. |
| initials | java.lang.String | Initialen van een nieuwe auteur. |

**Retourwaarden:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - Nieuw [ICommentAuthor](../../com.aspose.slides/icommentauthor) object.
### toArray() {#toArray--}
```
public abstract ICommentAuthor[] toArray()
```

Maakt een array met alle auteurs aan en retourneert deze.

**Retourwaarden:**
com.aspose.slides.ICommentAuthor[] - Array van [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public abstract ICommentAuthor[] findByName(String name)
```

Zoekt een auteur in een collectie op naam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van een te vinden auteur. |

**Retourwaarden:**
com.aspose.slides.ICommentAuthor[] - Auteur of null.
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor[] findByNameAndInitials(String name, String initials)
```

Zoekt een auteur in een collectie op naam en initialen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van een te vinden auteur. |
| initials | java.lang.String | Initialen van een te vinden auteur. |

**Retourwaarden:**
com.aspose.slides.ICommentAuthor[] - Auteur of null.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Verwijdert de auteur op de opgegeven index van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index van het te verwijderen element. |

### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public abstract void remove(ICommentAuthor author)
```

Verwijdert de eerste instantie van de opgegeven auteur in een collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | De auteur die uit een collectie moet worden verwijderd. |

### clear() {#clear--}
```
public abstract void clear()
```

Verwijdert alle auteurs uit een collectie.