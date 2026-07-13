---
title: CellInvalidReferenceException
second_title: Riferimento API Java di Aspose.Slides per Android
description: L'eccezione che viene lanciata quando viene incontrato un riferimento di cella non valido.
type: docs
url: /it/com.aspose.slides/cellinvalidreferenceexception/
---
**Eredità:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidReferenceException extends PptxEditException
```

L'eccezione che viene lanciata quando viene incontrato un riferimento di cella non valido.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [CellInvalidReferenceException()](#CellInvalidReferenceException--) | Inizializza una nuova istanza della classe [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception). |
| [CellInvalidReferenceException(String message)](#CellInvalidReferenceException-java.lang.String-) | Inizializza una nuova istanza della classe [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) con un messaggio di errore specificato. |
| [CellInvalidReferenceException(String message, RuntimeException innerException)](#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-) | Inizializza una nuova istanza della classe [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) con un messaggio di errore specificato e un riferimento all'eccezione interna che è la causa di questa eccezione. |
| [CellInvalidReferenceException(String message, String reference)](#CellInvalidReferenceException-java.lang.String-java.lang.String-) | Inizializza una nuova istanza della classe [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) con un messaggio di errore specificato e un riferimento di cella non valido. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getReference()](#getReference--) | Restituisce un riferimento di cella non valido. |
### CellInvalidReferenceException() {#CellInvalidReferenceException--}
```
public CellInvalidReferenceException()
```


Inizializza una nuova istanza della classe [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception).

### CellInvalidReferenceException(String message) {#CellInvalidReferenceException-java.lang.String-}
```
public CellInvalidReferenceException(String message)
```


Inizializza una nuova istanza della classe [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) con un messaggio di errore specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| message | java.lang.String | Una stringa che descrive l'errore. |

### CellInvalidReferenceException(String message, RuntimeException innerException) {#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidReferenceException(String message, RuntimeException innerException)
```


Inizializza una nuova istanza della classe [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) con un messaggio di errore specificato e un riferimento all'eccezione interna che è la causa di questa eccezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| message | java.lang.String | Una stringa che descrive l'errore. |
| innerException | java.lang.RuntimeException | L'eccezione che è la causa dell'eccezione corrente. |

### CellInvalidReferenceException(String message, String reference) {#CellInvalidReferenceException-java.lang.String-java.lang.String-}
```
public CellInvalidReferenceException(String message, String reference)
```


Inizializza una nuova istanza della classe [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) con un messaggio di errore specificato e un riferimento di cella non valido.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| message | java.lang.String | Una stringa che descrive l'errore. |
| reference | java.lang.String | Un riferimento di cella non valido. |

### getReference() {#getReference--}
```
public final String getReference()
```


Restituisce un riferimento di cella non valido.

**Restituisce:**
java.lang.String