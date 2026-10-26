---
title: IFindResultCallback
second_title: Aspose.Slides for Android via Java API Reference
description: Callback interface used to getting search text result.
type: docs
url: /de/com.aspose.slides/ifindresultcallback/
---```
public interface IFindResultCallback
```

Callback-Schnittstelle, die zum Abrufen von Suchergebnissen verwendet wird.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)](#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-) | Callback-Methode, die Daten zum gefundenen Text empfängt. |
### foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition) {#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-}
```
public abstract void foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)
```


Callback-Methode, die Daten zum gefundenen Text empfängt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Das [ITextFrame](../../com.aspose.slides/itextframe), in dem der Text gefunden wurde. |
| sourceText | java.lang.String | Der Quelltext, in dem der Text gefunden wurde. |
| foundText | java.lang.String | Der gefundene Text. |
| textPosition | int | Die Position des gefundenen Textes. |