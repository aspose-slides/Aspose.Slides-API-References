---
title: IOverridableText
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta testo sovrascrivibile per un grafico.
type: docs
url: /it/com.aspose.slides/ioverridabletext/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IOverridableText extends IFormattedTextContainer
```

Rappresenta testo sovrascrivibile per un grafico.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Può contenere un testo formattato ricco. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Inizializza TextFrameForOverriding con il testo nel parametro "text". |
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public abstract ITextFrame getTextFrameForOverriding()
```

Può contenere un testo riccamente formattato. Se questa proprietà non è null, allora questo valore di testo formattato sovrascrive il testo generato automaticamente. Il testo generato automaticamente è una proprietà implicita dell'etichetta dati, dell'etichetta dell'unità di visualizzazione dell'asse dei valori, del titolo dell'asse, del titolo del grafico, dell'etichetta della linea di tendenza. Il testo generato automaticamente è formattato con la proprietà IFormattedTextContainer.TextFormat. Solo lettura [ITextFrame](../../com.aspose.slides/itextframe).

**Restituisce:**
[ITextFrame](../../com.aspose.slides/itextframe)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public abstract ITextFrame addTextFrameForOverriding(String text)
```

Inizializza TextFrameForOverriding con il testo nel parametro "text". Se TextFrameForOverriding è già inizializzato, cambia semplicemente il suo testo.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo per un nuovo TextFrameForOverriding. |

**Restituisce:**
[ITextFrame](../../com.aspose.slides/itextframe) - Frame di testo [ITextFrame](../../com.aspose.slides/itextframe)