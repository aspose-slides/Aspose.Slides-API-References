---
title: IInterruptionTokenSource
second_title: Aspose.Slides for Android via Java API Reference
description: Represents the source of .
type: docs
url: /ru/com.aspose.slides/iinterruptiontokensource/
---```
public interface IInterruptionTokenSource
```

Представляет источник [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken).
## Методы

| Метод | Описание |
| --- | --- |
| [getToken()](#getToken--) | Возвращает новый токен, привязанный к этому [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource). |
| [isInterruptionRequested()](#isInterruptionRequested--) | Возвращает true, если запрошено прерывание, иначе false. |
| [interrupt()](#interrupt--) | Инициализировать запрос на прерывание. |
### getToken() {#getToken--}
```
public abstract IInterruptionToken getToken()
```

Возвращает новый токен, привязанный к этому [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Возвращает:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```

Возвращает true, если запрошено прерывание, иначе false.

**Возвращает:**
boolean
### interrupt() {#interrupt--}
```
public abstract void interrupt()
```

Инициализировать запрос на прерывание.