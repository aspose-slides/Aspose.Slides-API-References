---
title: IFindResultCallback
second_title: Aspose.Slides for Java API Reference
description: Visszahívási interfész, amely a keresési szöveg eredményének lekérésére szolgál.
type: docs
url: /hu/com.aspose.slides/ifindresultcallback/
---```
public interface IFindResultCallback
```

Visszahívási interfész, amely a keresési szöveg eredményének lekérésére szolgál.
## Módszerek

| Method | Description |
| --- | --- |
| [foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)](#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-) | Visszahívási módszer, amely a megtalált szövegről szóló adatokat kapja. |
### foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition) {#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-}
```
public abstract void foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)
```


Visszahívási módszer, amely a megtalált szövegről szóló adatokat kapja.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | A [ITextFrame](../../com.aspose.slides/itextframe), amelyben a szöveg megtalálható. |
| sourceText | java.lang.String | A forrás szöveg, amelyben a szöveg megtalálható. |
| foundText | java.lang.String | A megtalált szöveg. |
| textPosition | int | A megtalált szöveg pozíciója. |