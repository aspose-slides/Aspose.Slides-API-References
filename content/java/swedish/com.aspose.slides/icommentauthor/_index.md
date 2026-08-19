---
title: ICommentAuthor
second_title: Aspose.Slides for Java API-referens
description: Representerar en författare av kommentarer.
type: docs
url: /sv/com.aspose.slides/icommentauthor/
---```
public interface ICommentAuthor
```

Representerar en författare av kommentarer.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getName()](#getName--) | Returnerar eller anger författarens namn. |
| [setName(String value)](#setName-java.lang.String-) | Returnerar eller anger författarens namn. |
| [getInitials()](#getInitials--) | Returnerar eller anger författarens initialer. |
| [setInitials(String value)](#setInitials-java.lang.String-) | Returnerar eller anger författarens initialer. |
| [getComments()](#getComments--) | Returnerar samlingen av kommentarer som gjorts av denna författare. |
| [remove()](#remove--) | Tar bort författaren från föräldrakollektionen. |
### getName() {#getName--}
```
public abstract String getName()
```


Returnerar eller anger författarens namn. Läs/skriv String.

**Returnerar:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Returnerar eller anger författarens namn. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getInitials() {#getInitials--}
```
public abstract String getInitials()
```


Returnerar eller anger författarens initialer. Läs/skriv String.

**Returnerar:**
java.lang.String
### setInitials(String value) {#setInitials-java.lang.String-}
```
public abstract void setInitials(String value)
```


Returnerar eller anger författarens initialer. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public abstract ICommentCollection getComments()
```


Returnerar samlingen av kommentarer som gjorts av denna författare. Skrivskyddad [ICommentCollection](../../com.aspose.slides/icommentcollection).

**Returnerar:**
[ICommentCollection](../../com.aspose.slides/icommentcollection)
### remove() {#remove--}
```
public abstract void remove()
```


Tar bort författaren från föräldrakollektionen.