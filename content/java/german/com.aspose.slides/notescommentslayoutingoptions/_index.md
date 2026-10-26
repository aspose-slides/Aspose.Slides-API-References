---
title: NotesCommentsLayoutingOptions
second_title: Aspose.Slides für Java API-Referenz
description: Bietet Optionen, die das Aussehen der Anordnung von Notizen und Kommentaren im exportierten Dokument steuern.
type: docs
url: /de/com.aspose.slides/notescommentslayoutingoptions/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
```
public class NotesCommentsLayoutingOptions implements ISlidesLayoutOptions
```

Bietet Optionen, die das Aussehen der Anordnung von Notizen und Kommentaren im exportierten Dokument steuern.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [NotesCommentsLayoutingOptions()](#NotesCommentsLayoutingOptions--) | Standardkonstruktor. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getShowCommentsByNoAuthor()](#getShowCommentsByNoAuthor--) | Liest oder setzt die Sichtbarkeit von Kommentaren, die keinen Autor haben. |
| [setShowCommentsByNoAuthor(boolean value)](#setShowCommentsByNoAuthor-boolean-) | Liest oder setzt die Sichtbarkeit von Kommentaren, die keinen Autor haben. |
| [getNotesPosition()](#getNotesPosition--) | Liest oder setzt die Position der Notizen auf der Seite. |
| [setNotesPosition(int value)](#setNotesPosition-int-) | Liest oder setzt die Position der Notizen auf der Seite. |
| [getCommentsPosition()](#getCommentsPosition--) | Liest oder setzt die Position der Kommentare auf der Seite. |
| [setCommentsPosition(int value)](#setCommentsPosition-int-) | Liest oder setzt die Position der Kommentare auf der Seite. |
| [getCommentsAreaColor()](#getCommentsAreaColor--) | Liest oder setzt die Farbe des Kommentarbereichs (Gilt nur, wenn Kommentare rechts angezeigt werden). |
| [setCommentsAreaColor(Color value)](#setCommentsAreaColor-java.awt.Color-) | Liest oder setzt die Farbe des Kommentarbereichs (Gilt nur, wenn Kommentare rechts angezeigt werden). |
| [getCommentsAreaWidth()](#getCommentsAreaWidth--) | Liest oder setzt die Breite des Kommentar-Ausgabebereichs in Pixel (Gilt nur, wenn Kommentare rechts angezeigt werden). |
| [setCommentsAreaWidth(int value)](#setCommentsAreaWidth-int-) | Liest oder setzt die Breite des Kommentar-Ausgabebereichs in Pixel (Gilt nur, wenn Kommentare rechts angezeigt werden). |
### NotesCommentsLayoutingOptions() {#NotesCommentsLayoutingOptions--}
```
public NotesCommentsLayoutingOptions()
```

Standardkonstruktor.

### getShowCommentsByNoAuthor() {#getShowCommentsByNoAuthor--}
```
public final boolean getShowCommentsByNoAuthor()
```

Liest oder setzt die Sichtbarkeit von Kommentaren, die keinen Autor haben. Wenn true, werden die Kommentare angezeigt. (Gilt nur, wenn Kommentare angezeigt werden).

--------------------

Standardwert ist **false**.

**Rückgabe:**
boolean
### setShowCommentsByNoAuthor(boolean value) {#setShowCommentsByNoAuthor-boolean-}
```
public final void setShowCommentsByNoAuthor(boolean value)
```

Liest oder setzt die Sichtbarkeit von Kommentaren, die keinen Autor haben. Wenn true, werden die Kommentare angezeigt. (Gilt nur, wenn Kommentare angezeigt werden).

--------------------

Standardwert ist **false**.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getNotesPosition() {#getNotesPosition--}
```
public final int getNotesPosition()
```

Liest oder setzt die Position der Notizen auf der Seite.

--------------------

Standard ist **NotesPositions.None**.

**Rückgabe:**
int
### setNotesPosition(int value) {#setNotesPosition-int-}
```
public final void setNotesPosition(int value)
```

Liest oder setzt die Position der Notizen auf der Seite.

--------------------

Standard ist **NotesPositions.None**.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getCommentsPosition() {#getCommentsPosition--}
```
public final int getCommentsPosition()
```

Liest oder setzt die Position der Kommentare auf der Seite.

--------------------

Standard ist **CommentsPositions.None**.

**Rückgabe:**
int
### setCommentsPosition(int value) {#setCommentsPosition-int-}
```
public final void setCommentsPosition(int value)
```

Liest oder setzt die Position der Kommentare auf der Seite.

--------------------

Standard ist **CommentsPositions.None**.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getCommentsAreaColor() {#getCommentsAreaColor--}
```
public final Color getCommentsAreaColor()
```

Liest oder setzt die Farbe des Kommentarbereichs (Gilt nur, wenn Kommentare rechts angezeigt werden).

--------------------

Standard ist **Color.SkyBlue**.

**Rückgabe:**
java.awt.Color
### setCommentsAreaColor(Color value) {#setCommentsAreaColor-java.awt.Color-}
```
public final void setCommentsAreaColor(Color value)
```

Liest oder setzt die Farbe des Kommentarbereichs (Gilt nur, wenn Kommentare rechts angezeigt werden).

--------------------

Standard ist **Color.SkyBlue**.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.awt.Color |  |
### getCommentsAreaWidth() {#getCommentsAreaWidth--}
```
public final int getCommentsAreaWidth()
```

Liest oder setzt die Breite des Kommentar-Ausgabebereichs in Pixel (Gilt nur, wenn Kommentare rechts angezeigt werden).

--------------------

Minimaler und Standardwert ist **150**.

**Rückgabe:**
int
### setCommentsAreaWidth(int value) {#setCommentsAreaWidth-int-}
```
public final void setCommentsAreaWidth(int value)
```

Liest oder setzt die Breite des Kommentar-Ausgabebereichs in Pixel (Gilt nur, wenn Kommentare rechts angezeigt werden).

--------------------

Minimaler und Standardwert ist **150**.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |