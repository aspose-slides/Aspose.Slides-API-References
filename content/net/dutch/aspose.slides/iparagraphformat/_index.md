---
title: IParagraphFormat
second_title: Aspose.Sildes voor .NET API-referentie
description: Deze klasse bevat de alinea-opmaak eigenschappen. In tegenstelling tot IParagraphFormatEffectiveData./iparagraphformateffectivedata zijn alle eigenschappen van deze klasse schrijfbaar.
type: docs
weight: 6610
url: /nl/aspose.slides/iparagraphformat/
---
## IParagraphFormat interface

Deze klasse bevat de alinea-opmaak eigenschappen. In tegenstelling tot [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) zijn alle eigenschappen van deze klasse schrijfbaar.

```csharp
public interface IParagraphFormat
```

## Eigenschappen

| Name | Description |
| --- | --- |
| [Alignment](../../aspose.slides/iparagraphformat/alignment) { get; set; } | Returns or sets the text alignment in a paragraph with no inheritance. Lezen/Schrijven [`TextAlignment`](../textalignment). |
| [Bullet](../../aspose.slides/iparagraphformat/bullet) { get; } | Returns bullet format of the paragraph. Alleen-lezen [`IBulletFormat`](../ibulletformat). |
| [DefaultPortionFormat](../../aspose.slides/iparagraphformat/defaultportionformat) { get; } | Returns default portion format of a paragraph. No inheritance applied. Alleen-lezen [`IPortionFormat`](../iportionformat). |
| [DefaultTabSize](../../aspose.slides/iparagraphformat/defaulttabsize) { get; set; } | Returns or sets default tabulation size with no inheritance. Lezen/Schrijven Single. |
| [Depth](../../aspose.slides/iparagraphformat/depth) { get; set; } | Returns or sets depth of the paragraph. Value 0 means undefined value. Lezen/Schrijven Int16. |
| [EastAsianLineBreak](../../aspose.slides/iparagraphformat/eastasianlinebreak) { get; set; } | Determines whether the East Asian line break is used in a paragraph. No inheritance applied. Lezen/Schrijven [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/iparagraphformat/fontalignment) { get; set; } | Returns or sets a font alignment in a paragraph with no inheritance. Lezen/Schrijven [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/iparagraphformat/hangingpunctuation) { get; set; } | Determines whether the hanging punctuation is used in a paragraph. No inheritance applied. Lezen/Schrijven [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/iparagraphformat/indent) { get; set; } | Returns or sets paragraph First Line Indent/Hanging Indent with no inheritance. Hanging Indent can be defined with negative values. Lezen/Schrijven Single. |
| [LatinLineBreak](../../aspose.slides/iparagraphformat/latinlinebreak) { get; set; } | Determines whether the Latin line break is used in a paragraph. No inheritance applied. Lezen/Schrijven [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/iparagraphformat/marginleft) { get; set; } | Returns or sets the left margin in a paragraph with no inheritance. Lezen/Schrijven Single. |
| [MarginRight](../../aspose.slides/iparagraphformat/marginright) { get; set; } | Returns or sets the right margin in a paragraph with no inheritance. Lezen/Schrijven Single. |
| [RightToLeft](../../aspose.slides/iparagraphformat/righttoleft) { get; set; } | Determines whether the Right to Left writing is used in a paragraph. No inheritance applied. Lezen/Schrijven [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/iparagraphformat/spaceafter) { get; set; } | Returns or sets the amount of space after the last line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Lezen/Schrijven Single. |
| [SpaceBefore](../../aspose.slides/iparagraphformat/spacebefore) { get; set; } | Returns or sets the amount of space before the first line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Lezen/Schrijven Single. |
| [SpaceWithin](../../aspose.slides/iparagraphformat/spacewithin) { get; set; } | Returns or sets the amount of space between base lines in a paragraph. Positive value means percentage, negative - size in points. No inheritance applied. Lezen/Schrijven Single. |
| [Tabs](../../aspose.slides/iparagraphformat/tabs) { get; } | Returns tabulations of a paragraph. No inheritance applied. Alleen-lezen [`ITabCollection`](../itabcollection). |

## Methoden

| Name | Description |
| --- | --- |
| [GetEffective](../../aspose.slides/iparagraphformat/geteffective)() | Gets effective paragraph formatting data with the inheritance applied. |

### Opmerkingen

Deze klasse wordt gebruikt om de alinea-opmaak eigenschappen die voor een bepaalde alinea zijn gedefinieerd, op te halen en te bewerken. Dit betekent dat er geen overerving wordt toegepast bij het ophalen van waarden, dus in de meeste gevallen krijg je waarden die "onbepaald" betekenen.

Om de effectieve opmaakparameterwaarden inclusief geërfde waarden te verkrijgen, moet je de [`GetEffective`](./geteffective) methode gebruiken die een [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) instantie retourneert.

### Zie ook

* naamruimte [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->