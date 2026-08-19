---
title: CommentAuthorCollection
second_title: Aspose.Slides för Java API-referens
description: Representerar en samling av kommentarsförfattare.
type: docs
url: /sv/com.aspose.slides/commentauthorcollection/
---
**Arv:**
java.lang.Object, com.aspose.slides.DomObject

**Alla implementerade gränssnitt:**
[com.aspose.slides.ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
```
public final class CommentAuthorCollection extends DomObject<Presentation> implements ICommentAuthorCollection
```

Representerar en samling av kommentarsförfattare.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [size()](#size--) | Hämtar antalet element som faktiskt finns i samlingen. |
| [get_Item(int index)](#get-Item-int-) | Hämtar elementet på det angivna indexet. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | Lägg till ny författare i slutet av en samling. |
| [toArray()](#toArray--) | Skapar och returnerar en array med alla författare. |
| [findByName(String name)](#findByName-java.lang.String-) | Hitta författare i en samling efter namn. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | Hitta författare i en samling efter namn och initialer. |
| [removeAt(int index)](#removeAt-int-) | Tar bort författaren på det angivna indexet i samlingen. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | Tar bort den första förekomsten av den angivna författaren i en samling. |
| [clear()](#clear--) | Tar bort alla författare från en samling. |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [iteratorJava()](#iteratorJava--) | Returnerar en java-iteratör för hela samlingen. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopierar alla element från samlingen till den angivna arrayen. |
| [isSynchronized()](#isSynchronized--) | Returnerar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). |
| [getSyncRoot()](#getSyncRoot--) | Returnerar ett synkroniseringsrot. |
### size() {#size--}
```
public final int size()
```


Hämtar antalet element som faktiskt finns i samlingen. Skrivskyddad int.

**Returnerar:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ICommentAuthor get_Item(int index)
```


Hämtar elementet på det angivna indexet. Skrivskyddad [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public final ICommentAuthor addAuthor(String name, String initials)
```


Lägg till ny författare i slutet av en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namn på den nya författaren. |
| initials | java.lang.String | Initialer för den nya författaren. |

**Returnerar:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - Nytt [ICommentAuthor](../../com.aspose.slides/icommentauthor)-objekt.
### toArray() {#toArray--}
```
public final ICommentAuthor[] toArray()
```


Skapar och returnerar en array med alla författare.

**Returnerar:**
com.aspose.slides.ICommentAuthor[] - Array av [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public final ICommentAuthor[] findByName(String name)
```


Hitta författare i en samling efter namn.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namn på en författare att hitta. |

**Returnerar:**
com.aspose.slides.ICommentAuthor[] - Författare eller null.
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public final ICommentAuthor[] findByNameAndInitials(String name, String initials)
```


Hitta författare i en samling efter namn och initialer.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namn på en författare att hitta. |
| initials | java.lang.String | Initialer på en författare att hitta. |

**Returnerar:**
com.aspose.slides.ICommentAuthor[] - Författare eller null.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Tar bort författaren på det angivna indexet i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet för elementet som ska tas bort. |

### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public final void remove(ICommentAuthor author)
```


Tar bort den första förekomsten av den angivna författaren i en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Författaren att ta bort från en samling. |

### clear() {#clear--}
```
public final void clear()
```


Tar bort alla författare från en samling.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iterator()
```


Returnerar en enumerator som itererar genom samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - En IGenericEnumerator som kan användas för att iterera genom samlingen.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iteratorJava()
```


Returnerar en java-iteratör för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - En java.util.Iterator för hela samlingen.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopierar alla element från samlingen till den angivna arrayen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Målarray. |
| index | int | Startindex i målarry. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Returnerar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). Skrivskyddad boolean.

**Returnerar:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Returnerar ett synkroniseringsrot. Skrivskyddad Object.

**Returnerar:**
java.lang.Object