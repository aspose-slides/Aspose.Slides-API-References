﻿---
title: IMasterSlide class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/imasterslide/
---


## IMasterSlide class

Represents a master slide in a presentation.

The IMasterSlide type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/aspose.slides/imasterslide/header_footer_manager/) | Returns HeaderFooter manager of the master slide.<br/>            Read-only [`IMasterSlideHeaderFooterManager`](/slides/python-net/aspose.slides/imasterslideheaderfootermanager). |
| [`title_style`](/slides/python-net/aspose.slides/imasterslide/title_style/) | Returns the style of a title text.<br/>            Read-only [`ITextStyle`](/slides/python-net/aspose.slides/itextstyle). |
| [`body_style`](/slides/python-net/aspose.slides/imasterslide/body_style/) | Returns the style of a body text.<br/>            Read-only [`ITextStyle`](/slides/python-net/aspose.slides/itextstyle). |
| [`other_style`](/slides/python-net/aspose.slides/imasterslide/other_style/) | Returns the style of an other text.<br/>            Read-only [`ITextStyle`](/slides/python-net/aspose.slides/itextstyle). |
| [`layout_slides`](/slides/python-net/aspose.slides/imasterslide/layout_slides/) | Returns the collection of child layout slides for this master slide.<br/>            Read-only [`IMasterLayoutSlideCollection`](/slides/python-net/aspose.slides/imasterlayoutslidecollection). |
| [`preserve`](/slides/python-net/aspose.slides/imasterslide/preserve/) | Determines whether the corresponding master is deleted when all <br/>            the slides that follow that master are deleted.<br/>            Note: Aspose.Slides will never remove any unused master by itself, <br/>            to actually remove unused masters call [`IMasterSlideCollection.remove_unused`](/slides/python-net/aspose.slides/imasterslidecollection/remove_unused)<br/>            Read/write **bool**. |
| [`has_depending_slides`](/slides/python-net/aspose.slides/imasterslide/has_depending_slides/) | Returns true if there exists at least one slide that depends on this master slide.<br/>            Read-only **bool**. |
| [`shapes`](/slides/python-net/aspose.slides/imasterslide/shapes/) |  |
| [`controls`](/slides/python-net/aspose.slides/imasterslide/controls/) |  |
| [`name`](/slides/python-net/aspose.slides/imasterslide/name/) |  |
| [`slide_id`](/slides/python-net/aspose.slides/imasterslide/slide_id/) |  |
| [`custom_data`](/slides/python-net/aspose.slides/imasterslide/custom_data/) |  |
| [`timeline`](/slides/python-net/aspose.slides/imasterslide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/aspose.slides/imasterslide/slide_show_transition/) |  |
| [`background`](/slides/python-net/aspose.slides/imasterslide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/aspose.slides/imasterslide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/aspose.slides/imasterslide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/aspose.slides/imasterslide/slide/) |  |
| [`presentation`](/slides/python-net/aspose.slides/imasterslide/presentation/) |  |
| [`theme_manager`](/slides/python-net/aspose.slides/imasterslide/theme_manager/) |  |

## Methods

| Method | Description |
| :- | :- |
| [`apply_external_theme_to_depending_slides`](/slides/python-net/aspose.slides/imasterslide/apply_external_theme_to_depending_slides/#str) | Creates a new master slide based on the current one, applying an external theme to it <br/>            and applies the created master slide to all dependent slides. |
| [`get_depending_slides`](/slides/python-net/aspose.slides/imasterslide/get_depending_slides/#) | Returns an array with all slides, which depend on this master slide. |
| [`find_shape_by_alt_text`](/slides/python-net/aspose.slides/imasterslide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting`](/slides/python-net/aspose.slides/imasterslide/join_portions_with_same_formatting/#) |  |
| [`equals`](/slides/python-net/aspose.slides/imasterslide/equals/#ibaseslide) |  |
| [`create_theme_effective`](/slides/python-net/aspose.slides/imasterslide/create_theme_effective/#) |  |


### See Also
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

