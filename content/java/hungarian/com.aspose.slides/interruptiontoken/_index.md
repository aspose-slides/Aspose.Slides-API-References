---
title: InterruptionToken
second_title: Aspose.Slides Java API referencia
description: Ez az osztály azt a tokent jelenti, amelyet a hosszú ideig futó feladatok megszakítási kérésének jelzésére használnak.
type: docs
url: /hu/com.aspose.slides/interruptiontoken/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
```
public class InterruptionToken implements IInterruptionToken
```

Ez az osztály azt a tokent jelenti, amelyet a hosszú ideig futó feladatok megszakítási kérésének jelzésére használnak.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getNone()](#getNone--) | Üres megszakítási tokent képvisel. |
| [isInterruptionRequested()](#isInterruptionRequested--) | Igaz értéket ad vissza, ha a megszakítás kérése történt. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Kivételt dob, ha a megszakítás kérése történt. |
### getNone() {#getNone--}
```
public static InterruptionToken getNone()
```


Üres megszakítási tokent képvisel.

--------------------

A hosszú ideig futó műveletek soha nem lesznek megszakítva a [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) használatával, amikor ezt a tokent használják.

**Visszatérési érték:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```


Igaz értéket ad vissza, ha a megszakítás kérése történt.

**Visszatérési érték:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public final void throwIfInterruptionRequested()
```


Kivételt dob, ha a megszakítás kérése történt.