---
title: ISlideText
second_title: Aspose.Slides for Android via Java API Reference
description: Represents the text extracted from the slide
type: docs
url: /com.aspose.slides/islidetext/
---```
public interface ISlideText
```

Represents the text extracted from the slide
## Methods

| Method | Description |
| --- | --- |
| [getText()](#getText--) | The text on the slide's shapes |
| [getMasterText()](#getMasterText--) | The text on the master page's shapes for this slide |
| [getLayoutText()](#getLayoutText--) | The text on the layout page's shapes for this slide |
| [getNotesText()](#getNotesText--) | The text on the notes page's shapes for this slide |
| [getCommentsText()](#getCommentsText--) | The text of the slide comments |
### getText() {#getText--}
```
public abstract String getText()
```


The text on the slide's shapes

**Returns:**
java.lang.String
### getMasterText() {#getMasterText--}
```
public abstract String getMasterText()
```


The text on the master page's shapes for this slide

**Returns:**
java.lang.String
### getLayoutText() {#getLayoutText--}
```
public abstract String getLayoutText()
```


The text on the layout page's shapes for this slide

**Returns:**
java.lang.String
### getNotesText() {#getNotesText--}
```
public abstract String getNotesText()
```


The text on the notes page's shapes for this slide

**Returns:**
java.lang.String
### getCommentsText() {#getCommentsText--}
```
public abstract String getCommentsText()
```


The text of the slide comments

--------------------

This field is empty when the text is extracted using the Arranged mode.

**Returns:**
java.lang.String
