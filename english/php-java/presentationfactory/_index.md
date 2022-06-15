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
| [PresentationFactory](/php-java/presentationfactory/presentationfactory/)() |  |

## Methods

| name | return type | description |
| --- | --- | --- |
| [createPresentation](/php-java/presentationfactory/createpresentation/)() | IPresentation | Creates new presentation. |
| [createPresentation](/php-java/presentationfactory/createpresentation/)(ILoadOptions) | IPresentation | Creates new presentation with additional load options |
| [getInstance](/php-java/presentationfactory/getinstance/)() | PresentationFactory | Presentation factory static instance. Read-only PresentationFactory. |
| [getPresentationInfo](/php-java/presentationfactory/getpresentationinfo/)(String) | IPresentationInfo | Creates new PresentationInfo object from file and binds presentation to it. |
| [getPresentationInfo](/php-java/presentationfactory/getpresentationinfo/)(InputStream) | IPresentationInfo | Creates new PresentationInfo object from stream and binds presentation to it. Gets info about presentation in specified stream. |
| [getPresentationText](/php-java/presentationfactory/getpresentationtext/)(String, int) | IPresentationText | Retrieves the raw text from the slides |
| [getPresentationText](/php-java/presentationfactory/getpresentationtext/)(InputStream, int) | IPresentationText | Retrieves the raw text from the slides |
| [getPresentationText](/php-java/presentationfactory/getpresentationtext/)(InputStream, int, ILoadOptions) | IPresentationText | Retrieves the raw text from the slides |
| [readPresentation](/php-java/presentationfactory/readpresentation/)(byte[]) | IPresentation | Reads an existing presentation from array |
| [readPresentation](/php-java/presentationfactory/readpresentation/)(byte[], ILoadOptions) | IPresentation | Reads an existing presentation from array with additional load options |
| [readPresentation](/php-java/presentationfactory/readpresentation/)(InputStream) | IPresentation | Reads an existing presentation from stream |
| [readPresentation](/php-java/presentationfactory/readpresentation/)(InputStream, ILoadOptions) | IPresentation | Reads an existing presentation from stream with additional load options |
| [readPresentation](/php-java/presentationfactory/readpresentation/)(String) | IPresentation | Reads an existing presentation from file |
| [readPresentation](/php-java/presentationfactory/readpresentation/)(String, ILoadOptions) | IPresentation | Reads an existing presentation from stream with additional load options |
