---
title: NotesCommentsLayoutingOptions
second_title: Aspose.Slides pro Android prostřednictvím odkazu na Java API
description: Poskytuje možnosti, které řídí vzhled rozvržení poznámek a komentářů v exportovaném dokumentu.
type: docs
url: /cs/com.aspose.slides/notescommentslayoutingoptions/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
```
public class NotesCommentsLayoutingOptions implements ISlidesLayoutOptions
```

Poskytuje možnosti, které řídí vzhled rozvržení poznámek a komentářů v exportovaném dokumentu.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [NotesCommentsLayoutingOptions()](#NotesCommentsLayoutingOptions--) | Výchozí konstruktor. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getShowCommentsByNoAuthor()](#getShowCommentsByNoAuthor--) | Získá nebo nastaví viditelnost komentářů, které nemají autora. |
| [setShowCommentsByNoAuthor(boolean value)](#setShowCommentsByNoAuthor-boolean-) | Získá nebo nastaví viditelnost komentářů, které nemají autora. |
| [getNotesPosition()](#getNotesPosition--) | Získá nebo nastaví pozici poznámek na stránce. |
| [setNotesPosition(int value)](#setNotesPosition-int-) | Získá nebo nastaví pozici poznámek na stránce. |
| [getCommentsPosition()](#getCommentsPosition--) | Získá nebo nastaví pozici komentářů na stránce. |
| [setCommentsPosition(int value)](#setCommentsPosition-int-) | Získá nebo nastaví pozici komentářů na stránce. |
| [getCommentsAreaColor()](#getCommentsAreaColor--) | Získá nebo nastaví barvu oblasti komentářů (platí pouze, pokud jsou komentáře zobrazeny vpravo). |
| [setCommentsAreaColor(Integer value)](#setCommentsAreaColor-java.lang.Integer-) | Získá nebo nastaví barvu oblasti komentářů (platí pouze, pokud jsou komentáře zobrazeny vpravo). |
| [getCommentsAreaWidth()](#getCommentsAreaWidth--) | Získá nebo nastaví šířku výstupní oblasti komentářů v pixelech (platí pouze, pokud jsou komentáře zobrazeny vpravo). |
| [setCommentsAreaWidth(int value)](#setCommentsAreaWidth-int-) | Získá nebo nastaví šířku výstupní oblasti komentářů v pixelech (platí pouze, pokud jsou komentáře zobrazeny vpravo). |
### NotesCommentsLayoutingOptions() {#NotesCommentsLayoutingOptions--}
```
public NotesCommentsLayoutingOptions()
```

Výchozí konstruktor.

### getShowCommentsByNoAuthor() {#getShowCommentsByNoAuthor--}
```
public final boolean getShowCommentsByNoAuthor()
```

Získá nebo nastaví viditelnost komentářů, které nemají autora. Pokud je true, pak budou komentáře zobrazeny. (Platí pouze, pokud jsou komentáře zobrazeny).

--------------------

Výchozí hodnota je **false**.

**Vrací:**
boolean
### setShowCommentsByNoAuthor(boolean value) {#setShowCommentsByNoAuthor-boolean-}
```
public final void setShowCommentsByNoAuthor(boolean value)
```

Získá nebo nastaví viditelnost komentářů, které nemají autora. Pokud je true, pak budou komentáře zobrazeny. (Platí pouze, pokud jsou komentáře zobrazeny).

--------------------

Výchozí hodnota je **false**.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getNotesPosition() {#getNotesPosition--}
```
public final int getNotesPosition()
```

Získá nebo nastaví pozici poznámek na stránce.

--------------------

Výchozí hodnota je **NotesPositions.None**.

**Vrací:**
int
### setNotesPosition(int value) {#setNotesPosition-int-}
```
public final void setNotesPosition(int value)
```

Získá nebo nastaví pozici poznámek na stránce.

--------------------

Výchozí hodnota je **NotesPositions.None**.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getCommentsPosition() {#getCommentsPosition--}
```
public final int getCommentsPosition()
```

Získá nebo nastaví pozici komentářů na stránce.

--------------------

Výchozí hodnota je **CommentsPositions.None**.

**Vrací:**
int
### setCommentsPosition(int value) {#setCommentsPosition-int-}
```
public final void setCommentsPosition(int value)
```

Získá nebo nastaví pozici komentářů na stránce.

--------------------

Výchozí hodnota je **CommentsPositions.None**.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getCommentsAreaColor() {#getCommentsAreaColor--}
```
public final Integer getCommentsAreaColor()
```

Získá nebo nastaví barvu oblasti komentářů (platí pouze, pokud jsou komentáře zobrazeny vpravo).

--------------------

Výchozí hodnota je **SkyBlue**.

**Vrací:**
java.lang.Integer
### setCommentsAreaColor(Integer value) {#setCommentsAreaColor-java.lang.Integer-}
```
public final void setCommentsAreaColor(Integer value)
```

Získá nebo nastaví barvu oblasti komentářů (platí pouze, pokud jsou komentáře zobrazeny vpravo).

--------------------

Výchozí hodnota je **SkyBlue**.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.Integer |  |
### getCommentsAreaWidth() {#getCommentsAreaWidth--}
```
public final int getCommentsAreaWidth()
```

Získá nebo nastaví šířku výstupní oblasti komentářů v pixelech (platí pouze, pokud jsou komentáře zobrazeny vpravo).

--------------------

Minimální a výchozí hodnota je **150**.

**Vrací:**
int
### setCommentsAreaWidth(int value) {#setCommentsAreaWidth-int-}
```
public final void setCommentsAreaWidth(int value)
```

Získá nebo nastaví šířku výstupní oblasti komentářů v pixelech (platí pouze, pokud jsou komentáře zobrazeny vpravo).

--------------------

Minimální a výchozí hodnota je **150**.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |