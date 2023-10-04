---
title: CustomXmlPartCollection
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/customxmlpartcollection/
---

## CustomXmlPartCollection class

 Represents collection of custom xml parts.
 

## Functions

| Name | Description |
| --- | --- |
| [add](String) | Adds new custom xml part. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| xmlString | String | The xml string of new part to be added. |

### Result
[CustomXmlPart](../../customxmlpart)

### Error

| Error | Condition |
| --- | --- |
 | com.aspose.ms.System.ArgumentException | xmlString is empty or xml-data is invalid. |


---


| [add](byte[]) | Adds new custom xml part. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| xmlData | byte[] | The xml data of new part to be added. |

### Result
[CustomXmlPart](../../customxmlpart)

### Error

| Error | Condition |
| --- | --- |
 | com.aspose.ms.System.ArgumentException | xmlData is empty or invalid. |


---


| [addFromStream ](CustomXmlPartCollection, ReadStream, Function) | Adds new custom xml part. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| customxmlpartcollection | CustomXmlPartCollection  | link to self |
| inputStream | ReadStream | The inputStream with xml data of new part to be added. |
| callback | Function | callback(error, result) - Callback to be called when the method has completed |

### Result
[CustomXmlPart](../../customxmlpart)

### Error

| Error | Condition |
| --- | --- |
 | com.aspose.ms.System.ArgumentException | Data in inputStream is empty or invalid. |


---


| [clear]() | Removes all items from the collection. |


---


| [getSyncRoot]() | Returns a synchronization root. Read-only Object. |

### Result
Object


---


| [get_Item](int) | Returns the element at the specified index. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the element to get. |

### Result
[CustomXmlPart](../../customxmlpart)

### Error

| Error | Condition |
| --- | --- |
 | com.aspose.ms.System.ArgumentOutOfRangeException | index is less than 0.-or-index is equal to or greater than Count |


---


| [isSynchronized]() | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |

### Result
boolean


---


| [iterator]() | Returns an enumerator that iterates through the collection. |

### Result



---


| [iteratorJava]() | Returns a java iterator for the entire collection. |

### Result



---


| [remove]([CustomXmlPart](../customxmlpart)) | Removes the first occurrence of a specific object from the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [CustomXmlPart](../../customxmlpart) | The custom xml part to remove. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | com.aspose.ms.System.ArgumentNullException | item is null. |


---


| [removeAt](int) | Removes custom xml part at the specified index. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the element to remove. |

### Error

| Error | Condition |
| --- | --- |
 | com.aspose.ms.System.ArgumentOutOfRangeException | index is less than 0.-or-index is equal to or greater than Count |


---


| [size]() | Returns count of custom xml parts in the collection. Read-only int. |

### Result
int


---


