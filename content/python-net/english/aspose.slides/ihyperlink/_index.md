---
title: IHyperlink
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/ihyperlink/
---


IHyperlink class

Represents a hyperlink.

The IHyperlink type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [action_type](/slides/python-net/aspose.slides/ihyperlink/action_type/) | Returns type of HyperLinkEx's action.<br/>            Read-only :py:enum:`aspose.slides.HyperlinkActionType`. |
| [external_url](/slides/python-net/aspose.slides/ihyperlink/external_url/) | Specifies the external URL<br/>            If this property become not null then property TargetSlide become null.<br/>            Read-only :py:class:`System.String`. |
| [external_url_original](/slides/python-net/aspose.slides/ihyperlink/external_url_original/) | Represents a hyperlink that is set for this portion without regard to the actual content of the portion. |
| [target_slide](/slides/python-net/aspose.slides/ihyperlink/target_slide/) | If the HyperlinkEx targets specific slide returns this slide.<br/>            If the property become not null then property ExternalUrl become null.<br/>            Read-only :py:class:`aspose.slides.ISlide`. |
| [target_frame](/slides/python-net/aspose.slides/ihyperlink/target_frame/) | Returns the frame within the parent HTML frameset for the target<br/>            of the parent hyperlink when one exists.<br/>            Read/write :py:class:`System.String`. |
| [tooltip](/slides/python-net/aspose.slides/ihyperlink/tooltip/) | Returns the string which may be surfaced in a user interface<br/>            as associated with the parent hyperlink.<br/>            Read/write :py:class:`System.String`. |
| [history](/slides/python-net/aspose.slides/ihyperlink/history/) | Determines whether the target of the parent hyperlink shall be added<br/>            to a list of viewed hyperlinks when it is invoked.<br/>            Read/write :py:class:`bool`. |
| [highlight_click](/slides/python-net/aspose.slides/ihyperlink/highlight_click/) | Determines whether the hyperlink should be highlighted on click.<br/>            Read/write :py:class:`bool`. |
| [stop_sound_on_click](/slides/python-net/aspose.slides/ihyperlink/stop_sound_on_click/) | Determines whether the sound should be stopped on hyperlink click.<br/>            Read/write :py:class:`bool`. |
| [sound](/slides/python-net/aspose.slides/ihyperlink/sound/) | Represents the playing sound of the hyperlink.<br/>            Read/write :py:class:`aspose.slides.IAudio`. |
| [color_source](/slides/python-net/aspose.slides/ihyperlink/color_source/) | Represents the source of hyperlink color - either styles or portion format.<br/>            Read/write :py:enum:`aspose.slides.HyperlinkColorSource`. |

## Methods

| Method | Description |
| :- | :- |
| [equals](/slides/python-net/aspose.slides/ihyperlink/ihyperlink/#IHyperlink/) | Determines whether the two Hyperlink instances are equal. |

