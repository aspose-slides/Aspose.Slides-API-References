---
title: CaptionsCollection
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/captionscollection/
---

## CaptionsCollection class

 Represents a collection of the closed captions.
 
### add {#add}

| Name | Description |
| --- | --- |
| add (String, String) | Adds WebVTT closed captions at the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| label | String | Label of the closed captions. |
| filePath | String | Path to the file in WebVTT format. |

 **Returns:**
[Captions](../captions)

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | File path is empty. |


---


### add {#add}

| Name | Description |
| --- | --- |
| add (String, InputStream) | Adds WebVTT closed captions at the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| label | String | Label of the closed captions. |
| stream | InputStream | Input stream with data in WebVTT format. |

 **Returns:**
[Captions](../captions)

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Input data is not in the WebVTT format. |


---


### clear {#clear}

| Name | Description |
| --- | --- |
| clear () | Removes all elements from the collection. |

 **Returns:**
void


---


### getCount {#getCount}

| Name | Description |
| --- | --- |
| getCount () | Returns the number of elements in the collection. Read-only int. |

 **Returns:**
int


---


### get_Item {#get_Item}

| Name | Description |
| --- | --- |
| get_Item (int) | Returns the closed captions by index. Read-only ICaptions. |

 **Returns:**
[Captions](../captions)


---


### iterator {#iterator}

| Name | Description |
| --- | --- |
| iterator () | Returns an enumerator that iterates through the collection. |

 **Returns:**



---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([Captions](../captions)) | Removes the closed captions from the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| captions | [Captions](../captions) | Captions object that should be deleted. |

 **Returns:**
void


---


### removeAt {#removeAt}

| Name | Description |
| --- | --- |
| removeAt (int) | Removes the closed captions at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of the closed captions that should be deleted. |

 **Returns:**
void


---


