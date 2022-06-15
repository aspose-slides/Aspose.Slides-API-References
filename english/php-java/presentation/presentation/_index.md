---
title: Presentation
type: docs
weight: 10
url: /php-java/presentation/presentation/
---

# Presentation() constructor

 This constructor creates new presentation from scratch.
 Created presentation has one empty slide.
 


# Presentation(com.aspose.slides.LoadOptions) constructor

 This constructor creates new presentation from scratch.
 Created presentation has one empty slide.
 

##  Parameters

| name | description |
| --- | --- |
| loadOptions | Additional load options. |


# Presentation(java.io.InputStream) constructor

 This constructor is the primary mechanism for reading an existing Presentation.
 

 
```php
  $fis = new FileInputStream("demo.pptx");
  $pres = new Presentation($fis);
  $fis->close();
```

##  Parameters

| name | description |
| --- | --- |
| stream | Input stream. |


# Presentation(java.io.InputStream, com.aspose.slides.LoadOptions) constructor

 This constructor is the primary mechanism for reading an existing Presentation.
 

##  Parameters

| name | description |
| --- | --- |
| stream | Input stream. |
| loadOptions | Additional load options. |


# Presentation(java.lang.String) constructor

 This constructor gets a source file path from which
 the contents of the Presentation are read.
 

 
```php
  $pres = new Presentation("demo.pptx");
```

##  Parameters

| name | description |
| --- | --- |
| file | Input file. |


# Presentation(java.lang.String, com.aspose.slides.LoadOptions) constructor

 This constructor gets a source file path from which
 the contents of the Presentation are read.
 

##  Parameters

| name | description |
| --- | --- |
| file | Input file. |
| loadOptions | Additional load options. |


