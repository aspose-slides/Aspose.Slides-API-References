---
title: NotesCommentsLayoutingOptions
second_title: Aspose.Slides för Android via Java API-referens
description: Ger alternativ som styr utseendet på layout av noteringar och kommentarer i exporterade dokument.
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

Tillhandahåller alternativ som styr utseendet på layout av noteringar och kommentarer i exporterade dokument.
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [NotesCommentsLayoutingOptions()](#NotesCommentsLayoutingOptions--) | Standardkonstruktor. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getShowCommentsByNoAuthor()](#getShowCommentsByNoAuthor--) | Hämtar eller anger synligheten för kommentarer som saknar en författare. |
| [setShowCommentsByNoAuthor(boolean value)](#setShowCommentsByNoAuthor-boolean-) | Hämtar eller anger synligheten för kommentarer som saknar en författare. |
| [getNotesPosition()](#getNotesPosition--) | Hämtar eller anger positionen för noterna på sidan. |
| [setNotesPosition(int value)](#setNotesPosition-int-) | Hämtar eller anger positionen för noterna på sidan. |
| [getCommentsPosition()](#getCommentsPosition--) | Hämtar eller anger positionen för kommentarerna på sidan. |
| [setCommentsPosition(int value)](#setCommentsPosition-int-) | Hämtar eller anger positionen för kommentarerna på sidan. |
| [getCommentsAreaColor()](#getCommentsAreaColor--) | Hämtar eller anger färgen på kommentarsområdet (Gäller endast om kommentarer visas till höger). |
| [setCommentsAreaColor(Integer value)](#setCommentsAreaColor-java.lang.Integer-) | Hämtar eller anger färgen på kommentarsområdet (Gäller endast om kommentarer visas till höger). |
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

Hämtar eller anger synligheten för kommentarer som saknar en författare. Om true visas kommentarer. (Gäller endast om kommentarer visas).

--------------------

Standardvärdet är **false**.

**Returnerar:**
boolean
### setShowCommentsByNoAuthor(boolean value) {#setShowCommentsByNoAuthor-boolean-}
```
public final void setShowCommentsByNoAuthor(boolean value)
```

Hämtar eller anger synligheten för kommentarer som saknar en författare. Om true visas kommentarer. (Gäller endast om kommentarer visas).

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

Hämtar eller anger positionen för kommentarerna på sidan.

--------------------

Standard är **CommentsPositions.None**.

**Returnerar:**
int
### setCommentsPosition(int value) {#setCommentsPosition-int-}
```
public final void setCommentsPosition(int value)
```

Hämtar eller anger positionen för kommentarerna på sidan.

--------------------

Standard är **CommentsPositions.None**.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getCommentsAreaColor() {#getCommentsAreaColor--}
```
public final Integer getCommentsAreaColor()
```

Hämtar eller anger färgen på kommentarsområdet (Gäller endast om kommentarer visas till höger).

--------------------

Standard är **SkyBlue**.

**Returnerar:**
java.lang.Integer
### setCommentsAreaColor(Integer value) {#setCommentsAreaColor-java.lang.Integer-}
```
public final void setCommentsAreaColor(Integer value)
```

Hämtar eller anger färgen på kommentarsområdet (Gäller endast om kommentarer visas till höger).

--------------------

Standard är **SkyBlue**.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.Integer |  |

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