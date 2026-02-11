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


### getParentCell {#getParentCell}

| Name | Description |
| --- | --- |
| getParentCell () | Returns the parent cell or null if the parent object does not implement the ICell interface. Read-only ICell. |

 **Returns:**
[Cell](../cell)


---


### getParentShape {#getParentShape}

| Name | Description |
| --- | --- |
| getParentShape () | Returns the parent shape or null if the parent object does not implement the IShape interface Read-only IShape. |

 **Returns:**
[VideoFrame](../videoframe), [Shape](../shape), [SmartArt](../smartart), [PictureFrame](../pictureframe), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [GraphicalObject](../graphicalobject), [GroupShape](../groupshape), [AudioFrame](../audioframe), [AutoShape](../autoshape), [ZoomObject](../zoomobject), [Chart](../chart), [SummaryZoomFrame](../summaryzoomframe), [ZoomFrame](../zoomframe), [LegacyDiagram](../legacydiagram), [SectionZoomFrame](../sectionzoomframe), [InkActions](../inkactions), [Connector](../connector), [SummaryZoomSection](../summaryzoomsection), [GeometryShape](../geometryshape)


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
[NotesSlide](../notesslide), [MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [MasterNotesSlide](../masternotesslide), [Slide](../slide), [MasterSlide](../masterslide)


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


---


### joinPortionsWithSameFormatting {#joinPortionsWithSameFormatting}

| Name | Description |
| --- | --- |
| joinPortionsWithSameFormatting () | Joins runs with same formatting in all paragraphs. |


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


---


### setText {#setText}

| Name | Description |
| --- | --- |
| setText (String) | Gets or sets the plain text for a TextFrame. Read/write String. Value: The text. |


---


### splitTextByColumns {#splitTextByColumns}

| Name | Description |
| --- | --- |
| splitTextByColumns () | Splits the text content of the ITextFrame into an array of strings, where each element corresponds to a separate text column within the frame. |

 **Returns:**
String


---


