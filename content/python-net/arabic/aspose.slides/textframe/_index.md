---
title: TextFrame class
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/textframe/
---
## فئة TextFrame

يمثل TextFrame.

يكشف نوع TextFrame عن الأعضاء التالية:

## الخصائص

| Property | Description |
| :- | :- |
| [`paragraphs`](/slides/python-net/ar/aspose.slides/textframe/paragraphs/) | Returns the list of all paragraphs in a frame.<br/> Read-only [`IParagraphCollection`](/slides/python-net/ar/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/ar/aspose.slides/textframe/text/) | Gets or sets the plain text for a TextFrame.<br/> قراءة/كتابة **str**. |
| [`text_frame_format`](/slides/python-net/ar/aspose.slides/textframe/text_frame_format/) | Returns the formatting object for this TextFrame object.<br/> Read-only [`ITextFrameFormat`](/slides/python-net/ar/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/ar/aspose.slides/textframe/hyperlink_queries/) | Provides easy access to contained hyperlinks.<br/> Read-only [`IHyperlinkQueries`](/slides/python-net/ar/aspose.slides/ihyperlinkqueries). |
| [`slide`](/slides/python-net/ar/aspose.slides/textframe/slide/) | Returns the parent slide of a TextFrame.<br/> Read-only [`IBaseSlide`](/slides/python-net/ar/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ar/aspose.slides/textframe/presentation/) | Returns the parent presentation of a TextFrame.<br/> Read-only [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation). |
| [`parent_shape`](/slides/python-net/ar/aspose.slides/textframe/parent_shape/) | Returns the parent shape or None if the parent object does not implement the IShape interface<br/> Read-only [`IShape`](/slides/python-net/ar/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/ar/aspose.slides/textframe/parent_cell/) | Returns the parent cell or None if the parent object does not implement the ICell interface.<br/> Read-only [`ICell`](/slides/python-net/ar/aspose.slides/icell). |

## الطرق

| Method | Description |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/ar/aspose.slides/textframe/highlight_text/#str-asposeslidescolor) | Highlights all matches of the sample text with the specified color. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/ar/aspose.slides/textframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | Highlights all matches of the sample text with the specified color. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/ar/aspose.slides/textframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Highlights all matches of the sample text with the specified color. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/ar/aspose.slides/textframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | Highlights all matches of the regular expression with the specified color. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/ar/aspose.slides/textframe/highlight_regex/#str-asposeslidescolor) | Highlights all matches of the regular expression with the specified color. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ar/aspose.slides/textframe/join_portions_with_same_formatting/#) | Joins runs with same formatting in all paragraphs. |
| [`split_text_by_columns(self)`](/slides/python-net/ar/aspose.slides/textframe/split_text_by_columns/#) | Splits the text content of the [`ITextFrame`](/slides/python-net/ar/aspose.slides/itextframe) into an array of strings,<br/> where each element corresponds to a separate text column within the frame. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/ar/aspose.slides/textframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Replaces all occurrences of the specified text with another specified text. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/ar/aspose.slides/textframe/replace_regex/#str-str) | Replaces all matches of regular expression with specified string. |

### أنظر أيضًا
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)