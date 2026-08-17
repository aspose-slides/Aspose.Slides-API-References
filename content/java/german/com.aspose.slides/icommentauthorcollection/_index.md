---
title: ICommentAuthorCollection
second_title: Aspose.Slides für Java API-Referenz
description: Stellt eine Sammlung von Kommentarautoren dar.
type: docs
url: /de/com.aspose.slides/icommentauthorcollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.slides.IGenericCollection
```
public interface ICommentAuthorCollection extends IGenericCollection<ICommentAuthor>
```

Stellt eine Sammlung von Kommentar-Autoren dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Ruft das Element am angegebenen Index ab. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | Fügt einen neuen Autor am Ende einer Sammlung hinzu. |
| [toArray()](#toArray--) | Erstellt und gibt ein Array mit allen Autoren zurück. |
| [findByName(String name)](#findByName-java.lang.String-) | Findet einen Autor in einer Sammlung anhand des Namens. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | Findet einen Autor in einer Sammlung anhand von Name und Initialen. |
| [removeAt(int index)](#removeAt-int-) | Entfernt den Autor am angegebenen Index der Sammlung. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | Entfernt das erste Vorkommen des angegebenen Autors in einer Sammlung. |
| [clear()](#clear--) | Entfernt alle Autoren aus einer Sammlung. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICommentAuthor get_Item(int index)
```


Ruft das Element am angegebenen Index ab. Nur-Lesen [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabe:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor addAuthor(String name, String initials)
```


Fügt einen neuen Autor am Ende einer Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name eines neuen Autors. |
| initials | java.lang.String | Initialen eines neuen Autors. |

**Rückgabe:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - Neues [ICommentAuthor](../../com.aspose.slides/icommentauthor) Objekt.
### toArray() {#toArray--}
```
public abstract ICommentAuthor[] toArray()
```


Erstellt und gibt ein Array mit allen Autoren zurück.

**Rückgabe:**
com.aspose.slides.ICommentAuthor[] - Array von [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public abstract ICommentAuthor[] findByName(String name)
```


Findet einen Autor in einer Sammlung anhand des Namens.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name eines zu findenden Autors. |

**Rückgabe:**
com.aspose.slides.ICommentAuthor[] - Autor oder null.
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor[] findByNameAndInitials(String name, String initials)
```


Findet einen Autor in einer Sammlung anhand von Name und Initialen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name eines zu findenden Autors. |
| initials | java.lang.String | Initialen eines zu findenden Autors. |

**Rückgabe:**
com.aspose.slides.ICommentAuthor[] - Autor oder null.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Entfernt den Autor am angegebenen Index der Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index des zu entfernenden Elements. |

### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public abstract void remove(ICommentAuthor author)
```


Entfernt das erste Vorkommen des angegebenen Autors in einer Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Der zu entfernende Autor aus einer Sammlung. |

### clear() {#clear--}
```
public abstract void clear()
```


Entfernt alle Autoren aus einer Sammlung.