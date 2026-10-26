---
title: InterruptionToken
second_title: Aspose.Slides für Java API-Referenz
description: Diese Klasse repräsentiert das Token, das verwendet wird, um langlaufende Aufgaben darüber zu informieren, ob eine Unterbrechung angefordert wurde.
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

Diese Klasse repräsentiert das Token, das verwendet wird, um langlaufende Vorgänge darüber zu informieren, ob eine Unterbrechung angefordert wurde.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getNone()](#getNone--) | Repräsentiert ein leeres Unterbrechungstoken. |
| [isInterruptionRequested()](#isInterruptionRequested--) | Gibt true zurück, wenn eine Unterbrechung angefordert wurde. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Wirft eine, wenn eine Unterbrechung angefordert wurde. |
### getNone() {#getNone--}
```
public static InterruptionToken getNone()
```

Repräsentiert ein leeres Unterbrechungstoken.

--------------------

Langlaufende Vorgänge werden nie über [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) unterbrochen, wenn dieses Token verwendet wird.

**Rückgabewert:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```

Gibt true zurück, wenn eine Unterbrechung angefordert wurde.

**Rückgabewert:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public final void throwIfInterruptionRequested()
```

Wirft eine, wenn eine Unterbrechung angefordert wurde.