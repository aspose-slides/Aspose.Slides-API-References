---
title: IFindResultCallback
second_title: Riferimento API Java di Aspose.Slides per Android
description: Interfaccia di callback utilizzata per ottenere il risultato della ricerca di testo.
type: docs
url: /it/com.aspose.slides/ifindresultcallback/
---```
public interface IFindResultCallback
```

Interfaccia di callback utilizzata per ottenere il risultato della ricerca di testo.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)](#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-) | Metodo di callback che riceve i dati sul testo trovato. |
### foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition) {#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-}
```
public abstract void foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)
```

Metodo di callback che riceve i dati sul testo trovato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Il [ITextFrame](../../com.aspose.slides/itextframe) in cui è stato trovato il testo. |
| sourceText | java.lang.String | Il testo sorgente in cui è stato trovato il testo. |
| foundText | java.lang.String | Il testo trovato. |
| textPosition | int | La posizione del testo trovato. |