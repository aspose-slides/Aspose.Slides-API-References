---
title: IFindResultCallback
second_title: Aspose.Slides dla Androida – odniesienie API Java
description: Interfejs wywołania zwrotnego służący do uzyskiwania wyników wyszukiwania tekstu.
type: docs
url: /pl/com.aspose.slides/ifindresultcallback/
---```
public interface IFindResultCallback
```

Interfejs wywołania zwrotnego służący do uzyskiwania wyników wyszukiwania tekstu.
## Methods

| Metoda | Opis |
| --- | --- |
| [foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)](#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-) | Metoda wywołania zwrotnego, która otrzymuje dane o znalezionym tekście. |
### foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition) {#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-}
```
public abstract void foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)
```

Metoda wywołania zwrotnego, która otrzymuje dane o znalezionym tekście.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | [ITextFrame](../../com.aspose.slides/itextframe) w którym znaleziono tekst. |
| sourceText | java.lang.String | Tekst źródłowy, w którym znaleziono tekst. |
| foundText | java.lang.String | Znaleziony tekst. |
| textPosition | int | Pozycja znalezionego tekstu. |