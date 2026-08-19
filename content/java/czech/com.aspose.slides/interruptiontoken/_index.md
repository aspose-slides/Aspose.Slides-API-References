---
title: InterruptionToken
second_title: Aspose.Slides pro Java API Reference
description: Tato třída představuje token používaný k signalizaci dlouhých úkolů, zda bylo požádáno o přerušení.
type: docs
url: /cs/com.aspose.slides/interruptiontoken/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
```
public class InterruptionToken implements IInterruptionToken
```

Tato třída představuje token použivaný k signalizaci dlouhých úkolů, zda bylo požádáno o přerušení.
## Metody

| Metoda | Popis |
| --- | --- |
| [getNone()](#getNone--) | Představuje prázdný token přerušení. |
| [isInterruptionRequested()](#isInterruptionRequested--) | Vrací true, pokud bylo požádáno o přerušení. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Vyvolá výjimku, pokud bylo požádáno o přerušení. |
### getNone() {#getNone--}
```
public static InterruptionToken getNone()
```


Představuje prázdný token přerušení.

--------------------

Operace dlouho běžící se nikdy nepřeruší pomocí [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) při použití tohoto tokenu.

**Vrací:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```


Vrací true, pokud bylo požádáno o přerušení.

**Vrací:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public final void throwIfInterruptionRequested()
```


Vyvolá výjimku, pokud bylo požádáno o přerušení.