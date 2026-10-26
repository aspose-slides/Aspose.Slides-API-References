---
title: InterruptionToken
second_title: Aspose.Slides för Android via Java API-referens
description: Denna klass representerar token som används för att signalera långa uppgifter om avbrott har begärts.
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

Denna klass representerar token som används för att signalera långa uppgifter om avbrott har begärts.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getNone()](#getNone--) | Representerar en tom avbrottstoken. |
| [isInterruptionRequested()](#isInterruptionRequested--) | Returnerar true om avbrott har begärts. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Kastar ett undantag om avbrott har begärts. |
### getNone() {#getNone--}
```
public static InterruptionToken getNone()
```


Representerar en tom avbrottstoken.

--------------------

Långvariga operationer avbryts aldrig via [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) när denna token används.

**Returnerar:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```


Returnerar true om avbrott har begärts.

**Returnerar:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public final void throwIfInterruptionRequested()
```


Kastar ett undantag om avbrott har begärts.