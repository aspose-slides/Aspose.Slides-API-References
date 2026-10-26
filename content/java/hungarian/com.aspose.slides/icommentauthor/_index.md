---
title: ICommentAuthor
second_title: Aspose.Slides for Java API Reference
description: A kommentek szerzőjét reprezentálja.
type: docs
url: /hu/com.aspose.slides/icommentauthor/
---```
public interface ICommentAuthor
```

A kommentek szerzőjét reprezentálja.
## Metódusok

| Method | Leírás |
| --- | --- |
| [getName()](#getName--) | Visszaadja vagy beállítja a szerző nevét. |
| [setName(String value)](#setName-java.lang.String-) | Visszaadja vagy beállítja a szerző nevét. |
| [getInitials()](#getInitials--) | Visszaadja vagy beállítja a szerző kezdeti betűit. |
| [setInitials(String value)](#setInitials-java.lang.String-) | Visszaadja vagy beállítja a szerző kezdeti betűit. |
| [getComments()](#getComments--) | Visszaadja az e szerző által írt kommentek gyűjteményét. |
| [remove()](#remove--) | Eltávolítja a szerzőt a szülő gyűjteményből. |
### getName() {#getName--}
```
public abstract String getName()
```

Visszaadja vagy beállítja a szerző nevét. Olvasás/írás String.

**Visszatérési érték:**
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

Visszaadja vagy beállítja a szerző kezdeti betűit. Olvasás/írás String.

**Visszatérési érték:**
java.lang.String
### setInitials(String value) {#setInitials-java.lang.String-}
```
public abstract void setInitials(String value)
```

Visszaadja vagy beállítja a szerző kezdeti betűit. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getComments() {#getComments--}
```
public abstract ICommentCollection getComments()
```

Visszaadja az e szerző által írt kommentek gyűjteményét. Csak olvasható [ICommentCollection](../../com.aspose.slides/icommentcollection).

**Visszatérési érték:**
[ICommentCollection](../../com.aspose.slides/icommentcollection)
### remove() {#remove--}
```
public abstract void remove()
```

Eltávolítja a szerzőt a szülő gyűjteményből.