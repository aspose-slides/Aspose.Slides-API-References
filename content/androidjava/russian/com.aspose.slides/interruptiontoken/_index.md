---
title: InterruptionToken
second_title: Aspose.Slides для Android через справку Java API
description: Этот класс представляет токен, используемый для сигнализации о длительных задачах, запросивших прерывание.
type: docs
url: /ru/com.aspose.slides/interruptiontoken/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
```
public class InterruptionToken implements IInterruptionToken
```

Этот класс представляет токен, используемый для сигнализации о длительных задачах, запросивших прерывание.
## Методы

| Метод | Описание |
| --- | --- |
| [getNone()](#getNone--) | Represents an empty interruption token. |
| [isInterruptionRequested()](#isInterruptionRequested--) | Returns true if interruption was requested. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Throws an if interruption was requested. |
### getNone() {#getNone--}
```
public static InterruptionToken getNone()
```

Представляет пустой токен прерывания.

--------------------

Длительные операции никогда не будут прерваны через [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) при использовании этого токена.

**Возвращаемое значение:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```

Возвращает true, если прерывание было запрошено.

**Возвращаемое значение:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public final void throwIfInterruptionRequested()
```

Выбрасывает исключение, если прерывание было запрошено.