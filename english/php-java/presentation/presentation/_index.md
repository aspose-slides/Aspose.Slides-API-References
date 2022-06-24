---
title: Presentation
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 10
url: /php-java/presentation/presentation/
---

## Presentation() constructor

This constructor creates new presentation from scratch. Created presentation has one empty slide.
 

---


## Presentation(com.aspose.slides.LoadOptions) constructor

This constructor creates new presentation from scratch. Created presentation has one empty slide.

### Parameters

| Parameter |Description |
| --- | --- |
| loadOptions | Additional load options. |
 

---


## Presentation(java.io.InputStream) constructor

This constructor is the primary mechanism for reading an existing Presentation.

 
```php
  $fis = new FileInputStream("demo.pptx");
  $pres = new Presentation($fis);
  $fis->close();
```

### Parameters

| Parameter |Description |
| --- | --- |
| stream | Input stream. |
 

---


## Presentation(java.io.InputStream, com.aspose.slides.LoadOptions) constructor

This constructor is the primary mechanism for reading an existing Presentation.

### Parameters

| Parameter |Description |
| --- | --- |
| stream | Input stream. |
| loadOptions | Additional load options. |
 

---


## Presentation(java.lang.String) constructor

This constructor gets a source file path from which the contents of the Presentation are read.

 
```php
  $pres = new Presentation("demo.pptx");
```

### Parameters

| Parameter |Description |
| --- | --- |
| file | Input file. |

### Exception

| Exception | Condition |
| --- | --- |
 | com.aspose.ms.System.ArgumentException | Thrown when input file has zero length |
 

---


## Presentation(java.lang.String, com.aspose.slides.LoadOptions) constructor

This constructor gets a source file path from which the contents of the Presentation are read.

### Parameters

| Parameter |Description |
| --- | --- |
| file | Input file. |
| loadOptions | Additional load options. |

### Exception

| Exception | Condition |
| --- | --- |
 | ArgumentException | Thrown when input file has zero length |
 

---


