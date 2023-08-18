---
title: Hyperlink
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/hyperlink/hyperlink/
---

## Hyperlink(String url) function

 Creates an instance of a hyperlink.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| url | String | Hyperlink URL. |

### Result
Hyperlink


---


## Hyperlink([Slide](../../slide) slide) function

 Creates an instance of a hyperlink which points to specific slide.
 Note: created hyperlink should be assigned to some object from the same presentation, otherwise link will be saved as NoAction.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| slide | [Slide](../../slide) | Target slide. |

### Result
Hyperlink


---


## Hyperlink([Hyperlink](../../hyperlink) source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick) function

 Creates an instance of a hyperlink using another hyperlink as source, overriding secondary properties.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| source | [Hyperlink](../hyperlink) | Source hyperlink |
| targetFrame | String | Target frame |
| tooltip | String | Tooltip text |
| history | boolean | Determines whether the target of the parent hyperlink shall be added to a list of viewed hyperlinks when it is invoked. |
| stopSoundsOnClick | boolean | Determines whether the sound should be stopped on hyperlink click. |
| highlightClick | boolean | Determines whether the hyperlink should be highlighted on click. |

### Result
Hyperlink


---


