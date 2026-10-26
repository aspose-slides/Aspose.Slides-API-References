---
title: CellCircularReferenceException
second_title: Riferimento API Java di Aspose.Slides per Android
description: L'eccezione che viene generata quando una o più referenze circolari vengono rilevate, dove una formula fa riferimento alla propria cella direttamente o indirettamente.
type: docs
url: /it/com.aspose.slides/cellcircularreferenceexception/
---
**Ereditarietà:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellCircularReferenceException extends PptxEditException
```

L'eccezione che viene generata quando una o più referenze circolari vengono rilevate, dove una formula fa riferimento alla propria cella direttamente o indirettamente.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [CellCircularReferenceException()](#CellCircularReferenceException--) | Inizializza una nuova istanza della classe [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception). |
| [CellCircularReferenceException(String message)](#CellCircularReferenceException-java.lang.String-) | Inizializza una nuova istanza della classe [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) con un messaggio di errore specificato. |
| [CellCircularReferenceException(String message, RuntimeException innerException)](#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-) | Inizializza una nuova istanza della classe [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) con un messaggio di errore specificato e un riferimento all'eccezione interna che è la causa di questa eccezione. |
| [CellCircularReferenceException(String message, String reference)](#CellCircularReferenceException-java.lang.String-java.lang.String-) | Inizializza una nuova istanza della classe [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) con un messaggio di errore specificato e una referenza di cella circolare. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getReference()](#getReference--) | Restituisce una referenza di cella circolare. |
### CellCircularReferenceException() {#CellCircularReferenceException--}
```
public CellCircularReferenceException()
```


Inizializza una nuova istanza della classe [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception).

### CellCircularReferenceException(String message) {#CellCircularReferenceException-java.lang.String-}
```
public CellCircularReferenceException(String message)
```


Inizializza una nuova istanza della classe [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) con un messaggio di errore specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| message | java.lang.String | Una stringa che descrive l'errore. |

### CellCircularReferenceException(String message, RuntimeException innerException) {#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellCircularReferenceException(String message, RuntimeException innerException)
```


Inizializza una nuova istanza della classe [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) con un messaggio di errore specificato e un riferimento all'eccezione interna che è la causa di questa eccezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| message | java.lang.String | Una stringa che descrive l'errore. |
| innerException | java.lang.RuntimeException | L'eccezione che è la causa dell'eccezione corrente. |

### CellCircularReferenceException(String message, String reference) {#CellCircularReferenceException-java.lang.String-java.lang.String-}
```
public CellCircularReferenceException(String message, String reference)
```


Inizializza una nuova istanza della classe [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) con un messaggio di errore specificato e una referenza di cella circolare.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| message | java.lang.String | Una stringa che descrive l'errore. |
| reference | java.lang.String | Una referenza di cella circolare. |

### getReference() {#getReference--}
```
public final String getReference()
```


Restituisce una referenza di cella circolare.

**Restituisce:**
java.lang.String