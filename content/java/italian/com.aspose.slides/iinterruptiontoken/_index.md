---
title: IInterruptionToken
second_title: Aspose.Slides for Java API Reference
description: This class represents the token to use for signaling long running tasks whether the interruption was requested.
type: docs
url: /it/com.aspose.slides/iinterruptiontoken/
---```
public interface IInterruptionToken
```

Questa classe rappresenta il token da utilizzare per segnalare alle attività a lungo termine se è stata richiesta l'interruzione.
## Metodi

| Method | Descrizione |
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