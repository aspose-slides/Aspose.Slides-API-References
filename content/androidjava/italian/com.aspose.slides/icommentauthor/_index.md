---
title: ICommentAuthor
second_title: Aspose.Slides for Android via Java API Reference
description: Rappresenta un autore dei commenti.
type: docs
url: /it/com.aspose.slides/icommentauthor/
---```
public interface ICommentAuthor
```

Rappresenta un autore dei commenti.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getName()](#getName--) | Restituisce o imposta il nome dell'autore. |
| [setName(String value)](#setName-java.lang.String-) | Restituisce o imposta il nome dell'autore. |
| [getInitials()](#getInitials--) | Restituisce o imposta le iniziali dell'autore. |
| [setInitials(String value)](#setInitials-java.lang.String-) | Restituisce o imposta le iniziali dell'autore. |
| [getComments()](#getComments--) | Restituisce la raccolta di commenti effettuati da questo autore. |
| [remove()](#remove--) | Rimuove l'autore dalla collezione padre. |
### getName() {#getName--}
```
public abstract String getName()
```

Restituisce o imposta il nome dell'autore. Lettura/scrittura String.

**Restituisce:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Restituisce o imposta il nome dell'autore. Lettura/scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |
### getInitials() {#getInitials--}
```
public abstract String getInitials()
```

Restituisce o imposta le iniziali dell'autore. Lettura/scrittura String.

**Restituisce:**
java.lang.String
### setInitials(String value) {#setInitials-java.lang.String-}
```
public abstract void setInitials(String value)
```

Restituisce o imposta le iniziali dell'autore. Lettura/scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |
### getComments() {#getComments--}
```
public abstract ICommentCollection getComments()
```

Restituisce la raccolta di commenti effettuati da questo autore. Sola lettura [ICommentCollection](../../com.aspose.slides/icommentcollection).

**Restituisce:**
[ICommentCollection](../../com.aspose.slides/icommentcollection)
### remove() {#remove--}
```
public abstract void remove()
```

Rimuove l'autore dalla collezione genitore.