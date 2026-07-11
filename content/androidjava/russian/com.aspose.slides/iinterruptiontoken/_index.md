---
title: IInterruptionToken
second_title: Aspose.Slides для Android через справочник API
description: Этот класс представляет токен, который используется для сигнализации долгосрочным задачам о том, запрошено ли прерывание.
type: docs
url: /ru/com.aspose.slides/iinterruptiontoken/
---```
public interface IInterruptionToken
```

Этот класс представляет токен, который используется для сигнализации долгосрочным задачам о том, запрошено ли прерывание.
## Методы

| Метод | Описание |
| --- | --- |
| [isInterruptionRequested()](#isInterruptionRequested--) | Возвращает true, если прерывание было запрошено. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Выбрасывает исключение, если прерывание было запрошено. |
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```

Возвращает true, если прерывание было запрошено.

**Возвращаемое:**  
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public abstract void throwIfInterruptionRequested()
```

Выбрасывает исключение, если прерывание было запрошено.