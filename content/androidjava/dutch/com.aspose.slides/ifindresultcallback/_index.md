---
title: IFindResultCallback
second_title: Aspose.Slides for Android via Java API Reference
description: Callback interface die wordt gebruikt om zoektekstresultaten te verkrijgen.
type: docs
url: /nl/com.aspose.slides/ifindresultcallback/
---```
public interface IFindResultCallback
```

Callback interface die wordt gebruikt om zoektekstresultaten te verkrijgen.

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)](#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-) | Callback-methode die gegevens over de gevonden tekst ontvangt. |
### foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition) {#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-}
```
public abstract void foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)
```

Callback-methode die gegevens over de gevonden tekst ontvangt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | De [ITextFrame](../../com.aspose.slides/itextframe) waarin de tekst werd gevonden. |
| sourceText | java.lang.String | De brontekst waarin de tekst werd gevonden. |
| foundText | java.lang.String | De gevonden tekst. |
| textPosition | int | De positie van de gevonden tekst. |