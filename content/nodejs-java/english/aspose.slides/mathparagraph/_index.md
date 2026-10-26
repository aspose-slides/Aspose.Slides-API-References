---
title: MathParagraph
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/mathparagraph/
---

## MathParagraph class

 Mathematical paragraph that is a container for mathematical blocks (IMathBlock)
 
### MathParagraph {#MathParagraph}

| Name | Description |
| --- | --- |
| MathParagraph() | Initializes a new instance of the MathParagraph class. |

 **Returns:**
MathParagraph


---


### MathParagraph {#MathParagraph}

| Name | Description |
| --- | --- |
| MathParagraph([MathBlock](../mathblock)) | Initializes a new instance of the MathParagraph class. |

 **Returns:**
MathParagraph


---


### add {#add}

| Name | Description |
| --- | --- |
| add ([MathBlock](../mathblock)) | Adds IMathBlock to the end of collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| mathBlock | [MathBlock](../mathblock) | A mathematical block that will be added to the end of the collection |


---


### clear {#clear}

| Name | Description |
| --- | --- |
| clear () | Removes all elements from the collection. |


---


### contains {#contains}

| Name | Description |
| --- | --- |
| contains ([MathBlock](../mathblock)) | Determines whether the collection contains a specific value. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| mathBlock | [MathBlock](../mathblock) | The object to locate in the collection. |

 **Returns:**
boolean


---


### getCount {#getCount}

| Name | Description |
| --- | --- |
| getCount () | Gets the number of elements actually contained in the collection. Read-only int. |

 **Returns:**
int


---


### getJustification {#getJustification}

| Name | Description |
| --- | --- |
| getJustification () | Paragraph Justification Default value: CenteredAsGroup |

 **Returns:**
int


---


### get_Item {#get_Item}

| Name | Description |
| --- | --- |
| get_Item (int) | Gets the item at the specified index. Read-only IMathBlock. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the item to get |

 **Returns:**
[MathBlock](../mathblock)


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([MathBlock](../mathblock)) | Determines the index of a specific IMathBlock in collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| mathBlock | [MathBlock](../mathblock) | The item to locate in the collection. |

 **Returns:**
int


---


### insert {#insert}

| Name | Description |
| --- | --- |
| insert (int, [MathBlock](../mathblock)) | Inserts IMathBlock into the collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which an item should be inserted. |
| mathBlock | [MathBlock](../mathblock) | The IMathBlock to insert. |


---


### iterator {#iterator}

| Name | Description |
| --- | --- |
| iterator () |  |

 **Returns:**



---


### iteratorJava {#iteratorJava}

| Name | Description |
| --- | --- |
| iteratorJava () |  |

 **Returns:**



---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([MathBlock](../mathblock)) | Removes the first occurrence of a specific object from the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| mathBlock | [MathBlock](../mathblock) | The object to remove from the collection. |

 **Returns:**
boolean


---


### removeAt {#removeAt}

| Name | Description |
| --- | --- |
| removeAt (int) | Removes an item at the specified index of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the item to remove. |


---


### setJustification {#setJustification}

| Name | Description |
| --- | --- |
| setJustification (int) | Paragraph Justification Default value: CenteredAsGroup |


---


### set_Item {#set_Item}

| Name | Description |
| --- | --- |
| set_Item (int, [MathBlock](../mathblock)) | Gets the item at the specified index. Read-only IMathBlock. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| value | int | The block of a mathematical text. |
| index | [MathBlock](../mathblock) | The zero-based index of the item to get |


---


### toLatex {#toLatex}

| Name | Description |
| --- | --- |
| toLatex () | Gets mathematical equation in LaTeX format |

 **Returns:**
String


---


### writeAsMathMlToStream  {#writeAsMathMlToStream }

| Name | Description |
| --- | --- |
| writeAsMathMlToStream  (MathParagraph, WriteStream) | Saves content of this MathParagraph as MathML |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| mathparagraph | MathParagraph  | link to self |
| stream | WriteStream | Target stream |


---


