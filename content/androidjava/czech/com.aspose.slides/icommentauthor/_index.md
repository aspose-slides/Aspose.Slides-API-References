---
title: ICommentAuthor
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an author of comments.
type: docs
url: /cs/com.aspose.slides/icommentauthor/
---```
public interface ICommentAuthor
```

Reprezentuje autora komentářů.
## Metody

| Metoda | Popis |
| --- | --- |
| [getName()](#getName--) | Vrací nebo nastavuje jméno autora. |
| [setName(String value)](#setName-java.lang.String-) | Vrací nebo nastavuje jméno autora. |
| [getInitials()](#getInitials--) | Vrací nebo nastavuje iniciály autora. |
| [setInitials(String value)](#setInitials-java.lang.String-) | Vrací nebo nastavuje iniciály autora. |
| [getComments()](#getComments--) | Vrací kolekci komentářů vytvořených tímto autorem. |
| [remove()](#remove--) | Odstraní autora z nadřazené kolekce. |
### getName() {#getName--}
```
public abstract String getName()
```


Vrací nebo nastavuje jméno autora. Čtení/zápis String.

**Vrací:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Vrací nebo nastavuje jméno autora. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getInitials() {#getInitials--}
```
public abstract String getInitials()
```


Vrací nebo nastavuje iniciály autora. Čtení/zápis String.

**Vrací:**
java.lang.String
### setInitials(String value) {#setInitials-java.lang.String-}
```
public abstract void setInitials(String value)
```


Vrací nebo nastavuje iniciály autora. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public abstract ICommentCollection getComments()
```


Vrací kolekci komentářů vytvořených tímto autorem. Pouze pro čtení [ICommentCollection](../../com.aspose.slides/icommentcollection).

**Vrací:**
[ICommentCollection](../../com.aspose.slides/icommentcollection)
### remove() {#remove--}
```
public abstract void remove()
```


Odstraní autora z nadřazené kolekce.