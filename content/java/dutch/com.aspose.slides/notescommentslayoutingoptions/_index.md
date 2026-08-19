---
title: NotesCommentsLayoutingOptions
second_title: Aspose.Slides voor Java API-referentie
description: Biedt opties die de weergave van notities en opmerkingen in een geëxporteerd document regelen.
type: docs
url: /nl/com.aspose.slides/notescommentslayoutingoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
```
public class NotesCommentsLayoutingOptions implements ISlidesLayoutOptions
```

Biedt opties die de weergave van notities en opmerkingen in een geëxporteerd document regelen.
## Constructoren

| Constructor | Description |
| --- | --- |
| [NotesCommentsLayoutingOptions()](#NotesCommentsLayoutingOptions--) | Standaardconstructor. |
## Methoden

| Method | Description |
| --- | --- |
| [getShowCommentsByNoAuthor()](#getShowCommentsByNoAuthor--) | Haalt de zichtbaarheid van opmerkingen zonder auteur op of stelt deze in. |
| [setShowCommentsByNoAuthor(boolean value)](#setShowCommentsByNoAuthor-boolean-) | Haalt de zichtbaarheid van opmerkingen zonder auteur op of stelt deze in. |
| [getNotesPosition()](#getNotesPosition--) | Haalt de positie van de notities op de pagina op of stelt deze in. |
| [setNotesPosition(int value)](#setNotesPosition-int-) | Haalt de positie van de notities op de pagina op of stelt deze in. |
| [getCommentsPosition()](#getCommentsPosition--) | Haalt de positie van de opmerkingen op de pagina op of stelt deze in. |
| [setCommentsPosition(int value)](#setCommentsPosition-int-) | Haalt de positie van de opmerkingen op de pagina op of stelt deze in. |
| [getCommentsAreaColor()](#getCommentsAreaColor--) | Haalt de kleur van het opmerkingengebied op of stelt deze in (geldt alleen als opmerkingen aan de rechterkant worden weergegeven). |
| [setCommentsAreaColor(Color value)](#setCommentsAreaColor-java.awt.Color-) | Haalt de kleur van het opmerkingengebied op of stelt deze in (geldt alleen als opmerkingen aan de rechterkant worden weergegeven). |
| [getCommentsAreaWidth()](#getCommentsAreaWidth--) | Haalt de breedte van het opmerkingen-uitvoergebied in pixels op of stelt deze in (geldt alleen als opmerkingen aan de rechterkant worden weergegeven). |
| [setCommentsAreaWidth(int value)](#setCommentsAreaWidth-int-) | Haalt de breedte van het opmerkingen-uitvoergebied in pixels op of stelt deze in (geldt alleen als opmerkingen aan de rechterkant worden weergegeven). |
### NotesCommentsLayoutingOptions() {#NotesCommentsLayoutingOptions--}
```
public NotesCommentsLayoutingOptions()
```


Standaardconstructor.

### getShowCommentsByNoAuthor() {#getShowCommentsByNoAuthor--}
```
public final boolean getShowCommentsByNoAuthor()
```


Haalt de zichtbaarheid van opmerkingen zonder auteur op of stelt deze in. Als **true**, worden opmerkingen weergegeven. (Geldt alleen als opmerkingen worden weergegeven).

--------------------

Standaardwaarde is **false**.

**Retour:**
boolean
### setShowCommentsByNoAuthor(boolean value) {#setShowCommentsByNoAuthor-boolean-}
```
public final void setShowCommentsByNoAuthor(boolean value)
```


Haalt de zichtbaarheid van opmerkingen zonder auteur op of stelt deze in. Als **true**, worden opmerkingen weergegeven. (Geldt alleen als opmerkingen worden weergegeven).

--------------------

Standaardwaarde is **false**.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getNotesPosition() {#getNotesPosition--}
```
public final int getNotesPosition()
```


Haalt de positie van de notities op de pagina op of stelt deze in.

--------------------

Standaard is **NotesPositions.None**.

**Retour:**
int
### setNotesPosition(int value) {#setNotesPosition-int-}
```
public final void setNotesPosition(int value)
```


Haalt de positie van de notities op de pagina op of stelt deze in.

--------------------

Standaard is **NotesPositions.None**.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCommentsPosition() {#getCommentsPosition--}
```
public final int getCommentsPosition()
```


Haalt de positie van de opmerkingen op de pagina op of stelt deze in.

--------------------

Standaard is **CommentsPositions.None**.

**Retour:**
int
### setCommentsPosition(int value) {#setCommentsPosition-int-}
```
public final void setCommentsPosition(int value)
```


Haalt de positie van de opmerkingen op de pagina op of stelt deze in.

--------------------

Standaard is **CommentsPositions.None**.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCommentsAreaColor() {#getCommentsAreaColor--}
```
public final Color getCommentsAreaColor()
```


Haalt de kleur van het opmerkingengebied op of stelt deze in (geldt alleen als opmerkingen aan de rechterkant worden weergegeven).

--------------------

Standaard is **Color.SkyBlue**.

**Retour:**
java.awt.Color
### setCommentsAreaColor(Color value) {#setCommentsAreaColor-java.awt.Color-}
```
public final void setCommentsAreaColor(Color value)
```


Haalt de kleur van het opmerkingengebied op of stelt deze in (geldt alleen als opmerkingen aan de rechterkant worden weergegeven).

--------------------

Standaard is **Color.SkyBlue**.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Color |  |

### getCommentsAreaWidth() {#getCommentsAreaWidth--}
```
public final int getCommentsAreaWidth()
```


Haalt de breedte van het opmerkingen-uitvoergebied in pixels op of stelt deze in (geldt alleen als opmerkingen aan de rechterkant worden weergegeven).

--------------------

Minimale en standaardwaarde is **150**.

**Retour:**
int
### setCommentsAreaWidth(int value) {#setCommentsAreaWidth-int-}
```
public final void setCommentsAreaWidth(int value)
```


Haalt de breedte van het opmerkingen-uitvoergebied in pixels op of stelt deze in (geldt alleen als opmerkingen aan de rechterkant worden weergegeven).

--------------------

Minimale en standaardwaarde is **150**.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |