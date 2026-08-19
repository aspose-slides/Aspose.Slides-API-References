---
title: NotesCommentsLayoutingOptions
second_title: Aspose.Slides för Java API-referens
description: Tillhandahåller alternativ som styr utseendet på layouten av anteckningar och kommentarer i ett exporterat dokument.
type: docs
url: /sv/com.aspose.slides/notescommentslayoutingoptions/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
```
public class NotesCommentsLayoutingOptions implements ISlidesLayoutOptions
```

Tillhandahåller alternativ som styr utseendet på layouten av anteckningar och kommentarer i exporterat dokument.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [NotesCommentsLayoutingOptions()](#NotesCommentsLayoutingOptions--) | Standardkonstruktor. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getShowCommentsByNoAuthor()](#getShowCommentsByNoAuthor--) | Hämtar eller anger synligheten för kommentarer som saknar författare. |
| [setShowCommentsByNoAuthor(boolean value)](#setShowCommentsByNoAuthor-boolean-) | Hämtar eller anger synligheten för kommentarer som saknar författare. |
| [getNotesPosition()](#getNotesPosition--) | Hämtar eller anger positionen för noterna på sidan. |
| [setNotesPosition(int value)](#setNotesPosition-int-) | Hämtar eller anger positionen för noterna på sidan. |
| [getCommentsPosition()](#getCommentsPosition--) | Hämtar eller anger positionen för kommentarer på sidan. |
| [setCommentsPosition(int value)](#setCommentsPosition-int-) | Hämtar eller anger positionen för kommentarer på sidan. |
| [getCommentsAreaColor()](#getCommentsAreaColor--) | Hämtar eller anger färgen på kommentarsområdet (Gäller endast om kommentarer visas till höger). |
| [setCommentsAreaColor(Color value)](#setCommentsAreaColor-java.awt.Color-) | Hämtar eller anger färgen på kommentarsområdet (Gäller endast om kommentarer visas till höger). |
| [getCommentsAreaWidth()](#getCommentsAreaWidth--) | Hämtar eller anger bredden på kommentarsutmatningsområdet i pixlar (Gäller endast om kommentarer visas till höger). |
| [setCommentsAreaWidth(int value)](#setCommentsAreaWidth-int-) | Hämtar eller anger bredden på kommentarsutmatningsområdet i pixlar (Gäller endast om kommentarer visas till höger). |
### NotesCommentsLayoutingOptions() {#NotesCommentsLayoutingOptions--}
```
public NotesCommentsLayoutingOptions()
```


Standardkonstruktor.

### getShowCommentsByNoAuthor() {#getShowCommentsByNoAuthor--}
```
public final boolean getShowCommentsByNoAuthor()
```


Hämtar eller anger synligheten för kommentarer som saknar författare. Om true visas kommentarer. (Gäller endast om kommentarer visas).

--------------------

Standardvärdet är **false**.

**Returnerar:**
boolean
### setShowCommentsByNoAuthor(boolean value) {#setShowCommentsByNoAuthor-boolean-}
```
public final void setShowCommentsByNoAuthor(boolean value)
```


Hämtar eller anger synligheten för kommentarer som saknar författare. Om true visas kommentarer. (Gäller endast om kommentarer visas).

--------------------

Standardvärdet är **false**.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getNotesPosition() {#getNotesPosition--}
```
public final int getNotesPosition()
```


Hämtar eller anger positionen för noterna på sidan.

--------------------

Standard är **NotesPositions.None**.

**Returnerar:**
int
### setNotesPosition(int value) {#setNotesPosition-int-}
```
public final void setNotesPosition(int value)
```


Hämtar eller anger positionen för noterna på sidan.

--------------------

Standard är **NotesPositions.None**.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getCommentsPosition() {#getCommentsPosition--}
```
public final int getCommentsPosition()
```


Hämtar eller anger positionen för kommentarer på sidan.

--------------------

Standard är **CommentsPositions.None**.

**Returnerar:**
int
### setCommentsPosition(int value) {#setCommentsPosition-int-}
```
public final void setCommentsPosition(int value)
```


Hämtar eller anger positionen för kommentarer på sidan.

--------------------

Standard är **CommentsPositions.None**.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getCommentsAreaColor() {#getCommentsAreaColor--}
```
public final Color getCommentsAreaColor()
```


Hämtar eller anger färgen på kommentarsområdet (Gäller endast om kommentarer visas till höger).

--------------------

Standard är **Color.SkyBlue**.

**Returnerar:**
java.awt.Color
### setCommentsAreaColor(Color value) {#setCommentsAreaColor-java.awt.Color-}
```
public final void setCommentsAreaColor(Color value)
```


Hämtar eller anger färgen på kommentarsområdet (Gäller endast om kommentarer visas till höger).

--------------------

Standard är **Color.SkyBlue**.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.awt.Color |  |

### getCommentsAreaWidth() {#getCommentsAreaWidth--}
```
public final int getCommentsAreaWidth()
```


Hämtar eller anger bredden på kommentarsutmatningsområdet i pixlar (Gäller endast om kommentarer visas till höger).

--------------------

Minimalt och standardvärde är **150**.

**Returnerar:**
int
### setCommentsAreaWidth(int value) {#setCommentsAreaWidth-int-}
```
public final void setCommentsAreaWidth(int value)
```


Hämtar eller anger bredden på kommentarsutmatningsområdet i pixlar (Gäller endast om kommentarer visas till höger).

--------------------

Minimalt och standardvärde är **150**.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |