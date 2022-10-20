---
title: Convert.GetOutPathCallback
second_title: Aspose.Slides for Java API Reference
description: 
type: docs
weight: 10
url: /java/com.aspose.slides/convert.getoutpathcallback/
---```
public static interface Convert.GetOutPathCallback
```
## Methods

| Method | Description |
| --- | --- |
| [invoke(Slide slide, int index)](#invoke-com.aspose.slides.Slide-int-) | Callback that will be invoked for each [Slide](../../com.aspose.slides/slide), the output path expected to be returned. |
### invoke(Slide slide, int index) {#invoke-com.aspose.slides.Slide-int-}
```
public abstract String invoke(Slide slide, int index)
```


Callback that will be invoked for each [Slide](../../com.aspose.slides/slide), the output path expected to be returned.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| slide | [Slide](../../com.aspose.slides/slide) | Current iterated slide |
| index | int | Index of the current slide |

**Returns:**
java.lang.String
