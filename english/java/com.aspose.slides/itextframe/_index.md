---
title: ITextFrame
second_title: Aspose.Slides for Java API Reference
description: Represents a TextFrame.
type: docs
weight: 1069
url: /java/com.aspose.slides/itextframe/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ITextFrame extends ISlideComponent
```

Represents a TextFrame.
## Methods

| Method | Description |
| --- | --- |
| [getParagraphs()](#getParagraphs--) | Returns the list of all paragraphs in a frame. |
| [getText()](#getText--) | Gets or sets the plain text for a TextFrame. |
| [setText(String value)](#setText-java.lang.String-) | Gets or sets the plain text for a TextFrame. |
| [getTextFrameFormat()](#getTextFrameFormat--) | Returns the formatting object for this TextFrame object. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Provides easy access to contained hyperlinks. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Joins runs with same formatting in all paragraphs. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | Highlight all matches of sample in text frame text using specified color. |
| [highlightText(String text, Color highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | Highlight all matches of sample in text frame text using specified color. |
| [highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | Highlight all matches of regular expression in text frame text using specified color. |
### getParagraphs() {#getParagraphs--}
```
public abstract IParagraphCollection getParagraphs()
```


Returns the list of all paragraphs in a frame. Read-only [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**Returns:**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
### getText() {#getText--}
```
public abstract String getText()
```


Gets or sets the plain text for a TextFrame. Read/write String.

Value: The text.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


Gets or sets the plain text for a TextFrame. Read/write String.

Value: The text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFrameFormat() {#getTextFrameFormat--}
```
public abstract ITextFrameFormat getTextFrameFormat()
```


Returns the formatting object for this TextFrame object. Read-only [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Returns:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```


Provides easy access to contained hyperlinks. Read-only [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Returns:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```


Joins runs with same formatting in all paragraphs.

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public abstract void highlightText(String text, Color highlightColor)
```


Highlight all matches of sample in text frame text using specified color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text sample to highlight. |
| highlightColor | java.awt.Color | Highlighting color. |

### highlightText(String text, Color highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightText(String text, Color highlightColor, ITextHighlightingOptions options)
```


Highlight all matches of sample in text frame text using specified color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text sample to highlight. |
| highlightColor | java.awt.Color | Highlighting color. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Highlighting options. |

### highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)
```


Highlight all matches of regular expression in text frame text using specified color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| regex | java.lang.String | Text of regular expression to get text to highlight. |
| highlightColor | java.awt.Color | Highlighting color. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Highlighting options. |

