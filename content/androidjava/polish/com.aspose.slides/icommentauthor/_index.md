---
title: ICommentAuthor
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an author of comments.
type: docs
url: /pl/com.aspose.slides/icommentauthor/
---```
public interface ICommentAuthor
```

Reprezentuje autora komentarzy.
## Metody

| Metoda | Opis |
| --- | --- |
| [getName()](#getName--) | Zwraca lub ustawia nazwę autora. |
| [setName(String value)](#setName-java.lang.String-) | Zwraca lub ustawia nazwę autora. |
| [getInitials()](#getInitials--) | Zwraca lub ustawia inicjały autora. |
| [setInitials(String value)](#setInitials-java.lang.String-) | Zwraca lub ustawia inicjały autora. |
| [getComments()](#getComments--) | Zwraca kolekcję komentarzy utworzonych przez tego autora. |
| [remove()](#remove--) | Usuwa autora z kolekcji nadrzędnej. |
### getName() {#getName--}
```
public abstract String getName()
```


Zwraca lub ustawia nazwę autora. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Zwraca lub ustawia nazwę autora. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |
### getInitials() {#getInitials--}
```
public abstract String getInitials()
```


Zwraca lub ustawia inicjały autora. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setInitials(String value) {#setInitials-java.lang.String-}
```
public abstract void setInitials(String value)
```


Zwraca lub ustawia inicjały autora. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |
### getComments() {#getComments--}
```
public abstract ICommentCollection getComments()
```


Zwraca kolekcję komentarzy utworzonych przez tego autora. Tylko do odczytu [ICommentCollection](../../com.aspose.slides/icommentcollection).

**Zwraca:**
[ICommentCollection](../../com.aspose.slides/icommentcollection)
### remove() {#remove--}
```
public abstract void remove()
```


Usuwa autora z kolekcji nadrzędnej.