---
title: InterruptionToken
second_title: Riferimento API di Aspose.Slides per Java
description: Questa classe rappresenta il token da utilizzare per segnalare alle attività a lunga esecuzione se è stata richiesta l'interruzione.
type: docs
url: /it/com.aspose.slides/interruptiontoken/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
```
public class InterruptionToken implements IInterruptionToken
```

Questa classe rappresenta il token da utilizzare per segnalare alle attività a lunga esecuzione se è stata richiesta l'interruzione.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getNone()](#getNone--) | Rappresenta un token di interruzione vuoto. |
| [isInterruptionRequested()](#isInterruptionRequested--) | Restituisce true se è stata richiesta l'interruzione. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Lancia un'eccezione se è stata richiesta l'interruzione. |
### getNone() {#getNone--}
```
public static InterruptionToken getNone()
```

Rappresenta un token di interruzione vuoto.

--------------------

Le operazioni a lunga esecuzione non verranno mai interrotte tramite [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) quando si utilizza questo token.

**Restituisce:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```

Restituisce true se è stata richiesta l'interruzione.

**Restituisce:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public final void throwIfInterruptionRequested()
```

Lancia un'eccezione se è stata richiesta l'interruzione.