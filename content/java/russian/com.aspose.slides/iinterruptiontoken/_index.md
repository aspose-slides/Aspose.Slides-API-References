---
title: IInterruptionToken
second_title: Aspose.Slides для Java API Reference
description: Этот класс представляет токен, используемый для сигнализации длительным задачам, запросило ли прерывание.
type: docs
url: /ru/com.aspose.slides/iinterruptiontoken/
---```
public interface IInterruptionToken
```

Этот класс представляет токен, используемый для сигнализации длительным задачам, запросило ли прерывание.
## Методы

| Метод | Описание |
| --- | --- |
| [isInterruptionRequested()](#isInterruptionRequested--) | Возвращает true, если прерывание было запрошено. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Брасывает исключение, если прерывание было запрошено. |
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```

Возвращает true, если прерывание было запрошено.

**Возвращает:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public abstract void throwIfInterruptionRequested()
```

Брасывает исключение, если прерывание было запрошено.