---
title: IFindResultCallback
second_title: Aspose.Slides för Java API-referens
description: Callback-gränssnitt som används för att hämta söktextresultat.
type: docs
url: /sv/com.aspose.slides/ifindresultcallback/
---```
public interface IFindResultCallback
```

Callback-gränssnitt som används för att hämta söktextresultat.
## Metoder

| Method | Description |
| --- | --- |
| [foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)](#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-) | Callback-metod som tar emot data om den hittade texten. |
### foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition) {#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-}
```
public abstract void foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)
```

Callback-metod som tar emot data om den hittade texten.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Den [ITextFrame](../../com.aspose.slides/itextframe) i vilken texten hittades. |
| sourceText | java.lang.String | Källtexten i vilken texten hittades. |
| foundText | java.lang.String | Den hittade texten. |
| textPosition | int | Positionen för den hittade texten. |