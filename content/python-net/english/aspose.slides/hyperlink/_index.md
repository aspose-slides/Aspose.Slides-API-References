---
title: Hyperlink
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/hyperlink/
---


Hyperlink class

Represents a hyperlink.

**Inheritance:**[`Hyperlink`](/slides/python-net/aspose.slides/hyperlink) → [`PVIObject`](/slides/python-net/aspose.slides/pviobject)

The Hyperlink type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [__init__](/slides/python-net/aspose.slides/hyperlink/hyperlink/#string/) | Creates an instance of a hyperlink. |
| [__init__](/slides/python-net/aspose.slides/hyperlink/hyperlink/#ISlide/) | Creates an instance of a hyperlink which points to specific slide.<br/>            Note: created hyperlink should be assigned to some object from the same presentation, otherwise link will be saved as NoAction. |
| [__init__](/slides/python-net/aspose.slides/hyperlink/hyperlink/#Hyperlink-string-string-bool-bool-bool/) | Creates an instance of a hyperlink using another hyperlink as source, overriding secondary properties. |

## Properties

| Property | Description |
| :- | :- |
| [as_i_presentation_component](/slides/python-net/aspose.slides/hyperlink/as_i_presentation_component/) | Allows to get base IPresentationComponent interface.<br/>            Read-only :py:class:`aspose.slides.IPresentationComponent`. |
| [no_action](/slides/python-net/aspose.slides/hyperlink/no_action/) | Returns a special "do nothing" hyperlink.<br/>            Read-only :py:class:`aspose.slides.Hyperlink`. |
| [media](/slides/python-net/aspose.slides/hyperlink/media/) | Returns a special "play mediafile" hyperlink. Used in AudioFrame and VideoFrame.<br/>            Read-only :py:class:`aspose.slides.Hyperlink`. |
| [next_slide](/slides/python-net/aspose.slides/hyperlink/next_slide/) | Returns a hyperlink to the next slide.<br/>            Read-only :py:class:`aspose.slides.Hyperlink`. |
| [previous_slide](/slides/python-net/aspose.slides/hyperlink/previous_slide/) | Returns a hyperlink to the previous slide.<br/>            Read-only :py:class:`aspose.slides.Hyperlink`. |
| [first_slide](/slides/python-net/aspose.slides/hyperlink/first_slide/) | Returns a hyperlink to the first slide of the presentation.<br/>            Read-only :py:class:`aspose.slides.Hyperlink`. |
| [last_slide](/slides/python-net/aspose.slides/hyperlink/last_slide/) | Returns a hyperlink to the last slide of the presentation.<br/>            Read-only :py:class:`aspose.slides.Hyperlink`. |
| [last_vieved_slide](/slides/python-net/aspose.slides/hyperlink/last_vieved_slide/) | Returns a hyperlink to the last viewed slide.<br/>            Read-only :py:class:`aspose.slides.Hyperlink`. |
| [end_show](/slides/python-net/aspose.slides/hyperlink/end_show/) | Returns a hyperlink which ends the show.<br/>            Read-only :py:class:`aspose.slides.Hyperlink`. |
| [action_type](/slides/python-net/aspose.slides/hyperlink/action_type/) | Returns type of Hyperlink's action.<br/>            Read-only :py:enum:`aspose.slides.HyperlinkActionType`. |
| [external_url](/slides/python-net/aspose.slides/hyperlink/external_url/) | Specifies the external URL.<br/>            Read-only :py:class:`System.String`. |
| [target_slide](/slides/python-net/aspose.slides/hyperlink/target_slide/) | If the Hyperlink targets specific slide returns this slide.<br/>            Read-only :py:class:`aspose.slides.ISlide`. |
| [external_url_original](/slides/python-net/aspose.slides/hyperlink/external_url_original/) | Represents a hyperlink that is set for this portion without regard to the actual content of the portion. |
| [target_frame](/slides/python-net/aspose.slides/hyperlink/target_frame/) | Returns the frame within the parent HTML frameset for the target<br/>            of the parent hyperlink when one exists.<br/>            Read/wite :py:class:`System.String`. |
| [tooltip](/slides/python-net/aspose.slides/hyperlink/tooltip/) | Returns the string which may be surfaced in a user interface<br/>            as associated with the parent hyperlink.<br/>            Read/write :py:class:`System.String`. |
| [history](/slides/python-net/aspose.slides/hyperlink/history/) | Determines whether the target of the parent hyperlink shall be added<br/>            to a list of viewed hyperlinks when it is invoked.<br/>            Read/write :py:class:`bool`. |
| [highlight_click](/slides/python-net/aspose.slides/hyperlink/highlight_click/) | Determines whether the hyperlink should be highlighted on click.<br/>            Read/write :py:class:`bool`. |
| [stop_sound_on_click](/slides/python-net/aspose.slides/hyperlink/stop_sound_on_click/) | Determines whether the sound should be stopped on hyperlink click.<br/>            Read/write :py:class:`bool`. |
| [sound](/slides/python-net/aspose.slides/hyperlink/sound/) | Represents the playing sound of the hyperlink.<br/>            Read/write :py:class:`aspose.slides.IAudio`. |
| [color_source](/slides/python-net/aspose.slides/hyperlink/color_source/) | Represents the source of hyperlink color - either styles or portion format.<br/>            Read/write :py:enum:`aspose.slides.HyperlinkColorSource`. |
| [slide](/slides/python-net/aspose.slides/hyperlink/slide/) |  |
| [presentation](/slides/python-net/aspose.slides/hyperlink/presentation/) |  |

## Methods

| Method | Description |
| :- | :- |
| [equals](/slides/python-net/aspose.slides/hyperlink/hyperlink/#IHyperlink/) | Determines whether the two Hyperlink instances are equal. |

