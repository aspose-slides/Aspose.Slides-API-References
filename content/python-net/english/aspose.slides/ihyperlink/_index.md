---
title: IHyperlink
second_title: Aspose.Sildes for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/ihyperlink/
---

## IHyperlink class

Represents a hyperlink.

The IHyperlink type exposes the following members:
## Properties
| Name | Description |
| :- | :- |
|action_type|Returns type of HyperLinkEx's action.<br/>            Read-only [HyperlinkActionType](/slides/python-net/aspose.slides/hyperlinkactiontype/).|
|external_url|Specifies the external URL<br/>            If this property become not null then property TargetSlide become null.<br/>            Read-only string.|
|target_slide|If the HyperlinkEx targets specific slide returns this slide.<br/>            If the property become not null then property ExternalUrl become null.<br/>            Read-only [ISlide](/slides/python-net/aspose.slides/islide/).|
|target_frame|Returns the frame within the parent HTML frameset for the target<br/>            of the parent hyperlink when one exists.<br/>            Read/write string.|
|tooltip|Returns the string which may be surfaced in a user interface<br/>            as associated with the parent hyperlink.<br/>            Read/write string.|
|history|Determines whether the target of the parent hyperlink shall be added<br/>            to a list of viewed hyperlinks when it is invoked.<br/>            Read/write bool.|
|highlight_click|Determines whether the hyperlink should be highlighted on click.<br/>            Read/write bool.|
|stop_sound_on_click|Determines whether the sound should be stopped on hyperlink click.<br/>            Read/write bool.|
|sound|Represents the playing sound of the hyperlink.<br/>            Read/write [IAudio](/slides/python-net/aspose.slides/iaudio/).|
|color_source|Represents the source of hyperlink color - either styles or portion format.<br/>            Read/write [HyperlinkColorSource](/slides/python-net/aspose.slides/hyperlinkcolorsource/).|
## Methods
| Name | Description |
| :- | :- |
|equals(hlink)|Determines whether the two Hyperlink instances are equal.|

### See Also

* namespace [aspose.slides](/slides/python-net/aspose.slides/)
* assembly [Aspose.Slides](/slides/python-net/)

