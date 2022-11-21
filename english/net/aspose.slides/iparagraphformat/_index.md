---
title: IParagraphFormat
second_title: Aspose.Sildes for .NET API Reference
description: This class contains the paragraph formatting properties. Unlike IParagraphFormatEffectiveData./iparagraphformateffectivedata all properties of this class are writeable.
type: docs
weight: 6110
url: /net/aspose.slides/iparagraphformat/
---
## IParagraphFormat interface

This class contains the paragraph formatting properties. Unlike [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata), all properties of this class are writeable.

```csharp
public interface IParagraphFormat
```

## Properties

| Name | Description |
| --- | --- |
| [Alignment](../../aspose.slides/iparagraphformat/alignment) { get; set; } | Returns or sets the text alignment in a paragraph with no inheritance. Read/write [`TextAlignment`](../textalignment). |
| [Bullet](../../aspose.slides/iparagraphformat/bullet) { get; } | Returns bullet format of the paragraph. Read-only [`IBulletFormat`](../ibulletformat). |
| [DefaultPortionFormat](../../aspose.slides/iparagraphformat/defaultportionformat) { get; } | Returns default portion format of a paragraph. No inheritance applied. Read-only [`IPortionFormat`](../iportionformat). |
| [DefaultTabSize](../../aspose.slides/iparagraphformat/defaulttabsize) { get; set; } | Returns or sets default tabulation size with no inheritance. Read/write Single. |
| [Depth](../../aspose.slides/iparagraphformat/depth) { get; set; } | Returns or sets depth of the paragraph. Value 0 means undefined value. Read/write Int16. |
| [EastAsianLineBreak](../../aspose.slides/iparagraphformat/eastasianlinebreak) { get; set; } | Determines whether the East Asian line break is used in a paragraph. No inheritance applied. Read/write [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/iparagraphformat/fontalignment) { get; set; } | Returns or sets a font alignment in a paragraph with no inheritance. Read/write [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/iparagraphformat/hangingpunctuation) { get; set; } | Determines whether the hanging punctuation is used in a paragraph. No inheritance applied. Read/write [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/iparagraphformat/indent) { get; set; } | Returns or sets paragraph First Line Indent/Hanging Indent with no inheritance. Hanging Indent can be defined with negative values. Read/write Single. |
| [LatinLineBreak](../../aspose.slides/iparagraphformat/latinlinebreak) { get; set; } | Determines whether the Latin line break is used in a paragraph. No inheritance applied. Read/write [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/iparagraphformat/marginleft) { get; set; } | Returns or sets the left margin in a paragraph with no inheritance. Read/write Single. |
| [MarginRight](../../aspose.slides/iparagraphformat/marginright) { get; set; } | Returns or sets the right margin in a paragraph with no inheritance. Read/write Single. |
| [RightToLeft](../../aspose.slides/iparagraphformat/righttoleft) { get; set; } | Determines whether the Right to Left writing is used in a paragraph. No inheritance applied. Read/write [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/iparagraphformat/spaceafter) { get; set; } | Returns or sets the amount of space after the last line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write Single. |
| [SpaceBefore](../../aspose.slides/iparagraphformat/spacebefore) { get; set; } | Returns or sets the amount of space before the first line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write Single. |
| [SpaceWithin](../../aspose.slides/iparagraphformat/spacewithin) { get; set; } | Returns or sets the amount of space between base lines in a paragraph. Positive value means percentage, negative - size in points. No inheritance applied. Read/write Single. |
| [Tabs](../../aspose.slides/iparagraphformat/tabs) { get; } | Returns tabulations of a paragraph. No inheritance applied. Read-only [`ITabCollection`](../itabcollection). |

## Methods

| Name | Description |
| --- | --- |
| [GetEffective](../../aspose.slides/iparagraphformat/geteffective)() | Gets effective paragraph formatting data with the inheritance applied. |

### Remarks

This class is used to return and manipulate paragraph formatting properties defined for the particular paragraph. This means that no inheritance is applied when getting values so for the majority of cases you will get values meaning "undefined".

In order to get the effective formatting parameter values including inherited you need to use [`GetEffective`](./geteffective) method which returns a [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) instance.

### See Also

* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
