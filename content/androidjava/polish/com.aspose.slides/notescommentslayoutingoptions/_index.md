---
title: NotesCommentsLayoutingOptions
second_title: Aspose.Slides dla Androida poprzez odniesienie do Java API
description: Udostępnia opcje, które sterują wyglądem układu notatek i komentarzy w wyeksportowanym dokumencie.
type: docs
url: /pl/com.aspose.slides/notescommentslayoutingoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
```
public class NotesCommentsLayoutingOptions implements ISlidesLayoutOptions
```

Udostępnia opcje kontrolujące wygląd układu notatek i komentarzy w wyeksportowanym dokumencie.

## Konstruktorzy

| Konstruktor | Opis |
| --- | --- |
| [NotesCommentsLayoutingOptions()](#NotesCommentsLayoutingOptions--) | Konstruktor domyślny. |

## Metody

| Metoda | Opis |
| --- | --- |
| [getShowCommentsByNoAuthor()](#getShowCommentsByNoAuthor--) | Pobiera lub ustawia widoczność komentarzy, które nie mają autora. |
| [setShowCommentsByNoAuthor(boolean value)](#setShowCommentsByNoAuthor-boolean-) | Pobiera lub ustawia widoczność komentarzy, które nie mają autora. |
| [getNotesPosition()](#getNotesPosition--) | Pobiera lub ustawia pozycję notatek na stronie. |
| [setNotesPosition(int value)](#setNotesPosition-int-) | Pobiera lub ustawia pozycję notatek na stronie. |
| [getCommentsPosition()](#getCommentsPosition--) | Pobiera lub ustawia pozycję komentarzy na stronie. |
| [setCommentsPosition(int value)](#setCommentsPosition-int-) | Pobiera lub ustawia pozycję komentarzy na stronie. |
| [getCommentsAreaColor()](#getCommentsAreaColor--) | Pobiera lub ustawia kolor obszaru komentarzy (Dotyczy tylko, gdy komentarze są wyświetlane po prawej stronie). |
| [setCommentsAreaColor(Integer value)](#setCommentsAreaColor-java.lang.Integer-) | Pobiera lub ustawia kolor obszaru komentarzy (Dotyczy tylko, gdy komentarze są wyświetlane po prawej stronie). |
| [getCommentsAreaWidth()](#getCommentsAreaWidth--) | Pobiera lub ustawia szerokość obszaru wyjściowego komentarzy w pikselach (Dotyczy tylko, gdy komentarze są wyświetlane po prawej stronie). |
| [setCommentsAreaWidth(int value)](#setCommentsAreaWidth-int-) | Pobiera lub ustawia szerokość obszaru wyjściowego komentarzy w pikselach (Dotyczy tylko, gdy komentarze są wyświetlane po prawej stronie). |

### NotesCommentsLayoutingOptions() {#NotesCommentsLayoutingOptions--}
```
public NotesCommentsLayoutingOptions()
```

Konstruktor domyślny.

### getShowCommentsByNoAuthor() {#getShowCommentsByNoAuthor--}
```
public final boolean getShowCommentsByNoAuthor()
```

Pobiera lub ustawia widoczność komentarzy, które nie mają autora. Jeśli true, komentarze zostaną wyświetlone. (Dotyczy tylko, gdy komentarze są wyświetlane).

--------------------

Domyślna wartość to **false**.

**Zwraca:**
boolean

### setShowCommentsByNoAuthor(boolean value) {#setShowCommentsByNoAuthor-boolean-}
```
public final void setShowCommentsByNoAuthor(boolean value)
```

Pobiera lub ustawia widoczność komentarzy, które nie mają autora. Jeśli true, komentarze zostaną wyświetlone. (Dotyczy tylko, gdy komentarze są wyświetlane).

--------------------

Domyślna wartość to **false**.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getNotesPosition() {#getNotesPosition--}
```
public final int getNotesPosition()
```

Pobiera lub ustawia pozycję notatek na stronie.

--------------------

Domyślne jest **NotesPositions.None**.

**Zwraca:**
int

### setNotesPosition(int value) {#setNotesPosition-int-}
```
public final void setNotesPosition(int value)
```

Pobiera lub ustawia pozycję notatek na stronie.

--------------------

Domyślne jest **NotesPositions.None**.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getCommentsPosition() {#getCommentsPosition--}
```
public final int getCommentsPosition()
```

Pobiera lub ustawia pozycję komentarzy na stronie.

--------------------

Domyślne jest **CommentsPositions.None**.

**Zwraca:**
int

### setCommentsPosition(int value) {#setCommentsPosition-int-}
```
public final void setCommentsPosition(int value)
```

Pobiera lub ustawia pozycję komentarzy na stronie.

--------------------

Domyślne jest **CommentsPositions.None**.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getCommentsAreaColor() {#getCommentsAreaColor--}
```
public final Integer getCommentsAreaColor()
```

Pobiera lub ustawia kolor obszaru komentarzy (Dotyczy tylko, gdy komentarze są wyświetlane po prawej stronie).

--------------------

Domyślna wartość to **SkyBlue**.

**Zwraca:**
java.lang.Integer

### setCommentsAreaColor(Integer value) {#setCommentsAreaColor-java.lang.Integer-}
```
public final void setCommentsAreaColor(Integer value)
```

Pobiera lub ustawia kolor obszaru komentarzy (Dotyczy tylko, gdy komentarze są wyświetlane po prawej stronie).

--------------------

Domyślna wartość to **SkyBlue**.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getCommentsAreaWidth() {#getCommentsAreaWidth--}
```
public final int getCommentsAreaWidth()
```

Pobiera lub ustawia szerokość obszaru wyjściowego komentarzy w pikselach (Dotyczy tylko, gdy komentarze są wyświetlane po prawej stronie).

--------------------

Minimalna i domyślna wartość to **150**.

**Zwraca:**
int

### setCommentsAreaWidth(int value) {#setCommentsAreaWidth-int-}
```
public final void setCommentsAreaWidth(int value)
```

Pobiera lub ustawia szerokość obszaru wyjściowego komentarzy w pikselach (Dotyczy tylko, gdy komentarze są wyświetlane po prawej stronie).

--------------------

Minimalna i domyślna wartość to **150**.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |