---
title: IPortion
second_title: Aspose.Sildes for .NET API Reference
description: Represents a portion of text inside a text paragraph.
type: docs
weight: 6560
url: /aspose.slides/iportion/
---

## IPortion interface

Represents a portion of text inside a text paragraph.

```csharp
public interface IPortion : ISlideComponent
```

## Properties

| Name | Description |
| --- | --- |
| [AsISlideComponent](../../aspose.slides/iportion/asislidecomponent) { get; } | Allows to get base ISlideComponent interface. Read-only [`ISlideComponent`](../islidecomponent). |
| [Field](../../aspose.slides/iportion/field) { get; } | Returns a field of this portion. Read-only [`IField`](../ifield). |
| [PortionFormat](../../aspose.slides/iportion/portionformat) { get; } | Returns formatting object which contains explicitly set formatting properties of the text portion with no inheritance applied. Read-only [`IPortionFormat`](../iportionformat). |
| [Text](../../aspose.slides/iportion/text) { get; set; } | Gets or sets the plain text of a portion. Read/write String. |

## Methods

| Name | Description |
| --- | --- |
| [AddField](../../aspose.slides/iportion/addfield#addfield)(IFieldType) | Converts this portion to the automaticaly updated field. |
| [AddField](../../aspose.slides/iportion/addfield#addfield_1)(string) | Converts this portion to the automaticaly updated field. |
| [GetCoordinates](../../aspose.slides/iportion/getcoordinates)() | Get coordinates of the beginning of the portion. The X coordinate of point represents the portion beginning from the first character including left side bearing. The Y coordinate includes top side bearing. |
| [GetRect](../../aspose.slides/iportion/getrect)() | Get coordinates of rect that bounds portion. The rect includes all the lines of text in portion, including empty ones. |
| [RemoveField](../../aspose.slides/iportion/removefield)() | Converts this field portion to the simple portion. |

### See Also

* interface [ISlideComponent](../islidecomponent)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
