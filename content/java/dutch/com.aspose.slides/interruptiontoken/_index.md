---
title: InterruptionToken
second_title: Aspose.Slides voor Java API-referentie
description: Deze klasse stelt de token voor die wordt gebruikt om lange lopende taken te signaleren of een onderbreking is aangevraagd.
type: docs
url: /nl/com.aspose.slides/interruptiontoken/
---
**Erfelijkheid:**  
java.lang.Object

**Alle geïmplementeerde interfaces:**  
[com.aspose.slides.IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)  
```
public class InterruptionToken implements IInterruptionToken
```

Deze klasse stelt de token voor die wordt gebruikt om lange lopende taken te signaleren of een onderbreking is aangevraagd.

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getNone()](#getNone--) | Stelt een lege onderbrekingstoken voor. |
| [isInterruptionRequested()](#isInterruptionRequested--) | Geeft true terug als onderbreking is aangevraagd. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Gooit een uitzondering als onderbreking is aangevraagd. |
### getNone() {#getNone--}
```
public static InterruptionToken getNone()
```

Stelt een lege onderbrekingstoken voor.

--------------------

Langdurige bewerkingen worden nooit onderbroken via [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) bij gebruik van deze token.

**Retour:**  
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```

Geeft true terug als onderbreking is aangevraagd.

**Retour:**  
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public final void throwIfInterruptionRequested()
```

Gooit een uitzondering als onderbreking is aangevraagd.