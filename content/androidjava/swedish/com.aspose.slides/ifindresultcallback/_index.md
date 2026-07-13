---
title: IFindResultCallback
second_title: Aspose.Slides för Android via Java API-referens
description: Callback-gränssnitt som används för att hämta sökresultatet för text.
type: docs
url: /sv/com.aspose.slides/ifindresultcallback/
---```
public interface IFindResultCallback
```

Callback-gränssnitt som används för att hämta sökresultatet för text.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)](#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-) | Callback-metod som tar emot data om den hittade texten. |
### foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition) {#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-}
```
public abstract void foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)
```

Callback-metod som tar emot data om den hittade texten.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Den [ITextFrame](../../com.aspose.slides/itextframe) där texten hittades. |
| sourceText | java.lang.String | Källtexten där texten hittades. |
| foundText | java.lang.String | Den hittade texten. |
| textPosition | int | Positionen för den hittade texten. |