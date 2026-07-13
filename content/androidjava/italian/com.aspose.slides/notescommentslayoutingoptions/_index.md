---
title: NotesCommentsLayoutingOptions
second_title: Aspose.Slides per Android via Riferimento API Java
description: Fornisce opzioni che controllano l'aspetto della disposizione di note e commenti nel documento esportato.
type: docs
url: /it/com.aspose.slides/notescommentslayoutingoptions/
---
**Ereditarietà:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
```
public class NotesCommentsLayoutingOptions implements ISlidesLayoutOptions
```

Fornisce opzioni che controllano l'aspetto della disposizione di note e commenti nel documento esportato.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [NotesCommentsLayoutingOptions()](#NotesCommentsLayoutingOptions--) | Costruttore predefinito. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getShowCommentsByNoAuthor()](#getShowCommentsByNoAuthor--) | Ottiene o imposta la visibilità dei commenti che non hanno un autore. |
| [setShowCommentsByNoAuthor(boolean value)](#setShowCommentsByNoAuthor-boolean-) | Ottiene o imposta la visibilità dei commenti che non hanno un autore. |
| [getNotesPosition()](#getNotesPosition--) | Ottiene o imposta la posizione delle note sulla pagina. |
| [setNotesPosition(int value)](#setNotesPosition-int-) | Ottiene o imposta la posizione delle note sulla pagina. |
| [getCommentsPosition()](#getCommentsPosition--) | Ottiene o imposta la posizione dei commenti sulla pagina. |
| [setCommentsPosition(int value)](#setCommentsPosition-int-) | Ottiene o imposta la posizione dei commenti sulla pagina. |
| [getCommentsAreaColor()](#getCommentsAreaColor--) | Ottiene o imposta il colore dell'area dei commenti (si applica solo se i commenti sono visualizzati a destra). |
| [setCommentsAreaColor(Integer value)](#setCommentsAreaColor-java.lang.Integer-) | Ottiene o imposta il colore dell'area dei commenti (si applica solo se i commenti sono visualizzati a destra). |
| [getCommentsAreaWidth()](#getCommentsAreaWidth--) | Ottiene o imposta la larghezza dell'area di output dei commenti in pixel (si applica solo se i commenti sono visualizzati a destra). |
| [setCommentsAreaWidth(int value)](#setCommentsAreaWidth-int-) | Ottiene o imposta la larghezza dell'area di output dei commenti in pixel (si applica solo se i commenti sono visualizzati a destra). |
### NotesCommentsLayoutingOptions() {#NotesCommentsLayoutingOptions--}
```
public NotesCommentsLayoutingOptions()
```

Costruttore predefinito.

### getShowCommentsByNoAuthor() {#getShowCommentsByNoAuthor--}
```
public final boolean getShowCommentsByNoAuthor()
```

Ottiene o imposta la visibilità dei commenti che non hanno un autore. Se true allora i commenti verranno visualizzati. (Si applica solo se i commenti sono visualizzati).

--------------------

Il valore predefinito è **false**.

**Restituisce:**
boolean
### setShowCommentsByNoAuthor(boolean value) {#setShowCommentsByNoAuthor-boolean-}
```
public final void setShowCommentsByNoAuthor(boolean value)
```

Ottiene o imposta la visibilità dei commenti che non hanno un autore. Se true allora i commenti verranno visualizzati. (Si applica solo se i commenti sono visualizzati).

--------------------

Il valore predefinito è **false**.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getNotesPosition() {#getNotesPosition--}
```
public final int getNotesPosition()
```

Ottiene o imposta la posizione delle note sulla pagina.

--------------------

Il valore predefinito è **NotesPositions.None**.

**Restituisce:**
int
### setNotesPosition(int value) {#setNotesPosition-int-}
```
public final void setNotesPosition(int value)
```

Ottiene o imposta la posizione delle note sulla pagina.

--------------------

Il valore predefinito è **NotesPositions.None**.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getCommentsPosition() {#getCommentsPosition--}
```
public final int getCommentsPosition()
```

Ottiene o imposta la posizione dei commenti sulla pagina.

--------------------

Il valore predefinito è **CommentsPositions.None**.

**Restituisce:**
int
### setCommentsPosition(int value) {#setCommentsPosition-int-}
```
public final void setCommentsPosition(int value)
```

Ottiene o imposta la posizione dei commenti sulla pagina.

--------------------

Il valore predefinito è **CommentsPositions.None**.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getCommentsAreaColor() {#getCommentsAreaColor--}
```
public final Integer getCommentsAreaColor()
```

Ottiene o imposta il colore dell'area dei commenti (si applica solo se i commenti sono visualizzati a destra).

--------------------

Il valore predefinito è **SkyBlue**.

**Restituisce:**
java.lang.Integer
### setCommentsAreaColor(Integer value) {#setCommentsAreaColor-java.lang.Integer-}
```
public final void setCommentsAreaColor(Integer value)
```

Ottiene o imposta il colore dell'area dei commenti (si applica solo se i commenti sono visualizzati a destra).

--------------------

Il valore predefinito è **SkyBlue**.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getCommentsAreaWidth() {#getCommentsAreaWidth--}
```
public final int getCommentsAreaWidth()
```

Ottiene o imposta la larghezza dell'area di output dei commenti in pixel (si applica solo se i commenti sono visualizzati a destra).

--------------------

Il valore minimo e predefinito è **150**.

**Restituisce:**
int
### setCommentsAreaWidth(int value) {#setCommentsAreaWidth-int-}
```
public final void setCommentsAreaWidth(int value)
```

Ottiene o imposta la larghezza dell'area di output dei commenti in pixel (si applica solo se i commenti sono visualizzati a destra).

--------------------

Il valore minimo e predefinito è **150**.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |