---
title: Presentation
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/presentation/presentation/
---

## Presentation() function

 This constructor creates new presentation from scratch.
 Created presentation has one empty slide.
 

### Result
Presentation


---


## Presentation([LoadOptions](../../loadoptions) loadOptions) function

 This constructor creates new presentation from scratch.
 Created presentation has one empty slide.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| loadOptions | [LoadOptions](../../loadoptions) | Additional load options. |

### Result
Presentation


---


## createPresentationFromStream (ReadStream stream, Function callback) function

 This constructor is the primary mechanism for reading an existing Presentation.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| stream | ReadStream | Input stream. |
| callback | Function | callback(error, item) - Callback to be called when the class is created, item is the new instance of the Presentation |

### Result
Presentation


---


## createPresentationFromStream (ReadStream stream, [LoadOptions](../../loadoptions) loadOptions, Function callback) function

 This constructor is the primary mechanism for reading an existing Presentation.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| stream | ReadStream | Input stream. |
| loadOptions | [LoadOptions](../../loadoptions) | Additional load options. |
| callback | Function | callback(error, item) - Callback to be called when the class is created, item is the new instance of the Presentation |

### Result
Presentation


---


## Presentation(String file) function

 This constructor gets a source file path from which
 the contents of the Presentation are read.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| file | String | Input file. |

### Result
Presentation

### Error

| Error | Condition |
| --- | --- |
 | com.aspose.ms.System.ArgumentException | Thrown when input file has zero length |


---


## Presentation(String file, [LoadOptions](../../loadoptions) loadOptions) function

 This constructor gets a source file path from which
 the contents of the Presentation are read.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| file | String | Input file. |
| loadOptions | [LoadOptions](../../loadoptions) | Additional load options. |

### Result
Presentation

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when input file has zero length |


---


