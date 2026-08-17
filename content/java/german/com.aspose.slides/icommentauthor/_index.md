---
title: ICommentAuthor
second_title: Aspose.Slides for Java API Reference
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
| [getName()](#getName--) | Gibt den Namen des Autors zurück oder legt ihn fest. |
| [setName(String value)](#setName-java.lang.String-) | Gibt den Namen des Autors zurück oder legt ihn fest. |
| [getInitials()](#getInitials--) | Gibt die Initialen des Autors zurück oder legt sie fest. |
| [setInitials(String value)](#setInitials-java.lang.String-) | Gibt die Initialen des Autors zurück oder legt sie fest. |
| [getComments()](#getComments--) | Gibt die Sammlung von Kommentaren zurück, die von diesem Autor erstellt wurden. |
| [remove()](#remove--) | Entfernt den Autor aus der übergeordneten Sammlung. |
### getName() {#getName--}
```
public abstract String getName()
```

Gibt den Namen des Autors zurück oder legt ihn fest. Lese-/Schreibzugriff String.

**Rückgabewert:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Gibt den Namen des Autors zurück oder legt ihn fest. Lese-/Schreibzugriff String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getInitials() {#getInitials--}
```
public abstract String getInitials()
```

Gibt die Initialen des Autors zurück oder legt sie fest. Lese-/Schreibzugriff String.

**Rückgabewert:**
java.lang.String
### setInitials(String value) {#setInitials-java.lang.String-}
```
public abstract void setInitials(String value)
```

Gibt die Initialen des Autors zurück oder legt sie fest. Lese-/Schreibzugriff String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getComments() {#getComments--}
```
public abstract ICommentCollection getComments()
```

Gibt die Sammlung von Kommentaren zurück, die von diesem Autor erstellt wurden. Nur-Lesezugriff [ICommentCollection](../../com.aspose.slides/icommentcollection).

**Rückgabewert:**
[ICommentCollection](../../com.aspose.slides/icommentcollection)
### remove() {#remove--}
```
public abstract void remove()
```

Entfernt den Autor aus der übergeordneten Sammlung.