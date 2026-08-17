---
title: InterruptionToken
second_title: Справочник API Aspose.Slides для Java
description: Этот класс представляет токен, используемый для сигнализации длительным задачам о том, был ли запрошен прерывание.
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

Этот класс представляет токен, используемый для сигнализации длительным заданиям о том, был ли запрошен прерывание.
## Методы

| Метод | Описание |
| --- | --- |
| [getNone()](#getNone--) | Представляет пустой токен прерывания. |
| [isInterruptionRequested()](#isInterruptionRequested--) | Возвращает true, если прерывание было запрошено. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Выбрасывает исключение, если прерывание было запрошено. |
### getNone() {#getNone--}
```
public static InterruptionToken getNone()
```


Представляет пустой токен прерывания.

--------------------

Длительные операции никогда не будут прерваны через [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) при использовании этого токена.

**Возвращает:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```


Возвращает true, если прерывание было запрошено.

**Возвращает:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public final void throwIfInterruptionRequested()
```


Выбрасывает исключение, если прерывание было запрошено.