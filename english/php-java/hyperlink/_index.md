---
title: Hyperlink
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/hyperlink/
---

## Hyperlink class

 Represents a hyperlink.
 

## Constructors

| Name | Description |
| --- | --- |
| [Hyperlink](hyperlink)(String) | Creates an instance of a hyperlink. |
| [Hyperlink](hyperlink)([Slide](../slide)) | Creates an instance of a hyperlink which points to specific slide. Note: created hyperlink should be assigned to some object from the same presentation, otherwise link will be saved as NoAction. |
| [Hyperlink](hyperlink)([Hyperlink](../hyperlink), String, String, boolean, boolean, boolean) | Creates an instance of a hyperlink using another hyperlink as source, overriding secondary properties. |

## Methods

| Name | Description |
| --- | --- |
| [equals](equals)(Object) | Determines whether the two Hyperlink instances are equal. |
| [equals](equals)([Hyperlink](../hyperlink)) | Determines whether the two Hyperlink instances are equal. |
| [getActionType](getactiontype)() | Returns type of Hyperlink's action. Read-only HyperlinkActionType. |
| [getColorSource](getcolorsource)() | Represents the source of hyperlink color - either styles or portion format. Read/write HyperlinkColorSource. |
| [getEndShow](getendshow)() | Returns a hyperlink which ends the show. Read-only Hyperlink. |
| [getExternalUrl](getexternalurl)() | Specifies the external URL. Read-only String. |
| [getFirstSlide](getfirstslide)() | Returns a hyperlink to the first slide of the presentation. Read-only Hyperlink. |
| [getHighlightClick](gethighlightclick)() | Determines whether the hyperlink should be highlighted on click. Read/write boolean. |
| [getHistory](gethistory)() | Determines whether the target of the parent hyperlink shall be added to a list of viewed hyperlinks when it is invoked. Read/write boolean. |
| [getLastSlide](getlastslide)() | Returns a hyperlink to the last slide of the presentation. Read-only Hyperlink. |
| [getLastVievedSlide](getlastvievedslide)() | Returns a hyperlink to the last viewed slide. Read-only Hyperlink. |
| [getMedia](getmedia)() | Returns a special "play mediafile" hyperlink. Used in AudioFrame and VideoFrame. Read-only Hyperlink. |
| [getNextSlide](getnextslide)() | Returns a hyperlink to the next slide. Read-only Hyperlink. |
| [getNoAction](getnoaction)() | Returns a special "do nothing" hyperlink. Read-only Hyperlink. |
| [getPreviousSlide](getpreviousslide)() | Returns a hyperlink to the previous slide. Read-only Hyperlink. |
| [getStopSoundOnClick](getstopsoundonclick)() | Determines whether the sound should be stopped on hyperlink click. Read/write boolean. |
| [getTargetFrame](gettargetframe)() | Returns the frame within the parent HTML frameset for the target of the parent hyperlink when one exists. Read/wite String. |
| [getTargetSlide](gettargetslide)() | If the Hyperlink targets specific slide returns this slide. Read-only ISlide. |
| [getTooltip](gettooltip)() | Returns the string which may be surfaced in a user interface as associated with the parent hyperlink. Read/write String. |
| [hashCode](hashcode)() | Serves as a hash function for a particular type, suitable for use in hashing algorithms and data structures like a hash table. |
| [op_Equality](op_equality)([Hyperlink](../hyperlink), [Hyperlink](../hyperlink)) | Tests two hyperlinks for equality. |
| [op_Inequality](op_inequality)([Hyperlink](../hyperlink), [Hyperlink](../hyperlink)) | Tests two hyperlinks for inequality. |
| [setColorSource](setcolorsource)(int) | Represents the source of hyperlink color - either styles or portion format. Read/write HyperlinkColorSource. |
| [setHighlightClick](sethighlightclick)(boolean) | Determines whether the hyperlink should be highlighted on click. Read/write boolean. |
| [setHistory](sethistory)(boolean) | Determines whether the target of the parent hyperlink shall be added to a list of viewed hyperlinks when it is invoked. Read/write boolean. |
| [setStopSoundOnClick](setstopsoundonclick)(boolean) | Determines whether the sound should be stopped on hyperlink click. Read/write boolean. |
| [setTargetFrame](settargetframe)(String) | Returns the frame within the parent HTML frameset for the target of the parent hyperlink when one exists. Read/wite String. |
| [setTooltip](settooltip)(String) | Returns the string which may be surfaced in a user interface as associated with the parent hyperlink. Read/write String. |
