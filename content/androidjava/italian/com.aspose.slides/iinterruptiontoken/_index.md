---
title: IInterruptionToken
second_title: Aspose.Slides for Android via Riferimento API Java
description: Questa classe rappresenta il token da utilizzare per segnalare ai processi a lunga esecuzione se è stata richiesta l'interruzione.
type: docs
url: /it/com.aspose.slides/iinterruptiontoken/
---```
public interface IInterruptionToken
```

Questa classe rappresenta il token da utilizzare per segnalare ai processi a lunga esecuzione se è stata richiesta l'interruzione.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isInterruptionRequested()](#isInterruptionRequested--) | Restituisce true se è stata richiesta l'interruzione. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Lancia un'eccezione se è stata richiesta l'interruzione. |
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```


Restituisce true se è stata richiesta l'interruzione.

**Restituisce:**  
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public abstract void throwIfInterruptionRequested()
```


Lancia un'eccezione se è stata richiesta l'interruzione.