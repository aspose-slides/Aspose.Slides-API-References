---
title: SensitivityLabelCollection
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/sensitivitylabelcollection/
---

## SensitivityLabelCollection class

 Represents a collection of sensitivity labels applied to the document.
 
### add {#add}

| Name | Description |
| --- | --- |
| add (String, UUID, boolean, int) | Adds the sensitivity label at the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| id | String | The id of sensitivity label. |
| siteId | UUID | The Azure Active Directory (Azure AD) site identifier. |
| isEnabled | boolean | Flag indicates whether the sensitivity label is enabled. |
| methodType | int | The assignment function for the sensitivity label. |

 **Returns:**
[SensitivityLabel](../sensitivitylabel)


---


### add {#add}

| Name | Description |
| --- | --- |
| add ([SensitivityLabel](../sensitivitylabel)) | Adds a SensitivityLabel to the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| label | [SensitivityLabel](../sensitivitylabel) | The SensitivityLabel object to be added at the end of the collection. |

 **Returns:**
int

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when the sensitivity label with the same Id has already been added. |


---


### clear {#clear}

| Name | Description |
| --- | --- |
| clear () | Removes all elements from the collection. |


---


### copyTo {#copyTo}

| Name | Description |
| --- | --- |
| copyTo (com.aspose.slides.ISensitivityLabel[], int) | Copies all elements from the collection to the specified array. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| array | com.aspose.slides.ISensitivityLabel[] | Target array. |
| index | int | Starting index in the target array. |


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
| get_Item (int) | Returns the sensitivity label by index. |

 **Returns:**
[SensitivityLabel](../sensitivitylabel)


---


### iterator {#iterator}

| Name | Description |
| --- | --- |
| iterator () | Returns an enumerator that iterates through the collection. |

 **Returns:**



---


### removeAt {#removeAt}

| Name | Description |
| --- | --- |
| removeAt (int) | Removes the sensitivity label at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of the sensitivity label that should be deleted. |


---


