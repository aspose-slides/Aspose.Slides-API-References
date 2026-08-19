---
title: InterruptionToken
second_title: Aspose.Slides för Java API-referens
description: Denna klass representerar token som används för att signalera långa körningar om avbrott har begärts.
type: docs
url: /sv/com.aspose.slides/interruptiontoken/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
```
public class InterruptionToken implements IInterruptionToken
```

Denna klass representerar token som används för att signalera långa körningar om avbrott har begärts.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getNone()](#getNone--) | Representerar en tom avbrottstoken. |
| [isInterruptionRequested()](#isInterruptionRequested--) | Returnerar true om avbrott begärdes. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Kastar ett undantag om avbrott begärdes. |
### getNone() {#getNone--}
```
public static InterruptionToken getNone()
```

Representerar en tom avbrottstoken.

--------------------

Långvariga operationer kommer aldrig att avbrytas via [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) när den här token används.

**Returnerar:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```

Returnerar true om avbrott begärdes.

**Returnerar:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public final void throwIfInterruptionRequested()
```

Kastar ett undantag om avbrott begärdes.