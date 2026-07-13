---
title: IOverridableText
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta il testo sovrascrivibile per un grafico.
type: docs
url: /it/com.aspose.slides/ioverridabletext/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IOverridableText extends IFormattedTextContainer
```

Rappresenta il testo sovrascrivibile per un grafico.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Può contenere un testo formattato ricco. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Inizializza TextFrameForOverriding con il testo nel paramener "text". |
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public abstract ITextFrame getTextFrameForOverriding()
```


Può contenere un testo formattato ricco. Se questa proprietà non è null, allora questo valore di testo formattato sovrascrive il testo generato automaticamente. Il testo generato automaticamente è una proprietà implicita dell’etichetta dati, dell’etichetta unità di visualizzazione dell’asse dei valori, del titolo dell’asse, del titolo del grafico, dell’etichetta della linea di tendenza. Il testo generato automaticamente è formattato con la proprietà IFormattedTextContainer.TextFormat. Sola lettura [ITextFrame](../../com.aspose.slides/itextframe).

**Restituisce:**
[ITextFrame](../../com.aspose.slides/itextframe)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public abstract ITextFrame addTextFrameForOverriding(String text)
```


Inizializza TextFrameForOverriding con il testo nel paramener "text". Se TextFrameForOverriding è già inizializzato, allora cambia semplicemente il suo testo.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo per un nuovo TextFrameForOverriding. |

**Restituisce:**
[ITextFrame](../../com.aspose.slides/itextframe) - Quadro di testo [ITextFrame](../../com.aspose.slides/itextframe)