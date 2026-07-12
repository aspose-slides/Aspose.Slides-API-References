---
title: InterruptionToken
second_title: Aspose.Slides Androidhoz a Java API hivatkozásán keresztül
description: Ez az osztály azt a tokent képviseli, amelyet a hosszú futású feladatok megszakítási kérésének jelzésére használnak.
type: docs
url: /hu/com.aspose.slides/interruptiontoken/
---
**Öröklődés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
```
public class InterruptionToken implements IInterruptionToken
```

Ez az osztály azt a tokent képviseli, amelyet a hosszú futású feladatok megszakítási kérése jelzésére használnak.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getNone()](#getNone--) | Egy üres megszakítási tokent képvisel. |
| [isInterruptionRequested()](#isInterruptionRequested--) | Igaz értéket ad vissza, ha a megszakítás kérés történt. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Kivételt dob, ha a megszakítás kérés történt. |
### getNone() {#getNone--}
```
public static InterruptionToken getNone()
```


Egy üres megszakítási tokent képvisel.

--------------------

A hosszú futású műveletek soha nem lesznek megszakítva a [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) használatával, ha ezt a tokent használják.

**Visszatér:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```


Igaz értéket ad vissza, ha a megszakítás kérés történt.

**Visszatér:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public final void throwIfInterruptionRequested()
```


Kivételt dob, ha a megszakítás kérés történt.