---
title: InterruptionToken
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Tato třída představuje token, který se používá k signalizaci dlouhodobých úloh, zda bylo požádáno o přerušení.
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

Tato třída představuje token, který se používá k signalizaci dlouhodobých úloh, zda bylo požádáno o přerušení.
## Metody

| Method | Description |
| --- | --- |
| [getNone()](#getNone--) | Představuje prázdný token přerušení. |
| [isInterruptionRequested()](#isInterruptionRequested--) | Vrací true, pokud bylo požádáno o přerušení. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Vyhodí výjimku, pokud bylo požádáno o přerušení. |
### getNone() {#getNone--}
```
public static InterruptionToken getNone()
```

Představuje prázdný token přerušení.

--------------------

Operace s dlouhým běhovým časem nebudou nikdy přerušeny pomocí [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt), pokud se používá tento token.

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

Vyhodí výjimku, pokud bylo požádáno o přerušení.