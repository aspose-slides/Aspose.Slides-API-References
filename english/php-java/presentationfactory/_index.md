---
title: PresentationFactory
type: docs
weight: 0
url: /php-java/presentationfactory/
---

# PresentationFactory class

 Allows to create presentation via COM interface
 

## Constructors

| name | description |
| --- | --- |
| [PresentationFactory](/slides/php-java/presentationfactory/presentationfactory/)() |  |

## Methods

| name | return type | description |
| --- | --- | --- |
| [createPresentation](/slides/php-java/presentationfactory/createpresentation/)() | IPresentation | Creates new presentation. |
| [createPresentation](/slides/php-java/presentationfactory/createpresentation/)(ILoadOptions) | IPresentation | Creates new presentation with additional load options |
| [getInstance](/slides/php-java/presentationfactory/getinstance/)() | PresentationFactory | Presentation factory static instance. Read-only PresentationFactory. |
| [getPresentationInfo](/slides/php-java/presentationfactory/getpresentationinfo/)(String) | IPresentationInfo | Creates new PresentationInfo object from file and binds presentation to it. |
| [getPresentationInfo](/slides/php-java/presentationfactory/getpresentationinfo/)(InputStream) | IPresentationInfo | Creates new PresentationInfo object from stream and binds presentation to it. Gets info about presentation in specified stream. |
| [getPresentationText](/slides/php-java/presentationfactory/getpresentationtext/)(String, int) | IPresentationText | Retrieves the raw text from the slides |
| [getPresentationText](/slides/php-java/presentationfactory/getpresentationtext/)(InputStream, int) | IPresentationText | Retrieves the raw text from the slides |
| [getPresentationText](/slides/php-java/presentationfactory/getpresentationtext/)(InputStream, int, ILoadOptions) | IPresentationText | Retrieves the raw text from the slides |
| [readPresentation](/slides/php-java/presentationfactory/readpresentation/)(byte[]) | IPresentation | Reads an existing presentation from array |
| [readPresentation](/slides/php-java/presentationfactory/readpresentation/)(byte[], ILoadOptions) | IPresentation | Reads an existing presentation from array with additional load options |
| [readPresentation](/slides/php-java/presentationfactory/readpresentation/)(InputStream) | IPresentation | Reads an existing presentation from stream |
| [readPresentation](/slides/php-java/presentationfactory/readpresentation/)(InputStream, ILoadOptions) | IPresentation | Reads an existing presentation from stream with additional load options |
| [readPresentation](/slides/php-java/presentationfactory/readpresentation/)(String) | IPresentation | Reads an existing presentation from file |
| [readPresentation](/slides/php-java/presentationfactory/readpresentation/)(String, ILoadOptions) | IPresentation | Reads an existing presentation from stream with additional load options |
