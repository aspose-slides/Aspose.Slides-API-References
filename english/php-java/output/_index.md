---
title: Output
type: docs
weight: 0
url: /php-java/output/
---

# Output class

 Represents a collection of output elements for IWebDocument.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [add](/php-java/output/add/)(String, String, TContextObject) | IOutputFile | Adds an output element for the context object. |
| [add](/php-java/output/add/)(String, IPPImage) | IOutputFile | Adds an output element for the image. |
| [add](/php-java/output/add/)(String, BufferedImage) | IOutputFile | Adds an output element for the image. |
| [add](/php-java/output/add/)(String, IVideo) | IOutputFile | Adds an output element for the video. |
| [add](/php-java/output/add/)(String, IFontData, int) | IOutputFile | Adds an output element for the font. |
| [add](/php-java/output/add/)(String, String) | IOutputFile | Adds an output element for the text content. |
| [bindResource](/php-java/output/bindresource/)(IOutputFile, Object) | void | Binds resource to output file. |
| [getResourcePath](/php-java/output/getresourcepath/)(Object) | String | Returns the path for a given resource. |
