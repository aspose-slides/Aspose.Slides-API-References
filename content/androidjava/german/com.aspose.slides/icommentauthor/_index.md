---
title: ICommentAuthor
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt einen Autor von Kommentaren dar.
type: docs
url: /de/com.aspose.slides/icommentauthor/
---```
public interface ICommentAuthor
```

Stellt einen Autor von Kommentaren dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getName()](#getName--) | Liefert oder setzt den Namen des Autors. |
| [setName(String value)](#setName-java.lang.String-) | Liefert oder setzt den Namen des Autors. |
| [getInitials()](#getInitials--) | Liefert oder setzt die Initialen des Autors. |
| [setInitials(String value)](#setInitials-java.lang.String-) | Liefert oder setzt die Initialen des Autors. |
| [getComments()](#getComments--) | Liefert die Sammlung von Kommentaren dieses Autors. |
| [remove()](#remove--) | Entfernt den Autor aus der übergeordneten Sammlung. |
### getName() {#getName--}
```
public abstract String getName()
```

Liefert oder setzt den Namen des Autors. Lese-/Schreib String.

**Rückgabe:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Liefert oder setzt den Namen des Autors. Lese-/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getInitials() {#getInitials--}
```
public abstract String getInitials()
```

Liefert oder setzt die Initialen des Autors. Lese-/Schreib String.

**Rückgabe:**
java.lang.String
### setInitials(String value) {#setInitials-java.lang.String-}
```
public abstract void setInitials(String value)
```

Liefert oder setzt die Initialen des Autors. Lese-/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getComments() {#getComments--}
```
public abstract ICommentCollection getComments()
```

Liefert die Sammlung von Kommentaren dieses Autors. Nur-Lesen [ICommentCollection](../../com.aspose.slides/icommentcollection).

**Rückgabe:**
[ICommentCollection](../../com.aspose.slides/icommentcollection)
### remove() {#remove--}
```
public abstract void remove()
```

Entfernt den Autor aus der übergeordneten Sammlung.