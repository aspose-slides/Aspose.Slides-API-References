---
title: Hyperlink
type: docs
weight: 0
url: /php-java/hyperlink/
---

# Hyperlink class

 Represents a hyperlink.
 

## Constructors

| name | description |
| --- | --- |
| [Hyperlink](/php-java/hyperlink/hyperlink/)(String) | Creates an instance of a hyperlink. |
| [Hyperlink](/php-java/hyperlink/hyperlink/)(ISlide) | Creates an instance of a hyperlink which points to specific slide. Note: created hyperlink should be assigned to some object from the same presentation, otherwise link will be saved as NoAction. |
| [Hyperlink](/php-java/hyperlink/hyperlink/)(Hyperlink, String, String, boolean, boolean, boolean) | Creates an instance of a hyperlink using another hyperlink as source, overriding secondary properties. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [equals](/php-java/hyperlink/equals/)(Object) | boolean | Determines whether the two Hyperlink instances are equal. |
| [equals](/php-java/hyperlink/equals/)(IHyperlink) | boolean | Determines whether the two Hyperlink instances are equal. |
| [getActionType](/php-java/hyperlink/getactiontype/)() | int | Returns type of Hyperlink's action. Read-only HyperlinkActionType. |
| [getColorSource](/php-java/hyperlink/getcolorsource/)() | int | Represents the source of hyperlink color - either styles or portion format. Read/write HyperlinkColorSource. |
| [getEndShow](/php-java/hyperlink/getendshow/)() | Hyperlink | Returns a hyperlink which ends the show. Read-only Hyperlink. |
| [getExternalUrl](/php-java/hyperlink/getexternalurl/)() | String | Specifies the external URL. Read-only String. |
| [getFirstSlide](/php-java/hyperlink/getfirstslide/)() | Hyperlink | Returns a hyperlink to the first slide of the presentation. Read-only Hyperlink. |
| [getHighlightClick](/php-java/hyperlink/gethighlightclick/)() | boolean | Determines whether the hyperlink should be highlighted on click. Read/write boolean. |
| [getHistory](/php-java/hyperlink/gethistory/)() | boolean | Determines whether the target of the parent hyperlink shall be added to a list of viewed hyperlinks when it is invoked. Read/write boolean. |
| [getLastSlide](/php-java/hyperlink/getlastslide/)() | Hyperlink | Returns a hyperlink to the last slide of the presentation. Read-only Hyperlink. |
| [getLastVievedSlide](/php-java/hyperlink/getlastvievedslide/)() | Hyperlink | Returns a hyperlink to the last viewed slide. Read-only Hyperlink. |
| [getMedia](/php-java/hyperlink/getmedia/)() | Hyperlink | Returns a special "play mediafile" hyperlink. Used in AudioFrame and VideoFrame. Read-only Hyperlink. |
| [getNextSlide](/php-java/hyperlink/getnextslide/)() | Hyperlink | Returns a hyperlink to the next slide. Read-only Hyperlink. |
| [getNoAction](/php-java/hyperlink/getnoaction/)() | Hyperlink | Returns a special "do nothing" hyperlink. Read-only Hyperlink. |
| [getPreviousSlide](/php-java/hyperlink/getpreviousslide/)() | Hyperlink | Returns a hyperlink to the previous slide. Read-only Hyperlink. |
| [getStopSoundOnClick](/php-java/hyperlink/getstopsoundonclick/)() | boolean | Determines whether the sound should be stopped on hyperlink click. Read/write boolean. |
| [getTargetFrame](/php-java/hyperlink/gettargetframe/)() | String | Returns the frame within the parent HTML frameset for the target of the parent hyperlink when one exists. Read/wite String. |
| [getTargetSlide](/php-java/hyperlink/gettargetslide/)() | ISlide | If the Hyperlink targets specific slide returns this slide. Read-only ISlide. |
| [getTooltip](/php-java/hyperlink/gettooltip/)() | String | Returns the string which may be surfaced in a user interface as associated with the parent hyperlink. Read/write String. |
| [hashCode](/php-java/hyperlink/hashcode/)() | int | Serves as a hash function for a particular type, suitable for use in hashing algorithms and data structures like a hash table. |
| [op_Equality](/php-java/hyperlink/op_equality/)(Hyperlink, Hyperlink) | boolean | Tests two hyperlinks for equality. |
| [op_Inequality](/php-java/hyperlink/op_inequality/)(Hyperlink, Hyperlink) | boolean | Tests two hyperlinks for inequality. |
| [setColorSource](/php-java/hyperlink/setcolorsource/)(int) | void | Represents the source of hyperlink color - either styles or portion format. Read/write HyperlinkColorSource. |
| [setHighlightClick](/php-java/hyperlink/sethighlightclick/)(boolean) | void | Determines whether the hyperlink should be highlighted on click. Read/write boolean. |
| [setHistory](/php-java/hyperlink/sethistory/)(boolean) | void | Determines whether the target of the parent hyperlink shall be added to a list of viewed hyperlinks when it is invoked. Read/write boolean. |
| [setStopSoundOnClick](/php-java/hyperlink/setstopsoundonclick/)(boolean) | void | Determines whether the sound should be stopped on hyperlink click. Read/write boolean. |
| [setTargetFrame](/php-java/hyperlink/settargetframe/)(String) | void | Returns the frame within the parent HTML frameset for the target of the parent hyperlink when one exists. Read/wite String. |
| [setTooltip](/php-java/hyperlink/settooltip/)(String) | void | Returns the string which may be surfaced in a user interface as associated with the parent hyperlink. Read/write String. |
