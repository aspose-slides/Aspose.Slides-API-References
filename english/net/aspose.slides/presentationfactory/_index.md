---
title: PresentationFactory
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 8880
url: /net/aspose.slides/presentationfactory/
---
## PresentationFactory class

Allows to create presentation via COM interface

```csharp
public class PresentationFactory : IPresentationFactory
```

## Constructors

| Name | Description |
| --- | --- |
| [PresentationFactory](presentationfactory)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| static [Instance](../../aspose.slides/presentationfactory/instance) { get; } | Presentation factory static instance. Read-only [`PresentationFactory`](../presentationfactory). |

## Methods

| Name | Description |
| --- | --- |
| [CreatePresentation](../../aspose.slides/presentationfactory/createpresentation)() | Creates new presentation. |
| [CreatePresentation](../../aspose.slides/presentationfactory/createpresentation)(ILoadOptions) | Creates new presentation with additional load options |
| [GetPresentationInfo](../../aspose.slides/presentationfactory/getpresentationinfo)(Stream) | Creates new PresentationInfo object from stream and binds presentation to it. Gets info about presentation in specified stream. |
| [GetPresentationInfo](../../aspose.slides/presentationfactory/getpresentationinfo)(string) | Creates new PresentationInfo object from file and binds presentation to it. |
| [GetPresentationText](../../aspose.slides/presentationfactory/getpresentationtext)(Stream, TextExtractionArrangingMode) | Retrieves the raw text from the slides |
| [GetPresentationText](../../aspose.slides/presentationfactory/getpresentationtext)(string, TextExtractionArrangingMode) | Retrieves the raw text from the slides |
| [GetPresentationText](../../aspose.slides/presentationfactory/getpresentationtext)(Stream, TextExtractionArrangingMode, ILoadOptions) | Retrieves the raw text from the slides |
| [ReadPresentation](../../aspose.slides/presentationfactory/readpresentation)(byte[]) | Reads an existing presentation from array |
| [ReadPresentation](../../aspose.slides/presentationfactory/readpresentation)(Stream) | Reads an existing presentation from stream |
| [ReadPresentation](../../aspose.slides/presentationfactory/readpresentation)(string) | Reads an existing presentation from file |
| [ReadPresentation](../../aspose.slides/presentationfactory/readpresentation)(byte[], ILoadOptions) | Reads an existing presentation from array with additional load options |
| [ReadPresentation](../../aspose.slides/presentationfactory/readpresentation)(Stream, ILoadOptions) | Reads an existing presentation from stream with additional load options |
| [ReadPresentation](../../aspose.slides/presentationfactory/readpresentation)(string, ILoadOptions) | Reads an existing presentation from stream with additional load options |

### See Also

* interface [IPresentationFactory](../ipresentationfactory)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
