---
title: IFindResultCallback
second_title: Aspose.Slides for Android via Java API Reference
description: Callback interface used to getting search text result.
type: docs
url: /com.aspose.slides/ifindresultcallback/
---```
public interface IFindResultCallback
```

Callback interface used to getting search text result.
## Methods

| Method | Description |
| --- | --- |
| [foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)](#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-) | Callback method that receives data about the found text. |
### foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition) {#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-}
```
public abstract void foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)
```


Callback method that receives data about the found text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | The [ITextFrame](../../com.aspose.slides/itextframe) in which the text was found. |
| sourceText | java.lang.String | The source text in which the text was found. |
| foundText | java.lang.String | The found text. |
| textPosition | int | The position of the found text. |

