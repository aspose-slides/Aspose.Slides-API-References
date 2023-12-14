---
title: INotesCommentsLayoutingOptions
second_title: Aspose.Slides for Java API Reference
description: Provides options that control the look of layouting of notes and comments in exported document.
type: docs
url: /com.aspose.slides/inotescommentslayoutingoptions/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
```
public interface INotesCommentsLayoutingOptions extends ISlidesLayoutOptions
```

Provides options that control the look of layouting of notes and comments in exported document.
## Methods

| Method | Description |
| --- | --- |
| [getNotesPosition()](#getNotesPosition--) | Gets or sets the position of the notes on the page. |
| [setNotesPosition(int value)](#setNotesPosition-int-) | Gets or sets the position of the notes on the page. |
| [getCommentsPosition()](#getCommentsPosition--) | Gets or sets the position of the comments on the page. |
| [setCommentsPosition(int value)](#setCommentsPosition-int-) | Gets or sets the position of the comments on the page. |
| [getCommentsAreaColor()](#getCommentsAreaColor--) | Gets or sets the color of comments area (Applies only if comments are displayed on the right). |
| [setCommentsAreaColor(Color value)](#setCommentsAreaColor-java.awt.Color-) | Gets or sets the color of comments area (Applies only if comments are displayed on the right). |
| [getCommentsAreaWidth()](#getCommentsAreaWidth--) | Gets or sets the width of the comment output area in pixels (Applies only if comments are displayed on the right). |
| [setCommentsAreaWidth(int value)](#setCommentsAreaWidth-int-) | Gets or sets the width of the comment output area in pixels (Applies only if comments are displayed on the right). |
| [getShowCommentsByNoAuthor()](#getShowCommentsByNoAuthor--) | Gets or sets the visibility of comments that do not have an author. |
| [setShowCommentsByNoAuthor(boolean value)](#setShowCommentsByNoAuthor-boolean-) | Gets or sets the visibility of comments that do not have an author. |
### getNotesPosition() {#getNotesPosition--}
```
public abstract int getNotesPosition()
```


Gets or sets the position of the notes on the page.

--------------------

Default is [NotesPositions.None](../../com.aspose.slides/notespositions\#None).

**Returns:**
int
### setNotesPosition(int value) {#setNotesPosition-int-}
```
public abstract void setNotesPosition(int value)
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
public abstract int getCommentsPosition()
```


Gets or sets the position of the comments on the page.

--------------------

Default is **CommentsPositions\#None**.

**Returns:**
int
### setCommentsPosition(int value) {#setCommentsPosition-int-}
```
public abstract void setCommentsPosition(int value)
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
public abstract Color getCommentsAreaColor()
```


Gets or sets the color of comments area (Applies only if comments are displayed on the right).

--------------------

Default is java.awt.Color\#BLUE.BLUE.

**Returns:**
java.awt.Color
### setCommentsAreaColor(Color value) {#setCommentsAreaColor-java.awt.Color-}
```
public abstract void setCommentsAreaColor(Color value)
```


Gets or sets the color of comments area (Applies only if comments are displayed on the right).

--------------------

Default is java.awt.Color\#BLUE.BLUE.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Color |  |

### getCommentsAreaWidth() {#getCommentsAreaWidth--}
```
public abstract int getCommentsAreaWidth()
```


Gets or sets the width of the comment output area in pixels (Applies only if comments are displayed on the right).

--------------------

Minimal and default value is **150**.

**Returns:**
int
### setCommentsAreaWidth(int value) {#setCommentsAreaWidth-int-}
```
public abstract void setCommentsAreaWidth(int value)
```


Gets or sets the width of the comment output area in pixels (Applies only if comments are displayed on the right).

--------------------

Minimal and default value is **150**.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getShowCommentsByNoAuthor() {#getShowCommentsByNoAuthor--}
```
public abstract boolean getShowCommentsByNoAuthor()
```


Gets or sets the visibility of comments that do not have an author. If true then comments will be displayed. (Applies only if comments are displayed).

--------------------

Default value is **false**.

**Returns:**
boolean
### setShowCommentsByNoAuthor(boolean value) {#setShowCommentsByNoAuthor-boolean-}
```
public abstract void setShowCommentsByNoAuthor(boolean value)
```


Gets or sets the visibility of comments that do not have an author. If true then comments will be displayed. (Applies only if comments are displayed).

--------------------

Default value is **false**.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

