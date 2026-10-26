---
title: IInterruptionTokenSource
second_title: Aspose.Slides for Java API Reference
description: Rappresenta la sorgente di .
type: docs
url: /it/com.aspose.slides/iinterruptiontokensource/
---```
public interface IInterruptionTokenSource
```

Rappresenta la sorgente di [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken).
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getToken()](#getToken--) | Restituisce un nuovo token associato a questo [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource). |
| [isInterruptionRequested()](#isInterruptionRequested--) | Restituisce true se è stata richiesta l'interruzione, false altrimenti. |
| [interrupt()](#interrupt--) | Inizializza la richiesta di interruzione. |
### getToken() {#getToken--}
```
public abstract IInterruptionToken getToken()
```


Restituisce un nuovo token associato a questo [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Restituisce:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```


Restituisce true se è stata richiesta l'interruzione, false altrimenti.

**Restituisce:**
boolean
### interrupt() {#interrupt--}
```
public abstract void interrupt()
```


Inizializza la richiesta di interruzione.