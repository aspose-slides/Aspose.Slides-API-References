---
title: Presentation
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/presentation/presentation/
---

## Presentation()  constructor

 This constructor creates new presentation from scratch.
 Created presentation has one empty slide.
 


---


## Presentation([LoadOptions](../../loadoptions) loadOptions)  constructor

 This constructor creates new presentation from scratch.
 Created presentation has one empty slide.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| loadOptions | [LoadOptions](../../loadoptions) | Additional load options. |


---


## Presentation(InputStream stream)  constructor

 This constructor is the primary mechanism for reading an existing Presentation.
 

 
```php
  $fis = new FileInputStream("demo.pptx");
  $pres = new Presentation($fis);
  $fis->close();
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| stream | InputStream | Input stream. |


---


## Presentation(InputStream stream, [LoadOptions](../../loadoptions) loadOptions)  constructor

 This constructor is the primary mechanism for reading an existing Presentation.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| stream | InputStream | Input stream. |
| loadOptions | [LoadOptions](../../loadoptions) | Additional load options. |


---


## Presentation(String file)  constructor

 This constructor gets a source file path from which
 the contents of the Presentation are read.
 

 
```php
  $pres = new Presentation("demo.pptx");
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| file | String | Input file. |

### Exception

| Exception | Condition |
| --- | --- |
 | com.aspose.ms.System.ArgumentException | Thrown when input file has zero length |


---


## Presentation(String file, [LoadOptions](../../loadoptions) loadOptions)  constructor

 This constructor gets a source file path from which
 the contents of the Presentation are read.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| file | String | Input file. |
| loadOptions | [LoadOptions](../../loadoptions) | Additional load options. |

### Exception

| Exception | Condition |
| --- | --- |
 | ArgumentException | Thrown when input file has zero length |


---


