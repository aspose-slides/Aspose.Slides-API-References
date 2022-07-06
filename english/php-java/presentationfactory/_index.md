---
title: PresentationFactory
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/presentationfactory/
---

## PresentationFactory class

 Allows to create presentation via COM interface
 

## Constructors

| Name | Description |
| --- | --- |
| [PresentationFactory](presentationfactory)() |  |

## Methods

| Name | Description |
| --- | --- |
| [createPresentation](createpresentation)() | Creates new presentation. |
| [createPresentation](createpresentation)([../LoadOptions]LoadOptions) | Creates new presentation with additional load options |
| [getInstance](getinstance)() | Presentation factory static instance. Read-only PresentationFactory. |
| [getPresentationInfo](getpresentationinfo)(String) | Creates new PresentationInfo object from file and binds presentation to it. |
| [getPresentationInfo](getpresentationinfo)(InputStream) | Creates new PresentationInfo object from stream and binds presentation to it. Gets info about presentation in specified stream. |
| [getPresentationText](getpresentationtext)(String, int) | Retrieves the raw text from the slides |
| [getPresentationText](getpresentationtext)(InputStream, int) | Retrieves the raw text from the slides |
| [getPresentationText](getpresentationtext)(InputStream, int, [../LoadOptions]LoadOptions) | Retrieves the raw text from the slides |
| [readPresentation](readpresentation)(byte[]) | Reads an existing presentation from array |
| [readPresentation](readpresentation)(byte[], [../LoadOptions]LoadOptions) | Reads an existing presentation from array with additional load options |
| [readPresentation](readpresentation)(InputStream) | Reads an existing presentation from stream |
| [readPresentation](readpresentation)(InputStream, [../LoadOptions]LoadOptions) | Reads an existing presentation from stream with additional load options |
| [readPresentation](readpresentation)(String) | Reads an existing presentation from file |
| [readPresentation](readpresentation)(String, [../LoadOptions]LoadOptions) | Reads an existing presentation from stream with additional load options |
