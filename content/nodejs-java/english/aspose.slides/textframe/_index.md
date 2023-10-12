---
title: TextFrame
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/textframe/
---

## TextFrame class

  Represents a TextFrame.
 
### getHyperlinkQueries {#getHyperlinkQueries}

| Name | Description |
| --- | --- |
| getHyperlinkQueries () | Provides easy access to contained hyperlinks. Read-only IHyperlinkQueries. |

 **Result**
[HyperlinkQueries](../hyperlinkqueries)


---


### getParagraphs {#getParagraphs}

| Name | Description |
| --- | --- |
| getParagraphs () | Returns the list of all paragraphs in a frame. Read-only IParagraphCollection. |

 **Result**
[ParagraphCollection](../paragraphcollection)


---


### getPresentation {#getPresentation}

| Name | Description |
| --- | --- |
| getPresentation () | Returns the parent presentation of a TextFrame. Read-only IPresentation. |

 **Result**
[Presentation](../presentation)


---


### getSlide {#getSlide}

| Name | Description |
| --- | --- |
| getSlide () | Returns the parent slide of a TextFrame. Read-only IBaseSlide. |

 **Result**
[MasterNotesSlide](../masternotesslide), [MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [NotesSlide](../notesslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide)


---


### getText {#getText}

| Name | Description |
| --- | --- |
| getText () | Gets or sets the plain text for a TextFrame. Read/write String. Value: The text. |

 **Result**
String


---


### getTextFrameFormat {#getTextFrameFormat}

| Name | Description |
| --- | --- |
| getTextFrameFormat () | Returns the formatting object for this TextFrame object. Read-only ITextFrameFormat. |

 **Result**
[TextFrameFormat](../textframeformat)


---


### highlightRegex {#highlightRegex}

| Name | Description |
| --- | --- |
| highlightRegex (String, Color, [TextHighlightingOptions](../texthighlightingoptions)) | Highlight all matches of regular expression in text frame text using specified color. |

 **Parameters**

| Name | Type | Description |
| --- | --- | --- |
| regex | String | Text of regular expression to get text to highlight. |
| highlightColor | Color | Highlighting color. |
| options | [TextHighlightingOptions](../texthighlightingoptions) | Highlighting options. |


---


### highlightText {#highlightText}

| Name | Description |
| --- | --- |
| highlightText (String, Color) | Highlight all matches of sample in text frame text using specified color. |

 **Parameters**

| Name | Type | Description |
| --- | --- | --- |
| text | String | Text sample to highlight. |
| highlightColor | Color | Highlighting color. |


---


### highlightText {#highlightText}

| Name | Description |
| --- | --- |
| highlightText (String, Color, [TextHighlightingOptions](../texthighlightingoptions)) | Highlight all matches of sample in text frame text using specified color. |

 **Parameters**

| Name | Type | Description |
| --- | --- | --- |
| text | String | Text sample to highlight. |
| highlightColor | Color | Highlighting color. |
| options | [TextHighlightingOptions](../texthighlightingoptions) | Highlighting options. |


---


### joinPortionsWithSameFormatting {#joinPortionsWithSameFormatting}

| Name | Description |
| --- | --- |
| joinPortionsWithSameFormatting () | Joins runs with same formatting in all paragraphs. |


---


### setText {#setText}

| Name | Description |
| --- | --- |
| setText (String) | Gets or sets the plain text for a TextFrame. Read/write String. Value: The text. |


---


