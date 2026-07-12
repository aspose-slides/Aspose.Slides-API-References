---
title: NotesCommentsLayoutingOptions
second_title: Aspose.Slides Android-hoz Java API Referencia
description: Lehetőségeket biztosít a jegyzetek és megjegyzések elrendezésének megjelenésének szabályozásához az exportált dokumentumban.
type: docs
url: /hu/com.aspose.slides/notescommentslayoutingoptions/
---
**Öröklés:**
java.lang.Object

**Az összes implementált interfész:**
[com.aspose.slides.ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
```
public class NotesCommentsLayoutingOptions implements ISlidesLayoutOptions
```

Lehetőségeket biztosít a jegyzetek és megjegyzések megjelenésének ellenőrzésére az exportált dokumentumban.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [NotesCommentsLayoutingOptions()](#NotesCommentsLayoutingOptions--) | Alapértelmezett konstruktor. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getShowCommentsByNoAuthor()](#getShowCommentsByNoAuthor--) | Lekéri vagy beállítja a szerző nélküli megjegyzések láthatóságát. |
| [setShowCommentsByNoAuthor(boolean value)](#setShowCommentsByNoAuthor-boolean-) | Lekéri vagy beállítja a szerző nélküli megjegyzések láthatóságát. |
| [getNotesPosition()](#getNotesPosition--) | Lekéri vagy beállítja a jegyzetek pozícióját az oldalon. |
| [setNotesPosition(int value)](#setNotesPosition-int-) | Lekéri vagy beállítja a jegyzetek pozícióját az oldalon. |
| [getCommentsPosition()](#getCommentsPosition--) | Lekéri vagy beállítja a megjegyzések pozícióját az oldalon. |
| [setCommentsPosition(int value)](#setCommentsPosition-int-) | Lekéri vagy beállítja a megjegyzések pozícióját az oldalon. |
| [getCommentsAreaColor()](#getCommentsAreaColor--) | Lekéri vagy beállítja a megjegyzések területének színét (Csak akkor alkalmazható, ha a megjegyzések jobbra vannak megjelenítve). |
| [setCommentsAreaColor(Integer value)](#setCommentsAreaColor-java.lang.Integer-) | Lekéri vagy beállítja a megjegyzések területének színét (Csak akkor alkalmazható, ha a megjegyzések jobbra vannak megjelenítve). |
| [getCommentsAreaWidth()](#getCommentsAreaWidth--) | Lekéri vagy beállítja a megjegyzés kimeneti területének szélességét pixelben (Csak akkor alkalmazható, ha a megjegyzések jobbra vannak megjelenítve). |
| [setCommentsAreaWidth(int value)](#setCommentsAreaWidth-int-) | Lekéri vagy beállítja a megjegyzés kimeneti területének szélességét pixelben (Csak akkor alkalmazható, ha a megjegyzések jobbra vannak megjelenítve). |
### NotesCommentsLayoutingOptions() {#NotesCommentsLayoutingOptions--}
```
public NotesCommentsLayoutingOptions()
```

Alapértelmezett konstruktor.

### getShowCommentsByNoAuthor() {#getShowCommentsByNoAuthor--}
```
public final boolean getShowCommentsByNoAuthor()
```

Lekéri vagy beállítja a szerző nélküli megjegyzések láthatóságát. Ha igaz, a megjegyzések megjelennek. (Csak akkor alkalmazható, ha a megjegyzések megjelennek).

--------------------

Alapértelmezett érték **false**.

**Visszatérési érték:**  
boolean
### setShowCommentsByNoAuthor(boolean value) {#setShowCommentsByNoAuthor-boolean-}
```
public final void setShowCommentsByNoAuthor(boolean value)
```

Lekéri vagy beállítja a szerző nélküli megjegyzések láthatóságát. Ha igaz, a megjegyzések megjelennek. (Csak akkor alkalmazható, ha a megjegyzések megjelennek).

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

Lekéri vagy beállítja a jegyzetek pozícióját az oldalon.

--------------------

Alapértelmezett **NotesPositions.None**.

**Visszatérési érték:**  
int
### setNotesPosition(int value) {#setNotesPosition-int-}
```
public final void setNotesPosition(int value)
```

Lekéri vagy beállítja a jegyzetek pozícióját az oldalon.

--------------------

Alapértelmezett **NotesPositions.None**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getCommentsPosition() {#getCommentsPosition--}
```
public final int getCommentsPosition()
```

Lekéri vagy beállítja a megjegyzések pozícióját az oldalon.

--------------------

Alapértelmezett **CommentsPositions.None**.

**Visszatérési érték:**  
int
### setCommentsPosition(int value) {#setCommentsPosition-int-}
```
public final void setCommentsPosition(int value)
```

Lekéri vagy beállítja a megjegyzések pozícióját az oldalon.

--------------------

Alapértelmezett **CommentsPositions.None**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getCommentsAreaColor() {#getCommentsAreaColor--}
```
public final Integer getCommentsAreaColor()
```

Lekéri vagy beállítja a megjegyzések területének színét (Csak akkor alkalmazható, ha a megjegyzések jobbra vannak megjelenítve).

--------------------

Alapértelmezett **SkyBlue**.

**Visszatérési érték:**  
java.lang.Integer
### setCommentsAreaColor(Integer value) {#setCommentsAreaColor-java.lang.Integer-}
```
public final void setCommentsAreaColor(Integer value)
```

Lekéri vagy beállítja a megjegyzések területének színét (Csak akkor alkalmazható, ha a megjegyzések jobbra vannak megjelenítve).

--------------------

Alapértelmezett **SkyBlue**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.Integer |  |
### getCommentsAreaWidth() {#getCommentsAreaWidth--}
```
public final int getCommentsAreaWidth()
```

Lekéri vagy beállítja a megjegyzés kimeneti területének szélességét pixelben (Csak akkor alkalmazható, ha a megjegyzések jobbra vannak megjelenítve).

--------------------

Legkisebb és alapértelmezett érték **150**.

**Visszatérési érték:**  
int
### setCommentsAreaWidth(int value) {#setCommentsAreaWidth-int-}
```
public final void setCommentsAreaWidth(int value)
```

Lekéri vagy beállítja a megjegyzés kimeneti területének szélességét pixelben (Csak akkor alkalmazható, ha a megjegyzések jobbra vannak megjelenítve).

--------------------

Legkisebb és alapértelmezett érték **150**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |