---
title: Hyperlink
second_title: Aspose.Sildes for .NET API Reference
description: Represents a hyperlink.
type: docs
weight: 4980
url: /aspose.slides/hyperlink/
---

## Hyperlink class

Represents a hyperlink.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## Constructors

| Name | Description |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | Creates an instance of a hyperlink which points to specific slide. Note: created hyperlink should be assigned to some object from the same presentation, otherwise link will be saved as NoAction. |
| [Hyperlink](hyperlink#constructor_2)(string) | Creates an instance of a hyperlink. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | Creates an instance of a hyperlink using another hyperlink as source, overriding secondary properties. |

## Properties

| Name | Description |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | Returns a hyperlink which ends the show. Read-only [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | Returns a hyperlink to the first slide of the presentation. Read-only [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | Returns a hyperlink to the last slide of the presentation. Read-only [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | Returns a hyperlink to the last viewed slide. Read-only [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | Returns a special "play mediafile" hyperlink. Used in AudioFrame and VideoFrame. Read-only [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | Returns a hyperlink to the next slide. Read-only [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | Returns a special "do nothing" hyperlink. Read-only [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | Returns a hyperlink to the previous slide. Read-only [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | Returns type of Hyperlink's action. Read-only [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Allows to get base IPresentationComponent interface. Read-only [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | Represents the source of hyperlink color - either styles or portion format. Read/write [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | Specifies the external URL. Read-only String. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | Represents a hyperlink that is set for this portion without regard to the actual content of the portion.  PowerPoint behaves specifically for links and their corresponding text in a portion. It allows to create text for the hyperlink in the form of a valid URL, different from the real address of the link. In this case, when you view the link in the edit window, it will be changed to match the text portion. This property represents the original value of the hyperlink. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | Determines whether the hyperlink should be highlighted on click. Read/write Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | Determines whether the target of the parent hyperlink shall be added to a list of viewed hyperlinks when it is invoked. Read/write Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | Represents the playing sound of the hyperlink. Read/write [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | Determines whether the sound should be stopped on hyperlink click. Read/write Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | Returns the frame within the parent HTML frameset for the target of the parent hyperlink when one exists. Read/wite String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | If the Hyperlink targets specific slide returns this slide. Read-only [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | Returns the string which may be surfaced in a user interface as associated with the parent hyperlink. Read/write String. |

## Methods

| Name | Description |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | Determines whether the two Hyperlink instances are equal. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | Determines whether the two Hyperlink instances are equal. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | Serves as a hash function for a particular type, suitable for use in hashing algorithms and data structures like a hash table. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | Tests two hyperlinks for equality. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | Tests two hyperlinks for inequality. |

### See Also

* class [PVIObject](../pviobject)
* interface [IHyperlink](../ihyperlink)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
