---
title: ICommentAuthor
second_title: Aspose.Slides for Android via Java API Reference
description: Egy megjegyzés szerzőjét reprezentálja.
type: docs
url: /hu/com.aspose.slides/icommentauthor/
---```
public interface ICommentAuthor
```

Egy megjegyzés szerzőjét reprezentálja.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getName()](#getName--) | Visszaadja vagy beállítja a szerző nevét. |
| [setName(String value)](#setName-java.lang.String-) | Visszaadja vagy beállítja a szerző nevét. |
| [getInitials()](#getInitials--) | Visszaadja vagy beállítja a szerző kezdőbetűit. |
| [setInitials(String value)](#setInitials-java.lang.String-) | Visszaadja vagy beállítja a szerző kezdőbetűit. |
| [getComments()](#getComments--) | Visszaadja a szerző által írt megjegyzések gyűjteményét. |
| [remove()](#remove--) | Eltávolítja a szerzőt a szülő gyűjteményből. |
### getName() {#getName--}
```
public abstract String getName()
```


Visszaadja vagy beállítja a szerző nevét. Olvasás/írás String.

**Visszatér:**  
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Visszaadja vagy beállítja a szerző nevét. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getInitials() {#getInitials--}
```
public abstract String getInitials()
```


Visszaadja vagy beállítja a szerző kezdőbetűit. Olvasás/írás String.

**Visszatér:**  
java.lang.String
### setInitials(String value) {#setInitials-java.lang.String-}
```
public abstract void setInitials(String value)
```


Visszaadja vagy beállítja a szerző kezdőbetűit. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getComments() {#getComments--}
```
public abstract ICommentCollection getComments()
```


Visszaadja a szerző által írt megjegyzések gyűjteményét. Csak olvasható [ICommentCollection](../../com.aspose.slides/icommentcollection).

**Visszatér:**  
[ICommentCollection](../../com.aspose.slides/icommentcollection)
### remove() {#remove--}
```
public abstract void remove()
```


Eltávolítja a szerzőt a szülő gyűjteményből.