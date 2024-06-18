---
title: IFindResultCallback
second_title: Aspose.Slides for Java API Reference
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
| [foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)](#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-) | Callback method which receives data about found text. |
### foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition) {#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-}
```
public abstract void foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)
```


Callback method which receives data about found text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | [ITextFrame](../../com.aspose.slides/itextframe) where serching text was found. |
| sourceText | java.lang.String | Source text of TextFrame where text was found. |
| foundText | java.lang.String | Found text. |
| textPosition | int | Position of found text in source text. |

