---
title: InterruptionToken
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Diese Klasse repräsentiert das Token, das zur Signalisierung lang laufender Aufgaben verwendet wird, um anzuzeigen, ob die Unterbrechung angefordert wurde.
type: docs
url: /de/com.aspose.slides/interruptiontoken/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
```
public class InterruptionToken implements IInterruptionToken
```

Diese Klasse repräsentiert das Token, das für die Signalisierung lang laufender Aufgaben verwendet wird, um anzuzeigen, ob die Unterbrechung angefordert wurde.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getNone()](#getNone--) | Stellt ein leeres Unterbrechungs-Token dar. |
| [isInterruptionRequested()](#isInterruptionRequested--) | Gibt true zurück, wenn die Unterbrechung angefordert wurde. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Wirft eine, wenn die Unterbrechung angefordert wurde. |
### getNone() {#getNone--}
```
public static InterruptionToken getNone()
```


Stellt ein leeres Unterbrechungs-Token dar.

--------------------

Langlaufende Vorgänge werden bei Verwendung dieses Tokens niemals über [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) unterbrochen.

**Rückgabewert:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```


Gibt true zurück, wenn die Unterbrechung angefordert wurde.

**Rückgabewert:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public final void throwIfInterruptionRequested()
```


Wirft eine, wenn die Unterbrechung angefordert wurde.