---
title: TextFrame
second_title: Aspose.Sildes for PHP via Java API Reference
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

 **Returns:**
[HyperlinkQueries](../hyperlinkqueries)


---


### getParagraphs {#getParagraphs}

| Name | Description |
| --- | --- |
| getParagraphs () | Returns the list of all paragraphs in a frame. Read-only IParagraphCollection. |

 **Returns:**
[ParagraphCollection](../paragraphcollection)


---


### getPresentation {#getPresentation}

| Name | Description |
| --- | --- |
| getPresentation () | Returns the parent presentation of a TextFrame. Read-only IPresentation. |

 **Returns:**
[Presentation](../presentation)


---


### getSlide {#getSlide}

| Name | Description |
| --- | --- |
| getSlide () | Returns the parent slide of a TextFrame. Read-only IBaseSlide. |

 **Returns:**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)


---


### getText {#getText}

| Name | Description |
| --- | --- |
| getText () | Gets or sets the plain text for a TextFrame. Read/write String. Value: The text. |

 **Returns:**
String


---


### getTextFrameFormat {#getTextFrameFormat}

| Name | Description |
| --- | --- |
| getTextFrameFormat () | Returns the formatting object for this TextFrame object. Read-only ITextFrameFormat. |

 **Returns:**
[TextFrameFormat](../textframeformat)


---


### highlightRegex {#highlightRegex}

| Name | Description |
| --- | --- |
| highlightRegex (String, Color, [TextHighlightingOptions](../texthighlightingoptions)) | Highlights all matches of the regular expression with the specified color. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| regex | String | Text of regular expression to get text to highlight. |
| highlightColor | Color | The color to highlight the text. |
| options | [TextHighlightingOptions](../texthighlightingoptions) | Highlighting options. |

 **Returns:**
void


---


### highlightRegex {#highlightRegex}

| Name | Description |
| --- | --- |
| highlightRegex (Pattern, Color, [IFindResultCallback](../ifindresultcallback)) | Highlights all matches of the regular expression with the specified color. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| regex | Pattern | The regular expression java.util.regex.Pattern to get strings to highlight. |
| highlightColor | Color | The color to highlight the text. |
| callback | [IFindResultCallback](../ifindresultcallback) | The callback object for receiving search results IFindResultCallback. |

 **Returns:**
void


---


### highlightText {#highlightText}

| Name | Description |
| --- | --- |
| highlightText (String, Color) | Highlights all matches of the sample text with the specified color. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| text | String | Text sample to highlight. |
| highlightColor | Color | The color to highlight the text. |

 **Returns:**
void


---


### highlightText {#highlightText}

| Name | Description |
| --- | --- |
| highlightText (String, Color, [TextHighlightingOptions](../texthighlightingoptions)) | Highlights all matches of the sample text with the specified color. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| text | String | The text to highlight. |
| highlightColor | Color | The color to highlight the text. |
| options | [TextHighlightingOptions](../texthighlightingoptions) | Highlighting options. |

 **Returns:**
void


---


### highlightText {#highlightText}

| Name | Description |
| --- | --- |
| highlightText (String, Color, [TextSearchOptions](../textsearchoptions), [IFindResultCallback](../ifindresultcallback)) | Highlights all matches of the sample text with the specified color. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| text | String | The text to highlight. |
| highlightColor | Color | The color to highlight the text. |
| options | [TextSearchOptions](../textsearchoptions) | Text search options ITextSearchOptions. |
| callback | [IFindResultCallback](../ifindresultcallback) | The callback object for receiving search results IFindResultCallback. |

 **Returns:**
void


---


### joinPortionsWithSameFormatting {#joinPortionsWithSameFormatting}

| Name | Description |
| --- | --- |
| joinPortionsWithSameFormatting () | Joins runs with same formatting in all paragraphs. |

 **Returns:**
void


---


### replaceRegex {#replaceRegex}

| Name | Description |
| --- | --- |
| replaceRegex (Pattern, String, [IFindResultCallback](../ifindresultcallback)) | Replaces all matches of regular expression with specified string. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| regex | Pattern | The regular expression java.util.regex.Pattern to get strings to be replaced. |
| newText | String | The string to replace all occurrences of strings to be replaced. |
| callback | [IFindResultCallback](../ifindresultcallback) | Callback object for saving replacement operation result IFindResultCallback. |

 **Returns:**
void


---


### replaceText {#replaceText}

| Name | Description |
| --- | --- |
| replaceText (String, String, [TextSearchOptions](../textsearchoptions), [IFindResultCallback](../ifindresultcallback)) | Replaces all occurrences of the specified text with another specified text. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| oldText | String | The string to be replaced. |
| newText | String | The string to replace all occurrences of oldText. |
| options | [TextSearchOptions](../textsearchoptions) | Text search options ITextSearchOptions. |
| callback | [IFindResultCallback](../ifindresultcallback) | Callback object for saving replacement operation result IFindResultCallback. |

 **Returns:**
void


---


### setText {#setText}

| Name | Description |
| --- | --- |
| setText (String) | Gets or sets the plain text for a TextFrame. Read/write String. Value: The text. |

 **Returns:**
void


---


