---
title: NotesCommentsLayoutingOptions
second_title: Aspose.Slides pro Java - reference API
description: Poskytuje možnosti, které řídí vzhled rozložení poznámek a komentářů v exportovaném dokumentu.
type: docs
url: /cs/com.aspose.slides/notescommentslayoutingoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
```
public class NotesCommentsLayoutingOptions implements ISlidesLayoutOptions
```

Poskytuje možnosti, které řídí vzhled rozložení poznámek a komentářů v exportovaném dokumentu.
## Constructors

| Constructor | Description |
| --- | --- |
| [NotesCommentsLayoutingOptions()](#NotesCommentsLayoutingOptions--) | Výchozí konstruktor. |
## Methods

| Method | Description |
| --- | --- |
| [getShowCommentsByNoAuthor()](#getShowCommentsByNoAuthor--) | Získá nebo nastaví viditelnost komentářů, které nemají autora. |
| [setShowCommentsByNoAuthor(boolean value)](#setShowCommentsByNoAuthor-boolean-) | Získá nebo nastaví viditelnost komentářů, které nemají autora. |
| [getNotesPosition()](#getNotesPosition--) | Získá nebo nastaví pozici poznámek na stránce. |
| [setNotesPosition(int value)](#setNotesPosition-int-) | Získá nebo nastaví pozici poznámek na stránce. |
| [getCommentsPosition()](#getCommentsPosition--) | Získá nebo nastaví pozici komentářů na stránce. |
| [setCommentsPosition(int value)](#setCommentsPosition-int-) | Získá nebo nastaví pozici komentářů na stránce. |
| [getCommentsAreaColor()](#getCommentsAreaColor--) | Získá nebo nastaví barvu oblasti komentářů (Platí pouze pokud jsou komentáře zobrazeny vpravo). |
| [setCommentsAreaColor(Color value)](#setCommentsAreaColor-java.awt.Color-) | Získá nebo nastaví barvu oblasti komentářů (Platí pouze pokud jsou komentáře zobrazeny vpravo). |
| [getCommentsAreaWidth()](#getCommentsAreaWidth--) | Získá nebo nastaví šířku výstupní oblasti komentáře v pixelech (Platí pouze pokud jsou komentáře zobrazeny vpravo). |
| [setCommentsAreaWidth(int value)](#setCommentsAreaWidth-int-) | Získá nebo nastaví šířku výstupní oblasti komentáře v pixelech (Platí pouze pokud jsou komentáře zobrazeny vpravo). |
### NotesCommentsLayoutingOptions() {#NotesCommentsLayoutingOptions--}
```
public NotesCommentsLayoutingOptions()
```


Výchozí konstruktor.

### getShowCommentsByNoAuthor() {#getShowCommentsByNoAuthor--}
```
public final boolean getShowCommentsByNoAuthor()
```


Získá nebo nastaví viditelnost komentářů, které nemají autora. Pokud je true, pak budou komentáře zobrazeny. (Platí pouze pokud jsou komentáře zobrazeny).

--------------------

Výchozí hodnota je **false**.

**Návratová hodnota:**
boolean
### setShowCommentsByNoAuthor(boolean value) {#setShowCommentsByNoAuthor-boolean-}
```
public final void setShowCommentsByNoAuthor(boolean value)
```


Získá nebo nastaví viditelnost komentářů, které nemají autora. Pokud je true, pak budou komentáře zobrazeny. (Platí pouze pokud jsou komentáře zobrazeny).

--------------------

Výchozí hodnota je **false**.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getNotesPosition() {#getNotesPosition--}
```
public final int getNotesPosition()
```


Získá nebo nastaví pozici poznámek na stránce.

--------------------

Výchozí je **NotesPositions.None**.

**Návratová hodnota:**
int
### setNotesPosition(int value) {#setNotesPosition-int-}
```
public final void setNotesPosition(int value)
```


Získá nebo nastaví pozici poznámek na stránce.

--------------------

Výchozí je **NotesPositions.None**.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getCommentsPosition() {#getCommentsPosition--}
```
public final int getCommentsPosition()
```


Získá nebo nastaví pozici komentářů na stránce.

--------------------

Výchozí je **CommentsPositions.None**.

**Návratová hodnota:**
int
### setCommentsPosition(int value) {#setCommentsPosition-int-}
```
public final void setCommentsPosition(int value)
```


Získá nebo nastaví pozici komentářů na stránce.

--------------------

Výchozí je **CommentsPositions.None**.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getCommentsAreaColor() {#getCommentsAreaColor--}
```
public final Color getCommentsAreaColor()
```


Získá nebo nastaví barvu oblasti komentářů (Platí pouze pokud jsou komentáře zobrazeny vpravo).

--------------------

Výchozí je **Color.SkyBlue**.

**Návratová hodnota:**
java.awt.Color
### setCommentsAreaColor(Color value) {#setCommentsAreaColor-java.awt.Color-}
```
public final void setCommentsAreaColor(Color value)
```


Získá nebo nastaví barvu oblasti komentářů (Platí pouze pokud jsou komentáře zobrazeny vpravo).

--------------------

Výchozí je **Color.SkyBlue**.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Color |  |
### getCommentsAreaWidth() {#getCommentsAreaWidth--}
```
public final int getCommentsAreaWidth()
```


Získá nebo nastaví šířku výstupní oblasti komentáře v pixelech (Platí pouze pokud jsou komentáře zobrazeny vpravo).

--------------------

Minimální a výchozí hodnota je **150**.

**Návratová hodnota:**
int
### setCommentsAreaWidth(int value) {#setCommentsAreaWidth-int-}
```
public final void setCommentsAreaWidth(int value)
```


Získá nebo nastaví šířku výstupní oblasti komentáře v pixelech (Platí pouze pokud jsou komentáře zobrazeny vpravo).

--------------------

Minimální a výchozí hodnota je **150**.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |