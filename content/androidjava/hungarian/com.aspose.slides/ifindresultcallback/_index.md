---
title: IFindResultCallback
second_title: Aspose.Slides for Android via Java API Reference
description: Callback interface used to getting search text result.
type: docs
url: /hu/com.aspose.slides/ifindresultcallback/
---```
public interface IFindResultCallback
```

Visszahívási interfész a keresési szövegeredmény lekéréséhez használt.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)](#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-) | Visszahívási metódus, amely a megtalált szövegről szóló adatokat kapja. |
### foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition) {#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-}
```
public abstract void foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)
```


Visszahívási metódus, amely a megtalált szövegről szóló adatokat kapja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | [ITextFrame](../../com.aspose.slides/itextframe) amelyben a szöveget megtalálták. |
| sourceText | java.lang.String | A forrás szöveg, amelyben a szöveget megtalálták. |
| foundText | java.lang.String | A megtalált szöveg. |
| textPosition | int | A megtalált szöveg pozíciója. |