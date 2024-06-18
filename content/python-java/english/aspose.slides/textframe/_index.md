---
title: TextFrame
second_title: Aspose.Sildes for Python via Java API Reference
description: 
type: docs

url: /aspose.slides/textframe/
---

## TextFrame class

  Represents a TextFrame.
 
### getHyperlinkQueries {#getHyperlinkQueries}

| Name | Description |
| --- | --- |
| getHyperlinkQueries() | Provides easy access to contained hyperlinks. Read-only IHyperlinkQueries. |

 **Returns:**
[HyperlinkQueries](../hyperlinkqueries)


---


### getParagraphs {#getParagraphs}

| Name | Description |
| --- | --- |
| getParagraphs() | Returns the list of all paragraphs in a frame. Read-only IParagraphCollection. |

 **Returns:**
[ParagraphCollection](../paragraphcollection)


---


### getPresentation {#getPresentation}

| Name | Description |
| --- | --- |
| getPresentation() | Returns the parent presentation of a TextFrame. Read-only IPresentation. |

 **Returns:**
[Presentation](../presentation)


---


### getSlide {#getSlide}

| Name | Description |
| --- | --- |
| getSlide() | Returns the parent slide of a TextFrame. Read-only IBaseSlide. |

 **Returns:**
[Slide](../slide), [MasterSlide](../masterslide), [LayoutSlide](../layoutslide), [MasterHandoutSlide](../masterhandoutslide), [NotesSlide](../notesslide), [BaseSlide](../baseslide), [MasterNotesSlide](../masternotesslide)


---


### getText {#getText}

| Name | Description |
| --- | --- |
| getText() | Gets or sets the plain text for a TextFrame. Read/write String. Value: The text. |

 **Returns:**
String


---


### getTextFrameFormat {#getTextFrameFormat}

| Name | Description |
| --- | --- |
| getTextFrameFormat() | Returns the formatting object for this TextFrame object. Read-only ITextFrameFormat. |

 **Returns:**
[TextFrameFormat](../textframeformat)


---


### highlightRegex {#highlightRegex}

| Name | Description |
| --- | --- |
| highlightRegex(String, Color, [TextHighlightingOptions](../texthighlightingoptions)) | Highlight all matches of regular expression in text frame text using specified color. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| regex | String | Text of regular expression to get text to highlight. |
| highlightColor | Color | Highlighting color. |
| options | [TextHighlightingOptions](../texthighlightingoptions) | Highlighting options. |


---


### highlightRegex {#highlightRegex}

| Name | Description |
| --- | --- |
| highlightRegex(Pattern, Color, [IFindResultCallback](../ifindresultcallback)) | Highlight all matches of regular expression in text frame text using specified color. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| regex | Pattern | The regular expression java.util.regex.Pattern to get strings to be replaced. |
| highlightColor | Color | Highlighting color. |
| callback | [IFindResultCallback](../ifindresultcallback) | Callback object for saving replacement operation result IFindResultCallback. |


---


### highlightText {#highlightText}

| Name | Description |
| --- | --- |
| highlightText(String, Color) | Highlight all matches of sample in text frame text using specified color. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| text | String | Text sample to highlight. |
| highlightColor | Color | Highlighting color. |


---


### highlightText {#highlightText}

| Name | Description |
| --- | --- |
| highlightText(String, Color, [TextHighlightingOptions](../texthighlightingoptions)) | Highlight all matches of sample in text frame text using specified color. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| text | String | Text sample to highlight. |
| highlightColor | Color | Highlighting color. |
| options | [TextHighlightingOptions](../texthighlightingoptions) | Highlighting options. |


---


### highlightText {#highlightText}

| Name | Description |
| --- | --- |
| highlightText(String, Color, [TextSearchOptions](../textsearchoptions), [IFindResultCallback](../ifindresultcallback)) | Highlight all matches of sample in text frame text using specified color. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| text | String | Text sample to highlight. |
| highlightColor | Color | Highlighting color. |
| options | [TextSearchOptions](../textsearchoptions) | Text search options ITextSearchOptions. |
| callback | [IFindResultCallback](../ifindresultcallback) | Callback object for saving replacement operation result IFindResultCallback. |


---


### joinPortionsWithSameFormatting {#joinPortionsWithSameFormatting}

| Name | Description |
| --- | --- |
| joinPortionsWithSameFormatting() | Joins runs with same formatting in all paragraphs. |


---


### replaceRegex {#replaceRegex}

| Name | Description |
| --- | --- |
| replaceRegex(Pattern, String, [IFindResultCallback](../ifindresultcallback)) | Replaces all matches of regular expression with specified string. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| regex | Pattern | The regular expression java.util.regex.Pattern to get strings to be replaced. |
| newText | String | The string to replace all occurrences of strings to be replaced. |
| callback | [IFindResultCallback](../ifindresultcallback) | Callback object for saving replacement operation result IFindResultCallback. |


---


### replaceText {#replaceText}

| Name | Description |
| --- | --- |
| replaceText(String, String, [TextSearchOptions](../textsearchoptions), [IFindResultCallback](../ifindresultcallback)) | Replaces all occurrences of the specified text with another specified text. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| oldText | String | The string to be replaced. |
| newText | String | The string to replace all occurrences of oldText. |
| options | [TextSearchOptions](../textsearchoptions) | Text search options ITextSearchOptions. |
| callback | [IFindResultCallback](../ifindresultcallback) | Callback object for saving replacement operation result IFindResultCallback. |


---


### setText {#setText}

| Name | Description |
| --- | --- |
| setText(String) | Gets or sets the plain text for a TextFrame. Read/write String. Value: The text. |


---


