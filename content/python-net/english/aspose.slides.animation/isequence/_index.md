﻿---
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
| [`add_effect`](/slides/python-net/aspose.slides.animation/isequence/add_effect/#ishape-effecttype-effectsubtype-effecttriggertype) | Add new effect to the end of sequence. |
| [`add_effect`](/slides/python-net/aspose.slides.animation/isequence/add_effect/#iparagraph-effecttype-effectsubtype-effecttriggertype) | Add new animation effect for paragraph to the end of sequence. |
| [`add_effect`](/slides/python-net/aspose.slides.animation/isequence/add_effect/#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype) | Adds the new chart animation effect for category or series to the end of sequence. |
| [`add_effect`](/slides/python-net/aspose.slides.animation/isequence/add_effect/#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype) | Adds the new chart animation effect for elements in category or series to the end of sequence. |
| [`remove`](/slides/python-net/aspose.slides.animation/isequence/remove/#ieffect) | Removes specified effect from a collection. |
| [`remove_at`](/slides/python-net/aspose.slides.animation/isequence/remove_at/#int) | Removes an effect from a collection. |
| [`clear`](/slides/python-net/aspose.slides.animation/isequence/clear/#) | Removes all effects from a collection. |
| [`remove_by_shape`](/slides/python-net/aspose.slides.animation/isequence/remove_by_shape/#ishape) | Remove effect for the specified shape. |
| [`get_effects_by_shape`](/slides/python-net/aspose.slides.animation/isequence/get_effects_by_shape/#ishape) | Returns array of effects for the specified shape. |
| [`get_effects_by_paragraph`](/slides/python-net/aspose.slides.animation/isequence/get_effects_by_paragraph/#iparagraph) | Returns array of effects for the specified paragraph. |
| [`get_count`](/slides/python-net/aspose.slides.animation/isequence/get_count/#ishape) | Returns count of effects for the specified shape. |


### See Also
* module [`aspose.slides.animation`](/slides/python-net/aspose.slides.animation)
* library [`Aspose.Slides`](/slides/python-net)

