---
title: CaptionsCollection
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/captionscollection/
---

## CaptionsCollection class

 Represents a collection of the closed captions.
 
### add {#add}

| Name | Description |
| --- | --- |
| add (String, String) | Adds WebVTT closed captions to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| label | String | The label of the closed captions. |
| filePath | String | The path to the WebVTT file. |

 **Returns:**
[Captions](../captions)

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown if filePath is empty. |


---


### addFromStream  {#addFromStream }

| Name | Description |
| --- | --- |
| addFromStream  (CaptionsCollection, String, ReadStream, Function) | Adds WebVTT closed captions to the end of the collection from a stream. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| captionscollection | CaptionsCollection  | link to self |
| label | String | The label of the closed captions. |
| stream | ReadStream | The input stream containing data in WebVTT format. |
| callback | Function | callback(error, Returns) - Callback to be called when the method has completed |

 **Returns:**
[Captions](../captions)

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown if the input data is not in WebVTT format. |


---


### clear {#clear}

| Name | Description |
| --- | --- |
| clear () | Removes all closed captions from the collection. |


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
| get_Item (int) | Returns the closed captions at the specified index. Read-only ICaptions. |

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
| remove ([Captions](../captions)) | Removes the specified closed captions from the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| captions | [Captions](../captions) | The closed captions to remove. |


---


### removeAt {#removeAt}

| Name | Description |
| --- | --- |
| removeAt (int) | Removes the closed captions at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The index of the closed captions to remove. |


---


