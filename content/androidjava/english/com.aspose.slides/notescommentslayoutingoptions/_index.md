---
title: NotesCommentsLayoutingOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Provides options that control the look of layouting of notes and comments in exported document.
type: docs
url: /com.aspose.slides/notescommentslayoutingoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.INotesCommentsLayoutingOptions](../../com.aspose.slides/inotescommentslayoutingoptions)
```
public class NotesCommentsLayoutingOptions implements INotesCommentsLayoutingOptions
```

Provides options that control the look of layouting of notes and comments in exported document.
## Constructors

| Constructor | Description |
| --- | --- |
| [NotesCommentsLayoutingOptions()](#NotesCommentsLayoutingOptions--) | Default constructor. |
## Methods

| Method | Description |
| --- | --- |
| [getShowCommentsByNoAuthor()](#getShowCommentsByNoAuthor--) | Gets or sets the visibility of comments that do not have an author. |
| [setShowCommentsByNoAuthor(boolean value)](#setShowCommentsByNoAuthor-boolean-) | Gets or sets the visibility of comments that do not have an author. |
| [getNotesPosition()](#getNotesPosition--) | Gets or sets the position of the notes on the page. |
| [setNotesPosition(int value)](#setNotesPosition-int-) | Gets or sets the position of the notes on the page. |
| [getCommentsPosition()](#getCommentsPosition--) | Gets or sets the position of the comments on the page. |
| [setCommentsPosition(int value)](#setCommentsPosition-int-) | Gets or sets the position of the comments on the page. |
| [getCommentsAreaColor()](#getCommentsAreaColor--) | Gets or sets the color of comments area (Applies only if comments are displayed on the right). |
| [setCommentsAreaColor(Integer value)](#setCommentsAreaColor-java.lang.Integer-) | Gets or sets the color of comments area (Applies only if comments are displayed on the right). |
| [getCommentsAreaWidth()](#getCommentsAreaWidth--) | Gets or sets the width of the comment output area in pixels (Applies only if comments are displayed on the right). |
| [setCommentsAreaWidth(int value)](#setCommentsAreaWidth-int-) | Gets or sets the width of the comment output area in pixels (Applies only if comments are displayed on the right). |
### NotesCommentsLayoutingOptions() {#NotesCommentsLayoutingOptions--}
```
public NotesCommentsLayoutingOptions()
```


Default constructor.

### getShowCommentsByNoAuthor() {#getShowCommentsByNoAuthor--}
```
public final boolean getShowCommentsByNoAuthor()
```


Gets or sets the visibility of comments that do not have an author. If true then comments will be displayed. (Applies only if comments are displayed).

--------------------

Default value is **false**.

**Returns:**
boolean
### setShowCommentsByNoAuthor(boolean value) {#setShowCommentsByNoAuthor-boolean-}
```
public final void setShowCommentsByNoAuthor(boolean value)
```


Gets or sets the visibility of comments that do not have an author. If true then comments will be displayed. (Applies only if comments are displayed).

--------------------

Default value is **false**.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getNotesPosition() {#getNotesPosition--}
```
public final int getNotesPosition()
```


Gets or sets the position of the notes on the page.

--------------------

Default is [NotesPositions.None](../../com.aspose.slides/notespositions\#None).

**Returns:**
int
### setNotesPosition(int value) {#setNotesPosition-int-}
```
public final void setNotesPosition(int value)
```


Gets or sets the position of the notes on the page.

--------------------

Default is [NotesPositions.None](../../com.aspose.slides/notespositions\#None).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCommentsPosition() {#getCommentsPosition--}
```
public final int getCommentsPosition()
```


Gets or sets the position of the comments on the page.

--------------------

Default is **CommentsPositions\#None**.

**Returns:**
int
### setCommentsPosition(int value) {#setCommentsPosition-int-}
```
public final void setCommentsPosition(int value)
```


Gets or sets the position of the comments on the page.

--------------------

Default is **CommentsPositions\#None**.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCommentsAreaColor() {#getCommentsAreaColor--}
```
public final Integer getCommentsAreaColor()
```


Gets or sets the color of comments area (Applies only if comments are displayed on the right).

--------------------

Default is java.lang.Integer\#BLUE.BLUE.

**Returns:**
java.lang.Integer
### setCommentsAreaColor(Integer value) {#setCommentsAreaColor-java.lang.Integer-}
```
public final void setCommentsAreaColor(Integer value)
```


Gets or sets the color of comments area (Applies only if comments are displayed on the right).

--------------------

Default is java.lang.Integer\#BLUE.BLUE.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getCommentsAreaWidth() {#getCommentsAreaWidth--}
```
public final int getCommentsAreaWidth()
```


Gets or sets the width of the comment output area in pixels (Applies only if comments are displayed on the right).

--------------------

Minimal and default value is **150**.

**Returns:**
int
### setCommentsAreaWidth(int value) {#setCommentsAreaWidth-int-}
```
public final void setCommentsAreaWidth(int value)
```


Gets or sets the width of the comment output area in pixels (Applies only if comments are displayed on the right).

--------------------

Minimal and default value is **150**.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

