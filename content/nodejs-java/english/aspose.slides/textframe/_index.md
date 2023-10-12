---
title: TextFrame
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/textframe/
---

## TextFrame class

  Represents a TextFrame.
 
| [getHyperlinkQueries] () | Provides easy access to contained hyperlinks. Read-only IHyperlinkQueries. |

### Result
[HyperlinkQueries]


---


| [getParagraphs] () | Returns the list of all paragraphs in a frame. Read-only IParagraphCollection. |

### Result
[ParagraphCollection]


---


| [getPresentation] () | Returns the parent presentation of a TextFrame. Read-only IPresentation. |

### Result
[Presentation]


---


| [getSlide] () | Returns the parent slide of a TextFrame. Read-only IBaseSlide. |

### Result
[MasterNotesSlide], [MasterHandoutSlide], [BaseSlide], [NotesSlide], [LayoutSlide], [Slide], [MasterSlide]


---


| [getText] () | Gets or sets the plain text for a TextFrame. Read/write String. Value: The text. |

### Result
String


---


| [getTextFrameFormat] () | Returns the formatting object for this TextFrame object. Read-only ITextFrameFormat. |

### Result
[TextFrameFormat]


---


| [highlightRegex] ([String], [Color], [TextHighlightingOptions]) | Highlight all matches of regular expression in text frame text using specified color. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| regex | [String] | Text of regular expression to get text to highlight. |
| highlightColor | [Color] | Highlighting color. |
| options | [TextHighlightingOptions] | Highlighting options. |


---


| [highlightText] ([String], [Color]) | Highlight all matches of sample in text frame text using specified color. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| text | [String] | Text sample to highlight. |
| highlightColor | [Color] | Highlighting color. |


---


| [highlightText] ([String], [Color], [TextHighlightingOptions]) | Highlight all matches of sample in text frame text using specified color. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| text | [String] | Text sample to highlight. |
| highlightColor | [Color] | Highlighting color. |
| options | [TextHighlightingOptions] | Highlighting options. |


---


| [joinPortionsWithSameFormatting] () | Joins runs with same formatting in all paragraphs. |


---


| [setText] ([String]) | Gets or sets the plain text for a TextFrame. Read/write String. Value: The text. |


---


