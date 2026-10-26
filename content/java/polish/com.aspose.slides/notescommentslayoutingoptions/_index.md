---
title: NotesCommentsLayoutingOptions
second_title: Aspose.Slides dla Java – Dokumentacja API
description: Udostępnia opcje kontrolujące wygląd układu notatek i komentarzy w wyeksportowanym dokumencie.
type: docs
url: /pl/com.aspose.slides/notescommentslayoutingoptions/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
```
public class NotesCommentsLayoutingOptions implements ISlidesLayoutOptions
```

Udostępnia opcje kontrolujące wygląd układu notatek i komentarzy w wyeksportowanym dokumencie.

## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [NotesCommentsLayoutingOptions()](#NotesCommentsLayoutingOptions--) | Konstruktor domyślny. |

## Metody

| Metoda | Opis |
| --- | --- |
| [getShowCommentsByNoAuthor()](#getShowCommentsByNoAuthor--) | Pobiera lub ustawia widoczność komentarzy bez autora. |
| [setShowCommentsByNoAuthor(boolean value)](#setShowCommentsByNoAuthor-boolean-) | Pobiera lub ustawia widoczność komentarzy bez autora. |
| [getNotesPosition()](#getNotesPosition--) | Pobiera lub ustawia pozycję notatek na stronie. |
| [setNotesPosition(int value)](#setNotesPosition-int-) | Pobiera lub ustawia pozycję notatek na stronie. |
| [getCommentsPosition()](#getCommentsPosition--) | Pobiera lub ustawia pozycję komentarzy na stronie. |
| [setCommentsPosition(int value)](#setCommentsPosition-int-) | Pobiera lub ustawia pozycję komentarzy na stronie. |
| [getCommentsAreaColor()](#getCommentsAreaColor--) | Pobiera lub ustawia kolor obszaru komentarzy (dotyczy tylko, gdy komentarze są wyświetlane po prawej). |
| [setCommentsAreaColor(Color value)](#setCommentsAreaColor-java.awt.Color-) | Pobiera lub ustawia kolor obszaru komentarzy (dotyczy tylko, gdy komentarze są wyświetlane po prawej). |
| [getCommentsAreaWidth()](#getCommentsAreaWidth--) | Pobiera lub ustawia szerokość obszaru wyjściowego komentarzy w pikselach (dotyczy tylko, gdy komentarze są wyświetlane po prawej). |
| [setCommentsAreaWidth(int value)](#setCommentsAreaWidth-int-) | Pobiera lub ustawia szerokość obszaru wyjściowego komentarzy w pikselach (dotyczy tylko, gdy komentarze są wyświetlane po prawej). |

### NotesCommentsLayoutingOptions() {#NotesCommentsLayoutingOptions--}
```
public NotesCommentsLayoutingOptions()
```

Konstruktor domyślny.

### getShowCommentsByNoAuthor() {#getShowCommentsByNoAuthor--}
```
public final boolean getShowCommentsByNoAuthor()
```

Pobiera lub ustawia widoczność komentarzy bez autora. Jeśli **true**, komentarze będą wyświetlane. (Dotyczy tylko, gdy komentarze są wyświetlane).

--------------------

Domyślna wartość to **false**.

**Zwraca:**
boolean

### setShowCommentsByNoAuthor(boolean value) {#setShowCommentsByNoAuthor-boolean-}
```
public final void setShowCommentsByNoAuthor(boolean value)
```

Pobiera lub ustawia widoczność komentarzy bez autora. Jeśli **true**, komentarze będą wyświetlane. (Dotyczy tylko, gdy komentarze są wyświetlane).

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

Domyślnie jest **NotesPositions.None**.

**Zwraca:**
int

### setNotesPosition(int value) {#setNotesPosition-int-}
```
public final void setNotesPosition(int value)
```

Pobiera lub ustawia pozycję notatek na stronie.

--------------------

Domyślnie jest **NotesPositions.None**.

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

Domyślnie jest **CommentsPositions.None**.

**Zwraca:**
int

### setCommentsPosition(int value) {#setCommentsPosition-int-}
```
public final void setCommentsPosition(int value)
```

Pobiera lub ustawia pozycję komentarzy na stronie.

--------------------

Domyślnie jest **CommentsPositions.None**.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getCommentsAreaColor() {#getCommentsAreaColor--}
```
public final Color getCommentsAreaColor()
```

Pobiera lub ustawia kolor obszaru komentarzy (dotyczy tylko, gdy komentarze są wyświetlane po prawej).

--------------------

Domyślnie jest **Color.SkyBlue**.

**Zwraca:**
java.awt.Color

### setCommentsAreaColor(Color value) {#setCommentsAreaColor-java.awt.Color-}
```
public final void setCommentsAreaColor(Color value)
```

Pobiera lub ustawia kolor obszaru komentarzy (dotyczy tylko, gdy komentarze są wyświetlane po prawej).

--------------------

Domyślnie jest **Color.SkyBlue**.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.awt.Color |  |

### getCommentsAreaWidth() {#getCommentsAreaWidth--}
```
public final int getCommentsAreaWidth()
```

Pobiera lub ustawia szerokość obszaru wyjściowego komentarzy w pikselach (dotyczy tylko, gdy komentarze są wyświetlane po prawej).

--------------------

Minimalna i domyślna wartość to **150**.

**Zwraca:**
int

### setCommentsAreaWidth(int value) {#setCommentsAreaWidth-int-}
```
public final void setCommentsAreaWidth(int value)
```

Pobiera lub ustawia szerokość obszaru wyjściowego komentarzy w pikselach (dotyczy tylko, gdy komentarze są wyświetlane po prawej).

--------------------

Minimalna i domyślna wartość to **150**.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |