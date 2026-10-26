---
title: IParagraphFormat class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/iparagraphformat/
---
## IParagraphFormat klasse

Deze klasse bevat de alinea-opmaak eigenschappen. In tegenstelling tot [`IParagraphFormatEffectiveData`](/slides/python-net/nl/aspose.slides/iparagraphformateffectivedata) zijn alle eigenschappen van deze klasse schrijfbaar.

Het IParagraphFormat type exposeert de volgende leden:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`bullet`](/slides/python-net/nl/aspose.slides/iparagraphformat/bullet/) | Returns bullet format of the paragraph.<br/>            Alleen-lezen [`IBulletFormat`](/slides/python-net/nl/aspose.slides/ibulletformat). |
| [`depth`](/slides/python-net/nl/aspose.slides/iparagraphformat/depth/) | Returns or sets depth of the paragraph.<br/>            Value 0 means undefined value.<br/>            Lezen/schrijven **int**. |
| [`alignment`](/slides/python-net/nl/aspose.slides/iparagraphformat/alignment/) | Returns or sets the text alignment in a paragraph with no inheritance.<br/>            Lezen/schrijven [`TextAlignment`](/slides/python-net/nl/aspose.slides/textalignment). |
| [`space_within`](/slides/python-net/nl/aspose.slides/iparagraphformat/space_within/) | Returns or sets the amount of space between base lines in a paragraph. Positive value means percentage, negative - size in points. No inheritance applied.<br/>            Lezen/schrijven **float**. |
| [`space_before`](/slides/python-net/nl/aspose.slides/iparagraphformat/space_before/) | Returns or sets the amount of space before the first line in a paragraph with no inheritance.<br/>            A positive value specifies the percentage of the font size that the white space should be.<br/>            A negative value specifies the size of the white space in point size.<br/>            Lezen/schrijven **float**. |
| [`space_after`](/slides/python-net/nl/aspose.slides/iparagraphformat/space_after/) | Returns or sets the amount of space after the last line in a paragraph with no inheritance.<br/>            A positive value specifies the percentage of the font size that the white space should be.<br/>            A negative value specifies the size of the white space in point size.<br/>            Lezen/schrijven **float**. |
| [`east_asian_line_break`](/slides/python-net/nl/aspose.slides/iparagraphformat/east_asian_line_break/) | Determines whether the East Asian line break is used in a paragraph. No inheritance applied.<br/>            Lezen/schrijven [`NullableBool`](/slides/python-net/nl/aspose.slides/nullablebool). |
| [`right_to_left`](/slides/python-net/nl/aspose.slides/iparagraphformat/right_to_left/) | Determines whether the Right to Left writing is used in a paragraph. No inheritance applied.<br/>            Lezen/schrijven [`NullableBool`](/slides/python-net/nl/aspose.slides/nullablebool). |
| [`latin_line_break`](/slides/python-net/nl/aspose.slides/iparagraphformat/latin_line_break/) | Determines whether the Latin line break is used in a paragraph. No inheritance applied.<br/>            Lezen/schrijven [`NullableBool`](/slides/python-net/nl/aspose.slides/nullablebool). |
| [`hanging_punctuation`](/slides/python-net/nl/aspose.slides/iparagraphformat/hanging_punctuation/) | Determines whether the hanging punctuation is used in a paragraph. No inheritance applied.<br/>            Lezen/schrijven [`NullableBool`](/slides/python-net/nl/aspose.slides/nullablebool). |
| [`margin_left`](/slides/python-net/nl/aspose.slides/iparagraphformat/margin_left/) | Returns or sets the left margin in a paragraph with no inheritance.<br/>            Lezen/schrijven **float**. |
| [`margin_right`](/slides/python-net/nl/aspose.slides/iparagraphformat/margin_right/) | Returns or sets the right margin in a paragraph with no inheritance.<br/>            Lezen/schrijven **float**. |
| [`indent`](/slides/python-net/nl/aspose.slides/iparagraphformat/indent/) | Returns or sets paragraph First Line Indent/Hanging Indent with no inheritance. Hanging Indent can be defined with negative values.<br/>            Lezen/schrijven **float**. |
| [`default_tab_size`](/slides/python-net/nl/aspose.slides/iparagraphformat/default_tab_size/) | Returns or sets default tabulation size with no inheritance.<br/>            Lezen/schrijven **float**. |
| [`tabs`](/slides/python-net/nl/aspose.slides/iparagraphformat/tabs/) | Returns tabulations of a paragraph. No inheritance applied.<br/>            Alleen-lezen [`ITabCollection`](/slides/python-net/nl/aspose.slides/itabcollection). |
| [`font_alignment`](/slides/python-net/nl/aspose.slides/iparagraphformat/font_alignment/) | Returns or sets a font alignment in a paragraph with no inheritance.<br/>            Lezen/schrijven [`FontAlignment`](/slides/python-net/nl/aspose.slides/fontalignment). |
| [`default_portion_format`](/slides/python-net/nl/aspose.slides/iparagraphformat/default_portion_format/) | Returns default portion format of a paragraph. No inheritance applied.<br/>            Alleen-lezen [`IPortionFormat`](/slides/python-net/nl/aspose.slides/iportionformat). |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/nl/aspose.slides/iparagraphformat/get_effective/#) | Gets effective paragraph formatting data with the inheritance applied. |

### Opmerkingen

Deze klasse wordt gebruikt om alinea-opmaak eigenschappen die voor een bepaalde alinea zijn gedefinieerd, op te halen en te manipuleren. Dit betekent dat er geen erfelijkheid wordt toegepast bij het ophalen van waarden, dus in de meeste gevallen krijg je waarden die “onbepaald” betekenen.

Om de effectieve opmaakparameterwaarden inclusief geërfde waarden te verkrijgen, moet je de [`IParagraphFormat.get_effective`](/slides/python-net/nl/aspose.slides/iparagraphformat/get_effective) methode gebruiken die een [`IParagraphFormatEffectiveData`](/slides/python-net/nl/aspose.slides/iparagraphformateffectivedata) instantie retourneert.

### Zie ook
* klasse [`IParagraphFormatEffectiveData`](/slides/python-net/nl/aspose.slides/iparagraphformateffectivedata)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)