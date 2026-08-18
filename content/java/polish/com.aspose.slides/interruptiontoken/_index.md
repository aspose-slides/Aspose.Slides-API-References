---
title: InterruptionToken
second_title: Aspose.Slides dla odniesienia API Java
description: Ta klasa reprezentuje token używany do sygnalizowania długotrwałych zadań, czy przerwanie zostało zgłoszone.
type: docs
url: /pl/com.aspose.slides/interruptiontoken/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie implementowane interfejsy:**
[com.aspose.slides.IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
```
public class InterruptionToken implements IInterruptionToken
```

Ta klasa reprezentuje token używany do sygnalizowania długotrwałych zadań, czy przerwanie zostało zgłoszone.
## Metody

| Method | Description |
| --- | --- |
| [getNone()](#getNone--) | Reprezentuje pusty token przerwania. |
| [isInterruptionRequested()](#isInterruptionRequested--) | Zwraca true, jeśli przerwanie zostało zgłoszone. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Rzuca wyjątek, jeśli przerwanie zostało zgłoszone. |
### getNone() {#getNone--}
```
public static InterruptionToken getNone()
```


Reprezentuje pusty token przerwania.

--------------------

Operacje długotrwałe nigdy nie będą przerywane przez [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) przy użyciu tego tokenu.

**Zwraca:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```


Zwraca true, jeśli przerwanie zostało zgłoszone.

**Zwraca:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public final void throwIfInterruptionRequested()
```


Rzuca wyjątek, jeśli przerwanie zostało zgłoszone.