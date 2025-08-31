---
title: ISequence class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.animation/isequence/
---


## ISequence class

Represents sequence (collection of effects).

The ISequence type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`count`](/slides/python-net/aspose.slides.animation/isequence/count/) | Returns the number of effects in a sequense.<br/>            Read-only **int**. |
| [`trigger_shape`](/slides/python-net/aspose.slides.animation/isequence/trigger_shape/) | Returns or sets shape target for INTERACTIVE sequence.<br/>            If sequence is not interactive then returns None.<br/>            Read/write [`IShape`](/slides/python-net/aspose.slides/ishape). |

Returns an effect at the specified index.

## Indexer

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/aspose.slides.animation/isequence/__getitem__/) | Index |

## Methods

| Method | Description |
| :- | :- |
| [`add_effect`](/slides/python-net/aspose.slides.animation/isequence/add_effect/#asposeslidesishape-asposeslidesanimationeffecttype-asposeslidesanimationeffectsubtype-asposeslidesanimationeffecttriggertype) | Add new effect to the end of sequence. |
| [`add_effect`](/slides/python-net/aspose.slides.animation/isequence/add_effect/#asposeslidesiparagraph-asposeslidesanimationeffecttype-asposeslidesanimationeffectsubtype-asposeslidesanimationeffecttriggertype) | Add new animation effect for paragraph to the end of sequence. |
| [`add_effect`](/slides/python-net/aspose.slides.animation/isequence/add_effect/#asposeslideschartsichart-asposeslidesanimationeffectchartmajorgroupingtype-int-asposeslidesanimationeffecttype-asposeslidesanimationeffectsubtype-asposeslidesanimationeffecttriggertype) | Adds the new chart animation effect for category or series to the end of sequence. |
| [`add_effect`](/slides/python-net/aspose.slides.animation/isequence/add_effect/#asposeslideschartsichart-asposeslidesanimationeffectchartminorgroupingtype-int-int-asposeslidesanimationeffecttype-asposeslidesanimationeffectsubtype-asposeslidesanimationeffecttriggertype) | Adds the new chart animation effect for elements in category or series to the end of sequence. |
| [`remove`](/slides/python-net/aspose.slides.animation/isequence/remove/#asposeslidesanimationieffect) | Removes specified effect from a collection. |
| [`remove_at`](/slides/python-net/aspose.slides.animation/isequence/remove_at/#int) | Removes an effect from a collection. |
| [`clear`](/slides/python-net/aspose.slides.animation/isequence/clear/#) | Removes all effects from a collection. |
| [`remove_by_shape`](/slides/python-net/aspose.slides.animation/isequence/remove_by_shape/#asposeslidesishape) | Remove effect for the specified shape. |
| [`get_effects_by_shape`](/slides/python-net/aspose.slides.animation/isequence/get_effects_by_shape/#asposeslidesishape) | Returns array of effects for the specified shape. |
| [`get_effects_by_paragraph`](/slides/python-net/aspose.slides.animation/isequence/get_effects_by_paragraph/#asposeslidesiparagraph) | Returns array of effects for the specified paragraph. |
| [`get_count`](/slides/python-net/aspose.slides.animation/isequence/get_count/#asposeslidesishape) | Returns count of effects for the specified shape. |


### See Also
* module [`aspose.slides.animation`](/slides/python-net/aspose.slides.animation)
* library [`Aspose.Slides`](/slides/python-net)

