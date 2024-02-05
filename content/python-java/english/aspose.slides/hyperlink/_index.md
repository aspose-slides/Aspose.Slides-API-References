---
title: Hyperlink
second_title: Aspose.Sildes for Python via Java API Reference
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

 **Result:**
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

 **Result:**
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

 **Result:**
Hyperlink


---


### equals {#equals}

| Name | Description |
| --- | --- |
| equals(Object) | Determines whether the two Hyperlink instances are equal. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| obj | Object | The Hyperlink to compare with the current Hyperlink. |

 **Result:**
boolean


---


### equals {#equals}

| Name | Description |
| --- | --- |
| equals([Hyperlink](../hyperlink)) | Determines whether the two Hyperlink instances are equal. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| hlink | [Hyperlink](../hyperlink) | The Hyperlink to compare with the current Hyperlink. |

 **Result:**
boolean


---


### getActionType {#getActionType}

| Name | Description |
| --- | --- |
| getActionType() | Returns type of Hyperlink's action. Read-only HyperlinkActionType. |

 **Result:**
int


---


### getColorSource {#getColorSource}

| Name | Description |
| --- | --- |
| getColorSource() | Represents the source of hyperlink color - either styles or portion format. Read/write HyperlinkColorSource. |

 **Result:**
int


---


### getEndShow {#getEndShow}

| Name | Description |
| --- | --- |
| getEndShow() | Returns a hyperlink which ends the show. Read-only Hyperlink. |

 **Result:**
Hyperlink


---


### getExternalUrl {#getExternalUrl}

| Name | Description |
| --- | --- |
| getExternalUrl() | Specifies the external URL. Read-only String. |

 **Result:**
String


---


### getFirstSlide {#getFirstSlide}

| Name | Description |
| --- | --- |
| getFirstSlide() | Returns a hyperlink to the first slide of the presentation. Read-only Hyperlink. |

 **Result:**
Hyperlink


---


### getHighlightClick {#getHighlightClick}

| Name | Description |
| --- | --- |
| getHighlightClick() | Determines whether the hyperlink should be highlighted on click. Read/write boolean. |

 **Result:**
boolean


---


### getHistory {#getHistory}

| Name | Description |
| --- | --- |
| getHistory() | Determines whether the target of the parent hyperlink shall be added to a list of viewed hyperlinks when it is invoked. Read/write boolean. |

 **Result:**
boolean


---


### getLastSlide {#getLastSlide}

| Name | Description |
| --- | --- |
| getLastSlide() | Returns a hyperlink to the last slide of the presentation. Read-only Hyperlink. |

 **Result:**
Hyperlink


---


### getLastVievedSlide {#getLastVievedSlide}

| Name | Description |
| --- | --- |
| getLastVievedSlide() | Returns a hyperlink to the last viewed slide. Read-only Hyperlink. |

 **Result:**
Hyperlink


---


### getMedia {#getMedia}

| Name | Description |
| --- | --- |
| getMedia() | Returns a special "play mediafile" hyperlink. Used in AudioFrame and VideoFrame. Read-only Hyperlink. |

 **Result:**
Hyperlink


---


### getNextSlide {#getNextSlide}

| Name | Description |
| --- | --- |
| getNextSlide() | Returns a hyperlink to the next slide. Read-only Hyperlink. |

 **Result:**
Hyperlink


---


### getNoAction {#getNoAction}

| Name | Description |
| --- | --- |
| getNoAction() | Returns a special "do nothing" hyperlink. Read-only Hyperlink. |

 **Result:**
Hyperlink


---


### getParent_IPresentationComponent {#getParent_IPresentationComponent}

| Name | Description |
| --- | --- |
| getParent_IPresentationComponent() |  |


---


### getParent_ISlideComponent {#getParent_ISlideComponent}

| Name | Description |
| --- | --- |
| getParent_ISlideComponent() |  |


---


### getPresentation {#getPresentation}

| Name | Description |
| --- | --- |
| getPresentation() |  |

 **Result:**
Presentation


---


### getPreviousSlide {#getPreviousSlide}

| Name | Description |
| --- | --- |
| getPreviousSlide() | Returns a hyperlink to the previous slide. Read-only Hyperlink. |

 **Result:**
Hyperlink


---


### getSlide {#getSlide}

| Name | Description |
| --- | --- |
| getSlide() |  |

 **Result:**
BaseSlide


---


### getSound {#getSound}

| Name | Description |
| --- | --- |
| getSound() | Represents the playing sound of the hyperlink. Read/write IAudio. |

 **Result:**
[Audio](../audio)


---


### getStopSoundOnClick {#getStopSoundOnClick}

| Name | Description |
| --- | --- |
| getStopSoundOnClick() | Determines whether the sound should be stopped on hyperlink click. Read/write boolean. |

 **Result:**
boolean


---


### getTargetFrame {#getTargetFrame}

| Name | Description |
| --- | --- |
| getTargetFrame() | Returns the frame within the parent HTML frameset for the target of the parent hyperlink when one exists. Read/wite String. |

 **Result:**
String


---


### getTargetSlide {#getTargetSlide}

| Name | Description |
| --- | --- |
| getTargetSlide() | If the Hyperlink targets specific slide returns this slide. Read-only ISlide. |

 **Result:**
[Slide](../slide)


---


### getTooltip {#getTooltip}

| Name | Description |
| --- | --- |
| getTooltip() | Returns the string which may be surfaced in a user interface as associated with the parent hyperlink. Read/write String. |

 **Result:**
String


---


### getVersion {#getVersion}

| Name | Description |
| --- | --- |
| getVersion() |  |

 **Result:**
long


---


### getVersion {#getVersion}

| Name | Description |
| --- | --- |
| getVersion() |  |

 **Result:**
long


---


### hashCode {#hashCode}

| Name | Description |
| --- | --- |
| hashCode() | Serves as a hash function for a particular type, suitable for use in hashing algorithms and data structures like a hash table. |

 **Result:**
int


---


### op_Equality {#op_Equality}

| Name | Description |
| --- | --- |
| op_Equality([Hyperlink](../hyperlink), [Hyperlink](../hyperlink)) | Tests two hyperlinks for equality. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| hlink1 | [Hyperlink](../hyperlink) | First hyperlink to be tested. |
| hlink2 | [Hyperlink](../hyperlink) | Second hyperlink to be tested. |

 **Result:**
boolean


---


### op_Inequality {#op_Inequality}

| Name | Description |
| --- | --- |
| op_Inequality([Hyperlink](../hyperlink), [Hyperlink](../hyperlink)) | Tests two hyperlinks for inequality. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| hlink1 | [Hyperlink](../hyperlink) | First hyperlink to be tested. |
| hlink2 | [Hyperlink](../hyperlink) | Second hyperlink to be tested. |

 **Result:**
boolean


---


### setColorSource {#setColorSource}

| Name | Description |
| --- | --- |
| setColorSource(int) | Represents the source of hyperlink color - either styles or portion format. Read/write HyperlinkColorSource. |


---


### setHighlightClick {#setHighlightClick}

| Name | Description |
| --- | --- |
| setHighlightClick(boolean) | Determines whether the hyperlink should be highlighted on click. Read/write boolean. |


---


### setHistory {#setHistory}

| Name | Description |
| --- | --- |
| setHistory(boolean) | Determines whether the target of the parent hyperlink shall be added to a list of viewed hyperlinks when it is invoked. Read/write boolean. |


---


### setSound {#setSound}

| Name | Description |
| --- | --- |
| setSound([Audio](../audio)) | Represents the playing sound of the hyperlink. Read/write IAudio. |


---


### setStopSoundOnClick {#setStopSoundOnClick}

| Name | Description |
| --- | --- |
| setStopSoundOnClick(boolean) | Determines whether the sound should be stopped on hyperlink click. Read/write boolean. |


---


### setTargetFrame {#setTargetFrame}

| Name | Description |
| --- | --- |
| setTargetFrame(String) | Returns the frame within the parent HTML frameset for the target of the parent hyperlink when one exists. Read/wite String. |


---


### setTooltip {#setTooltip}

| Name | Description |
| --- | --- |
| setTooltip(String) | Returns the string which may be surfaced in a user interface as associated with the parent hyperlink. Read/write String. |


---


