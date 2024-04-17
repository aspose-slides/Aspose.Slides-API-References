---
title: Hyperlink
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/hyperlink/
---

## Hyperlink class

 Represents a hyperlink.
 
### Hyperlink {#Hyperlink}

| Name | Description |
| --- | --- |
| Hyperlink(String) | Creates an instance of a hyperlink. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| url | String | Hyperlink URL. |

 **Returns:**
Hyperlink


---


### Hyperlink {#Hyperlink}

| Name | Description |
| --- | --- |
| Hyperlink([Slide](../slide)) | Creates an instance of a hyperlink which points to specific slide. Note: created hyperlink should be assigned to some object from the same presentation, otherwise link will be saved as NoAction. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| slide | [Slide](../slide) | Target slide. |

 **Returns:**
Hyperlink


---


### Hyperlink {#Hyperlink}

| Name | Description |
| --- | --- |
| Hyperlink([Hyperlink](../hyperlink), String, String, boolean, boolean, boolean) | Creates an instance of a hyperlink using another hyperlink as source, overriding secondary properties. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| source | [Hyperlink](../hyperlink) | Source hyperlink |
| targetFrame | String | Target frame |
| tooltip | String | Tooltip text |
| history | boolean | Determines whether the target of the parent hyperlink shall be added to a list of viewed hyperlinks when it is invoked. |
| stopSoundsOnClick | boolean | Determines whether the sound should be stopped on hyperlink click. |
| highlightClick | boolean | Determines whether the hyperlink should be highlighted on click. |

 **Returns:**
Hyperlink


---


### equals {#equals}

| Name | Description |
| --- | --- |
| equals (Object) | Determines whether the two Hyperlink instances are equal. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| obj | Object | The Hyperlink to compare with the current Hyperlink. |

 **Returns:**
boolean


---


### equals {#equals}

| Name | Description |
| --- | --- |
| equals ([Hyperlink](../hyperlink)) | Determines whether the two Hyperlink instances are equal. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| hlink | [Hyperlink](../hyperlink) | The Hyperlink to compare with the current Hyperlink. |

 **Returns:**
boolean


---


### getActionType {#getActionType}

| Name | Description |
| --- | --- |
| getActionType () | Returns type of Hyperlink's action. Read-only HyperlinkActionType. |

 **Returns:**
int


---


### getColorSource {#getColorSource}

| Name | Description |
| --- | --- |
| getColorSource () | Represents the source of hyperlink color - either styles or portion format. Read/write HyperlinkColorSource. |

 **Returns:**
int


---


### getEndShow {#getEndShow}

| Name | Description |
| --- | --- |
| getEndShow () | Returns a hyperlink which ends the show. Read-only Hyperlink. |

 **Returns:**
Hyperlink


---


### getExternalUrl {#getExternalUrl}

| Name | Description |
| --- | --- |
| getExternalUrl () | Specifies the external URL. Read-only String. |

 **Returns:**
String


---


### getExternalUrlOriginal {#getExternalUrlOriginal}

| Name | Description |
| --- | --- |
| getExternalUrlOriginal () | Represents a hyperlink that is set for this portion without regard to the actual content of the portion. PowerPoint behaves specifically for links and their corresponding text in a portion. It allows to create text for the hyperlink in the form of a valid URL, different from the real address of the link. In this case, when you view the link in the edit window, it will be changed to match the text portion. This property represents the original value of the hyperlink. |

 **Returns:**
String


---


### getFirstSlide {#getFirstSlide}

| Name | Description |
| --- | --- |
| getFirstSlide () | Returns a hyperlink to the first slide of the presentation. Read-only Hyperlink. |

 **Returns:**
Hyperlink


---


### getHighlightClick {#getHighlightClick}

| Name | Description |
| --- | --- |
| getHighlightClick () | Determines whether the hyperlink should be highlighted on click. Read/write boolean. |

 **Returns:**
boolean


---


### getHistory {#getHistory}

| Name | Description |
| --- | --- |
| getHistory () | Determines whether the target of the parent hyperlink shall be added to a list of viewed hyperlinks when it is invoked. Read/write boolean. |

 **Returns:**
boolean


---


### getLastSlide {#getLastSlide}

| Name | Description |
| --- | --- |
| getLastSlide () | Returns a hyperlink to the last slide of the presentation. Read-only Hyperlink. |

 **Returns:**
Hyperlink


---


### getLastVievedSlide {#getLastVievedSlide}

| Name | Description |
| --- | --- |
| getLastVievedSlide () | Returns a hyperlink to the last viewed slide. Read-only Hyperlink. |

 **Returns:**
Hyperlink


---


### getMedia {#getMedia}

| Name | Description |
| --- | --- |
| getMedia () | Returns a special "play mediafile" hyperlink. Used in AudioFrame and VideoFrame. Read-only Hyperlink. |

 **Returns:**
Hyperlink


---


### getNextSlide {#getNextSlide}

| Name | Description |
| --- | --- |
| getNextSlide () | Returns a hyperlink to the next slide. Read-only Hyperlink. |

 **Returns:**
Hyperlink


---


### getNoAction {#getNoAction}

| Name | Description |
| --- | --- |
| getNoAction () | Returns a special "do nothing" hyperlink. Read-only Hyperlink. |

 **Returns:**
Hyperlink


---


### getPreviousSlide {#getPreviousSlide}

| Name | Description |
| --- | --- |
| getPreviousSlide () | Returns a hyperlink to the previous slide. Read-only Hyperlink. |

 **Returns:**
Hyperlink


---


### getSound {#getSound}

| Name | Description |
| --- | --- |
| getSound () | Represents the playing sound of the hyperlink. Read/write IAudio. |

 **Returns:**
[Audio](../audio)


---


### getStopSoundOnClick {#getStopSoundOnClick}

| Name | Description |
| --- | --- |
| getStopSoundOnClick () | Determines whether the sound should be stopped on hyperlink click. Read/write boolean. |

 **Returns:**
boolean


---


### getTargetFrame {#getTargetFrame}

| Name | Description |
| --- | --- |
| getTargetFrame () | Returns the frame within the parent HTML frameset for the target of the parent hyperlink when one exists. Read/wite String. |

 **Returns:**
String


---


### getTargetSlide {#getTargetSlide}

| Name | Description |
| --- | --- |
| getTargetSlide () | If the Hyperlink targets specific slide returns this slide. Read-only ISlide. |

 **Returns:**
[Slide](../slide)


---


### getTooltip {#getTooltip}

| Name | Description |
| --- | --- |
| getTooltip () | Returns the string which may be surfaced in a user interface as associated with the parent hyperlink. Read/write String. |

 **Returns:**
String


---


### getVersion {#getVersion}

| Name | Description |
| --- | --- |
| getVersion () |  |

 **Returns:**
long


---


### hashCode {#hashCode}

| Name | Description |
| --- | --- |
| hashCode () | Serves as a hash function for a particular type, suitable for use in hashing algorithms and data structures like a hash table. |

 **Returns:**
int


---


### op_Equality {#op_Equality}

| Name | Description |
| --- | --- |
| op_Equality ([Hyperlink](../hyperlink), [Hyperlink](../hyperlink)) | Tests two hyperlinks for equality. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| hlink1 | [Hyperlink](../hyperlink) | First hyperlink to be tested. |
| hlink2 | [Hyperlink](../hyperlink) | Second hyperlink to be tested. |

 **Returns:**
boolean


---


### op_Inequality {#op_Inequality}

| Name | Description |
| --- | --- |
| op_Inequality ([Hyperlink](../hyperlink), [Hyperlink](../hyperlink)) | Tests two hyperlinks for inequality. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| hlink1 | [Hyperlink](../hyperlink) | First hyperlink to be tested. |
| hlink2 | [Hyperlink](../hyperlink) | Second hyperlink to be tested. |

 **Returns:**
boolean


---


### setColorSource {#setColorSource}

| Name | Description |
| --- | --- |
| setColorSource (int) | Represents the source of hyperlink color - either styles or portion format. Read/write HyperlinkColorSource. |

 **Returns:**
void


---


### setHighlightClick {#setHighlightClick}

| Name | Description |
| --- | --- |
| setHighlightClick (boolean) | Determines whether the hyperlink should be highlighted on click. Read/write boolean. |

 **Returns:**
void


---


### setHistory {#setHistory}

| Name | Description |
| --- | --- |
| setHistory (boolean) | Determines whether the target of the parent hyperlink shall be added to a list of viewed hyperlinks when it is invoked. Read/write boolean. |

 **Returns:**
void


---


### setSound {#setSound}

| Name | Description |
| --- | --- |
| setSound ([Audio](../audio)) | Represents the playing sound of the hyperlink. Read/write IAudio. |

 **Returns:**
void


---


### setStopSoundOnClick {#setStopSoundOnClick}

| Name | Description |
| --- | --- |
| setStopSoundOnClick (boolean) | Determines whether the sound should be stopped on hyperlink click. Read/write boolean. |

 **Returns:**
void


---


### setTargetFrame {#setTargetFrame}

| Name | Description |
| --- | --- |
| setTargetFrame (String) | Returns the frame within the parent HTML frameset for the target of the parent hyperlink when one exists. Read/wite String. |

 **Returns:**
void


---


### setTooltip {#setTooltip}

| Name | Description |
| --- | --- |
| setTooltip (String) | Returns the string which may be surfaced in a user interface as associated with the parent hyperlink. Read/write String. |

 **Returns:**
void


---


