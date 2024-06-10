---
title: ParagraphFormat
second_title: Aspose.Sildes for .NET API Reference
description: This class contains the paragraph formatting properties. Unlike IParagraphFormatEffectiveData./iparagraphformateffectivedata all properties of this class are writeable.
type: docs
weight: 8890
url: /aspose.slides/paragraphformat/
---

## ParagraphFormat class

This class contains the paragraph formatting properties. Unlike [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata), all properties of this class are writeable.

```csharp
public sealed class ParagraphFormat : PVIObject, IChartParagraphFormat, IParagraphFormat
```

## Constructors

| Name | Description |
| --- | --- |
| [ParagraphFormat](paragraphformat)() | Initializes a new instance of [`ParagraphFormat`](../paragraphformat) class. |

## Properties

| Name | Description |
| --- | --- |
| [Alignment](../../aspose.slides/paragraphformat/alignment) { get; set; } | Returns or sets the text alignment in a paragraph with no inheritance. Read/write [`TextAlignment`](../textalignment). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Allows to get base IPresentationComponent interface. Read-only [`IPresentationComponent`](../ipresentationcomponent). |
| [DefaultTabSize](../../aspose.slides/paragraphformat/defaulttabsize) { get; set; } | Returns or sets default tabulation size with no inheritance. Read/write Single. |
| [EastAsianLineBreak](../../aspose.slides/paragraphformat/eastasianlinebreak) { get; set; } | Determines whether the East Asian line break is used in a paragraph. No inheritance applied. Read/write [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/paragraphformat/fontalignment) { get; set; } | Returns or sets a font alignment in a paragraph with no inheritance. Read/write [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/paragraphformat/hangingpunctuation) { get; set; } | Determines whether the hanging punctuation is used in a paragraph. No inheritance applied. Read/write [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/paragraphformat/indent) { get; set; } | Returns or sets paragraph First Line Indent/Hanging Indent with no inheritance. Hanging Indent can be defined with negative values. Read/write Single. |
| [LatinLineBreak](../../aspose.slides/paragraphformat/latinlinebreak) { get; set; } | Determines whether the Latin line break is used in a paragraph. No inheritance applied. Read/write [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/paragraphformat/marginleft) { get; set; } | Returns or sets the left margin in a paragraph with no inheritance. Read/write Single. |
| [MarginRight](../../aspose.slides/paragraphformat/marginright) { get; set; } | Returns or sets the right margin in a paragraph with no inheritance. Read/write Single. |
| [RightToLeft](../../aspose.slides/paragraphformat/righttoleft) { get; set; } | Determines whether the Right to Left writing is used in a paragraph. No inheritance applied. Read/write [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/paragraphformat/spaceafter) { get; set; } | Returns or sets the amount of space after the last line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write Single. |
| [SpaceBefore](../../aspose.slides/paragraphformat/spacebefore) { get; set; } | Returns or sets the amount of space before the first line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write Single. |
| [SpaceWithin](../../aspose.slides/paragraphformat/spacewithin) { get; set; } | Returns or sets the amount of space between base lines in a paragraph. Positive value means percentage, negative - size in points. No inheritance applied. Read/write Single. |
| [Tabs](../../aspose.slides/paragraphformat/tabs) { get; } | Returns tabulations of a paragraph. No inheritance applied. Read-only [`ITabCollection`](../itabcollection). |

## Methods

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compares with specified object. |
| [GetEffective](../../aspose.slides/paragraphformat/geteffective)() | Gets effective paragraph formatting data with the inheritance applied. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Returns hash code. |

### Remarks

This class is used to return and manipulate paragraph formatting properties defined for the particular paragraph. This means that no inheritance is applied when getting values so for the majority of cases you will get values meaning "undefined".

In order to get the effective formatting parameter values including inherited you need to use [`GetEffective`](./geteffective) method which returns a [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) instance.

### See Also

* class [PVIObject](../pviobject)
* interface [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat)
* interface [IParagraphFormat](../iparagraphformat)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
