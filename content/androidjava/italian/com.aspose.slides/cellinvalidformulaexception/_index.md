---
title: CellInvalidFormulaException
second_title: Riferimento API Java di Aspose.Slides per Android
description: L'eccezione che viene sollevata quando una formula calcolata non è corretta o non è stata analizzata.
type: docs
url: /it/com.aspose.slides/cellinvalidformulaexception/
---
**Eredità:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidFormulaException extends PptxEditException
```

L'eccezione che viene sollevata quando una formula calcolata non è corretta o non è stata analizzata.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [CellInvalidFormulaException()](#CellInvalidFormulaException--) | Inizializza una nuova istanza della classe [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception). |
| [CellInvalidFormulaException(String message)](#CellInvalidFormulaException-java.lang.String-) | Inizializza una nuova istanza della classe [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) con un messaggio di errore specificato. |
| [CellInvalidFormulaException(String message, RuntimeException innerException)](#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-) | Inizializza una nuova istanza della classe [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) con un messaggio di errore specificato e un riferimento all'eccezione interna che è la causa di questa eccezione. |
| [CellInvalidFormulaException(String message, String reference)](#CellInvalidFormulaException-java.lang.String-java.lang.String-) | Inizializza una nuova istanza della classe [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) con un messaggio di errore specificato e un riferimento di cella che contiene la formula non valida. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getReference()](#getReference--) | Restituisce un riferimento di cella che contiene la formula non valida. |
### CellInvalidFormulaException() {#CellInvalidFormulaException--}
```
public CellInvalidFormulaException()
```

Inizializza una nuova istanza della classe [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception).

### CellInvalidFormulaException(String message) {#CellInvalidFormulaException-java.lang.String-}
```
public CellInvalidFormulaException(String message)
```

Inizializza una nuova istanza della classe [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) con un messaggio di errore specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| message | java.lang.String | Una stringa che descrive l'errore. |

### CellInvalidFormulaException(String message, RuntimeException innerException) {#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidFormulaException(String message, RuntimeException innerException)
```

Inizializza una nuova istanza della classe [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) con un messaggio di errore specificato e un riferimento all'eccezione interna che è la causa di questa eccezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| message | java.lang.String | Una stringa che descrive l'errore. |
| innerException | java.lang.RuntimeException | L'eccezione che è la causa dell'eccezione corrente. |

### CellInvalidFormulaException(String message, String reference) {#CellInvalidFormulaException-java.lang.String-java.lang.String-}
```
public CellInvalidFormulaException(String message, String reference)
```

Inizializza una nuova istanza della classe [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) con un messaggio di errore specificato e un riferimento di cella che contiene la formula non valida.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| message | java.lang.String | Una stringa che descrive l'errore. |
| reference | java.lang.String | Una stringa che descrive un riferimento all'eccezione interna |

### getReference() {#getReference--}
```
public final String getReference()
```

Restituisce un riferimento di cella che contiene la formula non valida.

**Restituisce:**
java.lang.String