---
title: IInterruptionToken
second_title: Aspose.Slides for Android via Java API Reference
description: Cette classe représente le jeton à utiliser pour signaler aux tâches de longue durée si une interruption a été demandée.
type: docs
url: /fr/com.aspose.slides/iinterruptiontoken/
---```
public interface IInterruptionToken
```

Cette classe représente le jeton à utiliser pour signaler aux tâches de longue durée si une interruption a été demandée.
## Méthodes

| Méthode | Description |
| --- | --- |
| [isInterruptionRequested()](#isInterruptionRequested--) | Returns true if interruption was requested. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Throws an if interruption was requested. |
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```

Renvoie true si une interruption a été demandée.

**Renvoie:**  
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public abstract void throwIfInterruptionRequested()
```

Lance une exception si une interruption a été demandée.