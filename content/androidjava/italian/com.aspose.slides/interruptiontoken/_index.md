---
title: InterruptionToken
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Questa classe rappresenta il token da utilizzare per segnalare alle operazioni a lunga durata se l'interruzione è stata richiesta.
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

Questa classe rappresenta il token da utilizzare per segnalare alle operazioni a lunga durata se l'interruzione è stata richiesta.
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

Le operazioni a lunga durata non saranno mai interrotte tramite [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) quando si utilizza questo token.

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