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
| [action_type](/slides/python-net/aspose.slides/ihyperlink/action_type/) | Returns type of HyperLinkEx's action.<br/>            Read-only [`HyperlinkActionType`](/slides/python-net/aspose.slides/hyperlinkactiontype). |
| [external_url](/slides/python-net/aspose.slides/ihyperlink/external_url/) | Specifies the external URL<br/>            If this property become not null then property TargetSlide become null.<br/>            Read-only .NET type System.String. |
| [external_url_original](/slides/python-net/aspose.slides/ihyperlink/external_url_original/) | Represents a hyperlink that is set for this portion without regard to the actual content of the portion.<br/>            <br/>            PowerPoint behaves specifically for links and their corresponding text in a portion. It allows to create text for the hyperlink in<br/>            the form of a valid URL, different from the real address of the link. In this case, when you view the link in the edit window, it will be<br/>            changed to match the text portion. This property represents the original value of the hyperlink. |
| [target_slide](/slides/python-net/aspose.slides/ihyperlink/target_slide/) | If the HyperlinkEx targets specific slide returns this slide.<br/>            If the property become not null then property ExternalUrl become null.<br/>            Read-only [`ISlide`](/slides/python-net/aspose.slides/islide). |
| [target_frame](/slides/python-net/aspose.slides/ihyperlink/target_frame/) | Returns the frame within the parent HTML frameset for the target<br/>            of the parent hyperlink when one exists.<br/>            Read/write .NET type System.String. |
| [tooltip](/slides/python-net/aspose.slides/ihyperlink/tooltip/) | Returns the string which may be surfaced in a user interface<br/>            as associated with the parent hyperlink.<br/>            Read/write .NET type System.String. |
| [history](/slides/python-net/aspose.slides/ihyperlink/history/) | Determines whether the target of the parent hyperlink shall be added<br/>            to a list of viewed hyperlinks when it is invoked.<br/>            Read/write .NET type System.Boolean. |
| [highlight_click](/slides/python-net/aspose.slides/ihyperlink/highlight_click/) | Determines whether the hyperlink should be highlighted on click.<br/>            Read/write .NET type System.Boolean. |
| [stop_sound_on_click](/slides/python-net/aspose.slides/ihyperlink/stop_sound_on_click/) | Determines whether the sound should be stopped on hyperlink click.<br/>            Read/write .NET type System.Boolean. |
| [sound](/slides/python-net/aspose.slides/ihyperlink/sound/) | Represents the playing sound of the hyperlink.<br/>            Read/write [`IAudio`](/slides/python-net/aspose.slides/iaudio). |
| [color_source](/slides/python-net/aspose.slides/ihyperlink/color_source/) | Represents the source of hyperlink color - either styles or portion format.<br/>            Read/write [`HyperlinkColorSource`](/slides/python-net/aspose.slides/hyperlinkcolorsource). |

## Methods

| Method | Description |
| :- | :- |
| [equals](/slides/python-net/aspose.slides/ihyperlink/ihyperlink/#IHyperlink/) | Determines whether the two Hyperlink instances are equal. |

