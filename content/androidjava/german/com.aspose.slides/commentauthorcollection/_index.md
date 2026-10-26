---
title: CommentAuthorCollection
second_title: Aspose.Slides für Android über die Java API-Referenz
description: Stellt eine Sammlung von Kommentarautoren dar.
type: docs
url: /de/com.aspose.slides/commentauthorcollection/
---
**Vererbung:**
java.lang.Object, com.aspose.slides.DomObject

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
```
public final class CommentAuthorCollection extends DomObject<Presentation> implements ICommentAuthorCollection
```

Stellt eine Sammlung von Kommentarautoren dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [size()](#size--) | Gibt die tatsächlich in der Sammlung enthaltene Elementanzahl zurück. |
| [get_Item(int index)](#get-Item-int-) | Gibt das Element am angegebenen Index zurück. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | Fügt einen neuen Autor am Ende einer Sammlung hinzu. |
| [toArray()](#toArray--) | Erstellt und gibt ein Array mit allen Autoren zurück. |
| [findByName(String name)](#findByName-java.lang.String-) | Findet einen Autor in einer Sammlung nach Namen. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | Findet einen Autor in einer Sammlung nach Namen und Initialen. |
| [removeAt(int index)](#removeAt-int-) | Entfernt den Autor am angegebenen Index der Sammlung. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | Entfernt das erste Vorkommen des angegebenen Autors in einer Sammlung. |
| [clear()](#clear--) | Entfernt alle Autoren aus einer Sammlung. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiert alle Elemente aus der Sammlung in das angegebene Array. |
| [isSynchronized()](#isSynchronized--) | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert ist (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Gibt die Synchronisationswurzel zurück. |
### size() {#size--}
```
public final int size()
```


Gibt die tatsächlich in der Sammlung enthaltene Elementanzahl zurück. Nur lesbare int.

**Rückgabe:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ICommentAuthor get_Item(int index)
```


Gibt das Element am angegebenen Index zurück. Nur lesbare [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabe:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public final ICommentAuthor addAuthor(String name, String initials)
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
public final ICommentAuthor[] toArray()
```


Erstellt und gibt ein Array mit allen Autoren zurück.

**Rückgabe:**
com.aspose.slides.ICommentAuthor[] - Array von [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public final ICommentAuthor[] findByName(String name)
```


Findet einen Autor in einer Sammlung nach Namen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name eines Autors zum Suchen. |

**Rückgabe:**
com.aspose.slides.ICommentAuthor[] - Autor oder null.
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public final ICommentAuthor[] findByNameAndInitials(String name, String initials)
```


Findet einen Autor in einer Sammlung nach Namen und Initialen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name eines Autors zum Suchen. |
| initials | java.lang.String | Initialen eines Autors zum Suchen. |

**Rückgabe:**
com.aspose.slides.ICommentAuthor[] - Autor oder null.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Entfernt den Autor am angegebenen Index der Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index des zu entfernenden Elements. |

### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public final void remove(ICommentAuthor author)
```


Entfernt das erste Vorkommen des angegebenen Autors in einer Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Der zu entfernende Autor aus einer Sammlung. |

### clear() {#clear--}
```
public final void clear()
```


Entfernt alle Autoren aus einer Sammlung.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iterator()
```


Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - Ein IGenericEnumerator, der zum Durchlaufen der Sammlung verwendet werden kann.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iteratorJava()
```


Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - Ein java.util.Iterator für die gesamte Sammlung.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopiert alle Elemente aus der Sammlung in das angegebene Array.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Zielarray. |
| index | int | Startindex im Zielarray. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert ist (thread-safe). Nur lesbare boolean.

**Rückgabe:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Gibt die Synchronisationswurzel zurück. Nur lesbare Object.

**Rückgabe:**
java.lang.Object