---
title: ICommentAuthorCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av kommentarsförfattare.
type: docs
url: /sv/com.aspose.slides/icommentauthorcollection/
---
**Alla implementerade gränssnitt:**
com.aspose.slides.IGenericCollection
```
public interface ICommentAuthorCollection extends IGenericCollection<ICommentAuthor>
```

Representerar en samling av kommentarsförfattare.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Hämtar elementet på det angivna indexet. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | Lägg till ny författare i slutet av en samling. |
| [toArray()](#toArray--) | Skapar och returnerar en array med alla författare. |
| [findByName(String name)](#findByName-java.lang.String-) | Hitta författare i en samling med namn. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | Hitta författare i en samling med namn och initialer. |
| [removeAt(int index)](#removeAt-int-) | Tar bort författaren på det angivna indexet i samlingen. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | Tar bort den första förekomsten av den angivna författaren i en samling. |
| [clear()](#clear--) | Tar bort alla författare från en samling. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICommentAuthor get_Item(int index)
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
public abstract ICommentAuthor addAuthor(String name, String initials)
```

Lägg till ny författare i slutet av en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namn på en ny författare. |
| initials | java.lang.String | Initialer för en ny författare. |

**Returnerar:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - Ny [ICommentAuthor](../../com.aspose.slides/icommentauthor)-objekt.
### toArray() {#toArray--}
```
public abstract ICommentAuthor[] toArray()
```

Skapar och returnerar en array med alla författare.

**Returnerar:**
com.aspose.slides.ICommentAuthor[] - Array av [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public abstract ICommentAuthor[] findByName(String name)
```

Hitta författare i en samling med namn.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namn på en författare att hitta. |

**Returnerar:**
com.aspose.slides.ICommentAuthor[] - Författare eller null.
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor[] findByNameAndInitials(String name, String initials)
```

Hitta författare i en samling med namn och initialer.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namn på en författare att hitta. |
| initials | java.lang.String | Initialer på en författare att hitta. |

**Returnerar:**
com.aspose.slides.ICommentAuthor[] - Författare eller null.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Tar bort författaren på det angivna indexet i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Nollbaserat index för elementet som ska tas bort. |

### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public abstract void remove(ICommentAuthor author)
```

Tar bort den första förekomsten av den angivna författaren i en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Författaren som ska tas bort från en samling. |

### clear() {#clear--}
```
public abstract void clear()
```

Tar bort alla författare från en samling.