---
title: TextFrame
type: docs
weight: 0
url: /php-java/textframe/
---

# TextFrame class

  Represents a TextFrame.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [getHyperlinkQueries](/php-java/textframe/gethyperlinkqueries/)() | IHyperlinkQueries | Provides easy access to contained hyperlinks. Read-only IHyperlinkQueries. |
| [getParagraphs](/php-java/textframe/getparagraphs/)() | IParagraphCollection | Returns the list of all paragraphs in a frame. Read-only IParagraphCollection. |
| [getPresentation](/php-java/textframe/getpresentation/)() | IPresentation | Returns the parent presentation of a TextFrame. Read-only IPresentation. |
| [getSlide](/php-java/textframe/getslide/)() | IBaseSlide | Returns the parent slide of a TextFrame. Read-only IBaseSlide. |
| [getText](/php-java/textframe/gettext/)() | String | Gets or sets the plain text for a TextFrame. Read/write String. Value: The text. |
| [getTextFrameFormat](/php-java/textframe/gettextframeformat/)() | ITextFrameFormat | Returns the formatting object for this TextFrame object. Read-only ITextFrameFormat. |
| [highlightRegex](/php-java/textframe/highlightregex/)(String, Color, ITextHighlightingOptions) | void | Highlight all matches of regular expression in text frame text using specified color. |
| [highlightText](/php-java/textframe/highlighttext/)(String, Color) | void | Highlight all matches of sample in text frame text using specified color. |
| [highlightText](/php-java/textframe/highlighttext/)(String, Color, ITextHighlightingOptions) | void | Highlight all matches of sample in text frame text using specified color. |
| [joinPortionsWithSameFormatting](/php-java/textframe/joinportionswithsameformatting/)() | void | Joins runs with same formatting in all paragraphs. |
| [setText](/php-java/textframe/settext/)(String) | void | Gets or sets the plain text for a TextFrame. Read/write String. Value: The text. |
