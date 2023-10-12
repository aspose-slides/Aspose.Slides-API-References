---
title: Hyperlink
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/hyperlink/
---

## Hyperlink class

 Represents a hyperlink.
 
| [Hyperlink]([String]) | Creates an instance of a hyperlink. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| url | [String] | Hyperlink URL. |

### Result
Hyperlink


---


| [Hyperlink]([Slide]) | Creates an instance of a hyperlink which points to specific slide. Note: created hyperlink should be assigned to some object from the same presentation, otherwise link will be saved as NoAction. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| slide | [Slide] | Target slide. |

### Result
Hyperlink


---


| [Hyperlink]([Hyperlink], [String], [String], [boolean], [boolean], [boolean]) | Creates an instance of a hyperlink using another hyperlink as source, overriding secondary properties. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| source | [Hyperlink] | Source hyperlink |
| targetFrame | [String] | Target frame |
| tooltip | [String] | Tooltip text |
| history | [boolean] | Determines whether the target of the parent hyperlink shall be added to a list of viewed hyperlinks when it is invoked. |
| stopSoundsOnClick | [boolean] | Determines whether the sound should be stopped on hyperlink click. |
| highlightClick | [boolean] | Determines whether the hyperlink should be highlighted on click. |

### Result
Hyperlink


---


| [equals] ([Object]) | Determines whether the two Hyperlink instances are equal. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| obj | [Object] | The Hyperlink to compare with the current Hyperlink. |

### Result
boolean


---


| [equals] ([Hyperlink]) | Determines whether the two Hyperlink instances are equal. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| hlink | [Hyperlink] | The Hyperlink to compare with the current Hyperlink. |

### Result
boolean


---


| [getActionType] () | Returns type of Hyperlink's action. Read-only HyperlinkActionType. |

### Result
int


---


| [getColorSource] () | Represents the source of hyperlink color - either styles or portion format. Read/write HyperlinkColorSource. |

### Result
int


---


| [getEndShow] () | Returns a hyperlink which ends the show. Read-only Hyperlink. |

### Result
Hyperlink


---


| [getExternalUrl] () | Specifies the external URL. Read-only String. |

### Result
String


---


| [getFirstSlide] () | Returns a hyperlink to the first slide of the presentation. Read-only Hyperlink. |

### Result
Hyperlink


---


| [getHighlightClick] () | Determines whether the hyperlink should be highlighted on click. Read/write boolean. |

### Result
boolean


---


| [getHistory] () | Determines whether the target of the parent hyperlink shall be added to a list of viewed hyperlinks when it is invoked. Read/write boolean. |

### Result
boolean


---


| [getLastSlide] () | Returns a hyperlink to the last slide of the presentation. Read-only Hyperlink. |

### Result
Hyperlink


---


| [getLastVievedSlide] () | Returns a hyperlink to the last viewed slide. Read-only Hyperlink. |

### Result
Hyperlink


---


| [getMedia] () | Returns a special "play mediafile" hyperlink. Used in AudioFrame and VideoFrame. Read-only Hyperlink. |

### Result
Hyperlink


---


| [getNextSlide] () | Returns a hyperlink to the next slide. Read-only Hyperlink. |

### Result
Hyperlink


---


| [getNoAction] () | Returns a special "do nothing" hyperlink. Read-only Hyperlink. |

### Result
Hyperlink


---


| [getPreviousSlide] () | Returns a hyperlink to the previous slide. Read-only Hyperlink. |

### Result
Hyperlink


---


| [getSound] () | Represents the playing sound of the hyperlink. Read/write IAudio. |

### Result
[Audio]


---


| [getStopSoundOnClick] () | Determines whether the sound should be stopped on hyperlink click. Read/write boolean. |

### Result
boolean


---


| [getTargetFrame] () | Returns the frame within the parent HTML frameset for the target of the parent hyperlink when one exists. Read/wite String. |

### Result
String


---


| [getTargetSlide] () | If the Hyperlink targets specific slide returns this slide. Read-only ISlide. |

### Result
[Slide]


---


| [getTooltip] () | Returns the string which may be surfaced in a user interface as associated with the parent hyperlink. Read/write String. |

### Result
String


---


| [getVersion] () |  |

### Result
long


---


| [hashCode] () | Serves as a hash function for a particular type, suitable for use in hashing algorithms and data structures like a hash table. |

### Result
int


---


| [op_Equality] ([Hyperlink], [Hyperlink]) | Tests two hyperlinks for equality. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| hlink1 | [Hyperlink] | First hyperlink to be tested. |
| hlink2 | [Hyperlink] | Second hyperlink to be tested. |

### Result
boolean


---


| [op_Inequality] ([Hyperlink], [Hyperlink]) | Tests two hyperlinks for inequality. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| hlink1 | [Hyperlink] | First hyperlink to be tested. |
| hlink2 | [Hyperlink] | Second hyperlink to be tested. |

### Result
boolean


---


| [setColorSource] ([int]) | Represents the source of hyperlink color - either styles or portion format. Read/write HyperlinkColorSource. |


---


| [setHighlightClick] ([boolean]) | Determines whether the hyperlink should be highlighted on click. Read/write boolean. |


---


| [setHistory] ([boolean]) | Determines whether the target of the parent hyperlink shall be added to a list of viewed hyperlinks when it is invoked. Read/write boolean. |


---


| [setSound] ([Audio]) | Represents the playing sound of the hyperlink. Read/write IAudio. |


---


| [setStopSoundOnClick] ([boolean]) | Determines whether the sound should be stopped on hyperlink click. Read/write boolean. |


---


| [setTargetFrame] ([String]) | Returns the frame within the parent HTML frameset for the target of the parent hyperlink when one exists. Read/wite String. |


---


| [setTooltip] ([String]) | Returns the string which may be surfaced in a user interface as associated with the parent hyperlink. Read/write String. |


---


