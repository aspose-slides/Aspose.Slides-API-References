---
title: NotesCommentsLayoutingOptions
second_title: Aspose.Slides Java API referencia
description: Lehetőségeket biztosít a megjegyzések és kommentek elrendezésének megjelenésének szabályozásához az exportált dokumentumban.
type: docs
url: /hu/com.aspose.slides/notescommentslayoutingoptions/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
```
public class NotesCommentsLayoutingOptions implements ISlidesLayoutOptions
```

Lehetőségeket biztosít a megjegyzések és kommentek megjelenésének elrendezéséhez az exportált dokumentumban.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [NotesCommentsLayoutingOptions()](#NotesCommentsLayoutingOptions--) | Alapértelmezett konstruktor. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getShowCommentsByNoAuthor()](#getShowCommentsByNoAuthor--) | Lekérdezi vagy beállítja a szerző nélküli kommentek láthatóságát. |
| [setShowCommentsByNoAuthor(boolean value)](#setShowCommentsByNoAuthor-boolean-) | Lekérdezi vagy beállítja a szerző nélküli kommentek láthatóságát. |
| [getNotesPosition()](#getNotesPosition--) | Lekérdezi vagy beállítja a feljegyzések pozícióját az oldalon. |
| [setNotesPosition(int value)](#setNotesPosition-int-) | Lekérdezi vagy beállítja a feljegyzések pozícióját az oldalon. |
| [getCommentsPosition()](#getCommentsPosition--) | Lekérdezi vagy beállítja a kommentek pozícióját az oldalon. |
| [setCommentsPosition(int value)](#setCommentsPosition-int-) | Lekérdezi vagy beállítja a kommentek pozícióját az oldalon. |
| [getCommentsAreaColor()](#getCommentsAreaColor--) | Lekérdezi vagy beállítja a kommentek területének színét (csak akkor érvényes, ha a kommentek jobbra vannak megjelenítve). |
| [setCommentsAreaColor(Color value)](#setCommentsAreaColor-java.awt.Color-) | Lekérdezi vagy beállítja a kommentek területének színét (csak akkor érvényes, ha a kommentek jobbra vannak megjelenítve). |
| [getCommentsAreaWidth()](#getCommentsAreaWidth--) | Lekérdezi vagy beállítja a komment kimeneti területének szélességét pixelben (csak akkor érvényes, ha a kommentek jobbra vannak megjelenítve). |
| [setCommentsAreaWidth(int value)](#setCommentsAreaWidth-int-) | Lekérdezi vagy beállítja a komment kimeneti területének szélességét pixelben (csak akkor érvényes, ha a kommentek jobbra vannak megjelenítve). |
### NotesCommentsLayoutingOptions() {#NotesCommentsLayoutingOptions--}
```
public NotesCommentsLayoutingOptions()
```

Alapértelmezett konstruktor.

### getShowCommentsByNoAuthor() {#getShowCommentsByNoAuthor--}
```
public final boolean getShowCommentsByNoAuthor()
```

Lekérdezi vagy beállítja a szerző nélküli kommentek láthatóságát. Ha true, akkor a kommentek megjelennek. (Csak akkor érvényes, ha a kommentek megjelennek.)

--------------------

Alapértelmezett érték **false**.

**Visszatér:**  
boolean
### setShowCommentsByNoAuthor(boolean value) {#setShowCommentsByNoAuthor-boolean-}
```
public final void setShowCommentsByNoAuthor(boolean value)
```

Lekérdezi vagy beállítja a szerző nélküli kommentek láthatóságát. Ha true, akkor a kommentek megjelennek. (Csak akkor érvényes, ha a kommentek megjelennek.)

--------------------

Alapértelmezett érték **false**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getNotesPosition() {#getNotesPosition--}
```
public final int getNotesPosition()
```

Lekérdezi vagy beállítja a feljegyzések pozícióját az oldalon.

--------------------

Alapértelmezett érték **NotesPositions.None**.

**Visszatér:**  
int
### setNotesPosition(int value) {#setNotesPosition-int-}
```
public final void setNotesPosition(int value)
```

Lekérdezi vagy beállítja a feljegyzések pozícióját az oldalon.

--------------------

Alapértelmezett érték **NotesPositions.None**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getCommentsPosition() {#getCommentsPosition--}
```
public final int getCommentsPosition()
```

Lekérdezi vagy beállítja a kommentek pozícióját az oldalon.

--------------------

Alapértelmezett érték **CommentsPositions.None**.

**Visszatér:**  
int
### setCommentsPosition(int value) {#setCommentsPosition-int-}
```
public final void setCommentsPosition(int value)
```

Lekérdezi vagy beállítja a kommentek pozícióját az oldalon.

--------------------

Alapértelmezett érték **CommentsPositions.None**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getCommentsAreaColor() {#getCommentsAreaColor--}
```
public final Color getCommentsAreaColor()
```

Lekérdezi vagy beállítja a kommentek területének színét (csak akkor érvényes, ha a kommentek jobbra vannak megjelenítve).

--------------------

Alapértelmezett érték **Color.SkyBlue**.

**Visszatér:**  
java.awt.Color
### setCommentsAreaColor(Color value) {#setCommentsAreaColor-java.awt.Color-}
```
public final void setCommentsAreaColor(Color value)
```

Lekérdezi vagy beállítja a kommentek területének színét (csak akkor érvényes, ha a kommentek jobbra vannak megjelenítve).

--------------------

Alapértelmezett érték **Color.SkyBlue**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.awt.Color |  |
### getCommentsAreaWidth() {#getCommentsAreaWidth--}
```
public final int getCommentsAreaWidth()
```

Lekérdezi vagy beállítja a komment kimeneti területének szélességét pixelben (csak akkor érvényes, ha a kommentek jobbra vannak megjelenítve).

--------------------

Minimális és alapértelmezett érték **150**.

**Visszatér:**  
int
### setCommentsAreaWidth(int value) {#setCommentsAreaWidth-int-}
```
public final void setCommentsAreaWidth(int value)
```

Lekérdezi vagy beállítja a komment kimeneti területének szélességét pixelben (csak akkor érvényes, ha a kommentek jobbra vannak megjelenítve).

--------------------

Minimális és alapértelmezett érték **150**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |