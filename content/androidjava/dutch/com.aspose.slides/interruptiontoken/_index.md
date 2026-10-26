---
title: InterruptionToken
second_title: Aspose.Slides voor Android via Java API-referentie
description: Deze klasse vertegenwoordigt het token dat gebruikt wordt om langdurige taken te signaleren of onderbreking is aangevraagd.
type: docs
url: /nl/com.aspose.slides/interruptiontoken/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
```
public class InterruptionToken implements IInterruptionToken
```

Deze klasse stelt het token voor dat gebruikt wordt om langdurige taken te signaleren of onderbreking is aangevraagd.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getNone()](#getNone--) | Stelt een leeg onderbrekingstoken voor. |
| [isInterruptionRequested()](#isInterruptionRequested--) | Retourneert true als onderbreking is aangevraagd. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Gooit een als onderbreking is aangevraagd. |
### getNone() {#getNone--}
```
public static InterruptionToken getNone()
```


Stelt een leeg onderbrekingstoken voor.

--------------------

Langdurige bewerkingen worden nooit onderbroken via [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) bij gebruik van dit token.

**Retourneert:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```


Retourneert true als onderbreking is aangevraagd.

**Retourneert:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public final void throwIfInterruptionRequested()
```


Gooit een als onderbreking is aangevraagd.