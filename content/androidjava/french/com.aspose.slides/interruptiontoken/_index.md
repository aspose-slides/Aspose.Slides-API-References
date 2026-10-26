---
title: InterruptionToken
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Cette classe représente le jeton à utiliser pour signaler aux tâches de longue durée si une interruption a été demandée.
type: docs
url: /fr/com.aspose.slides/interruptiontoken/
---
**Héritage:**  
java.lang.Object

**Toutes les interfaces implémentées:**  
[com.aspose.slides.IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)  
```
public class InterruptionToken implements IInterruptionToken
```

Cette classe représente le jeton à utiliser pour signaler aux tâches de longue durée si une interruption a été demandée.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getNone()](#getNone--) | Représente un jeton d'interruption vide. |
| [isInterruptionRequested()](#isInterruptionRequested--) | Renvoie vrai si une interruption a été demandée. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Lance une exception si une interruption a été demandée. |

### getNone() {#getNone--}
```
public static InterruptionToken getNone()
```

Représente un jeton d'interruption vide.

--------------------

Les opérations de longue durée ne seront jamais interrompues via [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) lors de l'utilisation de ce jeton.

**Renvoie:**  
[InterruptionToken](../../com.aspose.slides/interruptiontoken)

### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```

Renvoie vrai si une interruption a été demandée.

**Renvoie:**  
boolean

### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public final void throwIfInterruptionRequested()
```

Lance une exception si une interruption a été demandée.