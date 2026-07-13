---
title: InterruptionToken
second_title: Aspose.Slides dla Androida – odwołanie do API Java
description: Ta klasa reprezentuje token używany do sygnalizowania długotrwałych zadań, czy żądane zostało przerwanie.
type: docs
url: /pl/com.aspose.slides/interruptiontoken/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
```
public class InterruptionToken implements IInterruptionToken
```

Ta klasa reprezentuje token używany do sygnalizowania długotrwałych zadań, czy żądane zostało przerwanie.
## Metody

| Metoda | Opis |
| --- | --- |
| [getNone()](#getNone--) | Reprezentuje pusty token przerwania. |
| [isInterruptionRequested()](#isInterruptionRequested--) | Zwraca true, jeśli żądane zostało przerwanie. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Rzuca an, jeśli żądane zostało przerwanie. |
### getNone() {#getNone--}
```
public static InterruptionToken getNone()
```


Reprezentuje pusty token przerwania.

--------------------

Operacje długotrwałe nigdy nie zostaną przerwane za pośrednictwem [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) przy użyciu tego tokena.

**Zwraca:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```


Zwraca true, jeśli żądane zostało przerwanie.

**Zwraca:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public final void throwIfInterruptionRequested()
```


Rzuca an, jeśli żądane zostało przerwanie.